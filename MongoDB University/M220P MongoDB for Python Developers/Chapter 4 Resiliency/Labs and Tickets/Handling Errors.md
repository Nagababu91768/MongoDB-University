**Chapter 4: Resiliency**

# Ticket: Handling Errors
**Problem:**

**Task**

For this ticket, you'll be required to make the API more robust by handling exceptions. Specifically, what would happen should an incorrectly formatted _id be passed to get_movie in db.py?

To determine the exact exception that will be thrown in this case, please consult the documentation to see which exceptions pymongo and bson can raise:
```bash
pymongo exceptions
bson exceptions
```
Once you've determined the exception you need to handle, make sure to catch it in the get_movie method.

Although this ticket will only test that you've handled exceptions for the get_movie method, it's also a good idea to look over the entirety of **db.py** to look for other potential exceptions and handle them!

You can find examples of Error Handling in **notebooks/error_handling.ipynb.**

**Testing and Running the Application**

You can run the unit tests for this ticket by running:

```bash
pytest -m error_handling
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant unit tests, what is the validation code for Error Handling?

Attempts Remaining:Correct Answer

Enter answer here:

        5ae9b76a703c7c603202ef22
