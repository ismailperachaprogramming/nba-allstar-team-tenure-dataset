**NBA All-Star Team Tenure Outcomes (2016–2026)**

**Overview**

This dataset tracks NBA players who were selected as All-Stars between the 2016–17 and 2025–26 seasons and analyzes their team tenure outcomes.

Each row represents a continuous stint with a team during which the player was an All-Star.

The purpose of this dataset is to analyze:

Star player retention patterns

Post-peak tenure duration

Championship outcomes by acquisition type

Team dependency on elite players

**Kaggle Dataset Link:**
👉 https://www.kaggle.com/datasets/ismailperacha/nba-all-star-dependency-dataset-20162026

**Eligibility Rules**

A player-team stint is included if:

The player was selected as an NBA All-Star between 2016–2026.

The stint represents a continuous tenure during which the player was an All-Star.

Mid-season trades end a stint.

Previous or later non-All-Star stints are excluded.

Ongoing seasons use TBD for outcome-based fields.

This dataset does not track full career history — only qualifying All-Star stints.

**Definition of “Peak Season”**

Peak season is defined as:

The deepest playoff result achieved during the stint.

If multiple seasons reach the same playoff round, the best seed is used.

If still tied, the earliest occurrence is selected.

This season is stored in:

peak_season_with_team

**Columns**

Column	Description
player	Player full name
team	Team full name
first_all_star_season_with_team	First All-Star season during the stint
last_season_with_team	Final season of stint (NULL if active)
tenure_years_with_team	Total years in stint
acquisition_type	Draft, Trade, Free Agency, etc.
acquisition_year	Year player joined team
peak_season_with_team	Season of deepest playoff run
best_seed_with_team	Best regular season seed achieved
best_playoff_result_with_team	Deepest playoff outcome
championships_with_team	Number of championships during stint
best_accolade_with_team	Highest individual accolade during stint
total_all_star_count_with_team	Total All-Star selections during stint
left_team_flag	Yes/No
departure_season	Season player left
departure_reason	Trade, Free Agency, Retired, etc.
years_post_peak_to_exit	Years between peak season and departure

**Example Research Questions**

How long do teams retain All-Stars after peak success?

Are drafted stars retained longer than traded stars?

Do championship-winning stars leave sooner or stay longer?

Is post-peak retention correlated with acquisition type?

What is the average tenure length of All-Stars by team?


**Author**

Ismail Peracha
B.S. Computer Science — California State University, Fullerton
