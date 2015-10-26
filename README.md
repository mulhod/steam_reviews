# Steam Review Datasets

## Background

These datasets were scraped from the Steam [website](http://store.steampowered.com/) as part of a research project for my master's thesis. Each review comes alongside numerous pieces of data, including the number of people who marked the review helpful, the number of people who marked the review funny, the number of friends the reviewer has on the site, etc. One of the more important pieces of data, however, is the number of hours that the reviewer played the game that they are reviewing. My project -- at least, initially -- was focused on creating models of reviews that would be able to predict how useful they were or whether they were real reviews or not and I was using this piece of data as a proxy for that. (If at all interested in finding out more information about my work, I store the code related to that project in [this GitHub repository](https://github.com/mulhod/reviewer_experience_prediction).)

## Data

The datasets are contained in the ```data``` directory. Datasets were extracted for the following games (with number of reviews in parentheses):

1. Arma 3 (7,151)
2. Counter Strike (6,040)
3. Counter Strike: Global Offensive (7,073)
4. Dota 2 (9,720)
5. Football Manager 2015 (1,522)
6. Garry's Mod (7,151)
7. Grand Theft Auto V (13,349)
8. Sid Meier's Civilization 5 (7,467)
9. Team Fortress 2 (5,676)
10. The Elder Scrolls V (7,165)
11. Warframe (7,123)

Some filtering was done to ensure that reviews contained some textual content, were in English, and didn't have an outlier-like number of game-hours played, etc. Information about how the reviews were filtered is contained in the ```reports``` directory.
