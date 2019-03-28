

## Rules

* Do not code **HTML**, SCSS, JS in the **global**, **shortcodes**, **[type]/[layout]** folders.
* Only code HTML, SCSS, JS in the **partials/app-[partial name]** folders.
* The **global** folder is only for:
  * Importing SCSS variables.
  * Importing SCSS mixins.
  * Defining global SCSS variables for the partials.
  * Defining global JS constants, variables for the partials.
* For **shortcodes** and **[content type]/[layout.html]**, you must include partials to render the template in HTML.
