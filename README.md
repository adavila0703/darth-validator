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
```python
pip install dark-validator
```
## Use

```python
from validator import validator

validator.validator('/path/1', '/path/2')
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
