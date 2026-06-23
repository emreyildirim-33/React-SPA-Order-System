# React SPA Order System

A React-based Single Page Application (SPA) for an interactive food ordering flow.  
The project focuses on React routing, form validation, state lifting, reusable components, API request simulation, and Cypress E2E testing.

## Overview

This project was developed as a hands-on React SPA project to practice building a multi-page ordering experience with client-side routing and form-based user interaction.

The application includes a home page, an order form page, and an order confirmation page.  
Users can select order options, fill in form fields, submit the order, and see the submitted order summary on the confirmation screen.

The main focus of this project is frontend application logic, state management through React, form validation, routing, and testing user flows.

## Tech Stack

- React
- Vite
- JavaScript
- CSS
- React Router
- Axios
- Cypress
- Component-based architecture
- Form validation
- State lifting
- Mock API request handling

## Features

- Single Page Application structure
- Client-side routing between pages
- Home page with order call-to-action
- Interactive order form
- Form validation for required fields
- Multiple selection inputs
- Radio button selection flow
- Notes / text area input handling
- Disabled submit button when form data is invalid
- Order submission flow with API request simulation
- Order confirmation page
- State transfer between order form and confirmation page using state lifting
- Error handling for failed order requests
- Cypress E2E tests for key user flows
- Clean component-based project structure

## Application Flow

```text
Home Page
↓
Order Button
↓
Order Form
↓
Form Validation
↓
Submit Order
↓
Mock API Request
↓
Order Confirmation Page
```

## Main Pages

| Page | Description |
|---|---|
| Home Page | Landing page where the user starts the order process |
| Order Form | Interactive form for selecting order details |
| Order Confirmation | Displays submitted order information after successful submission |

## Form Logic

The order form handles user input and validation logic such as:

- Name input validation
- Size selection
- Multiple ingredient selection
- Notes field
- Submit button enable / disable logic
- Error state management
- Form data state management
- Order payload preparation

## Testing

This project includes Cypress tests for validating important user flows.

Tested areas include:

- Entering text into form fields
- Selecting multiple ingredients
- Submitting the order form
- Checking validation behavior
- Verifying user interaction flow

## Project Structure

```text
src/
 ├── components/
 ├── pages/
 ├── assets/
 ├── App.jsx
 └── main.jsx

cypress/
 └── e2e/
```

## What I Practiced

- Building a React Single Page Application
- Using React Router for client-side navigation
- Managing form state with React
- Passing data between pages with state lifting
- Creating reusable UI components
- Handling form validation and error states
- Sending mock API requests with Axios
- Building a user-friendly order flow
- Writing Cypress E2E tests
- Structuring a frontend project for maintainability

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/emreyildirim-33/React-SPA-Order-System.git
cd React-SPA-Order-System
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

The application will run locally at:

```text
http://localhost:5173
```

## Running Tests

Run Cypress:

```bash
npx cypress open
```

or run tests in the terminal:

```bash
npx cypress run
```

## Notes

This project was built as a frontend-focused React training project.  
The main focus was not building a production food delivery platform, but practicing React SPA architecture, routing, form validation, state management, API request simulation, and Cypress testing.

## Repository

GitHub: https://github.com/emreyildirim-33/React-SPA-Order-System
