# Dominion: collectable card game deck builder

## Copyright Information

<h1>Welcome to the Dominion Deck Builder</h1>

<h2> Search here for cards </h2>

<form>
	Card Name:<br>
	<input type="text" name="cardname"><br>

	Card Type:
	<input type="radio" name="cardtype" value="MP" checked> MP<br>
	<input type="radio" name="cardtype" value="Campaign"> Campaign<br>
	<input type="radio" name="cardtype" value="Tactic"> Tactic<br>
	<input type="radio" name="cardtype" value="Political Capital"> Political Capital<br>
	<input type="radio" name="cardtype" value="Bills"> Bills<br>
	<input type="radio" name="cardtype" value="Private Member's Bills"> Private Member's Bills<br>

	Party:
	<select>
  		<option value="Cons">Cons</option>
  		<option value="Grits">Grits</option>
  		<option value="Dippers">Dippers</option>
  		<option value="Tories">Tories</option>
		<option value="CRAP">CRAP</option>
		<option value="Sep">Sep</option>
		<option value="Greens">Greens</option>
	</select>

	<input type="submit" value="Submit">
</form>
