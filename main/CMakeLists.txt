# Este comando define o seu componente 'main' e suas dependências.
idf_component_register(SRCS "main.c"
                           "wifi_manager.c"
                       REQUIRES "esp_event"
                                "esp_netif"
                                "nvs_flash"
                                "dht"
                                "mqtt"
                                "esp_wifi"
                                "driver"
                       )