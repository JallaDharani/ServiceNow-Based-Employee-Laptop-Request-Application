# ServiceNow-Based Employee Laptop Request Application

## 📌 Project Overview

The **ServiceNow-Based Employee Laptop Request Application** is a ServiceNow application designed to automate and manage the employee laptop request process.

Employees can submit laptop requests, managers can review and approve requests, and IT teams can manage the fulfillment process.

## 🎯 Objectives

- Provide a centralized laptop request system
- Automate the approval process
- Prevent duplicate laptop requests within a year
- Implement role-based access control
- Track request status
- Improve request management and visibility

## ⚙️ Key Features

- Custom Laptop Request Form
- Record Producer
- Manager Approval Workflow
- Business Rule for duplicate request prevention
- IT Manager and IT Employee roles
- Groups and role mapping
- Access Control Lists (ACLs)
- Email Notifications
- Request Status Tracking
- Update Set for deployment

## 👥 User Roles

### IT Employee
- Create laptop requests
- View requests
- Update requests

### IT Manager
- View laptop requests
- Review requests
- Approve or reject requests

## 🛠️ Technologies

- ServiceNow
- Service Catalog
- Flow Designer
- Business Rules
- ACLs
- JavaScript
- Update Sets

## 🔄 Request Workflow

Employee submits request  
↓  
Request validation  
↓  
Manager approval  
↓  
Approved / Rejected  
↓  
Request status updated

## 🔐 Security

Role-based access is implemented using ACLs.

- `it_employee` — Read, Create, Write
- `it_manager` — Read

## 📂 Documentation

Project documentation and supporting files are available in the [Documentation](Documentation/) folder.

## 📦 Update Set

The exported ServiceNow Update Set XML is available in the [Update-Set](Update-Set/) folder.

## 🎥 Demo

The project demo link is available in the [Demo](Demo/) folder.

## 👩‍💻 Project

**ServiceNow-Based Employee Laptop Request Application**

Developed as part of ServiceNow project/training work.