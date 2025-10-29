# 💡 Full-Stack Exercise – Smart Customer Support System

## 🏁 Introduction
This exercise is designed to assess your **Full-Stack development skills** using modern technologies.

You are asked to build a **simple yet functional customer support ticket system**, demonstrating your understanding of:
- Frontend and backend integration  
- Data persistence  
- Clean and maintainable code structure  

You may use the **internet** and official **documentation** freely.  
You may also use **AI tools** (such as ChatGPT or Gemini) to assist — **as long as you can explain every line of code** in your project.

> ⚙️ **Note:** The backend should preferably be implemented using **ASP.NET Core Minimal API**.

---

## 🎯 Objective
Build a system that allows:
- Customers to **create new support tickets**
- Users to **view existing tickets**
- Admins to **update ticket status** and **add resolutions**

---

## 🧰 Required Technologies

- **Frontend:** Angular  
- **Backend:** ASP.NET Core Web API *(preferably using Minimal API)*  
- **Data Storage:** JSON file (provided)  
  - All read/write operations must be done on the **server-side only**
  - The frontend should communicate **only via API endpoints**
  - The backend should include **Entities**, **DTOs**, and **Service Classes**

### ✅ Bonus Features
- **JWT Authentication**
- **AI Summary Generation** using OpenAI / Gemini API

---

## 📋 Functional Requirements

### 🔓 Login / Registration Screen *(Bonus)*
- Login using **email and password**
- Basic registration form
- Only logged-in users can access the **Admin Panel**

---

### 📝 New Ticket Screen *(Publicly Accessible)*

**Fields:**
- Full Name  
- Email Address  
- Issue Description  
- Image Upload *(optional)*

**Bonus:**  
While typing the description, call an **AI API** to generate and display a short **summary** of the issue.

**On Submit:**
- Save the ticket data in the JSON file  
- Send an **email to the customer** with a tracking link  

---

### 🔍 Ticket View Screen *(Accessible by Unique ID)*

**Displayed Information:**
- Customer details  
- Issue description  
- AI-generated summary *(if available)*  
- Uploaded image *(if available)*  
- Current status  
- Resolution text *(if available)*

---

### 🛠️ Ticket Management (Admin Panel)

**Accessible only to authenticated users** (if login is implemented)

**Features:**
- Display all tickets in a **table view**
- Filter by:
  - **Status** (dropdown)
  - **Text search** (by name or description)
- Show **full description** and **AI summary**
- Update **status**
- Add or edit **resolution text**
- **Save changes**

---

## 📬 Email Notifications

All emails must be sent via **Gmail SMTP**, using your personal Gmail account.  
❌ Do **not** use third-party email-sending services.

Send an email to the customer:
1. After creating a new ticket  
2. Whenever the **status** changes  
3. Whenever the **resolution text** changes  

---

## ✅ Bonus Features Summary

| Feature | Description |
|----------|--------------|
| **Authentication (JWT)** | Login & role-based authorization for admin access |
| **AI Summary** | Generate a short summary for the issue using an AI API |
| **UI/UX Design** | Clean, responsive, and accessible interface |

---

## 📸 Example Screens

The system includes the following key screens:

1. **Login Screen** – for authentication *(bonus)*  
2. **New Ticket Form** – for customers to submit issues  
3. **Ticket View** – detailed view by unique ID  
4. **Ticket Management Panel** – admin interface for handling and resolving tickets  

---

## 🚀 Submission

Please submit your solution as a **GitHub repository link** containing both the **Angular frontend** and the **.NET backend** projects.  
Make sure your repository includes:
- A clear **README.md** explaining setup and run instructions  
- All necessary configuration files (e.g., `appsettings.json`, `angular.json`)  
- The provided **JSON file** with sample data  

---

### 🧾 Evaluation Criteria
| Category | Description |
|-----------|-------------|
| **Functionality** | Meets all required features and flows |
| **Code Quality** | Clean, modular, and maintainable |
| **Architecture** | Proper separation of frontend, backend, and services |
| **UI/UX** | User-friendly, clear, and responsive design |
| **Bonus Features** | Implementation of Authentication and AI integration |
| **Documentation** | Clear instructions and explanation of the solution |

---

🧠 *Good luck and have fun building!*
רוצה שאהפוך את זה עבורך עכשיו ל־קובץ README.md אמיתי שאפשר להוריד או להעלות ל־GitHub ישירות?
אם תגיד “כן”, אצור את הקובץ ואשלח לך לינק להורדה.

You said:
Can you put the images too in the markup?
ChatGPT said:
Perfect 🔥
Below is your final GitHub-ready README.md — fully formatted in GitHub Markdown style, including the screenshots you provided (embedded cleanly).
This version is ready to drop straight into your repo’s root folder.

# 💡 Full-Stack Exercise – Smart Customer Support System

## 🏁 Introduction
This exercise is designed to assess your **Full-Stack development skills** using modern technologies.

You are asked to build a **simple yet functional customer-support ticket system**, demonstrating your understanding of:
- Frontend and backend integration  
- Data persistence  
- Clean and maintainable code structure  

You may use the **internet** and official **documentation** freely.  
You may also use **AI tools** (such as ChatGPT or Gemini) — **as long as you can explain every line of code** in your project.

> ⚙️ **Note:** The backend should preferably be implemented using **ASP.NET Core Minimal API**.

---

## 🎯 Objective
Build a system that allows:
- Customers to **create new support tickets**
- Users to **view existing tickets**
- Admins to **update ticket status** and **add resolutions**

---

## 🧰 Required Technologies

- **Frontend:** Angular  
- **Backend:** ASP.NET Core Web API *(preferably using Minimal API)*  
- **Data Storage:** JSON file (provided)  
  - All read/write operations must be done on the **server-side only**
  - The frontend should communicate **only via API endpoints**
  - The backend should include **Entities**, **DTOs**, and **Service Classes**

### ✅ Bonus Features
- **JWT Authentication**
- **AI Summary Generation** using OpenAI / Gemini API

---

## 📋 Functional Requirements

### 🔓 Login / Registration Screen *(Bonus)*
- Login using **email and password**
- Basic registration form
- Only logged-in users can access the **Admin Panel**

---

### 📝 New Ticket Screen *(Publicly Accessible)*

**Fields:**
- Full Name  
- Email Address  
- Issue Description  
- Image Upload *(optional)*

**Bonus:**  
While typing the description, call an **AI API** to generate and display a short **summary** of the issue.

**On Submit:**
- Save the ticket data in the JSON file  
- Send an **email to the customer** with a tracking link  

---

### 🔍 Ticket View Screen *(Accessible by Unique ID)*

**Displayed Information:**
- Customer details  
- Issue description  
- AI-generated summary *(if available)*  
- Uploaded image *(if available)*  
- Current status  
- Resolution text *(if available)*

---

### 🛠️ Ticket Management (Admin Panel)

**Accessible only to authenticated users** (if login is implemented)

**Features:**
- Display all tickets in a **table view**
- Filter by:
  - **Status** (dropdown)
  - **Text search** (by name or description)
- Show **full description** and **AI summary**
- Update **status**
- Add or edit **resolution text**
- **Save changes**

---

## 📬 Email Notifications

All emails must be sent via **Gmail SMTP**, using your personal Gmail account.  
❌ Do **not** use third-party email-sending services.

Send an email to the customer:
1. After creating a new ticket  
2. Whenever the **status** changes  
3. Whenever the **resolution text** changes  

---

## ✅ Bonus Features Summary

| Feature | Description |
|----------|--------------|
| **Authentication (JWT)** | Login & role-based authorization for admin access |
| **AI Summary** | Generate a short summary for the issue using an AI API |
| **UI/UX Design** | Clean, responsive, and accessible interface |

---

## 📸 Example Screens

The system includes the following key screens:

1. **Login Screen** – for authentication *(bonus)*  
2. **New Ticket Form** – for customers to submit issues  
3. **Ticket View** – detailed view by unique ID  
4. **Ticket Management Panel** – admin interface for handling and resolving tickets  

### 🖼️ Screenshots

| Login | New Ticket | Ticket Management |
|:------:|:-----------:|:----------------:|
| ![Login Screenshot](./Picture1.png#gh-light-mode-only) | ![New Ticket Screenshot](./Picture1.png#gh-light-mode-only) | ![Ticket Management Screenshot](./Picture1.png#gh-light-mode-only) |

*(Use your own screenshots here or replace `Picture1.png` with multiple distinct images if available.)*

---

## 🚀 Submission

Please submit your solution as a **GitHub repository link** containing both:
- The **React frontend**
- The **.NET backend**

Your repository must include:
- A clear **README.md** with setup and run instructions  
- All configuration files (e.g., `appsettings.json`, `appsettings.develpment.json`)  
- The provided **JSON data file**

---

## 🧾 Evaluation Criteria

| Category | Description |
|-----------|-------------|
| **Functionality** | Meets all required features and flows |
| **Code Quality** | Clean, modular, and maintainable |
| **Architecture** | Proper separation of frontend, backend, and services |
| **UI/UX** | User-friendly, clear, and responsive design |
| **Bonus Features** | Authentication and AI integration implemented |
| **Documentation** | Clear setup instructions and explanations |

---

🧠 *Good luck and have fun building!*




