<h1>Kali_log_and_monitoring</h1>
<br></br>
<h3>Steps to start:</h3>
<ul>
  <li>sudo apt install sysstat ifstat</li>
  <li>nano kali_monitor.sh</li>
  <li>add the code and make any changes if needed</li>
  <li>save the filr</li>
  <li>chmod +x kali_monitor.sh</li>
  <li>./kali_monitor.sh</li>
</ul>
<br>
<h4>Schedule a cron task for weekly or daily loggin</h4>
<h3>Steps to start:</h3>
<ul>
  <li>crontab -e</li>
  <li>0 * * * * /path/to/your_script.sh >> /var/log/system_monitor.log</li> (this is to run hourly)
</ul>
<br>

![Screenshot_2024-11-21_17-08-37](https://github.com/user-attachments/assets/797ab818-944a-47d4-8e26-3b9b0e9fd3be)


