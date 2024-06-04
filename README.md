# Follow the instructions to install Gitlab to your server

Run the following commands:

    $ docker-compose up -d
    $ docker exec -it gitlab-ce grep 'Password:' /etc/gitlabinitial_root_password

Copy the paswword into your clipboard, and run the following: 

    $ ifconfig

Get your ip address and go your browser at the following URL:

    http://<IP>:8080

There, you can use **root** as a username to login and the password is the password you copied on your clipboard.
