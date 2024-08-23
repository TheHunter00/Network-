
### **Understanding TCP and UDP**

**TCP (Transmission Control Protocol)** and **UDP (User Datagram Protocol)** are two key methods for sending data over the internet.

#### **TCP (Transmission Control Protocol)**

- **Reliable**: Ensures data arrives accurately and in the right order.
- **Connection-Oriented**: Sets up a connection before sending data (like making a phone call).
- **Features**:
  - **Reliable Delivery**: Resends lost or corrupted packets.
  - **Data Ordering**: Reorders packets if they arrive out of sequence.
  - **Error Checking**: Verifies data integrity.
  - **Flow Control**: Manages data transfer rate.

- **Example**: Loading a web page (HTTP on Port 80).

#### **UDP (User Datagram Protocol)**

- **Faster**: Sends data quickly but without guaranteed delivery.
- **Connectionless**: Sends data without establishing a connection first (like sending a letter).
- **Features**:
  - **Faster Transmission**: No overhead for connection setup.
  - **No Guarantee of Delivery**: Doesn’t ensure packet arrival or order.
  - **Simple Error Checking**: Basic checks but no retransmissions.

- **Example**: Streaming a video online (often uses Port 1935).

### **Port Numbers Overview**

Ports direct network traffic to the right application or service. They are categorized into three main ranges:

1. **Well-Known Ports**:
   - **Range**: 0 to 1023
   - **Purpose**: Reserved for widely-used services.
   - **Examples**:
     - **HTTP**: Port 80
     - **HTTPS**: Port 443
     - **FTP**: Port 21
     - **SMTP**: Port 25

2. **Registered Ports**:
   - **Range**: 1024 to 49151
   - **Purpose**: Used by specific applications and services.
   - **Examples**:
     - **MySQL**: Port 3306
     - **PostgreSQL**: Port 5432
     - **Microsoft SQL Server**: Port 1433

3. **Dynamic or Private Ports**:
   - **Range**: 49152 to 65535
   - **Purpose**: For temporary or client-side connections.
   - **Examples**: Used for ephemeral connections in client applications.

### **Summary**

- **TCP**: Reliable, ensures data integrity and order. Ideal for applications requiring accuracy.
- **UDP**: Faster, focuses on speed. Suitable for applications where speed is more important than accuracy.

- **Port Ranges**:
  - **Well-Known Ports**: 0 - 1023 (e.g., HTTP, FTP)
  - **Registered Ports**: 1024 - 49151 (e.g., MySQL, PostgreSQL)
  - **Dynamic/Private Ports**: 49152 - 65535 (e.g., temporary connections)

![image](https://github.com/user-attachments/assets/64e17611-d13c-45d1-b0b9-365a188fba93)
![image](https://github.com/user-attachments/assets/fc1438a0-5203-4f7b-9ce2-380173e37d39)
<hr>

# Important Ports


### **1. Well-Known Ports (0 to 1023)**

- **HTTP (Hypertext Transfer Protocol)**: **Port 80**
  - Used for standard web traffic.

- **HTTPS (HTTP Secure)**: **Port 443**
  - Used for secure web traffic (encrypted communication).

- **FTP (File Transfer Protocol)**: **Port 21**
  - Used for transferring files between computers.

- **SFTP (Secure File Transfer Protocol)**: **Port 22**
  - Used for secure file transfer, often over SSH.

- **SSH (Secure Shell)**: **Port 22**
  - Used for secure remote login and command execution.

- **SMTP (Simple Mail Transfer Protocol)**: **Port 25**
  - Used for sending emails.

- **POP3 (Post Office Protocol v3)**: **Port 110**
  - Used for receiving emails.

- **IMAP (Internet Message Access Protocol)**: **Port 143**
  - Used for receiving emails with more advanced features than POP3.

- **DNS (Domain Name System)**: **Port 53**
  - Used for translating domain names into IP addresses.

### **2. Registered Ports (1024 to 49151)**

- **MySQL**: **Port 3306**
  - Used for MySQL database connections.

- **PostgreSQL**: **Port 5432**
  - Used for PostgreSQL database connections.

- **Microsoft SQL Server**: **Port 1433**
  - Used for Microsoft SQL Server database connections.

- **RDP (Remote Desktop Protocol)**: **Port 3389**
  - Used for remote desktop access to Windows systems.

### **3. Dynamic/Private Ports (49152 to 65535)**

- **Used by client-side applications**: These ports are often dynamically assigned for temporary connections.

### **Summary**

- **Web Traffic**: HTTP (Port 80), HTTPS (Port 443)
- **File Transfer**: FTP (Port 21), SFTP (Port 22)
- **Remote Access**: SSH (Port 22), RDP (Port 3389)
- **Email**: SMTP (Port 25), POP3 (Port 110), IMAP (Port 143)
- **Databases**: MySQL (Port 3306), PostgreSQL (Port 5432), SQL Server (Port 1433)
- **DNS**: Port 53

![image](https://github.com/user-attachments/assets/53b1b470-22ab-4091-a68a-c428184e1d2d)
