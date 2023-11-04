# Plume

## Overview
Plume is a comprehensive web application designed for birdwatching enthusiasts and ornithologists. It provides a platform where users can share their bird sightings, explore data from other birdwatchers, and access a wealth of information about various bird species through a dedicated bird wiki. The application also features user authentication, profile management, and interactive maps for a rich user experience.

## Features
### 1. **User Authentication:**
   - **Sign Up:** New users can create an account.
   - **Login:** Registered users can log in.
   - **Email Verification:** Validate user email addresses through a verification process.
   - **Password Reset:** Users can reset their passwords through their email.

### 2. **Bird Sighting Data Management:**
   - **Upload Sightings:** Users can upload their bird sighting data along with images and descriptions.
   - **View Sightings:** Explore bird sightings shared by other users.
   - **My Observations:** Users can view and manage their own bird sighting data.

### 3. **Plume Wiki:**
   - **Bird Information:** Access detailed information about various bird species.
   - **User Contributions:** Users can contribute to the bird wiki.

### 4. **Interactive Map:**
   - **Sighting Locations:** View the locations of bird sightings on an interactive map.
   - **Filter Options:** Filter sightings based on various parameters like species, date, etc.

### 5. **User Profile Management:**
   - **Dashboard:** View and manage personal birdwatching data.
   - **Settings:** Manage account settings and preferences.
   - **Profile Picture:** Upload and change profile pictures.

### 6. **Challenges and Subscriptions:**
   - **Participate:** Engage in birdwatching challenges.
   - **Subscribe:** Opt for various subscription plans for additional features.

### 7. **Community and Help:**
   - **Contact:** Users can send help requests or inquiries.
   - **Our Team:** Information about the developers and contributors.

### 8. **Privacy and Terms:**
   - **Privacy Policy:** Detailed information about data usage and privacy.
   - **Terms and Conditions:** Usage terms of the platform.

## Technology Stack
- **Backend:** Java with Spring Boot.
- **Frontend:** Thymeleaf, HTML, CSS, JavaScript.
- **Database:** Choose as per your requirement (e.g., MySQL, MongoDB).
- **Cloud Storage:** Google Cloud Storage.
- **Authentication:** Spring Security.
- **Email Service:** For sending verification and password reset emails.

## Setup and Installation
### Prerequisites
- Java JDK
- Maven
- A suitable IDE (e.g., IntelliJ IDEA, Eclipse)
- Database Server
- Google Cloud Account (for storage services)

### Steps
1. **Clone the Repository:**
   ```
   git clone [repository_url]
   ```
2. **Database Setup:**
   - Create a database and configure the `application.properties` file with your database credentials.
3. **Google Cloud Setup:**
   - Set up a bucket for storing images and configure the credentials in the application.
4. **Build and Run:**
   ```
   mvn clean install
   ```
   ```
   mvn spring-boot:run
   ```
5. Access the application at `http://localhost:8080`.

## Contribution
Contributions, bug reports, and feature requests are welcome! Feel free to check [issues page](#). If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- All contributors and testers who helped to build this application.
- Birdwatchers and ornithologists for their valuable insights.

---
