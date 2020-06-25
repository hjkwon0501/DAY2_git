# DAY2_git
user@DESKTOP-14530KF MINGW64 /c/User/user/test
$ docker build --tag hjkwon0501/ubuntu2 .
Sending build context to Docker daemon  536.6kB
Step 1/3 : FROM ubuntu
 ---> 74435f89ab78
Step 2/3 : RUN apt update
 ---> Using cache
 ---> eaffe9d04e59
Step 3/3 : RUN apt install -y nginx
 ---> Using cache
 ---> 1e1929b1fc37
Successfully built 1e1929b1fc37
Successfully tagged hjkwon0501/ubuntu2:latest
SECURITY WARNING: You are building a Docker image from Windows against a non-Windows Docker host. All files and directories added to build context will have '-rwxr-xr-x' permissions. It is recommended to double check and reset permissions for sensitive files and directories.
