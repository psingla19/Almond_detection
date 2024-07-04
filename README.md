# Alto-project
Advanced learning techniques for almond sorting and optimization


It is an ongoing project which aims in sorting almonds based on
sorting almonds based on quality and looks. firstly we detect the
almonds based on quality in two categories- either good or bad by
creating a virtual environment for object detection. This detection
is made possible through python libraries such as yolo and
tensorflow. we created our own dataset and labelled it for training model. Then we transfer this model it into raspberry pi. we used raspberry
pi 4 and global shutter camera along with camera lens for detection of almonds. Now we will be using servo motors for the segregation part. Almonds will move on conveyer belt, get detected through
camera and then get segregated by action of motor. Our next step in this project is to design a mechanical model for segregation which is under process. This Project was included under the summer internships organized
by experiential learning center(ELC), Thapar University, Patiala in
the month of june and july 2023. I also received a certificate for doing internship under ELC. 
link for the project:https://drive.google.com/drive/folders/1sjS_RJzBdHUvsUVkVgpDmdGct_9FBxtI?usp=sharing
steps to run tf2-gpu on windows wsl2 system
note:- only for tf 2.11 and above on windows

1. install wsl2 (wsl --install,wsl --update)
2. install latest ubuntu distro(wsl --install -d -(distro))
3. install cuda toolkit
4. create and activate virtual environment
5. install cuda and cdnn
6. install tensorflow 
7. vala
8. not working


alternate:-
1. roboflow autoML-https://app.roboflow.com/thapar-university-patiala/alto/2

