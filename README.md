# run-python-file-as-service

## Modify config.json file

- Give your service name without any space & special charecter 
- Give the command that runs your file.


Note: If your file is located in  /home/abu/codes/bc-projects/create-system-service-tutorial/hello_world.py  this path and you want to run it using python3 , then give the full command.
If your file is a Java file and you want to run the file using Java, you can also add the command to run the Java file.
If your file is Javascript file and you want to run it using Node, same: give the command to run the file



## Create the service using following command:
```
sudo sh create_service.sh 

```

- This command will create a service named you given in your json file
- Log file will be stored on /var/log/your_service_name.log file
