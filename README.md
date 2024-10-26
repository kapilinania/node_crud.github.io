# Node.js MySQL CRUD Application

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

## 📚 Overview

This project is a simple CRUD (Create, Read, Update, Delete) application built with Node.js and MySQL. It allows users to manage a database of records efficiently.

## 🗄️ Database

### Database Name

- **Database Name**: `crud_db`

### Table Structure

#### Users Table


CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL UNIQUE,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
); 

## 🚀 Getting Started
    Prerequisites
    Node.js (v12 or higher)
    MySQL (v5.7 or higher)

## 🛠️ Features
  Add new users
  View user list
  Update user information
  Delete users
  
## 📄 License
  This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing
  Contributions are welcome! Please open an issue or submit a pull request.
