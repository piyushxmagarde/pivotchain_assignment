# pivotchain_assignment
# Admin Dashboard Component
This is a React component that represents an Admin Dashboard. It allows you to view, create, edit, and delete customer data. The component fetches customer data from a backend API and displays it in a table. You can also add new customers and update existing customer information using a popup form.

## Features

- View a list of customers with their details such as name, email, contact details, status, created date, and updated date.
- Create a new customer by clicking on the "Create Customer" button, which opens a popup form.
- Edit an existing customer's information by clicking on the "Edit" button in the customer table.
- Delete a customer from the table by clicking on the "Delete" button.
- Sort the customer table by created date and updated date in ascending or descending order.

## Prerequisites

Before running the Admin Dashboard component, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Getting Started

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/admin-dashboard.git
```

2. Change into the project directory:

```bash
cd admin-dashboard
```

3. Install the required dependencies:

```bash
npm install
```

4. Run the React development server:

```bash
npm start
```

The Admin Dashboard component will be running at [http://localhost:3000](http://localhost:3000).

## API Integration

The Admin Dashboard component interacts with a backend API to fetch customer data and perform CRUD operations. Ensure that the backend API is running and accessible at `http://localhost:5000`.
