target_sources(${LRS_TARGET}
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/record/record_device.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/record/record_sensor.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/playback/playback_device.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/playback/playback_sensor.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/record/record_device.h"
        "${CMAKE_CURRENT_LIST_DIR}/record/record_sensor.h"
        "${CMAKE_CURRENT_LIST_DIR}/playback/playback_device.h"
        "${CMAKE_CURRENT_LIST_DIR}/playback/playback_sensor.h"
        "${CMAKE_CURRENT_LIST_DIR}/ros/ros_reader.h"
        "${CMAKE_CURRENT_LIST_DIR}/ros/ros_writer.h"
        "${CMAKE_CURRENT_LIST_DIR}/ros/ros_file_format.h"
)
