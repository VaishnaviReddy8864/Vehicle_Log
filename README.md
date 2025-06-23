# VehicleLog-Service Module Low-Level Documentation

This document provides a low-level overview of the VehicleLog-Service module, a microservice within the Parking Management System (PMS) responsible for managing vehicle entry and exit operations.

---
## 1. Project Overview

This document provides a low-level overview of the Vehicle Log-Service module, a microservice within the Parking Management System (PMS) responsible for managing vehicle entry and exit operations.

### Features

* **Create new users**
    * Allows users to register by providing essential details such as name, email, phone number, and password.
    * Validates user input to ensure data integrity and prevent duplicate entries.
    * Hashes passwords securely using algorithms before storing them in the database.

