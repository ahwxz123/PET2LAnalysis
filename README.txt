

 PET2LAnalysis Usage 
 Options: 
          -i/-il  path_to_input_file 
          -o      path_of_output 
         [-raw    yes/no ] 
         [-hist   yes/no ] 
         [-pdf    yes/no ] 
         [-png    yes/no ] 
         [-bin    yes/no ] 
         [-sino   yes/no ] 
         [-type   coin/single ] 
         [-event  delay/prompt/both ] 
         [-all    ] 
         [-v      ] 


 [Main setting]: 
         -i  path_to_input_file    : give an input datafile of PET2L datafile(s) Within absolute PATH. 
                                     option -in/-input is same as -i 
         -il path_to_input_txtfile : give an input txt-like file With absolute PATH, txtfile includes PET2L data format files. 
         -o  path_to_output        : give an absolute PATH for output, it must exist before analysis. 
                                     option -out/-output is same as -o  
         -raw  Option              : save raw data in rootfiles or not, Option: y/yes/Yes/YES/Y/n/no/No/NO/N. (default negetive)
         -hist Option              : save histogram in rootfiles or not, Option: y/yes/Yes/YES/Y/n/no/No/NO/N. (default positive)
         -pdf  Option              : save pdf file or not, Option: y/yes/Yes/YES/Y/n/no/No/NO/N. (default negetive)
         -png  Option              : save png file or not, Option: y/yes/Yes/YES/Y/n/no/No/NO/N. (default positive)
         -bin  Option              : save binary file or not, Option: y/yes/Yes/YES/Y/n/no/No/NO/N. (default negetive)
         -sino  Option             : save sino file or not, Option: y/yes/Yes/YES/Y/n/no/No/NO/N. (default positive)
         -type  Option             : data file type,Option: coin/coins/single/singles. (default coincidence data)
         -event Option             : event kind, delay/prompt/both. (default both) 
         -all                      : save all outputs, raw,hist,pdf,png,binary. 
         -v                        : print the version of this application 
                                     option -version/--version is same as -v  


