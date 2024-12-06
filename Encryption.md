# Encryption

## Transport Layer Security (TLS) Email
Transport Layer Security in its simplest form works to ensure that the data that you're sending from one source to another is secure throughout its entire transport process. But let's break it down a little bit more into some steps. 
1. Connection: When you log into your email account, it connects to the email server that you're using (ex. Yahoo). The email server is where the TLS encryption is housed and where all of the steps will commence.
2. Handshake: When you go to send your email, the server authenticates itself by providing a digital certificate (think of this like an ID badge) proving that the server is the correct server that you're using. Your email account will also provide their digital certificate and both your account and server will verify that they're both legit and then encrypt your email to be sent.
3. Data Encryption: When your email gets encrypted, it gets assigned a session key (think of this like a house key), only the people who possess this session key (the server and the email accounts) are allowed to read the contents of the email.
4. Delivery: When your email completes its long journey to the recipient's inbox, the recipient's email server will decode the encryption based on its own TLS protocol. 


## End-to-End Encryption (E2EE) Email
End-to-end encryption works similarly to TLS, but its goals are a little bit different. TLS is more concerned with the encryption of the email while it's traveling to its destination whereas E2EE ensures that only the sender and recipient can read the contents of the email. Here's how E2EE works 
1. Keys: E2EE encryption uses two sets of keys, a public and a private key. We can think of the public key as a locker. This public key is used to encrypt the email from the sender's side, which begins the email transfer. The private key is unique to only the recipient. We can think of this as the locker code, you can only decode the email if you have the correct private key to decrypt the email. This might sound a little confusing, but don't worry, you don't have to memorize the public and private keys, your email accounts do this for you.
2. Decryption: Once the email is delivered to the recipient's inbox, the email server uses the recipient's private key to unlock the contents of the email, and if it's the correct key, congratulations, you can now read the contents of the email. 
   
   
   
  
