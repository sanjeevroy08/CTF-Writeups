# Challenge Name
Riddle Registery

# Description:
Hi, intrepid investigator! 📄🔍 You've stumbled upon a peculiar PDF filled with what seems like nothing more than garbled nonsense. But beware! Not everything is as it appears. Amidst the chaos lies a hidden treasure—an elusive flag waiting to be uncovered.
Find the PDF file here Hidden Confidential Document and uncover the flag within the metadata.

# Analysis
1. In the description they have given the Confidential Document
2. In the hint1 they have given that:Don't be fooled by the visible text; it’s just a decoy!
3. In the hint2 they have given that:Look beyond the surface for hidden clues
4. So i understand that we have to look into the Details od the PDF
5. And they have given the flag is in the metadata

# Steps Taken
1. Downloaded Confidential Document
2. And used exiftool to get the metadata from that
3. Found Base64 string
4. Decoded using Base64 -d

# Flag
picoCTF{puzzl3d_m3tadata_f0und!_f94300c4}
<img width="1235" height="796" alt="image" src="https://github.com/user-attachments/assets/e7feb2cb-d608-480d-8a5c-e904107a5406" />
