![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

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
