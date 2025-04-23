# Eric Tuyishime | Full-Stack Developer Portfolio

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-blue?logo=github)](https://github.com/eric2003tu/port-folio)
[![License](https://img.shields.io/badge/License-None-lightgrey)](./LICENSE) <!-- Update if you add a license -->

## 1. Project Title and Description

This is my personal portfolio website, designed to showcase my skills, experience, and projects as a Full-Stack Developer and Telecommunications & ICT Specialist. It's built to be responsive, visually appealing, and informative, providing a comprehensive overview of my capabilities and accomplishments.

## 2. Features and Functionality

*   **Responsive Design:**  The website is fully responsive and adapts seamlessly to different screen sizes, ensuring a great user experience on desktops, tablets, and mobile devices.
*   **Navigation:** A fixed navigation bar provides easy access to different sections of the portfolio: Home, About, Experience, Education, Projects, and Contact.
*   **Hero Section:**  A visually engaging hero section introduces me and highlights my key skills and areas of expertise.  Includes buttons for direct contact, viewing projects, and downloading my CV.
*   **About Section:**  Provides a detailed introduction, my background, and a list of my technical skills presented using tags.
*   **Experience Section:**  Showcases my professional experience, including roles, companies, and key responsibilities.
*   **Education Section:**  Highlights my educational background, including degrees, institutions, and relevant coursework.
*   **Projects Section:**  Features a selection of my projects, each with a description, technologies used, and links (if applicable).
*   **Contact Section:**  Includes my contact information (email, phone, location) and a contact form for visitors to send me messages directly.

    *Contact Form Validation: The contact form includes client-side validation to ensure users enter valid information before submission.

    *Loading Spinner: A loading spinner indicates when the form is submitting.

    *Submission Confirmation: An alert message appears upon successfully submission of contact form
*   **Social Media Links:** Includes links to my GitHub, LinkedIn, and Twitter profiles.
*   **Downloadable CV:** A button allows visitors to download my CV in PDF format ("Eric\_Tuyishime\_CV (3).pdf").
*   **Animations:** The elements of the page fade in as the user scrolls down the page using javascript.
*   **Dynamic NavBar:** The navbar changes its appearance as the user scrolls the page using javascript.

## 3. Technology Stack

*   **HTML:**  The structure and content of the website.
*   **CSS:** Styling and layout, including custom CSS variables and media queries for responsiveness.
*   **JavaScript:**  Interactive elements, navigation, and animations.
*   **Font Awesome:** Icons used throughout the website.
*   **External Libraries:**
    *   `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css` (Font Awesome)

## 4. Prerequisites

To run this website locally, you'll need:

*   A web browser (e.g., Chrome, Firefox, Safari).
*   A code editor (e.g., VS Code, Sublime Text).

## 5. Installation Instructions

No installation is required to view the live website. However, if you want to run it locally:

1.  Clone the repository:
    ```bash
    git clone https://github.com/eric2003tu/port-folio.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd port-folio
    ```
3.  Open `index.html` in your web browser.

## 6. Usage Guide

Simply open the `index.html` file in your web browser to view the portfolio website.  Use the navigation bar to explore the different sections.

## 7. API Documentation (if applicable)

*   **Contact Form Endpoint:**

The contact form uses the following API endpoint to send messages:

*   **Endpoint:** `https://backend-qnfm.onrender.com/api/send`
*   **Method:** `POST`
*   **Headers:**
    ```json
    {
        "Content-Type": "application/json"
    }
    ```
*   **Body:**

A JSON object containing the following data:

    ```json
    {
        "name": "Your Name",
        "email": "Your Email",
        "subject": "Subject of the message",
        "message": "Your Message"
    }
    ```
*   **Response:**

    On success, the server returns a JSON response. In case of errors, an error message is returned.

## 8. Contributing Guidelines

Contributions are welcome! To contribute to this project:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Submit a pull request to the `master` branch of the original repository.

## 9. License Information

This project is currently not licensed. All rights are reserved by Eric Tuyishime.
Specify the license if you add. For example:

```
This project is licensed under the [MIT License](LICENSE).
```

## 10. Contact/Support Information

For any questions, feedback, or support, please contact me:

*   **Email:** erictuyishime574@gmail.com
*   **Phone:** +250 783 687 408

You can also connect with me on:

*   [GitHub](https://github.com/eric2003tu)
*   [LinkedIn](https://www.linkedin.com/in/eric-tuyishime-3444b3358/)
*   [Twitter](https://twitter.com/yourusername)

```
