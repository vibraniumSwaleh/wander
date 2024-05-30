## About Wander

![Wander Hero Section Image](/img/wander_hero.webp)

This webpage is built with HTML, CSS (preprocessed with Sass), and JavaScript. It features a responsive layout and showcases some of the most popular tours offered by Wander, along with information about the company and positive testimonials from past customers.

## Technologies Used
- HTML
- CSS
- Sass
- JavaScript

## Features
![Wander Feature Section Image](/img/wander_features.webp)

- Responsive design for optimal viewing on different devices.
- Interactive elements like popups for displaying important information.
- Easy-to-customize grid system for layout.

## Installation
1. Clone the repository: `git clone https://github.com/vibraniumSwaleh/wander.git`
2. Navigate to the project directory: `cd wander`
3. Open the index.html file in your web browser.
4. **(Optional) Set up Sass watcher:**
   - If you want to automatically compile Sass changes to CSS during development, run:
     ```bash
     npm run watch:sass
     ```

**Explanation:**

* We added a new step after installing dependencies:
    * `npm run watch:sass`: This command starts a Sass watcher using `node-sass`. It will automatically compile any changes in your `sass/main.scss` file to the `css/style.css` file, making development more efficient.

5. **(Optional) Set up Sass build:**
   - If you want to automatically build Sass files to CSS after development completion, run:
     ```bash
     npm run build:css
     ```

**Explanation:**

* We added a new step to compile Sass to css >> concatenate the output file to icon css file >> add vendor prefixes to the output file from previous process >> compress the file thereafter for production/deployment:

    * `npm run build:css`: This is a single command that automates the entire process of compiling, concatenating, prefixing, and compressing your CSS files. This makes it easier to manage your CSS and ensures that your website is optimized for performance and compatibility.

## Usage
1. Explore the different sections of the website by scrolling or using the navigation links.
2. Click on tour cards to view detailed information.
3. Use the contact form to get in touch with the website owner.

## Contributing
Contributions are welcome! If you'd like to contribute to {index}, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits
- Built by [github.com/vibraniumSwaleh](#).
