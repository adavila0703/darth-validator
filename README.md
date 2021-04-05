# darth-validator
> Automatically validates correlation between two workbooks.

```                                              
                        %%(                       
              ,@@@@@@@@@@@@@@@@@@@@@              
            @@@      @& @@@        &@@%           
          ,@@         * @@@          @@@          
          @@            @@@           @@@         
         @@&            @@@          / @@         
         @@             @@@         @@#@@#        
         @@ ,@@@@&      @@@      *@@@, @@@        
        (@@@       &@@@@@@@@@@@&.     @@@@        
        @@,,@@@@@@@@@@@  . (@@@@@@@@@@@ @@*       
       @@@ @@@       @@@& @@@       @@@  @@       
       @@  @@@@,   (@@@ @@ @@@&    @@@@  @@@      
      @@* *@@%@@@@@@& .@& @@ ,@@@@@@&@@@  @@      
     @@@  @@@        @@@@@@@@        /@@# .@@     
    @@@  @@@@@@@@@@ @@@@ @ @@@*@@@@@@@@@@  /@@    
   @@@        @@@%&@@@@  @ @@@@@ @@@@    ,  &@@   
  @@@@@@@@@@@@@@ @@@@ @ .@ @,&@@@ @@@@@@@@@@@@@@  
               &@@@@//@//@*@(//@@@@/              
              @ %@@@@@@@@@@@@@@@@@. @                                    
```

# How to's

## Install

### pip install
```python
pip install dark-validator
```

### python file only
```
https://github.com/adavila0703/darth-validator/releases/tag/1.01
```

### executable only
```
https://github.com/adavila0703/darth-validator/releases/tag/1.0
```
## Use

```python
from validator import validator

validator.validator('/path/1', '/path/2')
```

Command for using file based versions
```python
python validator.py example1.xlsx example2.xlsx
```
```python
darth-validator.exe example1.xlsx example2.xlsx
```

## Output

Console output will give you a quick summary of how much matching and unmatching data was found.

For more details you locate the reports in ./reports

```python
============================================Report================================================
         RowCount ColumnCount Matching Unmatching Matching% Unmatching% RunTime
example1     1000           5      999          1      99.9         0.1
example2     1000           5      999          1      99.9         0.1
Total                                                                     0.883
==================================================================================================
```
