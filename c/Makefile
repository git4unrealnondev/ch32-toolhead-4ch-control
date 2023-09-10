all : flash

TARGET:=main

include ./ch32v003fun/ch32v003fun/ch32v003fun.mk

flash : cv_flash
clean : 
	rm -rf $(TARGET).elf $(TARGET).bin $(TARGET).hex $(TARGET).lst $(TARGET).map $(TARGET).hex || true
