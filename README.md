
# STMS (Student Management System)

**A simple web-based Student Management System built using Bootstrap 5, HTML, CSS, and JavaScript.**  
This project allows users to register, view, update, and delete student information. The data is stored in `localStorage` for demonstration purposes.

## Features

- **Responsive Navbar**: A clean and mobile-friendly navigation bar built using Bootstrap 5.
- **Student Registration Form**: A form that allows users to input student information, including first name, last name, roll number, class, mobile number, and email.
- **View All Registered Students**: Displays all students in a tabular format with the ability to update or delete records.
- **Update Student Information**: Allows users to update any student’s information using a Bootstrap modal window.
- **Delete Student Records**: Users can remove student records with a confirmation prompt.
- **Pagination**: Dynamically generated pagination that adjusts based on the number of students displayed on the first page (10 students) and subsequent pages (5 students).
- **LocalStorage Persistence**: All data is stored in the browser’s `localStorage`, allowing persistence even after the page is refreshed.
- **Modal Form for Updates**: The update form pre-fills the selected student's data for easy editing.

## Technologies Used

- **Bootstrap 5**: For responsive design and layout.
- **HTML5 & CSS3**: For structuring and styling the web page.
- **JavaScript (ES6+)**: To handle form submissions, updating localStorage, and dynamic content generation.
- **LocalStorage**: To store and retrieve student data.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/STMS.git
   ```

2. Navigate to the project folder:
   ```bash
   cd STMS
   ```

3. Open `index.html` in your preferred browser:
   ```bash
   open index.html
   ```

4. Start registering students and managing data through the web interface.

## Future Enhancements

- Implement a real database for persistent data storage.
- Add authentication for managing student data securely.
- Add validation and input sanitization to the registration form.
- Implement more detailed student profiles.
