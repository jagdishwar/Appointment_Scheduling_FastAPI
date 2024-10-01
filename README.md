# FastAPI CRUD Application for Users, Meetings, and Unavailability

This project is a FastAPI-based web API that manages users, meetings, unavailability (leaves), and participants. It provides CRUD operations for each entity and supports fetching related data, such as participants of a meeting and a user's unavailability.

## Features

- **Users**: Add, fetch, and manage user data.
- **Meetings**: Create and retrieve meeting information, including participants.
- **Unavailability (Leave)**: Manage unavailability data for users.
- **Participants**: Manage participants and their meetings.
- **Auto-generated documentation**: Access interactive API docs at `/docs`.

## Prerequisites

Before running the application, make sure you have the following installed:

- **Python 3.8+**
- **FastAPI** for the API framework.
- **SQLAlchemy or a database** for data persistence.
  
To install the required Python packages, run:

```bash
pip install fastapi uvicorn
