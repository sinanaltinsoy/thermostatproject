add_executable(ThermostatApp ThermostatApp.cpp)
target_compile_features(ThermostatApp PRIVATE cxx_std_11)

target_link_libraries(ThermostatApp PRIVATE Device)
target_link_libraries(ThermostatApp PRIVATE Cooler)
target_link_libraries(ThermostatApp PRIVATE Heater)
target_link_libraries(ThermostatApp PRIVATE Thermostat)
target_link_libraries(ThermostatApp PRIVATE Room)
target_link_libraries(ThermostatApp PRIVATE RoomApp)