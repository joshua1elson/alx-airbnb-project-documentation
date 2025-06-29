# 📘 Airbnb Clone – Use Case Diagram

This directory contains the **Use Case Diagram** for the Airbnb Clone Backend Project. The diagram provides a high-level overview of how users and system components interact with the application’s core functionalities.

---

## 🧑‍🤝‍🧑 Actors

- **Guest**: Can search, book, review, and pay for properties.
- **Host**: Can list, update, delete properties and respond to reviews.
- **Admin**: Can manage all users, properties, bookings, and view system metrics.
- **Payment Service**: Handles all financial transactions securely.

---

## 🎯 Use Cases (System Functionalities)

| Use Case                  | Actor(s)        | Description |
|---------------------------|-----------------|-------------|
| Register / Login          | Guest, Host      | Allows users to sign up and authenticate. |
| Manage Profile            | Guest, Host      | Users can update profile info and pictures. |
| Search Properties         | Guest            | Search listings based on location, price, etc. |
| Book Property             | Guest            | Reserve a property for selected dates. |
| Cancel Booking            | Guest, Host      | Cancel confirmed or pending bookings. |
| Make Payment              | Guest            | Pay securely for bookings. |
| Receive Payment           | Host             | Hosts get payouts after successful stays. |
| Write Review              | Guest            | Submit reviews for properties. |
| Respond to Review         | Host             | Hosts can reply to guest reviews. |
| Manage Listings           | Host             | Create, update, and delete property listings. |
| Manage Users/Bookings     | Admin            | Admin can manage users, listings, and

