# Gui Markup Language (GML) #

TODO(Imalaia3): If Needed Split In Multiple Files
<br>
TODO(Imalaia3): Get It On SerenityOS 


## What is GML ##
GML is a GUI language for SerenityOS. It is used to make UIs for apps.




## GUI::Widget ##
GUI::Widget is used as a canvas for other items.
<br>
For Example:
<br>
<br>
Open GML Playground and create a Widget by writing this:

    @GUI::Widget {
      @GUI::Button {
        text:"Widgets!"
      }
    }
    
You don't have to worry about the button for now. This creates a Widget and adds a Button with the Widget as Parent. We can add more inside the Wdget and they will stay parented to the Widget.
<br>




