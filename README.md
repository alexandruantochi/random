# random


### oci_connect_class

```
include('path/to/oci_connect_class.php');
$conn = OracleDatabase::getConnection(); // returns a new connection or the same one if already opened
$query=oci_parse($conn, 'SELECT * FROM dual'); 
oci_execute($query);
```

```OracleDatabase::closeConnection(); // close the connection```
