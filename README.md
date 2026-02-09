# EECS449-Extra-Credit-1

By David Smith

UMID: 78206754

The feature I added was an estimate of the time it would take to complete a given task, in minutes. This function is run with the by llm() tag and has semantic context for the llm. The context explains that the estimate is an estimated time to complete the given todo task, and specifies that the return value has the unit of minutes. The code is located in the main.jac file. The node Todo has been updated to have the variable ```est_time```, and there is a function ```estimate_completion_time()``` below the node Todo declaration. In addition to that, functions like ```add_todo``` and ```get_todos``` have been updated to also return the ```est_time``` variable. Lastly, the HTML code at the bottom of the file has been updated to display the estimated time on the far right of the Todo.

# Installation Instructions

Clone this repository
```bash
git clone https://github.com/davidsmith097/EECS449-Extra-Credit-1.git
```

Create a Python virtual environment, either using .venv or anaconda. Then install the [Jaseci](https://docs.jaseci.org/tutorials/#prerequisites) packages and its dependencies.

Once Jaseci is installed, navigate into the my-todo directory and launch the app.
```bash
cd my-todo/
jac start main.jac
```
