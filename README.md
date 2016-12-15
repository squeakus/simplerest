
get a list of tasks:
curl -i http://localhost:5000/todo/api/v1.0/tasks

get a particular task:
curl -i http://localhost:5000/todo/api/v1.0/tasks/<id>

curl -i -H "Content-Type: application/json" -X POST -d '{"title":"Read a book"}' http://localhost:5000/todo/api/v1.0/tasks
