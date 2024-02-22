# FastAPI Practice Repository

Welcome to the FastAPIPractice Repository! This repository is designed for learning and practicing FastAPI, a modern, fast web framework for building APIs with Python 3.7+ based on standard Python type hints.

## Getting Started

### Prerequisites

Make sure you have Python 3.7 or later installed. You can download Python from [python.org](https://www.python.org/).

### Installation

1. Clone this repository:

   ```
   git clone https://github.com/Raja4959/FastAPIPractice.git
   ```

2. Navigate to the project directory:

   ```
   cd FastAPIPractice
   ```

3. Create a virtual environment (optional but recommended):

   ```
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```
     source venv/bin/activate
     ```

5. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

### Run the FastAPI Application

To run the FastAPI application, use the following command:

```
uvicorn main:app --reload
```

Visit [http://localhost:8000/docs](http://localhost:8000/docs) in your browser to access the interactive API documentation (Swagger UI).

## Project Structure

- `main.py`: Contains the FastAPI application instance and main API routes.
- `app`: Directory for additional FastAPI modules and dependencies.
- `tests`: Directory for writing tests using `pytest`.
- `requirements.txt`: List of project dependencies.

## Contributing

Feel free to contribute to this repository by creating issues or submitting pull requests. Your contributions are highly appreciated!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.