**Chapter 4: Resiliency**

# Ticket: Principle of Least Privilege
**Problem:**

**Task**

For this ticket, you'll be required to add a new user on your Atlas cluster for the MFlix application to connect with.

**The user should follow credentials:**
```bash
username: mflixAppUser
password: mflixAppPwd
````
This user should have the readWrite role on the sample_mflix database. Use Add Default Privileges to assign the user this specific role.

After you have created this user, modify the **SRV** connection string in your configuration file so the application connects with the new **username and password.**

**Testing and Running the Application**

There are no unit tests associated with this ticket.

Once you have modified the connection string, **stop and restart the application.**

Now proceed to the status page to run the full suite of integration tests and get your validation code.

What is the validation code for Principle of Least Privilege?

Attempts Remaining:Correct Answer

Enter answer here:

        5b61be29094dbae03bf30616