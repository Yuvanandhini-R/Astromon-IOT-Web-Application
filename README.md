# Astromon-IOT-Web-Application
This working prototype for Astromeda's AstroMon device is a telehealth web application enabling remote ICU monitoring. It allows healthcare staff to securely manage patient data and visualize real-time physiological vitals (ECG, HR) transmitted by the AstroMon wearable via IoT/5G connectivity.

## Overview

The Astromon IoT Web Application is the primary interface for managing and visualizing data collected by the **AstroMon** device—a portable telehealth ICU monitoring system developed by **Astromeda**.

This application is crucial for healthcare professionals, enabling them to remotely monitor patients' physiological parameters (such as ECG, heart rate, temperature, etc.) in real-time via 4G/5G/IoT connectivity.

## Project Status

**Prepared For:** Astromeda Space Private Limited
**Developed By:** Ms. Yuvanandhini T R, Software Development Intern

The recent focus has been on improving the **User Interface (UI)** and addressing critical performance issues related to **real-time data visualization**.

The application is currently a **working prototype** focused on demonstrating core functionality and data visualization. Recent efforts have been directed toward improving the **User Interface (UI)** and addressing critical performance issues related to **real-time data visualization**.

---


## Key Progress and Accomplishments

The following updates detail the transition from the "Old Update" (initial/previous state) to the "New Update" (current state) across various application pages:

### **General UI/UX Improvements**

* **Layout & Alignment:** Finished and refined the layouts for all core pages (Sign In, Sign Up, Forgot Password, Patient Management, Support, and Dashboard).
* **Font and Text Boxes:** Standardized to **Normal font size** and reduced the size of **text boxes** for a cleaner, more professional appearance.
* **Navigation:** **Enabled the Navigation Bar** across all relevant pages (Add Patient, Add Patient Details, Support, and Dashboard) for better site navigation.
* **Responsiveness:** Made **Minor & Major changes in Layout** to support initial responsiveness goals.

### **Functional and Data Visualization Improvements**

| Page/Module | Old Accomplishment | New Accomplishment |
| :--- | :--- | :--- |
| **Dash Board (Main Page)** | Smaller font size, Improper alignment, Time delay in ECG. | **Reduction of Time Delay in the ECG Graph** with proper data generation. Finished layout with an entirely different, cleaner format (Removed Box layout & separate SYS/DIA graphs). |
| **Add Patient Details Page** | Bigger text box size, Smaller font size, No default image. | **Set Default profile image.** Normal font size and text box size. |
| **Support Page** | No Logo, Box layout, Improper alignment. | **Added Logo in Background** and **Removed Box layout** for a refined look. |

---

## High-Priority Risks and Attention Areas

Two major areas require focused development and deep technical study:

### 1. Responsive Web Pages (UI Risk)

* **Description:** The biggest current risk is ensuring the entire website is fully **responsive** across different screen sizes.
* **Challenge:** The project requires significant time to complete the full responsiveness. Improper initial coding has created mismatched alignment, which complicates future development and requires structural correction.

### 2. Noise Reduction in ECG Graph (Core Functionality Risk)

* **Description:** A major technical risk is implementing effective **noise reduction** for the real-time ECG graph data.
* **Challenge:** This is a non-trivial issue to solve. It necessitates a **deep study of the ECG Graph modules** within the existing code structure to stabilize the data feed and minimize the time delay currently impacting the display.

---

## 💻 Technical Setup & Execution

Based on the project structure (`angular.json`, `package.json`, `firebase.json`), this project is an **Angular** application.

### 🛠️ Prerequisites

1.  **Node.js and npm:** (Latest LTS version recommended).
2.  **Angular CLI (Command Line Interface):** Install globally using npm:

    ```bash
    npm install -g @angular/cli
    ```

### ▶️ Installation and Local Run

1.  **Install dependencies:** Navigate to the project root and install all required packages:

    ```bash
    npm install
    ```

2.  **Run the application:** Serve the application on a local development server:

    ```bash
    ng serve
    ```

    Open your web browser and navigate to: **`http://localhost:4200/`**

### 🏗️ Building for Production

To create an optimized, deployable version of the application:

```bash
# Standard build
ng build

# Production build with optimizations
ng build --configuration production
```

The compiled files will be outputted to the `dist/` directory.

## ☁️ Deployment (Firebase)

This project is configured for Firebase hosting.

1.  **Install Firebase CLI** (if needed):

    ```bash
    npm install -g firebase-tools
    ```

2.  **Deploy the application:**

    ```bash
    firebase deploy
    ```
---

## 📝 Documentation and Access

| Item | Link |
| :--- | :--- |
| **Live Astromon IoT Web Application link** | [Astromon IoT Web App](https://astromon-iot.web.app/auth/signin) |
| **Technical Document (PDF)** | [Official Project Document](doc/astromon.pdf) |

---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

---
