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
  
The layers 2-4 are transport oriented, and the layers 5-7 are application oriented layers. In each layer, precisely defined tasks are performed, and the interfaces to the neighboring layers are precisely described. Each layer offers services for use to the layer directly above it. To make these services available, the layer uses the services of the layer below it and performs the tasks of its layer.

If two systems communicate, all seven layers of the OSI model are run through at least twice, since both the sender and the receiver must take the layer model into account. Therefore, a large number of different tasks must be performed in the individual layers to ensure the communication's security, reliability, and performance.

When an application sends a packet to the other system, the system works the layers shown above from layer 7 down to layer 1, and the receiving system unpacks the received packet from layer 1 up to layer 7.

By breaking down the process into these layers, the OSI Model helps network professionals understand and troubleshoot network communication in a structured way

![net_models4](https://github.com/user-attachments/assets/9459a4ca-49a2-49bb-9bc1-5d68dcba5748)

![osi-layers](https://github.com/user-attachments/assets/2393944f-d435-48ee-bbf0-c62b70364b3b)
