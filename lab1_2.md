# Experiment 1: Creating Files and Directories in Linux

## Objective
Learn to create directories, generate multiple files, and organize them efficiently.

## Steps

### *1. Navigate to Desktop*
bash
cd Desktop


### *2. Create Directories*
bash
mkdir friends family work


### *3. Create Files in Each Directory*
bash
cd friends && touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi && cd ..
cd family && touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi && cd ..
cd work && touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi && cd ..


### *4. Verify File Creation*
bash
ls friends family work


## Conclusion
Successfully created directories and organized files. If directories do not exist, check for typos or permission issues.

## Screenshot
<img width="640" alt="Screenshot 2025-03-19 at 10 15 46 AM" src="https://github.com/user-attachments/assets/854b4a52-4e9d-45e3-8ec4-72c8c8bbc96b" />
