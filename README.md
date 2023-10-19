# Parallax Effect Web Page
This project demonstrates the parallax effect using HTML and CSS. Parallax scrolling creates an illusion of depth by moving different layers at different speeds as the user scrolls down the page. In this example, it's used to create a dynamic and immersive storytelling experience.

## Technologies Used
**HTML5**: Used for structuring the web page content.

**CSS3**: Utilized for styling and creating the parallax effect.

**Images**: Background and foreground images to create the parallax layers.

## How Parallax Effect Works
Parallax scrolling is a technique where different elements on a webpage move at different speeds as the user scrolls down or up the page. This creates an illusion of depth and adds a dynamic, interactive element to the user experience.

In this project, the parallax effect is achieved using two main layers: the background and the foreground.

### HTML Structure:

The wrapper div contains the entire content and sets the perspective property to enable 3D perspective for child elements.
Inside the wrapper, there is a container div containing two images: background and foreground.
The heading "ADVENTURE" is placed inside the container div, creating a visually appealing focal point.

### CSS Styles:

The wrapper has a perspective property set to create a 3D effect. This property determines how intense the 3D effect is when scrolling.

The container div is styled with position: relative and transform-style: preserve-3d. This enables 3D transformations for its child elements.

The background and foreground images are positioned absolutely, covering the entire container. They have different transform properties applied, making them move at different speeds.

The transform: translateZ(-40px) scale(5); property on the background class moves it closer to the viewer (negative Z-axis) and scales it up, creating a slower scrolling effect.

The transform: translateZ(-20px) scale(3); property on the foreground class moves it closer to the viewer but not as much as the background, creating a faster scrolling effect.

The heading "ADVENTURE" is absolutely positioned with a large font size and a text shadow, creating a bold and clear visual element on the page.

As the user scrolls, the different layers (background and foreground) move at different speeds due to their translateZ and scale properties. This disparity in movement creates the parallax effect, making the background appear to move slower than the foreground, producing a sense of depth and immersion.

Additionally, the project includes sections with different background images (bg1, bg2, bg3) and corresponding headings and texts. These sections follow a similar principle of using parallax scrolling, giving the illusion of depth and enhancing the overall user experience.

## How to Use

Clone the repository and open the index.html file in your web browser to view the parallax effect in action. The scrolling will reveal different layers of images and text, creating a visually appealing experience.

## Features
**Parallax Effect**: Background and foreground images move at different speeds as the user scrolls, creating a 3D effect.

**Section Content**: There are sections with headings, texts, and images related to different adventure activities.

## Structure
**Wrapper**: The main container with a perspective property to enable 3D perspective for child elements.

**Container**: Contains background and foreground images along with the heading "ADVENTURE" creating the parallax effect.

**Sections**: Each section represents a different adventure activity with a background image, heading, and text.

## Contributing
Pull requests and issues are welcome. For major changes, please open an issue first to discuss what you would like to change.
