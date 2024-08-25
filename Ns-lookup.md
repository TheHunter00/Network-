

**What Is  **NS Lookup**:**
- **NS Lookup** is a tool used to query the Domain Name System (DNS) to get information about domain names and IP addresses.

**Purpose:**
- To find out which IP address is associated with a domain name (or vice versa).
- To get information about DNS records related to a domain.

**How It Works:**
1. **You Type a Domain:** You enter a domain name, like `example.com`, into the NS Lookup tool.
2. **Query to DNS Server:** The tool sends a request to a DNS server to find out the IP address associated with that domain name.
3. **Receive Answer:** The DNS server responds with the IP address or other DNS records related to that domain.

**Common Uses:**
- To check if a domain name resolves correctly.
- To find the mail servers for a domain.
- To diagnose DNS issues.

---

### **NS Lookup Command Structure**

**Basic Commands:**

- **`nslookup`**: Starts the NS Lookup tool.
- **`nslookup [domain]`**: Looks up the IP address for a domain name.
  - **Example:** `nslookup www.example.com`
- **`nslookup [IP address]`**: Looks up the domain name for an IP address (reverse lookup).
  - **Example:** `nslookup 93.184.216.34`

**Advanced Commands:**
- **`set type=MX`**: Looks up mail exchange (MX) records for a domain.
  - **Example:** `nslookup -type=MX example.com`
- **`set type=NS`**: Looks up name server (NS) records for a domain.
  - **Example:** `nslookup -type=NS example.com`

**Example NS Lookup for a Domain:**

1. **Request:**
   - **Command:** `nslookup www.example.com`
2. **Response:**
   - **Output:**
     ```
     Server:  your.dns.server
     Address:  192.168.1.1

     Name:    www.example.com
     Address:  93.184.216.34
     ```

**Example NS Lookup for MX Records:**

1. **Request:**
   - **Command:** `nslookup -type=MX example.com`
2. **Response:**
   - **Output:**
     ```
     Server:  your.dns.server
     Address:  192.168.1.1

     Non-authoritative answer:
     example.com     MX preference = 10, mail exchanger = mail.example.com
     ```

---

### **Domain Structure in NS Lookup**

When using NS Lookup, the domain structure is essential for understanding the results:

- **Full Domain:** `www.example.com`
  - **Top-Level Domain (TLD):** `.com`
  - **Second-Level Domain (SLD):** `example`
  - **Subdomain:** `www`

**Example Output for a Domain Lookup:**
```
Name:    www.example.com
Address:  93.184.216.34
```

**Example Output for MX Records Lookup:**
```
example.com     MX preference = 10, mail exchanger = mail.example.com
```

**Example Output for NS Records Lookup:**
```
example.com     nameserver = ns1.example.com
example.com     nameserver = ns2.example.com
```

---

### **Summary**

- **NS Lookup:** A tool to query DNS to find IP addresses or other DNS records for a domain.
- **Commands:** Allows querying for A records (IP addresses), MX records (mail servers), NS records (name servers), and more.
- **Domain Structure:**
  - **Top-Level Domain (TLD):** `.com`
  - **Second-Level Domain (SLD):** `example`
  - **Subdomain:** `www`, `mail`, etc.

NS Lookup helps you troubleshoot and verify domain name and IP address information, and understand the structure and settings of DNS records.

![24552_2](https://github.com/user-attachments/assets/7d28d578-0d4f-46f1-9203-f730ffde9e18)
