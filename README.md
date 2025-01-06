# Inventory Management System

A comprehensive inventory management system built with Django and MongoDB. This application allows users to manage products, suppliers, stock movements, and sales orders efficiently.

## Table of Contents
- [Project Setup](#project-setup)
- [Database Configuration](#database-configuration)
- [Running the Project](#running-the-project)

## Project Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/PIYUSH-MISHRA-00/Inventory-Management-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Inventory-Management-System
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Database Configuration
1. Ensure you have MongoDB installed and running on your local machine.
2. The project is configured to connect to MongoDB at `mongodb://localhost:27017`.

## Running the Project
1. Run the migrations to set up the database:
   ```bash
   python3 run.py makemigrations
   python3 run.py migrate
   ```
2. Start the development server:
   ```bash
   python3 run.py runserver 8001
   ```
3. Open your browser and navigate to `http://127.0.0.1:8001/` to access the application.
