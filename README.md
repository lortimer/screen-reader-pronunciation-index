# Screen Reader Pronunciation Index

When I test web interfaces with screen readers, I'm often surprised by strange pronunciations in specific contexts. For example, `<time datetime="10:00">10 AM</time>` is pronounced by JAWS as "ten ay em", but a time in the middle of a paragraph with lower-case letters and periods, like `<p>... 10 a.m. and ...</p>`, is pronounced "ten a dot m AND". It treats the second period like the end of the sentence and emphasizes the word "and" as if it's the first word in a new sentence.

I created this repository to list examples of how specific screen readers handle specific scenarios. I want it to serve as a reference for developers and testers who may not have access to a particular screen reader to create the best experience possible for their users.

## Contribution

If you want to document a specific case or add coverage for a screen reader that isn't listed, please submit a pull request following the format of other examples in this repository.
