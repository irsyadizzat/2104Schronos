################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := c:/ti/ccsv6/tools/compiler/msp430_4.3.3

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./main.obj" \
"./simpliciti/Components/nwk_applications/nwk_freq.obj" \
"./simpliciti/Components/nwk_applications/nwk_ioctl.obj" \
"./simpliciti/Components/nwk_applications/nwk_join.obj" \
"./simpliciti/Components/nwk_applications/nwk_link.obj" \
"./simpliciti/Components/nwk_applications/nwk_mgmt.obj" \
"./simpliciti/Components/nwk_applications/nwk_ping.obj" \
"./simpliciti/Components/nwk_applications/nwk_security.obj" \
"./simpliciti/Components/nwk/nwk.obj" \
"./simpliciti/Components/nwk/nwk_QMgmt.obj" \
"./simpliciti/Components/nwk/nwk_api.obj" \
"./simpliciti/Components/nwk/nwk_frame.obj" \
"./simpliciti/Components/nwk/nwk_globals.obj" \
"./simpliciti/Components/mrfi/mrfi.obj" \
"./simpliciti/Components/bsp/bsp.obj" \
"./simpliciti/Applications/application/End Device/main_ED_BM.obj" \
"./logic/acceleration.obj" \
"./logic/menu.obj" \
"./logic/stopwatch.obj" \
"./logic/test.obj" \
"./logic/user.obj" \
"./driver/adc12.obj" \
"./driver/as.obj" \
"./driver/bmp_as.obj" \
"./driver/bmp_ps.obj" \
"./driver/buzzer.obj" \
"./driver/display.obj" \
"./driver/pmm.obj" \
"./driver/ports.obj" \
"./driver/ps.obj" \
"./driver/rf1a.obj" \
"./driver/timer.obj" \
"../lnk_cc430f6137.cmd" \
"../bluerobin/BlueRobin_RX_433MHz.lib" \
-l"rts430x.lib" \
-l"libmath.a" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include simpliciti/Components/nwk_applications/subdir_vars.mk
-include simpliciti/Components/nwk/subdir_vars.mk
-include simpliciti/Components/mrfi/subdir_vars.mk
-include simpliciti/Components/bsp/subdir_vars.mk
-include simpliciti/Applications/application/End\ Device/subdir_vars.mk
-include logic/subdir_vars.mk
-include driver/subdir_vars.mk
-include bluerobin/subdir_vars.mk
-include subdir_rules.mk
-include simpliciti/Components/nwk_applications/subdir_rules.mk
-include simpliciti/Components/nwk/subdir_rules.mk
-include simpliciti/Components/mrfi/subdir_rules.mk
-include simpliciti/Components/bsp/subdir_rules.mk
-include simpliciti/Applications/application/End\ Device/subdir_rules.mk
-include logic/subdir_rules.mk
-include driver/subdir_rules.mk
-include bluerobin/subdir_rules.mk
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
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
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
ez430_chronos_433MHz.out \

EXE_OUTPUTS__QUOTED += \
"ez430_chronos_433MHz.out" \

BIN_OUTPUTS += \
ez430_chronos_433MHz.hex \

BIN_OUTPUTS__QUOTED += \
"ez430_chronos_433MHz.hex" \


# All Target
all: ez430_chronos_433MHz.out

# Tool invocations
ez430_chronos_433MHz.out: $(OBJS) $(CMD_SRCS) $(LIB_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: MSP430 Linker'
	"c:/ti/ccsv6/tools/compiler/msp430_4.3.3/bin/cl430" --cmd_file="C:\Users\IzzatLaptop\workspace_v6_0\ez430_chronos\simpliciti\Applications\configuration\smpl_nwk_config.dat" --cmd_file="C:\Users\IzzatLaptop\workspace_v6_0\ez430_chronos\simpliciti\Applications\configuration\End Device\smpl_config.dat"  -vmspx --abi=coffabi -O4 --opt_for_speed=0 -g --define=__CC430F6137__ --define=__CCE__ --define=ISM_LF --define=MRFI_CC430 --diag_warning=225 --display_error_number --diag_wrap=off --silicon_errata=CPU18 --silicon_errata=CPU21 --silicon_errata=CPU22 --silicon_errata=CPU23 --silicon_errata=CPU40 --call_assumptions=0 --gen_opt_info=2 --printf_support=minimal -z -m"ez430_chronos_433MHz.map" --heap_size=80 --stack_size=80 --use_hw_mpy=F5 --cinit_hold_wdt=on -i"c:/ti/ccsv6/ccs_base/msp430/include" -i"c:/ti/ccsv6/tools/compiler/msp430_4.3.3/lib" -i"c:/ti/ccsv6/tools/compiler/msp430_4.3.3/include" -i"c:/ti/ccsv6/ccs_base/msp430/lib" -i"c:/ti/ccsv6/ccs_base/msp430/lib/5xx_6xx_FRxx" --reread_libs --warn_sections --display_error_number --diag_wrap=off --xml_link_info="ez430_chronos_433MHz_linkInfo.xml" --rom_model -o "ez430_chronos_433MHz.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

ez430_chronos_433MHz.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: MSP430 Hex Utility'
	"c:/ti/ccsv6/tools/compiler/msp430_4.3.3/bin/hex430" --memwidth=8 --romwidth=8 -o "ez430_chronos_433MHz.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "main.pp" "simpliciti\Components\nwk_applications\nwk_freq.pp" "simpliciti\Components\nwk_applications\nwk_ioctl.pp" "simpliciti\Components\nwk_applications\nwk_join.pp" "simpliciti\Components\nwk_applications\nwk_link.pp" "simpliciti\Components\nwk_applications\nwk_mgmt.pp" "simpliciti\Components\nwk_applications\nwk_ping.pp" "simpliciti\Components\nwk_applications\nwk_security.pp" "simpliciti\Components\nwk\nwk.pp" "simpliciti\Components\nwk\nwk_QMgmt.pp" "simpliciti\Components\nwk\nwk_api.pp" "simpliciti\Components\nwk\nwk_frame.pp" "simpliciti\Components\nwk\nwk_globals.pp" "simpliciti\Components\mrfi\mrfi.pp" "simpliciti\Components\bsp\bsp.pp" "simpliciti\Applications\application\End Device\main_ED_BM.pp" "logic\acceleration.pp" "logic\menu.pp" "logic\stopwatch.pp" "logic\test.pp" "logic\user.pp" "driver\adc12.pp" "driver\as.pp" "driver\bmp_as.pp" "driver\bmp_ps.pp" "driver\buzzer.pp" "driver\display.pp" "driver\pmm.pp" "driver\ports.pp" "driver\ps.pp" "driver\rf1a.pp" "driver\timer.pp" 
	-$(RM) "main.obj" "simpliciti\Components\nwk_applications\nwk_freq.obj" "simpliciti\Components\nwk_applications\nwk_ioctl.obj" "simpliciti\Components\nwk_applications\nwk_join.obj" "simpliciti\Components\nwk_applications\nwk_link.obj" "simpliciti\Components\nwk_applications\nwk_mgmt.obj" "simpliciti\Components\nwk_applications\nwk_ping.obj" "simpliciti\Components\nwk_applications\nwk_security.obj" "simpliciti\Components\nwk\nwk.obj" "simpliciti\Components\nwk\nwk_QMgmt.obj" "simpliciti\Components\nwk\nwk_api.obj" "simpliciti\Components\nwk\nwk_frame.obj" "simpliciti\Components\nwk\nwk_globals.obj" "simpliciti\Components\mrfi\mrfi.obj" "simpliciti\Components\bsp\bsp.obj" "simpliciti\Applications\application\End Device\main_ED_BM.obj" "logic\acceleration.obj" "logic\menu.obj" "logic\stopwatch.obj" "logic\test.obj" "logic\user.obj" "driver\adc12.obj" "driver\as.obj" "driver\bmp_as.obj" "driver\bmp_ps.obj" "driver\buzzer.obj" "driver\display.obj" "driver\pmm.obj" "driver\ports.obj" "driver\ps.obj" 
	-$(RM) "driver\rf1a.obj" "driver\timer.obj" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-@echo 'Create flash image: TI-TXT'
	-"c:/ti/ccsv6/tools/compiler/msp430_4.3.3/bin/hex430.exe" --ti_txt "ez430_chronos_433MHz.out" -o "ez430_chronos_433MHz.txt" -order MS -romwidth 16
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets

