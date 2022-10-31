# LAB REPORT 5

## GREP COMMAND

### grep -c
For each input file, the command outputs the number of matching lines. This is useful when you aren't looking for specific text, but searching for every single file that carries the phrase or word that you are looking for.

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
Show only the lines that match and hide the filenames. This is useful when already in a certain file and you dont want it to repeatively keep on printing along with the text that you know you're in.

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
**Example 2 of "-h"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -h "ups"  ./911report/*.txt
    In upstate New York, NEADS personnel first learned of the shootdown order from this message: Floor Leadership: You need to read this. . . . The Region Commander has declared that we can shoot down aircraft that do not respond to our direction. Copy that?
                terrorists, work with a coalition to eliminate terrorist groups and networks, and
                on Bin Ladin for Now" (March 2001),"Terrorist Groups Said Cooperating on US Hostage
                groups had already used suicide vehicles, namely truck bombs, the leap to the use of
                on front pages, and the original story and its follow-ups dominated television news
                opposing groups of states, and measuring industrial might. To be dangerous, an enemy
                the Islamic world, inspired in part by al Qaeda, which has spawned terrorist groups
                find and destroy terrorist groups and their allies in the field, notably in
                The army is confronting groups of al Qaeda fighters and their local allies in very
                than two dozen other terrorist groups are pursuing CBRN [chemical, biological,
                diplomacy, as governments join together to identify named individuals and groups as
                decentralized terrorist groups, the premise behind the government's efforts-that
                agency for the investigation of foreign terrorist groups operating inside the United
                top tier of FBI management. Field intelligence groups have been created in all field
                least 20 Sunni Islamic extremist groups in the Middle East, South Asia, Africa, and
                groups and supporters (Jan 8, 1997; Jan. 31, 1997; Jan 31, 1997; Feb. 7, 1997); on
                terrorist groups, in 1993 the U.S. government designated the country a state sponsor
            85. For aid to the exile groups, see Karl Inderfurth interview (Feb. 18, 2004); Peter
                groups at this time, including the Libyan Islamic Fighting Group and a group headed
                report, "Comprehensive List of Terrorists and Groups Identified Under Executive
                Jan. 7,2004. For the two groups not meeting with each other, see Intelligence
                States may have made their way to al Qaeda or its affiliated groups. Frank G. and
                groups and WMD as transnational threats for the new global era. See, e.g., President
                On concerns about extremist groups exploiting millennial opportunities, see, e.g.,
                Called the Office of Transnational Issues (OTI), Illicit Transaction Groups (ITG),
                impact of increased aid to anti-Taliban groups in Afghanistan). Both Secretary
                Binalshibh, Oct. 2, 2002. Binalshibh also stated that Bin Ladin was upset with Iraqi
            10. See CIA, SEIB, "Terrorist Groups Said Cooperating on US Hostage Plot," May 23,
                Nineteen of them returned upstairs, where 18 died; the 20th was told by her
                supervisor, who was in the group, to leave rather than return upstairs. The
                processes for certain groups from Arab and Muslim countries; the Iraq war; and
                would offer an integrated depiction of groups like al Qaeda or Hezbollah worldwide,
                groups in Afghanistan fighting the Soviet occupation. This assistance was funneled
                the coordinating body for the consortium of terrorist groups with which he was
                building this Islamic army, he enlisted groups from Saudi Arabia, Egypt, Jordan,
                extremist groups from these same countries; from the African states of Chad, Mali,
                Islamist groups were focused on local battles, such as those in Egypt, Algeria,
                violent Islamist extremists came from all the groups represented in Bin Ladin's
                the late 1990s, these extremist groups suffered major defeats by Kurdish forces. In
                targets of some of these groups, added their own pressure. At the same time, the
                Pakistani politics. After a coup in 1977, military leaders turned to Islamist groups
                with other jihad groups and leaders, and plot and staff terrorist schemes. While Bin
                groups-in Egypt, Algeria, Yemen, Lebanon, Morocco, Tunisia, Somalia, and
                including the Malaysian-Indonesian JI and several Pakistani groups engaged in the
                weapons for actions carried out by members of allied groups. The attacks on the U.S.
                Center. The casing team also included a computer expert whose write-ups were
                groups sometimes cooperated. In the winter of 1999-2000, as will be detailed in
                regional conflicts, mainly in the Middle East. The majority of terrorist groups
                foul-ups on the ground resulted in the loss of eight aircraft, five airmen, and
                capability to preempt groups and individuals planning strikes against U.S.
                only guess at how much aid Bin Ladin gave to terrorist groups, what were the main
            Another diplomatic option may have been available: nurturing Afghan exile groups as a
                provided some support for talks among the leaders of exile Afghan groups, including
                INITIAL ASSAULTS 125 Northern Alliance with Pashtun groups. One U.S. diplomat later
                told us that the exile groups were not ready to move forward and that coordinating
                fractious groups residing in Bonn, Rome, and Cyprus proved extremely difficult.
                upset the United States.
                communications needs of Afghan groups, where he learned about drills used to
                with other mujahideen groups still operating in Afghanistan, including the group led
                comparable terrorist organization, he gives no indication of what other groups he
                Allah. Although Jarrah's transformation generated numerous quarrels, their breakups
                program. Rather, Bin Ladin selectively provided startup funds to new groups or money
                tempo." Second,"sleeper cells" and "a variety of terrorist groups" had turned up at
                organizations suspected of raising funds for al Qaeda or other terrorist groups. By
                groups than to executive branch interagency committees. The changes sought by the
                Assistance to anti-Taliban groups and proxies who might be encouraged to
                Washington would first consider options for aiding other anti- Taliban groups.
            The draft NSPD's goal was to "eliminate the al Qida network of terrorist groups as a
                anti-Taliban groups. The draft also tasked OMB with ensuring that sufficient funds
                program encouraging anti-Taliban Afghans of all major ethnic groups to stalemate the
                    groups.
                for instruments rating at Jones Aviation and failed. Very upset, they said they were
                The future hijackers usually arrived in groups of two or three, staying at the safe
                indicating a potential for attacks against U.S. targets abroad from groups "aligned
                terrorist groups were known to "plan and train for hijackings"and were able to build
                foreign partners to upset terrorist plans, closing embassies, moving military assets
            Several small groups of people who were physically unable to descend the stairs were
                groups, primarily between the 103rd and 106th floors. A large group was reported on
                instructed to go back upstairs-and in the upper sky lobby, where many waited for
                groups of civilians descended from that floor. Others remained on the floor to help
                the lobby via radio. Some units were directed to assist specific groups of
```
**Example 3 of "-h"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -h "burns"  ./biomed/*.txt   
          information on: skin characteristics, sunburns and
        of actinic keratosis, history of sunburns), then the lack
            substitute chemical include acute irritation and burns
          addition, patients with burns, hemorrhagic shock or those
        trauma, burns, haemorrhages, hypothermia, pancreatitis and
        are massively elevated in burns [ 11], heat stroke [ 21],
```

### grep -w
Displays the matching entire word along with in what exact file it was found. This is useful when you need to know where to find the certain phrase you're looking for

**Example 1 of "-w"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -w "burns"  ./biomed/*.txt
./biomed/1476-069X-2-9.txt:            substitute chemical include acute irritation and burns
./biomed/cc1498.txt:          addition, patients with burns, hemorrhagic shock or those
./biomed/cc1843.txt:        trauma, burns, haemorrhages, hypothermia, pancreatitis and
./biomed/cc300.txt:        are massively elevated in burns [ 11], heat stroke [ 21],
```

**Example 2 of "w"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -w "cops"  ./911report/*.txt
./911report/chapter-9.txt:                to take orders from cops. At least one firefighter who was in the North Tower has
```

**Example 3 of "w"**
```
desantiago@Davids-MacBook-Air-2 technical % grep -w "child"  ./plos/*.txt
./plos/journal.pbio.0020046.txt:        is no good way of predicting whether an affected child will recover (Yairi and Ambrose
./plos/journal.pbio.0020046.txt:        However, studies of personality traits and child–parent interactions did not detect
./plos/journal.pbio.0020140.txt:        so naturally to humans (and are in place so early in child development) that some might
./plos/journal.pbio.0020150.txt:        conclusions to the individual child. “At the moment, fMRI would be among the most useless
./plos/journal.pbio.0020150.txt:        consider other factors, such as a history of child abuse, in an attempt to more fully
./plos/journal.pbio.0020262.txt:        scientist looking like a small child beside Chris Greener, the tallest man in Britain, or
./plos/journal.pbio.0020267.txt:        Sara Webb, a child psychologist at UW, has followed about 70 autistic children since the
./plos/journal.pbio.0020267.txt:        differently from seeing a favorite toy, in the same way a normal child does. But activity
./plos/journal.pbio.0020267.txt:        opportunity to be shaped by the experience and input that a typically developing child
./plos/journal.pbio.0020267.txt:        behavioral therapy an autistic child receives, the better the outcome will be. That's why
./plos/journal.pbio.0020337.txt:        energies to build up, cycle by cycle, into an appreciable motion—like boosting a child on a
./plos/journal.pbio.0020337.txt:        child-on-swing analogy, rapidly bring swinging to a halt. Therefore, the argument goes, the
./plos/pmed.0010021.txt:        spent on one disease cannot be spent on another. Is it better to treat one child with
./plos/pmed.0010024.txt:        to calculate intracellular volume for each child. They also used a less invasive and more
./plos/pmed.0020016.txt:          treatment for STIs, and prevention of mother-to-child transmission. The comprehensive
./plos/pmed.0020034.txt:        allergen and the results strongly suggested that exposure in the child's own house was the
./plos/pmed.0020034.txt:        the United States Head Start program (a child-development program that aims to increase the
./plos/pmed.0020039.txt:        number of orphans and vulnerable children, reduce mother to child transmission of the
./plos/pmed.0020061.txt:        The developing fetus and young child is particularly vulnerable to certain environmental
./plos/pmed.0020061.txt:        enter a child's body transplacentally during fetal development or by direct ingestion of
./plos/pmed.0020061.txt:        a child's social and emotional well-being. It is also uncertain whether tests conducted
./plos/pmed.0020062.txt:        in mother and child care, and staff training in cultural competence. Results of the pilot
./plos/pmed.0020067.txt:        those related to poverty reduction, child health, and education. However, there are also
./plos/pmed.0020104.txt:        This is not to say that the big infectious disease killers and child health problems
./plos/pmed.0020182.txt:          maternalâ€“child health clinics in Gaborone or three nearby villages,
./plos/pmed.0020246.txt:            mortality and for the healthy development of the child;
./plos/pmed.0020247.txt:        mother-to-child transmission [7–9]. It may force mothers to expose babies to HIV infection
./plos/pmed.0020249.txt:        studies surprisingly showed that two-thirds of perinatal infections (i.e., mother-to-child
./plos/pmed.0020281.txt:        2005): “To leave the world a bit better, whether by a healthy child, a garden patch or a
```
