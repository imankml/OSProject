# OSProject Running Containers for Application Development

Group Name: __Awan Nano__. 

Section: __Section 7__. 

Team Mates:
1. __NUR AMIRA NABILA BINTI MOHD AB RAHMAN__ and __2220682__
2. __Fill name__ and __matric no__
3. __NURUL NASREEN BINTI ABDUL MALIK__ and __2217464__

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** __Fill answer here__.
2. How many files and folders are in this repository. ***(1 mark)*** __Fill answer here__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** 
    __Ubuntu Linux.__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
  __1. CPU 2-CORE: RAM = 8GB DISK = 32GB.__
  __2. CPU 4-CORE: RAM = 16GB DISK = 32GB.__
  <img src="./image_6.png" width="70%">

3. Why must we commit and sync our current work on source control? ***(1 mark)*** 
  __To save changes to the local repository, fetch and merge updates from the remote repository to synchronize with local modifications, and then push the changes back to the remote repository.__

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
__@MiraNabilaRahman ➜ /workspaces/OSProject (main) $ pwd/workspaces/OSProject__.
2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
__
@MiraNabilaRahman ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin__

3. Run the command **df** . ***(1 mark)*** 
__
@MiraNabilaRahman ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10714720  20438860  35% /
tmpfs              65536        0     65536   0% /dev
shm                65536        0     65536   0% /dev/shm
/dev/root       30298176 13280992  17000800  44% /vscode
/dev/sdb1       46127956 18762772  24989608  43% /tmp
/dev/loop4      32847680 10714720  20438860  35% /workspaces
__

4. Run the command **du** . ***(1 mark)*** 
__
@MiraNabilaRahman ➜ /workspaces/OSProject (main) $ du
8       ./.git/refs/heads
4       ./.git/refs/tags
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
68      ./.git/hooks
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/branches
4       ./.git/objects/info
3468    ./.git/objects/pack
3476    ./.git/objects
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
3756    ./.git
28      ./nodejs-app/node_modules/content-type
12      ./nodejs-app/node_modules/sqlstring/lib
40      ./nodejs-app/node_modules/sqlstring
28      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/constants
12      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/protocol/sequences/promise
40      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/protocol/sequences
12      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/protocol/packets/params
44      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/protocol/packets
88      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/protocol
16      ./nodejs-app/node_modules/mysql2/typings/mysql/lib/parsers
168     ./nodejs-app/node_modules/mysql2/typings/mysql/lib
184     ./nodejs-app/node_modules/mysql2/typings/mysql
188     ./nodejs-app/node_modules/mysql2/typings
236     ./nodejs-app/node_modules/mysql2/lib/constants
44      ./nodejs-app/node_modules/mysql2/lib/base
28      ./nodejs-app/node_modules/mysql2/lib/auth_plugins
32      ./nodejs-app/node_modules/mysql2/lib/promise
140     ./nodejs-app/node_modules/mysql2/lib/packets
28      ./nodejs-app/node_modules/mysql2/lib/parsers
80      ./nodejs-app/node_modules/mysql2/lib/commands
676     ./nodejs-app/node_modules/mysql2/lib
12      ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/.idea/codeStyles
8       ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/.idea/inspectionProfiles
36      ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/.idea
232     ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/encodings/tables
360     ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/encodings
8       ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/.github
24      ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite/lib
456     ./nodejs-app/node_modules/mysql2/node_modules/iconv-lite
460     ./nodejs-app/node_modules/mysql2/node_modules
1364    ./nodejs-app/node_modules/mysql2
28      ./nodejs-app/node_modules/statuses
8       ./nodejs-app/node_modules/get-proto/test
8       ./nodejs-app/node_modules/get-proto/.github
72      ./nodejs-app/node_modules/get-proto
8       ./nodejs-app/node_modules/depd/lib/browser
12      ./nodejs-app/node_modules/depd/lib
52      ./nodejs-app/node_modules/depd
40      ./nodejs-app/node_modules/serve-static
48      ./nodejs-app/node_modules/safe-buffer
8       ./nodejs-app/node_modules/side-channel-list/test
8       ./nodejs-app/node_modules/side-channel-list/.github
64      ./nodejs-app/node_modules/side-channel-list
20      ./nodejs-app/node_modules/encodeurl
24      ./nodejs-app/node_modules/methods
64      ./nodejs-app/node_modules/long/umd
144     ./nodejs-app/node_modules/long
20      ./nodejs-app/node_modules/array-flatten
8       ./nodejs-app/node_modules/hasown/.github
48      ./nodejs-app/node_modules/hasown
8       ./nodejs-app/node_modules/side-channel-map/test
8       ./nodejs-app/node_modules/side-channel-map/.github
60      ./nodejs-app/node_modules/side-channel-map
32      ./nodejs-app/node_modules/proxy-addr
24      ./nodejs-app/node_modules/cookie-signature
148     ./nodejs-app/node_modules/lru-cache
12      ./nodejs-app/node_modules/mime/src
80      ./nodejs-app/node_modules/mime
24      ./nodejs-app/node_modules/vary
16      ./nodejs-app/node_modules/dunder-proto/test
8       ./nodejs-app/node_modules/dunder-proto/.github
72      ./nodejs-app/node_modules/dunder-proto
8       ./nodejs-app/node_modules/call-bind-apply-helpers/test
8       ./nodejs-app/node_modules/call-bind-apply-helpers/.github
96      ./nodejs-app/node_modules/call-bind-apply-helpers
28      ./nodejs-app/node_modules/media-typer
32      ./nodejs-app/node_modules/generate-function
24      ./nodejs-app/node_modules/forwarded
8       ./nodejs-app/node_modules/es-object-atoms/test
8       ./nodejs-app/node_modules/es-object-atoms/.github
76      ./nodejs-app/node_modules/es-object-atoms
28      ./nodejs-app/node_modules/body-parser/lib/types
40      ./nodejs-app/node_modules/body-parser/lib
100     ./nodejs-app/node_modules/body-parser
232     ./nodejs-app/node_modules/iconv-lite/encodings/tables
348     ./nodejs-app/node_modules/iconv-lite/encodings
36      ./nodejs-app/node_modules/iconv-lite/lib
412     ./nodejs-app/node_modules/iconv-lite
36      ./nodejs-app/node_modules/content-disposition
4       ./nodejs-app/node_modules/.bin
24      ./nodejs-app/node_modules/destroy
20      ./nodejs-app/node_modules/escape-html
44      ./nodejs-app/node_modules/raw-body
32      ./nodejs-app/node_modules/express/lib/router
12      ./nodejs-app/node_modules/express/lib/middleware
128     ./nodejs-app/node_modules/express/lib
272     ./nodejs-app/node_modules/express
20      ./nodejs-app/node_modules/object-inspect/example
8       ./nodejs-app/node_modules/object-inspect/test/browser
96      ./nodejs-app/node_modules/object-inspect/test
8       ./nodejs-app/node_modules/object-inspect/.github
216     ./nodejs-app/node_modules/object-inspect
8       ./nodejs-app/node_modules/call-bound/test
8       ./nodejs-app/node_modules/call-bound/.github
56      ./nodejs-app/node_modules/call-bound
32      ./nodejs-app/node_modules/http-errors
12      ./nodejs-app/node_modules/aws-ssl-profiles/lib/@types
232     ./nodejs-app/node_modules/aws-ssl-profiles/lib/profiles/ca
236     ./nodejs-app/node_modules/aws-ssl-profiles/lib/profiles
260     ./nodejs-app/node_modules/aws-ssl-profiles/lib
276     ./nodejs-app/node_modules/aws-ssl-profiles
32      ./nodejs-app/node_modules/mime-types
24      ./nodejs-app/node_modules/inherits
8       ./nodejs-app/node_modules/setprototypeof/test
32      ./nodejs-app/node_modules/setprototypeof
16      ./nodejs-app/node_modules/get-intrinsic/test
8       ./nodejs-app/node_modules/get-intrinsic/.github
80      ./nodejs-app/node_modules/get-intrinsic
24      ./nodejs-app/node_modules/send/node_modules/encodeurl
20      ./nodejs-app/node_modules/send/node_modules/ms
48      ./nodejs-app/node_modules/send/node_modules
116     ./nodejs-app/node_modules/send
28      ./nodejs-app/node_modules/ipaddr.js/lib
64      ./nodejs-app/node_modules/ipaddr.js
28      ./nodejs-app/node_modules/math-intrinsics/constants
12      ./nodejs-app/node_modules/math-intrinsics/test
8       ./nodejs-app/node_modules/math-intrinsics/.github
172     ./nodejs-app/node_modules/math-intrinsics
24      ./nodejs-app/node_modules/fresh
24      ./nodejs-app/node_modules/merge-descriptors
52      ./nodejs-app/node_modules/qs/dist
120     ./nodejs-app/node_modules/qs/test
8       ./nodejs-app/node_modules/qs/.github
44      ./nodejs-app/node_modules/qs/lib
304     ./nodejs-app/node_modules/qs
8       ./nodejs-app/node_modules/side-channel/test
8       ./nodejs-app/node_modules/side-channel/.github
68      ./nodejs-app/node_modules/side-channel
8       ./nodejs-app/node_modules/lru.min/browser
28      ./nodejs-app/node_modules/lru.min/lib
60      ./nodejs-app/node_modules/lru.min
36      ./nodejs-app/node_modules/accepts
220     ./nodejs-app/node_modules/mime-db
36      ./nodejs-app/node_modules/type-is
32      ./nodejs-app/node_modules/on-finished
20      ./nodejs-app/node_modules/ms
32      ./nodejs-app/node_modules/is-property
24      ./nodejs-app/node_modules/unpipe
40      ./nodejs-app/node_modules/finalhandler
24      ./nodejs-app/node_modules/toidentifier
20      ./nodejs-app/node_modules/path-to-regexp
64      ./nodejs-app/node_modules/safer-buffer
48      ./nodejs-app/node_modules/denque
8       ./nodejs-app/node_modules/side-channel-weakmap/test
8       ./nodejs-app/node_modules/side-channel-weakmap/.github
60      ./nodejs-app/node_modules/side-channel-weakmap
12      ./nodejs-app/node_modules/has-symbols/test/shams
24      ./nodejs-app/node_modules/has-symbols/test
8       ./nodejs-app/node_modules/has-symbols/.github
88      ./nodejs-app/node_modules/has-symbols
24      ./nodejs-app/node_modules/negotiator/lib
52      ./nodejs-app/node_modules/negotiator
28      ./nodejs-app/node_modules/bytes
36      ./nodejs-app/node_modules/debug/src
112     ./nodejs-app/node_modules/debug
28      ./nodejs-app/node_modules/etag
20      ./nodejs-app/node_modules/function-bind/test
12      ./nodejs-app/node_modules/function-bind/.github
80      ./nodejs-app/node_modules/function-bind
24      ./nodejs-app/node_modules/parseurl
20      ./nodejs-app/node_modules/ee-first
12      ./nodejs-app/node_modules/seq-queue/test
12      ./nodejs-app/node_modules/seq-queue/lib
60      ./nodejs-app/node_modules/seq-queue
24      ./nodejs-app/node_modules/utils-merge
8       ./nodejs-app/node_modules/es-define-property/test
8       ./nodejs-app/node_modules/es-define-property/.github
56      ./nodejs-app/node_modules/es-define-property
8       ./nodejs-app/node_modules/gopd/test
8       ./nodejs-app/node_modules/gopd/.github
60      ./nodejs-app/node_modules/gopd
24      ./nodejs-app/node_modules/named-placeholders
36      ./nodejs-app/node_modules/cookie
8       ./nodejs-app/node_modules/es-errors/test
8       ./nodejs-app/node_modules/es-errors/.github
100     ./nodejs-app/node_modules/es-errors
24      ./nodejs-app/node_modules/range-parser
6692    ./nodejs-app/node_modules
6744    ./nodejs-app
1972    ./images
12788   .
__.

5. Run the command **ls** . ***(1 mark)*** 
```bash
__@MiraNabilaRahman ➜ /workspaces/OSProject (main) $ ls__
__README.md  image-1.png  image-2.png  image-3.png  image-4.png  image-5.png  image.png  image_6.png  images  nodejs-app__.
```

6. Run the command **ls -asl** . ***(1 mark)*** 
__@MiraNabilaRahman ➜ /workspaces/OSProject (main) $ ls -asl
total 340
  4 drwxrwxrwx+ 5 codespace root        4096 Jan 30 05:23 .
  4 drwxr-xrwx+ 5 codespace root        4096 Jan 30 03:07 ..
  4 drwxrwxrwx+ 9 codespace root        4096 Jan 30 14:47 .git
 36 -rw-rw-rw-  1 codespace root       36154 Jan 30 14:38 README.md
 44 -rw-rw-rw-  1 codespace root       41576 Jan 30 03:07 image-1.png
 44 -rw-rw-rw-  1 codespace root       41030 Jan 30 03:07 image-2.png
 12 -rw-rw-rw-  1 codespace root       11290 Jan 30 03:07 image-3.png
108 -rw-rw-rw-  1 codespace root      109814 Jan 30 03:07 image-4.png
 40 -rw-rw-rw-  1 codespace root       40828 Jan 30 03:07 image-5.png
 20 -rw-rw-rw-  1 codespace root       16599 Jan 30 03:07 image.png
 16 -rw-rw-rw-  1 codespace codespace  14987 Jan 30 05:23 image_6.png
  4 drwxrwxrwx+ 2 codespace root        4096 Jan 30 03:07 images
  4 drwxrwxrwx+ 3 codespace root        4096 Jan 30 03:07 nodejs-app
__.

7. Run the command **free -h** . ***(1 mark)*** __Fill answer here__.

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** __Fill answer here__.

9. Run the command **top** and type **q** to quit. ***(1 mark)*** __Fill answer here__.

10. Run the command **uname -a**. ***(1 mark)*** __Fill answer here__.

11. What is the available free memory in the system. ***(1 mark)*** __Fill answer here__.

12. What is the available disk space mounted on /workspace. ***(1 mark)*** __Fill answer here__.

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __Fill answer here__.

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __Fill answer here__.

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __Fill answer here__.

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __Fill answer here__.

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __Fill answer here__.


## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __Fill answer here__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Fill answer here__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __Fill answer here__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Fill answer here__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Fill answer here__.
2. What port is the apache web server running. ***(1 mark)*** __Fill answer here__.
3. What port is open for http protocol on the host machine? ***(1 mark)*** __Fill answer here__.

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 

__BusyBox is a compact software suite that consolidates numerous standard UNIX utilities into a single, lightweight executable. It is widely utilized in containers due to its simplicity and low resource usage.__

__The `--name` flag in the `docker run` command allows you to assign a specific name to a container, simplifying its identification and management.__

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** __![alt text](image-5.png)__.

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** 

__bluenet: 172.18.0.1__

__rednet: 172.19.0.1__

4. What is the network address for the running container c1 and c2? ***(1 mark)*** 

__c1: 172.18.0.2__

__c2: 172.19.0.2__

![alt text](image-1.png)

![alt text](image-2.png)

5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** __Fill answer here__.
![alt text](image-3.png)

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)***

 __Yes__.
 ![alt text](image-4.png)

2. What is different from the previous ping in the section above? ***(1 mark)*** 
__In the previous attempt, the operation failed because `c1` and `c2` were connected to different networks, `rednet` and `bluenet`, respectively. Due to this network isolation, the containers were unable to communicate with each other, resulting in a "bad address" error during the ping attempt.__

__In this new attempt, both `c1` and `c2` are connected to the same network, `bridgenet`, which enables proper communication between them. By being on the same network, they can resolve each other’s addresses and exchange data seamlessly. Consequently, the ping command succeeds without any errors, confirming that the containers are now able to communicate as expected.__

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** 
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ curl http://localhost:3000/random
curl: (7) Failed to connect to localhost port 3000: Connection refused
```

__The issue arises because the Node.js container and the MySQL container are on separate Docker networks, preventing them from communicating with each other.__

2. Show the instruction needed to make this work. ***(1 mark)*** 

__To connect both containers,__

__1. We first need to create a bridge network. This can be done using the following command:__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker network create mybridge
```
__2. Next, connect both containers to the  the newly created network.__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker network connect mybridge mysql-container
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker network connect mybridge nodejs-container
```
At this point, the instructions in step 5 should have worked, but in my case, there is an authentication issue between the Node.js MySQL client and the MySQL server. The following steps outline how to resolve the issue:

__To resolve the authentication issues between the Node.js MySQL client and the MySQL server__

 __1. First, update the authentication method for the MySQL user:__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker exec -it mysql-container mysql -uroot -p
Enter password: 
```
When prompted, enter the root password.

__2. After connecting to MySQL, execute the following commands:__
```
mysql> alter user 'myuser'@'%' identified with caching_sha2_password by 'mypassword';
Query OK, 0 rows affected (0.01 sec)

mysql> flush privileges;
Query OK, 0 rows affected, 1 warning (0.00 sec)
```
__3. Because mysql2 has greater support for caching_sha2_password, we must upgrade the Node.js application to use it instead of mysql. Enter the following commands in the node.js-app directory:__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ npm uninstall mysql

removed 12 packages, and audited 70 packages in 764ms

14 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ npm install mysql2

added 12 packages, and audited 82 packages in 1s

15 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```
__4. In the index.js file, modify the connection setup like this by using the command 'nano index.js':__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ nano index.js file

Update the index.js file exactly as shown below:

const express = require('express');
const mysql = require('mysql2');

const app = express();
const port = 3000;

// Create a MySQL connection
const connection = mysql.createConnection({
    host: 'mysql-container',
    user: 'myuser',
    password: 'mypassword',
    database: 'mydatabase',
});

// Connect to MySQL
connection.connect((err) => {
    if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
    }
    console.log('Connected to MySQL');
});

// Define a route to get a random row
app.get('/random', (req, res) => {
    const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
    connection.query(query, (err, results) => {
        if (err) {
            console.error('Error executing query:', err);
            return res.status(500).json({ error: 'Database query failed' });
        }
        res.json(results[0]);
    });
});

// Start the server
app.listen(port, () => {
    console.log(`Server running at http://localhost:${port}`);
});
```
__5. Rebuild the Docker image for Node.js:__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker build -t nodejs-app .
[+] Building 3.7s (11/11) FINISHED          docker:default
 => [internal] load build definition from Dockerfile  0.0s
 => => transferring dockerfile: 407B                  0.0s
 => [internal] load metadata for docker.io/library/n  1.5s
 => [auth] library/node:pull token for registry-1.do  0.0s
 => [internal] load .dockerignore                     0.0s
 => => transferring context: 2B                       0.0s
 => [1/5] FROM docker.io/library/node:14@sha256:a158  0.0s
 => [internal] load build context                     0.1s
 => => transferring context: 70.79kB                  0.1s
 => CACHED [2/5] WORKDIR /usr/src/app                 0.0s
 => CACHED [3/5] COPY package*.json ./                0.0s
 => CACHED [4/5] RUN npm install                      0.0s
 => [5/5] COPY . .                                    0.3s
 => exporting to image                                1.8s
 => => exporting layers                               1.8s
 => => writing image sha256:f8a8887d01a2e0a3bd0610fe  0.0s
 => => naming to docker.io/library/nodejs-app         0.0s
```
__6. Launch a new Node.js container after stopping and removing the previous one:__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker stop nodejs-container
nodejs-container
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker rm nodejs-container
nodejs-container
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ docker run --name nodejs-container --network mybridge -p 3000:3000 -d nodejs-app
a82e15e98d91cc2116784aa04f52064c2dd88bfbf3d4907c2b5f54b7f27b5f44
```
__7. Verify the connection__
```
@nanenmalik ➜ /workspaces/OSProject/nodejs-app (main) $ curl http://localhost:3000/random
{"id":1,"name":"example1","value":"value1"}
```
__Finally, the node.js application can be accessed.__

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
