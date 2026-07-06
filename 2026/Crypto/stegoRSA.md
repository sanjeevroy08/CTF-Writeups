# Challenge Name
StegoRSA

# Description:
A message has been encrypted using RSA. The public key is gone… but someone might have been careless with the private key. Can you recover it and decrypt the message?

# Analysis
1.in the given discryption they have given the private key can be availabe
2.hint1:Metadata can tell you more than you expect.
3.hint2:Hex can be turned back into a key file.

# Steps Taken
1. download the given files
2. see the metadata of the image using exiftool 
3. con vert the given hex value to text 
4. save the obtained peivate key in .pem file
5. use the .pem file to decrypt the flag.enc
6. got the flag
   
# Flag
<img width="1842" height="851" alt="image" src="https://github.com/user-attachments/assets/22b4f982-8449-41be-9c4c-b4ea7d5b00e5" />
<img width="942" height="372" alt="image" src="https://github.com/user-attachments/assets/162cea8c-0717-42b7-a51e-9b03b5ae1c30" />
<img width="665" height="107" alt="image" src="https://github.com/user-attachments/assets/38a31446-f6ee-4ae4-8e83-2af489fcaa0c" />
