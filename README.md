# NIM lab additional instructions

Some edits/ hints for  https://clouddocs.f5.com/training/community/nginx/html/class4/class4.html 

> Step 3: Install nginx-manager
for speed run the following
```
./reset.sh install-server
```

> Step 4: Enable and start the service
sudo systemctl enable nginx-agent --now
```
sudo systemctl restart nginx-agent
```
To generate some load, use the command line on the nginx-manager server, there is a load-gen.sh file.  Simply run it with a parameter of how many times to run.  It'll through traffic at the websites for each nginx instance.
```
./load-test.sh 1
```
