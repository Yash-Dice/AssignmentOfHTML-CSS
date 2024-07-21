### Class 19: Position Properties

**Content:**

- Position fixed and relative, absolute and sticky, top, bottom, right, left properties, and z-index

**Assignment Questions:**

1. Explain the differences between static, relative, absolute, fixed, and sticky positioning.
2. How do you position an element relative to its parent using CSS?
3. How do you create a fixed navigation bar at the top of the page?
4. How do you use the `z-index` property to layer elements?
5. How do you position an element at the bottom right corner of the page?
6. How do you create an element that sticks to the top of the page when scrolling?
7. How do you center an element both horizontally and vertically using absolute positioning?
8. How do you use relative positioning to offset an element from its normal position?
9. How do you make an element position relative to the viewport?
10. How do you troubleshoot overlapping elements using `z-index`?

**Coding Questions and Examples:**

1. **Create a fixed navigation bar at the top of the page.**

   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Fixed Navbar</title>
       <style>
         body {
           margin: 0;
           font-family: Arial, sans-serif;
         }
         .navbar {
           position: fixed;
           top: 0;
           width: 100%;
           background-color: #333;
           color: white;
           padding: 15px;
           text-align: center;
         }
         .content {
           margin-top: 60px;
           padding: 20px;
         }
       </style>
     </head>
     <body>
       <div class="navbar">Fixed Navbar</div>
       <div class="content">
         <p>Scroll down to see the fixed navbar in action.</p>
         <p>
           Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam
           tincidunt arcu vel arcu vehicula, at venenatis nulla tincidunt.
           Phasellus malesuada tortor nec nibh vehicula, sit amet fermentum
           velit laoreet.
         </p>
       </div>
     </body>
   </html>
   ```

   2**_Position an element at the bottom right corner of the page._**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bottom Right Position</title>
    <style>
      .bottom-right {
        position: absolute;
        bottom: 10px;
        right: 10px;
        background-color: #333;
        color: white;
        padding: 10px;
      }
    </style>
  </head>
  <body>
    <div class="bottom-right">Positioned at Bottom Right</div>
  </body>
</html>
```

3.**_Create an element that sticks to the top of the page when scrolling._**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sticky Element</title>
    <style>
      body {
        margin: 0;
        font-family: Arial, sans-serif;
      }
      .sticky {
        position: -webkit-sticky; /* Safari */
        position: sticky;
        top: 0;
        background-color: #333;
        color: white;
        padding: 15px;
        text-align: center;
      }
      .content {
        padding: 20px;
        height: 2000px; /* Just for demonstration */
      }
    </style>
  </head>
  <body>
    <div class="sticky">Sticky Element</div>
    <div class="content">
      <p>Scroll down to see the sticky element in action.</p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam
        tincidunt arcu vel arcu vehicula, at venenatis nulla tincidunt.
        Phasellus malesuada tortor nec nibh vehicula, sit amet fermentum velit
        laoreet.
      </p>
    </div>
  </body>
</html>
```

4. **_Center an element both horizontally and vertically using absolute positioning._**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Center Position</title>
    <style>
      .center {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: #333;
        color: white;
        padding: 20px;
        text-align: center;
      }
      body {
        height: 100vh;
        margin: 0;
        display: flex;
        justify-content: center;
        align-items: center;
      }
    </style>
  </head>
  <body>
    <div class="center">Centered Element</div>
  </body>
</html>
```

5. Use relative positioning to offset an element from its normal position.
1. ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Relative Position</title>
       <style>
         .relative {
           position: relative;
           top: 20px;
           left: 30px;
           background-color: #333;
           color: white;
           padding: 10px;
         }
       </style>
     </head>
     <body>
       <div class="relative">Relative Positioned Element</div>
     </body>
   </html>
   ```
