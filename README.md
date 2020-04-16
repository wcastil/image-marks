WELCOME TO THUNDERDOME. 

To work on my mac I had to pip install wxPython and run with the following command:
pythonw correspondence_tool.py path_to_image1/image1png path_to_image2/image2.png output.txt

MISSING:
-outputting the correspondence in a format needed for our testing
-More than two images to correspond
-Zoom


Image Correspondences
===========

A simple graphical tool to specify manual point-to-point correspondences between two images.

    python correpsondence_tool.py IMAGE1 IMAGE2 OUTPUT

![Screenshot of correspondence UI][screenshot]

Key | Binding
--- | ---
`s` | Save correpsondences to output file
`q` | Save correspondences to output file and exit
`c` | Clear all correspondences
`h` | Show/hide fitted homography (requires at least four points)

[screenshot]: https://raw.github.com/alexflint/image-marks/master/docs/screenshot-small.jpg


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/alexflint/image-marks/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

