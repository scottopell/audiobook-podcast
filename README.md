# Private Podcast Template

I use this to maintain a private podcast feed full of audio that I want to be
able to listen to easily on my phone and share easily.

One example use case might be audiobooks.

This is missing **2** critical components:

1. `_data/secrets.yaml`
```yaml
base_url: 'http://example.com'
```

1. `_data/books.yaml`
```yaml
- title: "Some Book"
  date: 2016-04-11
  duration: "07:23:44"
  length: "442169005"
  short_description: "whatever"
  aac_asset_link: "http://example.com/book.m4a"
  tags: [book]
```
