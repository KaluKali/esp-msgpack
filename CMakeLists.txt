idf_component_register(SRCS "msgpack-c/src/objectc.c" "msgpack-c/src/unpack.c" "msgpack-c/src/version.c" "msgpack-c/src/vrefbuffer.c" "msgpack-c/src/zone.c"
                    INCLUDE_DIRS "msgpack-c/include")
target_compile_options(${COMPONENT_LIB} PRIVATE "-DMSGPACK_ENDIAN_LITTLE_BYTE")