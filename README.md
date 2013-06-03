getwinner-final-
================

/**
 * Write a description of class getWinner here.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */
public class getWinner extends DeckTotal
{
    // instance variables - replace the example below with your own
    private int x;
    private int y;
    private String playerOne;
    private String playerTwo;
    /**
     * Constructor for objects of class getWinner
     */
    public getWinner()
    {
        // initialise instance variables
        x.getDeckTotal();
        y.getDeckTotal();
    }
    public String players()
    {
       x.add(playerOne);
       y.add(playerTwo);
    }
    /**
     * An example of a method - replace this comment with your own
     * 
     * @param  y   a sample parameter for a method
     * @return     the sum of x and y 
     */
    public int winningNum()
    {
       
 if(x > 21)
 {
 return "playerOne" + "" + "isBust";
 }
    else
     {
          if(x <= 21 && x > y)
            {
                return "playerOne" + "" + "isWinner";
            }
            return "playerOne" + "" + "isLoser";
      }
 if(y > 21)
 {
     return "playerTwo" + "" + "isBust";
 }
    else
    {
        if(y <= 21 && y > x)
        {
            return "playerTwo" + "" + "isWinner";
        }
            return "playerTwo" + "" + "isLoser";
     }
    }
}
