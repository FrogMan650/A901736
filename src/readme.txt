M60 - Spindle Collet Activate
M61 - Spindle Collet Deactivate
M62 - Left Posts Activate
M63 - Left Posts Deactivate
M64 - Front Posts Activate
M65 - Front Posts Deactivate
M66 - Clamp Area Activate
M67 - Clamp Area Deactivate
M70 - Send Spindle to HIGH position
M71 - Send Spindle to MED position
M72 - Send Spindle to LOW position

INP25 - Spindle HIGH position sensor SQ441
INP26 - Spindle MED position sensor SQ441A
INP27 - Spindle LOW position sensor SQ442

OUT18 - Spindle Collet YV263
OUT20 - Left Posts YV1A
OUT21 - Front Posts YV5A
OUT25 - Clamp Area YV9A
OUT27 - Spindle HIGH solenoid YV202B
OUT28 - Spindle MED solenoid YV202A
OUT29 - Spindle LOW solenoid YV202D

M70
Activate OUT27 until INP25 turn on

M71
Activate OUT28 until INP26 turn on

M72
Activate OUT29 until INP27 turn on