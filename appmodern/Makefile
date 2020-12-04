TARGET := iphone:clang:latest:7.0
INSTALL_TARGET_PROCESSES = appmodern

include $(THEOS)/makefiles/common.mk

APPLICATION_NAME = appmodern

appmodern_FILES = main.m NVAppDelegate.m NVRootViewController.m
appmodern_FRAMEWORKS = UIKit CoreGraphics
appmodern_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/application.mk
