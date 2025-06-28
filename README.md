# shell-fundamentals-alemoh-christian

### 📸 Screenshot 1: Making the Script Executable

![Screenshot1](screenshot1.png)

*I ran chmod +x todo.sh to make the script executable.*

---

### 📸 Screenshot 2: Running the Menu

![Screenshot2](screenshot2.png)

*Shows the script displaying the menu options.*

---

### 📸 Screenshot 3: Adding a Task

![Screenshot3](screenshot3.png)

*Demonstrates using option 2 to add a new task to the todo list.*

---

### 📸 Screenshot 4: Viewing Tasks

![Screenshot4](screenshot4.png)

*Lists tasks using nl to show line numbers for easy reference.*

---

### 📸 Screenshot 5: Deleting a Task

![Screenshot5](screenshot5.png)

*Deletes a task by entering its line number using sed -i.*

---

### ✅ How It Works

- The menu is displayed in a while true loop to keep the program running.
- Tasks are stored in ~/todo.txt so they persist between runs.
- Tasks are numbered using nl so they can be deleted by number.
- New tasks are added using echo with >>.
- Tasks are deleted by line number using sed -i.

---
