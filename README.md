# CSS Assignment

**Due:** Dec. 1, 2017, 3 p.m.


## Instructions

This assignment is worth **15 points**.

Using a corrected version of your HTML résumé, create a styled version for the web and print using CSS.

You have the freedom to be creative in how you present your résumé. All presentation should be through the use of CSS, the styling should follow proper visual design techniques and adhere to best practices.

Suggestion: Follow instructions. When you finish your first attempt at coding, print this page and mark off each requirement you have met. Fix your code/résumé to meet the requirements you have missed.


## Before You Begin

By now, you should have taken the time to correct the HTML version of your résumé based on feedback from your professor. You may choose to (or have to) modify your HTML in order for a design in CSS to take hold. Adjustments to your HTML are permitted.

*Note:* If your design does not warrant navigation (i.e. the design is, say, left-aligned, and won't shift content to the top), you may remove the navigation from your HTML.

Do not make the same mistakes you made on the first project. Any repeated mistakes from the HTML project will receive a general deduction.


## Requirements

Your web page should:

- Include at least one image saved in the proper file format at a reasonable size
- Utilize an external style sheet
- Exhibit use of box model properties (i.e. margin, border, padding)
-  Include two, well-paired web fonts from a provider such as Google Fonts
- Set colors for all link states (default, active, visited, hover)
- Keep content from stretching beyond 960 pixels
- Demonstrate a layout technique
- Avoid "design sins" (see below)

In general, your document should:

- follow best practices as specified during lectures
- be free of spelling, grammatical and style errors
- be free of broken links
- be free of broken images


### Reminder

When including an image (social media icons, for instance):

- you must have the rights to use it
- it must be included in your GitHub repo (no linking to an image or file hosted on another site)


### Design Sins

Your design should avoid the following:

- Things that blink
- Warped or distorted photos
- Naked photos (photos lacking a border)
- Bulky borders or boxes
- Bad bullets
- Unbalanced margins
- Poorly aligned elements
- Centering everything
- Clutter
- Trapped white space
- Busy backgrounds
- Tacky, mismatched or illegible type
- Mismatched colors


## A note about layout techniques

I have provided sample layouts using CSS Grid in the `layout-template` repository.

You are encouraged to try and implement a layout using grid on your own. If confusion remains or a solution for your individual idea cannot be realized you may use these templates as a scaffold in creating your styled resume.

Please read the comments in each HTML file. They explain why we do certain things (i.e. limit a container to 960 pixels). There are also explanations as to how you modify your HTML to make the grid work in this instance, even if it's not the ideal way of using grid.

### Conditions

If you use any of the provided templates, you must do the following:

- No style tags (or CSS rules) should appear in the HTML file. Transfer the necessary CSS code to an external style sheet.

- Remove the default styling (i.e. `background-color: #eee;`) I have added which allows you to see the elements. I have indicated these with a comment.

- Add a proper `grid-gap`. Don't use the default of 2px I used. Be original.

- Credit should be added at the top or bottom of the style sheet noting which CSS blocks were written by me. (I'm not looking for glory here, but I want you to get in the habit when you do use code from other permissible sources, you credit it appropriately.) Credit the author and provide a link to where the code came from. Something as simple as what follows will suffice:

```
/*
  CSS grid scaffolding provided by Erin Brown.
  http://github.com/umiami-web-design/grid-templates
*/
```

**Additional Resources:** You may also use examples from the `grid-walkthrough` from class or from [Rachel Andrews' Examples](https://gridbyexample.com/examples/) and [Grab & Go Patterns](https://gridbyexample.com/patterns/) gallery provided proper attribute (as detailed above) is given in your code.

**Failure meet the conditions above suggests little-to-no attempt to make your design unique and will result in a deduction.** This code is designed to scaffold what you want to achieve, not be the foundation for your entire project.


#### Things you should consider adjusting

- The proportion of your columns. Everything should be within a container of at least 960 pixels (it can be smaller). Try laying out your design where the container is 1/3 and 2/3 or maybe 1/4 and 3/4.

- Implementing one fixed-width column (i.e. 300px) and one flexible column. Maybe you have a small amount of content in a row that doesn't need added whitespace. Make it fixed. Or maybe use the `minmax()` property to give it a teeny amount of flexibility.

- If you have a left-aligned design (i.e. a left column with a background), you do not need to center the container. It goes against the design you're aiming for. (Unless, of course, you find a creative way to have that background stretch all the way to the left side of the browser window!)


## Submission

You will be submitting at least three files -- resume.html, style.css and an image file -- for this assignment. You may have extra files additional images. Commit your files to the username.github.io repo you created at the beginning of the semester.

Create an [issue](https://github.com/umiami-web-design/css/issues) in the `css` repository with your full name and a link to your web page (username.github.io/resume.html) by the deadline. If you are unsure of how to submit, check the example provided in the Issues section.

Do not wait until the last minute to submit your URL.


## Grading

Due to circumstances this semester, deductions will not be taken for each missing requirement. You are, however, expected to do your best to meet the requirements listed above. If you give an honest effort and submit the work on time, you will receive full credit.

To assure you do not make mistakes going forward, your professor will still provide feedback regarding missing requirements. One-on-one help will also be available at Hack Hours to go over any questions you may have to improve the quality of your work moving forward. Missing requirements and/or mistakes will not be overlooked on future assignments.

You are, however, required to submit this assignment properly and on time. A missed deadline (submitting the assignment at 3:00:01 p.m.) will result in a two (2) point deduction for every 24-hour period the assignment is late.

Failure to submit the assignment to GitHub as detailed above (to your username.github.io repo, as resume.html) will result in a two (2) point deduction.

(I use a computer script to clone and do an initial check of every student's work. If the script breaks, it means I have to do extra work to find and/or grade your assignment. Therefore, it will cost you in points.)

**Plagiarism or lapses in web ethics, as detailed in the course syllabus, will result in a zero (0) on the assignment, PLUS a 15-point penalty on your final grade and referral to the University of Miami Honor Council.**



## Feedback

Students who would like one-on-one feedback can [schedule time with me](https://docs.google.com/a/miami.edu/spreadsheets/d/1KczoeUsIavACeBvXXoSmBJYJ5AUTCp-3Dl9ednpbrow/edit?usp=sharing). **Sign-up is first-come, first-serve.**  You **must** be logged in to your miami.edu account to add your name to the spreadsheet. I will not grant access for individual gmail accounts. Please only block one slot when you sign up, and be sure to keep your appointment. If you miss your scheduled meeting for whatever reason, I will not permit a second sign-up. (It's not fair to another student who may have been able to use that slot, but didn't get to it since you signed up first. So please be considerate of your peers.)

I have not yet opened slots for Thursday. We will see how the week goes. I have prior commitments I must meet. But if there is a dire need, I may be able to postpone one or two of these.

Those who plan to meet should set aside 20-30 minutes. Come prepared. Bring your work in a somewhat completed state -- you might need some assistance tweaking your design, but for the most part the HTML and CSS should be done. You might have some broken parts and that's okay. But be aware: If your HTML is broken, I cannot help you with CSS. I will send you away to fix that and your appointment time may be wasted. So again, come prepared. Make sure your HTML validates.
