#
# Copyright (c) 2021 x-io Technologies
#
# SPDX-License-Identifier: MIT
#

zephyr_include_directories(Fusion)
add_subdirectory_ifdef(CONFIG_FUSION_AHRS Fusion)
