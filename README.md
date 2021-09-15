# Backend - Database Basics - Show Me

You are planning to build an app where users can add poems anonymously. You want to have _some_ data regarding the poem, but nothing that can be used to identify the user. Before even starting, try to think about the data you will be handling. You (as an administrator) are allowed to edit the poems.

You could take some inspiration from here; https://www.poetryfoundation.org/poems/152825/

- What data to save? 
    - Title, body (as short text), (and date if space is not an issue)
- Which types of fields would you have? Do you need dates? 
    - Tittle and body (input text and textarea), no need to input the date as it could be created in the back end if need be.
- Estimate how much data will you allow to be saved 
    - Up to 60 chars for title and up to 2000 chars (very long poem) for the body.
- Describe the data in whatever way you find best
- Show how you would create the table(s) for your data
    - CREATE TABLE <name> (<title> <varchar>(50),<body> <varchar>(2000),<date> <varchar>(16),<published> <bool>);
- Add Value:
    - INSERT INTO <name> VALUES('Poem title', 'Poem body', '16-08-2021', 'False');