**Suggested Steps:**

1. Download and install [TortoiseSVN](http://tortoisesvn.tigris.org/)

2. Create a directory `IQToolkit` for source code

3. Check out source to the directory:
```
http://iqtoolkit-oracle.googlecode.com/svn/trunk/iqtoolkit-oracle-read-only
```

finally, your directories look like:
```
IQToolkit (created in step 2)
 |-key.snk (generated by yourself)
 |-IQToolkit
 |-IQToolkit.Data
 |-IQToolkit.Data.OracleClient
 |-IQToolkit.Data.SqlClient
 |-Support
 |-Test
 |-IQToolkit.Oracle.sln
```

4. Open and build `IQToolkit.Oracle.sln` with VS2008 SP1

5. Edit connection string in app.config of Testing project to meet your environment (optional)

6. Run Test project (optional)