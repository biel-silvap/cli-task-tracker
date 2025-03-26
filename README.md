# CLI Task Tracker

A simple CLI task tracker, build with raw php for study purposes. It can add tasks, list with task status filter, mark tasks as "todo", "in-progress" or "done", update the task description, delete and prune tasks, using just a json file as storage. The objective is to create a simple and fast script using just one file with the best practices to manage and track a few tasks.

Take a look and leave me a star, suggest any feature or change. Feel free to fork the script.

## Requirements

- PHP >= 8.4

## Instalation

For any bash based terminal:

Clone the repository:
```sh
git clone https://github.com/biel-silvap/cli-task-tracker.git

# or if you use SSH
git clone git@github.com:biel-silvap/cli-task-tracker.git 
```

Move the project directory to your "/opt"
```sh
sudo mv path/to/project /opt
```

Adjust the permission, so your user can execute the script
```sh
sudo chmod 755 /opt/cli-task-tracker/bin/task-tracker
```

To execute the script calling the "task-tracker" command, add the trask-tracker bin directory to your path
```sh
echo "export PATH=\$PATH:/opt/cli-task-tracker/bin" >> $HOME/.bashrc
```

## Usage

Check the "help" command for the available functions
```sh
task-tracker help
```
