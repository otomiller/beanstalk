# Beanstalk



## Logs

```
tail -f /var/log/cfn-init.log

2022-12-13 19:54:15,065 [INFO] -----------------------Starting build-----------------------
2022-12-13 19:54:15,072 [INFO] Running configSets: Infra-EmbeddedPostBuild
2022-12-13 19:54:15,075 [INFO] Running configSet Infra-EmbeddedPostBuild
2022-12-13 19:54:15,078 [INFO] Running config postbuild_0_synectics_web_dev
2022-12-13 19:55:18,988 [INFO] Command 01initproject succeeded
2022-12-13 19:55:21,418 [INFO] Command disable_remi succeeded
2022-12-13 19:55:21,883 [INFO] Command enable_php_81 succeeded
2022-12-13 19:55:28,383 [INFO] Command install_epel succeeded
2022-12-13 19:55:54,226 [INFO] Command install_php succeeded
2022-12-13 19:55:54,812 [INFO] Command remove_php succeeded
2022-12-13 19:55:54,910 [INFO] Command start_php-fpm succeeded
2022-12-13 19:55:58,407 [INFO] Command yum_update succeeded
2022-12-13 19:55:58,408 [INFO] ConfigSets completed
2022-12-13 19:55:58,409 [INFO] -----------------------Build complete-----------------------

```

/var/log/eb-engine.log = Platform Logs
/var/log/nginx/ = Nginx Logs

## Official Documentation
* https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html
* https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/platforms-linux-extend.html#platforms-linux-extend.proxy.nginx
