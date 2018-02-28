# sugarbeet-processed
Each .mat file contain one struct, named `sugarbeet`:
```
sugarbeet = 

  struct with fields:

                  map: [944856×3 single]
             mapColor: [944856×3 double]
         mapSegmented: [28884×3 single]
    mapSegmentedColor: [28884×3 double]
      handLabeledSEPs: [25×2 double]
```

The fields contain the following data:
- `map` strip of sugarbeet pointcloud with points in format (x, y, z)
- `mapColor` color information for the points from `map` in format (R, G, B)
- `mapSegmented` sugarpeet after segmentation, format is the same as `map` 
- `mapColor` color information for the points from `mapSegmented`
- `hanLabeledSEPs` hand labeled sugarbeet positions in format (x, y)
