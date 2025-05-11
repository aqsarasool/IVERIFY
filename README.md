# 🔐 iVerify System

**iVerify** is a secure and intelligent verification system designed to validate mobile devices through unique identifiers such as IMEI numbers. It supports businesses in verifying product authenticity, managing supplier requests, and tracking product warranties. Built with Laravel and integrated with QA automation tools, iVerify ensures transparency and trust in digital verification workflows.

## 🌟 Features

- 📱 **Device Verification** using IMEI and serial numbers
- 📑 **Supplier Request Management** with form-based submissions
- 🧾 **Warranty and Specification Tracking**
- 📊 **Admin Dashboard** with charts, metrics, and search filters
- 🔐 **Role-Based Authentication** (Admin, Supplier)
- 🖼️ **Image Uploads** stored as Base64
- 📦 **Firestore Integration** (if applicable)
- 🧪 **QA Automation** with Selenium

---

## 🛠️ Built With

| Technology | Usage |
|------------|--------|
| Laravel    | Backend framework (PHP) |
| MySQL      | Relational database |
| Blade      | Laravel's templating engine |
| Bootstrap / Tailwind | UI styling |
| PHPUnit    | Unit and feature testing |
| Selenium WebDriver | Automated browser testing  |
| Git & GitHub | Version control |
| Postman    | API testing |

---

## 📂 Project Structure
/iverify
│
├── /flutter_app                 # Flutter frontend project
│   ├── /lib
│   │   ├── main.dart            # App entry point
│   │   ├── /views               # UI screens (Home, Login, Dashboard, etc.)
│   │   ├── /widgets             # Reusable widgets
│   │   ├── /services            # API, Web3, and blockchain interaction code
│   │   └── /models              # Data models
│   └── pubspec.yaml             # Flutter dependencies
│
├── /blockchain                 # Smart contract project (e.g., Hardhat or Truffle)
│   ├── /contracts              # Solidity contracts (e.g., iVerify.sol)
│   ├── /scripts                # Deployment and interaction scripts
│   └── .env                    # Environment variables (Infura, private key, etc.)
│
└── README.md                   # Project documentation


🚀 Getting Started
Follow these steps to set up the project locally, including the Flutter app and the blockchain smart contract backend.

📱 Flutter Frontend Setup
1. Clone the Repository

git clone https://github.com/aqsarasool/iverify.git
cd iverify/flutter_app  # or your actual Flutter project folder
2. Install Dependencies

flutter pub get
3. Run the App

flutter run
Make sure a device or emulator is connected.

🔗 Blockchain Backend Setup
Assuming you're using Solidity for smart contracts .

1. Navigate to Blockchain Directory

cd iverify/blockchain  # adjust to your actual smart contract folder
2. Install Dependencies

3. Compile Smart Contracts
   
4. Deploy to Local or Test Network
![5](https://github.com/user-attachments/assets/8400b742-83b9-493c-8ee2-05b6ed29ffce)
![4](https://github.com/user-attachments/assets/2801ef22-d829-445e-be2e-ab9769644bb4)
![3](https://github.com/user-attachments/assets/86600e41-01f9-4c84-9947-1fea2a668d74)
![2](https://github.com/user-attachments/assets/2f740271-0252-44a9-88df-bbabcf06c98f)
![1](https://github.com/user-attachments/assets/7c4c07dc-d6fb-470f-b1d4-9115c26c7859)





