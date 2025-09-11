ARG version
FROM almalinux:${version:-9}
ENV course="DevOps" \
    duration="120 hr" 
ARG trainer="kalyan"
ENV trainer=$trainer
RUN echo "hi, course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version is: ${version}"
CMD [ "sleep", "999" ]