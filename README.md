# Webpacker with custom rails env like staging or demo

```bash
RAILS_ENV=staging bundle exec rails assets:precompile
```

```bash
RAILS_ENV=staging bundle exec rails webpacker:compile
```

```bash
RAILS_ENV=staging NODE_ENV=production ./bin/webpack
```

