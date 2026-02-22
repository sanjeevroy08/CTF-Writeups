# Challenge Name
Log Hunt

# Description:
Our server seems to be leaking pieces of a secret flag in its logs. The parts are scattered and sometimes repeated. Can you reconstruct the original flag? Download the logs and figure out the full flag from the fragments.

# Analysis
1. In the description they have given that flag  fragments leaked in logs and they have given log file
2. In the hint1 they have given that:You can use grep to filter only matching lines from the log.
3. In the hint2 they have given that:Some lines are duplicates; ignore extra occurrences.
4. So i understand that we have to look into log file and search with help of grep

# Steps Taken
1. Downloaded the log file
2. And used cat serverlog |grep FLAGPART {Searched for FLAGPARTS because  when i used cat i notices that the Flag pices ate in FLAGPARTS}
3. Found missing Flag piecies 
4. concatinated the piecies

# Flag
picoCTF{us3_y0urlinux_sk1lls_cedfa5fb}
<img width="1013" height="238" alt="image" src="https://github.com/user-attachments/assets/7a3f9472-436a-4e0d-aac9-3f8fba960902" />
<img width="978" height="727" alt="image" src="https://github.com/user-attachments/assets/ba00139f-1e59-4e47-8bdb-ab16c9a077c4" />
