## Version 1.2-3
### CHANGES
 - mod_stat design change: now Analysis function is parametrized, if you do not want to see all output
 - gen_ping fix: uds scan for non sub-commands fixed, new subbcomands added
 - example uds_scan changed

## Version 1.2-2
### CHANGES
 - WEB interface fix: dependences from Intrnet connection (d3 external web) 

## Version 1.2-1
### CHANGES
 - mod_stat fix: table print format 

## Version 1.2-0
### CHANGES
 - mod_stat feature added: ASCII detection (print ASCII if found in the traffic)
 - mod_stat feature added: Marking CAN frames via metafile/metadata (COMMENTS for ID)
 - mod_stat feature added: Marking control bytes via metafile/metada  to re-assemble fragmented frames 
 - mod_stat feature added: experimental chain detection (re-assemble fragmented frames that are sent in LOOP)
 - mod_stat fix: UDS/ISO tp detection bug fixed (when you scan more)
 - mod_stat change: now it stores ALL packets, not just table, and save in REPLAY save all these frames (WARNINING: Now  this module stores all frames, which can affect memory and speed. Let's see how it works...)
 - mod_stat feature removed: alert feature removed
 

## Version 1.1-1
### CHANGES
 - mod_stat fixes: better output, simple dump functions

## V1.1b
### CHANGES
 - Fixed mod_stat analysis option bug, when CAN Frame has 1 byte size
 - Default sniff config added


## V1.0b
### CHANGES
First Beta

