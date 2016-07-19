# stateofmontana
Sample Mule App for State of Montana RFP Response

- Read a file using FTP (it can be easily changed to SFTP by adding trust-stores, certs etc)
- Validates it (as mentioned, this is similar to JSR 303) using schema validation (taking data as JSON)
- Transforms (basic transformation as of now)
- Writes to a file (not using JPA for now, just using Files)
- Makes this data available (using postman or browsers) using HTTP by reading the data that was written earlier.

To run the project, if you are running on a Windows machine, no changes are needed.  If on a Mac, you will need to update the outputPath and readFile paths.
