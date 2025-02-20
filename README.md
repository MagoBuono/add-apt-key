# add-apt-key

I got tired of not being able to use `apt-key adv --recv-key` the old fashioned way, so I wrote this script to get keys by ID and add `[signed-by=...]` to the .list file

So, something like this:
```
wget https://raw.githubusercontent.com/MagoBuono/add-apt-key/refs/heads/main/add-apt-key -O /usr/local/bin
chmod +x /usr/local/bin
```
to use it.
