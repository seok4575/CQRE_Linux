# cqre_linux
20184575 seok

## Hello.c git update

1. install git		
  - $ sudo apt-get install git

2. rogin git		
  - $ git config --global user.name (username)
  - $ git config --glabal user.email (useremail)
  - $ git config --global --list
    - ex) username : seok4575

3. create a new repository		
  * Initialize this repository with a README - check!
    - ex) repository name : cqre_linux 
           -> address : https://github.com/seok4575/cqre_linux
  
4. create a source file		
  - printf("Hello world!");
    - ex) hello.c
  
5. git clone		
  - $ git clone (address)
    - create folder cqre_linux
  
6. git add		
  - $ git add (filename)
  
7. git commit		
  - $ git commit -m "message"
    - ex) message : print hello world
  
8. git remote		
  - $ git remote add origin (address)
  
9. git push		
  - $ git push origin master

10. update a source file		
  - printf("Hello Linux!);
    - ex) hello.c
  
11 = 6. git add		
  - $ git add hello.c

12 = 7. git commit		
  - $ git commit -m "update hello linux!"
  
13 = 9. git push		
  - $ git push origin master
  
