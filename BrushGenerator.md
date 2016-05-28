Takes a csv delimited template and generates a properly formatted brush file.

# Introduction

BrushGenerator takes a csv delimited template and generates a properly formatted brush file. This allows for easy setup of brush entries using templated files.


# Details

```
<generatebrush brushFileName="${example.brush}" brushFileTemplate="${basedir}/templates/example_hudicon_research_brush.csv" 
   prefix = "HUDICON_RESEARCHSUBJECT_"
   cursorOverFileName="Example_Buttons_Research2_CursorOver" 
   disabledFileName="Example_Buttons_Research2_Disabled" 
   normalFileName="Example_Buttons_Research2_Normal" 
   pressedFileName="Example_Buttons_Research2_Normal">
</generatebrush>
```

example brush file:
Note empty entries are placeholders for future references and will not generate a brush entry.

```
ROW,COLUMN,ICON NAME,STARTX,STARTY,WIDTH,HEIGHT
1,1,NEPHILIM_ARMOR0,5,1,33,47
1,2,NEPHILIM_ARMOR1,56,1,33,47
1,3,NEPHILIM_ARMOR2,107,1,33,47
1,4,,158,1,33,47
1,5,,209,1,33,47 
.... 
```