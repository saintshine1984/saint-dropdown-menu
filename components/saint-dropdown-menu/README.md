[Demo](http://saintshine84.github.io/saint-dropdown-menu/components/saint-dropdown-menu/)

# saint-dropdown-menu
# saint-birthday-dropdown-menu

Custom paper-dropdown-menu.

```HTML
<saint-dropdown-menu label="Gender"  id="userGender" on-select="onSelect">         
  <paper-item value="1">male</paper-item>
  <paper-item value="2">female</paper-item>
</saint-dropdown-menu>

<saint-birthday-dropdown-menu
  year-start="0"
  year-end="100"
  init-date="1984-04-02"
  on-select="onSelect"
  postfixStyle>
</saint-birthday-dropdown-menu>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install --save saintshine84/saint-dropdown-menu
