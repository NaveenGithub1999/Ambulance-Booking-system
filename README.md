# Ambulance Booking System 🚑

A comprehensive Python-based Ambulance Booking System designed to allow users to book ambulances seamlessly. This project integrates a backend API, frontend interface, and a database for managing bookings, users, and ambulance availability.

---

## **Features**
- User registration and management
- Real-time ambulance availability
- Booking functionality with status updates
- RESTful APIs for backend operations
- User-friendly frontend for booking and managing requests
- SQLite/MySQL database integration

---

## **System Architecture**
The project uses a 3-tier architecture:
1. **Frontend**: Flask templates with JavaScript for user interaction.
2. **Backend**: Flask-based REST API for managing business logic.
3. **Database**: Relational database for storing user, ambulance, and booking information.

![System Architecture](./images/system-architecture.png)

---

## **Technologies Used**
- **Backend**: Python, Flask
- **Frontend**: HTML, JavaScript
- **Database**: SQLite (default), MySQL (optional)
- **Tools**: Postman (API Testing), Git

---

## **Setup Instructions**
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ambulance-booking-system.git
    cd ambulance-booking-system
    ```

2. Set up a virtual environment and install dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate     # For Windows
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python app.py
    ```

4. Access the application at `http://127.0.0.1:5000`.

---

## **Database Schema**
![Database Schema](./images/database-schema.png)

Tables:
- **Users**: Stores user information.
- **Ambulances**: Stores ambulance details and availability.
- **Bookings**: Tracks booking information and statuses.

---

## **API Endpoints**

| **Endpoint**        | **Method** | **Description**                      |
|----------------------|------------|--------------------------------------|
| `/api/users`         | `POST`     | Add a new user                      |
| `/api/ambulances`    | `GET`      | Get available ambulances            |
| `/api/bookings`      | `POST`     | Book an ambulance                   |
| `/api/bookings/<id>` | `GET`      | Get booking details by ID           |
| `/api/bookings/<id>` | `PUT`      | Update the booking status           |

---

## **Future Enhancements**
- Add user authentication and login functionality
- Implement real-time ambulance tracking using GPS
- Create an admin panel for ambulance management
- Integrate SMS notifications for booking confirmation

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contributing**
Contributions are welcome! Feel free to fork this repository, create a feature branch, and submit a pull request.
