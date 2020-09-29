# Plesk Blue Dark Theme
Alternative Theme for Plesk Server Admin GUI

<h2>Usage / Installation</h2>
There are currently not many dark themes for Plesk. So we made it our hobby to create a new theme based on Plesk Obsidian 18.0.30. To activate the branding theme in Plesk, proceed as follows. Via SSH access from the server, define the topaLE theme via console (root) the custom theme and activate it as default theme (upload ZIP file to server):
<br><br>
<pre>
<code>plesk bin branding_theme -i -vendor admin -source /usr/local/psa/topa.zip</code>
</pre>

<h2>Location for custom themes in Plesk on Linux Systems: ()</h2>
<pre>
<code>/usr/local/psa/admin/htdocs/theme-skins/topa/</code>
</pre>
<br>
Please keep the folder structure. Zip the individual folders to topa.zip (or any other name you like) and copy the ZIP archive into the folder on the server.
<br>
Have Fun ;-)
