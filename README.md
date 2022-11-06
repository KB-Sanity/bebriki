# Bebriki

## How to add/edit your keyboard

Create new [issue](https://github.com/KB-Sanity/bebriki/issues/new/choose) with "Keyboard data" template and fill all data in form

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
