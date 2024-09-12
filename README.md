In this project, model events (observers, after deleting, before creating etc) are created, e.g, if a record is deleted then all its associated records from db are also deleted, we can also do this inside Controller
but this is not convinient, so we do this in model class using model events
