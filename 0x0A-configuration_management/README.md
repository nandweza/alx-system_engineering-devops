<h1>0x0A. Configuration management</h1>
<br>
<hr>
<h2>Description</h2>
<p>This project is to introduce Server Configuration Management using Puppet.</p>
<br>
<h2><center>Table of Contents.</center><h2>
<table>
<tr>
<th>File</th>
<th>Description</th>
</tr>
<tr>
<td>0-create_a_file.pp</td>
<td>create a file in /tmp, using Puppet.
<ul>
<li>File path is /tmp/school</li>
<li>File permission is 0744</li>
<li>File owner is www-data</li>
<li>File group is www-data</li>
<li>File contains I love Puppet</li>
</ul>
</td>
</tr>
<tr>
<td>1-install_a_package.pp</td>
<td>install puppet-lint, using Puppet.
<ul>
<li>Install puppet-lint</li>
<li>Version must be 2.5.0</li>
</ul>
</td>
</tr>
<tr>
<td>2-execute_a_command.pp</td>
<td>Using Puppet, create a manifest that kills a process named killmenow.
<ul>
<li>Must use the exec Puppet resource</li>
<li>Must use pkill</li>
</ul>
</tr>
</table>