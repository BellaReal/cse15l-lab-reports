# Lab Report 2 - Incremental Development/Bugs

In this lab report, I will outline 3 different bugs found when trying to search for and print out the url links to sites in a .md file.

## Bug 1: empty lines
![Code Changes Made]()
[Test file that caused the failure](my-test-file-1.md)
![Symptom of the bug when running]()
This bug was caused in part by the loop boundaries that originally didn't stop until at the end of a file. The symptom was an infinite loop whenever a file had empty lines at the end of it.  Any files with empty lines would be considered failure-inducing inputs in this case.

## Bug 2: images versus links
![Code Changes Made]()
[Test file that caused the failure](my-test-file-2.md)
![Symptom of the bug when running]()
This bug is from us not distinguishing between images and links since the format is almost the same for images as it is for links.  The symptom of the bug is that the image file name is being printed as a link, when we are only looking for links.  The failure-inducing input is any file with an image.

## Bug 3: proper link formatting
![Code Changes Made]()
[Test file that caused the failure](my-test-file-3.md)
![Symptom of the bug when running]()
This bug is a result of 
