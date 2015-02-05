IP Validator
============

This is a validator made in Java to verify if a String is a valid IP. It was made during my Softare Engineering Fundamentals (CES-28) course and revised for my Programming Studio (CS242) course. JUnit 4 tests included.

Organization
============

The classes and methods were made in IntelliJ 14.0.3, so the .gitignore file was organized to only include source code based on the files automatically generated by this IDE. If you clone it in Eclipse, you might want to add a few more lines to your .gitignore.

The files included in the source folder are:

- console
  - IPConsole: main method that runs an IP verifier in the console. Returns errors if entry is not valid.

- validator
  - IPValidator: includes main method to verify IP strings.

- test
  - IPValidatorTest: JUnit 4 Test Case for IPValidator.
