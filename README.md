# Public API

This is a simple public API built with Express.js that returns basic information in JSON format.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/obinnafranklinduru/hng-task-0-public-api.git
   cd your-repo
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   ```

The server will start on port 3000 by default. You can change the port by setting the `PORT` environment variable.

### Endpoint

**GET** `/`

### Request

No request body or parameters are required.

### Response

- **200 OK**

  ```json
  {
    "email": "your-email@example.com",
    "current_datetime": "2025-01-30T09:30:00Z",
    "github_url": "https://github.com/yourusername/your-repo"
  }
  ```

### Example Usage

```bash
curl -X GET http://localhost:3000/
```

## Response Time

The API is designed to have a fast response time, typically under 500ms.

---

Looking to hire skilled Node.js developers? Check out [HNG's Node.js Developers Hiring Page](https://hng.tech/hire/nodejs-developers) to find top talent for your projects!
