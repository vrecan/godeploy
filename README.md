Basic install for perceptor using ansible

<h2>Deploy</h2>
<h3>Install goiostat:</h3>
<pre>
<code>
ansible-playbook site.yaml -i hosts  -t goiostat
</code>
</pre>
<h3>install perceptor:</h3>
<pre>
<code>
ansible-playbook site.yaml -i hosts  -t perceptor
</code>
</pre>
<h3>install system:</h3>
<pre>
<code>
ansible-playbook site.yaml -i hosts  -t system
</code>
</pre>
<h3>install everything:</h3>
<pre>
<code>
ansible-playbook site.yaml -i hosts
</code>
</pre>

<h2>Connect to consul web ui</h2>
`ssh -N -f -L 8500:localhost:8500 root@104.130.3.36`

Then just connect to http://localhost:8500/ui
