# roblox-uno-wins

This is an archive of [Roblox Uno](https://www.roblox.com/games/1689414409)'s wins leaderboard, with data up to `2023-06-11`, the day the game was taken down.
Even though the game may be taken down, the players' legacy shall live on.

Players with 1 win or lower were omitted because it made up 95% of the data, and would have inflated file size GREATLY.

Thanks for the 5 years of fun!

Moving onwards, [Crazy 8s](https://www.roblox.com/games/13772794683) is the proper re-branded version of Roblox Uno to comply with the law.

# Explanation

Win data can be found in the `data.csv` files in each of the data folders.
If the file was too large, it may be split into `data1.csv`, `data2.csv`, etc.
The format is in the following:

```csv
123,10
198,5
```

Such that a user with user id 123 has 10 wins, and user with user id 198 has 5 wins.

## Data folders

- [Leaderboard1](./Leaderboard1/) contains win data from `2022-02-06` to `2023-06-11`
- [Leaderboard](./Leaderboard/) contains win data from `2018-11-xx` to `2022-02-06`
- [Combined](./Combined/) contains all of the above combined into one. If there's a conflict (player id exists in both), we use the one from the newer leaderboard.
