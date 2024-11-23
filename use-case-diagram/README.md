# Airbnb Clone Use Case Diagram

## Overview
This document describes the **Use Case Diagram** for the **Airbnb Clone** project. The system represents the core functionalities of a rental marketplace where **Guests**, **Hosts**, and **Admins** interact with the platform, and **Payment Gateway** handles financial transactions.

## Actors
The following actors interact with the system:

1. **Guest**: A user looking for properties to rent.
2. **Host**: A user who owns properties and lists them for rent.
3. **Admin**: The system administrator who manages users, listings, bookings, and payments.
4. **Payment Gateway**: A third-party service (e.g., Stripe, PayPal) responsible for processing payments.

## Use Cases

### 1. User Management
- **Register**: Guests and Hosts can sign up using email/password or OAuth (e.g., Google, Facebook).
- **Login**: Users can authenticate using email/password or OAuth.
- **Update Profile**: Users can update personal information, profile photos, and preferences.

### 2. Property Listings Management
- **Add Listing**: Hosts can create new property listings by providing details like title, description, price, etc.
- **Edit Listing**: Hosts can edit existing property listings.
- **Delete Listing**: Hosts can remove property listings.

### 3. Search and Filtering
- **Search Listings**: Guests can search for properties by location, price, number of guests, and amenities.
- **Filter Listings**: Guests can filter search results based on criteria such as location, price, etc.

### 4. Booking Management
- **Create Booking**: Guests can book a property for specific dates.
- **Cancel Booking**: Guests or Hosts can cancel bookings based on the cancellation policy.
- **Track Booking Status**: Guests and Hosts can track booking statuses (pending, confirmed, canceled, or completed).

### 5. Payment Integration
- **Process Payment**: The payment gateway processes payments made by guests.
- **Payout to Host**: The payment gateway handles automatic payouts to hosts after booking completion.
- **Handle Multiple Currencies**: The system supports multiple currencies for payments.

### 6. Reviews and Ratings
- **Leave Review**: Guests can leave reviews and ratings for properties.
- **Respond to Reviews**: Hosts can respond to guest reviews.

### 7. Notifications System
- **Receive Notifications**: Users (Guests, Hosts, Admins) receive notifications via email or in-app about bookings, cancellations, and payment updates.

### 8. Admin Dashboard
- **Manage Users**: Admins can monitor and manage user accounts (Guests and Hosts).
- **Manage Listings**: Admins can view and manage property listings.
- **Manage Bookings**: Admins can oversee and manage bookings.
- **Manage Payments**: Admins can monitor payments and payouts to Hosts.

## Use Case Diagram Summary

- **Guest** interacts with:
  - User Management: Register, Login, Update Profile
  - Search and Filtering: Search Listings, Filter Listings
  - Booking Management: Create Booking, Cancel Booking, Track Booking Status
  - Reviews and Ratings: Leave Review
  - Notifications System: Receive Notifications

- **Host** interacts with:
  - User Management: Register, Login, Update Profile
  - Property Listings Management: Add Listing, Edit Listing, Delete Listing
  - Booking Management: Track Booking Status, Cancel Booking
  - Reviews and Ratings: Respond to Reviews
  - Notifications System: Receive Notifications
  - Payment Integration: Payout to Host

- **Admin** interacts with:
  - Admin Dashboard: Manage Users, Manage Listings, Manage Bookings, Manage Payments
  - Notifications System: Receive Notifications

- **Payment Gateway** interacts with:
  - Payment Integration: Process Payment, Payout to Host, Handle Multiple Currencies

## Diagram Description
The **Use Case Diagram** is used to represent the interactions between the system's actors and their respective use cases. Actors are depicted as stick figures, and use cases are represented as ovals. Lines are drawn between actors and use cases to show which actors interact with which functionalities.

## How to Use This Diagram
- The diagram helps visualize the core functionalities of the Airbnb Clone system.
- It shows the relationships between users, hosts, admins, and third-party services like payment gateways.
- You can use this diagram to understand the system's interactions and responsibilities for each actor.

