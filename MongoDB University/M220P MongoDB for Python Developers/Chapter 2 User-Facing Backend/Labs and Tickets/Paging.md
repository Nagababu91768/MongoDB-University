**Chapter 2: User-Facing Backend**

# Ticket: Paging
**Problem:**

**User Story**

"As a user, I'd like to get the next page of results for my query by scrolling down in the main window of the application."

**Task**

Modify the method get_movies in db.py to allow for paging. You can see how the page is parsed and sent in the api_search_movies method from movies.py.

You can find examples of using cursor methods in notebooks/cursor_methods_agg_equivalents.ipynb.

**MFlix Functionality**

The UI is already asking for infinite scroll! You may have noticed a message stating "paging not implemented" when scrolling to the bottom of the page.

Once this ticket is completed, this message will go away, and scrolling to the bottom of the page will result in a new page of movies.

**Testing and Running the Application**

Make sure you look at the tests in test_paging.py to look at what is expected.

You can run the unit tests for this ticket by running:

```bash
pytest -m paging
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```

Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Paging?

Attempts Remaining:Correct Answer

Enter answer here:

          5a9824d057adff467fb1f526
