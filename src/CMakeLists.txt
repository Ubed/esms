cmake_minimum_required(VERSION 3.12)
project(Project)

set(CMAKE_CXX_STANDARD 14)

add_executable(esms
        anyoption.cpp
        comment.cpp
        cond.cpp
        cond_action.cpp
        cond_condition.cpp
        cond_utils.cpp
        config.cpp
        esms.cpp
        game.h
        league_table.cpp
        league_table.h

        mt.cpp
        mt.h
        penalty.cpp
        report_event.cpp
        report_event.h

        rosterplayer.cpp
        rosterplayer.h
        tactics.cpp
        tactics.h
        teamsheet_reader.cpp
        teamsheet_reader.h

        util.cpp
        util.h )


add_subdirectory(googletest-master)
include(googletest-master/googletest/include)
