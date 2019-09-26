cmake_minimum_required(VERSION 3.14)
project(enPAC_BETA3_9)

set(CMAKE_CXX_STANDARD 14)
set(LINK_DIR /usr/local/lib)
link_directories(${LINK_DIR})
link_libraries(tcmalloc)


include_directories(.)

add_executable(enPAC_BETA3_9
        Data_Structures.cpp
        Data_Structures.h
        Lexer.cpp
        Lexer.h
        main.cpp
        Petri_Net.cpp
        Petri_Net.h
        product.cpp
        product.h
        README.txt
        RG.cpp
        RG.h
        SBA.cpp
        SBA.h
        Syntax_Tree.cpp
        Syntax_Tree.h
        TBA.cpp
        TBA.h
        TGBA.cpp
        TGBA.h
        tinystr.cpp
        tinystr.h
        tinyxml.cpp
        tinyxml.h
        tinyxmlerror.cpp
        tinyxmlparser.cpp
        xml2ltl.cpp
        xml2ltl.h)
