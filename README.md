The Blockchain-Based Student Attendance System is designed to provide a secure, transparent, and decentralized solution for managing student attendance. Traditional attendance systems depend on centralized databases and backend servers, which are prone to data manipulation, unauthorized access, and single-point failures. This project overcomes these limitations by using blockchain technology as the core data storage and execution layer.

In this system, attendance data is stored on the Ethereum blockchain through smart contracts written in Solidity. Once attendance is recorded, it becomes immutable, meaning it cannot be altered or deleted. This ensures data integrity and builds trust among students, faculty, and administrators.

The frontend of the application is developed using React.js and directly interacts with the blockchain using Ethers.js. The system does not require a backend server, making it completely serverless. Student authentication is handled using MetaMask, where each student is identified by a unique wallet address instead of traditional usernames and passwords.

Hardhat is used as the blockchain development environment to deploy and test smart contracts on a local Ethereum network. The system ensures that only registered students can mark attendance, thereby reducing proxy attendance and improving overall security.

Overall, this project demonstrates the practical use of blockchain technology in educational systems by providing a reliable, transparent, and tamper-proof attendance management solution.
