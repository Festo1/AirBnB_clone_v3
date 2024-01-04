# `AirBnB_clone_v3`


## Designing a RESTful API with Python and Flask

**# Unlocking a World of Travel Possibilities: The Airbnb Clone RESTful API**

### 0x05. AirBnB clone - RESTful API

![](https://bykowski.pl/wp-content/uploads/2021/06/api-przyklad-dzialania-1.jpg)

**Welcome to the backend API powering an AirBnB clone!** ️ This project demonstrates the development of a robust RESTful API to manage essential functionalities for a web application inspired by AirBnB.

**Forge a gateway to captivating experiences with this RESTful API, inspired by Airbnb.** Designed to power a web application that bridges travelers with remarkable accommodations, this project immerses you in the development of robust backend services.

**## Key Features**

- **Comprehensive Entity Management:**
    - Effortlessly create, read, update, and delete essential entities:
        - Users, each with personalized profiles and preferences
        - Places (accommodations), showcasing unique features, amenities, and availability
        - Amenities, enriching experiences with diverse offerings
        - Bookings, seamlessly managing reservations and guest experiences
- **Uncompromising Security:**
    - Implement robust authentication mechanisms for a trusted environment
    - Carefully manage user permissions to safeguard data integrity
    - Secure authentication and authorization
    -  Robust error handling
- **Exceptional User Experience:**
    - Craft informative error handling for smooth interactions and valuable feedback
    - Provide clear and concise API documentation for effortless navigation
- **Ensuring Code Quality:**
    - Implement thorough unit tests to guarantee code reliability and prevent unexpected errors
- **Clear and concise API documentation**
- **Comprehensive unit tests**

**## Technologies at the Helm:**

- **Python:** The versatile language orchestrating the API's core logic
- **Flask:** A lightweight and adaptable web framework, providing a solid foundation
- **SQLAlchemy:** The ORM skillfully bridging Python and the database
- **PostgreSQL:** A robust database system (or your preferred choice) for data management
- **Flask-RESTful:** Streamlining RESTful API development with ease
- **Flask-JWT-Extended:** Mastering authentication and authorization with JSON Web Tokens

**## Getting Started**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/AirBnB-Clone-RESTful-API.git
   ```
2. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set up environment variables:**
   - Create a `.env` file and add your database credentials and secret keys.

5. **Run the application:**
   ```bash
   flask run
   ```

**## API Documentation**

- **Interactive API documentation:** http://127.0.0.1:5000/api/v1/docs: http://127.0.0.1:5000/api/v1/docs
- **Detailed documentation in README (optional):** Provide clear descriptions of endpoints, request/response formats, and usage examples.

**## Usage Examples**

- **Fetch all places:**
   ```bash
   curl http://127.0.0.1:5000/api/v1/places
   ```
- **Create a new user:**
   ```bash
   curl -X POST -H "Content-Type: application/json" -d '{"username": "johndoe", "email": "johndoe@example.com", "password": "password123"}' http://127.0.0.1:5000/api/v1/users
   ```

**## Contributing**

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Submit a pull request.
