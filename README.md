# Full-Stack Learning Platform

A comprehensive full-stack course platform that enables users to learn online while allowing instructors to create and manage courses. This platform supports two distinct user roles: **Instructor** and **Learner**.

## Features

### Two User Roles
- **Instructor:** Can create, edit, and manage courses, including uploading videos, adding course descriptions, and setting pricing.  
- **Learner:** Can browse available courses, register, and purchase access to courses.

### Secure Authentication & Role-Based Routing
- Implemented using **JWT**, **React Router**, and **Redux** for secure login and access control.  
- Ensures only authorized users can access restricted routes based on their role.

### Payments
- Integrated **Razorpay payment gateway** for seamless course purchases.

### Responsive Design
- Mobile-first, **responsive layouts** designed with **Tailwind CSS** for optimal user experience across devices.

### File Uploads
- Course videos and other assets handled securely using **Multer**.

## Tech Stack

- **Frontend:** React.js, Redux, React Router, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT  
- **Payments:** Razorpay  
- **File Handling:** Multer

## Getting Started

### Prerequisites
- Node.js (v20+ recommended)  
- MongoDB (local or Atlas instance)  
- Razorpay account for payment integration  


