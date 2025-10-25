# To-Do-List

tasks = []

def add_task(task):
    tasks.append(task)
    print(f"Task '{task}' added!")

def show_tasks():
    if tasks:
        print("Your tasks:")
        for i, task in enumerate(tasks, 1):
            print(f"{i}. {task}")
    else:
        print("No tasks yet!")

add_task("Learn Python")
add_task("Build a project")
show_tasks()
