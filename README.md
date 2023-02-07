# HACKATON2023
NOVANTA Hackathon 2022 task
The topic is detection and recognition of QR codes.
Please download the following Novanta office walkthrough video: LINK. There are standard (and less standard) unique QR codes randomly placed in this video. 
The assignment consists of two tasks.
1.	Use a detection algorithm to find the QR codes and record their positions using your application. The application expects the video file on its input (or at least all the individual frames extracted from the video) and returns JSON file containing UID, time of appearance and position of QR codes together with its width and height (see appendix A).
2.	Decode as many codes as possible using your application. Participants are expected to submit a text file with unique QR codes’ UIDs and the decoded text for each one.
Fork the following repository https://github.com/jdkvision/HACKATON2023 and commit your solution to your fork. Send a link to your repository no later than Sunday, January 22nd at 12:00PM CET as a reply to this email. 
Feel free to ask questions. Point them to jaroslav.tomecek@novanta.com and michal.dvorak@novanta.com.
Usage of 3rd party tools for both tasks is allowed.
The criteria for the first task evaluation are following:
•	Number of correctly detected codes
•	Number of incorrectly detected codes 
o	The lower the better
•	Number of correctly assigned UIDs
o	Each QR code is present on tens of frames in the video, each occurrence of the same QR code must be assigned the same UID
o	Solution quality
The criteria for the second task evaluation are following: 
•	Total number of decoded unique QR codes
•	Average number of frames needed to decode QR codes
•	Automation level
•	Solution quality
•	NOTE: Use of manually annotated/extracted QR codes (i.e.. Not automatically detected during the first task), is acceptable but will be considered during evaluation.
Appendix A: Expected JSON file structure of the first task
{"codes":[
    {"UID":1,"time":"00:15.0666","x":100,"y":200,"w":50,"h":50},
    {"UID":1,"time":"00:15.1000","x":100,"y":200,"w":50,"h":50},
    {"UID":1,"time":"00:15.0333","x":100,"y":200,"w":50,"h":50},
    {"UID":2,"time":"01:00.0000","x":728,"y":445,"w":70,"h":80},
    {"UID":2,"time":"01:00.0333","x":728,"y":445,"w":70,"h":80},
    {"UID":3,"time":"01:5.0999","x":200,"y":350,"w":60,"h":55}
  ]
}

