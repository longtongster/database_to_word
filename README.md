# database_to_word

When working with policies and standard one might one to centralize all requirements in one database. Potentially you have different user groups that might do not want to read the policies but just one a summary of all requirements that apply to them. This is a toy project to investigate and work towards a code base that might be used for this. 

The high level workflow is as follows:
- Read the data from an xlsx file
- store the data in a sqlite database
- read data from the database
- depending on the life_cycle_phase filter the rows with requirements from the database
- per phase create a table in word with the requirements

## ToDo
- make a requirements.txt or an environment.yml
- so for no success in setting the column width.
