# todo_app
Simple To Do app created with FastAPI and SQLAlchemy.

Comes with 5 operations:
* create_todo - create To Do note [POST](/todo)
* read_todo - read To Do note with specified id [GET](/todo/{id})
* read_todo_list - read all To Do notes [GET](/todo)
* update_todo - update To Do note with specified id [PUT](/todo/{id})
* delete_todo - delte To Do note with specified id [DELETE](/todo/{id})

Notes are written to SQL lite database.
