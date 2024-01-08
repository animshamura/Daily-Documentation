<h1>Logic Discussion :</h1>

<h2>☐ To create n square numbers of n digits. <br/></h2>
<h4>1, 6 and 9 are going to be used here. <br/> <br/>
  Firstly there would be 169 and (n-3) 0s correspondingly. <br/> <br/>
  Then, a loop has to be run n/2 times. <br/> <br/>
  Each time simply execute (1 + i times 0s + 6 + i times Os + 9 + (n- 2i - 3) times 0s) <br/> <br/>
  and (9 + i times 0s + 6 + i times Os + 1 + (n- 2i - 3) times 0s). <br/> </h4>

<h2>☐ You can find an array of integers which form a target integer. <br/></h2>
<h4>You will have to find some integers those are not mentioned.<br/><br/>
It's as simple as it is. You got to find the multiplication of the given integers. <br/><br/>
Then, if the result is a factor of the target integer then you can find the rest integers. <br/><br/>
The first one of the remaining would be target/result and the rest would be only 1s.<br/></h4>
<h2>How can you find longest palindrome length? <br/></h2>
<h4> First convert the string to a set.<br/><br/>
Count occurance of each character if it is odd.<br/><br/>
Add occurence times - 1 to the result.<br/><br/>
Otherwise, add only occurences to result. <br/> <br/> 
After the execution if any odd occurence had occured, add 1 to the result. <br/>
</h4>

