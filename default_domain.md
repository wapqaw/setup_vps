#change default domain on ip vestacp.
<ol>
  <li>nano /etc/httpd/conf.d/vesta.conf</li>
<li>change order first config of domain.</li>
  <li>systemctl restart httpd</li>
  </ol>



#vps can't access after reboot
The firewall has been disabled. 
If you restart the server it will come back on.
Changed ports in Vesta.
