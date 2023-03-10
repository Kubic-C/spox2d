set(BOX2D_SOURCE_FILES
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_broad_phase.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_chain_shape.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_circle_shape.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_collide_circle.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_collide_edge.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_collide_polygon.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_collision.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_distance.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_dynamic_tree.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_edge_shape.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_polygon_shape.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/collision/b2_time_of_impact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/common/b2_block_allocator.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/common/b2_draw.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/common/b2_math.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/common/b2_settings.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/common/b2_stack_allocator.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/common/b2_timer.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_body.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_chain_circle_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_chain_circle_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_chain_polygon_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_chain_polygon_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_circle_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_circle_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_contact_manager.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_contact_solver.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_contact_solver.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_distance_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_edge_circle_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_edge_circle_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_edge_polygon_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_edge_polygon_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_fixture.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_friction_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_gear_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_island.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_island.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_motor_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_mouse_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_polygon_circle_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_polygon_circle_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_polygon_contact.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_polygon_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_prismatic_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_pulley_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_revolute_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_weld_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_wheel_joint.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_world.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/dynamics/b2_world_callbacks.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/rope/b2_rope.cpp)

set(BOX2D_HEADER_FILES
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_api.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_block_allocator.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_body.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_broad_phase.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_chain_shape.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_circle_shape.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_collision.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_common.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_contact.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_contact_manager.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_distance.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_distance_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_draw.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_dynamic_tree.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_edge_shape.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_fixture.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_friction_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_gear_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_growable_stack.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_math.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_motor_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_mouse_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_polygon_shape.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_prismatic_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_pulley_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_revolute_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_rope.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_settings.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_shape.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_stack_allocator.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_time_of_impact.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_timer.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_time_step.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_types.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_weld_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_wheel_joint.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_world.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/b2_world_callbacks.h
	${CMAKE_CURRENT_SOURCE_DIR}/../include/box2d/box2d.h)

target_sources(spock_engine PUBLIC ${BOX2D_HEADER_FILES})
target_sources(spock_engine PRIVATE ${BOX2D_SOURCE_FILES})

target_include_directories(spock_engine
  PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR}/../include
  PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}
)

# not allowed in spock
if(MSVC)
  message(ERROR "the MSVC compiler cannot be used")

  set_target_properties(spock_engine PROPERTIES
    COMPILE_PDB_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}"
    COMPILE_PDB_NAME box2d
  )

  install(
    FILES "${CMAKE_CURRENT_BINARY_DIR}/$<CONFIG>/box2d.pdb"
    DESTINATION ${CMAKE_INSTALL_LIBDIR}
    OPTIONAL
  )
endif()

if (BUILD_SHARED_LIBS)
  target_compile_definitions(box2d
    PUBLIC
      B2_SHARED
  )
endif()