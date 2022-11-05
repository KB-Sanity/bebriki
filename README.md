# Bebriki

## Data Scheme

Data:
```json
{
    "keyboards": KeyboardItem[],
}
```

KeyboardItem:
```json
{
    "switch_count": number | [number, number], // count or [minCount, maxCount]
    "tags": string[],
    "name": string,
}
```