# docker-jelastic-cli

# Running

In Gitlab CI

```yaml
deploy:
  image: mwienk/jelastic-cli
  script:
    - /root/jelastic/users/authentication/signin --login $LOGIN --password $PASSWORD --platformUrl $PLATFORM_URL
    - /root/jelastic/environment/control/getenvs
```
