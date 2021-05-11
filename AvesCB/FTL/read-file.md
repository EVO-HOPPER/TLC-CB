use readonly;                               #^# use read only for this read file.
                                            #*# Import Open Services System
!== require \open $Port->@value:%option;    #*# $Port->@value:%option
                                            #*# require packages 
     import *open* goto *close* system;     #*# import open select goto close select system
     *updater->*index.connect*;             #*# index.connect.src.api*
.push->index.connect.src.code*;             #*# index.connect.src.code*
                                            #*#
                                            #*# Api Connection Server Client
                                            #*#
open code* use __Main__.py                  #*# Main Module py package open code*
                                            #*# Options Main Menu    
                                            #*#
    use caller;                             #*# caller keyword
                                            #*# \\eq: abc + xyz 
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*#
    use syscall;                            #*# syscall keyword 
                                            #*# \\eq: abc + xyz 
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*#
    use $Caller;                            #*# scalar caller keyword
                                            #*# \\eq: abc + xyz 
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*#
    use service;                            #*# @service: \@reference #*# Link.comm32
                                            #*# \\eq: abc + xyz 
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*#
    use toolbox;                            #*# special toolbox SDK
                                            #*# \\eq: abc + xyz 
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*#
    use support;                            #*# support packages via SDK
                                            #*# \\eq: abc + xyz 
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*#
    use package;                            #*# basic modules from perl langaguage
                                            #*# \\eq: abc + xyz             
                                            #^# !== alphabet-CB/ + \eq: abc + xyz 
                                            #*# !== alphabet-CB// 
                                            #*# 
                                            #*# open->:S: set => default: 1;
 \close => our port via :T: :S: 0000        #*# \close => our port via :T: :S: 7890 'close' forwards ports 
 \open => our port via  :S: :A: 0000        #*#  \open => our port via :T: :S: 7890 'open'  forwards ports
                                            #*#
                                            #*# :switch: and or :transfer:
 \close => our port via :S:     0000        #*# \close => our port via :S: :B: 0000 '' forward ports 
 \open  => our port via :S: :A: 0000        #*#  \open => our port via :S: :B: 0000 '' forward ports
                                            #*#
                                            #*# :options: *updater.patch*
via {https://www.github.com/codeR32-dev}    #*# link {} 
and do \close @service;                     #*# and do \ref goto \close action for program
                                            #*#
                                            #&# Spool Down Server 
do next system system;                      #*# and do
                                            #*# Return Values For Project Understanding.
return 0; 1;                                #*#
