#ARG VERSION
#if we not supply version default
#FROM almalinux:${VERSION:-9}
#if we want to supply the version
#FROM almalinux:${VERSION}

FARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR"
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}, Version: ${VERSION}"
CMD ["sleep", "1000"]