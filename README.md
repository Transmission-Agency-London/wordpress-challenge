## WordPress

We have a simple challenge which we would like you to complete. It should ideally take less than one working day to finish.


### Challenge

Create a custom plugin. Fork this repository, work on the plugin and send us your plugin code!


### What's the task? ###

* Force use of TinyMCE in the Wordpress editor screen
* Create a custom plugin
* The plugin should create a custom post type called Videos
* CPT must have these fields for admin: Title, Subtitle, Description, Video ID, and Type (options are Youtube, Vimeo and Dailymotion - dropdown or radio buttons)
* CPT should not have its single page for readers and should not be in menu navs for Authors
* Create a shortcode that will display a video CPT with the following attributes:

```
[prefix_video id="POST ID" border_color="#3498db"]
```
* Default border should be 2 pixels wide
* Video output should be responsive
* Layout should be responsive
* Create shortcode generator - TinyMCE button that generates a popup with the following fields: post id, border width and border color with color picker option


### Additional notes ###

* Plugin must be fully translatable
* Code must follow the WP coding standards
* Code should not raise any warnings or notices