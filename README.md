# cloud-server-engine
A file server implemented as Java servlet. In response to HTTP POST and GET requests returns directory listings, file data, etc. as JSON.<br>   
Supports the following commands:<br>
<strong>list_contents</strong> returns the contents of a directory<br>
<strong>list_dirs</strong> returns the sub-directories in a directory<br>
<strong>list_files</strong> returns the files in a directory<br>
<strong>file_info</strong> returns information about a particular file<br>
<strong>ping</strong>  tests if there is connection and keeps the session alive<br>
<strong>download</strong>  initiates a file download<br>
<strong>upload</strong>  initiates a file upload<br>
<strong>recycle_file</strong>  moves a file to the bin<br>
<strong>recycle_dir</strong> moves a directory to the bin<br>
<strong>login</strong> user log in<br>
<strong>logout</strong> user log out<br>
<strong>change_pass</strong> changes the password of a user<br>
<strong>user_info returns</strong> detailed information regarding user's profile<br>
<strong>server_info</strong> returns detailed information regarding the server<br>
<strong>settings_get</strong>  returns the value of a server setting<br>
<strong>settings_set</strong>  changes the value of a server setting<br>
<strong>list_settings</strong> returns all server settings<br>
<strong>list_users</strong>  returns a list of all users<br>