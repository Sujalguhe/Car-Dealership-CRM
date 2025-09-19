# 🚗 Car Dealership CRM (Salesforce Project)

This project is a **Salesforce CRM application** designed to manage a car dealership’s operations, including **Cars, Customers, and Test Drives**.  
It showcases Salesforce **Admin + Developer** skills like custom objects, validation rules, reports, dashboards, email automation, and a basic Lightning Web Component (LWC) interface.  

## 📌 Features Implemented

### 🔹 Data Modeling
- Custom Objects: `Car`, `Customer`, `Test Drive`
- Fields for each object (Car Name, VIN, Price, Customer Email, Test Drive Date, etc.)
- Relationships: Lookup relationships between Cars, Customers, and Test Drives

### 🔹 Validation Rules
- **Car:** Price must be > 0, VIN must be 17 characters  
- **Customer:** Phone number must be 10 digits  
- **Test Drive:** Date must be scheduled in the future  

### 🔹 Automation
- **Workflow Rules & Email Alerts**
  - Email to customer when a test drive is scheduled  
  - Reminder email 1 day before the test drive  
- **Classic Email Templates** used for notifications  

### 🔹 Reporting & Dashboards
- Reports for Cars, Customers, and Test Drives  
- Dashboard showing dealership insights (scheduled drives, car inventory, customer list)  

### 🔹 User Interface
- Lightning App with custom tabs for Cars, Customers, and Test Drives  
- LWC component with a simple homepage UI:
  - Welcome message  
  - Tabs for viewing Cars, Customers, and Test Drives  
  - Record lists showing key fields  

## 🛠️ Tools & Technologies
- **Salesforce Platform** (Developer Edition)  
- **Admin Configurations:** Objects, Fields, Validation Rules, Reports, Dashboards, Workflow  
- **Developer Side:** Apex (minimal), LWC for simple UI  
- **Experience Cloud Site** for external access (basic)  

## 📂 Project Phases Completed
1. Problem Understanding & Industry Analysis  
2. Org Setup & Configuration  
3. Data Modeling & Relationships  
4. Process Automation (Validation Rules, Workflows, Email Alerts)  
5. Apex Programming (minimal usage)  
6. User Interface Development (Lightning App + LWC)  
8. Data Management & Deployment (Dummy data + reports)  
9. Reporting, Dashboards & Security Review  

## 🚀 How to Use
1. Clone or download this repository  
2. Deploy metadata to your Salesforce Developer Org  
3. Add dummy data (Cars, Customers, Test Drives)  
4. Explore reports, dashboards, and the LWC homepage  

## 📌 Future Enhancements
- WhatsApp integration for test drive alerts  
- Advanced LWC forms to create new Cars, Customers, and Test Drives directly from UI  
- Role-based dashboards for sales team vs management  

## 👨‍💻 Author
**Sujal Rajesh Guhe**  
Salesforce Admin & Developer | CRM Enthusiast  
