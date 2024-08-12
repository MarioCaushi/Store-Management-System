_**Grocery Store Management System**_

This project is a comprehensive Grocery Store Management System developed as the final project for the CEN 215 - Object-Oriented Programming course. It is designed to streamline the organizational and analytical tasks of a store or supermarket. The system is built using Java as the programming language, with a graphical user interface (GUI) developed using JavaFX.

**Features**

**Two Levels of Access**

The system offers two levels of authorization, each with its own set of permissions and responsibilities:

**1. Manager**

	•	Inventory Management: Add, edit, or remove products and manage stock levels.
	•	User Management: Manage the details of managers, cashiers, and customers.
	•	Loyalty Program: Oversee customer loyalty points and rewards.
	•	Profile Management: Update personal details such as name, email, and password.
	•	Sales Reports: Generate and analyze sales reports to track store performance.

**2. Cashier**

	•	Inventory Management: Manage product inventory.
	•	Profile Management: View and update personal profile details.
	•	Customer and Cashier Management: View customer and cashier information (with limited editing rights).
	•	Sales Reports: Generate receipts and track items purchased by customers.
	•	Point of Sale: Efficiently handle transactions and print receipts.

**Data Management**

	•	The system stores and retrieves data using binary files, ensuring that all operations, such as inventory updates and profile changes, are saved during the application’s runtime.

**Requirements**

	•	Java JDK
	•	JavaFX (Download JavaFX SDK)
	•	Eclipse or IntelliJ IDEA

**Setup**

	1.	Clone this repository to your local machine.
	2.	Load the project into your IDE (under your project directory).
	3.	Configure JavaFX:
	•	For IntelliJ:
	•	Navigate to File > Project Structure > Libraries > + > Java and locate the javafx-sdk/lib directory.
	•	Edit the run configuration to add VM options: Run > Edit Configuration > (under modify options) > Add VM options > add --module-path "\path\to\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml.

**Limitations**

	•	The system currently uses binary files for data storage, which might not be as efficient or scalable as a traditional database.

**Future Improvements**

	•	Integrating a database backend to enhance data management and scalability.

**Demonstrating Photos**

Register Page

<img width="593" alt="Screenshot 2024-08-12 at 13 34 23" src="https://github.com/user-attachments/assets/90e30340-94de-419a-917f-d849485bc25b">

Login Page

<img width="594" alt="Screenshot 2024-08-12 at 13 35 15" src="https://github.com/user-attachments/assets/afab643e-24a4-4279-b9db-509807399b27">

Manager-Home Page

<img width="897" alt="Screenshot 2024-08-12 at 13 36 36" src="https://github.com/user-attachments/assets/237b4c71-87e7-48e1-9fd6-8ad1c6556387">

Manager-Inventory

<img width="890" alt="Screenshot 2024-08-12 at 13 37 14" src="https://github.com/user-attachments/assets/3a53b001-8069-4b62-81e2-676eeedfa7f0">

Cashier-Home

<img width="895" alt="Screenshot 2024-08-12 at 13 37 38" src="https://github.com/user-attachments/assets/ad49e791-823d-4442-ab44-c9ae6480d0ab">


