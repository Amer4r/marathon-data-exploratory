# marathon-data-exploratory

## Ultra-Marathon Race Records Dataset
### Overview
This dataset contains a large collection of ultra-marathon race records registered between 1798 and 2022, spanning well over two centuries. The data includes 7,461,226 race records from 1,641,168 unique athletes. The original data, obtained from public websites, has been anonymized to comply with data protection laws and preserve athlete privacy. Each athlete is represented by a numerical Athlete ID instead of their name.

#### Columns
- Year of event (int64): The year in which the event took place.
- Event dates (object): Dates of the event.
- Event name (object): Name of the event, including country location information.
- Event distance/length (object): Describes the type of race, including popular distances (e.g., 50km, 100km) and lengths (e.g., 6h, 12h).
- Event number of finishers (int64): Number of athletes who finished the event.
- Athlete performance (object): Performance of the athlete in the race.
- Athlete club (object): Club affiliation of the athlete.
- Athlete country (object): Country of the athlete.
- Athlete year of birth (float64): Year of birth of the athlete.
- Athlete gender (object): Gender of the athlete.
- Athlete age category (object): Age category of the athlete.
- Athlete average speed (object): Average speed of the athlete during the race.
- Athlete ID (int64): Unique numerical ID representing each athlete.

#### Questions to Explore
- Difference in speed for the 50km,50min male to female?

    - Analyze the speed difference between male and female athletes in the 50km race, focusing on performances within 50 minutes.
- What age groups are best in the 50km race (20+ races minimum)?

    - Identify age groups that consistently perform well in the 50km race, considering athletes with a minimum of 20 races.
- What age groups are the worst in the 50km race (20+ races minimum)?

    - Determine age groups with lower performance levels in the 50km race, based on athletes with at least 20 races.
- Which season has less performance? summer or winter?
    - Investigate whether athlete performance is slower in summer compared to winter races, based on seasonal trends observed in the data.

These questions will provide valuable insights into the performance patterns, age-related trends, and seasonal variations within the ultra-marathon race records dataset.
#### Additional Information
The Event name column includes country location information that can be derived to a new column.
Seasonal information can be found in the Event dates column beyond the Year of event.
The dataset covers various ultra-marathon race distances and lengths, including 50km, 100km, 50mi, 100mi, as well as lengths such as 6h, 12h, 24h, 48h, 72h, 6d, and 10d.
Information on age, gender, and speed (in km/h) is provided in separate columns.
#### Purpose
This dataset serves as a valuable resource for analyzing trends and patterns in ultra-marathon races over a long period. Researchers, athletes, and enthusiasts can explore factors influencing athlete performance, participation trends, and the evolution of ultra-running events.

#### Dataset Source
The original dataset was compiled from public websites, and the anonymized version is made available for research and analysis purposes.
