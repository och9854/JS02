# Intro
---

<img width="100%" alt="image" src="https://user-images.githubusercontent.com/78291267/191666002-2c66ff35-9bfd-4552-bf20-b992bd03cb57.png">

When you type link:css, it will automatically writes this code below 

```HTML
<link rel="stylesheet" href="style.css"> 
```

## Use Bootstrap
---

Bootstrap is a free, open source front-end development framework for the creation of websites and web apps.

[Bootstrap link](https://getbootstrap.com/)

### How to use
---

After choosing version, in quick start

1. Copy CSS one line upper than **Style.css**
```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
```

2. Copy JS Bundle at the end of body tag
 
 ```HTML
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script> 
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
```


# Search in Bootstrap
---

Go to[bootstrap website](https://getbootstrap.com/docs/5.2/getting-started/introduction/) and search what you want.

Let us say we want a prettier button than just a simple button from HTML. We can search "button" in docs and choose what we want.

<img width="100%" alt="image" src="https://user-images.githubusercontent.com/78291267/191672797-c1a6dd50-d4f3-4e5a-8bbd-c97ec4e9f703.png">

# When you click "Start Test" Button
---

When you click start button, the intro should be disappeared and show the question lists. To do that, you have to make an question class and make it invisible until you click the button. Make an function which runs when button is onclick.

```JS
// JS
    <script>
        function start() {
            $('.start').hide();
            $(".question").show();
        }

    </script>
```

```CSS
.question {
    display: none;
}
```

```HTML
<!-- Start button and question article -->
<article class="start">
    <h1 class="mt-5">Find My Serengeti Animal </h1>
    <button type="button" class="btn btn-primary mt-5" onclick="start();">Start Test</button>
</article>

<article class="question">
    <h2> Question </h2>
</article>
```


# Make an progress bar
---

Progress bar is also in [Bootstrap website](https://getbootstrap.com/docs/5.2/components/progress/#multiple-bars). 

# Value Change
---


```JS
$("#A").click(function(){
    var type = $("#type").val();
    var preValue = $("#"+type).val();
    $("#"+type).val(parseInt(preValue)+1);
});

```

# SEO(Search Engine Optimization)
---

1. On-page SEO (HTML, Contents, Metatag etc)
2. Off-page SEO (Num of Backlink)

## TIP: Use Search Advisor
---

[NAVER Search Advisor](https://searchadvisor.naver.com/) helps you to make your website better. It recommends variable SEO strategies.


# Completing Service
---

Let's add some contents and edit css file more prettier. 