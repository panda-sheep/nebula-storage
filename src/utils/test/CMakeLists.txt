nebula_add_test(
    NAME
        nebula_key_utils_test
    SOURCES
        NebulaKeyUtilsTest.cpp
    OBJECTS
        $<TARGET_OBJECTS:keyutils_obj>
        $<TARGET_OBJECTS:common_base_obj>
        $<TARGET_OBJECTS:common_datatypes_obj>
    LIBRARIES
        gtest
)

nebula_add_test(
    NAME
        index_key_utils_test
    SOURCES
        IndexKeyUtilsTest.cpp
    OBJECTS
        $<TARGET_OBJECTS:keyutils_obj>
        $<TARGET_OBJECTS:common_base_obj>
        $<TARGET_OBJECTS:common_datatypes_obj>
    LIBRARIES
        gtest
)

