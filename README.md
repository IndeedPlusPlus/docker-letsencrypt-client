# Docker Let's Encrypt Client #

## Usage ##

Mount your config directory and specify with `--config-dir` flag.

For example, if you want to set the config directory to `/opt/letsencrypt`, to perform a renewal, you can use the following command.

```bash
docker run -it --rm -v /opt/letsencrypt:/opt/letsencrypt indeedplusplus/letsencrypt --config-dir /opt/letsencrypt renew
```

