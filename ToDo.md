
### Misc Issues
- Support A2HS - Adding to Home Screen - this prevents clearing of local storage by Safari.
    - https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Add_to_home_screen
    - https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Installable_PWAs
- Looking into hosting via github-pages
- Look into using <input type="date">
- Look into using regexp with input/text pattern attribute to validate text fields.
- favicon - might dovetail with manifest required by A2HS
- Error message if reference date < hire date. Currently, it just silently fails.

### Persistance of Data
- Safari wipes out local storage after 7 days.
    - https://www.theregister.com/2020/03/26/apple_relax_were_not_totally/
- One workaround is to make avp your home page, but downside is new windows do _not_ start out with the address bar focused. Is there a way to give the address bar focus on page load?