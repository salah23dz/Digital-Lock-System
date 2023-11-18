# Digital-Lock-System
The "Digital Lock System" program is designed to simulate a secure access control system where users are required to enter a passcode to unlock the system.

Project Description: Digital Lock System

The Digital Lock System is a Python program simulating a secure access control system where users must enter a passcode to unlock the system. The system includes features such as multiple user support with unique passcodes, time-stamped logging of access attempts, and the ability to lock and unlock the system.

Features:

User Management:

Description: Users and their corresponding passcodes are stored in a dictionary.
How to Use: Add new users with the add_user method by providing a unique username and passcode.
Passcode Entry:

Description: Users attempt to unlock the system by entering their username and passcode.
How to Use: Use the enter_passcode method by providing the username and passcode.
Logging:

Description: Access attempts, both successful and failed, are logged with timestamps.
How to Use: View the access log with the view_access_log method to monitor system activity.
Locking and Unlocking:

Description: The system can be locked or unlocked based on user actions.
How to Use: Lock the system with the lock method and unlock it by entering the correct passcode.
Status Display:

Description: The program provides the current status of the system (locked or unlocked).
How to Use: Check the system status with the status method.
How to Use:

Initialization:

Initialize the DigitalLockSystem by creating an instance.
User Management:

Add users using the add_user method with unique usernames and passcodes.
Passcode Entry:

Attempt to unlock the system by calling the enter_passcode method with a username and passcode.
Logging:

View access attempts and their statuses with the view_access_log method.
Locking and Unlocking:

Lock the system with the lock method.
Unlock the system by entering the correct passcode.
Status Display:

Check the current status of the system with the status method.
This Digital Lock System serves as a foundation for understanding access control mechanisms and can be extended for more sophisticated applications, such as integrating with external databases, implementing time-based access controls, or developing graphical user interfaces.
