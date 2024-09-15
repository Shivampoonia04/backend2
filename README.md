# Fruit.ai Backend

## Setup

1. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask app:

    ```bash
    python app.py
    ```

## API Endpoints

- `GET /faqs` - Fetch all FAQs
- `GET /faqs/<id>` - Fetch an FAQ by ID
- `POST /faqs` - Create a new FAQ
- `PUT /faqs/<id>` - Update an FAQ by ID
- `DELETE /faqs/<id>` - Delete an FAQ by ID
