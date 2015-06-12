# device-qcom-sepolicy

Repository that hosts SELinux common policies for QCOM Hardware

If you want to use these policies, add a

include device/qcom/sepolicy/sepolicy.mk

to your device's BoardConfig. It is highly recommended that in case
you have your own BOARD_SEPOLICY_DIRS and BOARD_SEPOLICY_UNION declarations,
the inclusion happens _before_ those lines
