# ReHome  -Giving Every Resource a Second Life  
#### A Community Resource Marketplace  

---

## 1. Product Identity

**Product Name:** ReHome  
**Tagline:** Giving Every Resource a Second Life  
**Project Type:** Full-Stack Web Application  
**Domain:** Community Resource Sharing / Marketplace  

**Development Goal:**  
To build a scalable, community-driven platform that enables users to buy, sell, and donate reusable items while promoting sustainability and reducing waste.  

---

## 2. Introduction

In today's world, millions of reusable items such as books, furniture, electronics, household appliances, and clothing remain unused or are discarded even though they are still valuable. At the same time, many individuals, students, families, and organizations actively search for affordable or donated resources but struggle to find trustworthy local sources. Existing online marketplaces primarily focus on commercial buying and selling, while donation platforms and community resource sharing remain fragmented.

ReHome is a community-driven resource marketplace that helps every useful resource find its next owner instead of becoming waste. The platform enables users to buy, sell, and donate reusable items while discovering resources based on their preferred location across India. By extending the lifecycle of everyday resources, ReHome promotes affordability, sustainability, and stronger community connections.

---

## 3. Problem Statement

Despite the growth of online marketplaces, there is still no unified platform that effectively combines buying, selling, and donating reusable resources within a trusted community-driven environment. Many people own items that are no longer useful to them but remain valuable to others. Unfortunately, these resources often remain unused or are discarded due to the lack of an accessible and reliable platform.

At the same time, individuals searching for affordable second-hand products or looking to donate items to people or organizations in need often struggle to identify trustworthy sources. Existing solutions often focus on only one aspect of resource exchange, requiring users to switch between multiple platforms.

The problem is not the lack of resources—it is the lack of connections between people who have them and people who need them.

ReHome aims to bridge this gap by creating a single platform that encourages responsible reuse and community-driven resource sharing.

---

## 4. Proposed Solution

ReHome provides a unified community-driven platform where users can buy, sell, and donate reusable items through a single application. The platform connects people who have resources with those who need them, making the exchange process simple, accessible, and location-based.

Users can create verified accounts, list items with images and descriptions, browse products using category and location filters, and directly contact sellers or donors through their preferred contact method. By combining second-hand commerce and donations within one platform, ReHome encourages responsible resource sharing, reduces waste, and promotes sustainable living.

The platform is designed with a modular architecture, allowing future enhancements such as AI-powered product condition assessment, personalized recommendations, in-app messaging, digital payments, and delivery integration.

---

## 5. Objectives

The primary objectives of ReHome are:

- Build a trusted platform for buying, selling, and donating reusable resources.
- Encourage sustainable consumption by extending the lifecycle of useful items.
- Help users discover affordable second-hand products within their preferred locations.
- Provide a simple and transparent way for individuals and NGOs to receive donated resources.
- Reduce unnecessary waste by promoting resource reuse.
- Create a scalable platform that can support future AI-based and smart marketplace features.

---

## 6. Project Scope

### Included in the MVP

- User Registration and Login (Individual Users + NGOs)
- User Profile Management
- Buy, Sell, and Donate Modules
- Product Listing with Images
- Product Categories
- Location-Based Search and Filtering
- Search Functionality
- Contact Seller/Donor
- NGO Registration and Admin Verification
- Product Management
- Admin Dashboard for Platform Management

### Donation System

- Users can choose to donate items instead of selling
- Donations can be directed to:
  - Individual users
  - Verified NGOs
- NGOs require admin approval before receiving donations

### Future Enhancements

- AI-based Product Condition Detection
- AI-powered Product Recommendations
- Online Payment Integration
- Delivery and Logistics Support
- In-App Chat System
- Wishlist and Favorites
- Product Reporting and Moderation
- Analytics Dashboard
- Mobile Application

## 7. Target Users

ReHome is designed for the following user groups:

- Individuals looking to buy affordable second-hand items
- Individuals who want to sell unused reusable items
- Users who want to donate items instead of discarding them
- Verified NGOs collecting donations for community support
- Administrators managing platform trust, safety, and verification

## 8. Core Features

ReHome provides a set of core features that enable seamless buying, selling, and donation of reusable resources within a community-driven platform.

---

### 1. User Authentication
- Secure registration and login system
- Supports Individual Users and NGOs
- Basic profile management

---

### 2. Product Listing System
- Users can create listings for reusable items
- Upload product images
- Add title, description, category, and price (or mark as donation)
- Specify location and contact preferences
- Add detailed product information including:
  - Condition (New / Like New / Good / Fair)
  - Usage age (e.g., months/years used)
  - Defects or damages (if any)
  - Reason for selling or donating

---

### 3. Browse and Search
- Users can browse all available listings
- Search items using keywords
- Filter results by category and location
- Sort listings based on relevance or recency

---

### 4. Buy & Contact System
- Interested users can view product details
- Users can contact sellers directly using provided contact methods
- No in-app payment system in MVP (external communication only)

---

### 5. Donation System
- Users can donate items instead of selling them
- Donations can be directed to:
  - Individual users
  - Verified NGOs
- Encourages reuse and reduces waste

---

### 6. NGO Integration
- NGOs can register and request verification
- Admin approves or rejects NGO accounts
- Verified NGOs can receive donated resources

---

### 7. Admin Panel
- Manage users and NGO verification
- Monitor and moderate product listings
- Remove fake or inappropriate content
- Maintain platform trust and safety

---

### 8. Location-Based Discovery
- Users can explore listings based on city or region
- Helps connect nearby buyers and sellers
- Improves relevance of search results

---

### 9. Product Transparency
- Each listing includes detailed condition and usage information
- Helps buyers make informed decisions before contacting sellers

## 9. Technology Stack

ReHome is designed as a full-stack web application using a simple, scalable, and industry-relevant technology stack suitable for rapid development and future expansion.

---

### Frontend
- HTML5, CSS3, JavaScript
- React.js (recommended for dynamic UI and component-based structure)
- Responsive design for mobile and desktop

---

### Backend
- Java (Core Java + OOP principles)
- Spring Boot (REST API development)
- Spring Boot MVC architecture
- Spring Data JPA (for database interaction)

---

### Database
- MySQL (Relational Database)
- Structured schema for users, NGOs, products, and transactions

---

### Authentication (MVP + Future Ready)
- Session-based authentication (MVP)
- JWT-based authentication (future enhancement)

---

### API Architecture
- RESTful APIs
- JSON data format for communication between frontend and backend
- Clear separation of frontend and backend layers

---

### File Storage
- Local storage for MVP
- Cloud storage (AWS S3 / Cloudinary) for future image handling

---

### Tools & Development Environment
- VS Code / IntelliJ IDEA
- Git & GitHub (Version Control)
- Postman (API testing)
- MySQL Workbench (Database design)

---

### Future Enhancements
- AI-based product recommendation system
- Image-based product condition detection
- Real-time chat system (WebSockets)
- Payment gateway integration (for paid listings)
- Mobile application (React Native / Flutter)


## 10. System Architecture

ReHome follows a simple 3-tier architecture consisting of Frontend, Backend, and Database layers. The system is designed to ensure scalability, modularity, and clear separation of concerns.

---

### 1. Architecture Overview

User (Frontend) → API Layer (Backend) → Database (MySQL)

---

### 2. Frontend Layer

- Built using HTML, CSS, JavaScript (or React in future)
- Responsible for user interface and user interactions
- Sends requests to backend APIs
- Displays product listings, forms, and dashboards

Example:
- User logs in
- User creates product listing
- User browses items

---

### 3. Backend Layer

- Built using Java + Spring Boot
- Handles business logic of the application
- Manages authentication, product listings, NGO verification, and admin controls
- Provides REST APIs for frontend communication

Main responsibilities:
- User management (register/login)
- Product management (add/update/delete listings)
- Donation system logic
- NGO verification workflow
- Admin operations

---

### 4. Database Layer

- MySQL relational database
- Stores all application data

Main tables:
- Users
- NGOs
- Products
- Donations
- Categories

---

### 5. Data Flow Example

1. User creates a product listing on frontend
2. Frontend sends API request to backend
3. Backend processes and validates data
4. Backend stores data in MySQL database
5. Backend sends response back to frontend
6. Frontend displays updated listing

---

### 6. High-Level System Design

[Frontend (UI)]
        ↓
[REST API - Backend (Spring Boot)]
        ↓
[MySQL Database]

## 11. Database Design

ReHome uses a relational database (MySQL) to store and manage all application data in a structured and scalable format.

The database is designed to support users, NGOs, product listings, and donation workflows with clear relationships between entities.

---

### 1. Users Table

Stores information about individual users.

**Fields:**
- user_id (Primary Key)
- name
- email
- phone
- password
- city
- state
- role (USER / NGO / ADMIN)
- created_at

---

### 2. NGO Table

Stores NGO-specific details and verification status.

**Fields:**
- ngo_id (Primary Key)
- organization_name
- contact_person
- email
- phone
- address
- city
- state
- verification_status (PENDING / APPROVED / REJECTED)
- created_at

---

### 3. Products Table

Stores all items listed for sale or donation.

**Fields:**
- product_id (Primary Key)
- title
- description
- category
- price (nullable for donations)
- condition (New / Like New / Good / Fair)
- usage_age
- defects
- listing_type (SELL / DONATE)
- location
- user_id (Foreign Key)
- created_at

---

### 4. Donations Table

Tracks donation transactions.

**Fields:**
- donation_id (Primary Key)
- product_id (Foreign Key)
- donor_id (User)
- receiver_type (INDIVIDUAL / NGO)
- receiver_id (nullable for NGO or user)
- status (PENDING / COMPLETED)
- created_at

---

### 5. Categories Table

Stores product categories.

**Fields:**
- category_id (Primary Key)
- category_name

---

### Relationships

- One User can create multiple Products
- One Product belongs to one User
- One Product can be donated or sold
- NGOs receive donations after verification
- Categories are linked to Products

---

### Database Design Goals

- Maintain data consistency using relational structure
- Support scalable product listings
- Enable easy filtering and search
- Ensure traceability of donations
- Maintain clear separation between users and NGOs

