# MicroSoftResearchIndia_TechnicalAssessment
Automation to download the latest PDF posted on a website
Utilized selenium ide to record the automation process of downloading the latest Final Offer Documents filed with ROC on the SEBI( Security and Exchange Board of India) website.

![image](https://github.com/KalpeshK4970/MicroSoftResearchIndia_TechnicalAssessment/assets/121095860/704e4b8a-528c-4d6f-86c7-8af79b9684ef)
<br>
<br>
Download the file and open the cmd terminal and run this command  > selenium-side-runner /path/to/your-project.side 
![image](https://github.com/KalpeshK4970/MicroSoftResearchIndia_TechnicalAssessment/assets/121095860/7dd7afff-092b-4bb7-8cb9-ad604e4b8b39)


Code: <br>
-> On recording the automation process i got the target as LinkText: Name of the first company<br>
-> Here is the catch, if the webiste gets updated and new pdf is uploaded if will still install the file with the old file<br>
-> Hence i changed the target using css selector <br>
-> css=.odd:nth-child(1) .points {if in the bracket i pass the value n i will get the nth row pdf}<br>
![image](https://github.com/KalpeshK4970/MicroSoftResearchIndia_TechnicalAssessment/assets/121095860/106300eb-6ca5-4d98-a906-5688c566beb8)


