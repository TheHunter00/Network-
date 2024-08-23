
### What is TTL?

**TTL (Time To Live)** is like a timer for data packets traveling across a network. It controls how long a packet can stay in the network before being discarded.

### How TTL Works

1. **Setting TTL**: When a packet is sent, it starts with a TTL value (like 64).
2. **Reducing TTL**: Each time the packet passes through a router, the TTL value decreases by 1.
3. **TTL Expiry**: If TTL reaches 0 before the packet reaches its destination, the packet is discarded and an error message is sent back to the sender.

### Why TTL is Important

- **Prevents Loops**: Stops packets from endlessly circulating in the network if there’s a routing problem.
- **Helps Troubleshooting**: Tools like `traceroute` use TTL to find out where packets are going and where they might be getting stuck.

In summary, TTL helps keep network traffic moving efficiently by ensuring packets don’t get stuck forever.
<hr>

![image](https://github.com/user-attachments/assets/47f7966e-4544-4d35-9b71-5f252bd7ef89)
