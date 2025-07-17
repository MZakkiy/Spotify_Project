# Analysis of Song Popularity on Spotify

This project analyzes over 114,000 songs from Spotify to identify the key factors that contribute to a song's popularity. The analysis moves beyond surface-level correlations to understand the nuanced relationships between a song's attributes and its success.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mrOERaltOXJN8D9bVmPBgQVd3fIOKQDT?usp=sharing)

## Project Overview

The goal of this project was to test the hypothesis that specific, measurable audio features could predict a song's popularity score on Spotify. I investigated not only which factors correlate with success, but also which commonly held beliefs about popular music are not supported by the data.

## Key Findings

1.  **Popularity is More Than Just Audio Features:** While one might expect "danceable" or "energetic" songs to be vastly more popular, the analysis shows that most individual audio features have a surprisingly weak correlation with a song's popularity score. This suggests that the technical sound of a song is not its main driver of success.

2.  **Many Common Factors are Not Decisive (Myth-Busting):** Further analysis revealed that several factors often assumed to be important have a minimal impact on average popularity. This includes:
    * **Tempo:** A song's pace (slow, moderate, or fast) does not significantly affect its popularity.
    * **Loudness:** Once a song reaches a moderate volume, being "louder" does not provide a popularity advantage.
    * **Musical Key:** Whether a song is in a major ("happy") or minor ("sad") key has a negligible effect.
    * **Explicit Lyrics:** While explicit songs have a slightly higher average popularity, the difference is too small to be a determining factor.

3.  **Genre Remain Key Pillars of Success:** The analysis consistently showed that broader, contextual factors are far more important than isolated audio features. The most popular songs were concentrated within specific genres (like **Pop-film** and **K-pop**).

## Tools and Libraries

* **Python**
* **Pandas** (for data manipulation)
* **Matplotlib & Seaborn** (for data visualization)
* **Google Colab** (as the development environment)
