# Airbnb Clone Backend

## Overview
The Airbnb Clone Backend is designed to power a rental marketplace platform. This system provides robust and scalable backend functionalities to manage user accounts, property listings, bookings, payments, and more. It uses modern technologies to ensure security, performance, and usability for guests, hosts, and administrators.

---

## Core Functionalities

### 1. **User Management**
The backend supports user account creation, authentication, and management, ensuring a seamless experience for guests and hosts.

- **User Registration**
  - Allow users to register as guests or hosts.
  - Secure authentication using JSON Web Tokens (JWT).

- **User Login and Authentication**
  - Login functionality using email and password.
  - Support for OAuth login options (e.g., Google, Facebook).

- **Profile Management**
  - Enable users to update their profiles, including:
    - Profile photos.
    - Contact information.
    - Preferences.

---

### 2. **Property Listings Management**
Hosts can manage property listings with essential features for a rental platform.

- **Add Listings**
  - Hosts can create new listings by providing:
    - Title, description, and location.
    - Pricing, amenities, and availability.

- **Edit/Delete Listings**
  - Update or remove property details as needed.

---

### 3. **Search and Filtering**
The platform includes advanced search and filtering capabilities to help users find properties efficiently.

- **Search Criteria**
  - Location.
  - Price range.
  - Number of guests.
  - Amenities (e.g., Wi-Fi, pool, pet-friendly).

- **Pagination**
  - Efficient handling of large datasets with paginated results.

---

### 4. **Booking Management**
A booking system that enables secure and organized property reservations.

- **Booking Creation**
  - Guests can book properties for specific dates.
  - Prevent double bookings with date validation.

- **Booking Cancellation**
  - Allow guests and hosts to cancel bookings based on the platform's cancellation policy.

- **Booking Status**
  - Track booking progress with statuses:
    - Pending.
    - Confirmed.
    - Canceled.
    - Completed.

---

### 5. **Payment Integration**
Secure payment handling with support for global payment gateways.

- **Payment Gateways**
  - Integration with Stripe and PayPal.

- **Payment Workflow**
  - Upfront payments by guests.
  - Automatic payouts to hosts after booking completion.

- **Multi-Currency Support**
  - Handle transactions in various currencies.

---

### 6. **Reviews and Ratings**
A feedback system to maintain trust and quality on the platform.

- **Guest Reviews**
  - Guests can leave reviews and ratings for properties.

- **Host Responses**
  - Hosts can respond to reviews.

- **Review Validation**
  - Reviews are linked to specific bookings to prevent abuse.

---

### 7. **Notifications System**
Keep users informed with email and in-app notifications.

- **Notifications Include**
  - Booking confirmations.
  - Cancellations.
  - Payment updates.

---

### 8. **Admin Dashboard**
Administrative tools for monitoring and managing platform activities.

- **Manage Users**
  - View and control user accounts.

- **Manage Listings**
  - Oversee property listings and their details.

- **Manage Bookings**
  - Monitor all booking activities on the platform.

- **Manage Payments**
  - Track payment transactions and resolve disputes.

---

## Technologies Used
- **Backend Framework**: Django
- **Database**: PostgreSQL, 
- **Authentication**: JSON Web Tokens (JWT), OAuth
- **Payment Gateways**: Stripe, PayPal
- **Notifications**: Email services (e.g., SendGrid) and in-app notifications

---

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/airbnb-clone-backend.git


2. **Navigate to the Project Directory**
    ```bash
    cd airbnb-clone-backend

3. **Install Dependencies**
    ```bash

    pip install -r requirements.txt  # For Python
4. **Set Up Environment Variables**
- Configure the .env file or environment variables for:
        - Database connection (e.g., PostgreSQL).
        - Payment gateway settings (e.g., Stripe, PayPal API keys).
5. Run the Server
    ```bash
    python manage.py runserver  # Django