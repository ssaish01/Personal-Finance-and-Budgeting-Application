# Personal Finance and Budgeting Application

This project is a personal finance and budgeting application that helps users track their income and expenses, set budgets, and visualize their financial patterns. Built with React on the frontend and Django on the backend, this application allows users to monitor their financial health, stay within budget limits, and make informed financial decisions. The app includes interactive charts for visualizing spending patterns and budget adherence.

## Key Features

### Frontend
- React: The user interface is built using React with hooks, providing a dynamic and responsive experience.
- Forms: Users can input income, expenses, and budget data through easy-to-use forms.
- Chart.js: Interactive charts are used to visualize spending patterns, showing how much users spend in each category (e.g., housing, transportation, entertainment), and whether they are adhering to their set budgets.

### Backend
- Python & Django: The backend is powered by Django, handling user authentication, storing financial records, and providing RESTful APIs to interact with the frontend.

### Budgeting and Financial Tracking
- Income & Expense Tracking: Users can track their income and expenses by category (e.g., housing, transportation, entertainment). Each expense can be assigned a category for easier tracking.
- Budget Creation: Users can set budgets for different categories (e.g., set a monthly limit for entertainment, housing, etc.). The app will notify users when they are nearing or exceeding their budget.
  
### Data Visualization
- Charts & Graphs: The application uses Chart.js to display spending patterns and budget adherence through interactive bar charts, pie charts, and line graphs. This allows users to visualize their financial data and identify areas where they may be overspending.

### Secure User Authentication
- JWT Authentication: Users can securely log in and authenticate via JWT (JSON Web Tokens), which ensures secure access to personal financial data.
- Password Hashing: User passwords are securely hashed before being stored, providing an additional layer of security.

## How It Works

1. Frontend:
   - The frontend is built with React, using hooks for state management and lifecycle methods.
   - Forms allow users to add and edit income and expense entries, assign categories to them, and monitor their budget.
   - Chart.js is used to render interactive charts that display financial data like spending by category, budget adherence, and income vs. expense trends over time.
   - Users can view their spending habits through visual representations of data, helping them stay within budget.

2. Backend:
   - The Django backend stores user data, including income, expenses, and budgets, in a secure database.
   - JWT authentication ensures that users' data is protected, allowing them to log in securely and access their financial data.
   - The backend provides RESTful APIs for managing financial records, creating budgets, and retrieving data for visualization on the frontend.

3. Budget and Spending Tracking:
   - Users can create categories for their spending (e.g., Housing, Food, Entertainment), set budgets for these categories, and track their spending throughout the month.
   - The app will calculate and display if the user is over or under budget for each category.
   - Users can edit their entries, view reports, and adjust their budgets based on their financial situation.

4. Data Visualization:
   - Chart.js provides visual charts to represent spending patterns over time, income versus expenses, and how well users are adhering to their budgets.
   - The dashboard provides users with an overview of their financial health, enabling them to make data-driven decisions.

### JWT Authentication
1. The backend uses JWT to authenticate users. After signing up or logging in, users will receive a token that should be used for subsequent API requests.
2. Store the JWT token in localStorage or cookies on the frontend for secure access to user data.

## Technologies Used

- Frontend: React, React Hooks, Form Handling, Chart.js
- Backend: Python, Django, Django REST Framework
- Authentication: JWT (JSON Web Tokens), Password Hashing
- Data Visualization: Chart.js
- Database: SQLite (default), can be configured to use PostgreSQL or MySQL

