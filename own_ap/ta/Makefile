CFG_TEE_TA_LOG_LEVEL ?= 4

# The UUID for the Trusted Application
#BINARY=8aaaf200-2450-11e4-abe2-0002a5d5c51b
BINARY=e2fee5c0-1089-4b70-ade8-13e305260051

-include $(TA_DEV_KIT_DIR)/mk/ta_dev_kit.mk

ifeq ($(wildcard $(TA_DEV_KIT_DIR)/mk/ta_dev_kit.mk), )
clean:
	@echo 'Note: $$(TA_DEV_KIT_DIR)/mk/ta_dev_kit.mk not found, cannot clean TA'
	@echo 'Note: TA_DEV_KIT_DIR=$(TA_DEV_KIT_DIR)'
endif
