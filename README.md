# Theme Generator - Ver 1.0.1

**Theme Generator** is a Python application that allows you to generate WordPress themes from existing websites. It downloads the HTML content, extracts CSS links, downloads CSS files, and generates WordPress theme files based on the provided website URL.

## How it Works

1. **Enter Website URL:**
   - Run the `Theme Generator.exe` application.
   - Enter the URL of the website you want to convert into a WordPress theme when prompted.

2. **Download HTML and CSS:**
   - The application downloads the HTML content from the provided URL.
   - It extracts CSS links from the HTML.

3. **Download CSS Files:**
   - The application downloads CSS files linked in the HTML content.

4. **Generate WordPress Theme Files:**
   - WordPress theme files (`header.php`, `footer.php`, `index.php`, and `style.css`) are generated based on the downloaded HTML and CSS.

5. **View Generated Files:**
   - The generated WordPress theme files are saved in the `wordpress_theme` directory.

6. **Copyright and Exit:**
   - The application prints a copyright notice and GitHub link.
   - Press 'R' to exit the application.
  
## License
      This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](LICENSE) file for details.
