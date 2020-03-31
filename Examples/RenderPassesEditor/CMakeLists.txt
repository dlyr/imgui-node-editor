add_example(RenderPassesEditor
    Blueprints.cpp
)

find_package(blueprint-utilities REQUIRED)

target_link_libraries(RenderPassesEditor PRIVATE blueprint-utilities)
