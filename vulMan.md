---
layout: default
title: Vulnerability Management | Project Details
---

# Vulnerability Management

## Nessus Essential

Welcome! This project demonstrates my experience in Vulnerability Management by performing security assessments on various devices, including my personal laptop and a Virtual Machine (VM). For this project, I utilized two industry-standard vulnerability scanning tools: Nessus Essentials and Qualys. Below, I outline the steps I followed and highlight the key findings from each tool.

Nessus Essentials is a powerful vulnerability scanner that allows for free scanning of up to 16 IP addresses per installation, making it ideal for educational and small-scale cybersecurity projects. It is particularly well-suited for students and entry-level professionals seeking to gain experience in identifying system vulnerabilities. Learn more about Nessus Essentials (https://www.tenable.com/products/nessus/nessus-faq#:~:text=Nessus®%20Essentials%20is%20free,starting%20out%20in%20cyber%20security.)


So to start, you first have to set up Nessus from their website and configure the software that will be used. After that, you will have to register an account that will serve as your login when using the tool. 

Now upon signing in, you will be directed to the main page. Here, you can set up for the vulnerability scanning of devices. In my case, I used my own laptop.

![Screenshot](images/vm/ne/ne1.png) 

I created a new scan and then I clicked on "Basic Network Scan".

![Screenshot](images/vm/ne/ne2.png)

After that, some settings can be configured the most important being the target IP Address. In order to get the IP Address of my device, I went to the Command Prompt and entered ipconfig.

![Screenshot](images/vm/ne/ne3.png)


I copied my IPV4 Address and pasted it on the target IP Address. I clicked "Save" and then a new scan will be created. I clicked "Launch". This started the vulnerability scan on my laptop.

![Screenshot](images/vm/ne/ne4.png)
![Screenshot](images/vm/ne/ne5.png)

I did the same process with the Virtual Machine that I set up.

![Screenshot](images/vm/ne/ne6.png)


This took some time. But after that the results of the scan can be viewed.

![Screenshot](images/vm/ne/ne7.png)
![Screenshot](images/vm/ne/ne8.png)
![Screenshot](images/vm/ne/ne9.png)

Upon further inspection, the vulnerability management tool detected multiple vulnerabilities in both my laptop and the virtual machine. The vulnerabilities are listed and have different details of classification such as the severity of the vulnerability, the common vulnerability scoring system, vulnerability priority rating and exploit prediction scoring system. 

![Screenshot](images/vm/ne/ne10.png)
![Screenshot](images/vm/ne/ne11.png)

By clicking a vulnerability, more information can be seen such as the description, solutions for the vulnerability, references, and the output of the vulnerability. 

![Screenshot](images/vm/ne/ne12.png)


After viewing the different solutions from the vulnerability, I did a remediation for each of the vulnerability the posed a level 2 threat and higher. After that, I did a rescan of the devices again.

![Screenshot](images/vm/ne/ne13.png)
![Screenshot](images/vm/ne/ne14.png)

And that concludes it for the Nessus Essential Vulnerability Managemnt Tool.

## Qualys 

For the second part of the project, I utilized Qualys, a cloud-based platform designed for comprehensive vulnerability detection across a wide range of networked assets. This tool can assess servers, workstations, and network devices such as routers, switches, and firewalls. Qualys can assess any device that has an IP address. (https://www.qualys.com/support/faq/general/#:~:text=Qualys%20is%20a%20cloud-based,that%20has%20an%20IP%20address.)

Qualys is another vulnerability management tool that I used for this project. The set up for this tool is a bit tricky so I just followed a youtube video that I found. (https://www.youtube.com/watch?v=JXt9hiH6clc)

![Screenshot](images/vm/q/q1.png)

After setting up, I used the Qualys Cloud Agent in order to vulnerability scan my laptop. 

![Screenshot](images/vm/q/q2.png)


once the Qualys Cloud Agent is set up, it will automatically sync with the Cloud Tool and your device will appear automatically on the listed devices. 

![Screenshot](images/vm/q/q3.png)

For my case, I had the tool running overnight already but you can set up another scan by clicking the arrow under the agent host, and click "On Demand Scan", "Vulnerability Scan" then click "Submit"

![Screenshot](images/vm/q/q4.png)
![Screenshot](images/vm/q/q5.png)


Here, details about your device or your "agent' can be seen. The results can be seen by clicking the name of your Agent, then clicking "Vulnerabilities".

![Screenshot](images/vm/q/q6.png)

The main dashboard can be seen with the results of the vulnerability scan. In my case, I have a lot of vulnerabilites in my laptop.

![Screenshot](images/vm/q/q7.png)

By clicking "View Vulnerabilities", the vulnerabilities will be listed in the classification of 1-5 on the Severity scale. 

![Screenshot](images/vm/q/q8.png)

Clicking on a specific vulnerability will show more of its details and the Threat/Description, Impact, Solution and Results. 

![Screenshot](images/vm/q/q9.png)

I remediated some of the vulnerabilites by following the solutions for the vulnerabilities. Most of them were just updates that I didn't do frequently. Though I couldn't remediate some vulnerabilities due to them being software applications that are cracked.

![Screenshot](images/vm/q/q10.png)


I then did another scan in order to see if the vulnerabilities were reduced. And they were.


That concludes the Qualys Cloud Tool!








