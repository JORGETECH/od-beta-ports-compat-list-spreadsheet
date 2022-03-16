Spreadsheet document with compatibility information on standalone ports running on OpenDingux Beta

#Preamble
The newer OpenDingux releases have a lot of changes compared to older releases that were used on devices like the GCW-Zero and RG-350 (at launch, as the stock system). Among the most important changes are the newer kernel and uClibc versions (now uClibc-ng is being used). Since uClibc does not really have ABI backwards compatibility some ported applications may not work correctly or crash upon launch, so those applications would need to be recompiled using the newer toolchain. Additionally, some libraries may have been deprecated in the main system, in which case they must be bundled in the OPK or replaced by newer ones.
