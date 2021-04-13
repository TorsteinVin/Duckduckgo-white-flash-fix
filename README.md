# Duckduckgo-white-flash-fix
This super simple CSS-file fixes the very annoying sudden bright white flash that occurs in Safari on macOS, when searching Duckduckgo in a new tab, and systemwide dark mode selected. Enjoy surfing duckduckgo without burning your retinas out at night :) 

Here's a video of the problem: https://www.youtube.com/watch?v=YCXCjLDkcp4

The CSS-file automatically detects if macOS system is set to Dark or Light-mode, and changes the background of Safari accordingly, either to dark/charcoal or white respectively. That way you won't get blinded by a white flash in dark mode, but you also don't have to look at a sudden black flash when in light mode. 

HOW TO INSTALL

- Download the stylesheet: https://github.com/TorsteinVin/Duckduckgo-white-flash-fix/blob/main/duckduckgo-torsteinvin-white-flash-fix.css
- Save the stylesheet somewhere safe, ie you documents folder
- Open Safari > Settings > Advanced >Stylesheet and choose this css-file
- Quit Safari and re-open. It should now work :) 
- **Don't delete the CSS-file after import, as it will dissappear from Safari if you do so**

Known issues:
- It's not specific to duckduckgo, and colors every webpage that hasn't defined a specific backgorund-color for body to be colored either black or white. This obviously breaks some websites. If you know how to fix that, please contact me :)
- 
