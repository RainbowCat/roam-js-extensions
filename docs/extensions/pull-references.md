## UNDER DEVELOPMENT

## Pull References

The Pull References gives user the ability to pull references to the page. The name of the script is `pull-references`.

### Usage

The script supports the following configuration attributes, to be added in the `[[roam/js/pull-references]]` page:

- `Format` - Coming soon...

Create a button by typing `{{pull references}}` into a page. Clicking the button adds all the linked references as references on the current page.

### Installation

Insert this as a child of any `{{[[roam/js]]}}` block to install the extension.

```javascript
var old = document.getElementById("pull-references");
if (old) {
  old.remove();
}

var s = document.createElement("script");
s.src = "https://roamjs.com/pull-references.js";
s.id = "pull-references";
s.async = false;
s.type = "text/javascript";
document.getElementsByTagName("head")[0].appendChild(s);
```

<iframe src="https://github.com/sponsors/dvargas92495/button" title="Sponsor dvargas92495" height="35" width="116" style="border: 0;"></iframe>