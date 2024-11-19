# Add new driver file to build target - Added by KahngJu (24/11/19)
obj-y += amba-pl011.o		# UART
obj-y += fixed.o			# Voltage regulator
obj-y += gpio-pl061.o		# GPIO
obj-y += i2c-versatile.o	# I2C
obj-y += irq-gic-v3.o		# GIC

#obj-y += mmci.o			# MMC		
armmmci-y := mmci.o         # MMC

obj-y += pl330.o			# DMA
obj-y += spi-pl022.o		# SPI

ccflags-y += -I$(src) 		# Add curr direc to include path