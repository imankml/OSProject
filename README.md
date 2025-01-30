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

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __Fill answer here__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __Fill answer here__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Fill answer here__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** __Fill answer here__.
2. Run the command **cat /etc/passwd** . ***(1 mark)*** __Fill answer here__.
3. Run the command **df** . ***(1 mark)*** __Fill answer here__.
4. Run the command **du** . ***(1 mark)*** __Fill answer here__.
5. Run the command **ls** . ***(1 mark)*** __Fill answer here__.
6. Run the command **ls -asl** . ***(1 mark)*** __Fill answer here__.
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
