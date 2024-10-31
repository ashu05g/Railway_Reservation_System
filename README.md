# 🚆 Railway Reservation System

> **A web-based platform to seamlessly manage railway ticket reservations, cancellations, and more.**

---

## 📜 **Project Overview**

The **Railway Reservation System** is a user-friendly website that allows passengers to book train tickets from one station to another, check available seats, manage bookings, and cancel tickets with ease. This project integrates database connectivity to manage user information, reservations, and cancellations securely.

---

## 💻 **Features**

1. **User Registration & Login**:
   - Secure user registration with form validation.
   - Login to access booking and other features.
   - Invalid login detection with appropriate error messages.
   
2. **Booking System**:
   - Check available trains between two stations.
   - Select preferred coach and enter passenger details.
   - Generate a unique PNR number for every booking.
   
3. **Ticket Cancellation**:
   - Cancel booked tickets using the PNR number.
   - Partial refund provided after deduction of the basic amount.

4. **Booking History**:
   - View details of all bookings using the PNR number.

5. **Session Management**:
   - Active session management until the user logs out.

---

## 🛠️ **Modules Overview**

### 🔑 **Login Module**
- Users need to log in before accessing any features.
- Invalid login attempts display error messages.
- Includes an option to register as a new user.

### 📝 **Registration Module**
- New users can register with valid credentials (username, password, phone number, email).
- Validation criteria:
   - Username: 6-10 characters, must be unique.
   - Password: Alphanumeric, minimum length of 10 characters.
   - Valid phone number and email required.

### 🎟️ **Booking Module**
- Select source, destination, and journey date (future dates only).
- Display of available trains for the selected route.
- Enter passenger details and select the coach (e.g., Sleeper, AC).
- PNR number generated upon successful booking, and details stored in the database.

### ❌ **Cancel Module**
- Cancel bookings by providing the PNR number.
- The system validates the PNR and provides a refund after deduction.

### 📂 **Show Booking Details**
- View details of any booking using the PNR number, including passenger and train details.

### 🚪 **Logout Module**
- Safely log out, ending the session and redirecting to the login page.

---

## ⚙️ **Technology Stack**

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (with Database Connectivity)
- **Database**: MySQL or any other relational database
- **Frameworks**: Django

---
##  **Screenshots**
![image](https://github.com/user-attachments/assets/f8157516-53a5-4f9e-9f68-241bb9d5cea1)
![image](https://github.com/user-attachments/assets/10335a67-70b2-48c3-8096-6fdccf2fa849)
![image](https://github.com/user-attachments/assets/f3161ccc-cfc7-47fe-afd0-ae5f973af414)
![image](https://github.com/user-attachments/assets/a13d4c74-6c1d-4a8d-af49-7064bbbf922c)
![image](https://github.com/user-attachments/assets/71d9fe36-0e8a-4151-8eb7-45681073a09d)
![image](https://github.com/user-attachments/assets/4f0ef751-3b84-4c1b-b81d-f6e06f08ad8b)
![image](https://github.com/user-attachments/assets/0b87cfaa-51a4-4c0f-a9f0-aeff08c3c18e)
![image](https://github.com/user-attachments/assets/6e0e1e7e-6e09-4923-ad3d-4bc04058a278)
![image](https://github.com/user-attachments/assets/5a71eec6-45dc-4cf9-9701-83fbcf86ca52)

---

## 📝 **How to Use**

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-repo/railway-reservation-system.git
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**:
    ```bash
    python app.py
    ```

4. **Access the Website**:
   Open `http://localhost:5000` in your browser and explore the Railway Reservation System!

---

## 📚 **License**

This project is licensed under the MIT License.
