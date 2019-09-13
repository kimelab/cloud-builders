FROM ubuntu
RUN apt update && apt install -y wget
RUN wget https://github.com/dhall-lang/dhall-haskell/releases/download/1.26.0/dhall-json-1.4.1-x86_64-linux.tar.bz2 && tar --extract --bzip2 --file dhall-json-1.4.1-x86_64-linux.tar.bz2
ENTRYPOINT [ "./bin/dhall-to-yaml" ]
