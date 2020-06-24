# ansible-jekyll-install

Install blog.koehntopp.info skeleton using ansible.

- Assumes Ubuntu 20.04
  - I am using a scaleway dev instance for testing.
- Assumes we do not care and build in /root.
- Installs Jekyll
- Installs type-on-strap

When finished:

```bash
# cd blog
# bundle exec jekyll serve
```

Listens on 127.0.0.1:4000, so `ssh root@ip -L 4001:localhost:4000`

