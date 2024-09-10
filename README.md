# COVID Bed Slot Booking System

## Project Overview

The COVID Bed Slot Booking System is a web application designed to facilitate the booking of hospital beds for COVID-19 patients. This system helps manage hospital resources efficiently during the pandemic by allowing users to check bed availability and book slots in real-time.

## Features

- User Registration and Login
- Hospital Registration and Login
- Admin Dashboard
- Real-time Bed Availability Updates
- Bed Booking for Patients
- Different Types of Beds (Normal, ICU, Ventilator)
- Hospital Data Management


## Technologies Used

- Python
- Flask (Web Framework)
- MySQL (Database)
- SQLAlchemy (ORM)
- HTML/CSS (Frontend)


## Installation

1. Clone the repository:
   ```
   git clone git@github.com:SameerAhmed07/Covid-Bed-Slot-Booking-System.git
   ```

2. Navigate to the project directory:
   ```
   cd Covid-Bed-Slot-Booking-System
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up the MySQL database:
   - Create a new database named `covidDBMS`
   - Import the `covid.sql` file into your database

5. Update the database connection in `main.py`:
   ```python
   app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://username:password@localhost/covidDBMS'
   ```

6. Run the application:
   ```
   python main.py
   ```

## Usage

1. Access the application through a web browser at `http://localhost:5000`
2. Register as a user or hospital
3. Login to access the dashboard
4. For patients: Check bed availability and book slots
5. For hospitals: Update bed availability and manage bookings
6. For admin: Manage hospital users and view system data


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any queries or support, please contact [SAMEER](sameerslens@gmail.com).
