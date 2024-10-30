# Advanced Slider Animated Website Design

This project showcases a visually appealing, animated slider for a modern website design. Each slide highlights unique backgrounds and descriptions for various travel destinations, transitioning through smooth animations and circular elements. This design can be used for travel portfolios, landing pages, or interactive image galleries.

## Features

- **Full-Screen Animated Backgrounds**: Each slide displays a full-screen background image with layered circle animations that add depth to the user experience.
- **Seamless Transitions**: CSS animations for images, text, and background circles ensure smooth and visually engaging transitions between slides.
- **Interactive Navbar**: A fixed, responsive header includes an elegant navbar with hover effects for a seamless navigation experience.
- **Rotating Control Button**: A rotating button in the bottom right corner enables users to cycle through slides, triggering animations as each new slide appears.
- **Responsive Design**: The layout adapts to various screen sizes, ensuring usability across desktops, tablets, and mobile devices.
- **Text Animations**: Each slide features animated location and country text with unique transition effects for a polished, modern look.

## Technologies Used

- **HTML5**: Provides the structural layout of the website.
- **CSS3**: Responsible for styling, responsive layout, and animations.
- **JavaScript (ES6)**: Adds functionality for slide rotation, animation controls, and interactivity.
- **Boxicons**: Icon library used for the rotating button icon, enhancing the UI without additional images.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/advanced-slider-animated-website.git
   ```

2. **Navigate to the Project Folder**:

   ```bash
   cd advanced-slider-animated-website
   ```

3. **Open the Project**:
   Open `index.html` in your preferred browser to view the project.

## Usage

1. **Navigating Slides**:

   - Click the **Rotate** button on the bottom-right corner to cycle through each slide.
   - Each click triggers the background transition, rotating to display the next location with its animated text description.

2. **Exploring Header Links**:
   - The header links (Home, About, Services, Contact) are styled with hover effects and provide a sleek navigation experience. You can add content to these sections as needed.

## Customization

This project is highly customizable. Below are some common customizations:

### 1. Adding New Slides

- To add more slides, duplicate any `<div class="bg-slide">` section in `index.html`.
- Update the `img` source and text content within each new slide for unique locations.

### 2. Changing Images

- Replace `img1.jpg`, `img2.jpg`, etc., with your desired images. Add new image files to the project directory and update `src` paths accordingly.

### 3. Modifying Animations

- **Transition Timing**: Adjust animation timing and delays in `style.css` under `.bg-slide .circle img`, `.content-text h1`, and `.content-text h2` for faster or slower animations.
- **Animation Effects**: Customize the effects by editing `transform`, `scale`, and `opacity` values within CSS for each circle and text element.

### 4. Adjusting Layouts

- Use media queries in `style.css` to further refine layout adjustments for specific screen sizes.
- Customize circle sizes and positions by modifying `.circle.large`, `.circle.small`, and `.circle.bg` properties for distinct looks.

### 5. Changing Colors

- Update colors for text, backgrounds, and other elements in `style.css` as desired. For example, modify the `color` property under `.navbar a`, `.rotate-btn`, and `.content-text h1`.

## JavaScript Overview

The main JavaScript functionality is located in `app.js`:

- **Slide Control**: The `rotateBtn` click event cycles through the slides by removing the `active` class from the current slide and adding it to the next.
- **Animation Triggering**: Classes such as `active` and `after-active` control animations by triggering CSS transitions on images and text.
- **Looping Slides**: After the last slide, the function resets the index to loop back to the first slide.

## Contributing

If you'd like to contribute to this project, please feel free to fork the repository and submit a pull request. Contributions for improved animations, bug fixes, and new features are always welcome!

## License

[MIT License](LICENSE) - This project is open-source and free to use under the MIT License.

---

This expanded README should offer clear guidance for users and contributors alike, along with easy-to-follow steps for setup and customization.
