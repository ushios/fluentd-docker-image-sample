fluentd-docker-image-sample
===========================
[fluent/fluentd-docker-image](https://github.com/fluent/fluentd-docker-image) sample

@see [fluent/fluentd-docker-image/Dockerfile.sample](https://github.com/fluent/fluentd-docker-image/blob/master/Dockerfile.sample)

# Run

```bash
$ docker-compose build
$ docker-compose up -d
```

## Testing

```bash
$ docker-compose logs -ft fluent
```

```bash
$ curl http://localhost:8888/foo.bar -F 'json={"hoge":"fuga"}'
```
