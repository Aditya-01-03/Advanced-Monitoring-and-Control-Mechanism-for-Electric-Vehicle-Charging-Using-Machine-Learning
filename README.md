# ⚡Advanced-Monitoring-and-Control-Mechanism-for-Electric-Vehicle-Charging-Using-Machine-Learning 🚗🔋
This project focuses on optimizing electric vehicle (EV) charging stations using machine learning to predict the best charging current while ensuring safety, efficiency, and fault detection.


![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Django](https://img.shields.io/badge/Django-4.0-green?style=flat&logo=django)
![React.js](https://img.shields.io/badge/React.js-18.0-blue?style=flat&logo=react)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?style=flat&logo=mysql)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

---

**Smart EV Charging Station - Monitoring & Control** is a **real-time monitoring and optimization system** designed for **intelligent EV charging management**.  
It leverages **IoT, Machine Learning, and Cloud Computing** to ensure:

✅ **Optimized Charging**: Adjust voltage/current for faster & safer charging.  
✅ **Energy Demand Prediction**: Use **Machine Learning** to forecast consumption.  
✅ **Fault Detection & Alerts**: Identify **overvoltage, overheating, and anomalies**.  
✅ **Grid Integration**: Load balancing for **efficient power distribution**.  
✅ **Real-time Monitoring**: Visualize data using **interactive dashboards**.  

---

## 🚀 Features

- 🔍 **Real-time Data Monitoring**: Voltage, Current, Power, Battery Temperature.
- ⚡ **Dynamic Charging Adjustment**: Auto-optimizes voltage/current to prevent overload.
- 📊 **ML-Based Demand Prediction**: Uses **Linear Regression, XGBoost, LSTMs** for forecasts.
- 🛠️ **Fault Detection & Alerts**: Detects **anomalies, power surges, and overheating**.
- 📡 **IoT Communication**: Uses **ESP32/Raspberry Pi** with **MQTT for live data**.
- 📊 **Web Dashboard**: **React.js frontend** for real-time data visualization.

---

## 🛠️ Technologies Used

| **Technology** | **Purpose** |
|---------------|------------|
| **Django** | Backend & API Handling |
| **Django REST Framework** | API Development |
| **React.js** | Interactive Web Dashboard |
| **Scikit-Learn (ML)** | Energy Consumption Prediction |
| **PostgreSQL/MySQL** | Charging Session Data Storage |
| **MQTT (IoT Protocol)** | Real-time Sensor Data Transmission |
| **ESP32/Raspberry Pi** | Sensor Data Collection |
| **Docker** | Containerized Deployment |
| **AWS / Heroku** | Cloud Hosting |

---

## 📋 Prerequisites
Before running this project, make sure you have:

- [Python 3.10+](https://www.python.org/downloads/)
- [Node.js 16+](https://nodejs.org/)
- [MySQL Server 8+](https://dev.mysql.com/downloads/)
- [ESP32 Firmware Flasher](https://espressif.github.io/esptool/)
- [Docker](https://www.docker.com/)

---

## 📂 Directory Structure  

```bash
EV_Charging_Project/
│── backend/                
│   ├── manage.py
│   ├── settings.py
│   ├── models.py            
│   ├── views.py             
│   ├── ml_model/            
│   │   ├── train.py        
│   │   ├── predict.py      
│── frontend/               
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js          
│── microcontroller/         
│   ├── main.py            
│── deployment/              
│   ├── docker-compose.yml
│   ├── nginx.conf
│── README.md



## 🗃️ Database Setup

1. Open MySQL and execute the following SQL commands:
   ```sql
   CREATE DATABASE ev_charging;

   USE ev_charging;

   CREATE TABLE charging_sessions (
       id INT AUTO_INCREMENT PRIMARY KEY,
       voltage FLOAT NOT NULL,
       current FLOAT NOT NULL,
       power_consumed FLOAT NOT NULL,
       timestamp TIMESTAMP DEFAULT CURRENT_TIMESTAMP
   );


## 🖥️ How to Run

1. **Clone the repository**:  
   Clone the repository using the following command:  
   ```bash
   git clone https://github.com/hariom710/BankingApplication.git


    Navigate to the project folder:
    ```bash
    cd BankingApplication

    Compile the project:
    ```bash
    cd src
    javac -d ../out Banking_management_system/*.java banking_application/*.java

    Run the application:
    ```bash
    java -cp "../out;../lib/mysql-connector-j-9.1.0.jar" banking_application.BankingApp
(For macOS/Linux, replace ; with : in the -cp option.)



Customization (Optional): Feel free to modify the content, add more destinations, or change the visuals to fit your own safari packages.

# 🤝 Contributingg
We welcome contributions to Banking Application If you'd like to add new features follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Add your changes (git add .).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request to the main branch.
Before submitting a pull request, ensure your code is properly formatted and includes necessary comments.

# 🧑‍💻 Code of Conduct
This project follows the Contributor Covenant Code of Conduct. We are committed to maintaining a harassment-free environment for all participants.

Please follow the guidelines outlined in the CODE_OF_CONDUCT.md file for more details.

# 📜 License
This project is licensed under the MIT License - see the LICENSE.md file for details.

### Key Sections:

- **Features**: Highlighted key features of the Banking Application.
- **Technologies Used**: Outlined the core technologies used for building the website (Java).
- **How to Use**: Provided clear steps on how to clone and run the project.
- **Contributing**: Explained how to contribute to the repository.
- **License**: Basic information about the license for the project.

🌟 Acknowledgements
Built with ❤️ using Java and MySQL.
Special thanks to open-source contributors and the development community.

This `README.md` provides an organized and clear introduction to your **Banking Application** project. You can expand or adjust the sections as your project grows.
