# Usage

Setting colors and modifiers for each statement:

```
import terminal-color

print(Red, Bold, "Error:")
println(Red, " This is an error message")
print(Yellow, Underlined, "Warning:")
println(Yellow, " This is a warning message")
println(Green, "This is a success message")
println(Cyan, "This is an info message")
```

Setting colors for all subsequent statements:

```
set-terminal-color(STANDARD-OUTPUT-STREAM, Red)
println("This message is in Red!")

set-terminal-color(STANDARD-OUTPUT-STREAM, Cyan)
println("This message is in Cyan!")

set-terminal-color(STANDARD-OUTPUT-STREAM, NoColor)
println("This message has no color associated with it!)
```
