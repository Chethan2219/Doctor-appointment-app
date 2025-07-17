# Doctor Appointment Web App

The **Doctor Appointment Web App** is a full-stack web application designed to enhance accessibility to healthcare by streamlining the process of booking doctor appointments. It supports three user roles — **Patient**, **Doctor**, and **Admin** — each with features tailored to their needs. The application integrates **Stripe and Razorpay** for seamless and secure online payments. Built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js), it delivers a responsive, intuitive experience for both patients and healthcare providers.

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Gateways**: Stripe, Razorpay
- **Authentication**: JSON Web Token (JWT)

## 🔑 Key Features

### 1. Role-Based Authentication

- **Patient Login**:  
  - Register, log in, and book appointments with doctors  
  - Manage appointments (view, cancel, reschedule)  
  - Secure payment options: Cash, Stripe, Razorpay  
  - Personal profile with editable info: name, email, address, gender, birthday, profile picture

- **Doctor Login**:  
  - Manage daily appointments  
  - Dashboard: earnings, total patients, recent bookings  
  - Update profile (bio, fees, address, availability)  
  - View appointment and patient details

- **Admin Login**:  
  - Create and manage doctor profiles  
  - Dashboard with total doctors, appointments, patients, and recent activity  
  - Add/edit doctor details (specialty, degree, experience, fees, etc.)  
  - View, cancel, or mark appointments as completed

## 🏠 Home Page

- Clean and intuitive interface  
- Search for doctors by specialty  
- View top doctors and their profiles  
- Access sections like About Us, Delivery Info, Privacy Policy, and Contact  
- Footer with quick navigation links

## 🩺 All Doctors Page

- Lists all available doctors  
- Filter by specialty  
- Clickable doctor profiles redirect to booking page

## 📄 About Page

- Highlights the mission and vision of the platform  
- **Why Choose Us** section focuses on:
  - **Efficiency**: Easy and fast appointment process  
  - **Convenience**: Online booking & payment  
  - **Personalization**: User-friendly experience tailored to individuals

## 📞 Contact Page

- Displays office location and contact information  
- Section for career opportunities  
- Standard footer navigation

## 📅 Doctor Appointment Page

- Shows selected doctor's details: image, qualifications, experience, short bio  
- Appointment booking form with date, time, and payment options  
- Payment methods: Cash, Stripe, Razorpay  
- Related doctors displayed below  
- Requires login or registration before booking

## 👤 User Profile

- Accessible post-login  
- Update profile information and profile picture  
- View upcoming and past appointments  
- Logout functionality

## 🗄️ Admin Panel

- Dashboard with key metrics: total doctors, patients, appointments, recent bookings  
- Doctor Management: add, edit, delete doctor profiles  
- Appointment Management: view, cancel, or mark appointments as completed

## 🩺 Doctor Dashboard

- View total earnings and appointment statistics  
- List of all scheduled appointments with patient details  
- Actions: complete or cancel appointments  
- Profile update functionality

## 💳 Payment Integration

- Multiple secure payment methods:
  - Cash
  - Stripe
  - Razorpay

## 🌐 Project Setup

To set up and run this project locally:

1. **Clone the Repository**
 
       git clone https://github.com/your-username/doctor-appointment-app.git
       cd doctor-appointment-app
   
2.  **Install Dependencies**

        npm install
        cd client
        npm install
        cd ..
    
3. **Environment Variables**
    Create a .env file in the root directory and add:

       MONGO_URI=your_mongodb_connection_string
       JWT_SECRET=your_jwt_secret
       STRIPE_API_KEY=your_stripe_api_key
       RAZORPAY_API_KEY=your_razorpay_api_key

4. **Run the Application**

       npm run dev

📦 Folder Structure
    plaintext
    Copy
    Edit
    doctor-appointment-app/
    ├── client/          # Frontend (React.js)
    ├── server/          # Backend (Node.js, Express.js)
    ├── models/          # MongoDB Schemas
    ├── controllers/     # API Controllers
    ├── routes/          # API Routes
    ├── middleware/      # Authentication and Error Handling
    ├── config/          # Configuration Files
    ├── utils/           # Utility Functions
    ├── public/          # Static Files
    └── .env             # Environment Variables

🤝 Contributing
Contributions are welcome! Feel free to fork the repo, submit issues, or open pull requests.

🌟 Acknowledgements
Special thanks to the open-source communities behind MongoDB, Express.js, React.js, Node.js, Stripe, and Razorpay for enabling modern web application development.

