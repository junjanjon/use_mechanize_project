
```
$ bundle exec irb -rnokogiri

body = `curl http://example.com/`
Nokogiri.parse(body)
```


```
$ bundle exec irb -rmechanize

client = Mechanize.new
client.get('http://example.com/')
```
