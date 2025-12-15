# Front-end Workshop 1: HTML

## Introduction

Welcome to the first front-end workshop! In this workshop, we'll be exploring modern HTML. By the end of this workshop, you should hopefully feel more confident about how to use HTML well when working on the front-end.

### What is HTML?

HyperText Markup Language (HTML) is a language that is used to describe the **structure** of a document, typically a web page. HTML is one of the three languages of the front-end, alongside Cascading Style Sheets (CSS) and JavaScript.

Together, these languages create functional web pages and apps. To better understand how they compliment each other, I like to use two analogies:

1. **A sentence**:

   - **HTML** is the **noun**
   - **CSS** is the **adjective**
   - **JavaScript** is the **verb**

2. **A human body**:

   - **HTML** is the **skeleton**
   - **CSS** is the **skin**
   - **JavaScript** is the **muscle**

HTML is the _foundational part of any website or web application_. Without HTML, we cannot build _anything_. Therefore, it is very important to feel comfortable reading, writing and understanding HTML!

## Rules for this workshop

There are 2 simple rules for this workshop:

1. You can **only use HTML**.
   - CSS and JavaScript are not allowed. All of the exercises can be completed without the use of any CSS or JS.
   - What you'll make in this workshop will look ugly, yes, but there is a reason for this which I will explain at the end.
2. You **cannot use generative AI tools**:
   - The goal of this workshop is to learn and explore, not to complete everything within the allowed time. AI can help complete the tasks, sure, but an important part of learning is finding the answers yourself.

If you break these rules you will be fired

## Getting Started

1. Clone this repository to your device
2. In a terminal, `cd` to your local copy of the repository
3. Run `npm install`
4. Run `npm run dev`
5. In your web browser, navigate to `http://localhost:5173/`. You should see a blank webpage
6. In your text editor, open the `index.html` within your local copy of the repository

## Challenges

Doctolib are preparing to announce the launch of their innovate new health service, the Doctolib Health Satellite Mesh Network. Using a group of satellites launched into space above Europe, Doctolib can now provide instant AI-driven healthcare, both in Europe and in space above Europe, to residents and astronauts that hold a DoctoCard NFT token for the low price of 100 DoctoCoins per consultation.

Your challenge is to prepare the web page announcing this fantastic new service!

### Challenge 1

The page is currently completely blank! Let's set up the structure of the page first.

We will need the following:

- Navigation with the following links:
  - Doctolib homepage
  - A login link
  - A help center link
  - A 'find a practitioner' link
- A section for the main content of the page (the blog post)
- A footer with the following links:
  - Privacy Policy
  - Cookie Policy
  - About Us
  - Careers

ℹ️ **NOTE::** You don't have to link to real pages here, you can use `#` as the `href` in the link to make a 'dummy' or placeholder link ℹ️

### Challenge 2

Now that the page isn't blank, we can start adding some content. In the `content/` folder, you'll find a file called `press-release.md`. Your task is to add the content of this file to the page, taking care to ensure the content is added semantically using proper HTML tags.

⚠️ **NOTE::** Remember to use semantic HTML to preserve the headings and formatting! ⚠️

### Challenge 3

Everyone is (understandably) _incredibly excited_ about Doctolib's new service, and our product managers want to get as many people as possible signed up to hear more news from Doctolib.

Product and Design want a newsletter sign-up within the article. They have provided you with the copy to be used in the newsletter sign-up in `newsletter-signup.md` within `content/`.

Their requirements are:

1. The newsletter sign-up should include a text field to type an email address into and a submit button
1. The signup should be visible within the article as an aside, just after the last paragraph.
1. We should validate that a real email address has been entered into the field.
1. When tapping on the field on a mobile device, the `@` symbol should be visible on the keyboard to make it easy for people to enter their email address. If we could also get autocomplete support for a visitor's email address that would be great.

## Extra Credit

The page looks pretty complete now! Here are some optional extra challenges to really stretch your learning. These challenges can be completed in any order. They're a bit tougher, so don't worry if you don't complete them today.

### Extra Credit 1 (Difficulty: easy)

There are no pictures on the blog post!

We've just sent a photographer up into space to take a photo of one of our satellites, and we want to add their photo to the page. The photo can be found in `public/satellite.png`.

Your task is to add this photo.

⚠️ **NOTE::** Since we're using `vite` for this workshop, you will need to exclude `public` from any `src` attributes in images. For example, `/public/example.jpg` -> `/example.jpg` ⚠️

### Extra Credit 2 (Difficulty: medium)

We've received lots of questions from our community about the Doctolib Health Satellite Mesh Network! Our product managers have compiled a set of frequently asked questions and answers, and would like to add these questions to the page. The questions and answers can be found in `content/faqs.md`.

Your challenge is to add the FAQ's to the page, with the following requirements:

1. The FAQ's should come _after_ the newsletter sign-up on the page
2. By default, only the questions should be visible. Clicking/tapping on a question should 'reveal' the answer.

### Extra Credit 3 (Difficulty: NIGHTMARE MODE)

Product want to include a diagram of the blueprints for the satellites within the article. We've received the blueprint image, but it's very hard to see on mobile devices, so Design have created a desktop version of the blueprints and a mobile version.

These blueprints can be found in `public/blueprint_mobile.png` and `public/blueprint_desktop.png`.

Your task is to insert these pictures into the article, with the following requirements:

1. People visiting the page on mobile devices **only** see the mobile blueprint image
2. People visiting the page on desktop devices **only** see the desktop blueprint image
3. By default, we show a visitor the mobile blueprint image if we can't determine desktop vs. mobile

## Resources

Handy resources for this workshop:

- [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML) - comprehensive documentation on different HTML elements.
- [web.dev](https://web.dev/html#new-to-html) - guides and articles about HTML usage.
