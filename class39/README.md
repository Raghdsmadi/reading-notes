# Reading: class 39 REACT NEXT JS

> [Back to  main](./README.md)
> 

****************************************
## Assets
- Next.js can serve static assets, like images, under the top-level public directory. Files inside public can be referenced from the root of the application similar to pages.<br>

- The public directory is also useful for robots.txt, Google Site Verification, and any other static assets. Check out the documentation for Static File Serving to learn more.

***************************************
## Download Your Profile Picture
- First, let's retrieve your profile picture.

- Download your profile picture in .jpg format (or use this file).<br>
- Create an images directory inside of the public directory.<br>
- Save the picture as profile.jpg in the public/images directory.<br>
- The image size can be around 400px by 400px.<br>
**You may remove the unused SVG logo file directly under the public directory.**

******************************************
## CSS Styling

- CSS modules allow you to locally scope CSS at the component-level by automatically creating unique class names. This allows you to use the same CSS class name in different files without worrying about class name collisions.
<br>
- In addition to CSS modules, you can style your Next.js application in a variety of ways, including:
<br>
- Sass which allows you to import .css and .scss files.<br>
- PostCSS libraries like Tailwind CSS.<br>
CSS-in-JS libraries such as styled-jsx, styled-components, and emotion