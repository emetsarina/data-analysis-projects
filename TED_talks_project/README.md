# History of TED-talks

## Presentation in Tableau
Presentation: https://public.tableau.com/views/HistoryofTED-talks/HistoryofTED-talksbyyears?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Description
TED (an acronym for Technology, Education, Design) is a nonprofit organization that hosts widely known conferences where experts from various fields deliver talks on current social, cultural, and scientific topics.  
In this project, we explore the history of TED conferences using Tableau.

## Data Description
The files `tableau_project_data_1.csv`, `tableau_project_data_2.csv`, and `tableau_project_data_3.csv` contain data on TED talks. Each file has the following structure:  
- `talk_id`: Unique identifier for each talk  
- `url`: Link to the talk recording  
- `title`: Title of the talk  
- `description`: Brief description of the talk  
- `film_date`: Date the talk was recorded  
- `duration`: Duration of the talk in seconds  
- `views`: Number of views  
- `main_tag`: Main category of the talk  
- `speaker_id`: Unique identifier of the speaker  
- `laughter_count`: Number of times the audience laughed during the talk  
- `applause_count`: Number of times the audience applauded during the talk  
- `language`: Language of the talk  
- `event_id`: Unique identifier of the conference  

The file `tableau_project_event_dict.csv` provides a reference for the conferences. Table structure:  
- `conf_id`: Unique identifier of the conference  
- `event`: Name of the conference  
- `country`: Country where the conference was held  

The file `tableau_project_speakers_dict.csv` provides a reference for the speakers. Table structure:  
- `author_id`: Unique identifier of the speaker  
- `speaker_name`: Name of the speaker  
- `speaker_occupation`: Speaker's professional field  
- `speaker_description`: Description of the speaker's professional activity

## Tools
`Tableau`, `Product metrics`, `Building dashboards`



