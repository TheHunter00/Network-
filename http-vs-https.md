![image](https://github.com/user-attachments/assets/095ef1df-3ad7-48db-8da8-276d11bf269f)

# HTTP vs. HTTPS Comparison

| **Feature**               | **HTTP**                                                                                   | **HTTPS**                                                                              |
|---------------------------|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| **Full Name**             | Hypertext Transfer Protocol                                                                | Hypertext Transfer Protocol Secure                                                      |
| **Security**              | Not secure; data is sent in plain text                                                     | Secure; data is encrypted using SSL/TLS                                                 |
| **Encryption**            | No encryption; data can be intercepted                                                     | Uses encryption (SSL/TLS) to protect data                                               |
| **URL Prefix**            | `http://`                                                                                  | `https://`                                                                             |
| **Browser Indicator**     | No padlock or a plain "not secure" warning                                                  | Padlock icon; shows "Secure" or similar message                                         |
| **Data Integrity**        | Data can be altered or tampered with                                                        | Data is protected against tampering                                                      |
| **Performance**           | Typically faster due to lack of encryption                                                  | Slightly slower due to encryption overhead                                              |
| **Usage**                 | Suitable for non-sensitive content like blogs or public information                        | Essential for sensitive transactions such as online banking, shopping, and login pages |
| **Trust Level**           | Lower trust; not recommended for handling personal or financial information                | Higher trust; indicated by the padlock and used for secure communications                |
| **Example of Usage**      | News websites, non-secure blogs                                                             | E-commerce sites, online banking, email services                                         |
| **Authentication**        | No server authentication                                                                     | Provides authentication with a digital certificate to verify the server’s identity       |
| **Common Methods**        | `GET`, `POST`, `PUT`, `DELETE`, `HEAD`, `OPTIONS`, `PATCH`                                 | Same methods as HTTP, but secure when transmitted                                        |
| **Method Description**    | - **GET:** Request data from a server <br> - **POST:** Submit data to a server <br> - **PUT:** Update data on a server <br> - **DELETE:** Remove data from a server <br> - **HEAD:** Retrieve headers only <br> - **OPTIONS:** Get supported methods from the server <br> - **PATCH:** Apply partial modifications to data | Same methods as HTTP with the added benefit of encryption during transmission           |

<hr>



### Explanation
#### Common Methods:
- GET: Retrieves data from a server.
- POST: Sends data to a server to create or update a resource.
- PUT: Updates an existing resource on the server.
- DELETE: Deletes a resource from the server.
- HEAD: Similar to GET but only retrieves headers, not the actual data.
- OPTIONS: Requests information about the communication options available for the target resource.
- PATCH: Applies partial modifications to a resource.

<hr>

![image](https://github.com/user-attachments/assets/63c8f48c-d8bd-48b0-af5c-de3a1ff944ed)
