# BOOTSTRAP-BUCHELI-COURSE-SETTING-COLUMN-WIDTHS

In the previous exercise, we saw how columns take on a default width based on the size of the row. However, Bootstrap gives us more customization options so that we can make columns of varying widths. Take a look at 4th and 5th row of the diagram for examples of rows containing columns of differing widths:

![](https://content.codecademy.com/courses/learn-bootstrap-4/12-col-grid-diff-widths.svg)

We can decide the width of a column by appending a hyphen and a number to the "col" class like so:

```
<div class="col-8">
  <p>This is the width of 8 columns.</p>
</div>
```

In our example, our row still has 4 columns worth of space. If we decide to add an adjacent column, we could also set our desired width like so:

```
<div class="row">
  <div class="col-8">
    <p>This is the width of 8 columns.</p>
  </div>
  <div class="col-4">
    <p>This has the width of 4 columns.</p>
  </div>
</div>
```

If we didn’t specify a desired width for the second column, it would still resize itself to fill in the remaining space in the row. But, by adding "-4", we make our code more readable and allow other developers to clearly know our intentions.

Now let’s customize the widths of our columns!
