**Chapter 3: Admin Backend**

# Ticket: User Report
**Problem:**

**User Story**

"As an administrator, I want to be able to view the top 20 users by their number of comments."

**Task**

For this ticket, you'll be required to modify one method in db.py, most_active_commenters. This method produces a report of the 20 most frequent commenters on the MFlix site.

**Hint**

This report is meant to be run from the backend by a manager that is very particular about the accuracy of data. Ensure that the read concern used in this read, avoids any potential document rollback.
Remember to add the necessary changes in the pipeline to meet the requirements. More information can be found in the comments of the method.

You can find examples of Aggregation with the Python driver in **notebooks/basic_aggregation.ipynb.**

**MFlix Functionality**

Once this ticket is completed, users with database access can make users administrators. Administrators will be able to generate a user report listing top commenters.

**Testing and Running the Application**

You can run the unit tests for this ticket by running:

```bash
pytest -m user_report
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for User Report?

Attempts Remaining:Correct Answer

Enter answer here:

        5accad3272455e5db79e4dad
