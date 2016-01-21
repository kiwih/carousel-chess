# carousel-chess

#### *A game of intrigue and chaos.*

Carousel chess is an adaptation of the rules of chess to create a play-style which supports any odd number of players.

It is the answer to the deeply important question "How can you play chess with 5 players?"

##Overview
Players are randomly divided onto three teams, *White*, *Black*, and *Stalemate* (only one player is on the Stalemate team). Players must not reveal the evidence to other players what team they are on (think Mafia) although it is permissible to talk about which team you are on (as a bluff or in truth).

As play progresses, pieces will be taken by players. Players should tally the value of the pieces they take using the [most common assignment values](https://en.wikipedia.org/wiki/Chess_piece_relative_value). 
  * That is, Pawn: 1, Knight: 3, Bishop: 3, Rook: 5, Queen: 9

If a checkmate should occur, that player is assigned 10 points, and the winning colour gets a bonus 5 points. If a stalemate occurs, the *Stalemate* player automatically wins the game. Note that it is possible for the *Stalemate* player to make the checkmate and still win.

Once a check-mate occurs, the true alignments of each player are revealed to the group, and the teams are scored together. The winning score wins.

##Playing the game

1. First, divide all players randomly into three teams, *White*, *Black*, and *Stalemate*.
  * There should be only one player on the *Stalemate* team
  * Players cannot show evidence for what team they are on, but it is permissible to talk about it

2. Determine randomly which player should start the game. They will open with a white move.
3. Play then progresses around the group, with each player making an appropriate move based on the state of the board, not on their team alignment.
  * If a player has the *White* alignment but is moving for the Black colour on the board, they may choose to do a bad move to disadvantage that team.
  * This should work out that each player will end up moving for black, then for white, then for black, etc...
  * This is the *Carousel*
4. Play continues until either a stalemate or a checkmate occurs.
5. If it is a stalemate, the *Stalemate* player wins.
6. If it is a checkmate, award 10 points to the player that made the move, and 5 points to the colour that won.
7. Reveal team alignments of players, and combine the scores of the *White* players and the *Black* players. 
8. The team with the highest score wins.

##Example of play

 Player | Affinity 
 ---| --- 
Jane | *White*
Joe | *Black*
Jeremy | *Black*
John | *Stalemate*
Jake | *White*

Board Turn | Who moves White? | Who moves Black?
--- | --- | ---
1. | Jane | Joe
2. | Jeremy | John
3. | Jake | Jane
4. | Joe | Jeremy
5. | John | Jake
6. | etc... | etc...

If at any point the game reaches stalemate, John wins as he has the stalemate affinity.

Otherwise, let's say Jane checkmates for a White victory. On her turns, she has captured three rooks (two blacks and a white) as well as three pawns of mixed colours.

Her total score is `15 (Rooks) + 3 (Pawns) + 10 (Checkmate)`.

Jake has captured a Queen and two knights so his total score is `9 (Queen) + 6 (Knights)`.

Their total combined score for *White* is thus `28 (Jane) + 15 (Jake) + 5 (White victory)`.


Notice that it is possible for a team not to win even though their colour on the board wins. In addition, it is possible for the *Stalemate* player to win even though the game may not finish with a stalemate.

##Notes

It was later discovered that these rules add to a pre-existing unorthodox chess game style called [Triune Chess](http://www.chessvariants.com/multiplayer.dir/triune-chess.html)
