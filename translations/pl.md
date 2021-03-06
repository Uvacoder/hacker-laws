# 馃捇馃摉 prawa-hakerskie

Prawa, teorie, zasady i wzorce, kt贸re programi艣ci uznaj膮 za przydatne.

[T艂umaczenia](#translations): [馃嚠馃嚛](./translations/id.md) [馃嚙馃嚪](./translations/pt-BR.md) [馃嚚馃嚦](https://github.com/nusr/hacker-laws-zh) [馃嚛馃嚜](./translations/de.md) [馃嚝馃嚪](./translations/fr.md) [馃嚞馃嚪](./translations/el.md) [馃嚠馃嚬](https://github.com/csparpa/hacker-laws-it) [馃嚤馃嚮](./translations/lv.md) [馃嚢馃嚪](https://github.com/codeanddonuts/hacker-laws-kr) [馃嚨馃嚤](./translations/pl.md) [馃嚪馃嚭](https://github.com/solarrust/hacker-laws) [馃嚜馃嚫](./translations/es-ES.md) [馃嚬馃嚪](https://github.com/umutphp/hacker-laws-tr) [馃嚡馃嚨](./translations/jp.md) [馃嚭馃嚘](./translations/uk.md)

Podoba Ci si臋 ten projekt? Prosz臋 rozwa偶y膰 [sponsorowanie mnie](https://github.com/sponsors/dwmkerr) i [t艂umaczy](#translations) . Sprawd藕 r贸wnie偶 ten podcast na [The Changelog - Laws for Hackers to Live By,](https://changelog.com/podcast/403) aby dowiedzie膰 si臋 wi臋cej o projekcie! Mo偶esz tak偶e [pobra膰 najnowszy e-book w formacie PDF](https://github.com/dwmkerr/hacker-laws/releases/latest/download/hacker-laws.pdf) . Sprawd藕 [Przewodnik](./.github/contributing.md) dla tw贸rc贸w, je艣li chcesz wnie艣膰 sw贸j wk艂ad!

---

<!-- vim-markdown-toc GFM -->

- [Wst臋p](#introduction)
- [Prawa](#laws)
    - [Zasada 90-9-1 (zasada 1%)](#zasada-90-9-1-zasada-1)
    - [Prawo Amdahla](#amdahls-law)
    - [Teoria zepsutych okien](#the-broken-windows-theory)
    - [Prawo Brooksa](#brooks-law)
    - [Twierdzenie CAP (Twierdzenie Brewera)](#cap-theorem-brewers-theorem)
    - [Prawo Conwaya](#conways-law)
    - [Prawo Cunninghama](#cunninghams-law)
    - [Numer Dunbara](#dunbars-number)
    - [Efekt Dunninga-Krugera](#the-dunning-kruger-effect)
    - [Prawo Fittsa](#fitts-law)
    - [Prawo Galla](#galls-law)
    - [Prawo Goodharta](#goodharts-law)
    - [Brzytwa Hanlona](#hanlons-razor)
    - [Prawo Hicka (Prawo Hicka-Hymana)](#hicks-law-hick-hyman-law)
    - [Prawo Hofstadtera](#hofstadters-law)
    - [Prawo Hutbera](#hutbers-law)
    - [Cykl szumu i prawo Amary](#the-hype-cycle--amaras-law)
    - [Prawo Hyruma (prawo niejawnych interfejs贸w)](#hyrums-law-the-law-of-implicit-interfaces)
    - [Prawo Kernighana](#kernighans-law)
    - [Prawo Linusa](#linuss-law)
    - [Prawo Metcalfego](#metcalfes-law)
    - [prawo Moore'a](#moores-law)
    - [Prawo Murphy'ego / Prawo Soda](#murphys-law--sods-law)
    - [Brzytwa Ockhama](#occams-razor)
    - [Prawo Parkinsona](#parkinsons-law)
    - [Przedwczesny efekt optymalizacji](#premature-optimization-effect)
    - [Prawo Putta](#putts-law)
    - [Prawo Reeda](#reeds-law)
    - [Prawo zachowania z艂o偶ono艣ci (prawo Teslera)](#the-law-of-conservation-of-complexity-teslers-law)
    - [Prawo Demeter](#the-law-of-demeter)
    - [Prawo nieszczelnych abstrakcji](#the-law-of-leaky-abstractions)
    - [Prawo trywialno艣ci](#the-law-of-triviality)
    - [Filozofia Uniksa](#the-unix-philosophy)
    - [Zasada Skauta](#the-scout-rule)
    - [Model Spotify](#the-spotify-model)
    - [Zasada dw贸ch pizzy](#the-two-pizza-rule)
    - [Prawo Wadlera](#wadlers-law)
    - [Prawo Wheatona](#wheatons-law)
- [Zasady](#principles)
    - [Wszystkie modele s膮 b艂臋dne (prawo George'a Boxa)](#all-models-are-wrong-george-boxs-law)
    - [P艂ot Chestertona](#chestertons-fence)
    - [Efekt Morza Martwego](#the-dead-sea-effect)
    - [Zasada Dilberta](#the-dilbert-principle)
    - [Zasada Pareto (Zasada 80/20)](#the-pareto-principle-the-8020-rule)
    - [Zasada Shirky](#the-shirky-principle)
    - [Zasada Piotra](#the-peter-principle)
    - [Zasada solidno艣ci (prawo Postela)](#the-robustness-principle-postels-law)
    - [SOLIDNY](#solid)
    - [Zasada pojedynczej odpowiedzialno艣ci](#the-single-responsibility-principle)
    - [Zasada otwarcia/zamkni臋cia](#the-openclosed-principle)
    - [Zasada substytucji Liskov](#the-liskov-substitution-principle)
    - [Zasada segregacji interfejs贸w](#the-interface-segregation-principle)
    - [Zasada odwr贸cenia zale偶no艣ci](#the-dependency-inversion-principle)
    - [Zasada SUSZENIA](#the-dry-principle)
    - [Zasada KISS](#the-kiss-principle)
    - [YAGNI](#yagni)
    - [B艂臋dy przetwarzania rozproszonego](#the-fallacies-of-distributed-computing)
- [Lista rzeczy do przeczytania](#reading-list)
- [Zasoby online](#online-resources)
- [eBook w formacie PDF](#pdf-ebook)
- [Podcast](#podcast)
- [T艂umaczenia](#translations)
- [Powi膮zane projekty](#related-projects)
- [Przyczynianie si臋](#contributing)
- [DO ZROBIENIA](#todo)

<!-- vim-markdown-toc -->

## Wst臋p

Istnieje wiele praw, o kt贸rych ludzie dyskutuj膮, m贸wi膮c o rozwoju. To repozytorium jest odniesieniem i przegl膮dem niekt贸rych z najcz臋stszych. Podziel si臋 i prze艣lij PR!

Odpowied藕: To repozytorium zawiera wyja艣nienie niekt贸rych praw, zasad i wzorc贸w, ale nie *zaleca* 偶adnego z nich. To, czy nale偶y je zastosowa膰, zawsze b臋dzie kwesti膮 dyskusyjn膮 i w du偶ej mierze zale偶y od tego, nad czym pracujesz.

## Prawa

No to zaczynamy!

### Zasada 90-9-1 (zasada 1%)

[Regu艂a 1% na Wikipedii](https://en.wikipedia.org/wiki/1%25_rule_(Internet_culture))

Zasada 90-9-1 sugeruje, 偶e w spo艂eczno艣ci internetowej, takiej jak wiki, 90% uczestnik贸w tylko korzysta z tre艣ci, 9% edytuje lub modyfikuje tre艣膰, a 1% uczestnik贸w dodaje tre艣膰.

Przyk艂ady ze 艣wiata rzeczywistego:

- Badanie z 2014 roku czterech cyfrowych portali spo艂eczno艣ciowych po艣wi臋conych zdrowiu wykaza艂o, 偶e 1% najpopularniejszych tworzy 73% post贸w, kolejne 9% stanowi艂o 艣rednio ~25%, a pozosta艂e 90% stanowi艂o 艣rednio 2% ( [Odniesienie](https://www.jmir.org/2014/2/e33/) )

Zobacz te偶:

- [Zasada Pareto](#the-pareto-principle-the-8020-rule)

### Prawo Amdahla

[Prawo Amdahla na Wikipedii](https://pl.wikipedia.org/wiki/Prawo_Amdahla)

> Prawo Amdahla to wz贸r pokazuj膮cy *potencjalne przyspieszenie* zadania obliczeniowego, kt贸re mo偶na osi膮gn膮膰 zwi臋kszaj膮c zasoby systemu. Zwykle u偶ywany w obliczeniach r贸wnoleg艂ych, mo偶e przewidzie膰 rzeczywiste korzy艣ci ze zwi臋kszenia liczby procesor贸w, co jest ograniczone przez mo偶liwo艣膰 r贸wnoleg艂o艣ci programu.

Najlepiej zilustrowane przyk艂adem. Je艣li program sk艂ada si臋 z dw贸ch cz臋艣ci, cz臋艣ci A, kt贸ra musi by膰 wykonywana przez pojedynczy procesor, i cz臋艣ci B, kt贸ra mo偶e by膰 zr贸wnoleglona, to widzimy, 偶e dodanie wielu procesor贸w do systemu wykonuj膮cego program mo偶e mie膰 tylko ograniczon膮 korzy艣膰 . Potencjalnie mo偶e znacznie poprawi膰 pr臋dko艣膰 cz臋艣ci B - ale pr臋dko艣膰 cz臋艣ci A pozostanie niezmieniona.

Poni偶szy diagram pokazuje kilka przyk艂ad贸w potencjalnej poprawy szybko艣ci:

<img width="480px" alt="Schemat: Prawo Amdahla" src="/images/amdahls_law.png" />

*(Odniesienie do obrazu: Daniels219 z angielskiej Wikipedii, Creative Commons Attribution-Share Alike 3.0 Unported, https://en.wikipedia.org/wiki/File:AmdahlsLaw.svg)*

Jak wida膰, nawet program, kt贸ry mo偶na zr贸wnolegla膰 w 50%, przyniesie niewiele korzy艣ci poza 10 jednostkami przetwarzania, podczas gdy program, kt贸ry mo偶na zr贸wnolelizowa膰 w 95%, nadal mo偶e osi膮gn膮膰 znaczn膮 popraw臋 szybko艣ci przy ponad tysi膮cu jednostek przetwarzania.

Poniewa偶 [prawo Moore'a](#moores-law) zwalnia, a przyspieszenie szybko艣ci poszczeg贸lnych procesor贸w zwalnia, r贸wnoleg艂o艣膰 jest kluczem do poprawy wydajno艣ci. Programowanie graficzne jest doskona艂ym przyk艂adem - przy nowoczesnych obliczeniach opartych na Shader, pojedyncze piksele lub fragmenty mog膮 by膰 renderowane r贸wnolegle - dlatego wsp贸艂czesne karty graficzne cz臋sto maj膮 wiele tysi臋cy rdzeni przetwarzaj膮cych (GPU lub Shader Units).

Zobacz te偶:

- [Prawo Brooksa](#brooks-law)
- [prawo Moore'a](#moores-law)

### Teoria zepsutych okien

[Teoria rozbitycg okien na Wikipedii](https://pl.wikipedia.org/wiki/Teoria_rozbitych_okien)

Teoria rozbitych okien sugeruje, 偶e widoczne oznaki przest臋pczo艣ci (lub braku dba艂o艣ci o 艣rodowisko) prowadz膮 do kolejnych i powa偶niejszych przest臋pstw (lub dalszego pogorszenia stanu 艣rodowiska).

Teoria ta zosta艂a zastosowana do rozwoju oprogramowania, co sugeruje, 偶e kod niskiej jako艣ci (lub [d艂ug techniczny](#TODO) ) mo偶e prowadzi膰 do przekonania, 偶e wysi艂ki na rzecz poprawy jako艣ci mog膮 by膰 ignorowane lub niedoceniane, co prowadzi do dalszej z艂ej jako艣ci kodu. Ten efekt kaskadowo prowadzi do znacznego spadku jako艣ci z biegiem czasu.

Zobacz te偶:

- [D艂ug techniczny](#TODO)

Przyk艂ady:

- [Programowanie pragmatyczne: entropia oprogramowania](https://flylib.com/books/en/1.315.1.15/1/)
- [Horror kodowania: teoria rozbitego okna](https://blog.codinghorror.com/the-broken-window-theory/)
- [OpenSource: Rado艣膰 z programowania 鈥? teoria rozbitego okna](https://opensourceforu.com/2011/05/joy-of-programming-broken-window-theory/)

### Prawo Brooksa

[Prawo Brooksa na Wikipedii](https://pl.wikipedia.org/wiki/Prawo_Brooksa)

> Dodanie zasob贸w ludzkich do sp贸藕nionego projektu rozwoju oprogramowania sprawia, 偶e jest to p贸藕niej.

Prawo to sugeruje, 偶e w wielu przypadkach pr贸ba przyspieszenia realizacji projektu, kt贸ry jest ju偶 sp贸藕niony, poprzez dodanie wi臋kszej liczby os贸b, spowoduje, 偶e realizacja b臋dzie jeszcze p贸藕niejsza. Brooks nie ma w膮tpliwo艣ci, 偶e jest to nadmierne uproszczenie, jednak og贸lne rozumowanie jest takie, 偶e bior膮c pod uwag臋 czas narastania nowych zasob贸w i og贸lne koszty komunikacji, w kr贸tkim czasie pr臋dko艣膰 spada. Ponadto wiele zada艅 mo偶e nie by膰 podzielnych, tj. 艂atwo rozdzielonych mi臋dzy wi臋cej zasob贸w, co oznacza, 偶e potencjalny wzrost pr臋dko艣ci jest r贸wnie偶 mniejszy.

Powszechne zdanie przy porodzie 鈥濪ziewi臋膰 kobiet nie mo偶e sp艂odzi膰 dziecka w ci膮gu jednego miesi膮ca鈥? odnosi si臋 do prawa Brooksa, w szczeg贸lno艣ci do faktu, 偶e niekt贸re rodzaje pracy nie s膮 podzielne ani r贸wnoleg艂e.

Jest to tematem przewodnim ksi膮偶ki 鈥? [Miesi膮c mitycznego cz艂owieka](#reading-list) 鈥?.

Zobacz te偶:

- [Marsz 艣mierci](#todo)
- [Lista lektur: Miesi膮c Mitycznego Cz艂owieka](#reading-list)

### Twierdzenie CAP (Twierdzenie Brewera)

Twierdzenie CAP (zdefiniowane przez Erica Brewera) stwierdza, 偶e w przypadku rozproszonego magazynu danych mo偶na uzyska膰 tylko dwie z trzech nast臋puj膮cych gwarancji (co najwy偶ej):

- Sp贸jno艣膰: podczas odczytu danych ka偶de 偶膮danie otrzymuje *najnowsze* dane lub zwracany jest b艂膮d
- Dost臋pno艣膰: podczas odczytu danych ka偶de 偶膮danie otrzymuje *odpowied藕* bez b艂臋du, bez gwarancji, 偶e s膮 to *najnowsze* dane
- Tolerancja partycji: gdy dowolna liczba 偶膮da艅 sieciowych mi臋dzy w臋z艂ami nie powiedzie si臋, system nadal dzia艂a zgodnie z oczekiwaniami

Sedno rozumowania jest nast臋puj膮ce. Nie mo偶na zagwarantowa膰, 偶e partycja sieciowa nie wyst膮pi (zobacz [The Fallacies of Distributed Computing](#the-fallacies-of-distributed-computing) ). Dlatego w przypadku partycji mo偶emy albo anulowa膰 operacj臋 (zwi臋kszaj膮c sp贸jno艣膰 i zmniejszaj膮c dost臋pno艣膰) albo kontynuowa膰 (zwi臋kszaj膮c dost臋pno艣膰, ale zmniejszaj膮c sp贸jno艣膰).

Nazwa pochodzi od pierwszych liter gwarancji (sp贸jno艣膰, dost臋pno艣膰, tolerancja partycji). Nale偶y pami臋ta膰, 偶e bardzo wa偶ne jest, aby mie膰 艣wiadomo艣膰, 偶e *nie* dotyczy to [*ACID*](#TODO) , kt贸ry ma inn膮 definicj臋 sp贸jno艣ci. Niedawno [opracowano](#TODO) twierdzenie PACELC, kt贸re dodaje ograniczenia dotycz膮ce op贸藕nie艅 i sp贸jno艣ci, gdy sie膰 *nie* jest podzielona na partycje (tj. gdy system dzia艂a zgodnie z oczekiwaniami).

Wi臋kszo艣膰 nowoczesnych platform bazodanowych potwierdza to twierdzenie po艣rednio, oferuj膮c u偶ytkownikowi bazy danych opcj臋 wyboru mi臋dzy operacj膮 o wysokiej dost臋pno艣ci (kt贸ra mo偶e obejmowa膰 鈥瀊rudny odczyt鈥?) a operacj膮 wysoce sp贸jn膮 (na przyk艂ad 鈥瀦apis z potwierdzeniem kworum ').

Przyk艂ady ze 艣wiata rzeczywistego:

- [Wewn膮trz Google Cloud Spanner i twierdzenia CAP](https://cloud.google.com/blog/products/gcp/inside-cloud-spanner-and-the-cap-theorem) 鈥? omawia szczeg贸艂y dzia艂ania Cloud Spanner, kt贸re na pierwszy rzut oka wydaje si臋 platform膮, kt贸ra ma *wszystkie* gwarancje CAP, ale pod mask膮 jest zasadniczo system CP.

Zobacz te偶:

- [KWAS](#TODO)
- [B艂臋dy przetwarzania rozproszonego](#the-fallacies-of-distributed-computing)
- [PACELC](#TODO)

### Prawo Conwaya

[Prawo Conwaya na Wikipedii](https://en.wikipedia.org/wiki/Conway%27s_law)

Prawo to sugeruje, 偶e granice techniczne systemu b臋d膮 odzwierciedla膰 struktur臋 organizacji. Cz臋sto m贸wi si臋 o tym, gdy patrzymy na ulepszenia organizacji. Prawo Conwaya sugeruje, 偶e je艣li organizacja jest podzielona na wiele ma艂ych, niepowi膮zanych ze sob膮 jednostek, tak b臋dzie tworzone oprogramowanie. Je艣li organizacja jest zbudowana bardziej wok贸艂 鈥瀊ran偶鈥?, kt贸re s膮 zorientowane na funkcje lub us艂ugi, systemy oprogramowania r贸wnie偶 to odzwierciedl膮.

Zobacz te偶:

- [Model Spotify](#the-spotify-model)

### Prawo Cunninghama

[Prawo Cunninghama na Wikipedii](https://en.wikipedia.org/wiki/Ward_Cunningham#Cunningham's_Law)

> Najlepszym sposobem na uzyskanie prawid艂owej odpowiedzi w Internecie nie jest zadawanie pyta艅, ale zamieszczenie b艂臋dnej odpowiedzi.

Wed艂ug Stevena McGeady'ego Ward Cunningham poradzi艂 mu na pocz膮tku lat 80.: 鈥濶ajlepszym sposobem na uzyskanie prawid艂owej odpowiedzi w Internecie jest nie zadawanie pyta艅, ale zamieszczenie z艂ej odpowiedzi鈥?. McGeady nazwa艂 to prawo Cunninghama, chocia偶 Cunningham zaprzecza w艂asno艣ci, nazywaj膮c to 鈥瀊艂臋dem鈥?. Chocia偶 pierwotnie odnosi艂o si臋 do interakcji w Usenecie, prawo zosta艂o u偶yte do opisania dzia艂ania innych spo艂eczno艣ci internetowych (np. Wikipedia, Reddit, Twitter, Facebook).

Zobacz te偶:

- [XKCD 386: 鈥濿ezwania do s艂u偶by鈥漖(https://xkcd.com/386/)

### Numer Dunbara

[Numer Dunbara na Wikipedii](https://en.wikipedia.org/wiki/Dunbar%27s_number)

鈥濴iczba Dunbara jest sugerowanym limitem poznawczym liczby os贸b, z kt贸rymi mo偶na utrzymywa膰 stabilne relacje spo艂eczne 鈥? relacje, w kt贸rych jednostka wie, kim jest ka偶da osoba i jak ka偶da osoba odnosi si臋 do ka偶dej innej osoby鈥?. Istnieje pewna niezgodno艣膰 co do dok艂adnej liczby. 鈥?... [Dunbar] zaproponowa艂, 偶e ludzie mog膮 wygodnie utrzymywa膰 tylko 150 stabilnych zwi膮zk贸w鈥?. Umie艣ci艂 t臋 liczb臋 w bardziej spo艂ecznym kontek艣cie, 鈥瀕iczb臋 os贸b, kt贸rych nie czuliby艣cie si臋 zawstydzeni do艂膮czeniem do nieproszonych drink贸w, gdyby艣cie wpadli na nich w barze鈥?. Szacunki dotycz膮ce liczby wahaj膮 si臋 od 100 do 250.

Podobnie jak w przypadku stabilnych relacji mi臋dzy jednostkami, utrzymanie relacji programisty z baz膮 kodu wymaga wysi艂ku. W obliczu du偶ych, skomplikowanych projekt贸w lub posiadania wielu projekt贸w opieramy si臋 na konwencji, zasadach i modelowanych procedurach w celu skalowania. Liczba Dunbar jest wa偶na nie tylko w miar臋 rozwoju biura, ale tak偶e przy ustalaniu zakresu dzia艂a艅 zespo艂u lub decydowaniu, kiedy system powinien zainwestowa膰 w narz臋dzia, kt贸re pomog膮 w modelowaniu i automatyzacji og贸lnych koszt贸w logistycznych. Umieszczaj膮c liczb臋 w kontek艣cie in偶ynierskim, jest to liczba projekt贸w (lub znormalizowana z艂o偶ono艣膰 pojedynczego projektu), w przypadku kt贸rych mo偶esz czu膰 si臋 pewnie, do艂膮czaj膮c do rotacji na wezwanie, aby wesprze膰.

Zobacz te偶:

- [Prawo Conwaya](#conways-law)

### Efekt Dunninga-Krugera

[Efekt Dunninga-Krugera na Wikipedii](https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect)

> Je艣li jeste艣 niekompetentny, nie mo偶esz wiedzie膰, 偶e jeste艣 niekompetentny... Umiej臋tno艣ci potrzebne do uzyskania prawid艂owej odpowiedzi to dok艂adnie te umiej臋tno艣ci, kt贸rych potrzebujesz, aby rozpozna膰, jaka jest w艂a艣ciwa odpowied藕.
>
> ( [Dawid Dunning](https://en.wikipedia.org/wiki/David_Dunning) )

Efekt Dunninga-Krugera to teoretyczne zniekszta艂cenie poznawcze, kt贸re zosta艂o opisane przez Davida Dunninga i Justina Krugera w badaniu psychologicznym i artykule z 1999 roku. Badanie sugeruje, 偶e osoby o niskim poziomie umiej臋tno艣ci w zadaniu prawdopodobnie przeceniaj膮 swoj膮 zdolno艣膰 do zadania. Proponowan膮 przyczyn膮 tego nastawienia jest to, 偶e *wymagana jest wystarczaj膮ca 艣wiadomo艣膰* z艂o偶ono艣ci problemu lub dziedziny, aby osoba by艂a w stanie wyrobi膰 sobie 艣wiadom膮 opini臋 na temat swojej zdolno艣ci do pracy w tej dziedzinie.

Efekt Dunninga-Krugera by艂 czasami u偶ywany do opisania powi膮zanego, ale niekoniecznie dorozumianego efektu, kt贸ry mo偶na opisa膰 jako 鈥濱m mniej dana osoba rozumie dan膮 dziedzin臋, tym bardziej prawdopodobne jest, 偶e uwierzy, 偶e mo偶e 艂atwo rozwi膮za膰 problemy w tej dziedzinie, poniewa偶 s膮 bardziej sk艂onni do postrzegania domeny jako *prostej* 鈥?. Ten bardziej og贸lny efekt jest bardzo istotny w technologii. Sugerowa艂oby to, 偶e ludzie mniej zaznajomieni z dan膮 domen膮, na przyk艂ad nietechniczni cz艂onkowie zespo艂u lub mniej do艣wiadczeni cz艂onkowie zespo艂u, cz臋艣ciej *nie doceniaj膮* wysi艂ku wymaganego do rozwi膮zania problemu w tej przestrzeni.

Wraz ze wzrostem zrozumienia i do艣wiadczenia danej osoby w danej domenie, mo偶e ona napotka膰 inny efekt, kt贸ry polega na tym, 偶e maj膮 tendencj臋 do *przeceniania* zdolno艣ci *innych* lub *niedoceniania* w艂asnych zdolno艣ci, poniewa偶 s膮 tak do艣wiadczeni w tej domenie. We wszystkich przypadkach skutki te s膮 *zniekszta艂ceniami poznawczymi* . Podobnie jak w przypadku ka偶dego uprzedzenia, zrozumienie, 偶e mo偶e ono by膰 obecne, cz臋sto wystarczy, aby unikn膮膰 wyzwa艅 鈥? poniewa偶 gdy istnieje 艣wiadomo艣膰 uprzedzenia, mo偶na uwzgl臋dni膰 wi臋cej danych wej艣ciowych i opinii, aby spr贸bowa膰 wyeliminowa膰 te uprzedzenia. 艢ci艣le pokrewnym jest nastawienie [iluzorycznej wy偶szo艣ci](https://pl.wikipedia.org/wiki/Z%C5%82udzenie_ponadprzeci%C4%99tno%C5%9Bci) .

Przyk艂ady ze 艣wiata rzeczywistego:

- [Apple kontra FBI: Dlaczego ten Anti-Terror Hawk zmieni艂 strony](https://fortune.com/2016/03/10/apple-fbi-lindsay-graham/) 鈥? w 2016 roku senator Lindsey Graham zmieni艂 swoje stanowisko wobec Apple, tworz膮c 鈥瀟ylne drzwi鈥? w szyfrowaniu urz膮dze艅. Pocz膮tkowo Graham by艂 krytyczny wobec Apple kwestionuj膮cego pro艣b臋 o stworzenie 鈥瀟ylnych drzwi鈥?, kt贸re uwa偶a艂 za konieczne do zbadania potencjalnych spisk贸w terrorystycznych. Jednak, jak sam przyzna艂 Graham, gdy dowiedzia艂 si臋 wi臋cej o technicznej z艂o偶ono艣ci tej domeny, zda艂 sobie spraw臋, 偶e za艂o偶y艂, i偶 jest ona o wiele prostsza, ni偶 s膮dzi艂, i 偶e takie tylne drzwi mog膮 mie膰 powa偶ne negatywne konsekwencje. Potencjalnie mo偶na to uzna膰 za przyk艂ad efektu Dunninga-Krugera 鈥? ekspert ds. cyberbezpiecze艅stwa prawdopodobnie natychmiast zrozumie, w jaki spos贸b mo偶na wykorzysta膰 takie tylne drzwi, poniewa偶 maj膮 dog艂臋bne zrozumienie domeny, laik mo偶e za艂o偶y膰, 偶e zabezpieczenia telefonu s膮 bardziej podobne do *bezpiecze艅stwa fizycznego,* gdzie praktyka posiadania 鈥瀔lucza g艂贸wnego鈥? dla organ贸w 艣cigania jest mo偶liwa, ale ta analogia nie ma wystarczaj膮cego zastosowania do opisania wsp贸艂czesnego szyfrowania w cyberbezpiecze艅stwie.

### Prawo Fittsa

[Prawo Fittsa na Wikipedii](https://pl.wikipedia.org/wiki/Prawo_Fittsa)

Prawo Fittsa przewiduje, 偶e czas potrzebny do przemieszczenia si臋 do obszaru docelowego jest funkcj膮 odleg艂o艣ci do celu podzielonej przez szeroko艣膰 celu.

<img width="300px" alt="Schemat: Prawo dopasowania" src="/images/Fitts_Law.svg">

*(Odniesienie do obrazu: Foobar628 z angielskiej Wikipedii, Creative Commons Attribution-Share Alike 3.0 Unported, https://en.wikipedia.org/wiki/Fitts%27s_law#/media/File:Fitts_Law.svg)*

Konsekwencje tego prawa nakazuj膮, aby przy projektowaniu UX czy UI elementy interaktywne by艂y jak najwi臋ksze, a odleg艂o艣膰 mi臋dzy obszarem uwagi u偶ytkownika a elementem interaktywnym by艂a jak najmniejsza. Ma to konsekwencje dla projektu, takie jak grupowanie zada艅, kt贸re s膮 cz臋sto u偶ywane blisko siebie.

Formalizuje r贸wnie偶 koncepcj臋 鈥瀖agicznych rog贸w鈥?, rog贸w ekranu, do kt贸rych u偶ytkownik mo偶e 鈥瀙rzesuwa膰鈥? mysz膮, aby 艂atwo trafi膰 鈥? czyli tam, gdzie mo偶na umie艣ci膰 kluczowe elementy interfejsu u偶ytkownika. Przycisk Start systemu Windows znajduje si臋 w magicznym rogu, co u艂atwia wyb贸r, a jako interesuj膮cy kontrast, przycisk 鈥瀦amknij okno鈥? systemu MacOS *nie* znajduje si臋 w magicznym rogu, co utrudnia przypadkowe trafienie.

Zobacz te偶:

- [Zdolno艣膰 informacyjna uk艂adu ruchu cz艂owieka w sterowaniu amplitud膮 ruchu.](https://www.semanticscholar.org/paper/The-information-capacity-of-the-human-motor-system-Fitts/634c9fde5f1c411e4487658ac738dcf18d98ea8d)

### Prawo Galla

[Prawo Galla na Wikipedii](https://en.wikipedia.org/wiki/John_Gall_(author)#Gall's_law)

> Niezmiennie okazuje si臋, 偶e z艂o偶ony system, kt贸ry dzia艂a, wyewoluowa艂 z prostego systemu, kt贸ry dzia艂a艂. Z艂o偶ony system zaprojektowany od podstaw nigdy nie dzia艂a i nie mo偶na go za艂ata膰, aby dzia艂a艂. Musisz zacz膮膰 od nowa z dzia艂aj膮cym prostym systemem.
>
> ( [John Gall](https://en.wikipedia.org/wiki/John_Gall_(author)) )

Prawo Galla sugeruje, 偶e pr贸by *zaprojektowania* bardzo z艂o偶onych system贸w mog膮 si臋 nie powie艣膰. Bardzo z艂o偶one systemy rzadko s膮 budowane za jednym razem, ale zamiast tego ewoluuj膮 z prostszych system贸w.

Klasycznym przyk艂adem jest sie膰 og贸lno艣wiatowa. W obecnym stanie jest to bardzo z艂o偶ony system. Jednak pocz膮tkowo zosta艂 zdefiniowany jako prosty spos贸b udost臋pniania tre艣ci mi臋dzy instytucjami akademickimi. Odni贸s艂 du偶y sukces w realizacji tych cel贸w i z czasem ewoluowa艂, by sta膰 si臋 bardziej z艂o偶ony.

Zobacz te偶:

- [KISS (Keep It Simple, Stupid)](#the-kiss-principle)

### Prawo Goodharta

[Prawo Goodharta na Wikipedii](https://en.wikipedia.org/wiki/Goodhart's_law)

> Jakakolwiek zaobserwowana prawid艂owo艣膰 statystyczna b臋dzie mia艂a tendencj臋 do za艂amania si臋, gdy zostanie na ni膮 na艂o偶ona presja w celach kontrolnych.
>
> *Karola Goodharta*

R贸wnie偶 powszechnie okre艣lany jako:

> Kiedy miara staje si臋 celem, przestaje by膰 dobr膮 miar膮.
>
> *Marilyn Strathern*

Prawo stanowi, 偶e optymalizacje oparte na pomiarach mog膮 prowadzi膰 do dewaluacji samego wyniku pomiaru. Nadmiernie selektywny zestaw miar ( [KPI](https://en.wikipedia.org/wiki/Performance_indicator) ) zastosowany na 艣lepo do procesu powoduje zniekszta艂cony efekt. Ludzie maj膮 tendencj臋 do optymalizacji lokalnie, 鈥瀘grywaj膮c鈥? system w celu spe艂nienia okre艣lonych wska藕nik贸w, zamiast zwraca膰 uwag臋 na ca艂o艣ciowy wynik swoich dzia艂a艅.

Przyk艂ady ze 艣wiata rzeczywistego:

- Testy bez asertywno艣ci spe艂niaj膮 oczekiwania dotycz膮ce pokrycia kodu, mimo 偶e intencj膮 metryki by艂o stworzenie dobrze przetestowanego oprogramowania.
- Wynik wydajno艣ci programisty wskazywany przez liczb臋 zatwierdzonych wierszy prowadzi do nieuzasadnionego rozd臋cia bazy kodu.

Zobacz te偶:

- [Prawo Goodharta: jak mierzenie niew艂a艣ciwych rzeczy prowadzi do niemoralnych zachowa艅](https://coffeeandjunk.com/goodharts-campbells-law/)
- [Dilbert o oprogramowaniu wolnym od b艂臋d贸w](https://dilbert.com/strip/1995-11-13)

### Brzytwa Hanlona

[Brzytwa Hanlona na Wikipedii](https://en.wikipedia.org/wiki/Hanlon%27s_razor)

> Nigdy nie przypisuj z艂o艣liwo艣ci tego, co adekwatnie t艂umaczy si臋 g艂upot膮.
>
> Robert J. Hanlon

Zasada ta sugeruje, 偶e dzia艂ania prowadz膮ce do negatywnych skutk贸w nie by艂y wynikiem z艂ej woli. Zamiast tego negatywny wynik jest bardziej prawdopodobnie przypisywany tym dzia艂aniom i/lub wp艂ywowi, kt贸ry nie jest w pe艂ni zrozumia艂y.

### Prawo Hicka (Prawo Hicka-Hymana)

[Prawo Hicka na Wikipedii](https://en.wikipedia.org/wiki/Hick%27s_law)

> Czas podejmowania decyzji ro艣nie logarytmicznie wraz z liczb膮 opcji do wyboru.
>
> William Edmund Hick i Ray Hyman

W poni偶szym r贸wnaniu `T` to czas na podj臋cie decyzji, `n` to liczba opcji, a `b` to sta艂a okre艣lona na podstawie analizy danych.

![Prawo Hicksa](/images/hicks_law.svg)

*(Odniesienie do obrazu: Creative Commons Attribution-Share Alike 3.0 Unported, https://en.wikipedia.org/wiki/Hick%27s_law)*

To prawo ma zastosowanie tylko wtedy, gdy liczba opcji jest *uporz膮dkowana* , na przyk艂ad alfabetycznie. Jest to implikowane w logarytmie o podstawie dwa, co oznacza, 偶e osoba podejmuj膮ca decyzje zasadniczo przeprowadza *wyszukiwanie binarne* . Je艣li opcje nie s膮 dobrze uporz膮dkowane, eksperymenty pokazuj膮, 偶e czas potrzebny jest liniowy.

Ma to znacz膮cy wp艂yw na projektowanie interfejsu u偶ytkownika; zapewnienie, 偶e u偶ytkownicy mog膮 艂atwo przeszukiwa膰 opcje, prowadzi do szybszego podejmowania decyzji.

W prawie Hicka wykazano r贸wnie偶 korelacj臋 mi臋dzy IQ a czasem reakcji, jak pokazano w [Speed of Information Processing: Developmental Change and Links to Intelligence](https://www.sciencedirect.com/science/article/pii/S0022440599000369) .

Zobacz te偶:

- [Prawo Fittsa](#fitts-law)

### Prawo Hofstadtera

[Prawo Hofstadtera na Wikipedii](https://en.wikipedia.org/wiki/Hofstadter%27s_law)

> Zawsze trwa to d艂u偶ej ni偶 si臋 spodziewasz, nawet bior膮c pod uwag臋 prawo Hofstadtera.
>
> (Douglas Hofstadter)

Mo偶esz us艂ysze膰 to prawo, o kt贸rym mowa, patrz膮c na szacunki, jak d艂ugo co艣 potrwa. Wydaje si臋 truizmem w tworzeniu oprogramowania, 偶e nie jeste艣my zbyt dobrzy w dok艂adnym szacowaniu, ile czasu zajmie dostarczenie czego艣.

To jest z ksi膮偶ki ' [G枚del, Escher, Bach: Wieczny z艂oty warkocz](#reading-list) '.

Zobacz te偶:

- [Lista lektur: G枚del, Escher, Bach: wieczny z艂oty warkocz](#reading-list)

### Prawo Hutbera

[Prawo Hutbera na Wikipedii](https://en.wikipedia.org/wiki/Hutber%27s_law)

> Poprawa oznacza pogorszenie.
>
> ( [Patryk Hutber](https://en.wikipedia.org/wiki/Patrick_Hutber) )

To prawo sugeruje, 偶e ulepszenia systemu doprowadz膮 do pogorszenia innych cz臋艣ci lub ukryj膮 inne pogorszenie, prowadz膮c og贸lnie do degradacji obecnego stanu systemu.

Na przyk艂ad, zmniejszenie op贸藕nienia odpowiedzi dla okre艣lonego punktu ko艅cowego mo偶e spowodowa膰 dalsze problemy z przepustowo艣ci膮 i pojemno艣ci膮 w przep艂ywie 偶膮da艅, wp艂ywaj膮c na zupe艂nie inny podsystem.

### Cykl szumu i prawo Amary

[Cykl szumu na Wikipedii](https://en.wikipedia.org/wiki/Hype_cycle)

> Mamy tendencj臋 do przeceniania wp艂ywu technologii na kr贸tk膮 met臋 i niedoceniania jej na d艂u偶sz膮 met臋.
>
> (Roy Amara)

Hype Cycle to wizualna reprezentacja ekscytacji i rozwoju technologii na przestrzeni czasu, pierwotnie wyprodukowana przez firm臋 Gartner. Najlepiej pokaza膰 to za pomoc膮 wizualizacji:

![Cykl szumu](/images/gartner_hype_cycle.png)

*(Odniesienie do obrazu: Jeremykemp z angielskiej Wikipedii, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=10547051)*

Kr贸tko m贸wi膮c, ten cykl sugeruje, 偶e nowa technologia i jej potencjalny wp艂yw zwykle budzi ogromne zainteresowanie. Zespo艂y cz臋sto szybko wskakuj膮 w te technologie i czasami s膮 rozczarowane wynikami. Mo偶e to by膰 spowodowane tym, 偶e technologia nie jest jeszcze wystarczaj膮co dojrza艂a lub aplikacje w 艣wiecie rzeczywistym nie s膮 jeszcze w pe艂ni zrealizowane. Po pewnym czasie zwi臋kszaj膮 si臋 mo偶liwo艣ci technologii i praktyczne mo偶liwo艣ci jej wykorzystania, a zespo艂y mog膮 wreszcie sta膰 si臋 produktywne. Cytat Roya Amary podsumowuje to w najbardziej zwi臋z艂y spos贸b: 鈥濵amy tendencj臋 do przeceniania wp艂ywu technologii na kr贸tk膮 met臋 i niedoceniania na d艂u偶sz膮 met臋".

### Prawo Hyruma (prawo niejawnych interfejs贸w)

[Prawo Hyruma w Internecie](http://www.hyrumslaw.com/)

> Przy wystarczaj膮cej liczbie u偶ytkownik贸w API nie ma znaczenia, co obiecujesz w kontrakcie: wszystkie obserwowalne zachowania Twojego systemu b臋d膮 przez kogo艣 zale偶ne.
>
> (Hyrum Wright)

Prawo Hyrum stanowi, 偶e gdy masz *wystarczaj膮co du偶膮 liczb臋 konsument贸w* API, wszystkie zachowania API (nawet te, kt贸re nie s膮 zdefiniowane jako cz臋艣膰 umowy publicznej) w ko艅cu stan膮 si臋 przez kogo艣 zale偶ne. Trywialnym przyk艂adem mog膮 by膰 elementy niefunkcjonalne, takie jak czas odpowiedzi API. Bardziej subtelnym przyk艂adem mog膮 by膰 konsumenci, kt贸rzy polegaj膮 na zastosowaniu wyra偶enia regularnego do komunikatu o b艂臋dzie w celu okre艣lenia *typu* b艂臋du interfejsu API. Nawet je艣li kontrakt publiczny interfejsu API nie m贸wi nic o zawarto艣ci komunikatu, wskazuj膮c, 偶e u偶ytkownicy powinni u偶y膰 powi膮zanego kodu b艂臋du, *niekt贸rzy* u偶ytkownicy mog膮 korzysta膰 z komunikatu, a zmiana komunikatu zasadniczo przerywa interfejs API dla tych u偶ytkownik贸w.

Zobacz te偶:

- [Prawo nieszczelnych abstrakcji](#the-law-of-leaky-abstractions)
- [XKCD 1172](https://xkcd.com/1172/)

### Prawo Kernighana

> Debugowanie jest dwa razy trudniejsze ni偶 pisanie kodu. Dlatego, je艣li piszesz kod tak sprytnie, jak to tylko mo偶liwe, z definicji nie jeste艣 wystarczaj膮co sprytny, aby go debugowa膰.
>
> (Brian Kernighan)

Prawo Kernighana zosta艂o nazwane na cze艣膰 [Briana Kernighana](https://en.wikipedia.org/wiki/Brian_Kernighan) i pochodzi z cytatu z ksi膮偶ki Kernighana i Plaugera 鈥? [Elementy stylu programowania鈥漖(https://en.wikipedia.org/wiki/The_Elements_of_Programming_Style) :

> Ka偶dy wie, 偶e debugowanie jest dwa razy trudniejsze ni偶 pisanie programu. Wi臋c je艣li jeste艣 tak sprytny, jak potrafisz, kiedy to piszesz, jak mo偶esz to kiedykolwiek debugowa膰?

Cho膰 hiperboliczne, prawo Kernighana przedstawia argument, 偶e prosty kod ma by膰 lepszy od kodu z艂o偶onego, poniewa偶 debugowanie wszelkich problem贸w pojawiaj膮cych si臋 w kodzie z艂o偶onym mo偶e by膰 kosztowne lub nawet niemo偶liwe.

Zobacz te偶:

- [Zasada KISS](#the-kiss-principle)
- [Filozofia Uniksa](#the-unix-philosophy)
- [Brzytwa Ockhama](#occams-razor)

### Prawo Linusa

[Prawo Linusa na Wikipedii](https://en.wikipedia.org/wiki/Linus%27s_law)

> Bior膮c pod uwag臋 wystarczaj膮c膮 liczb臋 ga艂ek ocznych, wszystkie b艂臋dy s膮 p艂ytkie.
>
> *Eric S. Raymond*

To prawo po prostu m贸wi, 偶e im wi臋cej ludzi widzi problem, tym wi臋ksze prawdopodobie艅stwo, 偶e kto艣 ju偶 wcze艣niej widzia艂 i rozwi膮za艂 problem lub co艣 bardzo podobnego.

Chocia偶 pierwotnie by艂 u偶ywany do opisywania warto艣ci modeli open-source dla projekt贸w, mo偶e by膰 zaakceptowany dla ka偶dego rodzaju projektu oprogramowania. Mo偶na go r贸wnie偶 rozszerzy膰 na procesy - wi臋cej przegl膮d贸w kodu, wi臋cej statycznej analizy i wielobran偶owe procesy testowe sprawi膮, 偶e problemy b臋d膮 bardziej widoczne i 艂atwiejsze do zidentyfikowania.

Bardziej formalnym o艣wiadczeniem mo偶e by膰:

> Maj膮c wystarczaj膮co du偶膮 baz臋 beta-tester贸w i programist贸w, prawie ka偶dy problem zostanie szybko scharakteryzowany i mo偶e zosta膰 rozwi膮zany przez kogo艣, kto ju偶 wcze艣niej spotka艂 si臋 z podobnym problemem.

Prawo to zosta艂o nazwane na cze艣膰 [Linusa Torvaldsa](https://en.wikipedia.org/wiki/Linus_Torvalds) w ksi膮偶ce Erica S. Raymonda 鈥? [Katedra i bazar](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar) 鈥?.

### Prawo Metcalfego

[Prawo Metcalfe'a na Wikipedii](https://en.wikipedia.org/wiki/Metcalfe's_law)

> W teorii sieci warto艣膰 systemu ro艣nie w przybli偶eniu do kwadratu liczby u偶ytkownik贸w systemu.

Prawo to opiera si臋 na liczbie mo偶liwych po艂膮cze艅 parami w systemie i jest 艣ci艣le zwi膮zane [z prawem Reeda](#reeds-law) . Odlyzko i inni argumentowali, 偶e zar贸wno prawo Reeda, jak i prawo Metcalfe'a zawy偶aj膮 warto艣膰 systemu, nie uwzgl臋dniaj膮c granic ludzkiego poznania na efektach sieciowych; zobacz [Numer Dunbara](#dunbars-number) .

Zobacz te偶:

- [Prawo Reeda](#reeds-law)
- [Numer Dunbara](#dunbars-number)

### prawo Moore'a

[Prawo Moore'a na Wikipedii](https://en.wikipedia.org/wiki/Moore%27s_law)

> Liczba tranzystor贸w w uk艂adzie scalonym podwaja si臋 mniej wi臋cej co dwa lata.

Prognozy Moore'a, cz臋sto u偶ywane do zilustrowania szybko艣ci, z jak膮 poprawi艂a si臋 technologia p贸艂przewodnik贸w i chip贸w, okaza艂y si臋 bardzo dok艂adne w okresie od lat 70. do p贸藕nych lat 2000. W ostatnich latach trend nieznacznie si臋 zmieni艂, cz臋艣ciowo ze wzgl臋du na [fizyczne ograniczenia dotycz膮ce stopnia miniaturyzacji komponent贸w](https://en.wikipedia.org/wiki/Quantum_tunnelling) . Jednak post臋py w zr贸wnoleglaniu i potencjalnie rewolucyjne zmiany w technologii p贸艂przewodnikowej i obliczeniach kwantowych mog膮 oznacza膰, 偶e prawo Moore'a mo偶e nadal obowi膮zywa膰 przez dziesi臋ciolecia.

### Prawo Murphy'ego / Prawo Soda

[Prawo Murphy'ego na Wikipedii](https://en.wikipedia.org/wiki/Murphy%27s_law)

> Wszystko, co mo偶e p贸j艣膰 nie tak, p贸jdzie nie tak.

Powi膮zane z [Edwardem A. Murphym, Jr](https://en.wikipedia.org/wiki/Edward_A._Murphy_Jr.) *Murphy's Law* stwierdza, 偶e je艣li co艣 mo偶e p贸j艣膰 nie tak, to p贸jdzie nie tak.

To powszechne powiedzenie w艣r贸d programist贸w. Czasami nieoczekiwane dzieje si臋 podczas tworzenia, testowania, a nawet produkcji. Mo偶e to by膰 r贸wnie偶 zwi膮zane z (bardziej powszechnym w brytyjskim angielskim) *Prawie Soda* :

> Je艣li co艣 mo偶e p贸j艣膰 nie tak, to w najgorszym mo偶liwym momencie.

Te 鈥瀙rawa鈥? s膮 na og贸艂 u偶ywane w komicznym sensie. Jednak zjawiska takie jak b艂膮d [*potwierdzenia*](#TODO) i b艂膮d [*selekcji*](#TODO) mog膮 sk艂ania膰 ludzi do nadmiernego podkre艣lania tych praw (w wi臋kszo艣ci przypadk贸w, gdy co艣 dzia艂a, pozostaj膮 niezauwa偶one, jednak niepowodzenia s膮 bardziej zauwa偶alne i wywo艂uj膮 wi臋cej dyskusji).

Zobacz te偶:

- [B艂膮d potwierdzenia](#TODO)
- [Odchylenie selekcji](#TODO)

### Brzytwa Ockhama

[Brzytwa Ockhama na Wikipedii](https://en.wikipedia.org/wiki/Occam's_razor)

> Nie nale偶y mno偶y膰 jednostek bez konieczno艣ci.
>
> Wilhelm z Ockhama

Brzytwa Ockhama m贸wi, 偶e spo艣r贸d kilku mo偶liwych rozwi膮za艅 najbardziej prawdopodobnym rozwi膮zaniem jest to, kt贸re ma najmniejsz膮 liczb臋 koncepcji i za艂o偶e艅. To rozwi膮zanie jest najprostsze i rozwi膮zuje tylko zadany problem, bez wprowadzania przypadkowych z艂o偶ono艣ci i ewentualnych negatywnych konsekwencji.

Zobacz te偶:

- [YAGNI](#yagni)
- [Brak srebrnej kuli: przypadkowa z艂o偶ono艣膰 i zasadnicza z艂o偶ono艣膰](https://en.wikipedia.org/wiki/No_Silver_Bullet)

Przyk艂ad:

- [Rozw贸j oprogramowania szczup艂ego: eliminuj marnotrawstwo](https://en.wikipedia.org/wiki/Lean_software_development#Eliminate_waste)

### Prawo Parkinsona

[Prawo Parkinsona na Wikipedii](https://en.wikipedia.org/wiki/Parkinson%27s_law)

> Praca rozwija si臋 tak, aby wype艂ni膰 czas dost臋pny na jej wykonanie.

W swoim pierwotnym kontek艣cie ustawa ta opiera艂a si臋 na badaniach biurokracji. Mo偶na to pesymistycznie zastosowa膰 do inicjatyw rozwoju oprogramowania, zgodnie z teori膮, 偶e zespo艂y b臋d膮 nieefektywne do czasu, gdy zbli偶aj膮 si臋 terminy, a nast臋pnie spiesz膮 si臋, aby uko艅czy膰 prac臋 w terminie, co sprawia, 偶e rzeczywisty termin jest nieco arbitralny.

Gdyby to prawo zosta艂o po艂膮czone z prawem [Hofstadtera](#hofstadters-law) , osi膮gni臋to jeszcze bardziej pesymistyczny punkt widzenia - praca rozszerzy si臋, aby wype艂ni膰 czas dost臋pny na jej uko艅czenie i *nadal b臋dzie trwa膰 d艂u偶ej ni偶 oczekiwano* .

Zobacz te偶:

- [Prawo Hofstadtera](#hofstadters-law)

### Przedwczesny efekt optymalizacji

[Przedwczesna optymalizacja na WikiWikiWeb](http://wiki.c2.com/?PrematureOptimization)

> Przedwcze艣nie optymalizacja jest 藕r贸d艂em wszelkiego z艂a.
>
> [(Donald Knuth)](https://twitter.com/realdonaldknuth?lang=en)

W artykule Donald Knuth's [Structured Programming with Go To Statements](http://wiki.c2.com/?StructuredProgrammingWithGoToStatements) napisa艂: 鈥濸rogrami艣ci marnuj膮 ogromne ilo艣ci czasu na my艣lenie lub martwienie si臋 o szybko艣膰 niekrytycznych cz臋艣ci swoich program贸w, a te pr贸by wydajno艣ci maj膮 naprawd臋 silny negatywny wp艂yw podczas debugowania i konserwacja s膮 brane pod uwag臋. Powinni艣my zapomnie膰 o ma艂ych wydajno艣ciach, powiedzmy w 97% przypadk贸w: **przedwczesna optymalizacja jest 藕r贸d艂em wszelkiego z艂a** . Jednak nie powinni艣my przepuszcza膰 naszych mo偶liwo艣ci w tych krytycznych 3%.鈥?

Jednak *przedwczesn膮 optymalizacj臋* mo偶na zdefiniowa膰 (w mniej obci膮偶onych terminach) jako optymalizacj臋, zanim zorientujemy si臋, 偶e jest to konieczne.

### Prawo Putta

[Prawo Putta na Wikipedii](https://en.wikipedia.org/wiki/Putt%27s_Law_and_the_Successful_Technocrat)

> Technologia jest zdominowana przez dwa typy ludzi, tych, kt贸rzy rozumiej膮 to, czym nie zarz膮dzaj膮, i tych, kt贸rzy zarz膮dzaj膮 tym, czego nie rozumiej膮.

Po prawie Putta cz臋sto nast臋puje nast臋pstwo Putta:

> Ka偶da hierarchia techniczna z czasem rozwija inwersj臋 kompetencji.

Stwierdzenia te sugeruj膮, 偶e ze wzgl臋du na r贸偶ne kryteria selekcji i trendy w organizacji grup, na szczeblach pracy organizacji technicznych znajdzie si臋 pewna liczba wykwalifikowanych os贸b oraz pewna liczba os贸b na stanowiskach kierowniczych, kt贸re nie s膮 艣wiadome z艂o偶ono艣ci i wyzwa艅 zwi膮zanych z prac臋, kt贸r膮 zarz膮dzaj膮. Mo偶e to by膰 spowodowane zjawiskami takimi jak [Zasada Petera](#the-peter-principle) lub [Zasada Dilberta](#the-dilbert-principle) .

Nale偶y jednak podkre艣li膰, 偶e takie przepisy s膮 szerokimi uog贸lnieniami i mog膮 mie膰 zastosowanie do *niekt贸rych* typ贸w organizacji, a nie do innych.

Zobacz te偶:

- [Zasada Piotra](#the-peter-principle)
- [Zasada Dilberta](#the-dilbert-principle)

### Prawo Reeda

[Prawo Reeda na Wikipedii](https://en.wikipedia.org/wiki/Reed's_law)

> U偶yteczno艣膰 du偶ych sieci, w szczeg贸lno艣ci sieci spo艂eczno艣ciowych, ro艣nie wyk艂adniczo wraz z rozmiarem sieci.

Prawo to opiera si臋 na teorii graf贸w, gdzie u偶yteczno艣膰 skaluje si臋 jako liczba mo偶liwych podgrup, czyli szybciej ni偶 liczba uczestnik贸w lub liczba mo偶liwych po艂膮cze艅 parami. Odlyzko i inni argumentowali, 偶e prawo Reeda zawy偶a u偶yteczno艣膰 systemu, nie uwzgl臋dniaj膮c ogranicze艅 ludzkiego poznania w zakresie efekt贸w sieciowych; zobacz [Numer Dunbara](#dunbars-number) .

Zobacz te偶:

- [Prawo Metcalfego](#metcalfes-law)
- [Numer Dunbara](#dunbars-number)

### Prawo zachowania z艂o偶ono艣ci (prawo Teslera)

[Prawo zachowania z艂o偶ono艣ci na Wikipedii](https://en.wikipedia.org/wiki/Law_of_conservation_of_complexity)

Prawo to m贸wi, 偶e w systemie wyst臋puje pewna z艂o偶ono艣膰, kt贸rej nie mo偶na zredukowa膰.

Pewna z艂o偶ono艣膰 systemu jest 鈥瀗ieumy艣lna鈥?. Jest to konsekwencja z艂ej struktury, b艂臋d贸w lub po prostu z艂ego zamodelowania problemu do rozwi膮zania. Przypadkow膮 z艂o偶ono艣膰 mo偶na zmniejszy膰 (lub wyeliminowa膰). Jednak pewna z艂o偶ono艣膰 jest 鈥瀢ewn臋trzna鈥? jako konsekwencja z艂o偶ono艣ci nieod艂膮cznie zwi膮zanej z rozwi膮zywanym problemem. T臋 z艂o偶ono艣膰 mo偶na przenie艣膰, ale nie mo偶na jej wyeliminowa膰.

Ciekawym elementem tego prawa jest sugestia, 偶e nawet uproszczenie ca艂ego systemu nie zmniejsza wewn臋trznej z艂o偶ono艣ci, lecz *przenosi si臋 na u偶ytkownika* , kt贸ry musi zachowywa膰 si臋 w bardziej z艂o偶ony spos贸b.

### Prawo Demeter

[Prawo Demeter na Wikipedii](https://en.wikipedia.org/wiki/Law_of_Demeter)

> Nie rozmawiaj z nieznajomymi.

Prawo Demeter, znane r贸wnie偶 jako 鈥瀦asada najmniejszej wiedzy鈥?, jest zasad膮 projektowania oprogramowania, szczeg贸lnie istotn膮 w j臋zykach obiektowych.

Stwierdza, 偶e jednostka oprogramowania powinna rozmawia膰 tylko ze swoimi bezpo艣rednimi wsp贸艂pracownikami. Obiekt `A` z odwo艂aniem do obiektu `B` mo偶e wywo艂ywa膰 swoje metody, ale je艣li `B` ma odwo艂anie do obiektu `C` , `A` nie powinien wywo艂ywa膰 `C` s. Tak wi臋c, je艣li `C` ma `doThing()` , `A` nie powinien wywo艂ywa膰 jej bezpo艣rednio; `B.getC().doThis()` .

Przestrzeganie tej zasady ogranicza zakres zmian, czyni膮c je 艂atwiejszymi i bezpieczniejszymi w przysz艂o艣ci.

### Prawo nieszczelnych abstrakcji

[Prawo nieszczelnych abstrakcji dotycz膮cych Joela na oprogramowaniu](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/)

> Wszystkie nietrywialne abstrakcje s膮 do pewnego stopnia nieszczelne.
>
> ( [Joel Spolsky](https://twitter.com/spolsky) )

Prawo to stanowi, 偶e abstrakcje, kt贸re s膮 zwykle u偶ywane w obliczeniach w celu uproszczenia pracy ze skomplikowanymi systemami, w pewnych sytuacjach 鈥瀢yciekaj膮鈥? elementy systemu bazowego, co powoduje, 偶e abstrakcja zachowuje si臋 w nieoczekiwany spos贸b.

Przyk艂adem mo偶e by膰 wczytanie pliku i odczytanie jego zawarto艣ci. Interfejsy API systemu plik贸w s膮 *abstrakcj膮* system贸w j膮dra ni偶szego poziomu, kt贸re same w sobie s膮 abstrakcj膮 fizycznych proces贸w zwi膮zanych ze zmian膮 danych na talerzu magnetycznym (lub pami臋ci flash w przypadku dysku SSD). W wi臋kszo艣ci przypadk贸w zadzia艂a abstrakcja traktowania pliku jako strumienia danych binarnych. Jednak w przypadku dysku magnetycznego sekwencyjny odczyt danych b臋dzie *znacznie* szybszy ni偶 dost臋p losowy (ze wzgl臋du na zwi臋kszony narzut b艂臋d贸w stron), ale w przypadku dysku SSD ten narzut nie b臋dzie obecny. Aby poradzi膰 sobie z tym przypadkiem, nale偶y zrozumie膰 podstawowe szczeg贸艂y (na przyk艂ad pliki indeksu bazy danych s膮 skonstruowane tak, aby zmniejszy膰 obci膮偶enie losowego dost臋pu), szczeg贸艂y implementacji 鈥瀙rzeciek贸w鈥? abstrakcji, o kt贸rych programista mo偶e by膰 艣wiadomy.

Powy偶szy przyk艂ad mo偶e sta膰 si臋 bardziej z艂o偶ony, gdy zostanie wprowadzonych *wi臋cej abstrakcji.* System operacyjny Linux umo偶liwia dost臋p do plik贸w przez sie膰, ale reprezentowane lokalnie jako 鈥瀗ormalne鈥? pliki. Ta abstrakcja 鈥瀙rzecieka鈥? w przypadku awarii sieci. Je艣li programista traktuje te pliki jako 鈥瀗ormalne鈥? pliki, nie bior膮c pod uwag臋 faktu, 偶e mog膮 one podlega膰 op贸藕nieniom i awariom sieci, rozwi膮zania b臋d膮 zawiera艂y b艂臋dy.

Artyku艂 opisuj膮cy prawo sugeruje, 偶e nadmierne poleganie na abstrakcjach w po艂膮czeniu ze s艂abym zrozumieniem proces贸w le偶膮cych u ich podstaw w rzeczywisto艣ci sprawia, 偶e radzenie sobie z danym problemem w niekt贸rych przypadkach *staje si臋 bardziej z艂o偶one.*

Zobacz te偶:

- [Prawo Hyruma](#hyrums-law-the-law-of-implicit-interfaces)

Przyk艂ady ze 艣wiata rzeczywistego:

- [Powolne uruchamianie programu Photoshop](https://forums.adobe.com/thread/376152) 鈥? problem, kt贸ry napotka艂em w przesz艂o艣ci. Photoshop uruchamia艂by si臋 wolno, czasami zajmuj膮c kilka minut. Wydaje si臋, 偶e problem polega艂 na tym, 偶e podczas uruchamiania odczytuje informacje o bie偶膮cej domy艣lnej drukarce. Je艣li jednak ta drukarka jest w rzeczywisto艣ci drukark膮 sieciow膮, mo偶e to zaj膮膰 bardzo du偶o czasu. *Abstrakcja* drukarki sieciowej prezentowanej systemowi podobnie do drukarki lokalnej powodowa艂a problem dla u偶ytkownik贸w w sytuacjach s艂abej 艂膮czno艣ci.

### Prawo trywialno艣ci

[Prawo trywialno艣ci na Wikipedii](https://en.wikipedia.org/wiki/Law_of_triviality)

To prawo sugeruje, 偶e grupy b臋d膮 po艣wi臋ca膰 znacznie wi臋cej czasu i uwagi b艂ahym lub kosmetycznym kwestiom ni偶 powa偶nym i istotnym.

Powszechnie u偶ywanym fikcyjnym przyk艂adem jest komitet zatwierdzaj膮cy plany elektrowni j膮drowej, kt贸ry sp臋dza wi臋kszo艣膰 czasu na omawianiu struktury szopy na rowery, a nie na znacznie wa偶niejszym projekcie samej elektrowni. Wniesienie warto艣ciowego wk艂adu w dyskusje na bardzo du偶e, z艂o偶one tematy mo偶e by膰 trudne bez wysokiego poziomu wiedzy merytorycznej lub przygotowania. Jednak ludzie chc膮 by膰 postrzegani jako wnosz膮cy cenny wk艂ad. St膮d tendencja do skupiania zbyt du偶ej ilo艣ci czasu na drobnych szczeg贸艂ach, kt贸re mo偶na 艂atwo wyt艂umaczy膰, ale niekoniecznie maj膮 one szczeg贸lne znaczenie.

Powy偶szy fikcyjny przyk艂ad doprowadzi艂 do u偶ycia terminu 鈥瀂rzucanie rower贸w鈥? jako wyra偶enia marnowania czasu na b艂ahe szczeg贸艂y. Pokrewnym terminem jest 鈥? [golenie](https://en.wiktionary.org/wiki/yak_shaving) jaka鈥?, kt贸re oznacza pozornie nieistotn膮 czynno艣膰, kt贸ra jest cz臋艣ci膮 d艂ugiego 艂a艅cucha warunk贸w wst臋pnych do g艂贸wnego zadania.

### Filozofia Uniksa

[Filozofia Uniksa na Wikipedii](https://en.wikipedia.org/wiki/Unix_philosophy)

Filozofia Uniksa polega na tym, 偶e komponenty oprogramowania powinny by膰 ma艂e i skoncentrowane na robieniu jednej konkretnej rzeczy dobrze. Mo偶e to u艂atwi膰 budowanie system贸w poprzez komponowanie ma艂ych, prostych, dobrze zdefiniowanych jednostek, zamiast u偶ywania du偶ych, z艂o偶onych, wielozadaniowych program贸w.

Nowoczesne praktyki, takie jak 鈥瀉rchitektura mikrous艂ug鈥?, mo偶na traktowa膰 jako zastosowanie tego prawa, w kt贸rym us艂ugi s膮 ma艂e, skoncentrowane i wykonuj膮 jedn膮 konkretn膮 rzecz, umo偶liwiaj膮c z艂o偶one zachowanie z艂o偶one z prostych element贸w konstrukcyjnych.

### Zasada Skauta

[Regu艂a Skauta na O'Reilly](https://www.oreilly.com/library/view/97-things-every/9780596809515/ch08.html)

> Zawsze zostawiaj kod lepszy, ni偶 go znalaz艂e艣.
>
> (Robert C. Martin (Wujek Bob))

Oparta na 鈥瀂asadze Zwiadowcy鈥?, kt贸ra m贸wi, 偶e 鈥瀦awsze zostawiaj pole kempingowe czystsze, ni偶 go znalaz艂e艣鈥?, zasada zwiadu w programowaniu to po prostu 鈥瀦awsze pozostawiaj kod czystszy, ni偶 go znalaz艂e艣鈥?.

Zosta艂o to wprowadzone w pierwszym rozdziale ksi膮偶ki [Czysty kod](https://www.goodreads.com/book/show/3735293-clean-code) autorstwa Boba Martina. Regu艂a sugeruje, 偶e programi艣ci powinni przeprowadza膰 鈥瀘ptymistyczne refaktoryzacj臋鈥?, co oznacza d膮偶enie do poprawy og贸lnej jako艣ci kodu podczas pracy nad nim. Je艣li zauwa偶ysz b艂膮d, spr贸buj go naprawi膰 lub wyczy艣膰. Jednak przy wprowadzaniu zmian w kodzie, kt贸ry wydaje si臋 niepoprawny, warto pami臋ta膰 [o p艂ocie Chestertona](#chestertons-fence) !

Zobacz te偶:

- [Lista lektur: czysty kod](#reading-list)
- [P艂ot Chestertona](#chestertons-fence)
- [Teoria zepsutych okien](#broken-windows-theory)

https://www.amazon.sg/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882

### Model Spotify

[Model Spotify w Spotify Labs](https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/)

Model Spotify to podej艣cie do struktury zespo艂u i organizacji spopularyzowane przez 鈥濻potify鈥?. W tym modelu zespo艂y s膮 zorganizowane wok贸艂 funkcji, a nie technologii.

Model Spotify popularyzuje r贸wnie偶 koncepcje plemion, gildii, oddzia艂贸w, kt贸re s膮 innymi elementami ich struktury organizacyjnej.

Cz艂onkowie organizacji opisali, 偶e rzeczywiste znaczenie tych grup zmienia si臋, ewoluuje i jest ci膮g艂ym eksperymentem. Fakt, 偶e model jest *procesem w ruchu* , a nie sta艂ym modelem, nadal prowadzi do r贸偶nych interpretacji struktury, kt贸re mog膮 opiera膰 si臋 na prezentacjach wyg艂aszanych przez pracownik贸w na konferencjach. Oznacza to, 偶e 鈥瀖igawki鈥? mog膮 by膰 鈥瀙rzepakowywane鈥? przez osoby trzecie w *sta艂膮 struktur臋* , co powoduje utrat臋 dynamiki modelu.

### Zasada dw贸ch pizzy

> Je艣li nie mo偶esz nakarmi膰 dru偶yny dwiema pizzami, jest za du偶a.
>
> (Jeff Bezos)

Ta zasada sugeruje, 偶e niezale偶nie od wielko艣ci firmy, zespo艂y powinny by膰 na tyle ma艂e, aby mog艂y je nakarmi膰 dwie pizze. Przekonanie to, przypisywane Jeffowi Bezosowi i Amazonowi, sugeruje, 偶e du偶e zespo艂y s膮 z natury nieefektywne. Potwierdza to fakt, 偶e wraz ze wzrostem liczebno艣ci zespo艂u liniowo, powi膮zania mi臋dzy lud藕mi rosn膮 kwadratowo; w ten spos贸b koszt koordynacji i komunikacji r贸wnie偶 ro艣nie kwadratowo. Je艣li ten koszt koordynacji jest zasadniczo kosztowny, nale偶y preferowa膰 mniejsze zespo艂y.

Liczb臋 powi膮za艅 mi臋dzy lud藕mi mo偶na wyrazi膰 jako `n(n-1)/2` gdzie n = liczba os贸b.

<img width="200px" alt="Kompletny wykres; Powi膮zania mi臋dzy lud藕mi" src="/images/complete_graph.png">

### Prawo Wadlera

[Prawo Wadlera na wiki.haskell.org](https://wiki.haskell.org/Wadler's_Law)

> W ka偶dym projekcie j臋zykowym ca艂kowity czas po艣wi臋cony na omawianie funkcji z tej listy jest proporcjonalny do dw贸ch podniesionych do pot臋gi jej pozycji.
>
> 1. Semantyka
> 2. Sk艂adnia
> 3. Sk艂adnia leksykalna
> 4. Sk艂adnia leksykalna komentarzy
>
> (W skr贸cie, na ka偶d膮 godzin臋 sp臋dzon膮 na semantyce, 8 godzin zostanie po艣wi臋conych na sk艂adni臋 komentarzy).

Podobnie jak [Prawo](#the-law-of-triviality) trywialno艣ci, Prawo Wadlera m贸wi, 偶e przy projektowaniu j臋zyka ilo艣膰 czasu po艣wi臋canego na struktury j臋zykowe jest nieproporcjonalnie du偶a w por贸wnaniu z wag膮 tych cech.

Zobacz te偶:

- [Prawo trywialno艣ci](#the-law-of-triviality)

### Prawo Wheatona

[Po艂膮czenie](http://www.wheatonslaw.com/)

[Dzie艅 Oficjalny](https://dontbeadickday.com/)

> Nie b膮d藕 kutasem.
>
> *Wila Wheatona*

Ukute przez Wila Wheatona (Star Trek: The Next Generation, The Big Bang Theory), to proste, zwi臋z艂e i pot臋偶ne prawo ma na celu zwi臋kszenie harmonii i szacunku w profesjonalnej organizacji. Mo偶e by膰 stosowany podczas rozm贸w ze wsp贸艂pracownikami, przeprowadzania przegl膮d贸w kodu, przeciwstawiania si臋 innym punktom widzenia, krytykowania i og贸lnie wi臋kszo艣ci profesjonalnych interakcji mi臋dzy lud藕mi.

## Zasady

Zasady s膮 zazwyczaj bardziej prawdopodobne jako wytyczne dotycz膮ce projektowania.

### Wszystkie modele s膮 z艂e (prawo George'a Boxa)

[Wszystkie modele s膮 z艂e](https://en.wikipedia.org/wiki/All_models_are_wrong)

> Wszystkie modele s膮 b艂臋dne, ale niekt贸re s膮 przydatne.
>
> *George Box*

Zasada ta sugeruje, 偶e wszystkie modele system贸w s膮 wadliwe, ale dop贸ki nie s膮 *zbyt* wadliwe, mog膮 by膰 u偶yteczne. Zasada ta ma swoje korzenie w statystyce, ale odnosi si臋 r贸wnie偶 do modeli naukowych i obliczeniowych.

Podstawowym wymaganiem wi臋kszo艣ci oprogramowania jest modelowanie pewnego rodzaju systemu. Niezale偶nie od tego, czy modelowany system jest sieci膮 komputerow膮, bibliotek膮, wykresem powi膮za艅 spo艂eczno艣ciowych czy jakimkolwiek innym systemem, projektant b臋dzie musia艂 okre艣li膰 odpowiedni poziom szczeg贸艂owo艣ci modelowania. Nadmierna szczeg贸艂owo艣膰 mo偶e prowadzi膰 do zbyt du偶ej z艂o偶ono艣ci, zbyt ma艂a szczeg贸艂owo艣膰 mo偶e uniemo偶liwi膰 funkcjonowanie modelu.

Zobacz te偶:

- [Prawo nieszczelnych abstrakcji](#the-law-of-leaky-abstractions)

### P艂ot Chestertona

[P艂ot Chestertona na Wikipedii](https://en.wikipedia.org/wiki/Wikipedia:Chesterton%27s_fence)

> Nie nale偶y przeprowadza膰 reform, dop贸ki nie zrozumie si臋 uzasadnienia istniej膮cego stanu rzeczy.

Ta zasada jest istotna w in偶ynierii oprogramowania przy usuwaniu d艂ugu technicznego. Ka偶da linia programu zosta艂a z jakiego艣 powodu napisana przez kogo艣. Chesterton's Fence sugeruje, 偶e nale偶y stara膰 si臋 w pe艂ni zrozumie膰 kontekst i znaczenie kodu przed jego zmian膮 lub usuni臋ciem, nawet je艣li na pierwszy rzut oka wydaje si臋 on zbyteczny lub niepoprawny.

Nazwa tej zasady pochodzi od opowiadania [GK Chestertona](https://en.wikipedia.org/wiki/G._K._Chesterton) . M臋偶czyzna natrafia na p艂ot przecinaj膮cy 艣rodek drogi. Skar偶y si臋 burmistrzowi, 偶e to bezu偶yteczne ogrodzenie przeszkadza i prosi o jego usuni臋cie. Burmistrz pyta, dlaczego w og贸le jest tam ogrodzenie. Kiedy m臋偶czyzna m贸wi, 偶e nie wie, burmistrz m贸wi: 鈥濲e艣li nie znasz jego przeznaczenia, na pewno nie pozwol臋 ci go usun膮膰. to."

### Efekt Morza Martwego

[Wp艂yw Morza Martwego na Bruce'a F. Webstera](http://brucefwebster.com/2008/04/11/the-wetware-crisis-the-dead-sea-effect/)

> 鈥?... [Z]i臋tniej utalentowani i skuteczni in偶ynierowie IT najcz臋艣ciej odchodz膮 鈥? by wyparowa膰鈥? [ci, kt贸rzy maj膮 tendencj臋 do pozostawania] w tyle [s膮] 鈥瀙ozosta艂o艣ciami鈥? 鈥? najmniej utalentowanymi i skutecznymi in偶ynierami IT 鈥?.
>
> *Bruce F. Webster*

鈥濫fekt Morza Martwego鈥? sugeruje, 偶e w ka偶dej organizacji umiej臋tno艣ci/talent/skuteczno艣膰 in偶ynier贸w s膮 cz臋sto odwrotnie proporcjonalne do ich czasu w firmie.

Zazwyczaj wysoko wykwalifikowani in偶ynierowie 艂atwo znajduj膮 zatrudnienie gdzie indziej i s膮 to pierwsi. In偶ynierowie, kt贸rzy maj膮 przestarza艂e lub s艂abe umiej臋tno艣ci, zwykle pozostaj膮 w firmie, poniewa偶 znalezienie pracy w innym miejscu jest trudne. Jest to szczeg贸lnie widoczne, je艣li w ci膮gu swojego czasu w firmie uzyskali dodatkowe podwy偶ki p艂ac, poniewa偶 uzyskanie ekwiwalentnego wynagrodzenia w innym miejscu mo偶e by膰 trudne.

### Zasada Dilberta

[Zasada Dilberta na Wikipedii](https://en.wikipedia.org/wiki/Dilbert_principle)

> Firmy maj膮 tendencj臋 do systematycznego awansowania niekompetentnych pracownik贸w do kierownictwa, aby wydosta膰 ich z przep艂ywu pracy.
>
> *Scott Adams*

Koncepcja zarz膮dzania opracowana przez Scotta Adamsa (tw贸rc臋 komiksu Dilberta), Zasada Dilberta jest inspirowana [Zasad膮 Petera](#the-peter-principle) . Zgodnie z Zasad膮 Dilberta pracownicy, kt贸rzy nigdy nie byli kompetentni, s膮 awansowani na stanowiska kierownicze w celu ograniczenia szk贸d, jakie mog膮 wyrz膮dzi膰. Adams po raz pierwszy wyja艣ni艂 t臋 zasad臋 w artykule Wall Street Journal z 1995 r., a nast臋pnie rozwin膮艂 j膮 w swojej ksi膮偶ce biznesowej z 1996 r. [鈥瀂asada Dilberta鈥漖(#reading-list) .

Zobacz te偶:

- [Zasada Piotra](#the-peter-principle)
- [Prawo Putta](#putts-law)

### Zasada Pareto (Zasada 80/20)

[Zasada Pareto na Wikipedii](https://en.wikipedia.org/wiki/Pareto_principle)

> Wi臋kszo艣膰 rzeczy w 偶yciu nie jest roz艂o偶ona r贸wnomiernie.

Zasada Pareto sugeruje, 偶e w niekt贸rych przypadkach wi臋kszo艣膰 wynik贸w pochodzi z mniejszo艣ci danych wej艣ciowych:

- 80% okre艣lonego fragmentu oprogramowania mo偶na napisa膰 w 20% ca艂kowitego przydzielonego czasu (odwrotnie, najtrudniejsze 20% kodu zajmuje 80% czasu)
- 20% wysi艂ku daje 80% rezultatu
- 20% pracy tworzy 80% przychod贸w
- 20% b艂臋d贸w powoduje 80% awarii
- 20% funkcji powoduje 80% u偶ytkowania

W latach czterdziestych ameryka艅sko-rumu艅ski in偶ynier dr Joseph Juran, powszechnie uwa偶any za ojca kontroli jako艣ci, [zacz膮艂 stosowa膰 zasad臋 Pareto do kwestii jako艣ci](https://en.wikipedia.org/wiki/Joseph_M._Juran) .

Ta zasada jest r贸wnie偶 znana jako: Regu艂a 80/20, Prawo Niewielu Witalnych oraz Zasada Rzadko艣ci Czynnik贸w.

Przyk艂ady ze 艣wiata rzeczywistego:

- W 2002 roku Microsoft poinformowa艂, 偶e naprawienie 20% najcz臋艣ciej zg艂aszanych b艂臋d贸w pozwoli wyeliminowa膰 80% powi膮zanych b艂臋d贸w i awarii w Windows i Office ( [Reference](https://www.crn.com/news/security/18821726/microsofts-ceo-80-20-rule-applies-to-bugs-not-just-features.htm) ).

### Zasada Shirky

[Wyja艣nienie zasady Shirky](https://kk.org/thetechnium/the-shirky-prin/)

> Instytucje b臋d膮 stara艂y si臋 zachowa膰 problem, kt贸rego s膮 rozwi膮zaniem.
>
> *Glina Shirky*

Zasada Shirky sugeruje, 偶e z艂o偶one rozwi膮zania 鈥? firma, bran偶a lub technologia 鈥? mog膮 by膰 tak skoncentrowane na problemie, kt贸ry rozwi膮zuj膮, 偶e mog膮 nieumy艣lnie utrwala膰 sam problem. Mo偶e to by膰 celowe (firma d膮偶膮ca do znalezienia nowych niuans贸w problemu, kt贸re uzasadniaj膮 dalsze opracowywanie rozwi膮zania) lub nieumy艣lne (niezdolno艣膰 lub niech臋膰 do zaakceptowania lub zbudowania rozwi膮zania, kt贸re ca艂kowicie rozwi膮偶e problem lub go ominie).

Zwi膮zany z:

- S艂ynny wiersz Uptona Sinclaira: *鈥濼rudno jest sprawi膰, by cz艂owiek co艣 zrozumia艂, kiedy jego pensja zale偶y od tego, czy tego nie rozumie!鈥?*
- *Dylemat innowatora* Claya Christensena

Zobacz te偶:

- [Zasada Pareto](#the-pareto-principle-the-8020-rule)

### Zasada Piotra

[Zasada Piotra na Wikipedii](https://en.wikipedia.org/wiki/Peter_principle)

> Ludzie w hierarchii maj膮 tendencj臋 do wznoszenia si臋 do swojego 鈥瀙oziomu niekompetencji鈥?.
>
> *Laurence J. Peter*

Koncepcja zarz膮dzania opracowana przez Laurence'a J. Petera, Zasada Petera, wskazuje, 偶e ludzie, kt贸rzy s膮 dobrzy w swojej pracy, s膮 awansowani, dop贸ki nie osi膮gn膮 poziomu, na kt贸rym nie odnosz膮 ju偶 sukces贸w (ich 鈥瀙oziom niekompetencji鈥?). W tym momencie, poniewa偶 s膮 bardziej starsi, jest mniej prawdopodobne, 偶e zostan膮 usuni臋ci z organizacji (chyba 偶e osi膮gaj膮 spektakularnie z艂e wyniki) i nadal b臋d膮 pe艂ni膰 rol臋, w kt贸rej maj膮 niewiele wrodzonych umiej臋tno艣ci, poniewa偶 ich oryginalne umiej臋tno艣ci, kt贸re ich uczyni艂y sukces niekoniecznie s膮 umiej臋tno艣ciami wymaganymi w nowej pracy.

Jest to szczeg贸lnie interesuj膮ce dla in偶ynier贸w 鈥? kt贸rzy pocz膮tkowo zaczynaj膮 od g艂臋boko technicznych r贸l, ale cz臋sto maj膮 艣cie偶k臋 kariery, kt贸ra prowadzi do *zarz膮dzania* innymi in偶ynierami 鈥? co wymaga zasadniczo innego zestawu umiej臋tno艣ci.

Zobacz te偶:

- [Zasada Dilberta](#the-dilbert-principle)
- [Prawo Putta](#putts-law)

### Zasada solidno艣ci (prawo Postela)

[Zasada solidno艣ci na Wikipedii](https://en.wikipedia.org/wiki/Robustness_principle)

> B膮d藕 konserwatywny w tym, co robisz, b膮d藕 liberalny w tym, co akceptujesz od innych.

Zasada ta, cz臋sto stosowana w tworzeniu aplikacji serwerowych, m贸wi, 偶e to, co wysy艂asz do innych, powinno by膰 jak najmniejsze i zgodne, ale powiniene艣 d膮偶y膰 do umo偶liwienia niezgodnych danych wej艣ciowych, je艣li mo偶na je przetworzy膰.

Celem tej zasady jest zbudowanie system贸w, kt贸re s膮 solidne, poniewa偶 mog膮 poradzi膰 sobie ze 藕le sformu艂owanymi danymi wej艣ciowymi, je艣li intencje mog膮 by膰 nadal zrozumia艂e. Jednak akceptowanie zniekszta艂conych danych wej艣ciowych mo偶e wi膮za膰 si臋 z potencjalnymi implikacjami bezpiecze艅stwa, szczeg贸lnie je艣li przetwarzanie takich danych wej艣ciowych nie jest dobrze przetestowane. Te implikacje i inne kwestie zosta艂y opisane przez Erica Allmana w [Reconsidered The Robustness Principle Reconsidered](https://queue.acm.org/detail.cfm?id=1999945) .

Dopuszczenie niezgodnych danych wej艣ciowych z czasem mo偶e os艂abi膰 zdolno艣膰 protoko艂贸w do ewolucji, poniewa偶 realizatorzy b臋d膮 w ko艅cu polega膰 na tej liberalno艣ci w budowaniu swoich funkcji.

Zobacz te偶:

- [Prawo Hyruma](#hyrums-law-the-law-of-implicit-interfaces)

### SOLIDNY

To jest akronim, kt贸ry odnosi si臋 do:

- S: [Zasada pojedynczej odpowiedzialno艣ci](#the-single-responsibility-principle)
- O: [Zasada otwarcia/zamkni臋cia](#the-openclosed-principle)
- L: [Zasada substytucji Liskov](#the-liskov-substitution-principle)
- I: [Zasada segregacji interfejs贸w](#the-interface-segregation-principle)
- D: [Zasada odwr贸cenia zale偶no艣ci](#the-dependency-inversion-principle)

S膮 to kluczowe zasady [programowania zorientowanego obiektowo](#todo) . Zasady projektowania, takie jak te, powinny by膰 w stanie pom贸c programistom w tworzeniu system贸w 艂atwiejszych w utrzymaniu.

### Zasada pojedynczej odpowiedzialno艣ci

[Zasada pojedynczej odpowiedzialno艣ci na Wikipedii](https://en.wikipedia.org/wiki/Single_responsibility_principle)

> Ka偶dy modu艂 lub klasa powinna mie膰 tylko jedn膮 odpowiedzialno艣膰.

Pierwsza z zasad 鈥? [SOLID](#solid) 鈥?. Ta zasada sugeruje, 偶e modu艂y lub klasy powinny robi膰 jedn膮 rzecz i tylko jedn膮 rzecz. W bardziej praktycznym uj臋ciu oznacza to, 偶e pojedyncza, niewielka zmiana w funkcji programu powinna wymaga膰 zmiany tylko w jednym komponencie. Na przyk艂ad zmiana sposobu sprawdzania poprawno艣ci has艂a pod k膮tem z艂o偶ono艣ci powinna wymaga膰 zmiany tylko w jednej cz臋艣ci programu.

Teoretycznie powinno to sprawi膰, 偶e kod b臋dzie bardziej niezawodny i 艂atwiejszy do zmiany. Wiedza, 偶e zmieniany komponent ma tylko jedn膮 odpowiedzialno艣膰, oznacza tylko, 偶e *testowanie* tej zmiany powinno by膰 艂atwiejsze. Korzystaj膮c z wcze艣niejszego przyk艂adu, zmiana sk艂adnika z艂o偶ono艣ci has艂a powinna mie膰 wp艂yw tylko na funkcje zwi膮zane ze z艂o偶ono艣ci膮 has艂a. O wiele trudniejsze mo偶e by膰 uzasadnienie wp艂ywu zmiany na element, kt贸ry ma wiele obowi膮zk贸w.

Zobacz te偶:

- [Programowanie obiektowe](#todo)
- [SOLIDNY](#solid)

### Zasada otwarcia/zamkni臋cia

[Zasada otwarcia/zamkni臋cia na Wikipedii](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)

> Encje powinny by膰 otwarte na rozszerzenie i zamkni臋te na modyfikacj臋.

Druga z zasad 鈥? [SOLID](#solid) 鈥?. Zasada ta stwierdza, 偶e encje (kt贸re mog膮 by膰 klasami, modu艂ami, funkcjami itd.) powinny mie膰 mo偶liwo艣膰 *rozszerzenia* ich zachowania, ale ich *istniej膮ce* zachowanie nie powinno by膰 modyfikowane.

Jako hipotetyczny przyk艂ad wyobra藕 sobie modu艂, kt贸ry jest w stanie zamieni膰 dokument Markdown w HTML. Teraz wyobra藕 sobie, 偶e do specyfikacji Markdown dodano now膮 sk艂adni臋, kt贸ra dodaje obs艂ug臋 r贸wna艅 matematycznych. Modu艂 powinien by膰 *otwarty do rozbudowy w* celu wdro偶enia nowej sk艂adni matematycznej. Jednak istniej膮ce implementacje sk艂adni (takie jak akapity, punktory itp.) powinny zosta膰 *zamkni臋te przed modyfikacj膮* . Ju偶 dzia艂aj膮, nie chcemy, 偶eby ludzie je zmieniali.

Ta zasada ma szczeg贸lne znaczenie w przypadku programowania obiektowego, w kt贸rym mo偶emy projektowa膰 obiekty tak, aby mo偶na je by艂o 艂atwo rozszerza膰, ale unikamy projektowania obiekt贸w, kt贸rych istniej膮ce zachowanie mo偶e zosta膰 zmienione w nieoczekiwany spos贸b.

Zobacz te偶:

- [Programowanie obiektowe](#todo)
- [SOLIDNY](#solid)

### Zasada substytucji Liskov

[Zasada substytucji Liskov na Wikipedii](https://en.wikipedia.org/wiki/Liskov_substitution_principle)

> Powinna istnie膰 mo偶liwo艣膰 zamiany typu na podtyp bez naruszania systemu.

Trzecia z zasad 鈥? [SOLID](#solid) 鈥?. Ta zasada m贸wi, 偶e je艣li komponent opiera si臋 na typie, powinien m贸c u偶ywa膰 podtyp贸w tego typu, bez awarii systemu lub konieczno艣ci poznania szczeg贸艂贸w tego podtypu.

Jako przyk艂ad wyobra藕my sobie, 偶e mamy metod臋, kt贸ra odczytuje dokument XML ze struktury reprezentuj膮cej plik. Je艣li metoda u偶ywa typu podstawowego 鈥瀙lik鈥?, to wszystko, co pochodzi od 鈥瀙lik鈥?, powinno by膰 mo偶liwe do u偶ycia w funkcji. Je艣li 鈥瀙lik鈥? obs艂uguje wyszukiwanie wsteczne, a parser XML korzysta z tej funkcji, ale typ pochodny 鈥瀙lik sieciowy鈥? nie powiedzie si臋 podczas pr贸by wyszukiwania wstecznego, w贸wczas 鈥瀙lik sieciowy鈥? narusza t臋 zasad臋.

Zasada ta ma szczeg贸lne znaczenie w przypadku programowania obiektowego, w kt贸rym hierarchie typ贸w musz膮 by膰 starannie modelowane, aby unikn膮膰 dezorientacji u偶ytkownik贸w systemu.

Zobacz te偶:

- [Programowanie obiektowe](#todo)
- [SOLIDNY](#solid)

### Zasada segregacji interfejs贸w

[Zasada segregacji interfejs贸w w Wikipedii](https://en.wikipedia.org/wiki/Interface_segregation_principle)

> 呕aden klient nie powinien by膰 zmuszany do polegania na metodach, kt贸rych nie u偶ywa.

Czwarta z zasad 鈥? [SOLID](#solid) 鈥?. Zasada ta stanowi, 偶e konsumenci komponentu nie powinni zale偶e膰 od funkcji tego komponentu, z kt贸rego faktycznie nie korzysta.

Jako przyk艂ad wyobra藕my sobie, 偶e mamy metod臋, kt贸ra odczytuje dokument XML ze struktury reprezentuj膮cej plik. Musi tylko czyta膰 bajty, przesuwa膰 si臋 do przodu lub do ty艂u w pliku. Je艣li ta metoda wymaga aktualizacji z powodu zmiany niepowi膮zanej cechy struktury pliku (takiej jak aktualizacja modelu uprawnie艅 u偶ywanego do reprezentowania bezpiecze艅stwa plik贸w), zasada zosta艂a uniewa偶niona. By艂oby lepiej, gdyby plik zaimplementowa艂 interfejs 鈥瀙rzeszukiwanego strumienia鈥? i aby czytnik XML go u偶ywa艂.

Zasada ta ma szczeg贸lne znaczenie dla programowania obiektowego, w kt贸rym interfejsy, hierarchie i typy abstrakcyjne s膮 u偶ywane w celu [zminimalizowania sprz臋偶enia](#todo) mi臋dzy r贸偶nymi komponentami. [Wpisywanie kaczki](#todo) to metodologia, kt贸ra wymusza t臋 zasad臋, eliminuj膮c jawne interfejsy.

Zobacz te偶:

- [Programowanie obiektowe](#todo)
- [SOLIDNY](#solid)
- [Pisanie kaczki](#todo)
- [Oddzielenie](#todo)

### Zasada odwr贸cenia zale偶no艣ci

[Zasada odwr贸cenia zale偶no艣ci na Wikipedii](https://en.wikipedia.org/wiki/Dependency_inversion_principle)

> Modu艂y wysokopoziomowe nie powinny by膰 zale偶ne od implementacji niskopoziomowych.

Pi膮ta z zasad 鈥? [SOLID](#solid) 鈥?. Ta zasada stanowi, 偶e komponenty orkiestruj膮ce wy偶szego poziomu nie powinny zna膰 szczeg贸艂贸w ich zale偶no艣ci.

Jako przyk艂ad wyobra藕 sobie, 偶e mamy program, kt贸ry odczytuje metadane ze strony internetowej. Przyj臋liby艣my, 偶e g艂贸wny komponent musia艂by wiedzie膰 o komponencie, aby pobra膰 zawarto艣膰 strony internetowej, a nast臋pnie komponent, kt贸ry mo偶e odczyta膰 metadane. Gdyby艣my wzi臋li pod uwag臋 inwersj臋 zale偶no艣ci, g艂贸wny sk艂adnik zale偶a艂by tylko od abstrakcyjnego komponentu, kt贸ry mo偶e pobiera膰 dane bajtowe, a nast臋pnie od abstrakcyjnego komponentu, kt贸ry by艂by w stanie odczyta膰 metadane ze strumienia bajt贸w. G艂贸wny komponent nie wiedzia艂by o TCP/IP, HTTP, HTML itp.

Ta zasada jest z艂o偶ona, poniewa偶 mo偶e si臋 wydawa膰, 偶e 鈥瀘dwraca鈥? oczekiwane zale偶no艣ci systemu (st膮d nazwa). W praktyce oznacza to r贸wnie偶, 偶e oddzielny sk艂adnik orkiestracji musi zapewnia膰 prawid艂owe implementacje typ贸w abstrakcyjnych (np. w poprzednim przyk艂adzie *co艣* musi nadal zapewnia膰 sk艂adnik czytnika metadanych 鈥? narz臋dzie do pobierania plik贸w HTTP i czytnik metatag贸w HTML). Nast臋pnie dotyka wzorc贸w, takich jak [Inversion of Control](#todo) i [Dependency Injection](#todo) .

Zobacz te偶:

- [Programowanie obiektowe](#todo)
- [SOLIDNY](#solid)
- [Odwr贸cenie sterowania](#todo)
- [Wstrzykiwanie zale偶no艣ci](#todo)

### Zasada SUSZENIA

[Zasada DRY na Wikipedii](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

> Ka偶da wiedza musi mie膰 jedn膮, jednoznaczn膮, autorytatywn膮 reprezentacj臋 w ramach systemu.

DRY to akronim od *Don't Repeat Yourself* . Ta zasada ma na celu pom贸c programistom w zmniejszeniu powtarzalno艣ci kodu i utrzymaniu informacji w jednym miejscu i zosta艂a przytoczona w 1999 roku przez Andrew Hunta i Dave'a Thomasa w ksi膮偶ce [The Pragmatic Developer](https://en.wikipedia.org/wiki/The_Pragmatic_Programmer)

> Przeciwie艅stwem DRY by艂oby *WET* (Write Everything Twice lub We Enjoy Typing).

W praktyce, je艣li masz t臋 sam膮 informacj臋 w dw贸ch (lub wi臋cej) r贸偶nych miejscach, mo偶esz u偶y膰 DRY, aby po艂膮czy膰 je w jedn膮 i ponownie wykorzysta膰 w dowolnym miejscu.

Zobacz te偶:

- [Pragmatyczny programista](https://en.wikipedia.org/wiki/The_Pragmatic_Programmer)

### Zasada KISS

[KISS na Wikipedii](https://en.wikipedia.org/wiki/KISS_principle)

> Niech to b臋dzie mo偶liwie proste

Zasada KISS stwierdza, 偶e wi臋kszo艣膰 system贸w dzia艂a najlepiej, je艣li s膮 proste, a nie skomplikowane; dlatego prostota powinna by膰 kluczowym celem w projektowaniu i nale偶y unika膰 niepotrzebnej z艂o偶ono艣ci. Pochodz膮ce z US Navy w 1960 r. wyra偶enie kojarzone jest z in偶ynierem lotniczym Kelly Johnson.

Zasad臋 t臋 najlepiej ilustruje historia Johnsona przekazuj膮cego zespo艂owi konstruktor贸w gar艣膰 narz臋dzi, z wyzwaniem, 偶e projektowany przez nich samolot odrzutowy musi by膰 naprawiany przez przeci臋tnego mechanika w terenie w warunkach bojowych za pomoc膮 tylko tych narz臋dzi. St膮d 鈥瀏艂upia鈥? odnosi si臋 do zwi膮zku mi臋dzy sposobem, w jaki rzeczy si臋 psuj膮, a wyrafinowaniem dost臋pnych narz臋dzi do ich naprawy, a nie mo偶liwo艣ciami samych in偶ynier贸w.

Zobacz te偶:

- [Prawo Galla](#galls-law)

### YAGNI

[YAGNI na Wikipedii](https://en.wikipedia.org/wiki/You_ain%27t_gonna_need_it)

Jest skr贸tem dla ***Y** Ou **A** in't **G** onna **N** Id **i** t.*

> Zawsze wdra偶aj rzeczy, kiedy naprawd臋 ich potrzebujesz, nigdy tylko wtedy, gdy tylko przewidujesz, 偶e ich potrzebujesz.
>
> ( [Ron Jeffries](https://twitter.com/RonJeffries) ) (wsp贸艂za艂o偶yciel XP i autor ksi膮偶ki 鈥瀂ainstalowane programowanie ekstremalne鈥?)

Ta *zasada Extreme Programming* (XP) sugeruje, 偶e programi艣ci powinni wdra偶a膰 tylko te funkcje, kt贸re s膮 potrzebne do natychmiastowych wymaga艅 i unika膰 pr贸b przewidywania przysz艂o艣ci poprzez implementacj臋 funkcji, kt贸re mog膮 by膰 potrzebne p贸藕niej.

Przestrzeganie tej zasady powinno zmniejszy膰 ilo艣膰 niewykorzystanego kodu w kodzie i unikn膮膰 marnowania czasu i wysi艂ku na funkcjonalno艣膰, kt贸ra nie przynosi 偶adnej warto艣ci.

Zobacz te偶:

- [Lista lektur: Zainstalowano ekstremalne programowanie](#reading-list)

### B艂臋dy przetwarzania rozproszonego

[B艂臋dy przetwarzania rozproszonego na Wikipedii](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)

Znane r贸wnie偶 jako *B艂臋dy Przetwarzania w Sieci* , B艂臋dy to lista przypuszcze艅 (lub przekona艅) na temat przetwarzania rozproszonego, kt贸re mog膮 prowadzi膰 do niepowodze艅 w rozwoju oprogramowania. Za艂o偶enia to:

- Sie膰 jest niezawodna
- Op贸藕nienie wynosi zero
- Przepustowo艣膰 jest niesko艅czona
- Sie膰 jest bezpieczna
- Topologia si臋 nie zmienia
- Jest jeden administrator
- Koszt transportu wynosi zero
- Sie膰 jest jednorodna

Pierwsze cztery pozycje zosta艂y wymienione przez [Billa Joya](https://en.wikipedia.org/wiki/Bill_Joy) i [Toma Lyona](https://twitter.com/aka_pugs) oko艂o 1991 roku i po raz pierwszy sklasyfikowane przez [Jamesa Goslinga](https://en.wikipedia.org/wiki/James_Gosling) jako 鈥濬allacies of Networked Computing鈥?. [L. Peter Deutsch](https://en.wikipedia.org/wiki/L._Peter_Deutsch) doda艂 b艂臋dy 5, 6 i 7. Pod koniec lat 90. Gosling doda艂 贸smy b艂膮d.

Grupa zosta艂a zainspirowana tym, co dzia艂o si臋 w tym czasie w [Sun Microsystems](https://en.wikipedia.org/wiki/Sun_Microsystems) .

Te b艂臋dy powinny by膰 uwa偶nie brane pod uwag臋 podczas projektowania kodu, kt贸ry jest odporny; zak艂adaj膮c, 偶e kt贸rykolwiek z tych b艂臋d贸w mo偶e prowadzi膰 do wadliwej logiki, kt贸ra nie radzi sobie z rzeczywisto艣ci膮 i z艂o偶ono艣ci膮 system贸w rozproszonych.

Zobacz te偶:

- [Poszukiwanie mit贸w rozproszonego przetwarzania (cz臋艣膰 1) 鈥? Vaidehi Joshi na Medium](https://medium.com/baseds/foraging-for-the-fallacies-of-distributed-computing-part-1-1b35c3b85b53)

## Lista rzeczy do przeczytania

Je艣li te koncepcje Ci臋 zainteresowa艂y, mog膮 Ci si臋 spodoba膰 nast臋puj膮ce ksi膮偶ki.

- [Czysty kod - Robert C. Martin](https://www.goodreads.com/book/show/3735293-clean-code) - Jedna z najbardziej szanowanych ksi膮偶ek o tym, jak pisa膰 czysty, 艂atwy w utrzymaniu kod.
- [Zainstalowane programowanie ekstremalne 鈥? Ron Jeffries, Ann Anderson, Chet Hendrikson](https://www.goodreads.com/en/book/show/67834) 鈥? Obejmuje podstawowe zasady programowania ekstremalnego.
- [G枚del, Escher, Bach: wieczny z艂oty warkocz - Douglas R. Hofstadter.](https://www.goodreads.com/book/show/24113.G_del_Escher_Bach) - Ta ksi膮偶ka jest trudna do sklasyfikowania. [Prawo Hofstadtera](#hofstadters-law) pochodzi z ksi膮偶ki.
- [Struktura i interpretacja program贸w komputerowych 鈥? Harold Abelson, Gerald Jay Sussman, Julie Sussman](https://www.goodreads.com/book/show/43713) 鈥? Je艣li by艂e艣 studentem informatyki lub in偶ynierii elektrycznej na MIT lub Cambridge, by艂o to twoje wprowadzenie do programowania. Powszechnie opisywany jako punkt zwrotny w 偶yciu ludzi.
- [Katedra i Bazar - Eric S. Raymond](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar) - zbi贸r esej贸w na temat open source. Ta ksi膮偶ka by艂a 藕r贸d艂em [Prawa Linusa](#linuss-law) .
- [Zasada Dilberta 鈥? Scott Adams](https://www.goodreads.com/book/show/85574.The_Dilbert_Principle) 鈥? Komiczne spojrzenie na korporacyjn膮 Ameryk臋 autorstwa autora, kt贸ry stworzy艂 [Zasad臋 Dilberta](#the-dilbert-principle) .
- [Miesi膮c Mitycznego Cz艂owieka 鈥? Frederick P. Brooks Jr.](https://www.goodreads.com/book/show/13629.The_Mythical_Man_Month) 鈥? Klasyczny tom po艣wi臋cony in偶ynierii oprogramowania. [Prawo Brooksa](#brooks-law) jest centralnym tematem ksi膮偶ki.
- [Zasada Petera 鈥? Lawrence J. Peter](https://www.goodreads.com/book/show/890728.The_Peter_Principle) 鈥? Kolejne komiksowe spojrzenie na wyzwania wi臋kszych organizacji i zarz膮dzania lud藕mi, 藕r贸d艂o [Zasady Petera](#the-peter-principle) .

## Zasoby online

Kilka przydatnych zasob贸w i lektur.

- [CB Insights: 8 praw prowadz膮cych do sukcesu w technologii: zasada 2 pizzy Amazona, zasada 80/20 i inne](https://www.cbinsights.com/research/report/tech-laws-success-failure) 鈥? interesuj膮cy opis niekt贸rych praw, kt贸re mia艂y du偶y wp艂yw na technologi臋.

## eBook w formacie PDF

Projekt jest dost臋pny jako eBook PDF, [pobierz najnowszy eBook PDF za pomoc膮 tego linku](https://github.com/dwmkerr/hacker-laws/releases/latest/download/hacker-laws.pdf) lub sprawd藕 [stron臋 wydania](https://github.com/dwmkerr/hacker-laws/releases) starszych wersji.

Nowa wersja eBooka jest tworzona automatycznie po przekazaniu znacznika nowej wersji.

## Podcast

Hacker Laws pojawi艂 si臋 w [The Changelog](https://changelog.com/podcast/403) , mo偶esz sprawdzi膰 odcinek podcastu, korzystaj膮c z poni偶szego linku:

<a href="https://changelog.com/podcast/403" target="_blank"></a>

## T艂umaczenia

Dzi臋ki wielu wspania艂ym wsp贸艂pracownikom, Hacker Laws jest dost臋pny w wielu j臋zykach. Prosz臋 rozwa偶y膰 sponsorowanie moderator贸w!

J臋zyk | Moderator | Status
--- | --- | ---
[馃嚠馃嚛 Bahasa Indonezja / indonezyjski](./translations/pt-BR.md) | [arywidiantara](https://github.com/arywidiantara) | [](https://gitlocalize.com/repo/2513/id?utm_source=badge)
[馃嚙馃嚪 Brasileiro/Brazylijski](./translations/pt-BR.md) | [Eug锚nio Moreira](https://github.com/eugenioamn) , [Leonardo Costa](https://github.com/leofc97) | [](https://gitlocalize.com/repo/2513/pt-BR?utm_source=badge)
[馃嚚馃嚦 涓枃 / chi艅ski](https://github.com/nusr/hacker-laws-zh) | [Steve Xu](https://github.com/nusr) | Cz臋艣ciowo uko艅czony
[馃嚛馃嚜 Niemiecki / Niemiecki](./translations/de.md) | [Wiktor](https://github.com/viktodergunov) | [](https://gitlocalize.com/repo/2513/de?utm_source=badge)
[馃嚝馃嚪 francuski / francuski](./translations/fr.md) | [Kevin Bockelandt](https://github.com/KevinBockelandt) | [](https://gitlocalize.com/repo/2513/fr?utm_source=badge)
[馃嚞馃嚪 蔚位位畏谓喂魏维 / grecki](./translations/el.md) | [Panagiotis Gourgaris](https://github.com/0gap) | [](https://gitlocalize.com/repo/2513/el?utm_source=badge)
[馃嚠馃嚬 W艂oski/W艂oski](https://github.com/csparpa/hacker-laws-it) | [Claudio Sparpaglione](https://github.com/csparpa) | Cz臋艣ciowo uko艅czony
[馃嚡馃嚨 JP 鏃ユ湰瑾? / japo艅ski](./translations/jp.md) | [Fumikazu Fujiwara](https://github.com/freddiefujiwara) | [](https://gitlocalize.com/repo/2513/ja?utm_source=badge)
[馃嚢馃嚪 頃滉淡鞏? / korea艅ski](https://github.com/codeanddonuts/hacker-laws-kr) | [P膮czek](https://github.com/codeanddonuts) | Cz臋艣ciowo uko艅czony
[馃嚤馃嚮 Latvie拧u Valoda / 艂otewski](./translations/lv.md) | [Artur Jansons](https://github.com/iegik) | [](https://gitlocalize.com/repo/2513/lv?utm_source=badge)
[馃嚨馃嚤 Polski / Polish](./translations/pl.md) | [Mariusz Kogen](https://github.com/k0gen) | [](https://gitlocalize.com/repo/2513/pl?utm_source=badge)
[馃嚪馃嚭 袪褍褋褋泻邪褟 胁械褉褋懈褟 / rosyjski](https://github.com/solarrust/hacker-laws) | [Alena Batitskaja](https://github.com/solarrust) | Cz臋艣ciowo uko艅czony
[馃嚜馃嚫 Castellano / hiszpa艅ski](./translations/es-ES.md) | [Manuel Rubio](https://github.com/manuel-rubio) ( [Sponsor](https://github.com/sponsors/manuel-rubio) ) | Cz臋艣ciowo uko艅czony
[馃嚬馃嚪 Turecki / Turecki](https://github.com/umutphp/hacker-laws-tr) | [Umut I艧ik](https://github.com/umutphp) | [](https://gitlocalize.com/repo/2513/tr?utm_source=badge)
[馃嚭馃嚘 褍泻褉邪褩薪褋褜泻邪 屑芯胁邪 / ukrai艅ski](./translations/uk.md) | [Nazar](https://github.com/troyane) , [Helga 艁astiwka](https://github.com/HelgaLastivka) | [](https://gitlocalize.com/repo/2513/uk?utm_source=badge)

Je艣li chcesz zaktualizowa膰 t艂umaczenie, post臋puj zgodnie z [Przewodnikiem dla wsp贸艂tw贸rc贸w t艂umaczy](https://github.com/dwmkerr/hacker-laws/blob/main/.github/contributing.md#translations) .

## Powi膮zane projekty

- [Porada dnia](https://tips.darekkay.com/html/hacker-laws-en.html) 鈥? otrzymuj codzienne przepisy/zasady hakerskie.
- [Hacker Laws CLI](https://github.com/umutphp/hacker-laws-cli) - Lista, przegl膮danie i ogl膮danie losowych przepis贸w z terminala!
- [Dzia艂anie na podstawie przepis贸w hakerskich](https://github.com/marketplace/actions/hacker-laws-action) 鈥? dodaje losowe prawo hakerskie do 偶膮dania 艣ci膮gni臋cia jako drobny prezent dla wsp贸艂tw贸rcy, dzi臋ki [Umut I艧谋k](https://github.com/umutphp)

## Przyczynianie si臋

Prosimy o wk艂ad! [Zg艂o艣 problem,](https://github.com/dwmkerr/hacker-laws/issues/new) je艣li chcesz zasugerowa膰 dodanie lub zmian臋, lub [Otw贸rz 偶膮danie 艣ci膮gni臋cia,](https://github.com/dwmkerr/hacker-laws/compare) aby zaproponowa膰 w艂asne zmiany.

[Koniecznie przeczytaj Wytyczne dotycz膮ce wk艂adu](./.github/contributing.md) , aby pozna膰 wymagania dotycz膮ce tekstu, stylu i tak dalej. Prosimy o zapoznanie si臋 z [Kodeksem post臋powania](./.github/CODE_OF_CONDUCT.md) podczas dyskusji na temat projektu.

## DO ZROBIENIA

Cze艣膰! Je艣li wyl膮dujesz tutaj, klikn膮艂e艣 link do tematu, kt贸rego jeszcze nie napisa艂em, przepraszam za to - prace w toku!

Mo偶esz [zg艂osi膰 problem,](https://github.com/dwmkerr/hacker-laws/issues) prosz膮c o wi臋cej szczeg贸艂贸w lub [otworzy膰 pull request,](https://github.com/dwmkerr/hacker-laws/pulls) aby przes艂a膰 proponowan膮 definicj臋 tematu.
