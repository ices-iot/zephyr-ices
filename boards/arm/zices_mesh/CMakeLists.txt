#
# Code based on nrf52840_pca10059.
# Base commit: 3ae52624ffa129dfd1b0f5dc337afd1ddd6c4c1c
# Edited by ZICES contributors.
#

# Copyright (c) 2022 ZICES
#
# SPDX-License-Identifier: Apache-2.0

zephyr_library()
zephyr_library_sources(board.c)
zephyr_library_include_directories(${ZEPHYR_BASE}/drivers)