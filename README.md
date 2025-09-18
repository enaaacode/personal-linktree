# Free Linktree Alternative

This is a free alternative to Linktree.  

In the `_data` folder, you will find two YAML files that allow you to personalize the setup.  

To change the colors, edit `style.css`:
- **Background:** use `background-color` in the `body` selector
- **Font color:** use `color` in the `body` selector
- **Link button color:** use `background-color` in `.li_link`

In `index.html`, you will find YAML front matter at the top.  
Change `title`, `description`, and `keywords` to suit your needs.

You can also pick another picture or icon by uploading it to the `assets` folder and updating this line in `index.html`:

```html
<img src="assets/favicon.svg" alt="" width="50px" />
