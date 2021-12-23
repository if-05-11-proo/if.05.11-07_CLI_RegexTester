# if.05.11-07_CLI_RegexTester

Goal:
Implement a command line application for testing regular expressions

Assignment:
Implement a simple command line application for testing regular expressions.
It shall be possible to enter
# the text to test
# the regular expression pattern
multiple times. The application shall be terminated with a specific command / key.

The text and the pattern shall be stored until they are changed. This allows to enter subsequently different pattern that are matching the previously entered text.

After each modification of either the pattern or the text, the application shall print out:
# Whether or not the text was matched at all
# The part of the text that is matched by the pattern
  It would be nice to visualize this by marking the according substring, e.g.
  `Hello World
         ^---^ `
  The text is printed in the first line, the second line indicates the start and the end of the match.  
 
# The number or regex groups
# The matched regex groups -> matched text for each group, visualize the match using group index as start / end marker instead of '^'.

Implement unit tests that tests the application. Use e-mail addresses and phone numbers in different styles for this purpose.
