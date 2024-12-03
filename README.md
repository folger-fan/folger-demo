# folger-demo
folger-demo

demo

[[TOC]]

<TOC />

# a header

## aa header

# b header

## bbheader


```yaml{5,8}
main:
  push:
    - stages:
      - name: echo file
        image: tencentcom/ssh
        settings:
          host: xx.xx.xx.xxx
          username: root
          password: xxxx
          port: 22
          script:
            - echo hello world
            - echo test > ~/test.txt
```
