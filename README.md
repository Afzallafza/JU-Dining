
# JU Dining

JU Dining automates the process of efficiently managing a canteen of a residential hall. It provides a platform for students to order online and get the coupon for their meal virtually. This project also facilitates arranging special holiday feasts for students. The manager of the canteen can see the potential growth of business and the demand for a menu among students.

## Features

- Online meal ordering for students.
- Virtual meal coupons.
- Arrangement of special holiday feasts.
- Insights for managers on business growth and menu demand.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/afzallafza/JU-Dining.git
    cd JU-Dining
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Create a superuser to access the admin panel:**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

7. **Access the application:**

    Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage

1. **Admin Panel:**
    - Go to `http://127.0.0.1:8000/admin/` to manage users, orders, and special feasts.

2. **Manager:**
    - Log in to view business insights and menu demands.
    - Arrange special holiday feasts.

3. **Student:**
    - Log in to order meals online and receive virtual coupons.

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, please contact:

- **Afzal Hossain Babor**
- **Email:afzallafza@gmail.com** 
