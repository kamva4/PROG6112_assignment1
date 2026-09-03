# PROG6112_assignment1
# Hospital Patient Management System

A Java-based Hospital Management System developed as part of a Java Programming assignment. The system manages patient registration, bed allocation, and ward management using OOP principles.

## Features

### 1. Patient Management (PatientManager)
- Register new patients with unique ID validation
- Prevent duplicate patient IDs
- Search patient by ID
- Delete patient by ID
- Sort patients by surname (alphabetical)
- Display all patients report

### 2. Bed Management (BedManager)
- 20-bed ward management (B01 - B20)
- Allocate available beds
- Prevent allocation of occupied beds
- Release beds
- Check if ward is full
- View available beds

### 3. Patient Categories (Enum)
- OUTPATIENT
- INPATIENT
- EMERGENCY
- ICU

## Project Structure

## Technologies Used
- Java 17+
- Maven
- JUnit 4.13.2 for unit testing
- NetBeans IDE

## How to Run

### 1. Run Main Application
Right-click `HospitalSystem.java` > **Run File**


### 2. Run Unit Tests
Right-click project `HospitalSystem` > **Test**
or Right-click `HospitalSystemTest.java` > **Test File**

Expected Result:

## Unit Tests Covered

| Test Method | Description |
|-------------|-------------|
| testRegisterPatient | Tests successful registration |
| testPreventDuplicateIds | Ensures duplicate IDs are blocked |
| testSearchPatient | Tests search by ID |
| testDeletePatient | Tests deletion |
| testAllocateBed | Tests bed allocation |
| testPreventAllocatingOccupiedBed | Prevents double booking |
| testReleaseBed | Tests bed release |
| testIsWardFull | Tests ward full logic (20 beds) |
| testSortBySurname | Tests alphabetical sorting |

All tests use JUnit assertions: `assertTrue`, `assertFalse`, `assertNotNull`, `assertEquals`.

## OOP Principles Applied
- **Encapsulation:** Private fields with getters/setters in Patient class
- **Enum:** PatientCategory for type safety
- **ArrayList & HashMap:** For dynamic patient and bed management
- **Separation of Concerns:** Manager classes separate from model

## Author
Student Name: Sibahle Bovungana
Student No: ST10526443
Module: Java Programming

## License
Academic Project - For educational purposes only.
