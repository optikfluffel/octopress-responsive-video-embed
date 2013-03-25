# Octopress responsive video embed

Helps you embed Youtube and Vimeo videos responsively to your Octopress since 2012. Also supports embeds from TrailerAddict and Ooyala (video player used by The Verge and Polygon).

## How to use it?

There are 3 easy steps.

1. Add ```youtube.rb```, ```vimeo.rb```, ```traileraddict.rb```, ```ooyala.rb``` to your ```plugin``` folder.
2. Copy the content from ```rve-styles.css``` to your own stylesheet or just add it to your template. (or to keep everything in sass, see below)
3. Now you can easily embed videos using only the ```id``` like this:

```markdown
# Vimeo example

{% vimeo 20241459 %}

# Youtube example

{% youtube QWq0bSvc31A %}

# TrailerAddict example

{% traileraddict 66840 %}

# Ooyala example (needs two id's, pbid and ec)

{% ooyala 2ff6d6fff2b2457bb9ea2cfcf77dc25b 1xaW1nYTqi1Z1ZiLwcJ2qSSrg94NAtkQ %}

```

## Optional - keep everything in sass

1. Copy ```_rve.scss``` to ```/sass/custom```
2. Add ```@import "custom/rve"``` to  ```/sass/screen.scss```

## Kudos

Thanks go to Anders M. Andersen for his [blogpost about responsive embeds](http://amobil.se/2011/11/responsive-embeds/) and to Portway Point for their [Jekyll Youtube Liquid Template Tag Gist](http://www.portwaypoint.co.uk/jekyll-youtube-liquid-template-tag-gist/)

## Edorsement

If you like it feel free to endorse me: [![](http://api.coderwall.com/optikfluffel/endorsecount.png)](http://coderwall.com/optikfluffel)
