# Troubleshooting

## A cell displays `NameError`

A required earlier cell probably has not been run. Select **Kernel > Restart Kernel and Run All Cells**, then let the notebook run from the beginning.

## The notebook says that a data file cannot be found

Keep the notebook in the same folder as the `data` folder. Do not rename either one. If you uploaded the files to an online Jupyter system, upload the entire unzipped folder rather than only the notebook.

## A simplex pivot cell gives an assertion or choice error

Recheck the entering variable, the eligible positive entries in its column, and the minimum-ratio test. Enter variable names exactly as shown, including lowercase letters and numbers—for example, `x3` or `s1`.

## I changed an instructor-provided code cell

Download a clean copy of the assignment and copy only your **YOUR CHOICE** entries and **YOUR RESPONSE** text into it. Instructor-provided cells are part of the assignment infrastructure and should not be edited.

## A plot does not appear

Run the plotting cell again after running every preceding cell. If that does not work, restart the kernel and run all cells.

## The notebook runs forever or appears stuck

Use **Kernel > Interrupt Kernel**, then **Restart Kernel and Run All Cells**. This assignment should normally finish in well under one minute after all responses have been entered.

## I cannot export to HTML

Try **File > Save and Export Notebook As > HTML** or **File > Download as > HTML**, depending on your Jupyter version. If the menu option is unavailable, save the notebook and contact your instructor before the deadline.

## My HTML file does not show the latest work

Save the notebook, restart and run all cells, save again, and then create a new HTML export.

## I still need help

Send your instructor a screenshot of the complete error message and state which problem and cell caused it. Do not send only “it does not work”; the exact message is needed to diagnose the issue.
