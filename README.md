## URL Shortener Project Documentation

### 1. Introduction
The URL Shortener project simplifies the conversion of long URLs into shortened, more manageable links. It leverages Node.js to streamline the sharing of URLs across various platforms and applications.

### 2. Project Overview
The URL Shortener project comprises the following components:
- **Backend:** Utilizes Node.js, Express.js and MongoDB to handle URL shortening requests, redirection, and analytics tracking.
- **Frontend:** Provides an interface for users to input long URLs and generate corresponding short links, built using HTML, CSS, and JavaScript.
- **Database:** Stores mappings between original URLs and their corresponding short codes, along with tracking analytics data using MongoDB.
- **API:** Exposes RESTful endpoints for URL shortening, link redirection, and analytics data retrieval.

### 3. Installation
To install and run the URL Shortener project locally, follow these steps:
1. **Repository:** `git clone https://.com/yash9111/UrlShort.git/`
2. **Navigate to Project Directory:** `cd urlener`
3. **Install Dependencies:** `npm install`
4. **Configure Variables:** Set environment variables for `PORT`, `MONGODB_URI`, and `BASE_URL` as requirements.
5. **Start the Server:** `npm start`
6. **Access the Application:** Visit [http://localhost:3000](http://localhost:3000)

### 4. Usage
Once the project is running, users can:
- Access the frontend interface via a web browser.
- Input long URLs into the provided field and generate short links with a click.
- Copy and share the generated short links as needed.
- Utilize API endpoints for programmatic access to URL shortening, link redirection, and analytics data retrieval.

### 5. Configuration
The URL Shortener project requires the following environment variables to be configured:
- **PORT:** The port on which the server listens for incoming requests.
- **MONGODB_URI:** The connection URI for the database.
- **BASE_URL:** The base URL for generated short links.

Ensure these variables are set appropriately before running the project.

### 6. API Reference
The URL Shortener project exposes the following API endpoints:
- **POST /shorten:** Shortens a long URL and returns the corresponding short link.
- **GET /:shortUrl:** Redirects users to the original URL associated with the provided short code.

