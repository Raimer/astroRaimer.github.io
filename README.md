## Welcome to My Personal Site

I build this homepage to share my views on the recent astrophysical studies and my daily live. The process of building such a homepage can be summarized as the following steps:

### First Step
Build a new repository and add [Just the Docs](https://github.com/pmarsceill/just-the-docs) to your Jekyll site’s ```_config.yml``` as a remote theme:
```
remote_theme: pmarsceill/just-the-docs
```

### Second Step
Edit the ```_config.yml```, ```index.md``` and add other pages in ```./docs```. More informations about this theme are in the [documentation](https://pmarsceill.github.io/just-the-docs/). Here I summary some tips for a quick start:

#### Scheme Color
Create your own ```.scss``` file in ```./_sass/color_schemes```. For example, I add a color scheme named ```blue``` as
```scss
$link-color: #3A66D2;
```
To use the color scheme you make, only set the color_scheme parameter in your site’s ```_config.yml``` file:
```yaml
color_scheme: blue
```

#### License Statement
By default, "This site uses Just the Docs, a documentation theme for Jekyll." is claimed at bottom of page. If you want to add the license of site, you can change the default statement in ```./_layouts/default.html```.

### License
This homepage is based on [Just the Docs](https://github.com/pmarsceill/just-the-docs), a documentation theme for [Jekyll](https://jekyllrb.com). The content on this site is licensed under a [CC BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/). 
