
In operation, we may need to copy one redis db to another. rdb is an awesome
mechanism but if you're migrating things in/out of services like ElastiCache.
It's just not on-the-fly.

Other people suggested some good approaches. Here are some ready-to-use codes
in python.
