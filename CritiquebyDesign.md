# Assignment 3&4: Critique by Design

### Step one: find a data visualization
[MoterSport Stats - Formula One Stats](https://www.motorsportstats.com/results/formula-one/2022/brazilian-grand-prix/standings)
Click on **Constructor** on the left and choose **POS** for **View**.


### Step two: critique the data visualization
![image](https://user-images.githubusercontent.com/102596125/202081814-48d6bbb8-7256-42b5-8021-555e88b7c29c.png)
![image](https://user-images.githubusercontent.com/102596125/202081835-d13f1da6-5b20-46b9-86c6-2dec75fd28f6.png)
![image](https://user-images.githubusercontent.com/102596125/202081853-37ac0604-db77-46ae-a304-d64d18642bd4.png)
![image](https://user-images.githubusercontent.com/102596125/202081866-2c9cabf3-fa89-4b77-89eb-aa3ef32b57e5.png)
<br />
Source: [Motor Sport Stats](https://www.motorsportstats.com/results/formula-one/2022/brazilian-grand-prix/standings)


### Step three: sketch out a solution
![image](https://user-images.githubusercontent.com/102596125/202118298-473ebf8d-83f2-4a4f-9136-a1ffcff15bc8.png)


### Step four: Test the solution
Q1: In 10 seconds, can you tell me what this chart is about?<br />
Q2: Which part of the chart is the most eye-catching?<br />
Q3: What are the things that you are confused? <br />
Q4: I will explain to you what this chart is about. After that, tell me your new concentration on this chart.<br />
Q5: If you are a fan of F1, what else do you wish to see? What on this chart you want to see less.<br />

Interviewee  | Feedback
------------- | -------------
Student, mid 20'  | A1: Maybe a geographic report because I saw national flags on the top.<br />A2: The way the chart was made was clean and concise.<br />A3: I noticed the numbers in the chart but had no idea what those were about. No title telling me what type of data it is.<br />A4: (After listening to my explanation) Now much better. I started to find the constructor who won the most championships. But I still don't understand the meaning of FL and PP, which were all over the chart.<br />A5: I'd like to see my favorite constructor's logo in the chart. That makes me more excited.
Student, late 20'  | A1: Some kind of games or matches between national teams.<br />A2: All the top three numbers for each country were highlighted, which was good because that tells me directly who won the game.<br />A3: What do "PTS" and "GAP" mean? And why the last country has no data at all?<br />A4: Okay, now I learned that Red Bull is the best team while Williams got a lot of improvement space. I'm focusing on finding out the trend for mid-table teams. And I'd also like to know the ranking gap between the two drivers for each constructor.<br />A5: I don't think having the constructor logos on the left of their names was a good idea. You should eliminate the duplicated information. You might need to get rid of the blank column at the end as well.


### Step five: Build your solution
**Original data visualization:**
![image](https://user-images.githubusercontent.com/102596125/202100403-4d97898a-d48b-4858-8b40-febc6336b965.png)
Source: [Motor Sport Stats](https://www.motorsportstats.com/results/formula-one/2022/brazilian-grand-prix/standings)

**Revision Steps:**
1. It was hard for me to figure out constructors' positions in each grand prix as my eyes were looking to the bottom right. The table was too large for me to link a constructor and its position in those late grand prixes.<br />
**Solution:** Redesigned the table from the vertical view to a horizontal view.<br /><br />
2. The audience doesn't understand the meaning of "FL" and "PP".<br />
**Solution:** Since those were not important to the information delivery, I have removed from the chart.<br /><br />
3. There were large blank spaces between the constructors and the corresponding data to the right. Meanwhile, it took time for me to read the constructors' names given some of them had similar calls.<br />
**Solution:** Replaced the constructor names by their logos and shortened the spaces. Easily for the audience to locate their favorite team.<br /><br />
4. People would like to see the gaps between teammates. They wanted to know whether the positions were because of teamwork or individual effort.<br />
**Solution:** Added the position data for the other driver in each team.<br /><br />
5. The plain white background didn't show any trends. The audience would like to see whether a team was improving or falling behind.<br />
**Solution:** Use heat map method to show this pattern.<br /><br />
6. Still too many numbers. The revised version made me feel dizzy.<br />
**Solution:** Removed all positions except the top 3. People only care about who won the games. We don't need the rest; let the colors tell the trends.<br /><br />
7. A title would be helpful for non-F1 fans to understand what this chart is about.<br />
**Solution:** Added a title.<br /><br />
8. The bright "DNF" signs distracted the audience from finding the champions given that all numbers are in a dark color.<br />
**Solution:** Darkened the "DNF" signs. Hightlighted the champion for each grand prix.<br /><br />
9. The first revision has an ugly Excel-generated color series.<br />
**Solution:** Blue and orange always had an amazing mechanism. Made orange as the highest position and blue as the lowest. The darkest blue means that a driver didn't finish the game.<br /><br />

## FINALLY: THE ULTIMATE VISUALIZATION👇
![image](https://user-images.githubusercontent.com/102596125/202099385-da192375-5f59-443e-91b3-7987a166698d.png)
