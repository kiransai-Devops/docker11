ARG Version
FROM almalinux:${Version:-9}
ARG Duration="10.30hours" \
    Course="AWS" 
ENV course: ${Course} 
RUN echo "duration: ${Duration}, course: ${Course}, version: ${Version}"
CMD [ "sleep", "1000" ]


