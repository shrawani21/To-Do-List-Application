# To-Do-List-Application

• Objective: Create a to-do list application where users can add, edit, and delete
tasks.
• Details: Use MongoDB to store tasks, Express.js for server-side operations,
React.js for the user interface, and Node.js for backend logic.

## Installation

1. Download the project as a link https://drive.google.com/drive/folders/1dn9cNSpxh-9sNQCdt9po5_y3Nf4H_KAU?usp=drive_link
2. Extract the downloaded zip file to your preferred location.

3. Open the folder in Visual Studio Code (VSC).

4. Navigate to the directory in the integrated terminal:

   ```bash
   cd MERN-Todo-List-Web-App-main
   ```

5. Navigate to the server directory:

   ```bash
   cd Server
   ```

6. Install server dependencies:

   ```bash
   npm install
   ```

7. Start the server:

   ```bash
   npm start
   ```

8. In MongoDB Compass, connect to your MongoDB instance using the following connection string:

   ```
   mongodb://localhost:27017/
   ```

   - Open MongoDB Compass.
   - Click on "New Connection."
   - Paste the connection string (`mongodb://localhost:27017/`) into the URI field.
   - Click the "Connect" button to establish a connection to your local MongoDB instance.

9. In a separate terminal, navigate to the `todolist` directory:

   ```bash
   cd MERN-Todo-List-Web-App-main/todolist
   ```

10. Install client dependencies:

    ```bash
    npm install
    ```

11. Start the client development server:

    ```bash
    npm run dev
    ```

## Usage

- Access the web app by opening your web browser.

- Use the app to add, edit, delete, and mark tasks as completed.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name (`git checkout -b feature/add-feature`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push your changes to your fork (`git push origin feature/add-feature`).
5. Open a pull request on the original repository.

## License

This project is licensed under the MIT License.
