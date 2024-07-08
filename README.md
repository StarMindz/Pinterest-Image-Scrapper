# Image Scraping from Pinterest

This repository contains a script for scraping images from Pinterest based on a list of search terms. This script is useful for gathering image datasets for computer vision applications, machine learning training, and general AI model training.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation
To use the script, you need to have Python and the following libraries installed:

- `selenium`
- `selenium-stealth`
- `pillow`
- `requests`

You can install these dependencies using pip:

```bash
pip install selenium selenium-stealth pillow requests
```
Ensure you have the Chrome browser installed and the appropriate version of ChromeDriver for your browser version.

## Usage
- Clone this repository:
  ```bash
  git clone https://github.com/your-username/Image_Scrapping.git
  ```
  ```bash
  cd Image_Scrapping
  ```
- Update the base_dir variable in the script to specify the directory where you want to save the images.
- Run the script:
  ```bash
  python Image_Scrapping.ipynb
  ```
- The script will create directories for each search term specified in the nigerian_dishes list and download the specified number of images into these directories.

## Script Description
The script includes functions to:
- Prepare a Selenium WebDriver instance.
- Download images from Pinterest.
- Handle scrolling and clicking elements to load more images.
- Save images to the specified directory.

## Features
- Automatic Directory Creation: Creates a folder for each search term.
- High-Quality Image Scraping: Option to scrape high-quality images.
- Customizable Search Terms: Easily modify the list of search terms.
- Error Handling: Handles errors during image download and page interactions.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
- Fork the repository.
- Create your feature branch: git checkout -b feature/your-feature-name
- Commit your changes: git commit -m 'Add some feature'
- Push to the branch: git push origin feature/your-feature-name
- Open a pull request.

## License
This project is licensed under the ]MIT License](/LICENSE) - see the LICENSE file for details.
