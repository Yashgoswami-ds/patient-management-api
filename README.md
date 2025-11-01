 Patient Management API 

Overview

Welcome to the Patient Management System API built with FastAPI. This API allows you to manage patient records efficiently and provides essential functionalities like creating, viewing, updating, and deleting patient data. With automated BMI calculations and health status verdicts (e.g., Normal, Underweight, Obese), this API is designed for healthcare applications, clinics, and wellness platforms.

This system stores data in a simple JSON file, providing easy-to-use endpoints for managing patient records.

 Features

Create new patient records with personalized details.

View patient information, including BMI and health verdict.

Sort records by BMI, weight, or height.

Update patient information, including health metrics.

Delete patients' records securely.

Automatic BMI Calculation: BMI calculated upon creation or update, and health verdict is assigned automatically.

echnologies Used

FastAPI – High-performance API framework for building web apps.

Uvicorn – ASGI server to run FastAPI.

Pydantic – Data validation and parsing for Python models.

JSON – Lightweight data storage format for patient records.
