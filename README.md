# Semantic UI Responsive Menu

This is a functional, responsive Bootstrap-like Semantic-UI menu — **the missing component in Semantic-UI** that requires _no additional menu_ for mobile. 

![f2bbdb54088538d66902fbc3f5dc834b.png](https://pictr.com/images/2018/06/24/f2bbdb54088538d66902fbc3f5dc834b.png)

CSS can be found at `src/site/globals/site.overrides`

## Usage

```
<a class="is-menu" href="#menu"><i class="bars icon"></i></a>

<div id="menu" class="ui top fixed menu">
    <div class="ui container">
        <div class="item">...</div>
        .
        .
    </div>
</div>
```

## js

```
$(document).ready(function() {
    $('.is-menu').on('click', function(){
        $('i', this)
            .toggleClass('window minimize outline')
        ;
        $('#menu.ui.menu')
            .transition('slide down')
        ;
    });
});
```

## TBD

- [x] First-level menu
- [ ] Second-level menu — _work-in-progress_

           
## Acknowledgments

1. 
2. 
3. 
