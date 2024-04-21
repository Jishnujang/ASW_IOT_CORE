idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    EMBED_TXTFILES aws_root_ca.pem certificate.pem.crt private.pem.key )
