---
title: "Creating clarifying code comments  "
output: html_document
---



# Creating clarifying code comments

<img src="resources/images/08-code_comments_files/figure-html//1PH9_KlLVggYpNJI0fgvcIcft2vDtGA_mlCqKFA8gnAg_gd422c5de97_0_54.png" alt="This chapter will demonstrate how to: Understand the goals of good code documentation. Describe characteristics of helpful code comments." width="1250" />

## The goal of a code documentation

Code documentation goes beyond your user. It's a part of writing good code and helps your collaborators and 'Future You'!

Most users will probably not look at your code directly -- those who do are probably:

- Quite desperately troubleshooting something and were not able to find answers elsewhere.
- Are “power users” who are already pretty invested in your tool and want to get more out of it -- may be helpful contributors too!

Good code comments are a part of writing good, readable code! Your code is more likely to stand the test of time for longer if others, including yourself in the future, can see what’s happening enough to trust it themselves. This will encourage others to use your code and help you maintain it!

'Current You' who is writing your code may know what is happening but 'Future You' will have no idea what 'Current You' was thinking [@Spielman]:

> 'Future You' comes into existence about one second after you write code, and has no idea what on earth Past You was thinking. Help out 'Future You' by adding lots of comments! 'Future You' next week thinks Today You is an idiot, and the only way you can convince 'Future You' that Today You is reasonably competent is by adding comments in your code explaining why Today You is actually not so bad.

Your code and your understanding of it will fade soon after you write it, leaving your hard work to deprecate. Code that works is a start, but **readable** AND working code is best!

Comments can help clarify at points where your code might need further explanation. The act of writing them can also help you think out your thought process and perhaps identify a better solution to the odd parts of your code.

## Characteristics of clarifying code comments

What kinds of comments are most helpful for 'Future You' and others?

@Spertus2021 lays out "Rules" for writing helpful code comments [in this article](https://stackoverflow.blog/2021/07/05/best-practices-for-writing-code-comments/) which we recommend you read.

> Rule 1: Comments should not duplicate the code.

> Rule 2: Good comments do not excuse unclear code.

> Rule 3: If you can’t write a clear comment, there may be a problem with the code.

> Rule 4: Comments should dispel confusion, not cause it.

> Rule 5: Explain unidiomatic code in comments.

> Rule 6: Provide links to the original source of copied code.

> Rule 7: Include links to external references where they will be most helpful.

> Rule 8: Add comments when fixing bugs.

> Rule 9: Use comments to mark incomplete implementations.

Here are more resources about good code comments that have plenty of great discussions about how to up your code comment game.

- [Best Practices for Writing Code Comments](https://stackoverflow.blog/2021/07/05/best-practices-for-writing-code-comments/) by @Spertus2021.
- [What Makes a Good Code Comment?](https://itnext.io/what-makes-a-good-code-comment-5267debd2c24) by @Cronin2019.  
- [The Value of Code Documentation](https://www.olioapps.com/blog/the-value-of-code-documentation/) by @Meza2018.  
- [Some internet wisdom on R documentation](http://alyssafrazee.com/2014/04/20/rdocs.html) by @Frazee2014.  
- [How to Comment Your Code Like a Pro: Best Practices and Good Habits](https://www.elegantthemes.com/blog/wordpress/how-to-comment-your-code-like-a-pro-best-practices-and-good-habits) by @Keeton2019.  

**In summary:**

<img src="resources/images/08-code_comments_files/figure-html//1PH9_KlLVggYpNJI0fgvcIcft2vDtGA_mlCqKFA8gnAg_gcdcbd8d802_0_132.png" alt="Good code documentation: Is a part of writing good code! Increases the readability of your code. Clarify where the code requires explanation. Can help you write out your thought process." width="1250" />

## Exercise: Evaluate your own code's comments

Take a look through some of your tool's code and its comments. Are there places it could be clearer? Take some time to think about your coding process and how it could improve. [Code review](https://simpleprogrammer.com/why-code-reviews-make-better-code-teams/) is also an excellent way to improve code clarity and quality [@Bodner2018]!
