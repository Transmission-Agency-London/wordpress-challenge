## WordPress

This should ideally take less than one working day to finish.


### Challenge

Create a custom plugin to display a video from a custom post type.


### What's the task? ###

* Create a custom plugin
* The plugin should create a custom post type called Videos
* CPT must have these fields for admin: Title, Subtitle, Description, Video ID, and Provider (options are Youtube or Vimeo - dropdown or radio buttons)
* CPT should not have its single page for readers and should not be in menu navigation for Authors
* Create a shortcode that will display a video CPT with the following attributes:

```
[prefix_video id="POST ID" border_color="#3498db"]
```
* Default border should be 2 pixels wide
* Video output should be responsive
* Layout should be responsive
* Create shortcode generator - TinyMCE button that generates a popup with the following fields: post id, border width and border colour with colour picker option


### Additional notes ###

* Plugin must be fully translatable
* Code must follow the WP coding standards
* Code should not raise any warnings or notices