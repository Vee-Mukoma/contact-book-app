# contact-book-app

📇 Contact Book Web App

This is a simple Contact Book web application that allows users to add, edit, delete, and view contacts. Each contact contains a name, email, phone number, and profile image (avatar). This app connects to a remote backend API and requires an API key to function.

🚀 Features

🔐 API Key-based authentication
📋 View list of contacts
➕ Add a new contact
✏️ Edit existing contacts
🗑️ Delete a contact
🖼️ Upload and display profile images

🗂️ File Structure

📁 ContactBook/
├── index.html              # Home page – displays all contacts
├── add-contact.html        # Form to add a new contact
├── edit-contact.html       # Form to view/edit/delete a contact
├── enter-api-key.html      # Prompt user to enter their API key
├── config.js               # Configuration file with rootPath and API key logic

🧪 How It Works

On first visit, config.js checks if an API key exists in localStorage. If not, the user is redirected to enter-api-key.html.

On the home page (index.html), contacts are fetched from the backend and displayed in a table format.

Clicking a contact opens edit-contact.html, where the user can:

Edit the contact fields

Submit changes

Delete the contact

The Add Contact button opens add-contact.html, where the user can add a new contact with all fields and an avatar.

🛠️ Setup & Usage

Clone or download the project folder.

Open index.html in your browser.

If prompted, enter your API key. This will be saved to localStorage.

Begin using the app to manage your contacts.
