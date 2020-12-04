TARGET := iphone:clang:latest:7.0

include $(THEOS)/makefiles/common.mk

TOOL_NAME = swifttool

swifttool_FILES = main.swift
swifttool_CODESIGN_FLAGS = -Sentitlements.plist
swifttool_INSTALL_PATH = /usr/local/bin

include $(THEOS_MAKE_PATH)/tool.mk
