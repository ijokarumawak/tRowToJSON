tRowToJSON
============
tRowToJSON is a Talend component which create a JSON document using column values within a row. You can keep column values as well as adding the JSON output column.

How To Use it
==============

Basic Settings
---------------

- ***JSON column***: Specify the output JSON column.

- ***Schema***: Specify the output schema. It can relay input columns by adding the same column name with the same type.

- ***Use all columns***: Check if you want to export all columns into JSON. This configuration would be useful when you have a lot of columns to write into JSON. However you can only map column values into the same name JSON field.

- ***Exclude columns***: Only available when ***Use all columns*** is checked. You can exclude some columns from output JSON.

- ***JSON fields***: 
  - Input column: Specify input column names to put into the output JSON document.
  - JSON field (optional): Specify a target JSON field if you want to map an input column as a different name. Wrap the field name with quote, like **"outputField"**. When it is blank, the target JSON field will be the same name as the input column.


Release note
==============

0.2
-----
Add ***Use all column*** and ***Exclude columns*** so that you can map a lot of columns easily.

0.1
-----
Initial release.