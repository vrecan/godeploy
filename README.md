Basic install for perceptor using ansible
<h2>Deploy</h2>
<h3>Install iostat:</h3>
<pre>
<code>
ansible-playbook site.yaml -i hosts  -t goiostat
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
