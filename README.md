<h1>GenesisL1 blockchain</h1>
Cosmos SDK sdk v0.46.15</br>
<i>Source code fork of cronos and ethermint</i>

<strong>Node requirements:</strong>

<li>300GB+ good hard drive disk</li> 
<li>8GB+ RAM (if necessary it will be swapped to 150GB from hard drive)</li>
<li>4 CPU Threads</li>
<li>Good Internet Connection</li>

<strong>Node init/upgrade time is 30-60min or a few tea cups</strong>

<li><i>Initialization (which will generate a new key):</i></br>
<code>sh genesisd.sh init $YOUR_NEW_NODE_NAME</code></li>

<li><i>Upgrading (for if you already have an existing .genesisd folder and configuration):</i></br>  
<code>sh genesisd.sh upgrade</code></li>

<li><i>Upgrading (for if you already have an existing .genesisd folder and configuration, but want a different node name):</i></br>
<code>sh genesisd.sh upgrade $YOUR_NEW_NODE_NAME</code></li>
