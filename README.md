# Superior-svg-graphics-rendering-in-R-and-why-it-matters

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

The biggest change in this release is the R package on Windows and MacOS now includes the latest librsvg 2.48.4. This is a major upgrade; the librsvg2 rendering engine has been completely rewritten in Rust 1 using components from Mozilla Servo. This has resulted in major improvements in quality and performance, and we have gained full support for css styling.

In this post we showcase how it works, and why you should use svg for R graphics.

Mozilla Servo documentation : https://research.mozilla.org/servo-engines/
