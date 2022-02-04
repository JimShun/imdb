## import IMDB Database using imdbpy –
file: PostgreSQL.yml


## name.basics.tsv.gz –
Contains the following information for names:

<strong>nconst</strong> (string) - alphanumeric unique identifier of the name/person<br>
<strong>primaryName</strong> (string)– name by which the person is most often credited<br>
<strong>birthYear</strong> – in YYYY format<br>
<strong>deathYear</strong> – in YYYY format if applicable, else '\N'<br>
<strong>primaryProfession</strong> (array of strings)– the top-3 professions of the person<br>
<strong>knownForTitles</strong> (array of tconsts) – titles the person is known for

## Top 3 of primary professions as producer and still alive  –

(primaryProfesison = producer)
(deathYear is None)
file: Q6.py
