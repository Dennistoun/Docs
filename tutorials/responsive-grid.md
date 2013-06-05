# Responsive Grid #

PageLines DMS encompasses a completely responsive grid system based on [Bootstrap](http://twitter.github.io/bootstrap/) that contains 12 columns, or "spans". The grid can be used virtually anywhere. Mark it up in a post, in a page, or wherever you need structured, responsive content.

The responsive grid system uses percents instead of pixels for column widths, ensuring proper proportions for key screen resolutions and devices.

<div class="docs-grid">
    <div class="row-fluid show-grid">
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
        <div class="span1">1</div>
    </div>
    <div class="row-fluid show-grid">
		<div class="span2">2</div>
		<div class="span2">2</div>
		<div class="span2">2</div>
		<div class="span2">2</div>
		<div class="span2">2</div>
		<div class="span2">2</div>
	</div>
	<div class="row-fluid show-grid">
		<div class="span3">3</div>
		<div class="span3">3</div>
		<div class="span3">3</div>
		<div class="span3">3</div>
	</div>
    <div class="row-fluid show-grid">
        <div class="span4">4</div>
        <div class="span4">4</div>
        <div class="span4">4</div>
    </div>
    <div class="row-fluid show-grid">
		<div class="span5">5</div>
		<div class="span2">2</div>
		<div class="span5">5</div>
	</div>
	<div class="row-fluid show-grid">
		<div class="span6">6</div>
		<div class="span6">6</div>
	</div>
	<div class="row-fluid show-grid">
		<div class="span7">7</div>
		<div class="span5">5</div>
	</div>
    <div class="row-fluid show-grid">
    	<div class="span8">8</div>
    	<div class="span4">4</div>
    </div>
    <div class="row-fluid show-grid">
		<div class="span9">9</div>
		<div class="span3">3</div>
	</div>
	<div class="row-fluid show-grid">
		<div class="span10">10</div>
		<div class="span2">2</div>
	</div>
    <div class="row-fluid show-grid">
        <div class="span11">11</div>
        <div class="span1">1</div>
    </div>
    <div class="row-fluid show-grid">
        <div class="span12">12</div>
    </div>
</div>

## How to use ##

### Basic Example ###

<div class="row-fluid">
<div class="span6">
<?prettify?>
<pre class="prettyprint linenums">
	<div class="row">
    	<div class="span4">Span 4</div>
    	<div class="span8">Span 8</div>
	</div>
</pre>
</div>
<div class="span6">
	<div class="row-fluid show-grid">
		<div class="span4">Span 4</div>
		<div class="span8">Span 8</div>
	</div>
</div>
</div>

### Nested Example ###

<div class="row">
	<div class="span6 zmb">
		<pre class="prettyprint linenums"></pre>
	</div>
	<div class="span6">
		<div class="row show-grid">
			<div class="span4">Span 4</div>
			<div class="span8">
			Span 8
		<div class="row">
			<div class="span6 zmb" style="background: #CCC">Span 6</div>
			<div class="span6 zmb" style="background: #CCC">Span 6</div>
		</div>
	</div>
	</div>
</div>
</div>