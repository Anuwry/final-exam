# OOP: Final Exam
## Project Overview:
Create the OOP Structure that design and implement a small object-oriented system that simulates a simple delivery service.
## Features:
Creates 4 classes:
Person
```csv
class Person:
    def __init__(self, name):
        self.name = name
```
Customer
```csv
class Customer(Person):
    def __init__(self, name, address):
        super().__init__(name)
        self.address = address
```
Driver
```csv
class Driver(Person):
    def __init__(self, name, vehicle):
        super().__init__(name)
        self.vehicle = vehicle
```
DeliveryOrder
```csv
class DeliveryOrder:
    def __init__(self, customer, item, status):
        self.customer = customer
        self.item = item
        self.status = status
```
### Then main code: 
Creates two customers and one driver.
Each customer places an order.
The driver is assigned to each order.
The driver delivers the orders.
## How to Run:
Just run on python IDE, using 
```csv
python final3.py
```
## Project Structure
```csv
OOP_Final
├── README.md
├── final3.py
```
## Screenshot
### IDE / Bash
<img width="1499" height="546" alt="image" src="https://github.com/user-attachments/assets/0b6a3f91-2b8e-41e7-b82a-ebf694b360f7" />
<img width="653" height="452" alt="image" src="https://github.com/user-attachments/assets/e6584ef5-97b8-46a7-91fc-f2588e7172a6" />

## Project is fully Completed without the bug
