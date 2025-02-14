

# Contact Management Web Application

This is a simple web-based contact management application that allows users to add, edit, delete, and search for contacts. The application uses HTML, CSS, and JavaScript to provide a dynamic user interface, and it persists data using the browser's local storage.

## Features

- **Add Contacts**: Users can input their name, email, and phone number to add a new contact.
- **Edit Contacts**: Existing contacts can be edited directly from the list.
- **Delete Contacts**: Users can remove contacts from the list.
- **Search Functionality**: A search bar allows users to filter contacts by name or email.
- **Persistent Data**: Contacts are stored in the browser's local storage, ensuring data persists even after refreshing the page.
- **Styling**: The application includes visually appealing styling with background images for both the website and input fields.

## Setup Instructions

### Prerequisites
- A modern web browser (e.g., Google Chrome, Firefox, Microsoft Edge).

### Steps to Run the Application
1. **Download the Code**:
   - Clone or download the source code from the repository or copy the provided HTML file.

2. **Open the File**:
   - Locate the `index.html` file in your file system.
   - Double-click the file to open it in your default web browser, or right-click and choose "Open with" to select a specific browser.

3. **Start Using**:
   - The application will load in your browser, and you can start adding, editing, deleting, and searching for contacts.

### Customization
- **Background Images**:
  - To change the background image of the website, replace the URL in the `body`'s `background-image` property in the CSS section:
    ```css
    background-image: url('https://via.placeholder.com/1920x1080');
    ```
  - To change the background image inside the input fields, replace the URL in the `input`'s `background-image` property:
    ```css
    background-image: url('https://via.placeholder.com/50');
    ```

- **Colors and Styles**:
  - Modify the CSS styles in the `<style>` section to customize the appearance of the form, buttons, and contact list.

## Usage

### Adding a Contact
1. Fill in the "Name", "Email", and "Phone Number" fields in the form.
2. Click the "Click to be one of my contacts" button to add the contact.
3. The contact will appear in the list below the form.

### Editing a Contact
1. Locate the contact you want to edit in the list.
2. Click the "Edit" button next to the contact.
3. The contact's details will populate the form fields.
4. Make your changes and click the "Click to be one of my contacts" button to save the updated information.

### Deleting a Contact
1. Locate the contact you want to delete in the list.
2. Click the "Delete" button next to the contact.
3. The contact will be removed from the list.

### Searching for Contacts
1. Use the search bar at the top of the contact list.
2. Type a name or email to filter the displayed contacts.

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling the form, buttons, and contact list.
- **JavaScript**: For handling dynamic interactions, such as adding, editing, deleting, and searching for contacts.
- **Local Storage**: For persisting contact data across browser sessions.

## Known Limitations

- The application is designed for client-side use only and does not include server-side functionality.
- Data is stored locally in the browser, so it is not shared between different devices or browsers.
- The search functionality is case-insensitive but does not support advanced filtering (e.g., partial matches for phone numbers).

## Future Enhancements

- Add drag-and-drop functionality to reorder contacts.
- Implement a backend to store data in a database for multi-device access.
- Add validation for phone numbers and email formats.
- Improve responsiveness for smaller screens.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute it as needed.

---

