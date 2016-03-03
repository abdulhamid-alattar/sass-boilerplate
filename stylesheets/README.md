# Main file

The main file (usually labelled `app.scss`) should be the only Sass file from the whole code base not to begin with an underscore. This file should not contain anything but `@import` `@include` and comments.

Reference: [Sass Guidelines](http://sass-guidelin.es/) > [Architecture](http://sass-guidelin.es/#architecture) > [Main file](http://sass-guidelin.es/#main-file)

# Settings file

It's a partial file that contains the Foundation settings. It's a deviation from the 7-1 architecture. This came from the foundation structure. All of Foundation's Sass variables can be found and modified here to help you customize your version of Foundation. 
