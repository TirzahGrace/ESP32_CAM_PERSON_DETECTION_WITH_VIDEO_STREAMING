set(srcs "connect_wifi.c")
idf_component_register(SRCS ${srcs}
                    INCLUDE_DIRS "."
                    REQUIRES nvs_flash esp_wifi esp_driver_gpio)
