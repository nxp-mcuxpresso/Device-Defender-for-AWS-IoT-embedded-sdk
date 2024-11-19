#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: MIT
#


if(CONFIG_MCUX_COMPONENT_middleware.aws_iot.device_defender)
    mcux_add_source(
        SOURCES source/defender.c
                source/include/defender.h
                source/include/defender_config_defaults.h
    )
    mcux_add_include(
        INCLUDES source/include
    )
endif()
