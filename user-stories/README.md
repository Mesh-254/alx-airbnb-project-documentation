# User Stories for Airbnb Clone Project

---

## 1. **User Management**

### **User Registration**
- **As a user**, I want to register an account as a guest or host to access the platform.
- **Acceptance Criteria**: Email/password or OAuth registration with JWT authentication.

### **User Login and Authentication**
- **As a user**, I want to log in using my email and password or OAuth provider.
- **Acceptance Criteria**: Email/password or OAuth login with JWT authentication.

### **Profile Management**
- **As a user**, I want to update my profile, contact info, preferences, and profile photo.
- **Acceptance Criteria**: Upload/update profile photo and edit personal details.

---

## 2. **Property Listings Management**

### **Add Listings**
- **As a host**, I want to add property listings with title, description, price, and availability.
- **Acceptance Criteria**: Create a new listing with required details and make it visible to guests.

### **Edit/Delete Listings**
- **As a host**, I want to edit or remove my property listings.
- **Acceptance Criteria**: Edit or delete listings as needed.

---

## 3. **Search and Filtering**

### **Search Listings**
- **As a guest**, I want to search for properties by location, price range, and number of guests.
- **Acceptance Criteria**: Search properties based on location, price, and guest number.

### **Filter Listings**
- **As a guest**, I want to filter properties by amenities like Wi-Fi, pool, or pet-friendly options.
- **Acceptance Criteria**: Apply multiple filters to narrow search results.

---

## 4. **Booking Management**

### **Booking Creation**
- **As a guest**, I want to book a property for specific dates.
- **Acceptance Criteria**: Select dates and confirm the booking with payment.

### **Booking Cancellation**
- **As a guest/host**, I want to cancel a booking as per the platform’s policy.
- **Acceptance Criteria**: Cancel a booking and notify both parties.

### **Booking Status**
- **As a guest/host**, I want to track booking statuses (pending, confirmed, canceled, completed).
- **Acceptance Criteria**: View and receive notifications on booking status changes.

---

## 5. **Payment Integration**

### **Process Payment**
- **As a guest**, I want to make secure payments via Stripe or PayPal.
- **Acceptance Criteria**: Payments processed securely, receipt provided.

### **Payout to Host**
- **As a host**, I want automatic payouts after booking completion.
- **Acceptance Criteria**: Payout processed after guest stay.

### **Handle Multiple Currencies**
- **As a guest**, I want to pay in my preferred currency.
- **Acceptance Criteria**: Select preferred currency, payments processed correctly.

---

## 6. **Reviews and Ratings**

### **Leave Review**
- **As a guest**, I want to leave reviews and ratings for properties I stayed in.
- **Acceptance Criteria**: Rate properties and leave feedback.

### **Respond to Reviews**
- **As a host**, I want to respond to guest reviews.
- **Acceptance Criteria**: Reply to reviews from the host profile.

---

## 7. **Notifications System**

### **Receive Notifications**
- **As a user**, I want to receive notifications about booking confirmations, cancellations, and payment updates.
- **Acceptance Criteria**: Notifications via email and in-app.

---

## 8. **Admin Dashboard**

### **Manage Users**
- **As an admin**, I want to manage user accounts (approve/block users).
- **Acceptance Criteria**: View and manage user status and activity.

### **Manage Listings**
- **As an admin**, I want to monitor and manage property listings.
- **Acceptance Criteria**: Approve/edit/remove listings based on platform guidelines.

### **Manage Bookings**
- **As an admin**, I want to monitor and manage bookings.
- **Acceptance Criteria**: View and modify bookings.

### **Manage Payments**
- **As an admin**, I want to track payment transactions and payouts to hosts.
- **Acceptance Criteria**: Monitor all payment transactions and their statuses.

---