# 🚆 RAILWAY RESERVATION & MANAGEMENT SYSTEM (C PROGRAM)

A complete *file-based Railway Reservation System* written in C with:
- Linked List for *Confirmed Ticket Management*
- Queue for *Waiting List Handling*
- Admin authentication (external file: admin.txt)
- Auto Seat Allocation & Real-Time Waiting Promotion
- Permanent storage using text files
- Runs on *Windows, Linux & macOS*

---

##  Features

###  Admin Login System
- Credentials stored in admin.txt
- Validates Username & Password
- Full Admin Control

---

###  Ticket Management

| Feature | Admin |
|--------|:----:|
| Book Ticket | ✔ |
| Cancel Ticket | ✔ |
| Search Passenger | ✔ |
| Update Passenger | ✔ |
| Display Passengers | ✔ |
| Auto-Waiting Promotion | ✔ |
| Logout | ✔ |

---

## 🗂 Data Storage Structure

### Confirmed Passenger File → booked.txt
id name age phone seatNo

makefile
Copy code

Example:
101 Nikhil 20 9876543210 1

102 Manoj 21 9123456780 2

---

### Waiting Passenger File → waiting.txt
id name age phone

makefile
Copy code

Example:
201 Surya 19 9876501234
202 Bala 20 9123456700



---

##  Authentication File Format (admin.txt)

username password


Example:
admin 1234


> Update credentials before deployment

---

##  Admin Menu

Book Ticket

Cancel Ticket

Display Passengers

Search Passenger

Update Passenger

Exit


---

##  Project Structure

Railway-Reservation-System/
├── railway.c
├── admin.txt
├── booked.txt (auto-created)
├── waiting.txt (auto-created)
└── README.md


---

##  Compile & Run

### Windows

gcc railway.c -o railway.exe
.\railway.exe
Linux / macOS


gcc railway.c -o railway
./railway
Example Database After Usage



Confirmed List – booked.txt

101 Nikhil 20 9876543210 1
102 Mani 21 9123456780 2
103 Bala 22 9988776655 3
104 Surya 23 8877665544 4
105 Sam 20 7766554433 5



Waiting List – waiting.txt

201 Hari 21 9090909090
202 Priya 19 9988998899

---

Data Structures Used
Purpose	Data Structure
Confirmed Tickets	Linked List
Waiting List	Queue
Storage	File Handling

---


⚙ Advantages
✔ Automatic seat numbering
✔ Efficient memory usage
✔ Real-time updates
✔ Unlimited waiting list
✔ Fast search and update

---


🧪Tested On
Windows 10/11 (MinGW GCC)

Ubuntu Linux (GCC)

macOS (Clang)

---


 Future Enhancements
✔ Multiple Trains Support
✔ GUI / Mobile App UI
✔ Ticket Print Receipt
✔ Database support (MySQL)
✔ Colored terminal UI
