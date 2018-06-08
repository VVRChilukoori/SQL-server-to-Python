<p><strong>&nbsp;</strong><strong>Environmental Setup for SQL Server 2014:</strong></p>
<ul>
<li>First, download the <a href="https://www.microsoft.com/en-us/download/details.aspx?id=21">Microsoft .NET Framework 3.5</a> and install it. You man need to restart the system after installing it.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/1.jpg" alt="" width="776" height="489" /></p>

<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/2.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Then download the <a href="https://www.microsoft.com/en-us/download/details.aspx?id=42299">Microsoft&reg; SQL Server&reg; 2014 Express</a></li>
<li>Check whether your system meet all your requirements or install the missing requirements/software&rsquo;s.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/3.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>For this project I am using a 64-bit machine. So, I have selected a 64-bit software/file for installation.</li>
<li>After downloading the file. Extract the files (Choose directory where to extract the files).</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/4.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Once it is extracted. The installation process starts directly. Then select the <strong>Planning</strong> option, then select the <strong>System Configuration Checker</strong> and run it, to check the configuration and it meets all the requirements. A new window opens and closes by itself if system meets all the requirements.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/5.jpg" alt="" width="776" height="489" /></p>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/6.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Then move on to the <strong>Installation</strong></li>
<li>Under installation options select <strong>New SQL Server stand-alone installation or add features to an existing installation</strong>.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/7.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Select the license terms. Then click on <strong>Next</strong>.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/8.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li><strong>Optional service</strong> select option <strong>Use Microsoft Update to check for updates (recommended)</strong></li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/9.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Select all the features that you need. Make changes to the directories according to your requirement. For this one I am using the default directories. Click on <strong>Next</strong>.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/10.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Select the named instance option (default name). For this installation, I am using the name <strong>SQLExpress</strong>. You can give any name as you want. But we careful about spacing. I would not recommend giving spacing for the instances. Note down the instance name you gave as you will be using that to connect to the instance thru SSMS later. Click on <strong>Next</strong>.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/11.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Click on <strong>Next</strong> for Server Configuration. Nothing need to be changed in it.</li>
<li>Under Database Engine Configuration under Server Configuration tab select the <strong>Authentication Mode</strong>. For this select the default <strong>Windows authentication mode</strong>.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/12.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Then go to <strong>FILESTREAM</strong> tab, select all the options and then click on <strong>Next</strong>.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/13.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Installation starts and after the installation is complete. Check whether all the features are installed properly or not. Then <strong>Close</strong> the window.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/14.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Then launch the <strong>SSMS</strong> from windows start menu and run with <strong>Administrative privileges.</strong></li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/15.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Select the <strong>Server type </strong>as<strong> Database engine</strong>, <strong>Server name </strong>that you gave while install the SQL server (server name (or computer name) \ instance name), <strong>Authentication</strong>. Then click on connect.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/16.jpg" alt="" width="776" height="489" /></p>
</ul>

<li>After connecting to the instance on expanding the database connection, you can see some default system databases as shown below. We will use master database for our project.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/17.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>On expanding further and running a query you can find the table values as shown below.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/18.jpg" alt="" width="776" height="489" /></p>
</ul>

<ul>
<li>Our project is to connect to the SQL Server database and retrieve data/table from a particular table and storing it in a .csv format file and we are connecting to a local SQL server database.</li>
<li>I hope all of you guys have installed the <strong><a href="https://www.anaconda.com/download/">Anaconda distribution</a></strong>. In case it is not setup, I request you to download and set it up. I will be using <strong>Jupyter Notebook</strong> in <strong>Anaconda distribution</strong>. You can also install only <strong><a href="http://jupyter.org/install">Jupyter Notebook</a></strong> if you want.</li>
<li>Launch the <strong>Jupyter Notebook</strong> and open a new python <strong>Jupyter notebook</strong> as shown in the figure below.</li>
</ul>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/19.jpg" alt="" width="776" height="489" /></p>
</ul>

<li>Below is the final output of the values.</li>
</ul>
<p>In Python (thru Jupyter Notebook) what I did is connected to my local SQL Server database instance <strong>SQLExpress</strong>, later ran SQL query to get a table from the system database <strong>master </strong>and then stored the table into a <strong>SQL_data.csv</strong> file. Later opened the <strong>SQL_data.csv</strong> file using python and displayed the table.</p>

<ul>
<p align="left"><img src="https://github.com/VVRChilukoori/SQL-server-to-Python/blob/master/img/20.jpg" alt="" width="776" height="489" /></p>
</ul>

<p><strong>Python (in Jupyter Notebook) Code</strong></p>
<ul>
<li>Python code for installing the library <strong>pyodbc</strong> to connect to the server (Installing it from Jupyter Notebook).</li>
</ul>
<p><span style="background-color: #999999;"><strong><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp;</span> &nbsp; &nbsp;!</strong>pip install pyodbc</span></p>
<ul>
<li>Importing <strong>pyodbc</strong> and other libraries into python</li>
</ul>
<p><span style="background-color: #999999;"><strong><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp;</span> &nbsp; &nbsp;import </strong>pyodbc <strong>as </strong>connector</span></p>
<p><span style="background-color: #999999;"><strong><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp;</span> &nbsp; &nbsp;import </strong>pandas <strong>as </strong>pd</span></p>
<p><span style="background-color: #999999;"><strong><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp;</span> &nbsp; &nbsp;import </strong>csv</span></p>
<ul>
<li>Below is the python code for how to connect to SQL Server.</li>
</ul>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; driver <strong>= </strong>connector.connect("Driver={SQL Server Native Client 11.0};"</span></p>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "Server=&lt;Server-name&gt;\&lt;Instance-name&gt;;"</span></p>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "Database=&lt;Database-Name&gt;;"</span></p>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "Trusted_Connection=yes;")</span></p>
<ul>
<li>Writing an SQL query to get data from the database into python</li>
</ul>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; table <strong>= </strong>pd.read_sql_query('&lt;SQL Query&gt;', driver)</span></p>
<ul>
<li>To print table.</li>
</ul>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; &nbsp;print (table)</span></p>
<ul>
<li>Storing the table to a .csv format file.</li>
</ul>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp; </span>&nbsp; &nbsp;dfCSV <strong>=</strong>table.to_csv('&lt;Filename&gt;.csv',index <strong>= </strong><strong>False</strong>)</span></p>
<ul>
<li>Reading the saved &lt;Filename&gt;.csv file in python.</li>
</ul>
<p><span style="background-color: #999999;"><span style="background-color: #ffffff;">&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;</span>&nbsp; &nbsp;pd.read_csv('&lt;Filename&gt;.csv')</span></p>
