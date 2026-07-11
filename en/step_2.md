## Add a second panel

Create a new panel with a picture and caption so your story has a second part.

Choose an image from the **Images** tab, then add another `<div>` underneath the first one in `index.html`.

```html filename="index.html" line_numbers="true" line_number_start="11" line_highlights="16-19"
  <div>
    <img src="sun.png">
    <p>There was once a star.</p>
  </div>

  <div> <!-- Add another panel for the next part of your story -->
    <img src="spaceship.png"> <!-- Use the filename of an image you chose -->
    <p>The star asked a friend to visit.</p> <!-- Add the next line of your story -->
  </div>
```

## Now run your code

Click **Run** and check that a second panel appears with your new picture and text.
