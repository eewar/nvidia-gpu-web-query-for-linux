# linux-nvidia-gpu-web-query
Get all nvidia gpu data over the web for monitor miner


# Requirement
Linux OS
Apache + PHP (cound be any version)
Nvidia Driver


# Installation
Just put the "nvidia-query.php" in "/var/www/html"


# How to use
Edit "nvidia-query.php" with your favorite text editor
Comment/Uncomment the value that you want/unwant
Open web broswer and goto "http://{ip_address}/nvidia-query.php"
In case that you have a rig management system. You might love to get the value in JSON format. Which you just simply use "http://{ip_address}/nvidia-query.php?json"


# Query code and explanation
You can easily read in our Wiki. We exported from command "nvidia-smi --help-query-gpu" (untouched). Each Nvidia version may different better check your Nvidia version first. To check Nvidia version just run "nvidia-smi".


# Our system
- Ubuntu Server 16.04 LTS with Apache2, PHP7.0, Nvidia 410.48
- Ubuntu Server 18.04 LTS with Apache2, PHP7.0, Nvidia 410.48
- We've maximum 12 GPUs in one rig

# Note
- The more GPU you have the more time it take to return the result (CPU, Ram, SSD not related)
