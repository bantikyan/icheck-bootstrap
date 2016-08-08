# icheck-bootstrap (Coming Soon) 

<a href="#" target="_blank"><img src="https://img.shields.io/badge/bower-v1.0.6-blue.svg" alt="Bower version"></a>
<a href="https://www.nuget.org/packages/icheck-bootstrap" target="_blank"><img src="https://img.shields.io/badge/nuget-v1.0.6-blue.svg" alt="Bower version"></a>

Did you had a problem customizing html checkboxes and radio buttons? icheck-bootstrap is pure css solution for displaying twitter bootstrap style checkboxes and radio buttons.

## Table of contents

* <a href="#user-content-getting-started">Getting started</a>
* <a href="#user-content-html-syntax">HTML syntax</a>
* <a href="#user-content-html-syntax">ASP.NET MVC syntax</a>
* <a href="#user-content-license">License</a>

## Getting started

Several quick start options are available:

* [Download the latest release](https://github.com//bantikyan/icheck-bootstrap/archive/master.zip)
* Install with [Bower](https://bower.io): <code>bower install icheck-bootstrap</code>
* Install with [Nuget](https://www.nuget.org/packages/icheck-bootstrap/): <code>Install-Package icheck-bootstrap</code>

icheck-bootstrap based on twitter bootstrap styles, make sure you link the [bootstrap](https://github.com/twbs/bootstrap) stylesheet properly in your header.

## HTML syntax

#### checkbox example

```
<div class="checkbox icheck-primary">
    <input type="checkbox" id="someCheckboxId" />
    <label for="someCheckboxId">Clieck to check</label>
</div>
```

#### radio buttons example

```
<div class="radio icheck-primary">
    <input type="radio" id="someRadioId1" name="someGroupName" />
    <label for="someRadioId1">Option 1</label>
</div>
<div class="radio icheck-primary">
    <input type="radio" id="someRadioId2" name="someGroupName" />
    <label for="someRadioId2">Option 2</label>
</div>
```

## ASP.NET MVC syntax

#### checkbox example

```
<div class="checkbox icheck-primary">
    @Html.CheckBoxFor(m => m.SomeProperty, new { id = "someCheckboxId" })
    <label for="someCheckboxId">Clieck to check</label>
</div>
```

#### radio buttons example

```
<div class="radio icheck-primary">
    @Html.RadioButtonFor(m => m.SomeProperty, SomeValue1, new { id = "someRadioId1" }) 
    <label for="someRadioId1">Option 1</label>
</div>
<div class="radio icheck-primary">
    @Html.RadioButtonFor(m => m.SomeProperty, SomeValue2, new { id = "someRadioId2" })
    <label for="someRadioId2">Option 2</label>
</div>
```

## License

icheck-bootstrap released under the [MIT license](https://github.com/bantikyan/icheck-bootstrap/blob/master/LICENSE). Feel free to use it in personal and commercial projects.
