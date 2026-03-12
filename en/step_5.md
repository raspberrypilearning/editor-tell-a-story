<h2 class="c-project-heading--task">Challenge</h2>

--- task ---
Customise the colours and font so the page matches the mood of your story.
--- /task ---

Open `style.css` and try your own colour and font choices.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2-3, 10
---
body {
  background-color: lightblue; /* Change the page background colour */
  font-family: Arial; /* Pick a font that matches your story */
}
div {
  display: inline-block;
  position: relative;
  overflow: hidden;
  margin: 2px;
  background-color: lightyellow; /* Give each panel a new background colour */
  width: 200px;
  height: 200px;
  border: 2px solid black;
}
p {
  position: absolute;
  background: white;
  bottom: -1em;
  border-top: 2px solid black;
  border-right: 2px solid black;
  padding: 5px;
  margin-right: -2px;
  font-size: 10pt;
}
img {
  max-height: 100%;
  display: block;
  margin: 0 auto;
}
--- /code ---

</div>

--- task ---
Test: Click **Run** and check that the font and colours on your page have changed.
--- /task ---
