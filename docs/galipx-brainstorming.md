# Galipx Ideas

## Page Layout

1. Index page

   - Header
     - logo
     - Language switcher
     - link to elibrary
   - Phase navigator
   - Footer
     - Links to othe page.
     - footer text

2. Phase Page
   - Header
     - Phase Navigator
     - Logo
     - Language switcher
     - Navigate to home link
     - Virtual library link
   - content
     - Steps Navigator
     - steps slider
     - content
     - notes
     - experience
     - definitions
     - tips
     - learn more
     - worth browsing

## Data Modeling

```json
{
    language:   {
        Phases :    [{
            title,
            description,
            steps: [{
                title,
                description,
                notes,
                experience,
                definitions,
                tips,
                learn more,
                worth browsing
            }]
        }]
    }
}
```
