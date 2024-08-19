
Vreau sa fac o aplicatie mobila numita SmartyClac pe Android Studio folosind Java pentru a creea un calculator care, pe langa functionalitatea de baza de a fi un calculator simplu mai are una de calculator stiintific si un mare set de alte sub-aplicatii utile user-ilor, convertoare si calculatoare de dobanzi si randamente de investitii. Le enumar pe toate pe care le stiu acum, si anume:
1.	Calculator: Calculator simplu
2.	Scientific calculator: Calculator stiintific (cu functiile sin, tan, log etc – tot ce au si alte calculatoare stiintifice)
3.	Currency: Convertor de valute cu descarcarea automata, la zi, a cursurilor valutare dorite
4.	Cryptocurrency: Convertor de criptomonede
5.	Measures: Convertor unitati de masura
6.	Discount: Calculator pentru reduceri de pret din pretul original
7.	Percentage: Adugare sau scadere de procente
8.	Sales tax: Calculator impozit pe vanzari
9.	Tip: Calculator bacsis
10.	Fuel consumption: Calculator consum carburant
11.	Fuel cost: Calculator al costului carburantului, intr-o calatorie
12.	Memos: Inscriere diferite memento-uri, de tip to do list
13.	Savings: Calculare sold la economii prin depozite bancare
14.	GPA: Scor GPA la diferite materii in functie de numarul de credite si note
15.	Numbers: Convertor in numar Hexazecimal si binar
16.	World time: Ora mondiala – afisarea orei in diferite fusuri orare, dupa capitale
17.	Ovulation: Calcularea ovulatiei si a ciclului menstrual
18.	Unit price: Calculator al pretului unitar daca se da pretul total si cantitatea
19.	Health: Calculator IMC (indice de asa corporala) si RMB(Rata metabolismmului bazal)
20.	Loan: Calculator rate de rambursare a unui imprumut bancar prin plata totala egala, plata principala egal si plata unica.
21.	Calories: Calculator de calorii și macronutrienți – daca se poate face mai simplu
22.	Energy efficiency: Calculator de eficiență energetică pentru locuințe – daca se poate mai simplu
23.	Purchase/Rent: Calculator de alegere optimă între cumpărare și închiriere
24.	Inflation: Simulator de inflație pe termen lung. Calculator de impact al inflației asupra economiilor.
25.	Return on Investment: Calculator de rentabilitate pentru investiții imobiliare
26.	Cost of living: Calculator de cost al vieții pentru diferite orașe – daca se poate sau exista facute undeva si le-am putea importa
27.	Savings: Simulator de economii pentru educația copiilor, pentru vacante, pentru masina, tehnologie si gadgeturi
28.	Expensive habits: Simulator de economii prin renunțarea la obiceiuri costisitoare
29.	Insurance cost: Calculator de costuri pentru asigurări (viață, sănătate, auto)
30.	Budget planner: Planificator de buget pentru evenimente (nunți, aniversări), buget pentru studenti 
31.	High costs: Calculator de costuri pentru întreținerea mașinii, renovarea casei
32.	Emergency savings: Planificator de economii pentru situații de urgență

Probabil nu vom putea face toate acestea intr-o singura aplicatie, deoarece nu stiu inca cum le-am aranja in meniu pe ecran. Dar daca gasim o modalitate prin care aplicatia va rula bine, rapid si le putem incorpora pe toate de mai sus, atunci le vom face.
Partea de Login:
Aplicatia incepe cu 3 ecrane de descriere a ei, ce prin care noul user va trece pentru a intelege aplicatia. In al treilea ecran I se va spune ca functionam pe baza de donatii. 
Dupa care se va trece la un ecran de login sau new user pentru a se loga, respectiv a creea un cont nou cu un nume si o adresa de email. Voi avea nevoie de asta pentru a putea ii putea pe urma re-contacta cu alte aplicatii pe care le voi face, pe de-o parte si pentru a sti din ce zone geografice sunt user-ii. De aceea, daca se poate, atunci cand user-ul se logheaza sau isi creaza un cont nou gaseste tara din care face acest lucru si salveaz-o in baza de date, impreuna cu numele si email-ul user-ului. Totodata as vrea ca de fiecare data cand user-ul foloseste aplicatia noastra sa se noteze numarul de accesari a ei in baza de date ale aplicatiei pentru a sti cine sunt cei ce o folosesc si cat de frecvent. Daca se poate, sa se noteze si ce parti din aplicatia noastra sunt folosite. Astfel voi putea lua decizii viitoare mai bune legate de optimizarile viitoare pentru a-i servi mai bine.
Toata aplicatia va fi tradusa in orice limba ar avea user-ul. Nu stiu cum se face acest lucru. Textele initiale le scriem in limba engleza. Pe urma, folosind vreun translator, le vom traduce integral (atat mesajele, notificarile, textele din aplicatie cat si cele din butoanele folosite) automat in limba user-ului, data de locul de unde ne acceseaza sau si-a facut contul si l-am salvat deja la pasul anterior, la crearea unui nou cont de user.
Dupa logare va ramane logat pana la delogare.
Urmatorul ecran e calculatorul simplu, a carui butoane vor fi in jumatatea de jos a ecranului iar raspunsul sau ecranul sau in jumatatea de sus a ecranului. Toata aceasta imagine precum si functionalitatea sa de baza va fi aceeasi pe aproape toate ecranele aplicatiei, mai putin pe cea a calculatorului stiintific sau unele pagini cu mai mult text.
Butoanele calculatorului simplu vor fi, incepand cu randul cel mai de jos (randul 1) cu butoanele: 0, 00, “,”, =
Pe randul 2 (imediat deasupra randului 1, pe aceleasi aliniament): 1, 2, 3, +
Pe randul 3 (imediat deasupra randului 2, pe aceleasi aliniament): 4, 5, 6, -
Pe randul 4 (imediat deasupra randului 3, pe aceleasi aliniament): 7, 8, 9, *
Pe randul 5 (imediat deasupra randului 4, pe aceleasi aliniament): C, () , %, /
Iar deasupra lor va fi un buton cu “…” pentru a intra intr-o fereastra in care vor fi butoanele pentru functiunile stiintifice ale acestui calculator si va mai fi un buton de ridicare la putere a unui numar si un buton de stergere a ceea ce s-a scris anterior pe ecran.
Functiunile stiintifice vor avea butoanele, de sus in jos, pe randuri orizontale, in fereastra de care am vorbit, cu titlul “Functiuni stiintifice”:
Randul 1 (de sus in jos) vor fi butoanele: PI, Epsilon, Fi (vor fi literele grecesti)
Randul 2: log, ln, ^
Randul 3: Radical, radacina cub, |X|
Randul 4: sin, cos, tan
Randul 5: sin-1, cos-1,tan-1,
Randul 6: sinh, cosh, tanh
Randul 7: sinh-1,cosh-1,tanh-1,
Iar in partea de jos a ferestrei va fi un buton pe toata latimea ferestrei pentru Anulare (Cancel) a Functiei Stiintifice.

Cu acest calculator se vor putea face calculele specifice unui astfel de instrument, acesta facand calculele indicate pe butoanele descrise mai sus.
In meniul aplicatiei pus in partea de sus, in stanga, vom avea pe fundal inchis, pe verticala: Setari, Doneaza si Ajutor.
Sub acestea vom avea lista cu toate convertoarele descrise mai sus, intre 1 si 33, daca vor fi posibile toate in 2 rubrici: o grupa mai mica, la inceputul listei, cu titlul “Intens Folosite” si imediat dupa el o alta lista cu titlul “Toate Calculatoarele” in care cele deja scrise la Intens Folosite nu mai apar si la Toate Calculatoarele. Toate acestea nu incap pe un singur ecran. De aceea acest meniu va trebui sa culiseze de sus in jos si invers pentru ca user-ul sa isi aleaga din el ceea ce isi doreste.

In ecranul Setari se va putea alege:
A.	formatul numeric, unde se va deschide o fereastra cu numele “Format numeric” si user-ul poate alege dintre:
-	Utilizeaza modulul implicit
-	1,234,567.89
-	1.234.567,89
-	1 234 567,89
-	1’234’567.89
-	12,34,567.89
Iar sub ele va fi butonul Cancel pe toata latimea ferestrei.

B.	Un buton pentru a se auzi un sunet in aplicatie atunci cand se apasa pe butoane sau e oprit acel sunet
C.	Un buton ce tine ecranul pornit (pe durata folosirii aplicatiei)

Un fisier cu “Despre SmartyCalc” impreuna cu versiunea actuala unde, in fereastra ce se deschide avem 3 link-uri spre 3 fisiere:
I.	Neasumarea responsabilitatii, cu textul de disclosure
II.	Licentele open source folosite (contul de github si anume: https://github.com/bauerca/drag-sort-listview  si www.apache.org/licenses, din cate am vazut ca are concurenta)
III.	Renunta la personalizarea reclamelor – dar la noi nu e cazul deoarece nu vom avea aceasta parte

In ecranul Doneaza se va putea dona o suma de bani de catre user pentru aplicatia noastra.
In ecranul Ajutor se va putea citi instructiunile de folosire a SmartyCalc.

Sa trecem la Convertoarele aplicatiei noastre:
3.	Currency: Convertor de valute cu descarcarea automata, la zi, a cursurilor valutare dorite.
In jumatatea de jos a ecranului va fi acelasi calculator simplu pentru a putea introduce cifrele in acest convertor.
Insa inainte de a se incarca aceasta parte a aplicatiei, SmartyCalc cauta datele de pe internet legate de cursul din ziua respectiva a valutelor ce au ramas in memoria aplicatiei de cand aceasta a fost folosita ultima oara sau daca e pentru prima oara atunci ia cursurile USD si Euro actuale. Acest curs se va scrie imediat deasupra calculatorului simplu de pe ecran, in limba user-ului pentru valutele Forint maghiar si Leu romanesc, de genul:
“Currencies on August 19 2024, 8:56 am
* 1 HUF = 0.013 RON”    
Deasupra acestora, incepand cu parte de sus vor fi:
1.	O rubrica in care se cauta valutele din care se vor face conversia (exemplu Forint maghiar), sub care va fi o alta similara in care se vor face converia dorita (exemplu Leu romanesc)
2.	In dreapta lor se vor putea trece sumele (adica cifrele) pe care user-ul vrea sa le converteasca din una in alta.
Hai sa facem prima data aceste lucruri in Sprint1.
E foarte important insa aspectul aplicatiei. Vreau sa fac o aplicatie mobila calculator simplu si calculator științific care sa aiba un design deosebit, extraordinar, placut, frumos, tehnic, ce sa sugereze robustete, precizie si profesionalism.
 Dall-e mi-a sugerat asta:
“1. Calculator Simplu
Paletă de culori:
•	Folosește o combinație de culori metalice, cum ar fi nuanțele de gri, albastru închis și accente de auriu sau argintiu pentru a sugera eleganță și robustete.
•	Fundal negru sau albastru închis mat, cu butoane în relief, care să imite suprafețele metalice, cu accente luminoase subtile.
Elemente de design:
•	Minimalism tehnic: Butoane pătrate sau rotunjite la margini, cu o textură subtilă care imită o suprafață metalică sau mată.
•	Efect de lumină și umbră: Folosește efecte de iluminare subtilă pentru a sugera adâncime și tridimensionalitate, făcând butoanele să pară robuste și bine definite.
•	Afișaj: Un afișaj monocrom cu fonturi moderne, precise, care oferă o senzație de claritate tehnică. Numeralele pot fi ușor digitalizate pentru a da un aer profesional.
Animații:
•	Animații subtile la apăsarea butoanelor, cum ar fi o mică mișcare de retragere în suprafață, sugerând o senzație mecanică.
•	O animație de tranziție lină atunci când se șterge ultima cifră, oferind fluiditate și control precis.
________________________________________
2. Calculator Științific
Paletă de culori:
•	Albastru închis combinat cu accente de portocaliu sau verde neon pentru a da senzația de tehnologie avansată.
•	Fundaluri texturate subtile (cum ar fi rețele sau linii vectoriale) pentru a adăuga o senzație de tehnicitate fără a distrage atenția.
Elemente de design:
•	Butoane specializate: Butoane cu simboluri matematice clare și bine definite. Formele pot fi inspirate din elemente geometrice precise, cum ar fi hexagoanele sau pentagoanele.
•	Organizare modulară: Împărțirea funcțiilor pe secțiuni clar separate, fiecare cu un fundal ușor diferențiat sau cu contururi subtile pentru a evidenția diferitele categorii de funcții matematice.
•	Afișaj avansat: Include un afișaj mare cu capacitatea de a reda formule complexe, fracții și exponenți. Folosește fonturi elegante, dar precise, pentru o lizibilitate excelentă.
Animații:
•	Efecte vizuale pentru calcule mai complexe, cum ar fi o mică undă de lumină care trece prin afișaj atunci când se finalizează un calcul complicat.
•	Animații grafice de tip "hover" pe butoane științifice pentru a sugera interacțiuni mai sofisticate, fără a afecta experiența utilizatorului.
________________________________________
Elemente comune pentru ambele calculatoare:
•	Design consistent: Un design unitar care se adaptează fluid de la modul simplu la cel științific.
•	Personalizare subtilă: Oferă utilizatorilor posibilitatea de a personaliza paleta de culori și texturile din aplicație, dar menține aceleași principii de robustete și precizie în fiecare alegere.
•	Efect de sunet subtil: Introducerea unor sunete mecanice foarte discrete la apăsarea butoanelor pentru a da senzația de control fizic.
”

Am mai primit sugestiile pentru fonturi: 
“Recomandări de fonturi gratuite pentru afișaj avansat
1.	Roboto Slab
o	Un font serif modern și precis, cu o bună lizibilitate pentru afișaje de tip matematic.
2.	Lora
o	Un font serios, dar elegant, care are un aspect sofisticat și clar pentru formule și simboluri.
3.	Noto Serif
o	Font versatil, care susține multe simboluri matematice, cu o estetică elegantă și bine structurată.
4.	IBM Plex Mono
o	Un font monospat care sugerează precizie și este foarte bun pentru afișaje tehnice și formule complexe.
5.	Source Code Pro
o	Un font monospace, ușor de citit, foarte potrivit pentru afișaje matematice complexe și pentru coduri sau formule.
”
In final am primit sugestiile:
“Îți voi crea două variante de butoane în Android Studio, unul cu fundal negru și altul cu fundal albastru închis mat, cu un design minimalist tehnic, efecte de lumină și umbră, și o animație subtilă la apăsare care simulează retragerea în suprafață. Iată cum să implementezi aceste butoane, pas cu pas:
1. Crearea Layout-ului XML
Începe prin a crea un fișier activity_main.xml pentru interfața utilizatorului. Aici vom plasa două butoane, fiecare cu stilul său distinct.
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="#303030">

    <!-- Buton pe fundal negru -->
    <Button
        android:id="@+id/button_black"
        android:layout_width="200dp"
        android:layout_height="60dp"
        android:background="@drawable/button_black_bg"
        android:text="Buton Negru"
        android:textColor="#FFFFFF"
        android:textSize="18sp"
        android:layout_marginBottom="20dp"/>

    <!-- Buton pe fundal albastru inchis mat -->
    <Button
        android:id="@+id/button_blue"
        android:layout_width="200dp"
        android:layout_height="60dp"
        android:background="@drawable/button_blue_bg"
        android:text="Buton Albastru"
        android:textColor="#FFFFFF"
        android:textSize="18sp"/>

</LinearLayout>
2. Crearea fundalului pentru butoane
Trebuie să creezi două fișiere XML pentru fundalul butoanelor, unul pentru butonul negru și altul pentru butonul albastru închis mat.
Fundal pentru butonul negru (button_black_bg.xml)
Creează acest fișier în res/drawable/:
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:state_pressed="true">
        <shape android:shape="rectangle">
            <solid android:color="#2A2A2A" /> <!-- Culoare la apăsare -->
            <corners android:radius="12dp" />
            <stroke android:width="2dp" android:color="#555555" />
            <padding android:left="10dp" android:right="10dp" />
        </shape>
    </item>
    <item>
        <shape android:shape="rectangle">
            <solid android:color="#000000" /> <!-- Fundal normal -->
            <corners android:radius="12dp" />
            <stroke android:width="2dp" android:color="#555555" /> <!-- Margine subtilă -->
            <padding android:left="10dp" android:right="10dp" />
        </shape>
    </item>
</selector>
Fundal pentru butonul albastru (button_blue_bg.xml)
Creează acest fișier în res/drawable/:
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:state_pressed="true">
        <shape android:shape="rectangle">
            <solid android:color="#1B3B4D" /> <!-- Culoare la apăsare -->
            <corners android:radius="12dp" />
            <stroke android:width="2dp" android:color="#336699" />
            <padding android:left="10dp" android:right="10dp" />
        </shape>
    </item>
    <item>
        <shape android:shape="rectangle">
            <solid android:color="#112233" /> <!-- Fundal normal -->
            <corners android:radius="12dp" />
            <stroke android:width="2dp" android:color="#336699" /> <!-- Margine subtilă -->
            <padding android:left="10dp" android:right="10dp" />
        </shape>
    </item>
</selector>
3. Adăugarea animației pentru apăsarea butonului
Vom crea un fișier de animație care va simula o mică retragere a butonului în suprafață când este apăsat.
Creează un fișier XML numit button_press_anim.xml în res/anim/:
<?xml version="1.0" encoding="utf-8"?>
<set xmlns:android="http://schemas.android.com/apk/res/android"
    android:interpolator="@android:interpolator/accelerate_decelerate">
    
    <scale
        android:duration="100"
        android:fromXScale="1.0"
        android:fromYScale="1.0"
        android:toXScale="0.95"
        android:toYScale="0.95"
        android:pivotX="50%"
        android:pivotY="50%" />

    <scale
        android:duration="100"
        android:startOffset="100"
        android:fromXScale="0.95"
        android:fromYScale="0.95"
        android:toXScale="1.0"
        android:toYScale="1.0"
        android:pivotX="50%"
        android:pivotY="50%" />
</set>
4. Implementarea animației în codul Java
În MainActivity.java, vom adăuga codul care aplică animația de apăsare la butoanele noastre.
package com.example.buttonanimation;

import android.os.Bundle;
import android.view.MotionEvent;
import android.view.animation.Animation;
import android.view.animation.AnimationUtils;
import android.widget.Button;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Butoanele
        Button blackButton = findViewById(R.id.button_black);
        Button blueButton = findViewById(R.id.button_blue);

        // Animație la apăsare
        Animation buttonPressAnim = AnimationUtils.loadAnimation(this, R.anim.button_press_anim);

        // Adaugă animația de retragere la apăsarea butonului negru
        blackButton.setOnTouchListener((v, event) -> {
            if (event.getAction() == MotionEvent.ACTION_DOWN) {
                v.startAnimation(buttonPressAnim);
            }
            return false;
        });

        // Adaugă animația de retragere la apăsarea butonului albastru
        blueButton.setOnTouchListener((v, event) -> {
            if (event.getAction() == MotionEvent.ACTION_DOWN) {
                v.startAnimation(buttonPressAnim);
            }
            return false;
        });
    }
}
5. Structura Proiectului
•	res/layout/activity_main.xml: Layout-ul principal care conține cele două butoane.
•	res/drawable/button_black_bg.xml: Fundalul pentru butonul negru.
•	res/drawable/button_blue_bg.xml: Fundalul pentru butonul albastru.
•	res/anim/button_press_anim.xml: Fișierul de animație pentru efectul de retragere la apăsare.
•	MainActivity.java: Codul Java care leagă layout-ul cu logica animațiilor.
6. Rezultatul Final
•	Butonul Negru: Va avea un fundal negru cu margini subțiri gri, iar când este apăsat, se va micșora ușor pentru a sugera retragerea în suprafață.
•	Butonul Albastru: Va avea un fundal albastru închis mat, cu margini subțiri albastre, și va avea aceeași animație subtilă de retragere.
Acum ai un design robust și profesionist pentru cele două butoane, împreună cu o animație subtilă care îmbunătățește experiența utilizatorului.
”


