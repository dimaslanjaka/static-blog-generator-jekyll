https://gist.github.com/ryanburnette/6107142

> This is a [Jekyll](http://jekyllrb.com) plugin for creating YouTube or Vimeo embed codes.

#### Usage

Put the plugin file `video-embeds.rb` in your `_plugins` directory. Create a tag specifying the type
of video you want to embed with the first required argument, the video id.

```liquid
{% youtube ab1234ab1 %}
```

You can also specify a height and width. If you do not, it defaults to 500 x 281.

```liquid
{% vimeo 123456789 1920 1080 %}
```