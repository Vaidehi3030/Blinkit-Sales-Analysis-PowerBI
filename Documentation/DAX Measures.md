# DAX Measures

## Total Sales

```DAX
Total Sales =
SUM(BlinkIT[Sales])
```

## Average Sales

```DAX
Average Sales =
AVERAGE(BlinkIT[Sales])
```

## Total Items

```DAX
Total Items =
COUNT(BlinkIT[Item Identifier])
```

## Average Rating

```DAX
Average Rating =
AVERAGE(BlinkIT[Rating])
```

## Total Outlets

```DAX
Total Outlets =
DISTINCTCOUNT(BlinkIT[Outlet Identifier])
```

## Sales %

```DAX
Sales % =
DIVIDE(
    [Total Sales],
    CALCULATE([Total Sales], ALL(BlinkIT))
)
```

## Average Visibility

```DAX
Average Visibility =
AVERAGE(BlinkIT[Item Visibility])
```
