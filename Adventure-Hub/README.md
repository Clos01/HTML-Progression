# Straw Hat Pirates Showcase

## Project Description
This project is an HTML5 webpage that highlights the famous Straw Hat Pirates from the One Piece universe. The page includes detailed sections about each crew member, their roles, and a brief background. You'll practice using semantic HTML elements, linking, media attributes, and image handling while making the page engaging and accessible.

## Installation
Simply open the `index.html` file in your browser to view the character showcase. Ensure that your `images/` directory contains all character images and that file paths are correctly set.

## Usage
The webpage includes the following:

1. **Introduction**: A welcoming message in a `<header>` element introducing the Straw Hat Pirates and a brief summary of their adventures.
2. **Character Profiles**: Each character is wrapped in an `<article>` element with:
    - **Title (`<h2>`)**: Character’s name.
    - **Image (`<img>`)**: A photo of the character with proper `src`, `alt`, `width`, and `height` attributes.
    - **Description (`<p>`)**: A brief story of the character, their abilities, and role on the crew.
    - **Link to More Info (`<a>`)**: Links to an external source for more details using the `href` attribute (e.g., Wikipedia).
    - **Downloadable Content**: A download link using the `download` attribute, such as wallpapers of the character.
3. **Navigation**: Use ID-based links (`#`) to allow users to jump directly to each character’s section using a `<nav>` element at the top.

## Features
- **Semantic HTML**: Organized with `<header>`, `<section>`, `<article>`, and `<footer>`.
- **Interactive Navigation**: A table of contents using `<nav>` that allows quick navigation between character profiles.
- **Accessibility**: Includes `alt` text for all images, maintaining a logical heading structure for screen readers.
- **Responsive Design**: Uses media queries to optimize the layout for mobile devices.
- **Download Attribute**: Allows users to download wallpapers or artwork of their favorite characters.

## Character List Example:
### Monkey D. Luffy (`<article id="luffy">`)
- **Title**: Captain
- **Image**: `src="images/luffy.jpg"` with `alt="Monkey D. Luffy smiling"`
- **Description**: Luffy is the fearless captain of the Straw Hat Pirates, known for his ambition to become the Pirate King.
- **Link**: [Learn more about Luffy](#)
- **Download**: `<a href="images/luffy-wallpaper.jpg" download="Luffy-Wallpaper">Download Wallpaper</a>`

### Roronoa Zoro (`<article id="zoro">`)
- **Title**: Swordsman
- **Image**: `src="images/zoro.jpg"` with `alt="Roronoa Zoro holding his three swords"`
- **Description**: Zoro is a master swordsman and the first mate of the Straw Hat Pirates, known for his unwavering dedication to his captain.
- **Link**: [Learn more about Zoro](#)
- **Download**: `<a href="images/zoro-wallpaper.jpg" download="Zoro-Wallpaper">Download Wallpaper</a>`

## Contributing
Feel free to add more characters from One Piece to the page or improve the design! To contribute, fork the repository, add a character profile, and submit a pull request.

## License
This project is licensed under the MIT License.

## Badges
(You can add badges for HTML validation, license, etc., from [shields.io](https://shields.io/)).

## Screenshots and GIFs
Include screenshots of the character showcase or a GIF that demonstrates navigating through the profiles.

## Documentation
Additional documentation on adding new characters or modifying the page can be found in the `docs/` folder.

## Changelog
- **Version 1.0**: Added initial character profiles for Luffy, Zoro, and Nami. Set up navigation and download links.

## Conclusion
This project is a fun way to apply everything you've learned about HTML, from semantic elements to attributes like `href`, `download`, and `media`. It lets you dive into the world of One Piece while practicing web development skills. Enjoy building, and remember to stretch your creativity!