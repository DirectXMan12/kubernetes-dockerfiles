FROM fedora:22
MAINTAINER Solly Ross <sross@redhat.com>

RUN yum update -y && yum install -y kubernetes-master

ENTRYPOINT ["/usr/bin/kube-scheduler"]
