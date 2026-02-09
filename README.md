# EECS449-Extra-Credit-1

By David Smith

UMID: 78206754

The feature I added was an estimate of the time it would take to complete a given task, in minutes. This function is run with the by llm() tag and has semantic context for the llm. The context explains that the estimate is an estimated time to complete the given todo task, and specifies that the return value has the unit of minutes.

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
