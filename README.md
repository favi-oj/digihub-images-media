DigiHub Images and Media Assignment

Project Description

This project is a personal profile webpage created using HTML5. It demonstrates the correct use of images, alternative text, figures, captions, native audio, and native video.

Features

* A profile image with meaningful alternative text.
* A decorative image with an empty alt attribute.
* A figure containing an image and a related caption.
* An HTML5 audio player with controls, a source element, and fallback text.
* An HTML5 video player with controls, a source element, and fallback text.
* Explicit width and height attributes on content images where appropriate.

Research Questions and Answers

Question 1: Why is <img src="developer.jpg"> incomplete for a meaningful image?

The code is incomplete because it does not include an alt attribute. Meaningful images need alternative text that communicates their important content or purpose. This helps people using screen readers and provides information when an image cannot be displayed.

Example:

<img src="developer.jpg" alt="Web developer writing HTML code on a laptop" width="600" height="400">

Question 2: Why is alt="image" usually poor alternative text?

The text alt="image" is usually poor because it does not explain what the image shows or why it matters. Screen readers already identify images, so the word “image” provides little additional information.

Better alternative text describes the important content or purpose of the image.

Example:

alt="Laptop and notebook arranged on a study desk"

Question 3: What alternative text would you write for your profile image, and why?

For my profile image, I would use:

alt="oil painting portrait of a young black person"

I would use this description because it clearly identifies the main subject of the photograph. It helps people who cannot see the image understand that it is my personal portrait.

Question 4: When should alt="" be used?

The empty alternative text alt="" should be used when an image is purely decorative and does not communicate important information.

Examples include decorative patterns, ornaments, and visual separators.

Using alt="" allows screen readers to ignore the decorative image and helps users focus on meaningful content.

Example:

<img src="images/decoration.jpg" alt="" width="600" height="200">

Project Files

* index.html — Main HTML webpage.
* images/ — Profile, decorative, and figure images.
* audio/ — Audio introduction.
* video/ — Video introduction.
* screenshots/html-validation.png — W3C HTML validation screenshot.
* screenshots/webpage-preview.png — Screenshot of the completed webpage.

HTML Validation

The HTML document was checked using the W3C Nu HTML Checker and passed with no errors or warnings.

Validator: https://validator.w3.org/nu/

Author
Created for the DigiHub HTML Images and Media Assignment.


## Live Website

View my completed DigiHub Images and Media assignment:

https://favi-oj.github.io/digihub-images-media/

## GitHub Repository

https://github.com/favi-oj/digihub-images-media/
