**Final Exam**

# Final: Question 6
**Problem:**

Suppose a client application is sending writes to a replica set with three nodes, but the primary node stops responding:

https://s3.amazonaws.com/edu-static.mongodb.com/lessons/M220/notebook_assets/replica_set_primary_down.png
Assume that none of the connection settings have been changed, and that the client is only sending insert statements with write concern w: 1 to the server.

After **30** seconds, the client still cannot connect to a new primary. Which of the following exceptions will be raised by **Pymongo?**

Attempts Remaining:Correct Answer

Choose the best answer:

- DuplicateKeyError
- **ServerSelectionTimeoutError**
- DocumentTooLarge
- ConfigurationError
- InvalidURI
