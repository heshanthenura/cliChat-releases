
# <p align="center"> Command Line Chat Application </p>
 
## <p align="center"> Command Line Chat Application Made Using Socket Utility </p>

<img style="text-align: center;" src="https://user-images.githubusercontent.com/75155192/184914041-e580521e-b5ad-4a26-a0ec-37a877b3f519.png">


### I know there are lots of apps that are more efficient and easy to use. But I created this as a hobby project. You can create a Server and Client to communicate. The Server is made with ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) and client made with ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white). [My Kind Request](#5kind-request)
<br>

<details open>
    <summary>Table of Content</summary>
    <ol>
        <li><a href="#1installation">Installation</a></li>
        <li><a href="#2execution">Execution</a>
            <ul>
                <li><a href="#windows">Windows</li>
                <li><a href="#linux">Linux</li>
            </ul>
        </li>
        <li><a href="#3usage">Usage</a></li>
        <li><a href="#4commands">Commands</a></li>
        <li><a href="#5kind-request">Kind Request</a></li>
    </ol>
</details>

## 1.Installation

If you are using *LINUX* you can download files from [here](https://github.com/heshanthenura/cliChat-releases/tree/main/Linux).
If you are using *WINDOWS* you can download files from [here](https://github.com/heshanthenura/cliChat-releases/tree/main/Windows).

## 2.Execution
   ### Windows
<hr>

go to the directory where downloaded file are located
and open CMD or POWERSHELL in that location
run the app using `cliChat-server.exe` or `cliChat-client.exe`

### Linux
<hr>

go to the directory where downloaded file are located
and open TERMINAL in that location
run the app using `./cliChat-server` or `./cliChat-client.exe`

## 3.Usage
Usage is same for any OS

###### First Run Server Application using `./cliChat-server(Linux) or ./cliChat-server(Windows)`

<hr>

* Then it will ask port number to run the Server

![port](https://user-images.githubusercontent.com/75155192/184917231-1994d988-0050-4e85-bf63-a4d1250b8a26.png)
<hr>

* If you see message `Server Started on PORT <port>`. Your server started successfully

![succsess](https://user-images.githubusercontent.com/75155192/184918793-dc919c77-4e5d-46fb-91e0-004534556682.png)
<hr>

###### Then Run Client Application using `./cliChat-client(Linux) or ./cliChat-client.exe(Windows)`
<hr>

* You should enter a NickName first

![nickanme](https://user-images.githubusercontent.com/75155192/184922417-0ba40033-d327-41c3-902d-6d8a0129dc77.png)
<hr>

* Then it will ask for the Address of server to connect

![address](https://user-images.githubusercontent.com/75155192/184924113-c75c253b-5f70-4959-971f-2c377f1b165f.png)
<hr>

* If there are no any Error you can see `Connected to Server <address>`

![csucces](https://user-images.githubusercontent.com/75155192/184924650-a160c05a-7733-4793-b050-65e2be86f007.png)
<hr>

* Server also can see your connectivity

![connectivity](https://user-images.githubusercontent.com/75155192/184926225-b4be159c-b030-4900-830b-12721a94fdd4.png)
<hr>

* Now you can send messages by just typing on console.

![mfm](https://user-images.githubusercontent.com/75155192/184927245-5840c1b7-4aa2-4e5d-8d40-119d9779b312.png)
<hr>

* Server can see your Message

![sm](https://user-images.githubusercontent.com/75155192/184927484-eb7fd0a6-d417-4ef3-ad9d-ed82e9912789.png)
<hr>

* Other connected users also can see your messages

![oum](https://user-images.githubusercontent.com/75155192/184927763-f3cc58f7-d93f-4084-b949-6d2de8a8b002.png)

* When You Disconnects other Users and Server can see you disconnection

![dc](https://user-images.githubusercontent.com/75155192/184928337-d2745bcf-12fa-40bb-926b-645de36da6d6.png)
<hr>

That how you should use this application.

## 4.Commands
 1. /count - Find number of users in the Server
 2. /chg \<new name> - Change NickName ex:- /chg Elon

`Commands are still Not Implemented`

## 5.Kind Request

##### Test my app, find bugs and report. This is not my my final app. I want to invent another useful application using this concept. Suggest me what commands should I implement and what are other changes that I should do.