# Project: Landing Page

## Introduction

For this assignment I created an entire web page from scratch. The objective was to replicate the Full Design provided, using the suggested Colors and Fonts.
Both the design and style originals can be found in the `img` folder.

- [Full Design](https://github.com/thaysmartinez/odin-landing-page/blob/main/img/full-design.png)
- [Color and Fonts](https://github.com/thaysmartinez/odin-landing-page/blob/main/img/colors-and-fonts.png)

## Concepts applied

The Landing Page website has four main sections, as well as a header and a footer.

I tackled the project by creating one section at a time, starting from the header.

For each section, I begun by creating the HTML and then styled it as close to the design as possible. As soon as I was satisfied with the result, I moved on to the next section.

Besides HTML, I used CSS to apply custom styles, heavily relying on the Flexbox layout to arrange groups of items in the page.

## Struggles

### The Flexbox Layout Mode

There are a few core concepts in the Flexbox Layout mode that I struggled with while developing this project:

- The Flex Alignment: more specifically alignment of elements with `flex-direction: column;`
- Growing and Shrinking (flex-grow, flex-shrink, flex-basis)

Although there are other layout modes to learn, the Flexbox model is extremely useful for arranging items vertically and horizontally, so I'll definitely spend more time practicing these concepts.

### When it comes to CSS:

- CSS Selectors: I couldn't figure out how to give better names for element classes and organize the class selectors that share the same declaration(s)
- CSS Cascading: how to write a clean and efficient CSS code that reduces repetition, avoids declaration overwriting and it's easier to maintain and scale (e.g. change of color pallete)

### Slow page load:

- After publishing the project to my GitHub, I noticed that the page load was painfully slow. The reason was because I loaded images in high resolution. This was easily fixed by resampling all the images.

## Images used

To avoid any problems with copywright, I used my own images. As a passionate photographer, I have thousands of photos of my dog, Nina Simone, so it was not a problem to find high resolution images for this project.

## Final thoughts

There are simpler ways to style web pages by using common CSS Frameworks like Bootstrap or Tailwind CSS.

Although these provide advanced features and allows faster and convenient web development, writing CSS code from scratch is the best approach to learn core concepts as a beginner in Web Development.
