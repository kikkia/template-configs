# template-configs
A collection of some random config templates, cause I am too lazy to setup k8s rn

### chrontab the config every 5 mins or whatever
`*/5 * * * * cd ~/template-configs && git pull origin master`
Need ~80 machines doing this before hitting ratelimiting (~1k/hr) adjust as needed
