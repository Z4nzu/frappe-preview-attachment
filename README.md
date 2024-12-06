# Frappe Attachment Preview

This Frappe app introduces a functionality to preview file attachments directly within the Frappe framework. By adding an **eye icon** next to each attachment, users can quickly view the content of attached files without downloading them.

## Features

- **Preview Dialog**: Provides a dedicated icon for each attachment that opens a dialog box to preview the file when clicked.
- **Draggable and Resizable Dialog**: The preview dialog can be stretched, dragged, and moved for better usability.
- **Supports Multiple File Types**: View various file formats directly in the browser, including:
  - Images
  - PDFs
  - Videos
  - Text Files
  - JSON Files
  - XML Files
- **Enhanced User Experience**: Saves time by allowing users to preview attachments without opening in a new tab.


## Screenshots

Add screenshots here to demonstrate the functionality:


## Installation

Follow these steps to install and use the app:

1. **Clone the Repository**
   ```bash
   bench get-app https://github.com/Z4nzu/frappe-attachment-preview.git
2. **Install the App**
    ```bash
   bench --site your-site-name install-app frappe_attachment_preview
   ```
3. **Restart Bench**
    ```bash
   bench restart
   ```
   
## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve this app.

1. Fork the repository.
2. Create a feature branch (git checkout -b your-feature).
3. Commit your changes (git commit -m "Add your feature").
4. Push to the branch (git push origin feature/your-feature).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.