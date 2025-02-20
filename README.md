# add-apt-key

I got tired of not being able to use `apt-key adv --recv-key` the old fashioned way, so I wrote this script to get keys by ID and add `[signed-by=...]` to the .list file

So, something like this:
```
curl -s https://raw.githubusercontent.com/MagoBuono/add-apt-key/refs/heads/main/add-apt-key -o /usr/local/bin/add-apt-key
chmod +x /usr/local/bin/add-apt-key
```
to use it.
