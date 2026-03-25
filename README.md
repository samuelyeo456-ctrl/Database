# Database
This is a database project in Python and MariaDB using air passenger data system. The project includes Tkinter GUI , CRUD , and analytics for airline popularity, stay duration, and travel trends.

Project Overview
The system provides a comprehensive platform to store and analyze arrival patterns, visitor demographics, and travel trends. By integrating scattered data sources, it enables stakeholders to optimize resource allocation, tailor marketing campaigns, and promote sustainable tourism.

Data Management (CRUD)
The application includes full Create, Read, Update, and Delete capabilities for passenger records:
- Create: Add new passenger arrival data, including flight details and length of stay.
- Read: Query and filter passenger information by various criteria like name or ID.
- Update: Modify existing passenger records via a unique Passenger ID (PID).
- Delete: Securely remove outdated or incorrect passenger data from the database.

Advanced Analytics
The system performs complex data processing to generate actionable insights:
- Airline Popularity Analysis: Ranks and visualizes the most popular carriers entering Singapore based on passenger volume.
- Tourism Duration Analysis: Categorizes and identifies the most common lengths of stay to help tailor regional tourism strategies.
- Airline Trend Analysis: Examines the relationship between a visitor's country of origin and their airline preferences.

Interactive User Interface
- A user-friendly GUI allows users to navigate through various analysis tools and data management functions without requiring direct SQL knowledge.

Database Architecture
The system utilizes a structured relational schema with four core entities:
- Passenger: Stores personal details (Age, Gender) and links to other tables.
- Airlines: Tracks passenger counts per airline.
- Countries: Monitors visitor numbers based on origin countries.
- Length_of_Stay: Manages data regarding the duration of visitor stays.
