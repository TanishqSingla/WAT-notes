# Block
A block in wat is used to skip through the code.

```wast
(block $break               ;; ------------
    br $break               ;;            |
    (local $random i32)     ;;            |
                            ;;            |
    i32.const 21            ;;            |
    local.set 32            ;;            |
)                           ;;            |                        
 ;; After br the execution gets here <-----
```