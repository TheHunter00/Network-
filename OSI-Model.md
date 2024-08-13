# What is the OSI Model?

The OSI Model is like a blueprint for how data travels across a network. It helps us understand how different parts of a network communication system work together.

## The 7 Layers of the OSI Model

### Physical Layer:
What it does: Deals with the actual hardware and cables that send data. Think of it as the physical infrastructure—like wires and switches.
Example: Ethernet cables and network adapters.
<hr>

### Data Link Layer:
What it does: Ensures data is correctly sent over the physical connection. It handles error detection and correction, and organizes data into frames.
Example: MAC addresses and switches.
<hr>

### Network Layer:
What it does: Decides how data should travel from one device to another across different networks. It deals with routing and addressing.
Example: IP addresses and routers.
<hr>

### Transport Layer:
What it does: Manages how data is transferred between devices, ensuring that data is complete and in the correct order. It deals with error recovery and flow control.
Example: TCP (which ensures data is delivered accurately) and UDP (which is faster but less reliable).
<hr>

### Session Layer:
What it does: Manages and controls the connections between computers. It helps establish, maintain, and terminate sessions between applications.
Example: Establishing a connection for a video call.
<hr>

### Presentation Layer:
What it does: Translates data into a format that the application layer can understand. It handles data encryption and decryption.
Example: Converting data into a readable format or encrypting data for secure communication.
<hr>

### Application Layer:
What it does: Interacts directly with end-user applications. It provides network services to applications like web browsers and email clients.
Example: HTTP (for web browsing) and SMTP (for sending emails).
<hr>

# How It Works Together
### When data is sent from one computer to another:
- It starts at the Application Layer (where it’s created by an application).
- Moves down through each layer, getting prepared for transmission (headers added at each layer).
- Travels over the network hardware (Physical Layer).
- At the receiving end, it goes through the layers in reverse, from the Physical Layer up to the Application Layer, where it’s finally used by the application.
  
By breaking down the process into these layers, the OSI Model helps network professionals understand and troubleshoot network communication in a structured way
