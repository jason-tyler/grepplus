# GrepPlus
## Summary
GrepPlus is a simple text search program that accepts one to many keys that are used to search a standard input stream.

## Usage
GrepPlus is a java program and is invoked using `java GrepPlus --key [VALUE]`. The text to be
searched must be provided to the standard input stream.

Examples:

Linux/MacOS
`cat some.file | java GrepPlus --key some --key text`

Windows
`type some.file | java GrepPlus --key some --key text`

## Supported Arguments
* --key [VALUE] - Provides a value for GrepPlus to search.
* --help - Outputs basic program help documentation.

## Enhancements
* Implement support for reading from files instead of just standard input.
