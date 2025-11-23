ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE = "DOCKER" \
    TRAINER ="CHIRANJEEVI"
ENV COURSE = ${COURSE}
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, Version: ${VERSION}"
CMD ["sleep", "1000"]