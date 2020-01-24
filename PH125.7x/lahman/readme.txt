The Baseball Archive Baseball Database
Version 4.5
Release Date: March 26, 2002


----------------------------------------------------------------------
README CONTENTS
  0.1 Copyright Notice
  0.2 Contact Information

  1.0 Release Contents
  1.1 Introduction
  1.2 What's New
  1.3 Acknowledgements
  1.4 Registration
  1.5 Using this Database
  1.6 Revision History

  2.0 Data Tables
  2.1 MASTER table
  2.2 Batting Table
  2.3 Pitching table
  2.4 Fielding Table
  2.5 All-Star table
  2.6 HOF table
  2.7 Managers table
  2.8 Teams table
  2.9 Awards table
 2.10 PostBatting table
 2.11 PostPitching table
 2.12 TeamMaster table

----------------------------------------------------------------------
0.1 Copyright Notice & Limited Use License

This database is copyright 1996-2002 by Sean Lahman. A license is granted
for individual use for research purposes. It may not be re-distributed
without permission. Any commercial use, or other dissemination of the
database in part or in whole is prohibited. Use of this database
constitutes acceptance of these terms.  

For licensing information or further information, contact the Baseball
Archive at: database@baseball1.com

----------------------------------------------------------------------
0.2 Contact Information

Web site: http://www.baseball1.com
 E-Mail : database@baseball1.com

This database can also be purchsed on CD-ROM.  
See http://baseball1.com/statistics for more details.

----------------------------------------------------------------------
1.0  Release Contents

This release of the database can be downloaded in several formats. The
contents of each version re listed below.

MS Access Version:
   baseball45.mdb     Database in Microsoft Access format
       readme.txt     This documentation file

Comma Delimited Version:
     allStars.csv   --
       awards.csv     |
      batting.csv     |
     fielding.csv     |
          hof.csv     |- comma delimited
     managers.csv     |-  data files
       master.csv     |
     pitching.csv     |
  postbatting.csv     |
 postpitching.csv     |
   teammaster.csv     | 
        teams.csv   --
       readme.txt     This documentation file

----------------------------------------------------------------------
1.1 Introduction

This database contains pitching, hitting, and fielding statistics for
Major League Baseball from 1871 through 2001.  It includes data from
the two current leagues (American and National), the four other "major" 
leagues (American Association, Union Association, Players League, and
Federal League), and the National Association of 1871-1875. 

This database was created by Sean Lahman, who pioneered the effort to
make baseball statistics freely available to the general public. What
started as a one man effort in 1994 has grown tremendously, and now a
team of researchers have collected their efforts to make this the
largest and most accurate source for baseball statistics available
anywhere. (See Acknowledgements below for a list of the key
contributors to this project.)

None of what we have done would have been possible without the
pioneering work of Hy Turkin, S.C. Thompson, David Neft, and Pete
Palmer (among others).  All baseball fans owe a debt of gratitude
to the people who have worked so hard to build the tremendous set
of data that we have today.  Our thanks also to the many members of
the Society for American Baseball Research who have helped us over
the years.  We strongly urge you to support and join their efforts.
Please vist their website (www.sabr.org).

This database can never take the place of a good reference book like 
Total Baseball.  But it will enable people do to the kind of queries
and analysis that those traditional sources don't allow.

If you have any problems or find any errors, please let us know.  Any 
feedback is appreciated

----------------------------------------------------------------------
1.2 What's New

Player statistics have been updated through the end of the 2001
season.

Many new fields have been add to the "Master" table. These provide
biographical information about the players included in this database, 
when that information is known.  The new data is:
    Height and weight
    Death date
    Location of birth
    Position

The "position" is derived from the fielding data and represents the
one position that they played most frequently during their career.
Because it has been included in the "Master" table, this information
is no longerincluded in the "batting" table.  Construction of queries
linking the fieldign and batting table can provide information about
positions played for individual seasons.

Post-season wins and losses were added to the managerial table.

Added some statistical categories to the postseason tables.

----------------------------------------------------------------------
1.3 Acknowledgements

Two people have been key contributors to this version of the database.
They also have been trailblazers in taking this database and creating
new things with it. 

The work of Sean Forman to create and maintain an online encyclopedia
at "baseball-reference.com" has been remarkable.  His efforts to help
streamline the database have been extremely helpful. Most importantly,
Forman has spearheaded the effort to provide standards that enable
several different databases to be used together.

The contribution of Tom Ruane's effort to the overall quality of the
underlying data has been tremendous. His creation at "retrosheet.org" 
integrates the yearly data with the day-by-day data, creating a 
reference source of startling depth. It is unlikely than any individual
has contributed as much to the field of baseball research in the past
five years as Ruane has.

Many other people have made significant contributions to the database
over the years.  Sean Holtz helped with a major overhaul and redesign
before the 2000 season. Keith Woolner was instrumental in helping turn
a huge collection of stats into a relational database.  Clifford
Otto & Ted Nye helped provide guidance to the early versions. Lee
Sinnis, John Northey & Erik Greenwood helped supply key pieces of data.
Many others have written in with corrections and suggestions that made
each subsequent version even better than what preceded it. 

The work of the SABR Baseball Records Committee, led by Lyle Spatz
has been invaluable.  So has the work of Bill Carle and the SABR 
Biographical Committee. David Vincent, keeper of the Home Run Log and
other bits of hard to find info, has always been helpful.

Thanks is also due to the staff at the National Baseball Library
in Cooperstown who have been so helpful -- Tim Wiles, Jim Gates,
Bruce Markusen, and the rest of the staff.

A special debt of gratitude is owed to Dave Smith and the folks at
Retrosheet. There is no other group working so hard to compile and
share baseball data.  Their website (www.retrosheet.org) will give
you a taste of the wealth of information Dave and the gang have collected.

Last but not least, we ackowledge the two key figures behind the
Baseball Archive. Sean Lahman launched the Archive's website back
before most people had heard of the world wide web.  Frustrated by
the lack of sports data available, he led the effort to build a 
baseball database that everyone could use. Baseball researchers 
everywhere owe him a debt of gratitude.  In recent years, Lahman
has worked fulltime in the publishing field, serving as co-editor of
the last two editions of Total Baseball (among other things). Enter
Todd Greanier, who has taken over the day-to-day operations of the 
Baseball Archive and ushered it into the 21st century.

Thanks to all contributors great and small. What you have created is
a wonderful thing.

----------------------------------------------------------------------
1.4 Registration

If you use this database, please use the online form to register.
There is no fee. This is completely FREE!  But by registering, it 
enables us to keep you updated when changes are made to the database.
You can register by sending e-mail to database@baseball1.com or by 
visiting the web site at: http://www.baseball1.com/statistics

----------------------------------------------------------------------
1.5 Using this Database

This version of the database is available in Microsoft Access
format or in a generic, comma delimited format. Because this is a
relational database, you will not be able to use the data in a
flat-database application.

If you are unable to import the data directly, you should download the
database in the delimted text format.  Then use the documentation
in sections 2.1 through 2.6 of this document to import the data into
your database application.  

----------------------------------------------------------------------
1.6 Revision History

     Version      Date            Comments
       1.0      December 1992     Database ported from dBase
       1.1      May 1993          Becomes fully relational
       1.2      July 1993         Corrections made to full database
       1.21     December 1993     1993 statistics added            
       1.3      July 1994         Pre-1900 data added 
       1.31     February 1995     1994 Statistics added
       1.32     August 1995       Statistics added for other leagues
       1.4      September 1995    Fielding Data added 
       1.41     November 1995     1995 statistics added
       1.42     March 1996        HOF/All-Star tables added
       1.5-MS   October 1996      1st public release - MS Access format
       1.5-GV   October 1996      Released generic comma-delimted files
       1.6-MS   December 1996     Updated with 1996 stats, some corrections
       1.61-MS  December 1996     Corrected error in MASTER table
       1.62     February 1997     Corrected 1914-1915 batters data and updated
       2.0      February 1998     Major Revisions-added teams & managers
       2.1      October 1998      Interim release w/1998 stats
       2.2      January 1999      New release w/post-season stats & awards added
       3.0	November 1999	  Major release - fixed errors and 1999 statistics added
       4.0      May 2001	  Major release - proofed & redesigned tables
       4.5      March 2002        Updated with 2001 stats and added new biographical data

------------------------------------------------------------------------------
2.0 Data Tables

The design follows these general principles.  Each player is assigned a
unique number (LahmanID).  All of the information relating to that player
is tagged with his LahmanID.  The LahmanIDs are linked to names and 
birthdates in the MASTER table.

The database is comprised of the following main tables:

  MASTER - Player names, DOB, and biographical info
  Batting - batting statistics
  Pitching - pitching statistics
  Fielding - fielding statistics

It is supplemented by these tables:

  AllStars - All-Star appearances
  HOF - Players in the Hall of Fame
  Managers - managerial statistics
  Teams - yearly stats and standings 
  Awards - award winners
  PostBatting - post-season batting statistics
  PostPitching - post-season pitching statistics
  TeamMaster - franchise information

Sections 2.1 through 2.11 of this document describe each of the tables in
detail and the fields that each contains.

Fourteen sample queries are included with the database.  If nothing else,
they provide some examples for building SQL queries that may be pertinent.

---------------------------------------------------------------------------
2.1 MASTER table



LahmanID       A unique number asssigned to each player.  The LahmanID
               links the data in this file with records in the other files.
LastName       Player's last name
FirstName      Player's first name
Bats           
Throws
Ht_Ft          -- Player's height split into two parts
Ht_In          -- feet and inches  
Wt             Player's weight
BirthYear      Year player was born
BirthMonth     Month player was born
BirthDay       Day player was born
DeathYear      Year player died
DeathMonth     Month player died
DeathDay       Day player died
BirthCity      City where player was born
BirthState     State where player was born
BirthCountry   Country where player was born
DebutYear      Year that player made first major league appearance
Position       The one position that this player played most often

------------------------------------------------------------------------------
2.2 Batting Table

LahmanID       Player ID Number
Year           Year
Team           Team
Lg             League
G              Games
AB             At Bats
R              Runs
H              Hits
2B             Doubles
3B             Triples
HR             Homeruns
RBI            Runs Batted In
SH             Sacrifice hits
SF             Sacrifice flies
SB             Stolen Bases
CS             Caught Stealing
BB             Base on Balls
IBB            Intentional walks
HBP            Hit by pitch
SO             Strikeouts
POS            Defensive Positions ranked by frequency of appearances
               C=Catcher, 1=Firstbaseman, 2=Second, 3= Thirdbaseman, 
               S=Shortstop, O=Outfield, D=Designated Hitter, H=Pinch-hitter
               only, R=Pinch-runner only, M=Manager

               Based on the standard notation first used by Total 
               Baseball. A preceding asterisk indicates that the player 
               was a starter at the first listed position.  A starter is
               defined as a player who played 100 games at that position 
               (or 2/3 of a teams scheduled games in seasons prior to 1900).
               Any position following a slash "/" indicates that the player 
               appeared in fewer than 10 games at that position.

------------------------------------------------------------------------------
2.3 Pitching table

LahmanID       Player ID Number
Year           Year
Team           Team
Lg             League
W              Wins
L              Losses
G              Games
GS             Games Started
CG             Complete Games 
SH             Shutouts
SV             Saves
IP             Innings Pitched (using the non-traditional standard 
               of .3 for 1/3 inning and .7 for 2/3 inning)
H              Hits
ER             Earned Runs
HR             Homeruns
BB             Walks
SO             Strikeouts
ERA            Earned Run Average

------------------------------------------------------------------------------
2.4 Fielding Table

LahmanID       Player ID Number
Pos            Defensive position
Year           Year
Team           Team
Lg             League
G              Games 
PO             Putouts
A              Assists
E              Errors
DP             Double Plays

------------------------------------------------------------------------------
2.5  All-Star table

LahmanID       Player ID Number
Year           Year
Team           Team
Lg             League

------------------------------------------------------------------------------
2.6  HOF table

LahmanID       Player ID Number
Inducted       Year of induction
By             Method of Induction (BW=Baseball writers, VC=Veteran's 
               committee, NL=Commitee on the Negro Leagues
Ballots        Total ballots cast in year of induction
Votes          Total votes received
Pct            Percentage of votes received
Pos            Primary playing position
Category       Type of inductee
------------------------------------------------------------------------------
2.7  Managers table

LahmanID       Player ID Number
Year           Year
Team           Team
Lg             League
Div            Division
G              Games managed
W              Wins
L              Losses
Pct            Winning percentage
Std            Team's final position in standings that year
Half           If season was split into halves, denotes 1st or 2nd half
Order          Managerial order.  Blank if the individual managed the team
               the entire year.  Otherwise denotes where the manager appeared
               in the managerial order (1 of 2, 2 of 2, etc.)
PlyrMgr        Player Manager (denoted by 'Y')
PostWins       Wins by manager in post-season
PostLosses     Losses by manager in post-season

------------------------------------------------------------------------------
2.8  Teams table

Year           Year
Team           Team
Lg             League
Div            Team's division
Pos            Position in final standings
G              Games played
W              Wins
L              Losses
Pct            Winning percentage
R              Runs scored
RA             Opponents runs scored
AB             At bats
H              Hits by batters
2B             Doubles
3B             Triples
HR             Homeruns by batters
TB             Total bases
BB             Walks by batters
HBP            Batters hit by pitch
SF             Sacrifice flies
SO             Strikeouts by batters
AVG            Batting average
OBP            On base percentage
SLG            Slugging percentage
SB             Stolen bases
CS             Caught stealing
ERA            Earned run average
CG             Complete games
SHO            Shutouts
SV             Saves
IP             Innings pitched
ER             Earned runs allowed
HA             Hits allowed
HRA            Homeruns allowed
BBA            Walks allowed
SOA            Strikeouts by pitchers
BPF            Three-year park factor for batters
PPF            Three-year park factor for pitchers
Ballpark       Name of team's home ballpark
Attendance     Home attendance total

------------------------------------------------------------------------------
2.9  Awards table

LahmanID       Player ID Number
Award          Name of annual award
Tie            Indicates whether two or more individuals shared the award
Year           Year
Lg             League
Pos            Position for Gold GLove awards, note otherwise

------------------------------------------------------------------------------
2.10  PostBatting table

LahmanID       Player ID Number
Year           Year
Team           Team
Lg             League
Playoff        Level of playoffs (WS = World Series, DIV = Divisional Series,
                 LCS = League Championship Series)
G              Games
AB             At Bats
R              Runs
H              Hits
2B             Doubles
3B             Triples
HR             Homeruns
RBI            Runs Batted In
SH             Sacrifices
SF             Sacrifice flies
SB             Stolen Bases
CS             Caught stealing
BB             Base on Balls
IBB            Intentional walks
HBP            Hit by pitch
SO             Strikeouts


------------------------------------------------------------------------------
2.11  PostPitching table

LahmanID       Player ID Number
Year           Year
Team           Team
Lg             League
Playoff        Level of playoffs (WS = World Series, DIV = Divisional Series,
                 LCS = League Championship Series)
W              Wins
L              Losses
SV             Saves
G              Games
GS             Games Started
CG             Complete Games
SH             Shutouts 
IP             Innings Pitched (using the non-traditional standard 
               of .3 for 1/3 inning and .7 for 2/3 inning)
H              Hits
ER             Earned Runs
BB             Walks
SO             Strikeouts
ERA            Earned run average

------------------------------------------------------------------------------
2.12  TeamMaster table

Team           Team abbreviation
League         Name of League
Start Year     First year of this team's existence
End Year       Last year of this team's existence
City           Name of city where team played
Nickname       Nickname of team

------------------------------------------------------------------------------
<end of file>