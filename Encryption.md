# Encryption

## Transport Layer Security (TLS) 
Transport Layer Security in its simplest form works to ensure that the data that you're sending from one source to another is secure throughout its entire transport process. But let's break it down a little bit more into some steps. 
1. Connection: When you log into your  account, it connects to the  server that you're using (ex. Yahoo, Instagram, etc). The  server is where the TLS encryption is housed and where all of the steps will commence.
2. Handshake: When you go to send your message/email, the server authenticates itself by providing a digital certificate (think of this like an ID badge) proving that the server is the correct server that you're using. Your  account will also provide their digital certificate and both your account and server will verify that they're both legit and then encrypt your message to be sent.
3. Data Encryption: When your message gets encrypted, it gets assigned a session key (think of this like a house key), and only the people who possess this session key (the server and the message accounts) are allowed to read the contents of the message.
4. Delivery: When your message completes its long journey to the recipient's inbox, the recipient's account server will decode the encryption based on its own TLS protocol. 


## End-to-End Encryption (E2EE) 
End-to-end encryption works similarly to TLS, but its goals are a little bit different. TLS is more concerned with the encryption of the message while it's traveling to its destination whereas E2EE ensures that only the sender and recipient can read the contents of the message. Here's how E2EE works 
1. Keys: E2EE encryption uses two sets of keys, a public and a private key. We can think of the public key as a locker. This public key is used to encrypt the message from the sender's side, which begins the data transfer. The private key is unique to only the recipient. We can think of this as the locker code, you can only decode the message if you have the correct private key to decrypt the message. This might sound a little confusing, but don't worry, you don't have to memorize the public and private keys, your messaging accounts do this for you.
2. Decryption: Once the message is delivered to the recipient's inbox, the messaging server uses the recipient's private key to unlock the contents of the message, and if it's the correct key, congratulations, you can now read the contents of your message. 
   
   
   
  
