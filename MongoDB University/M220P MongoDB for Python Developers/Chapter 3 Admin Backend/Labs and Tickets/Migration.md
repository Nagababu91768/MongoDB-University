**Chapter 3: Admin Backend**

# Ticket: Migration
**Problem:**

**Task**

For this ticket, you'll be required to complete the command-line script located in the migrations directory of mflix called **movie_last_updated_migration.py.**

Things always change, and a requirement has come down that the lastupdated value in each document of the movies collection needs to be stored as an ISODate rather than a String.

Complete the script so it updates the values using the bulk API.

To perform the migration, run the script:

```bash
python movie_last_updated_migration.py
```
You can find examples of Bulk Operations in **notebooks/bulk_writes.ipynb.**

**Testing and Running the Application**

You can run the unit tests for this ticket by running:

```bash
pytest -m migration
```
Once the unit tests are passing, run the application with:

```bash
python run.py
```
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Migration?

Attempts Remaining:Correct Answer

Enter answer here:

        5ad9f6a64fec134d116fb06f
