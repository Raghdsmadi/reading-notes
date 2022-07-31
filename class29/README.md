# Reading: class28 Django CRUD and forms

> [Back to  main](./README.md)
---------------------------
## Custom User Model
Creating our initial custom user model requires four steps:

update django_project/settings.py
create a new CustomUser model
create new UserCreation and UserChangeForm
update the admin
In settings.py we'll add the accounts app and use the AUTH_USER_MODEL config to tell Django to use our new custom user model in place of the built-in User model. We'll call our custom user model CustomUser.

Within INSTALLED_APPS add accounts at the bottom. Then at the bottom of the entire file, add the AUTH_USER_MODEL config.


************************************************************
## Superuser
It's helpful to create a superuser that we can use to log in to the admin and test out log in/log out. On the command line type the following command and go through the prompts.

************************************************************
## Conclusion
Now that our custom user model is configured you can easily and at any time add additional fields to it. See the Django docs for further instructions.

You can also check out DjangoX, which is an open-source Django starter framework that includes a custom user model, email/password by default instead of username/email/password, social authentication, and more.

And if you'd like an even more in-depth example of starting a new Django project check out the book Django for Beginners.