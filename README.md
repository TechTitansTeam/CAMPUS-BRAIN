# 🎓 CampusBrain – Smart Campus Management Platform 

**CampusBrain** is a web-based campus management platform designed to make academic resources more accessible and organized for students and faculty.

This repository contains the **prototype version of our CampusBrain project**. It demonstrates the proposed user interface, design, and basic workflow of the platform. The prototype serves as an initial model for future development and improvement.

## 🚀 Project Overview

CampusBrain aims to provide a centralized platform where faculty members can share academic materials and students can easily find, view, and download them.

The platform is designed around two primary user roles:

- **Faculty:** Upload and share academic materials with students.
- **Students:** Search for and access academic materials based on their academic year, semester, and file type.

The current prototype focuses on frontend design, user interaction, and demonstrating the proposed workflow.

## ✨ Key Features

- 🎨 Modern and user-friendly interface
- 🎓 Campus-focused academic resource management
- 👨‍🏫 Faculty interface for uploading academic files
- 🎓 Student interface for accessing learning materials
- 🔐 Separate student and faculty registration and login interfaces
- 📚 Academic material filtering by year and semester
- 🔎 Search and filter options for different types of files
- 📥 Options to view and download available academic materials
- 📱 Responsive design for different screen sizes
- 🧭 Simple navigation between interface sections

*Note: The availability and functionality of individual features depend on the current prototype implementation.*

## 🌐 Live Prototype

Explore the deployed CampusBrain frontend prototype using the link below:

**[Open CampusBrain Prototype](https://techtitansteam.github.io/CAMPUS-BRAIN/)**

## 🧪 How to Test the CampusBrain Prototype

To test the proposed faculty-to-student academic material sharing workflow, you can create two separate accounts: one Faculty account and one Student account.

Follow the steps below to explore the platform and test its intended functionality.

### Step 1: Open the Live Prototype

Visit the website:

**[https://techtitansteam.github.io/CAMPUS-BRAIN/](https://techtitansteam.github.io/CAMPUS-BRAIN/)**

### Step 2: Create Both Student and Faculty Accounts

1. Open the CampusBrain prototype.
2. Register a new account by selecting the **Faculty** role.
3. Complete the registration process and log in using the Faculty account.
4. Log out of the Faculty account.
5. Register another account by selecting the **Student** role.
6. Complete the registration process and log in using the Student account.

**Important:** You need both accounts to test the proposed faculty-to-student academic material sharing workflow. Use the appropriate account to access each role's interface.

### Step 3: Test the Faculty Interface

Log in using the Faculty account and follow these steps:

1. Navigate to the faculty dashboard or academic file upload section.
2. Select the relevant academic year.
3. Choose the appropriate semester.
4. Select the type of academic material you want to upload, such as:
   - Notes
   - Lab Manuals
   - Assignments
   - Question Papers
   - Other academic materials
5. Choose the respective file and upload it, if file uploading is supported by the current prototype.
6. Check whether the uploaded material appears in the faculty interface.

### Step 4: Test the Student Interface

After uploading academic material through the Faculty account:

1. Log out of the Faculty account.
2. Log in using the Student account.
3. Navigate to the student dashboard or academic materials section.
4. Search for academic materials using the available filters:
   - **Academic Year:** 1st Year, 2nd Year, 3rd Year, or 4th Year.
   - **Semester:** Semester 1 or Semester 2.
   - **File Type:** Notes, Lab Manuals, Assignments, Question Papers, etc.
5. Submit the search or apply the selected filters.
6. Check whether the matching academic materials are displayed.
7. If the material is available and downloading is implemented, open or download the file.

### Step 5: Verify the Complete Workflow

The intended workflow of CampusBrain is:

**Faculty Account → Upload Academic Material → Student Account → Search by Year, Semester, and File Type → View or Download Material**

**Example:**

Suppose a faculty member uploads a lab manual for second-year students in the first semester.

A student can then log in to the Student account, select **2nd Year**, **Semester 1**, and **Lab Manual**, and search for the relevant academic material.

If the upload, storage, and sharing features are implemented correctly, the student should be able to find and download the uploaded file.

*The results of these tests depend on the features supported by the current prototype. This example describes the intended workflow and does not guarantee that every step is fully functional in the deployed version.*

## 🛠️ Technologies Used

The CampusBrain prototype uses the following technologies:

- **HTML5** – Webpage structure
- **CSS3** – Styling and responsive design
- **JavaScript** – Frontend interactions
- **Java Spring Boot** – Backend development environment intended for future integration

## 💻 How to Run the Prototype Locally

Follow these steps to run the frontend prototype on your computer.

### 1. Clone the Repository

Open a terminal or command prompt and run:

```bash
git clone https://github.com/25A31A05GF/CAMPUSBRAIN.git
```

### 2. Open the Project Folder

Navigate to the downloaded project directory:

```bash
cd CAMPUSBRAIN
```

### 3. Navigate to the `docs` Folder

Open the `docs` directory containing the frontend prototype.

### 4. Launch the Website

Open `index.html` in your web browser to explore the interface.

Alternatively, visit the [live CampusBrain prototype](https://techtitansteam.github.io/CAMPUS-BRAIN/).

## 🌿 Repository Branch

The current CampusBrain prototype files are maintained in the **`master`** branch of this GitHub repository.

The `master` branch contains the frontend prototype source code and related project files used to develop and demonstrate the CampusBrain interface.

## ⚠️ Prototype Limitations

CampusBrain is an **early-stage prototype** intended to demonstrate the concept, interface, and proposed workflow of the platform.

The following limitations may apply, depending on the current implementation:

- Some features may be visual demonstrations rather than fully functional features.
- Registration and login may not provide secure or persistent authentication.
- Creating separate Student and Faculty accounts does not necessarily mean that the accounts share data.
- Files uploaded through the Faculty interface may not be stored permanently or made available to Student accounts.
- Search filters may not retrieve actual uploaded files if the required backend functionality is unavailable.
- File viewing and downloading depend on how file storage and retrieval are implemented.
- A shared database, file storage system, and properly deployed backend are needed for reliable academic material sharing across accounts and devices.
- Additional development, security improvements, and testing are required before production use.

**Important:** Creating both accounts allows you to test the separate Student and Faculty interfaces. However, the complete file-sharing workflow will work only if the relevant functionality has been implemented and connected correctly.

## 🔮 Future Enhancements

- Implement secure student and faculty registration and authentication.
- Integrate a shared database for persistent account and academic data storage.
- Connect the frontend to the Java Spring Boot backend.
- Enable faculty members to upload, manage, update, and delete academic materials.
- Allow students to search by academic year, semester, subject, and file type.
- Implement reliable file storage, retrieval, viewing, and downloading.
- Develop dedicated dashboards for students and faculty.
- Introduce role-based access control to protect academic resources.
- Improve input validation, security, error handling, and user experience.
- Deploy the complete application with backend and database support.

## 🎯 Project Objective

The objective of CampusBrain is to develop a centralized campus management platform that simplifies academic resource sharing between faculty and students.

By organizing learning materials according to academic year, semester, and file type, CampusBrain aims to help students access the resources they need more conveniently while providing faculty members with a straightforward way to share academic materials.

## 👥 Project Status

**Status:** Prototype / Initial Development

This version represents the initial prototype of CampusBrain and serves as a foundation for future improvements, testing, and development.

The current focus is on demonstrating the proposed interface and user workflow, with additional backend integration and functionality planned for future development.

---

*CampusBrain – Building a smarter campus experience.*
