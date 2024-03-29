# Project

## 1. DOCKER (./docker)

A. [install docker](https://docs.docker.com/get-docker/) </br>
B. docker-compose up -d

---

## 2. SERVER (./server)

A. [install nodejs](https://nodejs.org/en/download/) </br>
B. npm install</br>
C. npm install -g nodemon</br>
D. run "node gen.js" to create the TOKEN_SECRET value (won't work without it) </br>
E. make .env file with the following (change values in production (including the 'xxx' values)):

    TOKEN_SECRET = xxx
    COOKIE_PARSER_SECRET = xxx
    ARGON2_SECRET = xxx
    ARGON2_TIME_COST = 40
    ARGON2_MEM_COST = 5120
    ARGON2_NUM_THREADS = 1
    NANOID_LEN = 4
    CLIENT_API = http://localhost:3000
    EXPIRE_ACCOUNT = 86400
    SERVER_AMOUNT = 1
    NODE_ENV = development
    REDIS_URL = xxx

E. nodemon (run nodejs server)</br>

---


## THUNDERCLIENT SERVER (./server/tests)
A [video tutorial (optional)](https://www.youtube.com/watch?v=NKZ0ahNbmak) </br>
B. import JSON(s)</br>
C. run collection in **numbered order**</br>


---

## ALL HELPFUL/IMPORTANT INSTALLS
[Nodejs](https://nodejs.org/en/download/)</br>
[Git](https://git-scm.com/downloads)</br>
[Docker](https://docs.docker.com/get-docker/)</br>
[VScode](https://code.visualstudio.com/)</br>
[VScode (Svelte)](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode)</br>
[VScode (Docker)](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)</br>
[VScode (Thunder Client)](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)</br>
[AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager)</br>

---

## OTHER
npm: update packages
```
npm install -g npm-check-updates
npm ncu -u
npm update
```


