# Lisp Badge LE
A self-contained low-power computer with its own display and keyboard that you can program in Lisp. It now includes autocomplete, together with the new features in uLisp Release 4.8f.

The files are as follows:

* LispBadgeLE.ino - the uLisp source file for the Lisp Badge LE.
* LispBadgeLE-comments.ino - identical but including comprehensive comments.

Only use one of these files. It should be compiled and uploaded using the Arduino IDE.

For more information see http://www.technoblogy.com/show?3Z2Y.

Note that for consistency with the previous version of the Lisp Badge LE, autocomplete has been assigned to **META-ESC**. If you think that it would be more convenient to have autocomplete on **ESC** and Escape on **META-ESC**, swap the occurrences of '\e' and '\t' in **Keymap[]** before uploading uLisp.

