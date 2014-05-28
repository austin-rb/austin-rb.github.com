# Austin.RB Website

## Running It Locally

```
$ bundle
$ foreman start
$ open http://localhost:4000/
```

## Updating For New Meetings

* Create a new file in the `_posts` directory, with YAML front matter along the lines of:

  ``` yaml
  layout: post
  title: "January Meeting - A Title Goes Here"
  date: 2012-1-17
  ```
* Add details of the meeting to the newly-created post, including date, time, and location, as well as a short description of the talk for the evening, and an acknowledgement of the sponsor (you did find a sponsor for the event, didn't you? `^_-`)

* Update `_config.yml` to match the next meeting information. In the past, for the `url` key, we've used a link to an event on [Plancast](http://plancast.com/).

* `git commit -a -m "Adding post for #{month} meeting"`

* `git push`

## Group Contacts

 - Brad Fults (brad@austinrb.org)
 - Mando Escamilla (mando.escamilla@gmail.com)
 - Tim Tyrell (ttyrrell@gmail.com)
 - Trevor Rosen (trevor@catapult-creative.com)
