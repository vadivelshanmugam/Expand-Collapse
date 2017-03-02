# Expand-Collapse
This plugin about Expand and Collapse content.

### Plugin Call
```
$('.icon-img').on('click', function(e){
  $(this).expandCollapse(e, '<div>Content</div>'); //(event, Content to be viewwd in the expand)
});
```
### Example HTML snippet
```
<tr class="expand-header">
  <td><span class="text icon-expand">Header <a class="icon-img icon-open"></a></span></td>
</tr>
<tr class="expand-content"></tr>
-------------------------------
<div class="expand-header"><span class="text icon-expand">Header <a class="icon-img icon-open"></a></span></div>
<div class="expand-content"></div>
```
### Library
jQuery
