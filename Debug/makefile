################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv6/tools/compiler/gcc-arm-none-eabi-4_8-2014q3

ORDERED_OBJS += \
"./gpio.o" \
"./interrupts.o" \
"./lm3s6965_startup_ccs_gcc.o" \
"./main.o" \
"./system.o" \
-Wl,-T"../lm3s6965.lds" \
$(GEN_CMDS__FLAG) \
-Wl,--start-group \
-l"c" \
-l"gcc" \
-l"nosys" \
-Wl,--end-group \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
mcp-sch.out \

EXE_OUTPUTS__QUOTED += \
"mcp-sch.out" \

BIN_OUTPUTS += \
mcp-sch.hex \

BIN_OUTPUTS__QUOTED += \
"mcp-sch.hex" \


# All Target
all: mcp-sch.out

# Tool invocations
mcp-sch.out: $(OBJS) $(LDS_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: GNU Linker'
	"C:/ti/ccsv6/tools/compiler/gcc-arm-none-eabi-4_8-2014q3/bin/arm-none-eabi-gcc.exe" -mthumb -DPART_LM3S6965 -ffunction-sections -fdata-sections -g -gdwarf-3 -gstrict-dwarf -Wall -Wl,-Map,"mcp-sch.map" -static -o"mcp-sch.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

mcp-sch.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: GNU Objcopy Utility'
	"C:/ti/ccsv6/tools/compiler/gcc-arm-none-eabi-4_8-2014q3/bin/arm-none-eabi-objcopy.exe"  $(EXE_OUTPUTS__QUOTED) "mcp-sch.hex"
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "gpio.d" "interrupts.d" "lm3s6965_startup_ccs_gcc.d" "main.d" "system.d" 
	-$(RM) "gpio.o" "interrupts.o" "lm3s6965_startup_ccs_gcc.o" "main.o" "system.o" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

