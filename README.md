# Using the Simple theme

 * Copy the theme into the `themes/` directory of your SilverStripe project.  If you've named it correctly, there should be a directory called `themes/simpler/templates`.
 
 * Add the following to your `mysite/_config.php` file.  Remove any existing `SSViewer::set_theme` lines.

		SSViewer::set_theme("simpler");
