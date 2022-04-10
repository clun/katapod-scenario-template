<div style="width:100%; padding: 40px 0 20px 20px; background-color: rgb(28, 131, 165); color: white;">

# Try It Out: Cassandra Query Language (CQL)

### <a style="color: white; text-decoration: none;" href="command:katapod.loadPage?step2">◂</a> Step 2 of 7 <a style="color: white; text-decoration: none;" href="command:katapod.loadPage?step4">▸</a>

</div>

# Describe Keyspaces

Now let's try to get the list of the keyspaces:

```
DESCRIBE KEYSPACES;
```

Here you can see all of keyspaces that have been created in the Cassandra cluster. Cassandra automatically creates keyspaces that have names starting with `system` and uses these as the data dictionary for the cluster.

*Awesome, you know how to see all your keyspaces!*

[continue](command:katapod.loadPage?step4){.orange_bar}
