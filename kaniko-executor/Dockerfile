FROM gcr.io/kaniko-project/executor:latest as kaniko
FROM busybox:latest
MAINTAINER zzulyj<zzulyj@qq.com.com>
COPY --from=kaniko /kaniko /kaniko
ENTRYPOINT ["/bin/sh"]
