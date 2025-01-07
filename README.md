# TASK4_SONARQUBE_SECURITY_SCANNING_INTO_CI-CD

**NAME**: SHAIK SADDAM HUSSAN
**INTERN ID**: CT6WGKO
**DOMAIN**: DEVOPS
**BATCH DURTION**: DECEMBER 25TH,2024 TO FEBRURY 10TH,2025
**MENTOR NAME**: NEELA SANTHOSH
# ENTER DESCRIPTION OF TASK:
1.i am launched an two ec2 for jenkins and apache tomcat, i am selected ubuntu os.
2.installed jdk,apache2 web server,jenkins server from jenkins web sit link. in one server.
3.other server install apache tomcat.done all configertion like services file,user permissions for depolyment.
4.jenkins server install also sonarqube with docker pull image and run condainer.sonargube accesed ip with 9000 port.
4.i'll create job named as ci-cd configer GitHub hook trigger for GITScm polling for webhook it workes when we push to github that it bultd automatically(ci/cd).
5.and aslo writed pipeline script, then i'll genreted token in github for connet for github acc that toke copy past in system configertionglobal in github  in jenkins.
6.in jenkins installed pulgins like sonarqubescanner,deploy to condainer.and configer sonarqube server with token is genrated in sonarqube.
7.finally run the pipeline script.

# OUTPUT OF TASK
1.jenkins pipeline script.
![Screenshot 2025-01-07 184907](https://github.com/user-attachments/assets/059321fa-df0e-4721-b693-18f7aa6a66a9)

2.sonarqube.
![Screenshot 2025-01-07 185006](https://github.com/user-attachments/assets/cd3ce4cd-8fb2-41dd-b284-1c4e4f90daed)

3.apache tomcat.
![Screenshot 2025-01-07 185127](https://github.com/user-attachments/assets/d5b5c168-8653-4781-be3c-11ac691d9251)

4.jenkins stages.
![Screenshot 2025-01-07 185205](https://github.com/user-attachments/assets/2b3525c2-a3f4-424f-a6c4-3378f084072b)

6.deployed website.

![Screenshot 2025-01-07 185408](https://github.com/user-attachments/assets/fe25c4ad-222d-45c4-819e-06712ba5c299)
