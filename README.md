Bitcamp
=======

Hackathon at UMD 4/4/14

public Statistics(ArrayList<Integer> myHand, ArrayList<Integer> dealerHand, ArrayList<Integer> deck) {

	this.myHand = myHand;
	this.dealerHand = dealerHand;
	this.deck = deck;
	
	for (int x = 0; x < myHand.size(); x++) {
		handValue += myHand.get(x);
	}
		
	for (int x = 0; x < deck.size(); x++) {
		totalCards += deck.get(x);
	}
	
}
