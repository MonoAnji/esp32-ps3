idf_component_register(SRCS
                         "src/ps3.c"
                         "src/ps3_spp.c"
                         "src/ps3_parser.c"
                         "src/ps3_l2cap.c"
                       INCLUDE_DIRS
                         "src"
                         "src/include"
                       REQUIRES bt)