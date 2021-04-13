# Duckduckgo-white-flash-fix
This super simple CSS-file fixes the very annoying sudden bright white flash that occurs in Safari on macOS, when searching Duckduckgo in a new tab, and systemwide dark mode selected. Enjoy surfing duckduckgo without burning your retinas out at night :)

It automatically detects if your system is set to Dark or Light-mode, and changes the background of Safari accordingly, either to dark/charcoal or white respectively. 

HOW TO INSTALL

- Download the stylesheet: https://github.com/TorsteinVin/Duckduckgo-white-flash-fix/blob/main/duckduckgo-torsteinvin-white-flash-fix.css
- Save the stylesheet somewhere safe, ie you documents folder
- Open Safari > Settings > Advanced >Stylesheet and choose this css-file
- Quit Safari and re-open. It should now work :) 
- **Don't delete the CSS-file after import, as it will dissappear from Safari if you do so**********

If you'd rather want to make your own CSS-file instead of downloading and importing from a stranger like me, here's the code:




@media (prefers-color-scheme: dark) {
  body {
  background-color: #161616;
}
}
 
@media (prefers-color-scheme: light) {
  body {
  background-color: #FFFFF;
}
}

