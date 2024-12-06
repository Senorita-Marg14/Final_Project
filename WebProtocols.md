# Web Protocols
Web protocols are used to ensure that information being transmitted across the web is protected. Secure Socket Layer (SSL) and [Transport Layer Security (TLS)](Encryption.md) are two ways that websites use to make sure your data is protected. 

## Secure Socket Layer (SSL)
The Secure Socket layer works to connect the user to the server that the user is trying to access, it works through a process that I'm going to detail below.
1. Client Initialization: When the user attempts to access the website, it sends a message to the server that it is trying to access, attempting to create a connection. Think of this as knocking on the door of your friend's house.
2. Server Initialization: The server acknowledges the user's message by sending a message back of their own, and then selecting the best encryption method to use to start the session. This part is like when your friend looks through their peephole to see who's at the door. 
3. Certificate Exchange: The server will then send its public key certificate to the user to allow the user to verify that they are accessing the correct website and that this website is secure by referencing a known list of trusted certificates. This is when your friend opens the door to get a better look at your face, and you're able to see that your friend is the one who answered the door. 
4. Session Key Creation: A session key is created and used by both the client and the server throughout the time that the user is on the website. This ensures that the data the user is accessing or providing during the time they are on the website is secured and cannot be seen by people without the specific session key. This is perhaps when you hug your friend before you come in their home, or maybe a nice wave if you're not the hugging type. Once this step is complete, you can securely use the website you're on. 

# HTTPS
HTTPS stands for Hypertext Transfer Protocol Secure, and this is the primary protocol used to send data between web browsers and websites. This is the safest form of encryption on mainstream websites and a good indicator that your data will be safe while you are using this website. 


[Home](Websites.md)

