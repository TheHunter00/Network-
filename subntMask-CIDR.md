C

##  IP Addressing: Subnet Masks and CIDR

### **What is a Subnet Mask?**

A subnet mask is like a filter that helps computers understand which part of an IP address represents the network and which part represents the device (or host) on that network.

#### **How It Works**

1. **IP Address**: Think of it like a phone number with two parts:
   - **Network Part**: Identifies the network (similar to a city’s area code).
   - **Host Part**: Identifies the specific device (like a local phone number).

2. **Subnet Mask**: Tells the computer which portion of the IP address is the network and which part is the host.

#### **Example**

- **IP Address**: `192.168.1.10`
- **Subnet Mask**: `255.255.255.0`

In this case:
- **Network Part**: `192.168.1`
- **Host Part**: `10`

The subnet mask `255.255.255.0` indicates:
- The first three numbers (`192.168.1`) are the network part.
- The last number (`10`) is the host part.

#### **Why It’s Useful**

The subnet mask helps your computer determine which devices are on the same network and which are on different networks. This is crucial for routing data correctly.

### **What is CIDR?**

CIDR (Classless Inter-Domain Routing) is a method for allocating and specifying IP addresses more flexibly than the old class-based system.

#### **How CIDR Works**

1. **Old System (Class-Based)**:
   - IP addresses were divided into fixed classes (Class A, B, C).
   - Each class had a set number of addresses, which could lead to inefficiency if you didn't need that many.

2. **CIDR (Classless Inter-Domain Routing)**:
   - Allows for more flexible and efficient allocation of IP addresses.
   - You can define network sizes based on need, rather than sticking to fixed sizes.

#### **CIDR Notation**

CIDR uses a format like `192.168.1.0/24`. Here’s what it means:

- **IP Address**: `192.168.1.0` – The starting address of the network.
- **Slash and Number**: `/24` – Indicates how many bits are used for the network portion of the address.

#### **Breaking Down `/24`**

- **IP Address**: `192.168.1.0`
- **Subnet Mask Equivalent**: `255.255.255.0`

In this case:
- The `/24` means the first 24 bits of the IP address are used for the network.
- The remaining bits (8 bits) are used for the devices within that network.

#### **Why CIDR is Useful**

- **Flexibility**: Create networks of varying sizes as needed.
- **Efficiency**: Reduces wasted IP addresses by allowing precise network sizing.

#### **Examples**

- **CIDR Notation**: `192.168.0.0/16`
  - **IP Range**: From `192.168.0.0` to `192.168.255.255`
  - **Network Size**: 65,536 addresses

- **CIDR Notation**: `192.168.1.0/24`
  - **IP Range**: From `192.168.1.0` to `192.168.1.255`
  - **Network Size**: 256 addresses

### **In Summary**

- **Subnet Mask**: Helps in understanding which part of an IP address is for the network and which is for the device.
- **CIDR**: Provides a flexible and efficient way to allocate IP addresses, allowing for precise network sizes.

---

![image](https://github.com/user-attachments/assets/1c68071c-7d1b-4ca0-a99f-6bf5b505852b)
