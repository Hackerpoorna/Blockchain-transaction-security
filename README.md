Blockchain Transaction Security System
This project is a Java-based server application designed to enhance the security of blockchain transactions. It uses Java’s HttpServer class to handle HTTP requests and provides a user-friendly interface to interact with blockchain functionalities, including transaction authentication, verification, and secure data management.

Features
Transaction Authentication: Verifies the authenticity of blockchain transactions.
Transaction Registration: Accepts and stores transaction data securely in memory.
Dynamic Transaction Management: Allows users to view and update transaction details dynamically.
Static Page Serving: Serves multiple static HTML pages for features like transaction history, security settings, and data integrity checks.
Error Handling: Displays error messages for missing pages and incorrect HTTP methods.
Project Structure
The server uses several HttpHandler classes for different routes:

TransactionAuthHandler: Handles authentication of blockchain transactions.
TransactionRegistrationHandler: Manages registration and secure storage of transaction data.
TransactionManagementHandler: Displays and updates transaction details.
PageHandler: Generic handler for serving static HTML pages.
Setup
Prerequisites
Java JDK 11 or later
Installation
Clone repository:
git clone https://github.com/your-username/BlockchainTransactionSecurity.git
cd BlockchainTransactionSecurity
Team Members
V. Poorna Chandra - @poornachandra - Team Leader
