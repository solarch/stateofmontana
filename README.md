# stateofmontana
Sample Mule App for State of Montana RFP Response

- Read a file using the File connector (it can be easily changed to FTP or, SFTP by adding trust-stores, certs etc)
- Validates it (as mentioned, this is similar to JSR 303) using schema validation (taking data as JSON)
- Transforms (basic transformation as of now)
- Writes to a file (not using JPA for now, just using Files)
- Makes this data available (using postman or browsers) using HTTP by reading the data that was written earlier.

To run the project, - Before the project is run, copy the file "input-data.txt" into the folder "input" if it is empty. "input-data.txt" is present in the project folder.
