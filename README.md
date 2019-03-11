# pysh

pysh: shell in python

Tristan Price

COMMANDS:

start: on startup, enter pysh

exit: kill program from pysh

ls: print directories in current directory

cd _dir_: change to _dir_ in current directory

md _dir_: create _dir_ in current directory

cf _file_: create file _file_ in current directory

pd: print current directory

cl: clear screen

LIVE BUGS:
None

FIXED BUGS:
[002] [003] [001] [005] [004] [006] [007]

CHANGELOG:

1.0.5 19.03.11 #6 RELEASE

    cl: clear screen
    
1.0.4 19.03.11 #5

    fixes: [007]
    
1.0.3 19.03.9 #4

    fixes: [005] [004] [006]
    
    bugs:
    
        [007] ls showing past one level of directories
        
1.0.2 19.03.9 #3

    fixes: [001]
    
    bugs:
    
        [004] cf not functional
        
        [005] cding to a file messes up directories
        
        [006] pd not functional
        
1.0.1 19.03.8 #2

    pd: print current directory
    
    cf: create file in current directory
    
    fixes: [002] [003]
    
1.0.0 19.03.8 #1

    start: on startup, enter pysh
    
    exit: kill program from pysh
    
    ls: print directories in current directory
    
    cd _dir_: change to _dir_ in current directory
    
    md _dir_: create _dir_ in current directory
    
    bugs:
    
        [001] no back for cd
        
        [002] slash not needed for directories
        
        [003] exit not working
