See [this repository](https://github.com/chardskarth/gollum-behind-nginx)

# Setup

Add to your hosts file (for the sake of the demo)
```shell
sudo su
echo "127.0.0.1 local.chardskarth.me\n127.0.0.1 localgollum.chardskarth.me" >> /etc/hosts
```

# Run
docker compose up


# Test
http://localhost:3003/gollum/create/Home -> works (normal scenario)
http://localgollum.chardskarth.me:3003/ -> not working :(
http://local.chardskarth.me:3003/gollum -> not working :(

