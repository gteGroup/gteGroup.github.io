```
=IF(
  AND([Baseline Start Date]@row <> "", [Baseline Finish Date]@row <> ""),
  ROUND(
    IF(
      TODAY() < [Baseline Start Date]@row, 
      0,
      IF(
        TODAY() >= [Baseline Finish Date]@row, 
        1, 
        NETWORKDAYS([Baseline Start Date]@row, TODAY()) / NETWORKDAYS([Baseline Start Date]@row, [Baseline Finish Date]@row)
      )
    ), 2
  ),
  0
)
```
