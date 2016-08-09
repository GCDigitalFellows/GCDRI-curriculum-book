# Import data into table

1. Create a table with a field for each column in the csv file that we want to import

	```
	CREATE TABLE nypl_items (
		id INTEGER PRIMARY KEY,
		title VARCHAR,
		contributor VARCHAR,
		date VARCHAR,
		language VARCHAR,
		description VARCHAR,
		note VARCHAR,
		subject VARCHAR,
		resource VARCHAR,
		genre VARCHAR,
		publisher VARCHAR,
		place VARCHAR,
		url VARCHAR
	);
	```


2. Double click on the table "nypl_items" in the databases window and click on the import icon  

![Importing a csv file to a new table](images/csv_import.png)

3. Follow import instructions
