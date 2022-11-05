# Bebriki

## Data Scheme

Data:
```typescript
{
    "keyboards": KeyboardItem[],
}
```

KeyboardItem:
```typescript
{
    "switch_count": number | [number, number], // count or [minCount, maxCount]
    "tags": string[],
    "name": string,
}
```
