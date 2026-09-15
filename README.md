# LoveWeb

## Local development

Start the API from `Backend` with `uvicorn main:app --reload --port 8000`, then serve `Frontend` on port `5500` and open `http://127.0.0.1:5500`.

The SQLite database is stored in `Backend/love_app.db`. A default administrator is created on first startup:

- Username: `Admin`
- Password: `pass`

After logging in, use the **Admin** button to manage users and change the administrator password.
