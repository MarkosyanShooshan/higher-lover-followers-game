Higher Lower Game (Instagram Followers) 📈📉

[Armenian] Սա հանրահայտ "Higher Lower" խաղի Python տարբերակն է, որն աշխատում է հրամանային տողում (CLI):
Խաղացողին առաջարկվում է համեմատել սոցիալական մեդիայի երկու հայտնի էջեր (անունը, գործունեությունը և երկիրը) 
և գուշակել, թե նրանցից ով ունի ավելի շատ հետևորդ (followers) Instagram-ում: Յուրաքանչյուր ճիշտ պատասխանից 
հետո միավորները ավելանում են, իսկ սխալվելու դեպքում խաղն ավարտվում է:

[English] This is a command-line (CLI) adaptation of the famous "Higher Lower" web game, built using Python.
Players are presented with two famous social media accounts (displaying their name, description, and country)
and must guess who has more Instagram followers. Every correct guess increases the score, and a single wrong
answer ends the game.



 Features

* Դինամիկ համեմատություն (Dynamic Comparisons): Յուրաքանչյուր հերթում նախորդ հաղթող "B" տարբերակը դառնում
  է նոր "A" տարբերակ, իսկ որպես "B" ընտրվում է նոր պատահական էջ:
* Կրկնությունների բացառում (No Duplicates): Խաղը երաշխավորում է, որ "A" և "B" տարբերակները երբեք չեն լինի
  նույն էջը:
* Մոդուլային կառուցվածք (Modular Design): Տվյալները պահվում են առանձին `game_data.py` մոդուլում՝ կոդը
  մաքուր և կազմակերպված պահելու համար:
