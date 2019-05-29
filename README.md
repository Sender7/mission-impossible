# Mission impossible, but coding is  

 
Once upon a time on one of the vessel. There was a mighty crew with big stomachs. Chef has accidentally locked refrigerator. Chef has gracefully forgot the password. In order to avoid riots on the vessel. The crew needs your help to solve the maze and open the refrigerator doorlock. Your goal is to solve this maze within 60 minutes and save crew's stomachs.

## Before we begin

### Requirements:

- Clone project from github (https://github.com/Sender7/mission-impossible)
- Python 3.5 or later 
- PyCharm or any other IDE for Python
- Run command in Terminal or Command line inside project folder "*pip install -r requirements.txt*
"

## Quest 1

The 1st engineer remembers that first password number has been missing somewhere in the calculations. Your goal is to simulate integer arithmetic overflow and retrieve the phrase to execute. In order to do that you have to post request to url  with 

Url: /api/v1/calculator
* In the file by parameter name QUEST_1_URL_CALCULATOR *

Body:
{ a: 1, b: 1 }

After you receive the overflow you have to execute method with specific code phrase in MissionImpossible.py file

## Quest 2

After retrieving successfully from calculations the first digit. The captain has called to memory that the third digit of the password can be found in the history of web.Exactly in the first web page. This was long time ago in 1989 when the web was only in Universty of CERN and available for few scientists. Scientists has hidden in the content of the page the 3rd digit of the password and doesn't remember what is the number but remembers the algorithm. 

The scientists were smart and masked it into under the special algorithm:

1. Required to read all characters of the first web page
2. Count occurence of 3 characters ["s", "e", "a" ] in text
3. Multiply every character occurence on representation of the character symbol in byte value in ASCII table (e.g. "s" = 115)
4. Sum all results from the previous step
5. Take modulus of 8 from the sum of values from previous step

**Hints:** 
Use ASCII table to find proper characte [http://asciiset.com/]
Url for the first webpage content can be found in python file  QUEST_2_FIRST_WEB_PAGE_URL

## Quest 3 

The crew was so happy that have been able to find the 3rd digit of the password and started guessing the password. Crew started entering different combinations for the doorlock. The response was slow from the doorlock and it took for every request to respond at least 10 seconds.Thus, brute force is not an option. 

The intendant of the ship has started reviewing documents on his table. He found the clue that in one of the document there is hidden sign for the 4th digit. The file is encoded with special from binary to text encoding, which is widely used nowadays. The  4th digit  is stored on a new line after the phrase "I need this key". 

**Hint:** 
- The encoding widely used in the web starts with "base" 


## Quest 4

After finding the 4th digit it came out that crew had no anymore clues to find the last digit. One member of the crew has told that there is an option, which require to try different variants.
 
**Hint:** The doorlock url is https://missionimpossible.appspot.com/api/doorlock?code= and HTTP Request Get method


