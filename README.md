# new-codeee
just testing github
tasks = []

def add_task(task):
    tasks.append(task)

def show_tasks():
   for  i, t in enumerate(tasks, 1):
        print(f"{i}. {t}")

while True:
    cmd = input("Enter command (add/show/exit): ")
    if cmd == "add":
        add_task(input("Task: "))
    elif cmd == "show":
        show_tasks()
    elif cmd == "exit":
        break
