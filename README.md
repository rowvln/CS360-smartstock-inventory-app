# SmartStock – Inventory Management App

## Overview
SmartStock is a mobile inventory management app designed to help users track, update, and manage items in a simple and efficient way. The goal of this project was to build something practical that solves a real problem for small teams or individuals who need a lightweight alternative to more complex inventory systems.

This project represents the full development process from planning and UI design to implementation, testing, and refinement.

---

## Problem Statement
A lot of existing inventory tools are either too complex or not optimized for quick, mobile use. I wanted to create something that focuses on usability first, where users can quickly log in, manage items, and move on without unnecessary friction.

---

## Features
- User authentication (account creation and login)
- Add, update, and delete inventory items
- Centralized inventory dashboard
- SQLite database integration for persistent storage
- SMS notification feature with runtime permission handling
- Clean and simple UI focused on usability

---

## Tech Stack
- **Language:** Java  
- **Platform:** Android (Android Studio)  
- **Database:** SQLite  
- **Tools:** Android Emulator, XML layouts  

---

## Application Structure
The app is broken down into a few core components:

- **MainActivity:** Handles login and account creation  
- **InventoryActivity:** Manages inventory display and actions  
- **SmsSettingsActivity:** Handles SMS permissions and settings  
- **DatabaseHelper:** Manages all database operations  

This structure made it easier to separate concerns and keep the app organized as it scaled.

---

## How to Run the App
1. Clone or download this repository  
2. Extract the `SmartStock_App_Code_Design.zip` file  
3. Open the project in Android Studio  
4. Run the app using an emulator or physical device  

---

## Testing and Validation
I tested features as I built them and then validated the full app flow from login to inventory management.

Testing included:
- Verifying login and account creation  
- Confirming inventory data was stored and retrieved correctly  
- Testing CRUD functionality  
- Validating SMS permission behavior (both allowed and denied cases)  

This helped catch issues early and made sure everything worked consistently.

---

## Challenges and Solutions
One challenge was handling both adding new items and updating existing items within the same screen. At first, this caused confusion in both the UI and logic.

I adjusted the flow and UI cues so users could clearly tell what action they were taking. This improved both usability and overall app behavior.

---

## Key Achievement
The strongest part of this project was connecting the inventory system to the database. This showed my ability to tie together front-end interactions with back-end data handling so that user actions resulted in real-time updates.

---

## Reflection
This project focused on building a functional mobile app that solves a real-world problem while keeping the user experience front and center.

I approached development in stages, starting with authentication, then database integration, followed by inventory features and SMS functionality. Breaking it down this way helped me stay organized and made debugging more manageable.

From a design perspective, I focused on keeping the UI simple and intuitive. Screens were designed to reduce friction and make common actions easy to complete. Testing throughout the process helped validate decisions and identify areas for improvement.

Overall, this project reflects my ability to take an idea from concept to a working product while balancing both technical implementation and user-centered design.

---

## Repository Contents
- `SmartStock_App_Code_Design.zip` – Final app code and UI design  
- `README.md` – Project documentation and reflection  

---

## Future Improvements
- Improve UI polish and responsiveness  
- Add search and filtering for inventory  
- Integrate a cloud-based database  
- Expand notification capabilities  

---

## Author
**Rowvin Dizon**  
B.S. Computer Science – Southern New Hampshire University  
