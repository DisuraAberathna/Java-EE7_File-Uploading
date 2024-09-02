# File Uploading and Downloading Project

This project is a simple web application for uploading and downloading files, built using Java EE7, Bootstrap, and Fetch API. It serves as a learning exercise to understand file handling in a web environment.

## Features

- **File Uploading**: Users can upload files to the server.
- **File Downloading**: Users can download previously uploaded files.
- **Responsive Design**: The user interface is built with Bootstrap, ensuring it works well on various screen sizes.

## Technologies Used

- **Java EE7**: Used for the backend to handle file uploads and downloads.
- **Bootstrap**: Provides a responsive layout and styling.
- **Fetch API**: Utilized for making asynchronous requests to the server for file operations.
- **JDK 8**: The project is built and runs on Java Development Kit 8.
- **GlassFish 5**: The application is deployed on the GlassFish 5 server.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK) 8**
- **GlassFish 5** (Java EE server)
- **Git** (for version control)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DisuraAberathna/Java-EE7_File-Uploading.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd Java-EE7_File-Uploading
   ```

3. **Deploy the project to GlassFish 5:**
   - Copy the project directory to the GlassFish `domains/domain1/applications` folder.
   - Alternatively, you can deploy it via the GlassFish admin console by packaging the project as a WAR file.

4. **Run the server:**
   - Start GlassFish 5 and access the application in your browser.

### Usage

- **Uploading Files:**
  - Go to the "Upload" page.
  - Choose a file and click "Upload."
  
- **Downloading Files:**
  - Go to the "Download" page.
  - Select a file from the list and click "Download."

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Java EE documentation and community
- Bootstrap for the UI components
- MDN Web Docs for Fetch API references
