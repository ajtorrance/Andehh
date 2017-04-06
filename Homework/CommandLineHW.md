1. wc chipotle.txt
Order ID, quantity, item name, choice description (what is on the item, salsa/beans/guac etc, or soda flavor), price<br></br><br></br>

2. 1834 orders, tail chipotle.txt, last order # given that head chipotle.txt starts with 1<br></br><br></br>

3. wc chipotle.txt 4623 lines<br></br><br></br>
4. grep "Steak Burrito" chipotle.txt > steak.txt <br></br>
   grep "Chicken Burrito" chipotle.txt > chicken.txt<br></br>
   wc chicken.txt (returns 553 lines)<br></br>
   wc steak.txt (returns 368 lines)<br></br>
   Chicken Burrito is more popular than steak burrito!<br></br><br></br>
   
5. grep "Black Beans" chicken.txt > BBchicken.txt<br></br>
   grep "Pinto Beans" chicken.txt > PBchicken.txt<br></br>
   wc BBchicken.txt (returns 282 lines)<br></br>
   wc PBchicken.txt (returns 105 lines)<br></br>
   Black beans are more popular on the chicken burrito<br></br><br></br>

6.git clone https://github.com/ga-students/DS-SEA-06 <br></br>
find data /*.csv | find data /*.tsv | wc -l <br></br>

7. grep -r -i "dictionary" . | wc -w 1174
