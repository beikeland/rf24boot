objects-$(CONFIG_ROLE_SLAVE)+=avr-boot-common.o

cflags-y+=-DBOOTLOCK_PORTX=PORT$(call unquote,$(CONFIG_BOOTLOCK_PORT))
cflags-y+=-DBOOTLOCK_PINX=PIN$(call unquote,$(CONFIG_BOOTLOCK_PORT))
objects-$(CONFIG_BOOTLOCK_AVR)+=bootlock-avr.o
