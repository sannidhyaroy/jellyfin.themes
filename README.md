# Jellyfin Themes
A Collection of custom Jellyfin themes using CSS

---
## List of supported themes:
- [Hint of Green](hintofgreen.css)
- [Scyfin (modified)](scyfin.css)
- [Ultrachromic](ultrachromic.css)

---
## Installation:

### Copy one of the CSS codes below:
##### Hint of Green:
```css
@import url('https://sannidhyaroy.github.io/jellyfin.themes/hintofgreen.css');
```

##### Scyfin:
```css
@import url('https://sannidhyaroy.github.io/jellyfin.themes/scyfin.css');
```
##### Ultrachromic:
```css
@import url('https://sannidhyaroy.github.io/jellyfin.themes/ultrachromic.css');
```

### Then proceed with either Server-wide or Client-side Installation...

#### Server-wide Installation:
- Paste one of the CSS codes above into `Menu > Dashboard > General > Custom CSS code`.
- Ensure `Enable the Splash screen` is checked.
#### Client-side Installation:
- Paste one of the CSS codes above into `Menu > Display > Custom CSS code`.
- Ensure `Disable server-provided custom CSS code` is checked to above clashing with the Server's Custom CSS (if available).
- If you need to show an SSO Button on the login page, either add the contents of `sso-login-disclaimer.css` file to the `Menu > Display > Login Disclaimer` input field or the following import statement:
  ```css
  @import url('https://sannidhyaroy.github.io/jellyfin.themes/sso-login-disclaimer.css');
  ```
