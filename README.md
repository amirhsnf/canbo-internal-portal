# Canbo Intranet Portal

**Canbo Intranet Portal** is the internal enterprise portal developed for **Everest Modern Pars Co.**, the parent company of **Canbo** (a major chain of over 1200 retail grocery stores across Iran). This portal was built to digitize and streamline various operational workflows across departments.

> 🚫 **Note:** This is an internal-use system hosted inside the company’s private network and is not publicly accessible.

## 🛠️ Technologies Used

- **Frontend:** Angular  
- **Backend:** PHP  
- **Database:** Microsoft SQL Server  

## ✨ Features & Modules

### 🔸 Group Payment  
For the Finance and Treasury department to upload Excel files of supplier payments, validate IBANs via SAP web service, and process mass payments through Saman Bank's API. Each transaction goes through approval stages and is tracked for status and logs.

![Group Payment](/screenshots/group-payment.jpg)

---

### 🔸 Leaving Work (HR Offboarding Workflow)  
A dynamic multi-step workflow based on the employee's role. Each step has a responsible approver. When it reaches the payment stage, a payment order is created and finalized through the Saman Bank API.

![Leaving Work](/screenshots/leaving-work.jpg)

---

### 🔸 Map  
An interactive geographic interface displaying all regions and stores. Users can filter and view store locations visually.

![Map](/screenshots/map.jpg)

---

### 🔸 Store Cash  
Designed for store managers to register cash bundles with denominations and seal numbers. When the bank agent visits the store, sealed envelopes and logs are handed over securely.

![Store Cash](/screenshots/store-cash.jpg)

---

### 🔸 Fire Extinguisher  
Built for the HSE department to track fire extinguisher counts, refill status, and location (stores, warehouses, or HQ offices).

![Fire Extinguisher](/screenshots/fire-extinguisher.jpg)

---

### 🔸 Store Documents  
A document archive for each store. Regional assistants upload store-related documents for centralized and structured access.

![Store Documents](/screenshots/store-documents.jpg)

---

### 🔸 Truck Traffic  
One of the largest systems in the portal. Tracks truck departure and arrival at warehouses, driver details, cargo, and kilometers traveled. Originally implemented by me and later extended by my colleague **Arman Molaei** with additional features.

![Truck Traffic](/screenshots/truck-traffic.jpg)

---

## 🧑‍💻 Developer Notes

- Entire project (frontend/backend/integration) was bootstrapped at the beginning of my work at **Everest Modern Pars Co.**
- All features listed above were individually designed and implemented by me, except where otherwise noted.
- The portal is fully access-controlled with role-based permissions for different departments.

---

Feel free to reach out if you'd like more technical insight into any part of the system or its architecture.
