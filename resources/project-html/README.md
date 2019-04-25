# READ ME

## HTML Project
**DUE:** Friday, Feb. 22, Noon.


### Instructions

This projects is worth **10 points**.

Create a web-based version of your résumé using valid HTML5. It should be the equivalent of about 1 - 1 1/2 pages.

Do not use Toppel Career Center templates for this project. You are expected to create your résumé from scratch. The content and structure of your résumé should be original.

You have the creative freedom in how you present your résumé. It should take into account which part(s) of your details are the most important content-wise, be marked up in a way which describes the content and organized using HTML5 structural tags.

**Tip:** When you finish your first attempt at coding, print this page and mark off each requirement you have met. Then fix your code/résumé to meet the requirements you have missed.


### Before You Begin

Your résumé is a reflection of you. What you post to the web can be seen by anyone. Consider reading the following to craft an effective résumé:

[Resume Development Guide](https://hireacane.miami.edu/_assets/pdf/resources/guides/resume-cover-letter-guide.pdf). Toppel Career Center. [pdf, 164kb]

Baer, D. (2014, Sept. 25). [Google HR boss says 58% of résumés get trashed because of one spelling mistake](http://www.businessinsider.com/google-resume-mistake-2014-9). Business Insider.

Steinmetz, K. (2014, Sept. 29). [Why a typo can get your resume tossed in the trash](http://www.cbsnews.com/news/why-a-typo-can-get-your-resume-tossed-in-the-trash/). CBS MoneyWatch.


### Requirements

Your web page should:

- Be written in valid HTML5
- Include HTML5 structural tags -- `header`, `nav`, `main`, `section`, `article` (`footer` only if necessary)
- Properly use heading (`h1`-`h6`) tags
- Use appropriate semantic tags for marking up content
- Avoid use of decorative characters (i.e. hand-coded bullets (•), pipes (|), etc.)
- Exclude presentational elements (i.e. `b`, `i`, `hr`, `br`, etc.)
- Exclude generic tags (i.e. `span`, `div`)
- Exclude any styling
- Include at least two external links
- Include at least one properly sized and formatted image
- Follows best practices noted in class
- Be free of spelling, grammatical and style errors
- Be free of broken links
- Be free of broken images


#### Regarding Images

When you include an image or photo, you must:

- have the rights to use it
- size and format it properly for the web
- include in your GitHub repo (do not 'hot link' to the file hosted on another web site)

To properly size and format the image, use Photoshop as was explained in class.


### Submission

You will need to submit at least two files -- `resume.html` and your image file(s). Be sure to name the HTML document `resume.html`. Other names will result in a deduction.

Commit your files to the `username.github.io` repository you created during the GitHub Setup exercise. (You *do not* need to create a new repository for every project. You will always submit to the repository you added your first ever web page to.)

Create an [issue in this repository](https://github.com/umiami-web-design/project-html/issues) with your full name and a link to your web page (http://username.github.io/resume.html) by the deadline.

If you are unsure of what is required in the issue, [check the example](https://github.com/umiami-web-design/html-project/issues/1) provided.

Do not wait until the last minute to submit your URL.


### Grading

You are expected to do your best to meet the requirements listed above. If you give an *honest effort* and submit the work on time, you will receive full credit. Your professor reserves the right to deduct points for submissions perceived as rushed, insufficient or incomplete.

To assure you do not make mistakes going forward, you will receive feedback. One-on-one help will be available to go over any questions you may have to improve the quality of your work moving forward. Missing requirements and/or mistakes on future assignments will not be overlooked.

**You are required to submit this assignment properly and on time.** A missed deadline (submitting the assignment at 12:00:01 p.m.) will result in a two (2) point deduction for every 24-hour period the assignment is late up to three days past deadline.

Failure to submit the assignment to GitHub as detailed above (to your `username.github.io` repo, as `resume.html`) will result in a two (2) point deduction.

(I use a computer script to clone and do an initial validation check of every student's work. If the script breaks, it means I have to do extra work to find and/or grade your assignment. Therefore, it will cost you in points.)

**Plagiarism or lapses in web ethics, as detailed in the course syllabus, will result in a zero (0) on the assignment, PLUS a 15-point penalty on your final grade and referral to the University of Miami Honor Council.**

Good luck!


### FAQ

**Do I have to use all the heading tags?**

No. Remember, `h1`-`h6` are hierarchical, not sequential. If you only need to use `h1` and `h2`, to describe your content, that is fine.

**What if I need to use a presentational element like `b`, `i`, `hr` or `br`?**

Write a comment in your code justifying its use. If you cannot explain why you are using it for structural purposes, consider using another tag.

**The `ul` tag adds bullets, but the requirements says no decorative characters like bullets. Is using `ul` okay?**

Bullets are okay when you use the `<ul>` tag. This is a default style and can be changed with CSS.

What is *not* okay is using a hand-coded bullet or other decorative character like a pipe (`|`) in your HTML. For example:

- `&bull; my list item`.
- `123 Main Street | Miami, FL`

In the above cases, use semantic tags to better describe the content. We'll worry about how it looks when using CSS.

**Can I name my file `Resume.html` or `RESUME.html`?**

No. This will earn you a deduction for an incorrect submission.

Remember, web servers are case-sensitive --  `resume.html` and `Resume.html` are viewed as different files.

Also, it is considered a best practice to keep file names lowercase.
