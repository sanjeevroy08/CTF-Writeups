# Challenge Name
Flag in Frame

# Description:
The SOC team discovered a suspiciously large log file after a recent breach. When they opened it, they found an enormous block of encoded text instead of typical logs. Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it. The team is relying on your skills to uncover any concealed information within this unusual log. Download the encoded data here: Logs Data. Be prepared—the file is large, and examining it thoroughly is crucial .

# Analysis
1. In the description they have given the log file
2. In the hint1 they have given that:Use base64 to decode the data and generate the image file.
3. so i understand that we have to look innto that log file it is in text so i decided to convert the file into image becaue in hint they told us to convert into image file 


# Steps Taken
1. Downloaded log file
2. And used base64 to convert into image
3. save it into output.png
4. openrd the image and got the text which is in hexa decimal
5. used xxd to convert into plain text
6. got the flag
   
# Flag
picoCTF{forensics_analysis_is_amazing_5ccc7cb0}
<img width="1149" height="234" alt="image" src="https://github.com/user-attachments/assets/c2e82126-79f2-4065-ace0-5bf1aba85c48" />
<img width="1215" height="688" alt="image" src="https://github.com/user-attachments/assets/0d37e169-00a9-4590-a57c-9a57b0f5804a" />
<img width="1546" height="90" alt="image" src="https://github.com/user-attachments/assets/8a419422-8ddd-4702-9a1e-c86453258ba6" />
