# Contact Form Application - EZ Labs Assignment

A responsive single-page contact form application built with ReactJS and integrated with the Vernan Backend API.

## Features

- ✅ Responsive design for multiple devices (480p, 720p, 1080p, iPad, MacBook)
- ✅ Form validation (empty fields and email validation)
- ✅ API integration with POST request
- ✅ Success message display on form submission
- ✅ Clean and modern UI based on Figma design

## Technologies Used

- ReactJS
- Tailwind CSS
- Fetch API

## API Information

- **Server Link**: https://vernanbackend.ezlab.in
- **Endpoint**: /api/contact-us/
- **Method**: POST
- **Required Fields**: name, email, phone, message

## Installation

1. Clone the repository:
```bash
git clone 
cd contact-form-app
```

2. Install dependencies:
```bash
npm install
```

3. Run the application:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Responsive Breakpoints

- 480p (Mobile View)
- 720p
- 1080p
- 2732x2048 (iPad)
- 1440x823 (MacBook)

## Validation Rules

1. Empty form submission is not allowed
2. Email validation at front-end
3. All fields are required
4. Success message "Form Submitted" displays on successful submission (200 response)

## Build for Production
```bash
npm run build
```

## Postman Collection

Import the `postman_collection.json` file into Postman to test the API.

