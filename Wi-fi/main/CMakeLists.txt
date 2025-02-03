idf_component_register(SRCS "blynk_led_control.c" "scan.c"
                    INCLUDE_DIRS "."
                    REQUIRES esp_wifi esp_event nvs_flash blynk)