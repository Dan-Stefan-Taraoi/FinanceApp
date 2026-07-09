# Personal Financial Web Application

## Overview

This project is a **Personal Financial Web Application** designed to help users track their financial status, including expenses, investments, and overall financial health—similar to apps like Finanzguru. The app provides a user-friendly interface built with Angular and a backend API developed with ASP.NET Core Web API. 

Users can record and monitor their income, expenses, investments, and view detailed reports to better understand their financial situation and make informed decisions.

---

## Features

- Track income, expenses, and investments
- View financial summaries and reports
- Manage multiple accounts and categories
- Secure user authentication and data privacy
- Responsive design for desktop and mobile devices

---

## Initial Setup Instructions

Follow these steps to set up the development environment and run the application locally:

### 1. Create ASP.NET Core Web API Backend

- Use Visual Studio to create a new **ASP.NET Core Web API** project.
- Configure your backend logic, database connections, and API endpoints as needed.

### 2. Install Node.js

- Download and install Node.js from [nodejs.org](https://nodejs.org/).

### 3. Install Angular CLI

Open a terminal or command prompt and run:

```bash
npm install -g @angular/cli
```

This installs the Angular command-line interface globally on your machine.

### 4. Create Angular Project
Navigate to your desired directory and create a new Angular project named finance-app with routing and SCSS styling:

```bash
ng new finance-app --routing=true --style=scss
```
### 5. Add Angular Material
Navigate into the project directory:

```bash
cd finance-app
```
Add Angular Material to your project:

```bash
ng add @angular/material
```
Follow the prompts to choose a theme and set up global typography and animations.
### 6. Run the Application Locally
Start the Angular development server:

```bash
ng serve
```
Open your browser and navigate to http://localhost:4200 to see the running app.

[The last step, running "ng serve," is a command that starts a local development server for your Angular application. When you run "ng serve," Angular compiles your project and hosts it on a local web server, typically accessible at "http://localhost:4200" in your web browser.
Here's what it does in detail:

It compiles your Angular code, including components, styles, and dependencies.
It watches for file changes, so if you modify your code, the server automatically reloads the app.
It serves the app in a local environment, allowing you to test and develop your frontend interface.

So, by running "ng serve," you can see and interact with your Angular app in your browser at "http://localhost:4200" during development. Once you're ready to deploy, you'll build a production version of the app with "ng build" and integrate it with your ASP.NET Core backend.]
