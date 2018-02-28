# batstats2
second attempt from laptop

Problem:

Keep track of a single baseball player's hitting.

Solution:

Enter the data in a program that keeps track and calculates percentages.

GUI Based:

	-Have a form to enter stuff.

	-Have a panel that displays current data.

	-Save the stats to text on a harddrive.
	
	-Be able to create new players, get the existing player, and enter in new stats

Practicing:

	-OOP
	-Learn GIT and GITHub
	-Fun with programming and baseball
	
Class design:

	Player {
		Name - constant, string (after initial entering)
		Number	- constant, int (after initial entering)
		Position - constant, string (after initial entering)
		Games played - variable int, starts at 0, increments with each game
		Innings played - variable int, starts at 0, increments with each inning played
		At Bats - int times at bat (total)
		Wins - variable int, increments with each win
		Losses - variable int, increments with each loss
		Strike
			Swing
			NoSwing
			Foul		
		
		Contact - 
			Fly
			Grounder
			Tip
					
		Hits - variable int, increments with each hit
			Singles - variable int, increments with each Single, sub of hit
			Doubles - variable int, increments with each Double, sub of hit
			Triples - variable int, increments with each Triples, sub of hit
			RBI - variable int, increments with each RBI, sub of hit,
			HomeRun - variable int, increments with each HomeRun, adds to Run, sub of hit
		Run - variable int, increments with each increases with each run, not necessarily sub of hit, but most often
			HomeRun - variable int, increments with each HomeRun, sub of Run, sub of hit
			
		Walk - variable int, increments with each walk, not a hit
		OBP - calculated variable float, percentage of times at bat that gets to a base. Includes walks
		battingAverage -calculated variable float, percentage of times at bat that gets to a base, does not include walks
		Outs - variable int, increments with each out
			fly out - sub of out, variable int, increments with each fly out
				infield fly out -sub of 
			strikeOut - sub of out, variable int, increments with each out
			
			

