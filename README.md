# AKEZA Inventory Management System (AKEZA IMS)

## Overview

The AKEZA Inventory Management System (AKEZA IMS) is a comprehensive solution designed to streamline and automate inventory management tasks. The system is equipped with features for managing purchases, sales, and suppliers, along with generating detailed invoices. Built with HTML, CSS, JavaScript, Python (Django), and SQLite, the system provides a user-friendly interface and a robust backend.

## Project Architecture

- **Frontend:**
  - HTML, CSS, and JavaScript for the user interface.
  - `django-widget-tweaks` and `crispy_forms` for enhanced form styling and customization.
  
- **Backend:**
  - Python (Django framework) for handling business logic, data management, and API services.
  - SQLite for database management.
  
- **Key Modules:**
  - **Purchases:** Manages supplier-specific purchases, incoming stock, and generates purchase invoices.
  - **Sales:** Handles outgoing stock, customer details, pricing, taxes, and generates sales invoices.
  - **Suppliers:** Manages supplier profiles, contact information, and integrates with purchase records.
  - **Dashboard:** Provides an overview of inventory, recent transactions, and graphical data representation.

## Setup Instructions

To set up the AKEZA IMS on your local machine, follow these steps:

### Prerequisites

- Python 3.8 or higher
- Django 3.2 or higher
- SQLite (included with Django)
- Git (for version control)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/akeza-ims.git
   cd akeza-ims
