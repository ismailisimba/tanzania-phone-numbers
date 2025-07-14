

# Tanzania Carrier Lookup

[![Website](https://img.shields.io/badge/Website-Live%20Demo-brightgreen)](https://ismailisimba.github.io/tanzania-phone-numbers/)

A simple, fast, and self-contained web tool to identify the mobile network operator associated with a Tanzanian phone number prefix. It is based on the data published in the Tanzania Communications Regulatory Authority (TCRA) National Numbering Plan from June 2020.

Built with pure HTML, CSS, and JavaScript, this project is lightweight, has zero dependencies, and is perfectly suited for deployment on services like GitHub Pages.

## Live Demo

**Check it out here: [https://ismailisimba.github.io/tanzania-phone-numbers/](https://ismailisimba.github.io/tanzania-phone-numbers/)**



## Features

-   **Single-File Project:** All code is in a single `index.html` file for ultimate simplicity and portability.
-   **Intelligent Input Handling:** Correctly processes phone numbers in various formats, including `07...`, `+255...`, `255...`, with or without spaces.
-   **Instant Feedback:** Provides clear and color-coded messages for successful lookups and errors.
-   **Responsive Design:** The interface is clean and usable on both desktop and mobile devices.
-   **Zero Dependencies:** Runs directly in any modern browser with no need for external libraries or frameworks.
-   **Official Data Source:** All carrier prefix data is sourced directly from the TCRA's official 2020 numbering plan document.

## ⚠️ Important Disclaimer: Number Portability

This tool identifies the **original, assigned carrier** for a number's prefix according to the national numbering plan.

Due to Mobile Number Portability (MNP) in Tanzania, a subscriber can switch carriers (e.g., from Vodacom to Tigo) while keeping their original phone number (e.g., one starting with `075...`). This tool **cannot** detect if a specific number has been ported to a different network. It only reports the carrier that the prefix was originally assigned to.

## Data Source

The carrier assignments used in this tool are taken from **Table 6: ‘find me anywhere’ Assignments** in the following document:

-   **Document:** National Numbering Plan (Updated June, 2020)
-   **Authority:** Tanzania Communications Regulatory Authority (TCRA)

## How to Use

### Online

1.  Navigate to [the live demo site](https://ismailisimba.github.io/tanzania-phone-numbers/).
2.  Enter a Tanzanian mobile number in the input field.
3.  Click the "Check" button or press Enter.
4.  The assigned carrier for that number's prefix will be displayed.

### Running Locally

Since this is a self-contained project, running it locally is extremely simple:

1.  Clone the repository:
    ```sh
    git clone https://github.com/ismailisimba/tanzania-phone-numbers.git
    ```
2.  Navigate into the project directory:
    ```sh
    cd tanzania-phone-numbers
    ```
3.  Open the `index.html` file directly in your web browser.

That's it!

## Technology Stack

-   **HTML5:** For the page structure.
-   **CSS3:** For styling, using Flexbox for layout and custom properties for theming.
-   **JavaScript (ES6+):** For the core lookup logic and DOM manipulation.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
