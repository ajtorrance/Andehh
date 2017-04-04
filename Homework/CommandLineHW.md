1. wc chipotle.txt
Order ID, quantity, item name, choice description (what is on the item, salsa/beans/guac etc, or soda flavor), price

2. 1834 orders, tail chipotle.txt, last order # given that head chipotle.txt starts with 1

3. wc chipotle.txt 4623 lines
4. grep "Steak Burrito" chipotle.txt > steak.txt
   grep "Chicken Burrito" chipotle.txt > chicken.txt
   wc chicken.txt (returns 553 lines)
   wc steak.txt (returns 368 lines)
   Chicken Burrito is more popular than steak burrito!
   
5. grep "Black Beans" chicken.txt > BBchicken.txt
   grep "Pinto Beans" chicken.txt > PBchicken.txt
   wc BBchicken.txt (returns 282 lines)
   wc PBchicken.txt (returns 105 lines)
   Black beans are more popular on the chicken burrito

6.
