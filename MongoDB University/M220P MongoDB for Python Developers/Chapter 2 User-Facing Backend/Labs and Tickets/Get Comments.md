**Chapter 2: User-Facing Backend**

# Ticket: Get Comments
**Problem:**

**User Story**

"As a user, I want to be able to view comments for a movie when I look at the movie detail page."

**Task**

For this ticket, you'll be required to extend the get_movie method in db.py so that it also fetches the comments for a given movie.

The comments should be returned in order from most recent to least recent using the date key.

Movie comments are stored in the comments collection, so this task can be accomplished by performing a $lookup. Refer to the Aggregation Quick Reference for the specific syntax.

You can find examples of Aggregation with the Python driver in notebooks/basic_aggregation.ipynb.

**MFlix Functionality**

Once this ticket is completed, each movie's comments will be displayed on that movie's detail page.

**Testing and Running the Application**

You can run the unit tests for this ticket by running:

```bash
pytest -m get_comments
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Get Comments?

**Hint: We need to sort the comments in the $lookup stage.**

Attempts Remaining:Correct Answer

Enter answer here:

      5ab5094fb526e43b570e4633
