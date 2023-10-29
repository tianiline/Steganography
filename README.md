# Steganography
 - <b>[Steganography Analysis](https://imgur.com/a/RrahPw9)</b>
     - Description: In lab,i explored the field of steganography and its applications in digital forensics. I gained hands-on experience with steganography tools like Steghide and Stegosuite, allowing me to analyze, detect, and extract hidden data within digital media. 
1.	Selected a target image for steganography analysis.
2.	Used Stegosuite to analyze the selected file for potential hidden data by applying various steganography detection techniques.
3.	Noted any suspicious indicators or anomalies that may suggest the presence of hidden data within the file.
   - Embeded and Extracted Hidden Data
1.	Selected a cover file and a data file that i wanted to embed within the cover file.
2.	Used Steghide to embed the data file within the cover file by executing the following command:
steghide embed -cf dog.jpg -ef hidden.txt 
3.	Extracted the hidden data from the cover file using Steghide by executing the following command:
steghide extract -sf hidden.txt 
4.	I then Verified the successful extraction of the hidden data and analyzed its contents.
