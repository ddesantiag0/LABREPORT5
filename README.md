# LABREPORT5

## GREP COMMAND

### grep -c
For each input file, the command outputs the number of matching lines.

**Example 1 of "-c"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -c "call"  ./911report/*.txt
./911report/chapter-1.txt:69
./911report/chapter-10.txt:13
./911report/chapter-11.txt:14
./911report/chapter-12.txt:23
./911report/chapter-13.1.txt:12
./911report/chapter-13.2.txt:68
./911report/chapter-13.3.txt:14
./911report/chapter-13.4.txt:45
./911report/chapter-13.5.txt:79
./911report/chapter-2.txt:23
./911report/chapter-3.txt:72
./911report/chapter-5.txt:11
./911report/chapter-6.txt:41
./911report/chapter-7.txt:28
./911report/chapter-8.txt:29
./911report/chapter-9.txt:60
./911report/preface.txt:0
```
**Example 2 of "-c"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -c "words"  ./plos/*.txt      
./plos/journal.pbio.0020001.txt:0
./plos/journal.pbio.0020010.txt:0
./plos/journal.pbio.0020012.txt:0
./plos/journal.pbio.0020013.txt:0
./plos/journal.pbio.0020019.txt:0
./plos/journal.pbio.0020028.txt:0
./plos/journal.pbio.0020035.txt:0
./plos/journal.pbio.0020040.txt:0
./plos/journal.pbio.0020042.txt:0
./plos/journal.pbio.0020043.txt:0
./plos/journal.pbio.0020046.txt:3
./plos/journal.pbio.0020047.txt:1
./plos/journal.pbio.0020052.txt:0
./plos/journal.pbio.0020053.txt:0
./plos/journal.pbio.0020054.txt:0
./plos/journal.pbio.0020063.txt:0
./plos/journal.pbio.0020064.txt:0
```
**Example 3 of "-c"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -c "tired"  ./biomed/*.txt    
./biomed/1468-6708-3-1.txt:0
./biomed/1468-6708-3-10.txt:0
./biomed/1468-6708-3-3.txt:0
./biomed/1468-6708-3-4.txt:0
./biomed/1468-6708-3-7.txt:0
./biomed/1471-2091-2-10.txt:0
./biomed/1471-2091-2-11.txt:0
./biomed/1471-2091-2-12.txt:0
./biomed/1471-2091-2-13.txt:0
./biomed/1471-2091-2-16.txt:0
./biomed/1471-2091-2-5.txt:0
./biomed/1471-2091-2-7.txt:0
./biomed/1471-2091-2-9.txt:0
./biomed/1471-2091-3-13.txt:0
./biomed/1471-2091-3-14.txt:0
./biomed/1471-2091-3-15.txt:0
./biomed/1471-2091-3-16.txt:0
./biomed/1471-2091-3-17.txt:0
./biomed/1471-2091-3-18.txt:0
```
### grep -h 

**Example 1 of "-h"**

```
desantiago@Davids-MacBook-Air-2 technical % grep -h "tired"  ./biomed/*.txt
          tired of being sick and tired and I knew I could be a
          better parent to my children and I just was tired. I
          C57Bl/6J retired breeders also obtained from The Jackson
          nervous? Does your tinnitus make you feel tired or
          young retired breeders, were purchased from the National
          retired: bo322, bo395, bo663, bo667, bo669 and bo671 (G.
          candidate CDSs include retired Bnums (six Magnums), CDSs
```
