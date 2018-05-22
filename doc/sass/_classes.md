# undefined

This file provide the mixins to generate dropdown classes


## Mixins


### s-dropdown-classes

Print out the bare and style dropdown css
Classes generated:
- `.dropdown`
- `.dropdown--up`
- `.dropdown--right`
- `.dropdown__menu`
- `.dropdown__item`
- `.dropdown.active, .dropdown:active, .dropdown[active], .dropdown--active, .dropdown:hover`


Name  |  Type  |  Description  |  Status  |  Default
------------  |  ------------  |  ------------  |  ------------  |  ------------
$color  |  **{ List<Color> }**  |  The colors to generate  |  optional  |  default primary secondary


### s-dropdown-classes-bare

Print out the bare dropdown css
Classes generated:
- `.dropdown`
- `.dropdown--up`
- `.dropdown--right`
- `.dropdown__menu`
- `.dropdown__item`
- `.dropdown.active, .dropdown:active, .dropdown[active], .dropdown--active, .dropdown:hover`


### s-dropdown-classes-style

Print out the style dropdown css
Classes generated:
- `.dropdown`
- `.dropdown__menu`
- `.dropdown__item`
- `.dropdown.active, .dropdown:active, .dropdown[active], .dropdown--active, .dropdown:hover`


Name  |  Type  |  Description  |  Status  |  Default
------------  |  ------------  |  ------------  |  ------------  |  ------------
$color  |  **{ List<Color> }**  |  The colors to generate  |  optional  |  default primary secondary