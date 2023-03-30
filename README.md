# todo_app
Simple To Do app created with FastAPI and SQLAlchemy.

Comes with 5 operations:
* create_todo (POST) - create To Do note (/todo)
* read_todo (GET)- read To Do note with specified id (/todo/{id})
* read_todo_list (GET)- read all To Do notes (/todo)
* update_todo (PUT)- update To Do note with specified id (/todo/{id})
* delete_todo (DELETE) - delte To Do note with specified id (/todo/{id})

Notes are written to SQLite database.
