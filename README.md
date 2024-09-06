# Web-Crawler-for-Web-Analysis

This project is a simple web crawler built using Java and Selenium WebDriver. The crawler performs analysis on web pages by counting various elements, capturing screenshots and generates a report. 

## Project Overview

The web crawler performs the following tasks:
1. **Crawl Web Pages**: Navigates through a given web page and its links up to a specified depth.
2. **Capture Screenshots**: Takes screenshots of the web pages visited.
3. **Count Elements**: Counts and reports the number of links, images, forms, and total elements on each page.
4. **Generate Report**: Creates an HTML report with the analysis results and screenshots.

### Key Features
- **Web Page Navigation**: Visits a specified web page and follows links to additional pages.
- **Screenshot Capture**: Saves screenshots of each page visited.
- **Element Counting**: Counts the number of links, images, forms, and total elements on each page.
- **HTML Report**: Generates an HTML file with detailed information about the web pages crawled, including links and screenshots.

### Requirements
- **Java JDK**: Make sure you have Java Development Kit (JDK) installed.
- **Selenium WebDriver**: The project uses Selenium WebDriver to interact with web pages.
- **ChromeDriver**: A compatible version of ChromeDriver for your version of Google Chrome.

### Usage
- The crawler starts with a specified URL and a depth level for crawling.
- It navigates the web pages, captures screenshots, counts elements, and generates an HTML report.

### Example
- The project currently uses the GeeksforGeeks website as an example, but we can replace it with any other website URL of your choice.
