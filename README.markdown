# Octopress responsive video embed

Helps you embed Youtube and Vimeo videos responsively to your Octopress since 2012. Also supports embeds from TrailerAddict, Ooyala (video player used by The Verge and Polygon) and Dailymotion.

## How to use it?

There are 3 easy steps.

1. Add ```youtube.rb```, ```dailymotion.rb```, ```vimeo.rb```, ```traileraddict.rb```, ```ooyala.rb``` to your ```plugin``` folder.
2. Copy the content from ```rve-styles.css``` to your own stylesheet or just add it to your template. (Or, to keep everything in sass, see below)
3. Now you can easily embed videos using only the ```id``` like this:

```markdown
# Vimeo example

{% vimeo 20241459 %}
```

```ruby
# Youtube example

{% youtube QWq0bSvc31A %}
```

```ruby
# TrailerAddict example

{% traileraddict 66840 %}
```

```ruby
# Ooyala example (needs two id's, pbid and ec)

{% ooyala 2ff6d6fff2b2457bb9ea2cfcf77dc25b 1xaW1nYTqi1Z1ZiLwcJ2qSSrg94NAtkQ %}
```

```ruby
# Dailymotion example

{% dailymotion xme2zs %}
```

## Optional - keep everything in sass

1. Copy ```_rve.scss``` to ```/sass/custom```
2. Add ```@import "custom/rve"``` to  ```/sass/screen.scss```

## Kudos

### Starting Point

Thanks go to Anders M. Andersen for his [blogpost about responsive embeds](http://amobil.se/2011/11/responsive-embeds/) and to Portway Point for their [Jekyll Youtube Liquid Template Tag Gist](http://www.portwaypoint.co.uk/jekyll-youtube-liquid-template-tag-gist/).

### Contributors

Special thanks go to:

* [@geetotes](https://github.com/geetotes) for the Trailer Addict support
* [@DennisLaumen](https://github.com/DennisLaumen) for the Ooyala support
* [@jcbedier](https://github.com/jcbedier) for the Dailymotion support
* [@bhean](https://github.com/bhean) for making it work with SSL enabled sites

## Endorsement

If you like it, feel free to endorse me: [![](http://api.coderwall.com/optikfluffel/endorsecount.png)](http://coderwall.com/optikfluffel)
