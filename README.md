# Setup

Run a simple python server in terminal from the source folder:

```
$ python -m SimpleHTTPServer 7777
```

Once the server is up, go to http://localhost:777 to run the demo.

# Functionality

1. Data table from API data.
2. Search filter
3. Rows displayed per page
4. Pagination
5. Sorting of individual columns
6. Ability to edit/save the data.

## Notes

The ability to edit/save exists until the local session persists. The changes are reverted on reload.To make the changes persist, we can add a save button to post all changes to an API or db.



