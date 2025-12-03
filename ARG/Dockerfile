ARG VERSION
#if we not supply version default
#FROM almalinux:${VERSION:-9}
#if we want to supply the version
#FROM almalinux:${VERSION}

FROM almalinux:{VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="sivajakkam"
RUN echo "Trainer ${TRAINER}, Course: ${COURSE}"
CMD ["sleep", "1000"]
