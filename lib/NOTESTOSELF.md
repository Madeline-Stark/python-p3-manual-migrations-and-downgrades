- ran 
```
pipenv install
pipenv shell
```

- Need to cd into lib folder

# For downgrading
- To downgrade migrations, we need to find the ID of the migration that we want to return to. 
- This would work even if we chose to return to the original empty base migration- but let's search for the original students table instead.
- Look for id of create_table_students
- `791279dd0760_create_table_students.py`