# Numeric Conversions

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
