FROM ubuntu
USER root
ADD test.sh /etc/test.sh
RUN chown root:root /etc/test.sh
RUN chmod 700 /etc/test.sh
CMD ["/etc/test.sh","-d"]

