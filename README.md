
# cyberdojo/collector docker image

A micro-service for [cyber-dojo](http://cyber-dojo.org).
Every hour it garbage-collects docker volumes created by
[cyberdojo/runner](https://github.com/cyber-dojo/runner)
which have not been used for 24 hours.
