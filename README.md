# Strings to Positions

This library takes in the source text and a list of strings (or chunks) that occurs in the source text, the library will return either a list of offsets or a list of positions, the same length of the input list.

## Offset

`Tuple[startOffset, endOffset]`

## Position

```
{
  start: {
    line: "1-index int",
    column: "1-index int",
    offset: int
  },
  end: {
    line: "1-index int",
    column: "1-index int",
    offset: int
  }
}
```
