# vagrantfile

1. download vagrant and vmbox
2. create a new folder.
3. open terminal and run vagrant init
4. Open the Vagrantfile and copy paste from vagrantfile in github
5. Change the vagrant config as you need and save it
6. Run vagrant up
7. vagrant ssh
8. install docker
9. open another terminal and paste
```

ssh -i "~/.ssh/private_key" -p 2222 -L 3000:localhost:3000 -L 7007:localhost:7007 vagrant@localhost

```
10. docker run -d -p 3000:3000 -p 7007:7007 ${backstageimage}
