FROM gcr.io/kaniko-project/executor:v1.8.1 as kaniko
FROM busybox:latest
MAINTAINER zzulyj<zzulyj@qq.com.com>
COPY --from=kaniko /kaniko /kaniko
ENTRYPOINT ["/bin/sh"]
