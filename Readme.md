#### w6d1 - HW - Responsive Layout

###### Build a responsive layout for a message feed.

[Surge]()

**CSS Tools**
  * Used 
```
    @media screen and (min-width: px) {
        body {
            style: type; 
        }
    }
```
        
* Used `:nth-child(even)` and `:nth-child(odd)` to select message divs and give alternating background colors.
* Used `:last-child` to remove lingering margin from last message div.
* Used `$lightblue: #color` to declare color variable.  Color can now be changed in varibale, rather than in every instance of the style.