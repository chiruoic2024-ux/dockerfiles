# ARG VERSION
# FROM almalinux:${VERSION:-9}
# ARG COURSE = "DOCKER" \
#     TRAINER = "CHIRANJEEVI"
# ENV COURSE = ${COURSE}
# RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, Version: ${VERSION}"
# CMD ["sleep", "1000"]

ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR"
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}, Version: ${VERSION}"
CMD ["sleep", "1000"]