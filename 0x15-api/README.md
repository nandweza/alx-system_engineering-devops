<h1>0x15. API</h1>
<br>
<h2>Background Context</h2>
<br>
<p>Old-school system administrators usually only know Bash and that is what they use to build their scripts. While Bash is perfectly fine for a lot of things, it can quickly get messy and not efficient compared to other programming languages. The new generation of system administrators, usually called SREs, are pretty much regular software engineers but instead of building products, they are managing systems. And one of the big differences with their predecessors is that they know more than just Bash scripting.</p>
<p>One popular way to expose an application and dataset is to use an API. Often, they are the public facing part of websites and micro-services so that allow outsiders to interact with them – access and modify their data. In this project, you will access employee data via an API to organize and export them to different data structures.</p>
<p>This is a perfect example of a task that is not suited for Bash scripting, so let’s build Python scripts.</p>
<br>
<h2><center>Table of contents.</center></h2>
<br>
<table>
<tr>
<th>File</th>
<th>Description</th>
</tr>
<tr>
<td>0-gather_data_from_an_API.py</td>
<td>Gather data from an API</td>
</tr>
<tr>
<td>1-export_to_CSV.py</td>
<td>Using "0-gather_data_from_an_API.py", extends Python script to export data in the CSV format.</td>
</tr>
<tr>
<td>2-export_to_JSON.py</td
<td>Using "0-gather_data_from_an_API.py", extends Python script to export data in the JSON format(Export to JSON)</td>
</tr>
<tr>
<td>3-dictionary_of_list_of_dictionaries.py</td>
<td>Using "0-gather_data_from_an_API.py", extends Python script to export data in the JSON format( Dictionary of list of dictionaries)</td>
</tr>
</table>
