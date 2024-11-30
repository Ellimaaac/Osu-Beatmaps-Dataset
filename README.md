# Osu-Beatmaps-Dataset
Osu Dataset of ALL Beatmaps from 2007 to today 

## License
CC-BY-NC-SA

Available in [Kaggle](https://www.kaggle.com/datasets/ellimaaac/osu-dataset-of-all-beatmaps-from-2007-to-today)

| Titre                | Artiste   | Mapper   | Date de création | Date de ranked | État de la carte | Nominator | Genre | Langue | Playcount | Likes | Length | BPM | Circle Count | Slider Count | Circle Size | HP Drain | Accuracy | Approach Rate | Star Rating | Game Mode | URL | Difficultés |
|----------------------|-----------|----------|------------------|----------------|------------------|-----------|-------|--------|-----------|-------|--------|-----|--------------|--------------|-------------|----------|----------|---------------|-------------|-----------|-----|-------------|
| Vois sur ton Chemin | Bennett   | ELLIMAC  | 23 Sep 2024     | Non Ranked     | Graveyard        | ...         | Other | French | 54        | 0     | 2:54   | 220 | 578          | 196          | 4           | 5        | 8        | 9             | 6.27        | osu!     | https://osu.ppy.sh/beatmapsets/2254185  | Insane      |



- 22 features 
- 5 million beatmaps (estimation +20M raws)

## Status of progress
- **⚠ Code Operational :**
  - **Issue** : Take into account the first gamemode and not the others (if there is/are) (2024-11-16)
  - Testing code (2024-11-27 to 2024-11-30)
  - **Issue** : Explicit content management. SOme beatmaps has an explicit content page before accessing the main page (2024-11-30)
  - Testing code (2024-11-30)
- Dataset : test phase - 16k data (0,3 %  of the final data set) (2024-11-9)
- Dataset 2 : new (because of the issue) test phase - 30k beatmaps (2024-11-16)
- Next Dataset (2024-12-07)

## Updates & Modification
There is a HUGE size difference between test 2 and the last one.  Based on my data :

### Dataset 2

| Numkber of Beatmaps extract  | Numbers of Raws  | Percentage | Size (Mo) | Estimated size (Mo) |
|--------|-------|-------------|-------------|---------------------|
| 29484  | 55446 | 0,58968     | 10,2        | 1729,75173          |

### Actual one

| Number of Beatmaps extract | Number of Raws  | Percentage | Size (Mo) | Estimated size (Mo) |
|-------|-------|-------------|-------------|---------------------|
| 4035  | 25719 | 0,0807      | 5           | 6195,786865         |

**Before this code update I was able to extract 1k beatmaps per hour, now it's about 300 per hour. It will take some time.**
