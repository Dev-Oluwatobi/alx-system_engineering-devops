### 0x0C. Web server
### Background Context
![image1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/266/8Gu52Qv.png)
https://www.youtube.com/watch?v=AZg4uJkEa-4&feature=youtu.be&hd=1
In this project, some of the tasks will be graded on 2 aspects:

Is your web-01 server configured according to requirements
Does your answer file contain a Bash script that automatically performs commands to configure an Ubuntu machine to fit requirements (meaning without any human intervention)
For example, if I need to create a file /tmp/test containing the string hello world and modify the configuration of Nginx to listen on port 8080 instead of 80, I can use emacs on my server to create the file and to modify the Nginx configuration file /etc/nginx/sites-enabled/default.

But my answer file would contain:

sylvain@ubuntu cat 88-script_example
#!/usr/bin/env bash
# Configuring a server with specification XYZ
echo hello world > /tmp/test
sed -i 's/80/8080/g' /etc/nginx/sites-enabled/default
sylvain@ubuntu
As you can tell, I am not using emacs to perform the task in my answer file. This exercise is aiming at training you on automating your work. If you can automate tasks that you do manually, you can then automate yourself out of repetitive tasks and focus your energy on something more interesting. For an SRE, that comes very handy when there are hundreds or thousands of servers to manage, the work cannot be only done manually. Note that the checker will execute your script as the root user, you do not need to use the sudo command.

A good Software Engineer is a lazy Software Engineer.
![Image](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/266/82VsYEC.jpg)
## Resources
1. https://intranet.alxswe.com/rltoken/6TI3HiyFdwrbXWKVF24Gxw
2. https://intranet.alxswe.com/rltoken/vkVMGlaf39j2DWAQWzo6EA
3. https://intranet.alxswe.com/rltoken/zKrpVxWuUHVdW4URAjdFbw
4. https://intranet.alxswe.com/rltoken/Ar18u5sRis1fkvkVgzdcqg
5. https://intranet.alxswe.com/rltoken/xi3peVqYl02PfpHHHlCtxQ
6. https://intranet.alxswe.com/rltoken/sBrrP4EAmI3NoYjIgZrUhw
7. https://intranet.alxswe.com/rltoken/Eaa4ZuKvye941hTkP8VlBQ
8. https://intranet.alxswe.com/rltoken/eJSp2QFTY6jqqNtz8OVDEw
9. https://intranet.alxswe.com/rltoken/7WMNY5CWD-CBrxmQrdmfPg

# https://intranet.alxswe.com/rltoken/BGa6RrS0dnM6EdBGS_ZDUw
https://intranet.alxswe.com/rltoken/IZ2fyYn1qNZ9RXXsg5vG1g
