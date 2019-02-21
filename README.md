# Widget Class

The `Widget` class extends the WordPress Widget class (`WP_Widget`) to add some helper methods.

`Widget` expects only one method to be implemented: `protected function get_defaults()`.

`Widget` adds two static methods:
* `widget_save_inline_js()`: Outputs an inline admin script that autosaves a widget in the WordPress admin area.
* `is_widgets_page()`: Determines whether the current WordPress admin page is the widgets page.

