# hexo-deployer-s3

Amazon S3 deployer plugin for [Hexo](http://hexo.io/)

## Installation

``` bash
$ npm install hexo-deployer-s3 --save
```

## Options

You can configure this plugin in `_config.yml`.

``` yaml
# You can use this:
deploy:
  type: s3
  bucket: <S3 bucket>
  aws_key: <AWS id key>  // Optional, if the environment variable `AWS_ACCESS_KEY_ID` is set
  aws_secret: <AWS secret key>  // Optional, if the environment variable `AWS_SECRET_ACCESS_KEY` is set
  concurrency: <number of connections> // Optional
  region: <region>  // Optional, see https://github.com/LearnBoost/knox#region
```

## Contributors

- Josh Strange ([joshstrange](https://github.com/joshstrange); original implementation)

## License

MIT
