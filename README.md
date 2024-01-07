# Leonardo Lerma's Resume

Welcome to the repository of my professional resume. As a Full-Stack Software Engineer, this document is a comprehensive overview of my skills, experiences, and educational background. This resume is also accessible live at [leolerma.com](https://leolerma.com).

## Overview

This resume reflects my journey in the field of software development, detailing my professional experiences, skills, educational background, and other accomplishments.

## Structure

The resume is structured as follows:

- **Header**: Contains my name and contact information.
- **Professional Summary**: A brief introduction to my professional persona and key skills.
- **Work Experience**: Detailed descriptions of my roles and responsibilities in previous and current positions.
- **Education**: Academic qualifications and any relevant certifications or training.
- **Skills**: A list of technical and soft skills.
- **Interests**: A glimpse into my personal interests and hobbies.

## How to Navigate

- The resume is presented in HTML format for easy viewing in any web browser.
- Styles and layout are defined in an accompanying CSS file.

## Viewing the Resume

To view the resume:

1. Clone this repository to your local machine using `git clone`.
2. Open the HTML file in any web browser to see the formatted resume.

## Live Access

You can view the live version of my resume at [leolerma.com](https://leolerma.com). The website is hosted on AWS and is updated automatically using a CI/CD pipeline.

## CI/CD Pipeline

The website is automatically built and deployed using GitHub Actions whenever changes are pushed to the `main` branch. Here’s an overview of the pipeline:

- **Trigger**: The pipeline triggers on every push to the `main` branch.
- **Build and Deploy Steps**:
  - The code is checked out.
  - AWS CLI is set up for interactions with AWS services.
  - Files are synced to an S3 bucket (excluding unnecessary files like `.git`, `.github`, and `README.md`).
  - The CloudFront cache is invalidated to reflect the latest changes immediately.

### Note on AWS Secrets
The pipeline uses GitHub Actions secrets for AWS credentials, ensuring sensitive information is securely managed and not exposed in the code.

## Viewing and Contributing

- To view the resume, visit [leolerma.com](https://leolerma.com) or clone this repository.
- While this is a personal document, feedback and suggestions are always welcome. If you have any recommendations or notice any issues, please feel free to open an issue or submit a pull request.

## Contact

- LinkedIn: [Leo Lerma] (https://www.linkedin.com/in/leonardo-lerma/)

Thank you for exploring my professional background. I look forward to any opportunities for collaboration or professional growth.
