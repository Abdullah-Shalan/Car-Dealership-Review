# Car Dealership Review

*Full-stack Developer Capstone Project*

## Project Overview

This project is a web application that allows users to explore car dealerships and their reviews.
Built as part of a full-stack developer capstone for my portfolio.
Key goals:

* Display dealerships.
* Let users submit and view reviews.
* Provide a clean UI and solid backend for handling data and authentication (if applicable).
* Serve as a demonstrable end-to-end full-stack project (frontend + backend + database + deployment workflow).

## Features

* Browse list of car dealerships (name, location, other metadata).
* View details of a specific dealership (including reviews & ratings).
* Submit a new review for a dealership (rating, comments, user info).
* Filter or search dealerships by location or name (if implemented).
* Responsive UI (works on desktop and mobile).
* Containerized development and/or deployment (Docker/Docker-Compose).
* CI/CD workflow (GitHub Actions) for build/test/deploy.
* Backend API (REST) for handling dealership & review data.

## Tech Stack

* Frontend: REACT + HTML + CSS + JavaScript
* Backend: Python Django server
* Database: MongoDB
* Containerization: Docker, Kubernetes
* CI/CD: GitHub Actions workflow set up (see `.github/workflows/`)

## Testing

* Unit tests for backend API endpoints.
* Integration tests for database interactions.
* Check CI pipeline (look in `.github/workflows/`) for test job definitions.

## Usage Example

* User goes to homepage → sees list of dealerships.
* Clicks on a dealership → views details + review list.
* User submits a review (rating + comment) → review appears immediately.
* Future feature: filter/search dealerships by city or average rating.
