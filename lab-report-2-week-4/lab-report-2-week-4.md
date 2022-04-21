# Lab Report 2 - Incremental Development/Bugs

In this lab report, I will outline 3 different bugs found when trying to search for and print out the links to sites in a .md file.

## Bug 1: empty lines at end of code -> infinite loop

-Here are the changes made in the code to fix the bug:
![Code Changes Made](fix-for-reading-empty-lines1.png)
![More Changes](fix-for-reading-empty-lines2.png)

-Link to the test file that caused the bug:
[Test file that caused the failure](test-file.md)

-Here is a symptom of the bug:
![Symptom of the bug when running](symptom-from-bug1.png)

-Explaination of bug/symptom/failure-inducing input:
This bug was caused in part by the loop boundaries that originally didn't stop until at the end of a file. The symptom was an infinite loop whenever a file had empty lines at the end of it.  Any files with empty lines would be considered failure-inducing inputs in this case.

## Bug 2: proper link formatting
Here are the changes made in the code to fix the bug:
![Code Changes Made]()

-Link to the test file that caused the bug:
[Test file that caused the failure](my-test-file-1.md)

-Here is a symptom of the bug:
![Symptom of the bug when running]()

-Explaination of bug/symptom/failure-inducing input:
This bug is a result of 

## Bug 3: images in code -> images printed in output
-Here are the changes made in the code to fix the bug:
![Code Changes Made]()

-Link to the test file that caused the bug:
[Test file that caused the failure](my-test-file-2.md)

-Here is a symptom of the bug:
![Symptom of the bug when running]()

-Explaination of bug/symptom/failure-inducing input:
This bug is from us not distinguishing between images and links since the format is almost the same for images as it is for links.  The symptom of the bug is that the image file name is being printed as a link, when we are only looking for links.  The failure-inducing input is any file with an image.

