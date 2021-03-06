**Chapter 2: User-Facing Backend**

# Ticket: Faceted Search
**Problem:**

**User Story**

"As a user, I want to be able to filter cast search results by one facet, metacritic rating."

**Task**

For this Ticket, you'll be required to implement one method in db.py, get_movies_faceted, so the MFlix application can perform faceted searches.

**MFlix Functionality**

Once the change is implemented for this ticket, the user interface will reflect this change when you search for cast (e.g. "Tom Hanks"), then additional search parameters will be added as shown below:

https://university-courses.s3.amazonaws.com/m220/facetedSearchScreenshot.png
**What is a Faceted Search?**

Faceted search is a way of narrowing down search results as search parameters are added. For example, let's say MFlix allows users to filter movies by a rating from 1 to 10, but Kate Winslet has only acted in movies that have a rating of 6 or higher.

If we didn't specify any other search parameters, MFlix would allow us to choose a rating between 1 and 10. But if we first search for Kate Winslet, the application would only let us choose a rating between 6 and 10, because none of the movie documents in the result set have a rating below 6.

If you're curious, you can read more about Faceted Search here.

**Faceted Search in MFlix**

Faceted searches on the MFlix site cannot be supported with the basic search method get_movies, because that method uses the Mongo query language. For faceted searches, the application must use the Aggregation Framework.

The method get_movies_faceted uses the Aggregation Framework, and the individual stages in the pipeline have already been completed. Follow instructions in the db.py file to append the required stages to the pipeline object.

**Testing and Running the Application**

Look in the test_facets.py file in your tests directory to view the unit tests for this ticket.

You can run the unit tests for this ticket by running:

```bash
pytest -m facets
```

Once the unit tests are passing, run the application with:

```bash
python run.py
```

Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Faceted Search?

Attempts Remaining:Correct Answer

Enter answer here:

        5aa7d3948adcc3fb770f06fb
