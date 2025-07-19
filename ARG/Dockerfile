ARG version 
FROM almalinux:${version:-9}
ENV course="devops" \ 
    duration="120hrs" 
ARG trainer="siva" 
ENV trainer=$trainer 
RUN echo "Hello course is ${course},duration is ${duration},trainer is ${trainer}" 
CMD ["sleep","1000"]    