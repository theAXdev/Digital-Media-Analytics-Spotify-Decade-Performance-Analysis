# 🎵 Digital Media Analytics — Spotify Streaming Trends 2010–2019

> A comprehensive decade-long analysis of Spotify's top-streamed tracks and artists from 2010 to 2019, executed entirely in Microsoft Excel. The project uncovers the streaming patterns, genre dynamics, artist dominance, playlist influence, and sonic characteristics that defined a decade of global music consumption.

---
<img width="1735" height="898" alt="Digital_Media_Analytics_Dashboard-2" src="https://github.com/user-attachments/assets/bfb3633b-62ee-4174-83e2-888530d4e565" />




---

## 📌 Project Background

The music streaming industry operates on data. Playlist placement decisions, artist development investment, release timing strategy, and marketing budget allocation are all increasingly driven by streaming analytics. This project applies structured data analytics methodology to one of the most commercially significant datasets in digital media — a decade of Spotify's top-streamed songs.

Starting from a 599-song dataset sourced from DataCamp Workspace, the analysis moves through data preparation, Pivot Table construction, and dashboard visualisation in Microsoft Excel — transforming raw streaming figures into strategic insights about what drives music performance on global platforms.

This project is part of the **Digital Media Analytics Portfolio Series** — a collection of projects spanning music streaming, social media performance, and platform intelligence.

---

## 🎯 Project Objectives

- Identify the most-streamed artists and individual tracks across the full decade (2010–2019)
- Analyse year-on-year streaming volume trends to identify the industry's key inflection points
- Determine which genres consistently attracted the largest streaming audiences
- Quantify the relationship between cross-platform playlist appearances and total stream counts
- Profile the sonic and structural characteristics (mode, key, energy, danceability) common to the highest-performing tracks
- Translate analytical findings into evidence-based recommendations for artists, labels, and platform strategists

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| Total Streams (2010–2019) | 451.3 Billion |
| Songs Analysed | 599 |
| Most-Streamed Artist | Ed Sheeran — 16.57B streams |
| Most-Streamed Song | Hello (Adele) — 3.92B streams |
| Dominant Genre | Dance Pop — 203.3B streams (45% of top-5 genre total) |
| Peak Streaming Year | 2015 — 61.74B streams |
| Major Key Songs | 346 of 599 (57.8%) |
| Minor Key Songs | 253 of 599 (42.2%) |

---

## 🗄️ Dataset

| Field | Detail |
|---|---|
| Source | DataCamp Workspace — Spotify Top Streamed Songs |
| Coverage | 599 top-streamed songs, 2010–2019 |
| Format | Excel (.xlsx) |

### Variables Included

**Track Identity**
- Song title, Artist name, Genre classification, Release Year

**Streaming Volume**
- Total Streams — the primary performance metric for all rankings and analysis

**Cross-Platform Playlist & Chart Data**
- Spotify Playlists, Apple Music Playlists, Deezer Playlists, YouTube Playlists
- Spotify Charts, Apple Charts, Deezer Charts, Shazam Charts, Billboard Rankings

**Audio Features (Spotify Algorithm Scores)**
- BPM, Decibel level, Mode (Major/Minor), Energy, Danceability, Liveness, Valence, Duration, Acousticness, Speechiness

**Audience Metric**
- Popularity score — Spotify platform-assigned popularity index

---

## ⚙️ Tools & Techniques

| Tool / Technique | Application in This Project |
|---|---|
| **Microsoft Excel** | Full analysis environment — data preparation, Pivot Tables, visualisations, dashboard |
| **Pivot Tables** | Aggregating streams by artist, song, genre, year, and playlist platform |
| **Calculated Fields** | Stream share percentages, KPI card totals, genre contribution ratios |
| **Conditional Formatting** | Highlighting top performers across the Data Table without filter operations |
| **Data Visualisations** | Bar charts, line charts, donut charts, grouped column charts, KPI stat cards |
| **Slicer Controls** | Interactive filtering by Year, Genre, and Artist across all dashboard visuals |

---

## 📐 Analytical Methodology

This project applies two analytical modes in sequence:

**Descriptive Analytics** — Understanding what happened across the decade: who streamed the most, which songs led, which genres dominated, and how annual volumes evolved.

**Diagnostic Analytics** — Understanding why: examining the role of playlist placement, sonic characteristics, and release timing in separating the highest-performing tracks from the rest.

---

## 🗂️ Excel Workbook Structure

The workbook is organised across dedicated sheets for clean separation of raw data, Pivot Table outputs, and dashboard:

| Sheet | Purpose |
|---|---|
| `Raw Data` | 603-row source dataset — original Spotify audio features (14 columns) |
| `Data Table` | 599-row enriched analytics dataset — streaming, playlist, chart, and audio feature variables (25 columns) |
| `Most Streamed Songs` | Pivot Table ranking songs by total streams |
| `Best Performing Artists` | Pivot Table ranking artists by cumulative decade streams |
| `Streams Trend Over Time` | Pivot Table aggregating annual streaming volumes 2010–2019 |
| `Most Popular Genre` | Pivot Table ranking genres by total streams |
| `Songs per Artist` | Pivot Table counting chart-present songs per artist |
| `Modality Distribution` | Pivot Table counting Major vs Minor mode distribution |
| `Playlist Performance` | Cross-platform playlist inclusion table — top-3 songs per platform |
| `Sums for Cards` | Calculated values powering the KPI summary cards |
| `Dashboard` | Interactive visualisation and KPI summary sheet |
| `Pre-Analysis Board` | Pre-analysis working notes and hypothesis documentation |
| `In-Analysis Board` | In-analysis working notes and intermediate findings |
| `Final Observations & Recs` | Written observations and structured recommendations |

---

## 📈 Top 10 Artists by Total Streams

| # | Artist | Total Streams |
|---|---|---|
| 1 | Ed Sheeran | 16.57B |
| 2 | Maroon 5 | 15.30B |
| 3 | Shawn Mendes | 14.75B |
| 4 | Justin Bieber | 13.59B |
| 5 | Calvin Harris | 12.64B |
| 6 | The Chainsmokers | 12.60B |
| 7 | Bruno Mars | 12.05B |
| 8 | Adele | 11.90B |
| 9 | Rihanna | 9.95B |
| 10 | Ariana Grande | 9.62B |

Ed Sheeran's 16.57B total reflects sustained multi-year chart presence across multiple album cycles — not a single breakout moment. The gap between first and second place (1.27B) is notable in a tightly competitive top-five field.

---

## 🎶 Top 7 Most-Streamed Individual Songs

| # | Song | Artist | Total Streams |
|---|---|---|---|
| 1 | Hello | Adele | 3.92B |
| 2 | Someone Like You | Adele | 3.74B |
| 3 | Love Yourself | Justin Bieber | 3.67B |
| 4 | Lose You To Love Me | Selena Gomez | 3.56B |
| 5 | Someone You Loved | Lewis Capaldi | 2.89B |
| 6 | Señorita | Shawn Mendes | 2.86B |
| 7 | Memories | Maroon 5 | 2.84B |

Adele is the only artist with two songs in the top three — despite ranking 8th in the overall artist leaderboard. This reflects the exceptional repeat-listening behaviour that emotionally resonant ballads generate compared to high-volume catalogue artists.

---

## 📅 Year-on-Year Streaming Trend (2010–2019)

| Year | Total Streams | Context |
|---|---|---|
| 2010 | 29.66B | Baseline year — streaming in early adoption phase |
| 2011 | 31.40B | Modest growth — platform user bases expanding |
| 2012 | 24.44B | Dip — fewer breakout hits in the top-streamed cohort |
| 2013 | 43.25B | Major spike — several landmark releases drive volume |
| 2014 | 34.40B | Correction after 2013 peak |
| **2015** | **61.74B** | **Industry inflection point — streaming becomes dominant** |
| 2016 | 54.10B | Sustained high-volume era begins |
| 2017 | 50.89B | Slight decline but above all pre-2015 levels |
| 2018 | 61.16B | Near match of 2015 peak — second major streaming surge |
| 2019 | 60.30B | Decade closes at sustained high — streaming fully mainstream |
| **Total** | **451.3B** | |

**2015 is the single most important year in this dataset.** It marks the moment streaming crossed from alternative consumption mode into mainstream dominance — and the platform never fell below 50B annual streams again for the remainder of the decade.

---

## 🎸 Genre Performance

| Genre | Total Streams | Share of Top-5 |
|---|---|---|
| **Dance Pop** | **203.3B** | **45.0%** |
| Pop | 73.3B | 16.2% |
| Canadian Pop | 32.0B | 7.1% |
| Electropop | 16.2B | 3.6% |
| Boy Band | 13.5B | 3.0% |

Dance Pop commands more than 2.75x the streaming volume of second-placed Pop — driven by its alignment with streaming platform recommendation algorithms (high energy, moderate-to-high danceability, major key tonality). Canadian Pop's third-place position is almost entirely driven by Justin Bieber, Drake, and The Weeknd — illustrating how individual artist dominance can elevate an entire genre classification.

---

## 🔍 Key Findings

### 1. Ed Sheeran Is the Decade's Dominant Streaming Artist
16.57B streams built across multiple album cycles — not a single breakout hit. His sustained multi-year chart presence across 'x' (2014) and '÷' (2017) era tracks explains the volume advantage over artists with higher song counts but lower per-song performance.

### 2. Adele's 'Hello' Is the Most-Streamed Individual Track
3.92B streams — 173 million ahead of second-placed 'Someone Like You' (also Adele). Both songs are in Minor key, confirming that emotionally resonant ballads generate exceptional repeat listening behaviour — a finding that challenges the assumption that high-energy dance tracks drive the highest individual stream counts.

### 3. 2015 Was the Streaming Industry's Inflection Point
The jump from 34.40B in 2014 to 61.74B in 2015 represents a 79.4% year-on-year increase — the largest single-year jump in the dataset. Every year from 2015 through 2019 maintained above 50B streams. This is the most structurally significant trend in the decade.

### 4. Dance Pop Commands 45% of Top-Genre Stream Share
203.3B streams — a dominance that reflects genre-platform alignment more than genre preference alone. Dance Pop's sonic characteristics are strongly favoured by Spotify's recommendation and playlist algorithms, creating a reinforcing cycle of exposure and streaming volume.

### 5. Playlist Placement Is the Strongest Streaming Amplifier
'Hello' appears in 62,170 Spotify playlists, 12,692 Deezer playlists, and 74,320 YouTube playlists — the broadest cross-platform playlist penetration in the dataset. YouTube's figure of 74,320 is the highest single-platform count across all top-three rankings, confirming YouTube as a primary streaming discovery channel alongside Spotify.

### 6. Platform Playlist Profiles Differ Significantly
Apple Music's top playlist song is 'Just the Way You Are' (Bruno Mars: 67,788 playlists) — not 'Hello'. This platform divergence is commercially significant: cross-platform success cannot be assumed from single-platform playlist performance. Each platform's curation algorithm and user base skews toward different sonic characteristics.

### 7. Major Key Dominates — But Minor Key Produces the Biggest Hits
57.8% of top-streamed songs are in Major key — but three of the top-5 most-streamed individual tracks are in Minor key. Emotional depth in Minor key tracks drives repeat listening behaviour that outperforms high-energy Major key tracks at the individual song level.

### 8. Katy Perry Has the Most Songs in the Top-Streamed Cohort
17 chart-present songs — more than any other artist. Justin Bieber (16) and Maroon 5 (15) follow. However, volume of chart-present songs does not guarantee the highest cumulative streams: Ed Sheeran's fewer but higher-performing tracks outpace Katy Perry's broader but lower-per-song catalogue.

---

## ✅ Recommendations

### For Artists & Management

1. **Prioritise Cross-Platform Playlist Pitching** — Submit to curators on Spotify, YouTube, Apple Music, and Deezer simultaneously. 'Hello's top-three placement on three of four platforms is directly correlated with its 3.92B stream total. Platform-exclusive playlist strategy leaves significant streaming volume unrealised.

2. **Build Multi-Release Careers Over One-Off Hits** — Ed Sheeran's lead is built across multiple album cycles. Sustained chart presence across multiple releases compounds streaming volume in a way a single breakout hit cannot. Labels should invest in long-form artist career development over single-track campaigns.

3. **Release Music Early in the Year** — Songs released in Q1 and Q2 have more months within their release year to accumulate streams before the annual chart cycle resets. Earlier annual placement also maximises exposure during mid-year algorithmic recommendation windows.

4. **Do Not Ignore Minor Key Releases** — Three of the top-5 most-streamed songs are in Minor key. Emotionally resonant ballads generate exceptional long-tail streaming performance. A portfolio of releases should balance high-energy Dance Pop with emotionally direct Minor key tracks.

### For Labels & A&R

5. **Align New Signings with Dance Pop Characteristics** — The genre's 203.3B streaming dominance is driven by platform-algorithm alignment. Artists producing high-energy, danceable, major-key music are structurally advantaged in streaming platform recommendation systems.

6. **Analyse Sonic DNA of Top Performers** — The highest-streaming tracks share identifiable audio feature profiles. BPM, energy, valence, and danceability scores from Spotify's API should inform A&R decisions and production direction for new releases.

7. **Monitor Genre Shift Signals** — Canadian Pop's third-place position is driven by three artists. If those artists shift genre or reduce output, that category's position will collapse. Genre diversification across a label's portfolio protects against individual artist dependency.

### For Platform Strategists

8. **Use Cross-Platform Divergence as a Discovery Signal** — Apple Music's top playlist song differs from Spotify's. These divergences reveal platform-specific audience preferences that can be used to tailor editorial playlist strategies and identify songs that are underperforming relative to their cross-platform potential.

---

## ⚠️ Limitations

- **Cumulative streaming bias** — Songs released earlier in the decade have had more time to accumulate streams. 2010–2014 tracks may appear relatively stronger than their peak-period performance would suggest
- **Genre granularity inconsistency** — Some genre labels are highly specific (Canadian Pop) while others are broad (Pop), making genre comparison an approximation rather than a precise market share calculation
- **Self-reported platform dynamics** — Playlist counts indicate inclusion volume but not promotional weight; editorial playlist placement carries significantly more discovery impact than standard user playlist inclusion
- **Audio feature approximation** — Spotify's energy, danceability, and valence scores are algorithm-derived, not direct acoustic measurements, and may shift as Spotify's classification models are updated
- **Dataset scope** — The analysis covers top-streamed tracks only; mid-tier and niche genre performance is not represented, which means genre dominance figures reflect hits culture rather than total industry output

---

## 🔭 Future Extensions

- Extend the dataset to 2020–2024 to examine post-pandemic streaming behaviour and the emergence of new genre dominance patterns (Afrobeats, K-pop, Latin Pop)
- Build a regression model in Python or R to quantify the relative predictive power of playlist count, release year, genre, and audio features on total stream count
- Incorporate TikTok virality metrics and social media engagement data to test whether social media performance predicts streaming outcomes in the post-2020 era
- Develop a song performance scoring tool — combining weighted playlist count, genre alignment score, and audio feature match to produce a predicted streaming potential index for new releases
- Add label and distributor data to examine whether major label affiliation systematically drives higher editorial playlist inclusion rates

---

## 📁 Repository Structure
Digital-Media-Analytics-Spotify-Streaming-Trends-2010-2019
┣ 📊 Digital_Media_Analytics.xlsx              ← Full Excel workbook — raw data, Pivot Tables, and dashboard
┣ 📄 Digital_Media_Analytics_Technical_Report.docx  ← Full technical report
┣ 🖼️ Digital_Media_Analytics_Dashboard.jpg     ← Dashboard preview image (displayed in this README)
┗ 📝 README.md                                 ← Project documentation (you are here)

### How to Use This Repository

1. **To explore the dashboard** — download `Digital_Media_Analytics.xlsx` and open in Microsoft Excel (2016 or later recommended for full Pivot Table and slicer functionality)
2. **To read the full analysis** — open `Digital_Media_Analytics_Technical_Report.docx` in Microsoft Word or Google Docs
3. **To work with the raw data** — the `Raw Data` and `Data Table` sheets in the workbook contain the full 599-song dataset ready for further analysis in Excel, Python, or R

---

## 🏷️ Tags

`excel` `pivot-tables` `data-analytics` `spotify` `music-analytics` `digital-media` `streaming-trends` `data-visualisation` `portfolio` `entertainment-analytics`

---

*Digital Media Analytics Portfolio Series — Microsoft Excel End-to-End Project*
