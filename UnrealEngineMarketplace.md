# UnrealEngine Marketplace
### hide owned assets to easier spot not owned ones...
  
_Make sure to use plugin such as Stylus_
```css
@-moz-document domain("unrealengine.com") {
div.asset-container > article.asset--owned {
    display:none!important;
    opacity:0!important;
}
}
```
