# random


### oci_connect_class

```$conn = OracleDatabase::getConnection(); // returns a new connection or the same one if already opened```
```$query=oci_parse($conn, 'SELECT * FROM dual');```
```oci_execute($query);```

```OracleDatabase::closeConnection(); // close the connection```
