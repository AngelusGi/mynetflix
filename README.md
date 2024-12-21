# MyNetflix

MyNetflix is a Django-based web application for managing and viewing your personal movie collection.

## Requirements
- Python 3.11
- Django 5.1.x
- Terraform 1.10.x
- Git
- Azure
- GitHub Actions pipeline

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/mynetflix.git
    cd mynetflix
    ```

2. Create and activate a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Create a superuser:
    ```sh
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```sh
    python manage.py runserver
    ```

## Usage

- Access the application at `http://127.0.0.1:8000/`.
- Log in to the admin interface at `http://127.0.0.1:8000/admin/` using the superuser credentials.

## Contributing

Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.