# Local Archery Club

Local Archery Club is a website for people who love archery, meant for both first-timers and regular practicioners in Uppland, Sweden. The site is targeted towards archers who want a location to practice, socialice and have access to instructors at scheduled times.

![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features

### Existing Features

- **Navigation Bar**

  - Featured on all three pages (and fourth hidden which is confirmation.html). Fully responsive and includes links to logo, home, about and contact and is the same on each page for easy navigation.
  - Section allows user to easily navigate on all devices without the nesecessity of using the 'back' button.

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- **The landing page image**

  - The first image show a child and several adults exercising archery. Meant to be attractive for beginners, showing people of all ages and showing a social environment.

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- **Middle Sections**

  - The first part of the middle section explains core information. Beginning with that everyone is welcome.
  - The second image shows a young adult. Meant to reinforce that the club is also meant for adults.
  - Latter part of the middle section explains other core information. Beginning with information about newcomers. Then explaining what isn't allowed in the club and what it's meant for. Then finally showing pricing information.
  - The information is meant to be kept short and simple together with an accompanying image for easy reading.

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- **Times Table Section**

  - This section is present on every page as a simple reminder of what times the users can visit the club.
  - This section will be updated should the times change.

![Meetup Times](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- **The Footer**

  - The footer section contains the number for the club as well as its address on the left side. It contains relevant social media for Local Archery Club on its right side with clickable icons for easily taking the user to that site.
  - The footer encourages users to stay in contact with Local Archery Club's social media.

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- **About**

  - The gallery will provide the user with supporting images to see what the meet ups look like.
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together.

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- **Contact**

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address.

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Add change language button. Since the page is meant to be in sweden, original language should be swedish, and then can be changed to english next to the logo.

## Design

Insert wireframes here

Explain why the design is different from the wireframes

Lightblue background is chosen because it is a relaxing/cool colour. Meant to instill calmness and evoking a "freedom of outdoors skyview" feeling

Brown color is chosen to give a natural and "woody" feeling.

## Testing

| Action                                                                                                                             | Expected Behaviour                                         | Pass/Fail    |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ------------ |
| Click on logo, click on each of links in menu (home, about, contact). On all four html pages (index, about, contact, confirmation) | Links works correctly and the user is brought to each page | pass         |
| Content Cell                                                                                                                       | Content Cell                                               | Content Cell |

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Fixed Bugs

- Media screen when max-width go below 760px, menu jumps down below logo. However the menu is reversed, beginning with contact about home instead of home about contact.
  - Bug was fixed when using px instead of % in width for paddings and margins.

### Unfixed Bugs

- Send button on form is clickable only on 'Send!' text instead of the whole button.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html

## Credits

### Content

- HTML, CSS, layout, structuring and understanding of concepts was made with the help by the course material from Code Institute and inspired particularly by the Love Running project.
- HTML form and CSS for the form in contact was taken from Love Running project at the Code Institute program. Some attributes and elements have been changed but it has been used as the template.
- All icons were taken from fontawesome.
- Code for styling with flex display for centering images on about page https://blog.hubspot.com/website/center-an-image-in-html
- The flex-wrap wrap came from https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- README template was copied from Love Running Project given by Code Institute.

### Media

- All images were taken from pexels.com https://www.pexels.com/
  - images by Mikhail Nilov https://www.pexels.com/@mikhail-nilov/
    - file:///workspaces/local-archery-club/assets/images/pexels-mikhail-nilov-6620781.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-mikhail-nilov-6620778.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-mikhail-nilov-6620465.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-mikhail-nilov-6620459.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-mikhail-nilov-6620340.jpg
    - file:///workspaces/local-archery-club/README.md
  - images by RDNE Stock project https://www.pexels.com/@rdne/
    - file:///workspaces/local-archery-club/assets/images/pexels-rdne-stock-project-6669103.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-rdne-stock-project-6655617.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-rdne-stock-project-6655601.jpg
    - file:///workspaces/local-archery-club/assets/images/pexels-rdne-stock-project-6655481.jpg

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work!

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write a Git Commit Message

  - Make sure to keep the messages in the imperative mood

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.

  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept.

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process!
