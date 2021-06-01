# ClothesPurchaseChallange
A small challenge of cloths purchasing algorithms to be validated by the team.
A customer wants to buy a pair of jeans, a pair of shoes, a skirt, 
and a top but has a limited budget in dollars. 
Given different pricing options for each product, 
determine how many options our customer has to buy 1 of each product. 
You can not spend more money than the budgeted amount.
          
Example

priceOfJean = [2,3]
priceOfShoes = [4]
priceOfSkirts = [2,3]
priceofTops = [1,2]

The customer must buy shoes for 4 dollars since there is only one option. 
This leaves 6 dollars to spend on the other 3 items. 
Combination of prices paid for jeans, skirts, 
and tops respectively that add up to 6 dollars or fewer [2,2,2], [2,2,1], [3,2,1], [2,3,1].  
There are 4 ways the customer can purchase all 4 items.

Functional Description 
Complete the getNumberOfOptions function in the editor below. 
The function must return an integer that represents 
the number of options present to buy the four items. 
getNumberOfOptions has 5 parameters:

List<Integer> priceOfJeans : An integer array list that contains the price of the pairs of jeans available.
List<Integer> priceOfShoes: An integer array list that contains the price of the pairs of shoes available.
List<Integer> priceOfSkirts: An integer array list that contains the price of the skirts available.
List<Integer> priceOfTops : An integer array list that contains the price of the tops available.
int dollars: The total number of dollars available to shop with.

import java.io.*;
import java.util.*;

class Result {
	/**
	* Complete the 'getNumberOfOptions' function below.
	* The function is expected to return a LONG_INTEGER;
	* The function accepts following parameter:
	* 1.INTEGER_LIST priceOfJeans
	* 2.INTEGER_LIST priceOfShoes
	* 3.INTEGER_LIST priceOfSkirts
	* 4.INTEGER_LIST priceOfTops
	* 5.INTEGER	 dollars
	*/

	public static long getNumberOfOptions(List<Integer> priceOfJeans,
					List<Integer> priceOfShoes,
					List<Integer> priceOfSkirts,
					List<Integer> priceOfTops,int dollars)
	{

		return ? ;
	}
