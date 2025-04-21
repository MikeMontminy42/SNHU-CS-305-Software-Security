# SNHU-CS-305-Software-Security


# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client for this project was Artemis Financial. AF is a financial services company that is looking at modernizing their current security measures for their website. The software required a plethora of security enhancements to ensure proper potection of data going from a clients device, to the data servers within AF, and then back. These fixes included adding SHA-256 encryption, HTTPS protocol, and checksum verifications. The main issue they needed addressing was to be able to have confidence both on their end and for cusomers that all sensitive data would have high protection during instances of client and server transfers.


# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
The goal was to conduct a proper analysis of the system as is, identify vulnerabilities, identify fixes, and also propose fixes to be implemented. It is essential to use proper secure coding practices to prevent unwarranted data access, data tampering, data leaks, or hash key tampering. These enhancements also help to boost trust of clients of AF, strengthens againt financial and legal ramifications, and also helps to boos the overall reputation of AF for having cutting-edge security.


# Which part of the vulnerability assessment was challenging or helpful to you?
The hardest part of the assessment for me was trying to get the dependency check to work. I had to spend around an hour messing with a bunch of variables and reinstalls of EclipseIDE. In the end, it turned out that I had been trying to set the goal to 'Install' instead of 'install'.


# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To increase security I added the SHA256 encryption algorithm, set up the system to run off of HTTPS, added checksum verifications, and adjusted class visibility within the source code. In the future I would definitely set up some form of automated testing to rapidly test for issues, monthly dependency scans at a minimum, and several rounds of code reviewing before an update goes live.


# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To make sure the code was functional, my first test was by running dependency checks before to see what errors there were. A second test performed was to boot the server up under port 8443 and making sure that the certificate is read and the site loads under HTTPS. After the code was redone I had performed a second dependency check to make sure that no extra vulnerabilities were added by mistake. 


# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The main tools that were used during this project were the EclipseIDE for developing all of the source code to make sure the HTTPS server loads, and the maven dependency check to scan for all possible vulnerabilities whether they be legit concerns or false positives. One tool that had to be added was the SHA-256 encryption algorithm to be used for encrypting the input keys. A lot of these resources and tools will be extremely helpful if I choose to pursue a path in security management or general cybersecurity later down the line.


# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
A lot of these documents in the repository will help future employers and coworkers have proof that I do have an ability to properly identify and possible vulnerabilities, refactor to clear some out, and suppress any known false positives after running a dependency check. Another thing that could be shown is the ability to deliver, although a very basic, piece of secured software with a working certificate of security.
