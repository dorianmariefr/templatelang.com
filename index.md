---
title: Template and Code Documentation
layout: default
---

## Code

```ruby
true

false
```

### Hacker News

```ruby
title.include?("Ruby")

title.downcase.include?("react")

keywords.include?("Bitcoin")
```

### Twitter

```ruby
text.include?("#ruby")

retweets > 100

likes > 50

followers >= 1000
```

## Template

### Hacker News

```ruby
{items.first.title}

{items.each do |item|
  puts(item.title)
  puts
  puts(item.url)
  puts
  puts(item.comments_url)
  puts
end
nothing}

{pipeline.url}
```

### Twitter

```ruby
{items.first.text}

{items.each do |item|
  puts(item.text)
  puts
  puts(item.url)
  puts
end
nothing}

{pipeline.url}
```

## Examples of items

### Hacker News

```js
{
  "external_id": "34308045",
  "pipeline": {
    "id": 20,
    "slug": "tanstack-and-react-query-hacker-news-new-stories-to-email",
    "name": "React Query",
    "url": "/pipelines/tanstack-and-react-query-hacker-news-new-stories-to-email"
  },
  "id": "34308045",
  "url": "https://tkdodo.eu/blog/type-safe-react-query",
  "host": "tkdodo.eu",
  "href": "https://tkdodo.eu/blog/type-safe-react-query",
  "path": "/blog/type-safe-react-query",
  "score": 1,
  "title": "Type-Safe React Query",
  "domain": "tkdodo.eu",
  "user_id": "thebitofmyheart",
  "keywords": [
    "Type",
    "Safe",
    "React",
    "Query"
  ],
  "protocol": "https",
  "user_url": "https://news.ycombinator.com/user?id=thebitofmyheart",
  "domain_url": "https://news.ycombinator.com/",
  "comments_url": "https://news.ycombinator.com/item?id=34308045",
  "comments_count": 1,
  "domain_with_path": "tkdodo.eu"
}
```

### Twitter

```js
{
  "external_id": "1615497362646106112",
  "pipeline": {
    "id": 47,
    "slug": "paul-graham-s-tweets",
    "name": "Paul Graham's Tweets",
    "url": "/pipelines/paul-graham-s-tweets"
  },
  "id": "1615497362646106112",
  "url": "https://twitter.com/paulg/status/1615497362646106112",
  "lang": "en",
  "text": "@BillyM2k \"Vis-a-vis\" is a tell of an even worse kind than \"furthermore.\" It's conversational spackle, used when pe… https://t.co/gEY9W3Yu8D",
  "likes": 56,
  "quote?": false,
  "user_id": "183749519",
  "retweets": 2,
  "user_url": "https://twitter.com/paulg",
  "user_name": "Paul Graham",
  "created_at": "2023-01-17T23:52:40.000Z",
  "user_likes": 0,
  "user_handle": "paulg",
  "user_listed": 16079,
  "user_tweets": 33105,
  "user_friends": 711,
  "user_location": "null",
  "user_verified": true,
  "user_followers": 1630783,
  "user_image_url": "https://pbs.twimg.com/profile_images/1824002576/pg-railsconf_normal.jpg",
  "user_protected": false,
  "user_created_at": "2010-08-27T20:13:59.000Z",
  "user_description": "null",
  "user_profile_url": "https://twitter.com/paulg",
  "user_background_image_url": "https://abs.twimg.com/images/themes/theme1/bg.png"
}
```
