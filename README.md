

# Task Project Assesment



- I created the Task model
- Then in the Task Model I defined the attributes and the relationship with the User model using the belongsTo method
- Created the migration.
- In the migration file I updated it with the necessary columns, including the user_id foreign key
- Defined the relationship in the User model, indicating inverse relationship between the User model and the Task model, where a user has many tasks
- Then Created the Task-controller and action where we retrieve the currently authenticated user and fetch their tasks. Then, we pass the tasks to a view named tasks.index
- I created a route that maps to the index method of the TaskController, allowing users to view their tasks.
- Lastly I created a new directory named tasks under the resources/views directory. Inside the tasks directory, I created a new file named index.blade.php. 
## License

 [MIT license](https://opensource.org/licenses/MIT).
