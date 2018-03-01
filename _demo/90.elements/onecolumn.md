---
title: Elements
---

Lots to be styled and customised including basic elements like lists.
Taken from theme Massively.
Fontawesome.
Requires markdown extra

<!-- Text stuff -->
## Text

This is <b>bold</b> and this is **strong**. This is <i>italic</i> and this is _emphasized_.
This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.
This is <u>underlined</u> and this is code: `for (;;) { ... }`.
Finally, this is a [link](#).

- - - - - - -

## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

- - - - - - -

<header markdown="1">
## Heading with a Subtitle

Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

<header markdown="1">
### Heading with a Subtitle

Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

<header markdown="1">
#### Heading with a Subtitle

Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

- - - - - - -

<!-- Lists -->
## Lists

<div class="row">
<div class="6u 12u$(small)" markdown="1">

### Unordered

* Dolor pulvinar etiam.
* Sagittis lorem eleifend.
* Felis feugiat dolore viverra.
* Dolor pulvinar etiam.

### Alternate

<ul class="alt">
	<li>Dolor pulvinar etiam etiam.</li>
	<li>Sagittis adipiscing eleifend.</li>
	<li>Felis enim dolore viverra.</li>
	<li>Dolor pulvinar etiam etiam.</li>
</ul>
</div>

<div class="6u$ 12u$(small)" markdown="1">

### Ordered

1. Dolor pulvinar etiam.
1. Etiam vel felis at viverra.
1. Felis enim feugiat magna.
1. Etiam vel felis nullam.
1. Felis enim et tempus.

### Icons

<ul class="icons">
	<li><a href="#" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
	<li><a href="#" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
	<li><a href="#" class="icon fa-instagram"><span class="label">Instagram</span></a></li>
	<li><a href="#" class="icon fa-github"><span class="label">Github</span></a></li>
	<li><a href="#" class="icon fa-dribbble"><span class="label">Dribbble</span></a></li>
</ul>

<ul class="icons alt">
	<li><a href="#" class="icon alt fa-twitter"><span class="label">Twitter</span></a></li>
	<li><a href="#" class="icon alt fa-facebook"><span class="label">Facebook</span></a></li>
	<li><a href="#" class="icon alt fa-instagram"><span class="label">Instagram</span></a></li>
	<li><a href="#" class="icon alt fa-github"><span class="label">Github</span></a></li>
	<li><a href="#" class="icon alt fa-dribbble"><span class="label">Dribbble</span></a></li>
</ul>

</div>
</div>

### Definition

Item 1
:	Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent.

Item 2
:	Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent.

Item 3
:	Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent.

### Actions

<ul class="actions">
	<li><a href="#" class="button special">Special</a></li>
	<li><a href="#" class="button">Default</a></li>
</ul>
<ul class="actions small">
	<li><a href="#" class="button special small">Small</a></li>
	<li><a href="#" class="button small">Small</a></li>
</ul>
<div class="row">
	<div class="6u 12u$(small)">
		<ul class="actions vertical">
			<li><a href="#" class="button special">Default</a></li>
			<li><a href="#" class="button">Default</a></li>
		</ul>
	</div>
	<div class="6u 12u$(small)">
		<ul class="actions vertical small">
			<li><a href="#" class="button special small">Small</a></li>
			<li><a href="#" class="button small">Small</a></li>
		</ul>
	</div>
</div>
<div class="row">
	<div class="6u 12u$(small)">
		<ul class="actions vertical">
			<li><a href="#" class="button special fit">Default</a></li>
			<li><a href="#" class="button fit">Default</a></li>
		</ul>
	</div>
	<div class="6u$ 12u$(small)">
		<ul class="actions vertical small">
			<li><a href="#" class="button special small fit">Small</a></li>
			<li><a href="#" class="button small fit">Small</a></li>
		</ul>
	</div>
</div>

- - - - - - -

<!-- Blockquote -->
## Blockquote

> Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis.

- - - - - - -

## Table

### Default

<!-- damn, there's no Markdown Extra for the <tfoot> element, so good ol' HTML here for the table -->
<div class="table-wrapper">
	<table>
		<thead>
			<tr>
				<th>Name</th>
				<th>Description</th>
				<th>Price</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item 1</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 2</td>
				<td>Vis ac commodo adipiscing arcu aliquet.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 3</td>
				<td> Morbi faucibus arcu accumsan lorem.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 4</td>
				<td>Vitae integer tempus condimentum.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 5</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
		</tbody>
		<tfoot>
			<tr>
				<td colspan="2"></td>
				<td>100.00</td>
			</tr>
		</tfoot>
	</table>
</div>

### Alternate

<div class="table-wrapper">
	<table class="alt">
		<thead>
			<tr>
				<th>Name</th>
				<th>Description</th>
				<th>Price</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item 1</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 2</td>
				<td>Vis ac commodo adipiscing arcu aliquet.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 3</td>
				<td> Morbi faucibus arcu accumsan lorem.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 4</td>
				<td>Vitae integer tempus condimentum.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 5</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
		</tbody>
		<tfoot>
			<tr>
				<td colspan="2"></td>
				<td>100.00</td>
			</tr>
		</tfoot>
	</table>
</div>
