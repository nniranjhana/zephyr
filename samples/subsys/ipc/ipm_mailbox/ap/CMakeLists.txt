cmake_minimum_required(VERSION 3.8.2)
include($ENV{ZEPHYR_BASE}/cmake/app/boilerplate.cmake NO_POLICY_SCOPE)
project(ipm_mailbox_ap)

target_include_directories(app PRIVATE $ENV{ZEPHYR_BASE}/drivers)
target_sources(app PRIVATE src/hello.c)
