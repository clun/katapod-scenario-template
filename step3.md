<div style="width:100%; padding: 40px 0 20px 20px; background-color: rgb(28, 131, 165); color: white;">

# Try It Out: Cassandra Query Language (CQL)

### <a style="color: white; text-decoration: none;" href="command:katapod.loadPage?%5B%7B%22step%22%3A%22step2%22%7D%5D">◂</a> Step 2 of 7 <a style="color: white; text-decoration: none;" href="command:katapod.loadPage?%5B%7B%22step%22%3A%22step4%22%7D%5D">▸</a>

</div>

# Describe Keyspaces

Now let's try to get the list of the keyspaces:

<a style="cursor: pointer;text-decoration: none;" href="command:katapod.sendText?%5B%7B%22command%22%3A%22describe%20keyspaces%3B%22%7D%5D">
<pre><code>DESCRIBE KEYSPACES;
</code></pre></a>

Here you can see all of keyspaces that have been created in the Cassandra cluster. Cassandra automatically creates keyspaces that have names starting with `system` and uses these as the data dictionary for the cluster.

*Awesome, you know how to see all your keyspaces!*

<a style="display: block;cursor: pointer;text-decoration: none; color: white; background-color: rgb(253, 119, 0); vertical-align: middle; text-align: middle; padding: 20px; width: 100%;" href="command:katapod.loadPage?%5B%7B%22step%22%3A%22step4%22%7D%5D">CONTINUE</a> 