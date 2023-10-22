# todo-cli-go
cli for https://github.com/shubhamvernekar/go-todo-api

# install
1. cd repo
2. go build ./cmd/todo
    this will generate todo executable in root location of repo
3. ./todo -h

# Usages
1. Get All todos
    ```./todo get_all```
2. Get todo by id
    ```./todo -id <todo_id> get```
3. Create todo
    ```./todo -title "your title" create```
4. Mark todo as done
    ```./todo -id <todo_id> mark_done```
5. Delete todo
    ```./todo -id <todo_id> delete```

