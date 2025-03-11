NinebibiFood - Online Food Ordering App
NinebibiFood is a cross-platform food ordering application built with Flutter for the frontend and Next.js for the backend API,
which communicates with Supabase for authentication, database management, and real-time updates.

Key Features
- User Authentication – Sign up, log in, and manage user profiles
- Restaurant Listings – Browse restaurants by category and location
- Food Ordering System – Add items to the cart and place orders
- Order Tracking – Track order status in real-time
- Payment Integration – Multiple payment options (if applicable)

Flutter (Frontend):
The mobile app is built with Flutter, a popular framework for creating cross-platform apps.
The Flutter app interacts with the Next.js backend API via HTTP requests to fetch and send data (e.g., user data, restaurant data, orders).
The Flutter app uses Supabase's authentication methods (like JWT tokens) to allow users to sign up, log in, and manage their profiles securely.
Next.js (Backend API):

Next.js is used to create the API routes (using the pages/api directory).
These API routes handle all communication with Supabase, performing operations such as fetching restaurant data, creating new orders, and handling user authentication.
Supabase provides a RESTful API and real-time subscriptions, which are used to manage data and provide real-time updates to the mobile app and web app.
Supabase (Database and Authentication):

Supabase handles the database management with PostgreSQL and user authentication (via JWT tokens).
The app interacts with Supabase for managing users, restaurants, and orders. It also leverages Supabase's real-time functionality to provide instant updates on order statuses or any other live data.
