# WeMagazine

## 📚 Table of Contents
1. [Kanban Board Project Link](#kanban-board-project-link)
2. [Website Purpose](#website-purpose)
3. [Features](#features)
4. [Deployment Procedure](#deployment-procedure)
5. [Screenshots](#screenshots)
6. [Attribution](#attribution)
7. [AI Usage Declaration](#ai-usage-declaration)


Welcome! Click [here](https://dublino8576.github.io/WeMagazine/) to view WeMagazine's website, the online magazine by the people for the people!

Please go to the documentation folder to view extensive testing:
- Lighthouse performance
- HTML validator
- CSS validator
- Wireframes

Homepage Desktop Performance
<img width="1185" height="1159" alt="index_page_lighthouse_report_desktop-min" src="https://github.com/user-attachments/assets/d47da420-8075-485a-adbd-d0a1af3485b1" />

Homepage Mobile Performance
<img width="1182" height="1173" alt="mobile_report_indexPage-min" src="https://github.com/user-attachments/assets/fef50703-2919-4943-a9e9-4ac97fa26fe0" />


## Kanban Board Project Link
Click [here](https://github.com/users/dublino8576/projects/4) to view my project for WeMagazine.
It includes User Stories, must-haves for the MVP, and testing tasks for final deployment.



## Website Purpose

WeMagazine is an online magazine platform geared towards everyday people who feel inspired enough to share any bit of knowledge that is easy to understand for everyone in inclusive, friendly and relaxed way.
Two types of users can use this websites. We provide a stepping stone into the publishing world for writers of any experience that want to give back to the world and create a community.
Writers can submit their article on the submission form where they are asked to provide information for the article and pictures for the article and themselves, so readers can recognise and follow their favorite authors.
Once they submit their work, our team of developers makes up the article with the informations provided in an engaging and fun manner.
Our readers can browse through an ever-growing set of topics.

WeMagazine is a place "Where We Speak", everyone finds their voice.



## Features 

#### Navigation Bar

- The navigation bar is created using bootstrap, features links to all the must-haves for readers to open their favorite articles and for writers to navigate to the How-to-post section or click the CTA button directly landing to the submission form.
The Nav Bar is fully responsive and shows the user which page they are in by highlighting the appropriate navigation link.
- I have also integrated CSS to make the component fixed so that it follows the user around. The user must never be more than 2 clicks away from their destination.
To the left, a custom logo of WeMagazine is featured

#### Footer

- The footer is fully made with CSS.
- Bootstrap was only used for consistent spacing congruent with the rest of the website
- The "Curtain Effect": I have used the CSS property of sticky positioning to allow the navigation links to cover the logo at the top of the footer when the user has not fully scrolled down yet. Once the user has scrolled all the way down the logo appears like opening the curtains of a window.
- The navigation links are given block display property when on mobile and in-line block on bigger screens
- Xl and xxl screens see also separators between links
- The links are equipped with animation allowing them to scale up or down depending on their hover state

#### Hero Section

- The hero section features a video with overlay, animated text and CTA buttons for either readers or writers

#### Animation

- All sections part of the main content have an animation triggering when the user first views them. The animations are made with css keyframe and javascript

#### About Us Section

- This section features the use of Bootstrap grid as in the majority of the sections of the website for layout and spacing consistency reasons.
- The carousel is a step by step guide for authors to post on the magazine. This component is also from bootstrap but I have added some tweaks with CSS. Mobile viewers can see the current step number on the caption through the CSS content property with the ::before pseudo selector. All other devices will have a custom made step design using positioning and CSS flexbox.

#### Topics Section

- The topics cards feature overlays to make the title readable, the title gently and slowly scales up when hovered over

#### Daily Hacks Page

- The page features a list of article cards.The card components are from Bootstrap.
- Flip Card feature: CSS flip card is fully integrated with bootstrap card. Boostrap article card is resized to height and width of its parent component so that the flipping appears seamless and smooth.
- One side features the article's description with its image, the other has the author's detail and picture.

#### Article Page

- The article layout uses Bootstrap grid and features CSS donut with caption in the middle of the article height for helping engagement of readers during reading time.

#### Submission Form Page

- Features a fully integrated form in the layout of the page with all the required fields. The form is from Bootstrap and has been customised accordingly.
- When the user completes the form successfully, they are directed on a success page with a clear message and easy navigation links.

## Deployment Procedure

Early deployment was achieved using GitHub pages, which allowed me to view any bugs or rendering issues across web browsers and mobile devices early on.
I have used GitHub Projects to create a Kanban board template organising User Stories with related Acceptance Criteria and Developer Tasks.
Each small feature implemented had its dedicated branch, I have worked on one ticket and one feature at a time, allowing me to be time-efficient and precise.

## Screenshots

#### Home Page

<img width="2880" height="4766" alt="screenshot_index_laptop" src="https://github.com/user-attachments/assets/b8e5d1c3-dc62-4b0a-b0d3-096a4a660d62" />

#### Daily Hacks

<img width="1536" height="1784" alt="screenshot_daily_hacks_tablet" src="https://github.com/user-attachments/assets/8a8df167-6e90-40cf-b680-7991962179a8" />

#### Article Page

<img width="2880" height="2616" alt="screenshot_article_laptop" src="https://github.com/user-attachments/assets/b1b55606-7001-48c4-857b-7385f92322eb" />

#### Submission Form

<img width="2880" height="3126" alt="screenshot_submission_form_laptop" src="https://github.com/user-attachments/assets/021a022a-d9c9-4df8-b29c-3c9e8a5c666e" />

## Attribution

I have carefully selected assets of good quality which didn't require attribution, with the exception of the hero video I have included in the footer of the website.
I took inspiration from the website [Dazed](https://www.dazeddigital.com/) for ideas such as the overlay of the cards in the topics section and the curtain effect of the footer.

## AI Usage Declaration

AI was not used to generate broad templates. 

#### Copilot
- AI was used for the generation of the article text
- Detect syntax mistakes
- Use of Intellicence for quick text-shadow effects
- Explanation of aria-labels in different settings, tags and within particular components such as video tag or the form component
- Understanding User Stories priorities and clarification of the difference between Acceptance Criteria and Developer Tasks

#### ChatGpt
- AI was used for generating a broad spectrum of color combinations based on the purpose and audience of the website
- Generation of the logo from which I extrapolated to use for CTA buttons, navigation links

#### ChatGpt/Gemini
- Wireframes were generated after the completion of the website because of time constraints. 

