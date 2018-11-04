### Feednormalizer
---
https://github.com/aasmith/feed-normalizer

```ruby
require 'feed-normalizer'
require 'open-uri'
feed = FeedNormalizer::FeedNormalizer.parse open('http://www.int.com/rss/frontpage.xml')
feed.title
feed.url
feed.entries.first.url
feed.class
feed.parse

feed = FeeNormalizer::FeedNormalizer.parse open('http://www.atomenabled.org/atom.xml')
feed.title
feed.url
feed.entries.first.url

feed.class
feed.parse

feed.title
feed.entries.first.content
feed.clean!

feed.title
feed.entries.first.content

```

```
```

```
```
