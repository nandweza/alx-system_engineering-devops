<h1>0x0F. Load balancer</h1>
<br>
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/275/qfdked8.png">
<br>
<h2>Background Context.</h2>
<br>
<p>In this Project, will write Bash scripts to  improve our web stack so that there is redundancy for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.</p>
<br>
<h2>Concepts</h2>
<br>
<ul>
<li><a href="https://alx-intranet.hbtn.io/concepts/46">Load balancer</a></li>
<li><a> href="https://alx-intranet.hbtn.io/concepts/68">Web stack debugging</a></li>
</ul>
<br>
<h2>Resources</h2>
<br>
<ul>
<li><a href="https://alx-intranet.hbtn.io/rltoken/B7f3oz8i3Xvvom_YQZzLnQ">Introduction to load-balancing and HAproxy</a></li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/sZ9v3Vq2tgLwN_PWVQketw">HTTP header</a></li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/2VRAgtKKR9g6Xfb0xzGiSg">Debian/Ubuntu HAProxy packages</a></li>
</ul>
<br>
<h2>Table of Contents</h2>
<br>
<table>
<tr>
<th>Files</th>
<th>Description</th>
</tr>
<tr>
<td>0-custom_http_response_header</td>
<td> Double the number of webservers</td>
</tr>
<tr>
<td>1-install_load_balancer</td>
<td> Install your load balancer</td>
</tr>
<tr>
<td>2-puppet_custom_http_response_header.pp</td>
<td>Add a custom HTTP header with Puppet</td>
</tr>
</table>
