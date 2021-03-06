**Chapter 1: Driver Setup**

# Ticket: Projection
**Problem:**

**User Story**

"As a user, I'd like to be able to search movies by country and see a list of movie titles. I should be able to specify a comma-separated list of countries to search multiple countries."

**Task**

Implement the **get_movies_by_country** method in db.py to search movies by country and use projection to return the title and _id field. The _id field will be returned by default.

You can find examples in notebooks/your_first_read.ipynb.

**MFlix Functionality**

Once you complete this ticket, the UI will allow movie searches by one or more countries.

**Testing and Running the Application**

Make sure to look at the tests in test_projection.py to understand what is expected.

You can run the unit tests for this ticket by running:

```bash
pytest -m projection
```

Once the unit tests are passing, run the application with:

```bash
python run.py
```

Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant unit tests, what is the validation code for Projection?

Enter answer here:

           5a94762f949291c47fa6474d
