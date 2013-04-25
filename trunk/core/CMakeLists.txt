SET(core_SRC
    hello.cpp
    main.cpp
    zombie.cpp
    being.cpp
    flocker.cpp
    zombieManager.cpp
    beingManager.cpp
    world.cpp
    manager.cpp
    event.cpp
    localEvent.cpp
    globalEvent.cpp
)

add_executable(main ${core_SRC})
