# inline_colorization
add the library through writing in the command prompt:
```
cargo add inline_colorization
```
And in you main.rs file:
```
use inline_colorization::*;
```
Then you can run:
```
println!("Lets the user {color_red}colorize{color_reset} and {style_underline}style the output{style_reset} text using inline variables");
```
| Text Style Variables |
|----------------------|
| style_bold           |
| style_underline      |
| style_reset          |


| Text Color Variables |
|----------------------|
| color_black          |
| color_red            |
| color_green          |
| color_yellow         |
| color_blue           |
| color_magenta        |
| color_cyan           |
| color_white          |
| color_reset          |


| Text Background Variables |
|---------------------------|
| bg_black                  |
| bg_red                    |
| bg_green                  |
| bg_yellow                 |
| bg_blue                   |
| bg_magenta                |
| bg_cyan                   |
| bg_white                  |
| bg_reset                  |

Just remember to reset the style, color or background when you want the default text setting

  
