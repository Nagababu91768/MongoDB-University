**Chapter 2: User-Facing Backend**

# Ticket: User Management
**Problem:**

**User Story**

"As a user, I should be able to register for an account, log in, and logout."

**Task**

For this Ticket, you'll be required to implement all the methods in db.py that are called by the API endpoints in user.py. Specifically, you'll implement:

```bash
get_user
add_user
login_user
logout_user
get_user_session
delete_user
```
For this ticket, you will need to use the find_one(), update_one() and delete_one() methods. You can find examples in the following notebooks:

```bash
notebooks/deletes.ipynb
notebooks/your_first_write.ipynb
```
**MFlix Functionality**

Once this ticket is completed, users will be able to register for a new account, log in, logout, and delete their account.

Registering should create an account and log the user in, ensuring an entry is made in the sessions collection. There is a unique index on the user_id field in sessions, so we can efficiently query on this field.

**Testing and Running the Application**

Look within the test_user_management.py file in your tests directory to view the unit tests for this ticket.

You can run the unit tests for this ticket by running:

```bash
pytest -m user_management
```

Once the unit tests are passing, run the application with:

```bash
python run.py
```

Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for User Management?

Attempts Remaining:Correct Answer

Enter answer here:

        5a8d8ee2f9588ca2701894be
