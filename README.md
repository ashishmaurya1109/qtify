Overview
QTify is a song-browsing application built from scratch using ReactJS paired with Material UI and Swiper to deliver a seamless and aesthetic user interface, offering songs from different albums and genres for music lovers.

While building this Micro-Experience, I:

Conducted a thorough analysis of the provided Figma design, successfully identifying and documenting required front-end components.
Created modular UI components including Cards, Carousels, and Buttons optimizing for reusability across various sections of the application.
Implemented an intuitive genre-based song filtering system using a tab component by modifying the one provided by MaterialUI, allowing users to browse songs by their preferred genre effortlessly.
Utilized REST APIs to fetch data served by the backend server
Deployed the website to Vercel

![image](https://github.com/ashishmaurya1109/Qtify/assets/90845953/a1881156-bba7-492e-816c-6c2cfe80f655)
QTify Component Architecture

![image](https://github.com/ashishmaurya1109/Qtify/assets/90845953/c9d88ffe-8438-442f-9ba7-8d49307d883a)
QTify UI (Albums Section)

Component breakdown and building the Navbar and Hero Section
Scope of work
Conducted a thorough analysis of the provided Figma design, successfully identifying and documenting required front-end components
Designed a reusable button component with unique styling, adaptable for various functionalities across the application.
Developed a responsive navigation bar featuring a custom logo, a search component with custom styling, and a feedback button.
Created an eye-catching hero section with promotional content, effectively capturing user interest.
Skills used
ReactJS, Module-scoped CSS, Flexbox, CSS variables

Albums Section
Scope of work
Developed a dynamic, responsive, and reusable Card component with Material-UI integration, featuring custom CSS, efficient data handling, and enhanced user interaction through tooltips and lazy-loaded images.
Implemented and customized a carousel feature using the Swiper library and utilizing custom navigation.
Developed a dynamic Section component capable of dynamically displaying content in both carousel and grid layouts using conditional rendering.
Skills used
ReactJS, Module-scoped CSS, Condition Rendering, Component Reusability, Swiper Library usage, Material UI, Customizing Third-Party Components

Image(s)

![image](https://github.com/ashishmaurya1109/Qtify/assets/90845953/e0bbff1c-8656-4695-8076-0187ecb47cc1)
Top Albums Carousel View (Conditional Rendering)

![image](https://github.com/ashishmaurya1109/Qtify/assets/90845953/5d0065bd-4f3f-45d6-a39d-082e821d853c)
Top Albums Grid View (Conditional Rendering)

Songs Section
Scope of work
Created a reusable Filters component, using Material-UI Tabs for a seamless and interactive filtering experience
Utilized Axios to fetch the genre options and song data served by the backend, and performed error handling for the same.
Implemented conditional rendering logic to display filter options within the Section component exclusively in the Songs section.
Skills used
ReactJS, Module-scoped CSS, API Integration and Data Handling, Condition Rendering, Component Reusability, Customizing Third-Party Components

Image(s)

![image](https://github.com/ashishmaurya1109/Qtify/assets/90845953/2cae7847-d584-4d73-b40c-6162903cf778)
Songs Section reusing the Section component as Albums Section but includes Tab as well

![image](https://github.com/ashishmaurya1109/Qtify/assets/90845953/787c0a1f-0685-4914-a5f2-6fab9d5bd1c1)
Songs Section (now filtered as per Jazz genre)

Deploy the QTify website
Scope of Work
Deployed the Qtify React app to Vercel by importing the project repository from GitHub.
Skills used
Deployment, Vercel

