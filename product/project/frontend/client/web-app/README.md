# the web app is structured as such:

## HTML is for *structure*, *semantics*, meaning, ui/ux model  
- don't put css, js, visualisations inside
- use proper tagging: header, footer, main etc., not generic divs 
- on each element, ask: *what is the meaning* of this element
- will the meaning remain for text-readers, assistive technologies, bots
- disable css and test the *meaningful structure*
- disable javascript and see what is left for the bots and paranoid users. Do you want some meaning still available to visitor/user/bot...?
```
//logical hint:
jsEnabled ? executeApp() : returnStaticContent() ;
``` 


## CSS is for *representation*, *layout*, visuals; 
- separate *layout* and pure *visuals* 
- in the layout section, put just the positioning logic:  
-- if mobile ...  
-- else if tablet ...  
-- else if desktop ...  
- put the rest in the visuals section, altough you'll repeat selectors; this way you'll work safer with the concerns separated


