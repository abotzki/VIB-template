<!--
author:   Alexander Botzki

email:    alexander.botzki@vib.be

version:  0.0.1

language: en

narrator: US English Female

comment:  This plugin applies minor changes to for VIB layout.

@onload

const logo = document.querySelector(.lia_header__logo);

logo.src = "https://vib.be/sites/vib.sites.vib.be/files/logo_VIB_noTagline.svg"

@end
-->

# Fullscreen - Template

By importing this README via:

`import: https://raw.githubusercontent.com/vibbits/VIBLayyout/0.0.1/README.md`

into your document header, as it is shown below, an event listener will be added automatically to your course, which will apply the VIB logo and colors.

``` markdown
<!--
author:   ...

import: https://raw.githubusercontent.com/vibbits/VIBLayout/0.0.1/README.md
-->

# Main Title
```

## Implementation

``` javascript
@onload

const logo = document.querySelector(.lia_header__logo);

logo.src = "https://vib.be/sites/vib.sites.vib.be/files/logo_VIB_noTagline.svg"

@end
```