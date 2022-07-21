# Film distribution analysis

In this project, our task is to study the Russian film distribution market and identify current trends and analyze how films that received state support are of interest to the viewer


## Structure of the report:

1. Review of data and EDA
2. Data preprocessing
3. Building and checking hypothesis
4. Conclusion


## Columns:

The mkrf_movies table contains information from the rental license registry. One film can have several distribution certificates.

- title — the title of the movie;
- puNumber — rental certificate number;
- show_start_date — movie premiere date;
- type — movie type;
- film_studio — production studio;
- production_country — country of origin;
- director — director;
- producer — producer;
- age_restriction — age category;
- refundable_support — amount of state support refundable funds;
- nonrefundable_support — the amount of state support non-refundable funds;
- financing_source — source of government funding;
- budget — the total budget of the movie;
- ratings — movie rating on KinoPoisk;
- genres — the genre of the movie.


The mkrf_shows table contains information about movie screenings in Russian cinemas.

- puNumber — rental certificate number;
- box_office - fees in rubles


## Used libraries

- pandas
- numpy
- math
- sklearn
- plotly
- matplotlib
- seaborn
