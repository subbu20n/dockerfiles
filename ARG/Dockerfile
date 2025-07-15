ARG version 
FROM almalinux:${version:-9}
ENV course="devops" \ 
    duration="120hrs" 
ARG trainer="sivakumar" 
ENV trainer=$trainer 
RUN echo "Hi course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version is: ${version}" 
CMD ["sleep","1000"] 