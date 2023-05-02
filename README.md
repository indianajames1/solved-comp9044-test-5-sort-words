Download Link: https://assignmentchef.com/product/solved-comp9044-test-5-sort-words
<br>
Write a Perl program replace_digits.pl that take a single argument a filename.

It should replace all digits (0-9 characters) in the files with the character ‘#’.

Your program should not should produce any output.

Your program should only change the file. For example

$ <strong>cat file.txt</strong>

I can think of 100’s, no 1000,000s of other things I’d rather be doing than these 3 questions.

$ <strong>./replace_digits.pl file.txt</strong>

$ <strong>cat file.txt</strong>

I can think of ###’s, no ####,###s of other things I’d rather be doing than these # questions.

Hint: don’t try read and writing the file at the same time – it won’t work – read all all the file, then write the file.

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

You can assume the file contains ASCII and is less than 1 megabyte.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest replace_digits</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test05_replace_digits replace_digits.pl</strong>

Write a Perl program, identical_files.pl which takes 2 or more filenames are argument.

Your program should then check if each file has exactly the same contents ad the other files given as arguments.

If all files are identical (the same), it should print exactly the message in the example below.

Otherwise it should print a message indicating the first file which is different to a previous file on the command line. Again print exactly the message as in the example below.

For example if create some files for testing:

Then this is how identical_files.pl should behave:

$ <strong>./identical_files.pl five.txt 5.txt</strong>

All files are identical

$ <strong>./identical_files.pl fortytwo.txt 42.txt 42a.txt</strong>

All files are identical

$ <strong>./identical_files.pl 5.txt 42.txt 42a.txt five.text</strong>

42.txt is not identical

$ <strong>./identical_files.pl</strong>

Usage: ./identical_files.pl &lt;files&gt;

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

You can assume files contain ASCII and are less than 1 megabyte.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest identical_files</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test05_identical_files identical_files.pl</strong>