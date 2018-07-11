---
title: Change the Position of Overlapping Elements with the z-index Property
---
## Change the Position of Overlapping Elements with the z-index Property

## Example

Set the z-index for an image:

```html
img {
    position: absolute;
    left: 0px;
    top: 0px;
    z-index: -1;
}
```

## Definition and Usage

The ```html z-index ``` property specifies the stack order of an element.

An element with greater stack order is always in front of an element with a lower stack order.

<b>Note:</b> ```html z-index ``` only works on positioned elements (position:absolute, position:relative, or position:fixed).

<table>
  <tr>
    <th style="width:25%">Default value:</th>
    <td>auto</td>
  </tr>
  <tr>
    <th>Inherited:</th>
    <td>no</td>
  </tr>
  <tr>
    <th>Animatable:</th>
    <td>yes</td>
  </tr>
  <tr>
    <th>Version:</th>
    <td>CSS2</td>
  </tr>
  <tr>
    <th>JavaScript syntax:</th>
    <td>  <i>object</i>.style.zIndex="-1"</td>
  </tr>
</table>

## Browser Support

The numbers in the table specify the first browser version that fully supports the property.

<table class="browserref notranslate">
  <tbody><tr>
    <th style="width:20%;font-size:16px;text-align:left;">Property</th>
    <th style="width:16%;" >Chrome</th>
    <th style="width:16%;" >Edge</th>
    <th style="width:16%;" >Firefox</th>
    <th style="width:16%;" >Safari</th>
    <th style="width:16%;" >Opera</th>                
  </tr>
  <tr>
    <td style="text-align:left;">z-index</td>
    <td>1.0</td>
    <td>4.0</td>
    <td>3.0</td>
    <td>1.0</td>
    <td>4.0</td>
  </tr>
  </table>
    
## CSS Syntax

```html
z-index: auto|number|initial|inherit;
```
<h2>Property Values</h2>

<table>
<tr>
    <th style="width:14%">Value</th>
    <th>Description</th>
  </tr>  
  <tr>
    <td>auto</td>
    <td>Sets the stack order equal to its parents. This is default</td>                   
  </tr>
  <tr>
    <td><i>number</i></td>
    <td>Sets the stack order of the element. Negative numbers are allowed</td>                        
  </tr>
  <tr>
    <td>initial</td>
    <td>Sets this property to its default value.</td>                          
    </tr>
  <tr>
    <td>inherit</td>
    <td>Inherits this property from its parent element. </td>
    </tr>
  </table>

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->


