# Bootstrap!

Less need for the @media querie!

Seems like the slim build on JQuery doesn't work too well, we should use min version without slim.

It's predesigned code, sorted in all kinds of components to easily adjust use and adjust.

*In the head of the file insert the bootstrap stylesheet:* <br>
``` 
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
```

*At the end of body just insert:* <br>
```<script src="http://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>```

```<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>```

```<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>```

As with everything you just gotta play around to understand what's going on!<br>
Using additional container, and tailoring their attributes to your needs is the go to for disobedient img!

The components used for now are:
* https://getbootstrap.com/docs/4.4/components/card/#card-columns
* https://getbootstrap.com/docs/4.4/components/carousel/#with-controls
* https://getbootstrap.com/docs/4.4/components/collapse/
* https://getbootstrap.com/docs/4.4/components/forms/
* https://getbootstrap.com/docs/4.4/components/modal/
* https://getbootstrap.com/docs/4.0/components/navbar/
* https://getbootstrap.com/docs/4.4/components/progress