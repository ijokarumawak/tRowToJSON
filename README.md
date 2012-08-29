tRowToJSON
============
tRowToJSON is a Talend component which create a JSON document using column values within a row. You can keep column values as well as adding the JSON output column.

How To Use it
==============

Basic Settings
---------------

- ***JSON column***: Specify the output JSON column.
- ***Schema***: Specify the output schema. It can relay input columns by adding the same column name with the same type.
- ***JSON fields***: 
  - Input column: Specify input column names to put into the output JSON document.
  - JSON field (optional): Specify a target JSON field if you want to map an input column as a different name. Wrap the field name with quote, like **"outputField"**. When it is blank, the target JSON field will be the same name as the input column.