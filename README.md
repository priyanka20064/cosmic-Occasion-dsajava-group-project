<h1># cosmic-Occasion-dsajava-group-project</h1>
# 🎉 Java Event Management System

Welcome to our **Java-based Event Management System** – a terminal application designed to handle clients, events, bookings, and expense tracking in an organized and user-friendly way.

👩‍💻 **Project Members**:  
- Priyanka *(me)*  
- Mahi Awasthi  
- Mehak  
- Komal  

📚 **Project Type**: Academic project for evaluation  
🛠 **Language Used**: Java  
🖥️ **Interface**: Console-based (Terminal)

---

## 💡 Features

Here’s what you can do with this project:

### 👤 Client Management
- Add client (with validation for phone number)
- View all clients

### 📅 Event Management
- Add new events (date must be in future)
- View all events using Inorder Traversal (BST)
- Update existing event
- Delete event
- Search event by ID

### 🧾 Booking System
- Book an event for a client
- View all bookings (using a queue)

### 💸 Budget and Expense Manager
- Set a budget
- Add expenses (categorized)
- Remove expenses
- View all expenses
- View current balance

---

## 🔧 Technologies & Concepts Used

- Java Collections:
  - `LinkedList` for client storage
  - `Queue` for booking management
  - `Binary Search Tree` (custom) for storing events
- OOP Concepts: Classes, Inheritance, Encapsulation
- Input validation
- Console interaction using `Scanner`
- Enum usage for categorized expenses
- Utility methods for date & phone validation
![image](https://github.com/user-attachments/assets/d67521ef-b6f0-4b6d-8471-9f492b60d7fe)

---

## 🚀 How to Run the Project

1. 📥 **Clone or Download** the project files.

3. ✅ Make sure Java is installed (Java 8 or above).

4. Open terminal and compile:
   ```bash
   javac Main.java
Run the program:

javac Main.java then java Main
🧠 Follow the menu-driven options and enter the corresponding number to use any functionality.
<hr>
🚀 Screenshot


![image](https://github.com/user-attachments/assets/e6eea3ea-86d0-4041-82af-c037e9f44139)<br>
Figure . First Client added Successfully


![image](https://github.com/user-attachments/assets/2590633e-486a-4846-8171-8b24c668f930)<br>
Figure. Second Client added Successfully


 ![image](https://github.com/user-attachments/assets/d17ee838-98aa-4f6f-acf5-036566d67d9c)<br>
Figure.  Adding Event but Date must be in Future

 ![image](https://github.com/user-attachments/assets/28a7c238-7141-4208-89fd-62b04c87ce58)<br>

Figure.  First Event added Successfully


 ![image](https://github.com/user-attachments/assets/dc4064cc-d994-45c8-9eb3-82f2df740007)<br>

Figure.  Second Event added Successfully

 ![image](https://github.com/user-attachments/assets/dd2df525-e37a-412c-8b69-d509503df7a8)<br>

Figure.  Viewing Clients in Sorted order


 ![image](https://github.com/user-attachments/assets/614d3d78-08d0-4413-b056-301ceb236b41)<br>

Figure.  Searching Event By Its Name

 ![image](https://github.com/user-attachments/assets/62b92be5-09ff-4788-a30d-bd4e31c5b79e)<br>

Figure. Booking First Event with Client and Event


 ![image](https://github.com/user-attachments/assets/3f3a34bb-8106-4d43-9355-c9a5174b1451)<br>

Figure.  Booking Second Event with Client and Event

 ![image](https://github.com/user-attachments/assets/32db2ccc-aca2-4e0c-a5ff-300325ab3aee)<br>

Figure.  Viewing Bookings



 ![image](https://github.com/user-attachments/assets/3abe5c44-3580-4dc6-9e1d-5ae7c8d02a82)<br>

Figure.  Setting Budget for the Event

 ![image](https://github.com/user-attachments/assets/12db4528-4240-4323-bc5c-3c7586f93116)<br>

Figure.  Adding Expense


 ![image](https://github.com/user-attachments/assets/abc8395d-4200-45e8-acb3-6c3b97740a0b)<br>

Figure. Viewing Expense

 ![image](https://github.com/user-attachments/assets/abb7244d-cac1-424f-bc2f-44205fd04319)<br>

Figure. Viewing Balance

 ![image](https://github.com/user-attachments/assets/f718dd46-53c3-4a88-8fd8-a10d10699297)<br>

Figure. Updating Event

 ![image](https://github.com/user-attachments/assets/04a9ead1-f202-4c34-9f29-3672834a963f)<br>

Figure. Searching Event By its Name


 ![image](https://github.com/user-attachments/assets/5877096b-bcd5-4e2e-ac5b-c9315a631321)<br>

Figure. Viewing Events Sorted By Date

 ![image](https://github.com/user-attachments/assets/73dce6e9-7eff-4656-bc71-dac3baa827b4)<br>

Figure.  Exit
<hr>
📌 Notes
Dates must be in the format yyyy-MM-dd and should be in the future.

Phone numbers must be 10 digits.

Events are stored in a Binary Search Tree and displayed in sorted order using Inorder traversal.

Bookings are handled using a queue to ensure FIFO order.

Expenses are managed with categories (via Enum) and compared with the set budget.

🎓 Made With ❤️ By
Priyanka, Mahi Awasthi, Mehak & Komal
For our project evaluation 📝 at Chitkara University.

