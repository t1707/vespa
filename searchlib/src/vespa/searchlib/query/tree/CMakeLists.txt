# Copyright 2017 Yahoo Holdings. Licensed under the terms of the Apache 2.0 license. See LICENSE in the project root.
vespa_add_library(searchlib_query_tree OBJECT
    SOURCES
    intermediate.cpp
    intermediatenodes.cpp
    querybuilder.cpp
    stackdumpcreator.cpp
    term.cpp
    location.cpp
    range.cpp
    termnodes.cpp
    DEPENDS
)
