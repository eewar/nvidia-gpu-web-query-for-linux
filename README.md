# NVIDIA GPU web query for Linux
Query and return all Nvidia GPU value over the web. Very useful if you are a crypto miner. It will return all deep detail for you to monitor. You don't have to log in to a terminal to get it anymore.

It can also return as a JSON format. Which you can integrate to your rig management system.


# Requirement
- Linux OS
- Apache + PHP (cound be any version)
- Nvidia Driver


# Installation
- Just put the "nvidia-query.php" in "/var/www/html"


# How to use
- Edit "nvidia-query.php" with your favorite text editor
- Comment/Uncomment the value that you want/unwant
- Open web browser and goto "http://{ip_address}/nvidia-query.php"
- In case that you have a rig management system. You might love to get the value in JSON format. Which you just simply use "http://{ip_address}/nvidia-query.php?json"


# Query code and explanation
- You can easily read in our Wiki. We exported from command "nvidia-smi --help-query-gpu" (untouched).
- Each Nvidia version may different better check your Nvidia version first.
- To check Nvidia version just run "nvidia-smi".
