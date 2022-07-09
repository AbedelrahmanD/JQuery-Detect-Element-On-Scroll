<h1>
    JQuery Detect Element On Scroll
</h1>
<p>
    This plugin allows you detect the current element in the view port while the user is scrolling, and you can call functions when a specif element appear in the view port
</p>
<h1>
    Installation
</h1>
<p>
    Include the scripts
</p>

```
<script src="jquery.min.js"></script>
<script src="scroll_detector.js"></script>

```
<h1>
    Usage
</h1>
<p>
    Add <code>data-scroll</code> to the element you want to detect on scroll
</p>

```
<div data-scroll> example1</div>
<div></div>
<div data-scroll> example2</div>
```
<h1>
    Getting Current Element In View Port
</h1>
<p>
    The current element in view will have <code>data-in-view</code> attribute, you can select it by
</p>

```
$("[data-in-view]")
```

<h1>
    Call Function When Element Appear
</h1>
<p>
    Add function to <code>data-scroll</code>
</p>

```
<div data-scroll="myFunction(1)"> example1</div>
<div></div>
<div data-scroll="myFunction(2)"> example2</div>
```

<h1>
    Adding Offset
</h1>
<p>
    Add offset with <code>data-scroll-offset</code>
</p>

```
<div data-scroll="myFunction(1)" data-scroll-offset="500"> example1 </div>
<div></div>
<div data-scroll="myFunction(2)" data-scroll-offset="1000"> example2</div>
```

<h1>
    Styling Element In View
</h1>
<p>
    Add css to element with attribute <code>data-in-view</code>
</p>

```
<style>
    [data-in-view] {
        background-color: crimson;
    }
</style>
```
