package models;

import java.util.ArrayList;
import java.util.List;

public class Round
{
	private Game game;
	private int numberOfRound;
	private List<PlayerRoundData> playersData;
	
	public Round()
	{
		playersData = new ArrayList<>();
		for(int i=0; i < game.getPlayers().size(); i++)
		{			
			playersData.add(new PlayerRoundData());
		}
	}
	
	public Game getGame() {
		return game;
	}

	public void setGame(Game game) {
		this.game = game;
	}

	public int getNumberOfRound() {
		return numberOfRound;
	}

	public void setNumberOfRound(int numberOfRound) {
		this.numberOfRound = numberOfRound;
	}

	public List<PlayerRoundData> getPlayersData() {
		return playersData;
	}

	public void setPlayersData(List<PlayerRoundData> playersData) {
		this.playersData = playersData;
	}
}
