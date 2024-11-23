# **user stories**

---

### 1. **User Management**

#### **User Registration**
- **User Story**: As a user, I want to be able to register an account as a guest or host, so that I can start using the platform and access the relevant features.
  - Acceptance Criteria:
    - I can register using my email and password or through OAuth (Google, Facebook).
    - My registration data is securely handled with JWT authentication.

#### **User Login and Authentication**
- **User Story**: As a user, I want to log in using my email and password, or through an OAuth provider, so that I can securely access my account.
  - Acceptance Criteria:
    - I can log in using email/password or Google/Facebook OAuth.
    - I receive a token (JWT) upon successful login to authenticate subsequent requests.

#### **Profile Management**
- **User Story**: As a user, I want to be able to update my profile, including my contact info, preferences, and profile photo, so that I can maintain up-to-date information on the platform.
  - Acceptance Criteria:
    - I can upload or update my profile photo.
    - I can edit my personal contact details and preferences.

---

### 2. **Property Listings Management**

#### **Add Listings**
- **User Story**: As a host, I want to be able to add property listings by providing details such as title, description, location, price, amenities, and availability, so that guests can view and book my property.
  - Acceptance Criteria:
    - I can create a new listing with the required details (e.g., title, description, price).
    - The listing is saved and visible to potential guests after creation.

#### **Edit/Delete Listings**
- **User Story**: As a host, I want to be able to edit or remove my property listings, so that I can keep my offerings up to date or remove them when no longer available.
  - Acceptance Criteria:
    - I can update the details of an existing listing.
    - I can delete a listing from the platform if I no longer want to rent it.

---

### 3. **Search and Filtering**

#### **Search Listings**
- **User Story**: As a guest, I want to be able to search for properties by location, price range, number of guests, and amenities, so that I can find the best match for my needs.
  - Acceptance Criteria:
    - I can search listings based on location, price, and number of guests.
    - I can view a list of properties matching my search criteria.

#### **Filter Listings**
- **User Story**: As a guest, I want to be able to filter properties by amenities (e.g., Wi-Fi, pool, pet-friendly), so that I can find properties that meet my specific needs.
  - Acceptance Criteria:
    - I can apply multiple filters (e.g., price, location, amenities) to narrow down search results.
    - The results update dynamically as I apply filters.

---

### 4. **Booking Management**

#### **Booking Creation**
- **User Story**: As a guest, I want to be able to book a property for specific dates, so that I can reserve my stay in advance.
  - Acceptance Criteria:
    - I can select the dates for my stay.
    - I can confirm and pay for my booking immediately.

#### **Booking Cancellation**
- **User Story**: As a guest or host, I want to be able to cancel a booking, so that I can handle unexpected changes.
  - Acceptance Criteria:
    - I can cancel a booking based on the platform's cancellation policy.
    - The system notifies both parties (guest and host) of the cancellation.

#### **Booking Status**
- **User Story**: As a guest or host, I want to track the status of my booking (pending, confirmed, canceled, completed), so that I can stay informed about the booking's progress.
  - Acceptance Criteria:
    - I can see the current status of any booking in my profile.
    - I receive notifications when the status of my booking changes.

---

### 5. **Payment Integration**

#### **Process Payment**
- **User Story**: As a guest, I want to securely make a payment for my booking using a payment gateway like Stripe or PayPal, so that I can finalize my reservation.
  - Acceptance Criteria:
    - I can make payments using Stripe or PayPal.
    - Payments are processed securely and a receipt is provided.

#### **Payout to Host**
- **User Story**: As a host, I want to receive payments automatically after a booking is completed, so that I can be compensated for my property rental.
  - Acceptance Criteria:
    - The payment gateway automatically transfers the payout to the host after the guest completes their stay.
    - The system confirms the payout status to the host.

#### **Handle Multiple Currencies**
- **User Story**: As a guest, I want the platform to handle payments in multiple currencies, so that I can pay in my preferred currency.
  - Acceptance Criteria:
    - I can select my preferred currency at checkout.
    - Payments are processed in the correct currency and converted when necessary.

---

### 6. **Reviews and Ratings**

#### **Leave Review**
- **User Story**: As a guest, I want to leave a review and rating for a property I stayed in, so that I can share my experience with others.
  - Acceptance Criteria:
    - I can rate the property on a scale (e.g., 1 to 5 stars).
    - I can leave detailed feedback about the property and my stay.

#### **Respond to Reviews**
- **User Story**: As a host, I want to be able to respond to reviews left by guests, so that I can engage with feedback and address concerns.
  - Acceptance Criteria:
    - I can reply to guest reviews from my host profile.
    - My responses are publicly visible alongside the original review.

---

### 7. **Notifications System**

#### **Receive Notifications**
- **User Story**: As a user (guest, host, or admin), I want to receive email and in-app notifications for booking confirmations, cancellations, and payment updates, so that I am always informed about my activities.
  - Acceptance Criteria:
    - I receive notifications via email or in-app for booking updates, cancellations, and payment transactions.
    - Notifications can be viewed within my user profile.

---

### 8. **Admin Dashboard**

#### **Manage Users**
- **User Story**: As an admin, I want to be able to manage user accounts (guests and hosts), so that I can ensure the platform runs smoothly and address issues.
  - Acceptance Criteria:
    - I can view and manage the status of user accounts (approve or block users).
    - I can view user activity and reports.

#### **Manage Listings**
- **User Story**: As an admin, I want to be able to view and manage property listings, so that I can ensure they adhere to platform standards.
  - Acceptance Criteria:
    - I can approve, edit, or remove listings that violate platform guidelines.
    - I can view detailed information about each listing.

#### **Manage Bookings**
- **User Story**: As an admin, I want to monitor and manage bookings, so that I can ensure all transactions are legitimate and compliant with the platform rules.
  - Acceptance Criteria:
    - I can view all bookings made on the platform.
    - I can cancel or modify bookings if necessary.

#### **Manage Payments**
- **User Story**: As an admin, I want to monitor payments and payouts to hosts, so that I can ensure financial transactions are properly handled.
  - Acceptance Criteria:
    - I can track all payment transactions, including payouts to hosts.
    - I can view payment status for guests and hosts.

---