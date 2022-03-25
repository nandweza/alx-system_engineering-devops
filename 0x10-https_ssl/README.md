<h1>0x10. HTTPS SSL</h1>
<hr>
<br>
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/276/FlhGPEK.png">
<br>
<h2>General</h2>
<br>
<ul>
<li>What is HTTPS SSL 2 main roles</li>
<li>What is the purpose encrypting traffic</li>
<li>What SSL termination means</li>
</ul>
<br>
<h2>Table of Contents.</h2>
<br>
<table>
<tr>
<th>Files</th>
<th>Description</th>
</tr>
<tr>
<td>0-world_wide_web</td>
<td>Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains.</td>
</tr>
<tr>
<td>1-haproxy_ssl_termination</td>
<td>Create a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www..</td>
</tr>
<tr>
<td>100-redirect_http_to_https</td>
<td>Configure HAproxy to automatically redirect HTTP traffic to HTTPS.</td>
</tr>
</table>