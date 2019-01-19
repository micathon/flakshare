# impagey
Coming soon! Impagey is an open source (completely free) web-based image sharing tool written in Python, which makes use of Flask and Dropbox.

Every image is stored in either an image folder or a folder named "$" contained in an image folder. All image folders are stored in superfolders. A special superfolder named "z" contains the primary image folders. A subfolder of "z" which is also named "z" contains the tertiary image folders. All other image folders are designated as secondary image folders. Images are displayed in either a grid (defaults to 3 rows by 6 columns) or a single large image. The primary, secondary, and tertiary grids are collectively called grid outers. The grids beneath image folders are collectively called grid inners. The grids beneath "$" folders are collectively called grid cores. Image folder names beginning with an underscore are ignored. The user's local Dropbox folder is an ancestor folder of the root folder of all image folders.
