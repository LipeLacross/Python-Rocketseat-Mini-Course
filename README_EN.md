## 🌐 [Versão em Português do README](README.md)

# Python-Rocketseat-Mini-Course
# E-commerce Flask Application

This is an e-commerce application developed with Flask. It provides features for product creation and management, user authentication, and shopping cart operations.

## 🔨 Project Features

- **User Authentication**:
    - User registration and login.
    - Session management and logout.

- **Product Management**:
    - Add, update, view, and delete products.

- **Shopping Cart**:
    - Add and remove items from the cart.
    - View cart contents.
    - Checkout and clear the cart.

### Project Visual Example

![Screenshot 2024-09-11 183553](https://github.com/user-attachments/assets/8737a026-d079-4e64-a6c5-5c983c41f80d)
![Screenshot 2024-09-11 184640](https://github.com/user-attachments/assets/8c3d7381-c9fd-434c-bb83-79fd9fb91947)
![Screenshot 2024-09-11 185002](https://github.com/user-attachments/assets/c4d99af3-80a5-4093-a7f4-7af4215d2911)
![Screenshot 2024-09-11 185615](https://github.com/user-attachments/assets/368cd3d3-8902-435d-9515-a5641d87a9c2)
![Screenshot 2024-09-11 185555](https://github.com/user-attachments/assets/5f531acd-9d85-4a40-849b-18d009ad4473)
![Screenshot 2024-09-11 185320](https://github.com/user-attachments/assets/ebccd156-35b1-486a-86a8-c08d0e9f60c5)

To view the application, access the local URL at `http://127.0.0.1:5000` after starting the server.

## ✔️ Techniques and Technologies Used

- **Flask**: Web framework used to build the application.
- **Flask-SQLAlchemy**: ORM for interacting with the SQLite database.
- **Flask-Login**: Session management and user authentication.
- **Flask-Cors**: Support for CORS to allow cross-origin requests.
- **SQLite**: Database used to store product, user, and cart information.

## 📁 Project Structure

- **app.py**: Main Flask application file, containing route definitions and business logic.
- **ecommerce.db**: SQLite database that stores users, products, and cart items.
- **requirements.txt**: List of project dependencies.

## 🛠️ Running the Project

To run the project locally, follow the steps below:

1. **Ensure Python is Installed**:
    - [Python](https://www.python.org/) is required to run the project. You can check if it's installed with:

      ```bash
      python --version
      ```

    - If not installed, download and install the recommended version.

2. **Create and Activate a Virtual Environment**:
    - Create a virtual environment with the command:

      ```bash
      python -m venv .venv
      ```

    - Activate the virtual environment:
        - On Windows:

          ```bash
          .venv\Scripts\activate
          ```

        - On macOS and Linux:

          ```bash
          source .venv/bin/activate
          ```

3. **Install Dependencies**:
    - Run the following command to install the dependencies listed in `requirements.txt`:

      ```bash
      pip install -r requirements.txt
      ```

4. **Start the Server**:
    - Run the following command to start the Flask server:

      ```bash
      python app.py
      ```

    - The application will be available at `http://127.0.0.1:5000`.

5. **Access the Application**:
    - Open a web browser and go to `http://127.0.0.1:5000` to interact with the application.

## 🌐 Deploy

To deploy the application on a production server, follow the appropriate steps for the chosen server. Configure the server to use WSGI (such as Gunicorn or uWSGI) and a reverse web server (such as Nginx) to ensure efficient and secure operation of the application.
