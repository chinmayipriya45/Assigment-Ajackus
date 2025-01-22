User Management App

A simple web application for managing user details. Users can view, add, edit, and delete user data using a mock backend API.

Features
- View a list of users.
- Add new users.
- Edit existing user details.
- Delete users.
- Basic error handling for API requests.

Technologies Used
- React (with Vite)
- Axios for API requests
- JSONPlaceholder for mock API
- JavaScript (SWC compiler)
- Basic CSS for styling

Setup Instructions
Clone the repository:
   bash
   git clone <repository-url>
   cd user-management-app

Install dependencies:
npm install

Run the development server:
npm run dev

Challenges Faced
	•	Mock API Limitations: The JSONPlaceholder API doesn’t persist changes, so added or edited data is only simulated for demonstration purposes.
	•	Error Handling: Handling errors gracefully for different API scenarios (e.g., network errors or invalid responses) required careful implementation.
	•	UI Design: Ensuring the layout was clean and functional without overcomplicating the styling took some iteration.


Future Improvements
	•	Pagination: Add pagination or infinite scrolling for better handling of large datasets.
	•	Form Validation: Implement client-side validation to ensure valid input data before submission.
	•	Responsive Design: Improve the layout to work better on mobile and tablet devices.
