old-dtb := $(dtb-y)
dtb-y :=
makefile-path := platform/t210b01/ers/kernel-dts

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif

dts-include += $(makefile-path)

dtb-y += $(old-dtb)
