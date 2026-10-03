# spotify-track-popularity-powerbi
Power BI dashboard analyzing 7,900+ Spotify tracks to find what drives track popularity: artist popularity, album type, track length and genre.

## Spotify Track Popularity Analysis (Power BI)

This project analyzes 7,920 Spotify tracks by 2,548 artists, released between 1952 and 2025, to understand what drives a track's popularity score. The data was cleaned and transformed in Power Query, modeled in Power BI with DAX measures, and presented in a 3-page interactive dashboard.

## Business Questions
1. Does artist popularity or follower count matter more for a track's popularity?
2. Do albums, singles or compilations perform better?
3. How do explicit content and track length affect popularity?
4. Which genres and artists lead, and how has release volume changed over time?

## Tools Used
Power BI Desktop, Power Query, DAX, Excel/CSV

## Key Findings
- Artist popularity is the strongest driver of track popularity (correlation about 0.52). Follower count is weaker (about 0.25).
- Albums (58.8 average popularity) outperform singles (51.2) and compilations (45.9).
- Explicit tracks average 61.1 vs. 54.6 for clean tracks.
- Tracks of 3.5 to 5 minutes perform best (59.3), and tracks under 2.5 minutes perform worst (47.2).
- Release volume is rising: about 730 tracks from 2025 vs. about 440 from 2020.

## Limitations
- Popularity is Spotify's 0 to 100 score, not stream counts.
- A song's genre is its artist's genre, and 39% of tracks have an unknown genre.
- Correlation does not prove cause.
- Popularity is Spotify's 0 to 100 score, not stream counts.
- A song's genre is its artist's genre, and 39% of tracks have an unknown genre.
- Correlation does not prove cause.
