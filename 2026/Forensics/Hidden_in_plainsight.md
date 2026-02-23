# Challenge Name
Hidden in plain sight

# Description:
You’re given a seemingly ordinary JPG image. Something is tucked away out of sight inside the file. Your task is to discover the hidden payload and extract the flag. Download the jpg image here.

# Analysis
1. In the description they have given the image
3. In the hint1 they have given that:Download the jpg image and read its metadata
5. So i understand that we have to look into the Details od the img
6. And they have given the flag is in the metadata!


# Steps Taken
1. Downloaded image
2. And used exiftool toget the metadata from that
3. Found Base64 string
4. Decoded using Base64 -d
5. it is double encrypted
6. angain decrypted
7. we got that it is hidden in steghide
8. we use steghide to fing flag and entered the password

# Flag
picoCTF{h1dd3n_1n_1m4g3_54e31417}

<img width="987" height="654" alt="image" src="https://github.com/user-attachments/assets/47d21c46-f575-4e82-81ca-0e3227b1bc54" />
<img width="884" height="217" alt="image" src="https://github.com/user-attachments/assets/fe32d215-b974-4acd-87a3-f09859983020" />
<img width="638" height="304" alt="image" src="https://github.com/user-attachments/assets/49fab895-af06-4aa2-aab5-7288aca18737" />
