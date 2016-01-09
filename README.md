HP 58503A Backup Files


About: 

The HP 58503A has a serial bootloader mode, however there are no files available online for restoring the instrument in case the flash memory is corrupted. As an alternative the PLCC-32 Flash EEPROMs can be removed and replaced if the contents is available. 

The flash memory used in the HP 58503A is the AMD AM29F010-120

The dumps from each of the 4 memories is included in a few formats for ease of processing:

58503_800XX_RevA_XX.BIN: Part number AND silksceen designator in case the original labels are missing. These are the files dumped from each of the respective parts. 

58503a_X_LandM_Combined.BIN: The 58503A pairs up the flash chips. These files stich the data back together (alternating bytes) for processing purposes. 

58503a_x_LandM_Combined_Hexdump.txt: Same as above, but run through hexdump for ease of reading online. 



Current Status:

1/7/2016: The output files seem reasonable when looking at the ASCII output with regards to debug/output data, but I haven't been able to test using reflashed parts in my 58503A. I have a few replacement AM29F010 parts on order and will try them when they arrive. 