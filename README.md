# Project 1 Redaction Data

This repository contains test files you can use for your Project 1 submission.

Each file name in the root directory can have two forms `gatorlink`-`flagtype`-`in or out` or `gatorlink`-`concept`-`term`-`in or out`.
The words in the filename should be all lowercase and contain no spaces.
The `gatorlink` is the text in your UF email address before the @.
The `flagtype` should be either `names`, `dates`, `phones`, or `address`.
The `term` is the term associated with the concept flag.
The last string is either `in` or `out`.

You can submit up to five pairs of `-in` and `-out` files. 
Of those files, you can only use one of each flagtype and only one concept. 

Your data source must be at least 300 words.
You are recommended to use data from the Enron email corpus.

The contents of the `-in` file should be all plain text.
The contents of the `-out` file should be manually redacted text.
Be sure the files are identical except for the redacted components.
Also, ensure your text files only use `\n` line endings (Linux format) to avoid confusion.
An example pair for the `concept` flag is given in the table below.

| Example `-in` | Example `-out` |
| ------------- | -------------- |
|[christan-concept-house-in](christan-concept-house-in) | [christan-concept-house-out](christan-concept-house-out) |


**To submit**, make a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to add your examples files.

If you do not like how someone formatted a file or disagree, please open and *Issue*.

---
Back to [Project 1](https://ufdatastudio.com/cis6930fa24/assignments/project1)
