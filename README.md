# Follow the instructions to install Gitlab to your server

Run the following commands:

    $ docker-compose up -d
    $ docker exec -it gitlab-ce grep 'Password:' /etc/gitlabinitial_root_password

Go to your browser and copy the following URL:

    http://localhost:8080

There, you can use **root** as a username to login and the password is the password you copied on your clipboard.
