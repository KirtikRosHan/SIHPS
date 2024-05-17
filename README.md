# Smart India Hackathon Workshop
# Date: 17\05\2024
## Register Number: 212221043002
## Name: KIRTIK ROSHAN G.R
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
The E-Waste Facility Locator aims to encourage proper disposal of electronic waste by providing accessible information and incentives for recycling. By combining location services with educational content and reward mechanisms, the platform seeks to promote environmentally responsible behavior and reduce the negative impact of e-waste.
## Proposed Solution
Proposed Solution
User Interface (UI):

Home Page: Welcome message, navigation menu, and search bar for facility locator.
Facility Locator: Input location to find the nearest e-waste facilities.
Educational Pop-ups: Information about e-waste components and their impact.
Device Input Form: Form to input device model details and calculate credit points.
User Dashboard: Tracks points earned and history of disposed devices.
Backend Services:

Location Service: Integrates with mapping APIs to find nearest facilities.
Educational Content Management: Stores and serves educational content.
Device Model Database: Database of device models and associated precious metals.
Credit Points System: Manages user points and rewards.
Database:

User Data: Stores user profiles, location, and points.
Facility Data: Information on e-waste facilities.
Educational Content: Information about harmful components and effects.
Device Data: Details of devices and metal recovery potential.
APIs and Integrations:

Mapping API: For location services (e.g., Google Maps API).
User Authentication API: For user login and management.
Points and Rewards API: Manages credit points and redemption.
## Architecture Diagram
![fbuil-08-1030196-g005](https://github.com/KirtikRosHan/SIHPS/assets/142528873/fffa7c86-b2de-4875-bf36-48cb05e8254f)
## Use Cases
![519793_1_En_7_Fig1_HTML](https://github.com/KirtikRosHan/SIHPS/assets/142528873/86b94a6f-4403-4acf-9510-dc8e074f9754)
## Technology Stack
Frontend:
HTML/CSS: Structure and styling.
JavaScript: Interactive elements.
React.js: Frontend framework.
Bootstrap: UI components.
Backend:

Node.js: Server-side runtime.
Express.js: Web framework for Node.js.
MongoDB: NoSQL database for user and facility data.
RESTful APIs: For communication between frontend and backend.
APIs and Integrations:

Google Maps API: For location services.
Auth0: User authentication and management.
Reward API: Third-party service for managing points and rewards.

## Dependencies

Mapping and Location:

Google Maps API for location services.
Authentication and User Management:

Auth0 for user authentication.
Database:

MongoDB for storing user, facility, and device data.
Educational Content:

Content management system (CMS) for storing and serving educational material.
Points and Rewards:

Integration with a third-party rewards API to manage user points and redemptions.

