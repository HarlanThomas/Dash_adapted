    # Dash_adapted
Adaption of dash.js to connect mediaplayer with customized algo

To show process bar in the dash player,
    you should not only download the folder ``` dash-if-reference-player```into ```dash.js/sample```,
    
But also add the css declare of process bar 
Open ```dash.js/contrib/akamai/controlbar/controlbar.css ``` then add the following code paragraph into the 74 row beneath ```.volume{...}```

```
.processbar{
    float: right;
    width: 250px;
}
```


<img src="https://github.com/HarlanThomas/Dash_adapted/tree/master/dash-if-reference-player/19deecamp.wmv" alt="show" />
