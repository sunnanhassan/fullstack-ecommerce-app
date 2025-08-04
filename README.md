Fullstack E-Commerce Website using Django & React
=================================================

This is a complete full-stack e-commerce web application built using Django (REST Framework) for the backend and React (with Redux Toolkit) for the frontend. The project implements all the essential features required in a modern online store, including user authentication, product catalog, shopping cart, order management, and payment integration using PayPal.

--------------------------------------------------
🔧 Technologies Used
--------------------------------------------------

Backend (Django):
- Django
- Django REST Framework
- Simple JWT (Authentication)
- Pillow
- CORS Headers

Frontend (React):
- React
- Redux Toolkit
- Axios
- React Router DOM
- React Icons
- Bootstrap

--------------------------------------------------
📦 Features
--------------------------------------------------

✓ User registration and authentication (JWT)  
✓ Product catalog with images  
✓ Shopping cart and quantity control  
✓ Order creation and checkout system  
✓ PayPal payment gateway integration  
✓ Admin panel to manage products, users, and orders  
✓ Responsive design for all devices  
✓ API endpoints for users, products, and orders  
✓ Dynamic routing and screen-based frontend design  

--------------------------------------------------
📁 Folder Structure Overview
--------------------------------------------------

backend/
  ├── ecommerce/         # Django project settings
  ├── api/               # Main app for API logic
  ├── media/             # Uploaded product images
  ├── manage.py          # Django entry point

frontend/
  ├── components/        # Reusable UI elements
  ├── screens/           # Pages like Login, Home, Cart, etc.
  ├── redux/             # Redux slices and API handlers
  ├── App.js             # Main app component
  ├── index.js           # App entry point with Redux store

--------------------------------------------------
🧩 Key Modules and Implementation
--------------------------------------------------

Backend:
- Django project and app created and structured
- REST Framework configured with JWT Authentication
- Custom user model setup
- Models defined for User, Product, Order, Cart, etc.
- Serializers and views created for all models
- API routing for users, products, and orders
- Admin setup for managing data
- Media and static file handling configured
- Database connected with migrations and superuser

Frontend:
- React project initialized with essential dependencies
- Project folder structure organized
- Redux Toolkit configured (slices and APIs for user, product, cart, and orders)
- All core screens implemented: Home, Login, Register, Product, Cart, Checkout, Payment, Orders
- Components created for navigation, product cards, loader, alerts, etc.
- Routing configured for SPA navigation
- Integrated PayPal client-side payment
- Redux state management for user auth and cart persistence
- Mobile responsive and visually styled using Bootstrap

--------------------------------------------------
🚀 Getting Started
--------------------------------------------------

1. Clone the repository:
   git clone https://github.com/yourusername/ecommerce-react-django.git

2. Setup Django backend:
   cd backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py createsuperuser
   python manage.py runserver

3. Setup React frontend:
   cd ../frontend
   npm install
   npm start

4. Add your PayPal Client ID to frontend/.env:
   REACT_APP_PAYPAL_CLIENT_ID=your_paypal_client_id

--------------------------------------------------
🧪 Testing
--------------------------------------------------

- Access admin panel: http://localhost:8000/admin  
- Access API endpoints: http://localhost:8000/api  
- React frontend runs on: http://localhost:3000  

--------------------------------------------------
📦 Deployment Notes
--------------------------------------------------

- Backend can be deployed to Render, Railway, or Heroku
- Frontend can be deployed using Netlify or Vercel
- Set proper CORS and environment variables for production

--------------------------------------------------
📜 License
--------------------------------------------------

This project is licensed under the MIT License.

--------------------------------------------------
🔍 Keywords (SEO)
--------------------------------------------------

E-commerce website, Django React fullstack, online store tutorial, JWT authentication, PayPal integration, shopping cart with Redux, responsive React store, admin dashboard, product catalog, order management
