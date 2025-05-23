# Backend

This directory contains the backend code for the Azure Search OpenAI Demo application.

## Structure

- `api/` - API endpoints and business logic
- `services/` - Integration with Azure services and other utilities
- `requirements.txt` - Python dependencies

## Setup

1. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

2. **Configure environment variables:**  
    Copy `.env.example` to `.env` and update with your Azure credentials.

3. **Run the backend server:**
    ```bash
    uvicorn main:app --reload
    ```

## Features

- Connects to Azure Cognitive Search and OpenAI services
- Exposes RESTful APIs for frontend consumption

## License

See [LICENSE](../LICENSE) for details.