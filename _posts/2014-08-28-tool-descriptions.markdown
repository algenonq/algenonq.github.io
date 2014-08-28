---
layout: post 
title: "Calligraphy Toolbox - Tools” 
categories: calligraphy toolbox angular web 
tags: ["calligraphy","toolbox","architecture","angular"]
comments: true
---

#Tools Descriptions

Guidelines
----------

###Populating Values

The tool will allow the user to choose the script and/or the nib-width from a sample set. This will populate the proportion fields to save time. All values may then be adjusted for personal preferences.

If no script or nib is selected, foundation hand and Speedball C0 will be selected as defaults.

###Proportions

As in typography, each script in calligraphy has defined proportions which look “right”.

The proportions defined are:
- x-height: the height of the letter body e.g. the height of an “a”;
- ascender: the height of the ascender above the body e.g. the tail of a “d”;  
- descender: the depth of a descender below the body e.g. the tail of a “y”; and
- capitals: the height of a capital letter (not always the same as an ascender).

The dimensions used are always nib-widths. This means the proportions of the letter will remain the same regardless of the size.

Calligraphy pen nib-widths come in all sizes from thin lines to several millimetres. This tool will have a small database of the common pen sizes. This must be customisable as there are a variety of pen manufacturers out there.

As mentioned, most book based scripts will have the x, ascender and descender heights defined. However, the joy of calligraphy is in playing around with the proportion of letters. The tool will have a table of common script proportions as defined in several books. Each of the values must be editable.

###Spacing

Interlinear spacing is important for composition. This option allows for adjusting the spacing between the lines (again in nib-widths).

###Options

- Darkness: As guidelines are placed beneath the worksheet, they can sometimes be hard to see even with a light-box. The weight and colour of lines must be configurable.
- Verticals: Beginners often have trouble with keeping letters vertical. It is sometimes useful to draw vertical “reminders” periodically along the guideline. The “vertical may be set to an angle for sloped scripts like in the italic style.
- Shaded X: Sometimes it is hard to distinguish the x-height lines from the ascender and descender lines. Use this to fill between the x-height lines with hatches or solid colour.
- Description: text to be printed at the top of the page to denote the script chosen etc.
- Multiple pages: Rather than developing a pdf for a single pen width, I think it might be useful to allow the choice of selecting a range of nibs and generating one set of guidelines per page. E.g. rather than selecting Speedball C0 and generating a 1 page pdf, select Speedball All with 7 pages - one each for C0,C1,C2,C3,C4,C5 and C6.

###Interaction

I envisage this tool having a dynamic canvas which reflects the guideline choices as they are made. This canvas may be an image or may indeed be a pdf - depending on performance. 

I imagine the pen selection will be a multi-select from a pre-defined database. But the user must be able to enter custom pen widths here. 

Measurement - All working measurements are in nib-widths. Fractions are allowed. All nib widths are measured in mm.

Paper dimensions must include A2,A3,A4 and B5?. Also Letter. What about envelopes? hmmm.

The generated guideline pdfs are to be downloaded from the browser and saved. It is up to the user to print from there. Perhaps a print view which opens a new page with the pdf?

### Workflow

Experienced: Choose the script -> choose the pen -> adjust -> choose options -> save -> print

Iteration from any state must be allowed and feedback given through a exemplar.