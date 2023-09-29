# The November Room (GYM Major project Tailwind)

This project is a responsive landing page for "The November Room," a fitness and training center. It utilizes HTML and the Tailwind CSS framework for styling.


## Table of Contents
Click 👆 any section to navigate to code explanation part !
- [Nav Section](#nav-section)
- [Hero Section](#hero-section)
- [About Section](#about-section)
- [Trainers Section](#trainers-section)
- [Contact Section](#contact-section)
- [Footer Section](#footer-section)
- [Animate on Scroll (AOS)](#animate-on-scroll-aos)

## Nav Section

 #### `<nav class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between px-2 py-3 navbar-expand-lg">`

- Defines the navigation bar at the top of the webpage.
- Fixed at the top of the viewport (`top-0`) and stays visible while scrolling.
- Positioned above other elements in the stacking order (`z-50`).
- Spans the entire width of the screen (`w-full`).
- Uses flexbox to arrange its children elements in a row and wraps them when necessary.
- Vertically and horizontally centers its children (`items-center`, `justify-between`).
- Adds padding horizontally and vertically (`px-2`, `py-3`).
- Expands the navigation bar for larger screens (`.navbar-expand-lg`).

#### container
- `<div class="container px-4 mx-auto flex flex-wrap items-center justify-between">`

  - Contains the navigation bar content within a container.
  - Restricts the content width and centers it horizontally (`px-4`, `mx-auto`).
  - Uses flexbox to arrange its children elements in a row (`flex`).
  - Aligns its children items and justifies their spacing between each other (`items-center`, `justify-between`).

#### Logo 

- `<div class="logo w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start">`
  - Defines the container for the logo and menu toggle button.
  - Allows the logo to be flexible in size and maintains its position in larger screens (`w-full`, `lg:w-auto`, `lg:static`).
  - Positions the elements in a row and maintains spacing (`flex`, `justify-between`).

- `<a class="text-lg font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white" href="#">The November Room</a>`
  - Represents the website's name as a clickable link.
  - Uses a larger font size and bold text style (`text-lg`, `font-bold`).
  - Ensures the text doesn't wrap and maintains spacing (`whitespace-no-wrap`).

- `<button class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none" type="button">`
  - Creates a button for toggling the navigation menu on smaller screens.
  - Displays a hamburger icon (represented by `<i class="text-white fas fa-bars"></i>`) inside the button.
  - Uses appropriate padding and styling for visual appeal.

#### Social Media Icons

- `<div class="icons-wrapper lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none hidden" id="example-collapse-navbar">`
  - Contains social media icons and handles responsiveness for larger screens (`lg:flex`, `hidden` for smaller screens).
  - Uses flexbox to align icons in a row (`flex`) and allows them to grow and fill available space (`flex-grow`).
  - Provides a shadow effect for visual depth in larger screens (`lg:shadow-none`).

- Social media icons are represented as list items within an unordered list.
  - Each icon is wrapped in a clickable link (`<a>`) and styled for both normal and hover states.
  - Icons include Facebook, Twitter, and LinkedIn, each represented by appropriate Font Awesome classes and text colors.
## Hero Section

#### `<div class="min-h-[95vh] bg-bgi bg-cover bg-no-repeat relative pt-16 pb-32 flex content-center items-center justify-center">`

  - Sets the minimum height of the hero section to cover 95% of the viewport height (`min-h-[95vh]`).
  - Applies a background image with cover and no-repeat properties (`bg-bgi bg-cover bg-no-repeat`).
  - Allows content to be centered both vertically and horizontally (`flex content-center items-center justify-center`).

#### `<div class="container relative mx-auto" data-aos="fade-in">`

  - Contains the hero section content within a container.
  - Centers the content horizontally using auto margins (`mx-auto`).
  - Applies a fade-in animation on scroll (`data-aos="fade-in"`).

#### `<div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">`

  - Provides a responsive width for text content, taking up full width on smaller screens and half width on larger screens (`w-full lg:w-6/12`).
  - Centers the content horizontally on all screen sizes (`ml-auto mr-auto text-center`).

- `<h1 class="text-white font-semibold text-5xl">`

  - Displays a white, bold heading with a font size of 5xl.
  - Emphasizes the word "Power" in orange (`text-orange-500`).

- `<p class="mt-4 text-lg text-gray-300">`

  - Presents a light gray paragraph text with a font size of lg.
  - Describes the purpose and offerings of "The November Room."

- `<a href="#" class="bg-transparent hover:bg-orange-500 text-blue-500 font-semibold hover:text-white p-4 border border-orange-500 hover:border-transparent rounded inline-block mt-5 cursor-pointer">Download Brochure</a>`

  - Provides a call-to-action button with a transparent background and an orange border.
  - Changes background color and text color on hover to orange and white respectively.
  - Links to a brochure download page (currently represented by `href="#"`).

#### `<div class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden" style="height: 70px; transform: translateZ(0px);">`

  - Adds a decorative element at the bottom of the hero section.
  - Uses an absolute position to place it at the bottom of the container.
  - Utilizes an SVG polygon shape for the decorative design.


## About Section

#### `<section class="about relative py-20 bg-black text-white">`

- Defines the about section of the webpage.
- Sets the background color to black and text color to white.

#### Image and Content Layout

- `<div class="container mx-auto px-4">`

  - Contains the about section content within a container.
  - Centers the content horizontally using auto margins (`mx-auto`).

- Image Side:

  - `<div class="image-side w-full md:w-4/12 ml-auto mr-auto px-4" data-aos="flip-left">`
    - Contains an image on the left side of the section.
    - Takes up 4/12 of the width on medium screens (`md:w-4/12`).
    - Applies a flip-left animation on scroll (`data-aos="flip-left"`).

- Content Side:

  - `<div class="content-side w-full md:w-5/12 ml-auto mr-auto px-4" data-aos="fade-left">`
    - Contains text content on the right side of the section.
    - Takes up 5/12 of the width on medium screens (`md:w-5/12`).
    - Applies a fade-left animation on scroll (`data-aos="fade-left"`).

#### Text Content

- `<small class="text-orange-500">About our gym</small>`
  - Displays a small text in orange, indicating the context of the section.

- `<h3 class="text-4xl uppercase font-semibold">Safe body Building</h3>`
  - Presents a large, uppercase heading in white with a font size of 4xl.
  - Emphasizes the topic of the section.

- `<p class="mt-4 text-lg leading-relaxed">`
  - Provides a medium-sized paragraph text with a line height of relaxed.
  - Describes the gym and its offerings in a relaxed and readable manner.

#### Feature List

- `<ul class="lists list-none mt-6">`

  - Defines an unordered list without bullets and adds margin at the top.

  - `<li class="py-2">`
    - Represents a list item with padding on the y-axis.

    - Latest & Greatest Gym Equipment:
      - Displays a gym equipment icon and text.
      - Uses orange color for the icon.

  - `<li class="py-2">`
    - Represents another list item with padding on the y-axis.

    - 5-Inch, Quality Foam Floor Padding:
      - Displays a hard hat icon and text.
      - Uses orange color for the icon.

  - `<li class="py-2">`
    - Represents a third list item with padding on the y-axis.

    - 3 Professional Trainers:
      - Displays a users icon and text.
      - Uses orange color for the icon.

This section effectively communicates information about the gym's facilities and features in a visually appealing and structured manner.

## Trainers Section

#### `<section class="trainers pt-20 pb-48">`

- Defines the trainers section of the webpage.
- Adds padding at the top and bottom for spacing (`pt-20 pb-48`).

#### Heading and Description

- `<div class="heading-container flex flex-wrap justify-center text-center mb-24">`

  - Contains the heading and description for the trainers section.
  - Centers the content both horizontally and vertically (`flex flex-wrap justify-center text-center`).
  - Provides a maximum width of 6/12 on large screens (`lg:w-6/12`).
  - Adds margin at the bottom (`mb-24`).

- `<h2 class="text-4xl font-semibold uppercase">Meet our Trainers</h2>`

  - Displays a bold uppercase heading with a font size of 4xl.
  - Describes the purpose of the section.

- `<p class="text-lg leading-relaxed m-4 text-gray-600">`

  - Presents a medium-sized paragraph text with a relaxed line height and gray color.
  - Describes the trainers' dedication and purpose.
  - Adds margin on all sides (`m-4`).

#### Trainer Cards

- Trainer Card 1:

  - `<div class="trainer-card w-full md:w-4/12 lg:mb-0 mb-12 px-4 aos-init aos-animate" data-aos="flip-right">`
  
    - Represents the first trainer card.
    - Takes up 4/12 of the width on medium screens (`md:w-4/12`).
    - Applies a flip-right animation on scroll (`data-aos="flip-right"`).

  - `<h5 class="text-xl font-bold">Mr Rogers</h5>`

    - Displays a bold text with a font size of xl, representing the trainer's name.

  - `<p class="mt-1 text-sm text-gray-500 uppercase font-semibold">`
  
    - Presents a small text in uppercase and gray color.
    - Describes the trainer's role.

- Trainer Card 2 and 3:

  - Similar structure and properties as Trainer Card 1, with different trainer names and roles.

Each trainer card showcases an image, the trainer's name, and their role. The section effectively introduces the trainers and their roles to the visitors.

## Contact Section

#### `<section class="contact pb-20 relative block bg-black text-white">`

- Defines the contact section of the webpage.
- Adds padding at the bottom (`pb-20`).
- Sets the background color to black and text color to white.

#### Decorative SVG Element

- `<div class="h-[80px] bottom-auto top-0.5 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20">`

  - Adds a decorative SVG element at the top of the section.
  - Uses absolute positioning to place it above the content.
  - Utilizes an SVG polygon shape for the decorative design.

#### Content Layout

- `<div class="container mx-auto px-4 lg:pt-24 lg:pb-54 pb-20 pt-20">`

  - Contains the contact section content within a container.
  - Provides padding at the top and bottom for spacing (`lg:pt-24 lg:pb-54 pb-20 pt-20`).

- Heading and Description:

  - `<div class="heading-wrapper w-full lg:w-6/12 px-4">`
  
    - Contains the heading and description for the contact section.
    - Provides a maximum width of 6/12 on large screens (`lg:w-6/12`).

  - `<h2 class="text-4xl font-semibold text-white uppercase">Contact Us</h2>`

    - Displays a bold uppercase heading with a font size of 4xl.
    - Indicates the purpose of the section.

  - `<p class="text-lg leading-relaxed mt-4 mb-4">`
  
    - Presents a medium-sized paragraph text with relaxed line height.
    - Describes the purpose of contacting, inviting questions, membership inquiries, or trainer communication.

- Form Container:

  - `<div class="form-container w-full lg:w-6/12 px-4 mt-20">`

    - Contains the contact form within a container.
    - Takes up a maximum width of 6/12 on large screens (`lg:w-6/12`).

  - Form Fields:

    - `<input type="text" ... placeholder="Full Name">`
    
      - Provides an input field for the user's full name.

    - `<input type="email" ... placeholder="Email">`
    
      - Provides an input field for the user's email address.

    - `<textarea ... placeholder="Type a message..."></textarea>`
    
      - Provides a textarea for the user to type their message.

    - `<button ...>Send Message</button>`
    
      - Represents a button to submit the form.
      - Background color changes to gray-900 when active.
      - Displays a shadow on hover.
      - Triggers a send message action when clicked.

This section allows users to easily contact the website, providing a clear form layout for communication.

## Footer Section

#### `<footer class="relative bg-gray-300 pt-8 pb-6">`

- Defines the footer section of the webpage.
- Sets the background color to gray (`bg-gray-300`).
- Adds padding at the top and bottom (`pt-8 pb-6`).

#### Decorative SVG Element

- `<div class=" h-[80px] bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20">`

  - Adds a decorative SVG element at the top of the footer.
  - Uses absolute positioning to place it above the content.
  - Utilizes an SVG polygon shape for the decorative design.

#### Social Media Links

- `<h4 class="text-3xl font-semibold">Follow us on Social Media</h4>`

  - Displays a bold heading indicating social media presence.

- `<div class="icon-wrapper mt-6">`

  - Contains social media icons with buttons for Twitter, Facebook, Dribbble, and GitHub.
  - Each button has a white background, shadow, and specific icon from Font Awesome.
  - Icons change color on hover.
  - Provides a visually appealing way for users to connect on social media platforms.

#### Copyright Information

- `<div class="flex flex-wrap items-center md:justify-between justify-center">`

  - Aligns content in a flex container with justified alignment.
  - Contains copyright information centered on medium-sized screens (`md:justify-between`).

- `<p class="text-sm text-gray-600 font-semibold py-1">`

  - Displays a small-sized text in gray, indicating the copyright notice.
  - Specifies the website ownership and copyright year.

This section enhances user engagement by providing links to social media platforms and conveying copyright information in a visually appealing manner.

## Animate on Scroll (AOS)
The AOS library is used to add scroll-based animations to various elements on the page.

- Elements with `data-aos` attributes have animations applied.
- The AOS library is initialized with specific settings for delay and duration.

Feel free to customize this landing page for your needs. Enjoy coding!
