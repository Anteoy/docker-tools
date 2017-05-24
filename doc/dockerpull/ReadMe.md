116  2017-05-24 16:04:43 touch Dockerfile
117  2017-05-24 16:04:47 vim Dockerfile 
118  2017-05-24 16:05:05 docker build .
119  2017-05-24 16:05:10 docker images
120  2017-05-24 16:05:41 docker tag 1024a2c2bb55 anteoy/mysql:rbr
121  2017-05-24 16:05:44 docker images
122  2017-05-24 16:05:54 docker login
123  2017-05-24 16:06:53 docker push anteoy/mysql anteoy/mysql # invalid
124  2017-05-24 16:07:16 docker push --help 
125  2017-05-24 16:07:41 docker push 
126  2017-05-24 16:07:49 docker push anteoy/mysql
127  2017-05-24 16:12:36 docker ps
128  2017-05-24 16:13:47 docker commit 31060cd86c2e anteoy/mysql:cmt
129  2017-05-24 16:13:52 docker images
130  2017-05-24 16:14:11 docker push anteoy/mysql:cmt 