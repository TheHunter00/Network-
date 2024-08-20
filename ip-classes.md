
### **IP Address Classes**

**1. Class A**
- **Range**: From `0.0.0.0` to `127.255.255.255`
- **Network Size**: Very large networks (e.g., big organizations or ISPs).
- **Network Address Example**: `10.0.0.0`
- **Broadcast Address Example**: `10.255.255.255`
- **Usable Addresses**: Over 16 million addresses.
- **First Octet**: The first number (e.g., in `10.x.x.x`).

**2. Class B**
- **Range**: From `128.0.0.0` to `191.255.255.255`
- **Network Size**: Medium-sized networks (e.g., mid-sized companies).
- **Network Address Example**: `172.16.0.0`
- **Broadcast Address Example**: `172.31.255.255`
- **Usable Addresses**: Over 65,000 addresses.
- **First Octet**: The first number is between 128 and 191 (e.g., in `172.x.x.x`).

**3. Class C**
- **Range**: From `192.0.0.0` to `223.255.255.255`
- **Network Size**: Small networks (e.g., small businesses or home networks).
- **Network Address Example**: `192.168.1.0`
- **Broadcast Address Example**: `192.168.1.255`
- **Usable Addresses**: Up to 254 addresses.
- **First Octet**: The first number is between 192 and 223 (e.g., in `192.x.x.x`).

**4. Class D** (Used for multicast)
- **Range**: From `224.0.0.0` to `239.255.255.255`
- **Purpose**: For sending data to multiple destinations at once (like streaming video to many viewers).
- **Example**: `224.0.0.1`

**5. Class E** (Reserved for future use)
- **Range**: From `240.0.0.0` to `255.255.255.255`
- **Purpose**: Reserved for experimental purposes and not used in regular networks.
- **Example**: `240.0.0.1`

**Special Address Ranges**:
- **Loopback Address**: `127.0.0.0` to `127.255.255.255` (Used to test your own computer).
- **Private Addresses** (used within local networks):
  - **Class A**: `10.0.0.0` to `10.255.255.255`
  - **Class B**: `172.16.0.0` to `172.31.255.255`
  - **Class C**: `192.168.0.0` to `192.168.255.255`
- **Link-Local Addresses**: `169.254.0.0` to `169.254.255.255` (Used for automatic local communication when no other IP is available).

![image](https://github.com/user-attachments/assets/d9294c36-79fd-4caf-a284-989de3f130fe)
