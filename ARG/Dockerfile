ARG version
FROM almalinux:${version:-8}
RUN echo "Hello alamalinux version is :${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "Course is:${COURSE}, Trainer is: ${TRAINER}}"