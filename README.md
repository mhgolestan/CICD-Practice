# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course, featuring a comprehensive CI/CD pipeline with GitHub Actions, including automated testing, deployment, and Discord notifications.

## Technology Stack

### Frontend
- React 18.2.0
- React Router DOM 6.21.1
- Webpack 5.89.0 for bundling

### Backend
- Express 4.18.2
- Node.js

### Testing
- Jest 29.7.0 for unit testing
- React Testing Library 14.1.2 for component testing
- Playwright 1.54.2 for end-to-end testing

### Development Tools
- ESLint 8.56.0 for code linting
- Babel for JavaScript compilation
- Webpack Dev Server for development environment

## Features
- Automated CI/CD pipeline with GitHub Actions
- Automated testing and code quality checks
- Automated deployment
- Version management and release tagging
- Discord notifications for build status
- Health check monitoring
- Production and development environments

## Commands

Start by running `npm install` inside the project folder

- `npm start` - Runs the webpack dev server in development mode
- `npm run build` - Creates a production build
- `npm run start-prod` - Runs the production build
- `npm test` - Runs unit and component tests
- `npm run test:e2e` - Runs end-to-end tests with Playwright
- `npm run eslint` - Runs ESLint for code quality checks

## CI/CD Pipeline

The project includes a comprehensive GitHub Actions pipeline that handles:
- Automated testing
- Code quality checks
- Automated deployments
- Version bumping and release tagging
- Discord notifications for build status
- Health check monitoring

## Repository Setup

Fork this repository to complete the course exercises. The main branch is protected and requires passing CI checks before merging.