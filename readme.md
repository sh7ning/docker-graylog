see: http://docs.graylog.org/en/3.0/pages/installation/docker.html

```
echo -n "Enter Password: " && head -1 </dev/stdin | tr -d '\n' | sha256sum | cut -d" " -f1
```
