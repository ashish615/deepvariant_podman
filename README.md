# deepvariant_podman

--user remove from all scripts

## Replace files 
deepvariant-r1.4/tools/build_clif.sh
deepvariant-r1.4/third_party/nucleus/pip_package/build_pip_package.sh

## protobuf installation error
https://superuser.com/questions/1435437/how-to-get-around-this-error-when-untarring-an-archive-tar-cannot-change-owner

## change permissions
chmod -R 777 "${TOPDIR}/google"
chmod -R 777 "protobuf-$PROTOBUF_VERSION" && \
