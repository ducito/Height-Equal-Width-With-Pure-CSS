# Height-Equal-Width-With-Pure-CSS
Set height equal width with pure css

```
<div class="box"> That's it </div>
```

```
 <style>
        .box{
            width: 20vw;
            display: inline-block;
            background-color: #55cc33
        }
        .box:before {
            content: "";
            display: block;
            padding-top: 100%;
        }
    </style>
```


[@duccuimia](https://duc.ninja)
