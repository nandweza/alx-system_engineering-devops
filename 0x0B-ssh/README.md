<h1>0x0B. SSH</h1>
<br>
<h2>Description</h2>
<p>Along with this project, you have been attributed an Ubuntu server, living in a datacenter far far away. Like level 2 of the application process, you will connect using ssh. But contrary to level 2, you will not connect using a password but an RSA key. We’ve configured your server with the public key you created in the first task of a previous project shared in your intranet profile.</p>
<br>
<h2>Table of Contents</h2>
<br>
<table>
<tr>
<th>File</th>
<th>Description</th>
</tr>
<tr>
<td>0-use_a_private_key</td>
<td> Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu.</td>
</tr>
<tr>
<td>1-create_ssh_key_pair</td>
<td>Bash script that creates an RSA key pair.</td>
</tr>
<tr>
<td>2-ssh_config</td>
<td> Client configuration file</td>
</tr>
<tr>
<td>0x0B-ssh</td>
<td>Add the SSH public key below to your server so that we can connect using the ubuntu user.</td>
</tr>
<tr>
<td>100-puppet_ssh_config.pp</td>
<td>Client configuration file (w/ Puppet)</td>
</tr>
</table>