# Better-DOMJs Docs
This rebuilds the docment.createElement('button') &amp; more to $.makeObject('button') and it auto appends to document.body by default

# In Index.js
`import { $ } from "https://raw.githubusercontent.com/Zombiefiedgamingyt/Better-DOMJs/main/BetterDOM.js"`

# In Index.html
`<script type="module" src="https://raw.githubusercontent.com/Zombiefiedgamingyt/Better-DOMJs/main/BetterDOM.js"></script>`


### making a button
##### Index.js
```
import { $ } from "https://raw.githubusercontent.com/Zombiefiedgamingyt/Better-DOMJs/main/BetterDOM.js"

// Don't do this \/
$.content(($.makeObject("button", $.addMetadata($.makeObject("a"), "href", "https://discord.com")), "Go to Discord")


// Do this \/
let link, button

link = $.makeObject("a")
$.addMetadata(link, "href", "https://discord.com")
button = $.makeObject("button")
$.content(button, "Go to Discord")

```
