Here are the basic steps I went through in this course



#Clone init repo from github
	https://github.com/uniOpifex/command-line-mystery.git
$ cat readme.md
$ cat instructions
$ cd mystery

$ grep "CLUE" crimescence

#suspect is a tall 6' male with memberships AA, Delta SkyMiles, the local library, and the Museum of Bash History
#talk to a Anibel for more infor

$ grep "Annabel" people
#Annabel Church	F	38	Buckingham Place, line 179

#search streets for Buckingham_Place

$ head -n 179 streets/Buckingham_Place | tail -n 1
SEE INTERVIEW #699607

$ cat interviews/interview-699607
#car fled the scene. Blue Honda. Tag: L337<unknown>9

$  grep -A 5 "L337" vehicles

#short remaining memberships

$  cat /memberships Delta_SkyMiles AAA Terminal_City_Library Museum_of_Bash_History | grep "Jeremy Bowers"

#Jeremy Bowers is the only one which meets all criteria

