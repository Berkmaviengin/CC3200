################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./adc_userinput.obj" \
"./bma222drv.obj" \
"./gpio_if.obj" \
"./i2c_if.obj" \
"./main.obj" \
"./pinmux.obj" \
"./startup_ccs.obj" \
"./uart_if.obj" \
"../cc3200v1p32.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-l"C:/TI/CC3200SDK_1.3.0/CC3200SDK_1.3.0/cc3200-sdk/driverlib/ccs/Release/driverlib.a" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
9)BMA222_UART.out \

EXE_OUTPUTS__QUOTED += \
"9)BMA222_UART.out" \

BIN_OUTPUTS += \
9)BMA222_UART.bin \

BIN_OUTPUTS__QUOTED += \
"9)BMA222_UART.bin" \


# All Target
all: 9)BMA222_UART.out

# Tool invocations
9)BMA222_UART.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armcl" -mv7M4 --code_state=16 --float_support=vfplib --abi=eabi -me -Ooff -g --gcc --define=ccs --define=cc3200 --diag_wrap=off --diag_warning=225 --display_error_number --printf_support=full -z -m"9)BMA222_UART.map" --heap_size=0x00008000 --stack_size=0x00001000 -i"C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/lib" -i"C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/include" --reread_libs --display_error_number --diag_wrap=off --warn_sections --xml_link_info="9)BMA222_UART_linkInfo.xml" --rom_model -o "9)BMA222_UART.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

9)BMA222_UART.bin: $(EXE_OUTPUTS)
	@echo 'Invoking: ARM Hex Utility'
	"C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armhex"  -o "9)BMA222_UART.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "adc_userinput.obj" "bma222drv.obj" "gpio_if.obj" "i2c_if.obj" "main.obj" "pinmux.obj" "startup_ccs.obj" "uart_if.obj" 
	-$(RM) "adc_userinput.d" "bma222drv.d" "gpio_if.d" "i2c_if.d" "main.d" "pinmux.d" "startup_ccs.d" "uart_if.d" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"C:/TI/ccsv7/utils/tiobj2bin/tiobj2bin" "9)BMA222_UART.out" "9)BMA222_UART.bin" "C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armofd" "C:/TI/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armhex" "C:/TI/ccsv7/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

