# carousel-chess

#### *A game of intrigue and chaos.*

Carousel chess is an adaptation of the rules of chess to create a play-style which supports any odd number of players.

It is the answer to the deeply important question "How can you play chess on one board with 5 players?"

##Overview
At the beginning of the game, put N/2 (rounding down) pieces of paper with *White*, N/2 (rounding down) pieces of paper with *Black*, and 1 piece of paper with *Draw* in a hat.
Each player pulls a piece of paper from the hat, and keeps it secret to themselves. Therefore there is a *white* team, a *black* team, and a *draw* team, but no one knows who else is on their team. Players must not reveal the evidence to other players what team they are on (think Mafia) although it is permissible to talk about which team you are on (as a bluff or in truth).
If there are an even number of players, there should be one piece of paper left in the hat which should be discarded without being shown to the players.

As play progresses, pieces will be taken by players. Players should tally the value of the pieces they take using the [generally accepted piece values](https://en.wikipedia.org/wiki/Chess_piece_relative_value). 
  * Pawn: 1, Knight: 3, Bishop: 3, Rook: 5, Queen: 9

If a checkmate should occur, that player is assigned 10 points, and the winning colour gets a bonus 5 points. If a stalemate occurs, the *Draw* player automatically wins the game. Note that it is possible for the *Draw* player to make the checkmate and still win.

Once a check-mate occurs, the true alignments of each player are revealed to the group. The highest score wins.

##Playing the game

1. First, divide all players randomly into three teams, *White*, *Black*, and *Draw*.
  * There should be only one player on the *Draw* team
  * Players cannot show evidence for what team they are on, but it is permissible to talk about it

2. Determine randomly which player should start the game. They will open with a white move. The game follows normal FIDE rules, other than the turns.
3. Play then progresses around the group, with each player making an appropriate move based on the state of the board, not on their team alignment.
  * If a player has the *White* alignment but is moving for the Black colour on the board, they could choose to do a bad move to disadvantage that team (but they don't have to, as they might be trying to hide their alignment).
  * This should work out that each player will end up moving for black, then for white, then for black, etc...
  * This is the *Carousel*
  * If there are an even number of players, a random player should skip their turn each round.
  
  * When a player captures a piece, they keep the piece in front of them. 
  * If a previously captured piece needs to be used for pawn promotion purposes, then some token should be left with the player to indicate that they had that piece (so they still get the points at the end).
  * When a pawn is promoted, the player who promoted the pawn gets to keep the pawn.
  * We recommend using some marker to indicate the colour of the current move (i.e. white's move or black's move).
4. Play continues until either a stalemate or a checkmate occurs.
5. If it is a stalemate, the *Draw* player receives 100 points (and essentially wins the game).
6. If it is a checkmate, award 10 points to the player that made the move, and 5 points for each player on the team for the colour that won.
  * It is possible for a player to checkmate but not win the game!
7. The individual with the highest score wins.

##Example of play

 Player | Affinity 
 ---| --- 
Jane | *White*
Joe | *Black*
Jeremy | *Black*
John | *Draw*
Jake | *White*

Board Turn | Who moves White? | Who moves Black?
--- | --- | ---
1. | Jane | Joe
2. | Jeremy | John
3. | Jake | Jane
4. | Joe | Jeremy
5. | John | Jake
6. | etc... | etc...

If at any point the game reaches stalemate, John will likely win as he has the draw affinity and this gives him 100 points.

Otherwise, let's say Jane checkmates for a White victory. On her turns, she has captured three rooks (two blacks and a white) as well as three pawns of mixed colours.

Her total score is `15 (Rooks) + 3 (Pawns) + 10 (Checkmate) + 5 (White victory)`.

Jake has captured a Queen and two knights so his total score is `9 (Queen) + 6 (Knights) + 5 (White victory)`.

Jeremy, as he is on the Black team, only gets points for pieces he captured. He has taken three pawns and a bishop so his score is `3 (Pawns) + 3 (Bishop)`

And so forth.

Notice that it is possible for a player not to win even though they might do the checkmating move. In addition, it is possible for the *Draw* player to win even though the game may not finish with a stalemate.

##Notes

It was later discovered that these rules add to a pre-existing chess variant called [Triune Chess](http://www.chessvariants.com/multiplayer.dir/triune-chess.html)
