# Gui Markup Language (GML) #

TODO(Imalaia3): If Needed Split In Multiple Files
<br>
TODO(Imalaia3): Get It On SerenityOS 


## What is GML ##
GML is a GUI language for SerenityOS. It is used to make UIs for apps.




## @GUI::Widget ##
GUI::Widget is used as a canvas for for other items (like Button, TextBox)
<br>
## Usage ##
    @GUI::Widget {
        <Items...>
    
    }

<br>
<br>
layout:
<br>
"layout: " is used to set the layout of items (Top To Botton, Left To Right)
<br>
TODO:(Imalaia3): Make Desciption "GooD"
<br>
@GUI::VerticalBoxLayout{}
<br>
This can be added to the "layout: " to make the items in the widget go Top To Bottom.
<br>
@GUI::HorizontalBoxLayout{}
<br>
This can be added to the "layout: " to make the items in the widget go Left To Right.
<br>
<br>
You can add an item to: GUI::HorizontalBoxLayout / GUI::VerticalBoxLayout
<br>
## Spacing ##
<br>
spacing: <number> defines the space (pixels) between items in the widget. Example:
    
    layout: @GUI::VerticalBoxLayout {
        spacing: 20 //(< Spacing in pixels)
    }

