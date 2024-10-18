<h1>OpenSSH Server</h1>
<p>OpenSSH is a powerful collection of tools for remotely controlling networked computers and transferring data between them.</p>

<h3>Install the SSH Server and Client on our device(For Ubuntu)</h3>
<b>1</b> Before installing the package in Linux, It's generally a good idea to update or sometime upgrade your package.

           sudo apt update

<b>2</b> Install the ssh.

     sudo apt install openssh-client openssh-server

<b>3</b> Start the ssh service.

This command immediately starts the services, but will not automatically start at boot.

     sudo systemctl start ssh

<b>4</b> Enable the ssh.

This command start the ssh service to start automatically at boot but doesnot immediately start the service.

     sudo systemctl enable ssh

<b>5</b> Check the status.

In the Active it should show `Active: active(running)`

     systemctl status ssh

<b>6</b>Enable the firewall.

     sudo ufw enable

<b>7</b>Include the ssh protocol to firewall.

     sudo ufw allow ssh

<b>8</b> Check the status.

     sudo ufw status

<b>9</b>Find the ip address of your pc.

     ifconfig

Now we can connect using the ip address, username and password in your android phone.