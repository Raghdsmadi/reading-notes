# Reading: class27 Django Models

> [Back to  main](./README.md)
---------------------------

## what is model in Django ?

Django web applications access and manage data through Python objects referred to as models. Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc. 
The definition of the model is independent of the underlying database — you can choose one of several as part of your project settings. 
Once you've chosen what database you want to use, you don't need to talk to it directly at all — you just write your model structure and other code,
and Django handles all the dirty work of communicating with the database for you.

*************************************************
### overview 
A Django model is a table in your database.
***Model definition***:
Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata.

***Fields***
A model can have an arbitrary number of fields, of any type — each one represents a column of data that we want to store in one of our database tables. Each database record (row) will consist of one of each field value.


***Metadata***
You can declare model-level metadata for your Model by declaring class Meta
