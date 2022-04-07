<div style="width:100%; padding: 40px 0 20px 20px; background-color: rgb(28, 131, 165); color: white;">

# Try It Out: Cassandra Query Language (CQL)

### Step 1 of 7 <a style="color: white; text-decoration: none;" href="command:katapod.loadPage?%5B%7B%22step%22%3A%22step3%22%7D%5D">▸</a>

</div>

# Connect

First things first, we have to connect to the database. For that we will use a console client called `cqlsh` (Cassandra Query Language Shell). For the locally installed Cassandra with default settings we can connect as simple as that:

<a style="cursor: pointer;text-decoration: none;" href="command:katapod.sendText?%5B%7B%22command%22%3A%22cqlsh%22%7D%5D">
<pre><code>cqlsh
</code></pre></a>

# Create a keyspace

Let's first start learning CQL by creating a keyspace, using the `CREATE KEYSPACE` command.


<a style="cursor: pointer;text-decoration: none;" href="command:katapod.sendText?%5B%7B%22command%22%3A%22CREATE%20KEYSPACE%20demo%20WITH%20replication%20%3D%20%7B'class'%3A%20'SimpleStrategy'%2C%20'replication_factor'%3A%201%7D%3B%22%7D%5D">
<pre><code>CREATE KEYSPACE demo WITH replication = {'class': 'SimpleStrategy', 'replication_factor': 1};
</code></pre></a>

A keyspace is a way to logically group a collection of database objects together, such as:

* tables
* user-defined types
* user-defined functions
* and more!

<hr />
<b>ProTip:</b> You can use the `Tab` key in `cqlsh` to auto-complete or suggest the next part of your command, as you type.
<hr />

This is similar concept to the database or namespace used in relational databases.

In addition, the keyspace also controls the replication behavior for all of the data stored in the keyspace.

*Great, you now know how to create a keyspace in Apache Cassandra!*

<a style="display: block;cursor: pointer;text-decoration: none; color: white; background-color: rgb(253, 119, 0); vertical-align: middle; text-align: middle; padding: 20px; width: 100%;" href="command:katapod.loadPage?%5B%7B%22step%22%3A%22step3%22%7D%5D">CONTINUE</a> 