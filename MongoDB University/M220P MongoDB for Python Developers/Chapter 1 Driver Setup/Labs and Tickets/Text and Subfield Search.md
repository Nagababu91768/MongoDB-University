**Chapter 1: Driver Setup**

# Ticket: Text and Subfield Search
**Problem:**

**User Story**

"As a user, I'd like to be able to search movies by cast members, genre, or perform a text search of the plot summary, full plot, and title."

**Task**

For this ticket, you will need to modify the method **build_query_sort_project** in db.py to allow the following movie search criteria:

genres: finds movies that include any of the wanted genres.
Already, the **build_query_sort_project** method is able to return results for two different types of movie search criteria:

- text: performs a text search in the movies collection
- cast: finds movies that include any of the wanted cast
You just need to construct the query that queries the movies collection by the genres field.

**Hint**

Check the implementation of similar formats of search criteria - the genres query should be similar.
**MFlix Functionality**

Once you complete this ticket, the UI will allow movie searches by members of the cast, movie genres, movie title, and plot summary.

A text index was created for you when you restored the collections with mongorestore, so these queries will be performant once they are implemented.

**Testing and Running the Application**

Make sure to look at the tests in test_text_and_subfield_search.py to understand what is expected.

You can run the unit tests for this ticket with:

```bash
pytest -m text_and_subfield_search
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Text and Subfield Search?

Attempts Remaining:Correct Answer

Enter answer here:

                5a96a6a29c453a40d04922cc
