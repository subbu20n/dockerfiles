ARG version 
FROM almalinux:${version:-9} 
ENV course="devops" \
    duration="120hr" 
ARG trainer="sivakumar" 
ENV trainer=$trainer
RUN  echo "Hi, course is: ${course},duration is: ${duartion},trainer is: ${trainer},version: ${version}" 
CMD ["sleep","1000"]     

