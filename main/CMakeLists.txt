# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS  "test_SSD1306_i2c.c"
                    "u8g2_esp32_hal.c")
set(COMPONENT_ADD_INCLUDEDIRS "")

register_component()
