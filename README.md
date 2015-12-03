# rsssf format

football match schedule formats in plain "vanilla" text


use two formats (readers) ???  e.g. league format (no knockouts etc.) and cup format - why, why not??


## League Format

## Cup Format



### Round Headers

```
Round 1
Round 2
Round 3
Round 4
...
Round 33
Round 34
```

with Date Format (see below)

### Date Format

1) Free Standing

```
[Apr 11]
```

2) Inline - Round Header

```
Round 34 [May 17]
```




### Scoring (After Extra Time, Penalties, etc.)

Example:

```
TSG Hoffenheim           4-2 FC Augsburg         [aet]
Rot-Weiss Essen          2-2 Energie Cottbus     [aet, 6-5 pen]
```

### Special Cases (Abandoned, Replay, etc.)


Abandonend and replay

Example:

```
[Apr 11]
Nürnberg       abd Wolfsburg       [abandoned at 1-0 at half-time due to
                                    waterlogged pitch]
[Apr 20]
Nürnberg       1-0 Wolfsburg       [replay]
```




### Knockout Cases (Byes)

```
Round 5 [Jun 18]
MTV Gifhorn       0-2 VfB Oldenburg
SC Victoria       0-2 VfL Oldenburg
Bye: FC Oberneuland
```



### Outliers

```
Nürnberg       abd Wolfsburg       [abandoned at 1-0 at half-time due to
[Apr 12]                            waterlogged pitch]
```

abandonend wrap over two lines - use indentation to find match - why? why not?? 

