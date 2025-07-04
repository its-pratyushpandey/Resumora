# AI Resume Builder

## Overview
AI Resume Builder is a modern web application designed to help users create professional resumes effortlessly using AI-powered tools. The application is built with React, Vite, and TailwindCSS, ensuring a responsive and user-friendly experience.

## Features
- AI-powered resume generation
- Customizable themes and layouts
- Easy sharing and downloading options
- Responsive design for all devices

## Technologies Used
- React
- Vite
- TailwindCSS
- Clerk for authentication
- Strapi for backend API

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/its-pratyushpandey/AIResumeBuilder.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AIResumeBuilder
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables
Create a `.env` file in the root directory and add the following variables:
```properties
VITE_CLERK_PUBLISHABLE_KEY=your_actual_clerk_publishable_key
VITE_GOOGLE_AI_API_KEY=your_actual_google_ai_api_key
VITE_STRAPI_API_KEY=your_actual_strapi_api_key
VITE_API_BASE_URL=your_actual_strapi_base_url
VITE_BASE_URL=http://localhost:5173
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
