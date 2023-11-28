### User Story

```
As a software developer, I will have  to create a porfolio with my experience as a web developer, my work and how I can be contacted.
```

### Acceptance Criteria

When the page is loaded the page presents your name, a recent photo or avatar, and links to sections about you, your work, and how to contact you
When one of the links in the navigation is clicked then the UI scrolls to the corresponding section
When viewing the section about your work then the section contains titled images of your applications
When presented with the your first application then that application's image should be larger in size than the others
When images of the applications are clicked then the user is taken to that deployed application
When the page is resized or viewed on various screens and devices then the layout is responsive and adapts to my viewport

## What I have applyed

1. I initiated this page by employing a header as the initial HTML element tag. Within this header, I've utilized a list containing links that direct users to specific sections on the page by targeting their respective IDs.

2. Following the header, the initial section of the page showcases several details about myself as an individual, along with my experience in web development. This section comprises two divs: one enveloping the "About Me" paragraph and the other containing two <p> elements housing all the content. Inside the second div, the <p> elements were arranged side by side using flexbox. I also gave the secind div a border left to separate it form other content.

3. The subsequent section revolves around my past work and projects. Leveraging the grid layout, I've arranged the first image to occupy the full width, while the other four images form two equal columns below the first picture. Furthermore, clicking on these images redirects users to separate pages housing each project, achieved through links with a target attribute set to open in a new page.

4. Last Section is how I can be contacted also a link was added to direct the user to my GitHub account, as previousle I have used the same way to align the items on the page.

5. To ensure my portfolio remains visually appealing on smaller screens without disrupting the CSS layout, I've incorporated media queries with a breakpoint set at 600px. These media queries activate adjustments within the CSS when the screen size falls below 600px, allowing for a more optimized display on smaller devices.



   ![porfolio](https://github.com/IIosub/ioana-iosub-portfolio/assets/114613610/f0ce19f2-4a75-4790-9ee9-259f9ed5b506)


## -This is a front-end bootcamp challenge-
