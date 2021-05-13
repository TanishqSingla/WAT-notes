# Numeric Conversions

## Convert

The `convert` commands as the name suggests converts the types

| Function          | Action                    |
| ----------------- | ------------------------- |
| f32.convert_u/i32 | Converts u32 value to f32 |
| f32.convert_s/i32 | Coverts i32 value to f32  |
| f32.convert_u/i64 | Converts u64 value to f32 |
| f32.convert_s/i64 | Converts i64 value to f32 |

| Function          | Action                    |
| ----------------- | ------------------------- |
| f64.covnert_u/i32 | Converts u32 value to f64 |
| f64.convert_s/i32 | Converts i32 value to f64 |
| f64.convert_u/i64 | Converts u64 value to f64 |
| f64.convert_s/i64 | converts i64 value to f64 |

## Truncation

Truncation removes the fractional part of floating point number.

| Function        | Action               |
| --------------- | -------------------- |
| i32.trunc_u/f64 | Truncates f64 to u32 |
| i32.trunc_s/f64 | Truncates f64 to i32 |
| i32.trunc_u/f32 | Truncates f32 to u32 |
| i32.trunc_s/f32 | Truncates f32 to i32 |

| Function        | Action               |
| --------------- | -------------------- |
| i64.trunc_u/f64 | Truncates f64 to u64 |
| i64.trunc_s/f64 | Truncates f64 to i64 |
| i64.trunc_u/f32 | Truncates f32 to u64 |
| i64.trunc_s/f32 | Truncates f32 to i64 |

## Reinterpret

The `reinterpret` command keeps the bits same of the value but changes the type

| Function            | Action                        |
| ------------------- | ----------------------------- |
| i32.reinterpret/f32 | Reinterprets f32 value to i32 |
| i64.reinterpret/f64 | Reinterprets f64 value to i64 |

| Function            | Action                        |
| ------------------- | ----------------------------- |
| f32.reinterpret/i32 | Reinterprets i32 value to f32 |
| f64.reinterpret/i64 | Reinterprets i64 value to i32 |

## Extend

| Function         | Action                          |
| ---------------- | ------------------------------- |
| i64.extend_u/i32 | Converts i32 value to u64 value |
| i64.extend_s/i32 | Converts i32 value to i64 value |

## Wrap

The `wrap` command puts the lower 32 bits of a 64-bit integer into an i32.

| Function     | Action                             |
| ------------ | ---------------------------------- |
| i32.wrap/i64 | Wraps bits of i64 bit value to i32 |

## Promote and Demote

| Function        | Action              |
| --------------- | ------------------- |
| f32.demote/f64  | Converts f64 to f32 |
| f64.promote/f32 | Converts f32 to f64 |
