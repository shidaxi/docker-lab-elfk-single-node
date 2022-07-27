FROM obsidiandynamics/kafdrop:3.27.0

FROM centos:8

RUN yum install -y java-11-openjdk

COPY --from=0 /kafdrop.sh /kafdrop.sh

RUN mkdir -p /kafdrop-3.27.0/libs

COPY --from=0 /kafdrop-3.27.0/ /kafdrop-3.27.0/

ENTRYPOINT ["/kafdrop.sh"]