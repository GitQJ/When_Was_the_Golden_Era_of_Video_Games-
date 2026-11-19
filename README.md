# When_Was_the_Golden_Era_of_Video_Games-
Used SQL to figure out the golden era of video games!

## Video Game Golden Era: Sales, Critic & User Score Analysis with SQL Joins | SQL, Data Analysis

Used SQL to look for a "golden era" of video games by combining sales data with critic and user review scores for the top 400 games released since 1977. I ranked the best sellers, the best-reviewed release years and the years when critics and users agreed.

# CONTEXT
Gaming is a multi-billion dollar industry, and publishers want to know whether games are getting better. The question was which release years both critics and players rated most highly, and how that links to sales.

# MY ROLE
I wrote and checked all three queries.

# WHAT I DID
• Best sellers: sorted the game sales table by copies sold and returned the top 10 (Top game sold was  2006 Wii Sports by Nintendo)
• Critic ratings by year: joined game sales to reviews on game name, grouped by release year and averaged critic scores, rounded to 2 decimals. Each represented year were counting at least 4 games.
• Golden years: joined the pre-computed yearly critic and user averages, kept years where either average was above 9, and calculated the critic minus user gap as a "diff" column
• Ordered results to make rankings and trends easy to read

# RESULTS
• Top-selling game: Wii Sports (Nintendo), 82.9 million copies
• Highest-rated year for critics: 1998 (9.32)
• Golden years: 1997, 1998, 2004, 2008, 2009; critics and users differed most in 2009 (gap 0.63)
• We could see that some golden years are not in the top 10 highest rated years (1997 and 2009 are not present)

# TECH STACK
SQL, joins (inner), aggregation (AVG, COUNT, GROUP BY), filtering, ordering, rounding
