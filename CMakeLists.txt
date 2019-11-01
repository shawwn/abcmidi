cmake_minimum_required(VERSION 3.12)
project(abcmidi C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(abcmidi
    legacy_code/casecmp.c
    abc.h
    abcmatch.c
    config.h
    crack.c
    debug.c
    drawtune.c
    drawtune.h
    genmidi.c
    genmidi.h
    matchsup.c
    mftext.c
    midi2abc.c
    midicopy.c
    midicopy.h
    midifile.c
    midifile.h
    parseabc.c
    parseabc.h
    parser2.c
    parser2.h
    position.c
    pslib.c
    queues.c
    queues.h
    sizes.h
    store.c
    stresspat.c
    structs.h
    toabc.c
    yapstree.c)
