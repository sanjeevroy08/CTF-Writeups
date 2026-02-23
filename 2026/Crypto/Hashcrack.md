# Challenge Name
Hash crack

# Description:
A company stored a secret message on a server which got breached due to the admin using weakly hashed passwords. Can you gain access to the secret stored within the server?
Access the server using nc verbal-sleep.picoctf.net 52339

# Analysis
1. In the description they have given acess to the server
2. hint1: Understanding hashes is very crucial. Read more here.
3. hint2:Can you identify the hash algorithm? Look carefully at the length and structure of each hash identified.
4. hint3:Tried using any hash cracking tools?
5. decode using hash crack tool crackstation


# Steps Taken
1. log in to server
2. we get hash decrypt we get password
3. enter password we get another hash
4. decrypt again we will get 
5. used xxd to convert into plain text
6. got the flag
   
# Flag
<img width="1395" height="365" alt="image" src="https://github.com/user-attachments/assets/01f7cfba-dece-4397-be1a-11f9180517b5" />
<img width="1465" height="463" alt="image" src="https://github.com/user-attachments/assets/42dde6b0-5c2a-4edf-be2a-6bdca4b82988" />
<img width="1373" height="441" alt="Screenshot 2026-02-23 135116" src="https://github.com/user-attachments/assets/92720bc2-cbdd-489f-a210-3b7b2a2081f5" />

