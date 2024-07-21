### Class 17: Background Image All Properties

**Content:**

- Practice with all background properties

**Assignment Questions:**

1. Create a webpage with a full-page background image.
2. How do you add a background gradient to an element?
3. How do you set the background image to be centered both horizontally and vertically?
4. How do you use the `background-origin` property?
5. How do you apply a background image to only the content area of an element?

**Coding Questions and Examples:**

1. **Create a webpage with a full-page background image.**

   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Full Page Background Image</title>
       <style>
         body {
           background-image: url("path/to/your/image.jpg");
           background-size: cover;
           background-position: center;
           background-repeat: no-repeat;
           height: 100vh;
           margin: 0;
         }
       </style>
     </head>
     <body></body>
   </html>
   ```

2 .**_Add a background gradient to an element._**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Background Gradient</title>
    <style>
      .gradient-background {
        height: 100vh;
        background: linear-gradient(to right, #ff7e5f, #feb47b);
      }
    </style>
  </head>
  <body>
    <div class="gradient-background"></div>
  </body>
</html>
```

3. Set the background image to be centered both horizontally and vertically.
1. ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Centered Background Image</title>
       <style>
         .centered-background {
           height: 100vh;
           background-image: url("path/to/your/image.jpg");
           background-size: cover;
           background-position: center;
           background-repeat: no-repeat;
         }
       </style>
     </head>
     <body>
       <div class="centered-background"></div>
     </body>
   </html>
   ```

4.Use the background-origin property.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Background Origin</title>
    <style>
      .background-origin {
        width: 200px;
        height: 200px;
        border: 10px solid black;
        background-image: url("path/to/your/image.jpg");
        background-origin: content-box;
        background-repeat: no-repeat;
        background-size: cover;
      }
    </style>
  </head>
  <body>
    <div class="background-origin"></div>
  </body>
</html>
```
