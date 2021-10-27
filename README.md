# Plesk Blue Dark Theme
Alternative Theme for Plesk Server Admin GUI

## Usage / Installation
There are currently not many dark themes for Plesk. So we made it our hobby to create a new theme based on Plesk Obsidian 18.0.30. To activate the branding theme in Plesk, proceed as follows. Via SSH access from the server, define the topaLE theme via console (root) the custom theme and activate it as default theme (upload ZIP file to server). Download the **master.zip** and extract the zip file. Open the folder structure and merge the following folders and files as topa.zip or another name:
<br>
<pre>
<code>/css + /icons + /images + meta.xml</code>
</pre>
<br>
Reload the packed file via SSH (console):
<pre>
<code>/usr/local/psa/topa.zip</code>
</pre>

<br>
## Important: only the **3 folders** plus the **meta.xml** may be copied to the server as a packed archive (topa.zip)!
<br><br>
and execute the command mentioned below.
<br><br>
<pre>
<code>plesk bin branding_theme -i -vendor admin -source /usr/local/psa/topa.zip</code>
</pre>

## Location for custom themes in Plesk on Linux Systems:
<pre>
<code>/usr/local/psa/admin/htdocs/theme-skins/topa/</code>
</pre>
<br>
If you want to edit the custom.css again later, copy the existing .css in this path and overwrite the old file. Please keep the folder structure. Zip the individual folders to **topa.zip** (or any other name you like) and copy the ZIP archive into the folder on the server. The folders css, icons, images and the file meta.xml must be packed to a ZIP archive.
<br><br>
Have Fun ;-)
<br><br>
![Dark Blue Plesk Backend](https://raw.githubusercontent.com/topa-LE/plesk_blue_dark_theme/master/screenshots/plesk-backend-screen.jpg)
