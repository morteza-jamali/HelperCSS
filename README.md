<h1 align="center">
  <img src="https://raw.githubusercontent.com/morteza-jamali/HelperCSS/master/logo.png" alt="HelperCSS">
</h1>
<h1 align="center">
  HelperCSS
</h1>

<p align="center">
<img src="https://img.shields.io/badge/version-1.0.0-orange" alt="version">
<img src="https://img.shields.io/badge/license-Apache--2.0-yellowgreen" alt="license">
<img src="https://img.shields.io/badge/size-120%20KB-lightgrey" alt="size">
</p>

**HelperCSS** is a class based CSS library that provide a good way for styling elements using class .

<div align="center" style="padding-top:60px;padding-bottom:30px">
<div style="width:100px;height:100px;background-color:red;border-top-left-radius:50%;border-bottom-right-radius:50%;border:2px solid blue;padding-top:35px;color:white;border-top:0">Hello</div>
</div>

I want to create top element using Bootstrap class and CSS styles
```html
<div class="bg-danger border border-top-0 border-primary rounded-circle text-white pt-3" 
	 style="border-top-right-radius:0 !important; border-bottom-left-radius:0 !important; border-width: 2px">
	Hello
</div>
```

Oops! . I have many class and css styles in here that can confuse me . So , i use HelperCSS .

```html
<div class="color:b:red border:2:blue border:t:0  color:f:white padding:t:3 border-radius:tl:br:200x" >
	Hello
</div>
```

That's pretty cool !


- [Install](#install)
- [Usage](#usage)
- [Modules](#modules)
  - [Align](#align_module)
  - [Border](#border_module)
  - [Color](#color_module)
- [Development](#development)
- [License](#license)