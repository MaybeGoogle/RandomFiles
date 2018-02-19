How ~~to~~ **do I** start mining on this pool?  

***  

*Rewritten `How do I start mining on this pool?`:*

What you need:  
- A Monero payment address  
- A miner  
  - You can find basic instructions in "Setup Miner" after you enter your payment address [here](https://moneroocean.stream/#/dashboard).  
  - You can also mine right in your browser. Just press "Web Mining".  
  - Another option is to download a miner. Some examples:  
    - CPU: xmrig, xmr-stak  
    - AMD GPU: xmr-stak, wolf-xmr-miner  
    - nVidia GPU: xmrig-nvidia, xmr-stak, ccminer-cryptonight  

If you are using a downloaded miner, be sure to specify the following:  
  - Pool: Format it as `gulf.moneroocean.stream:#####`, with `#####` being the port number. The list of ports can be found at [the ports page](https://moneroocean.stream/#/ports).  
  - Username: Use your payment address.  
  - Password: Format it as `Worker_name:Some_password`. To receive email notifications about worker downtimes, set the password as your email. Please note that the first string you use after the `:` in your miner password will be your initial password on the website. This password will be used to access further options on the online dashboard.  

***  

I recommend ~~to use~~ **using** `gulf.moneroocean.stream` ~~address~~ for all cases because ~~first~~ **1)** it will direct you to the closest server with the lowest latency (the most important thing to consider) and ~~second~~ **2)** it will automatically redirect your miner to **an**other server if the nearest one ~~will became~~ **goes** down for some reason. Using specific gateway nodes like `de.moneroocean.stream`, `us.moneroocean.stream` and `jp.moneroocean.stream` make sense only in very~~, very~~ specific cases that ~~very~~ likely do not apply to you ~~if you do not aware about them~~.

***  

Does joining a server near to my location **or a server that has more miners** give me more shares ~~, or a server that has more miners~~?

***  

*Rewritten `How I can uninstall miner installed using moneroocean CPU miner setup scripts?`*:  

If you no longer want to mine using miner that was installed using setup script you can disable it using these directions:  
- Windows: Remove `moneroocean_miner.bat` from the  `%USERPROFILE%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup` or `%USERPROFILE%\Start Menu\Programs\Startup` directory if you installed miner under non admin mode. Otherwise, run `sc delete moneroocean_miner` command in admin command prompt.  
- Linux: remove call to `moneroocean/miner.sh script` in the bottom of your `$HOME/.profile` file or run `sudo systemctl stop moneroocean_miner.service` if setup script was executed with password-less sudo.

***  

Why **does** my hashrate on ~~website~~ **the dashboard** ~~look like waves~~ fluctuate?

***

Why **is the** web miner on the web site is not working (shows 0 hashrate)?

Try to use your browser**'s** incognito mode ~~first~~ or some other browser. If it still does not work please try to ~~go to~~ use https://webminerpool.com ~~site,~~. Put your wallet address and select moneroocean.stream **as your** mining pool. If ~~it helps~~ this works, please write to support@moneroocean.stream ~~email and~~ **to** let ~~pool operator~~ us know about ~~this~~ **the** issue.

***

**For private matters,** please write ~~me~~ **an** email to support@moneroocean.stream**.** ~~address for private matters or~~ Contact me via **Twitter** ([@MoneroOcean](https://twitter.com/MoneroOcean)) ~~twitter~~ for public matters.
