# CLI Assistant

CLI Assistant is a specialized desktop application designed to streamline social media workflows by leveraging generative AI to craft and publish professional content directly to Facebook Groups. It automates the transition from raw project descriptions to polished, engagement-ready social media posts.

## Key Features

* **AI Content Generation:** Integrates Google Gemini AI to transform raw text into professional Arabic-language posts, featuring automated formatting and emoji integration.
* **Facebook Graph API Integration:** Enables direct publishing to Facebook Groups using secure access tokens and automated HTTP requests.
* **Project Promotion Automation:** Specifically designed to highlight software projects by seamlessly embedding GitHub repository links into generated social media captions.

## Tech Stack

* **Language:** C#
* **Framework:** .NET / Windows Forms (WinForms)
* **APIs:** Google Gemini (GenerativeAI SDK), Facebook Graph API
* **Networking:** HttpClient for RESTful communication

## Getting Started

1. Launch the application and provide your Google Gemini API Key.
2. Enter the target Facebook Group ID and your Facebook Access Token.
3. Input your project description and use the "Generate" function to refine the content via AI.
4. Review the formatted output and click "Post" to publish directly to your group.