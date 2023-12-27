### 100 domande sull'HTML a cui uno Sviluppatore deve sapere rispondere

1. Cos'è HTML?
   ***html è un linguaggio di formattazione, cioè che da forma ad un testo online

2. Qual è l'attuale versione standard di HTML?
   ***La versione attuale di Html è la versione html 5.

3. Qual è la differenza tra HTML e XHTML?
   ***Ci sono varie differenze tra Html e xhtml che riguardano la "sintassi", "la case sensitivity", i "tag vuoti", gli "attributi citati", "l'error handling" e la "compatibilità".
4. Che cosa significa DOCTYPE e a cosa serve?
  ***"Doctype" significa Document Type Definition e serve a dichiarare al browser quale versione di Html o Xhtml viene usata

5. Come si struttura un documento HTML di base?
   ***Un documento html è strutturato da un "head" in cui vi sono alcuni elementi identificativi, non visibili nel browser, del sito come il "title" e il "body", il corpo del sito i cui elementi verrano visualizzati dl browser.

6. Qual è la differenza tra un elemento e un tag?
   ***La differenza sta nel fatto che il tag definisce l'inizio e la fine di uno o più elementi. Mentre l'elemento è la parte all'interno di un tag che ne definisce le caratteristiche. 

7. Come si inseriscono i commenti in un documento HTML?
   *** I commenti, in un documento html, si inseriscono con "<--!commento-->".

8. Quali sono gli elementi `<head>` più comuni in un documento HTML?
   ***Gli elementi più comuni dell "<head>" sono: <title>, <style>, <meta>, <link>, <script> e <base>

9. Che cosa fa l'elemento `<title>`?
   *** l'elemento <title> si occupa di definire il titolo del sito.

10. Come si collega un foglio di stile CSS a un documento HTML?
   ***Il foglio style css si lega ad un documento html tramite "<link rel="stylesheet" href="style.css">" nell'head dell'html

11. Come si collega uno script JavaScript a un documento HTML?
   ***Uno script di javascript si puo collegare ad un documento html con "<script src="script.js> </script> nel body dell'html.

12. Qual è la differenza tra elementi di blocco e elementi inline?
   ***La differenza tra elementi di blocco ed elementi inline sta nello spazio che occupano nella pagina e sul fatto di iniziare o meno su una nuova linea

13. Come si crea un link ipertestuale in HTML?
   ***Un link ipertestuale, in html, si crea con "<a href="link sito">sito</a>"

14. Che cos'è un attributo in HTML?
   ***Un attributo in HTML è un elemento o più elementi che aggiungono caratteristiche od influiscono sul comportamento di un tag.

15. Come si inserisce un'immagine in una pagina HTML?
   ***Un'immagine su HTML si può inserire con "<img src="immagine" alt="immagine">

16. Che cos'è l'attributo `alt` in un'immagine e perché è importante?
   ***L'attributo "alt" in un'immagine è un attributo che serve a fornire un testo alternativo ad un'immagine. La sua importanza è data dal fatto che in alcuni casi l'immagine non riesce ad essere visualizzata ed la persona può leggere la descrizione dell'attributo "alt".

17. Come si crea una lista ordinata o non ordinata in HTML?
   ***In HTML, una lista ordinata la si crea con <ol> </ol> e all'interno i vari elementi della lista sono contraddistinti da<li>.
   Invece la lista non ordinata ha il tag <ul></ul> e sempre all'interno si trova <li>.

18. Qual è la differenza tra `<div>` e `<span>`?
   ***Le differenze tra <div> e <span> hanno varie differenze ma ciò che particolarmente li contraddistingue è il fatto che lo span si occupa di piccoli frammenti di testo mantre il div si usa strutturare il layout della pagina tramite blocchi.


19. Che cos'è un iframe e come si utilizza?
   ***Un iframe (sta per "inline frame") è un elemneto dell'html che permette di visualizzare gli elementi di una pagina web all'interno di un'altra.

20. Come si può inserire un video o un file audio in HTML?
   ***Un file audio si può inserire nell'html con <audio controls><source src="file audio" type="tipo di file audio"> </audio>
   Mentre un video si inserisce con <video width "larghezza" height "altezza" controls><source src="file video" type="tipo di file video"></video>

21. Che cos'è il modello a box di CSS e come interagisce con HTML?
    ***Il modello box di css è ciò che definisce il layout e la formattazione degli elementi dell'html

22. Come si crea una tabella in HTML?
   ***In html una tabella la si crea con elemento <table> </table>, al cui interno si trovano <tr> per le righe, <th> per l'intestazione della colonna e <td> per i dati di una cella.

23. Qual è la differenza tra `thead`, `tbody` e `tfoot` in una tabella?
   ***La differenza tra i 3 elementi sta nel fatto che il thead è usata per le righe di intestazione, il tbody contiene le righe principali della tabella e il tfoot contiene le note a piè di pagina della tabella.


24. Come si può migliorare l'accessibilità in una pagina HTML?
    ***Ci sono vari metodi per migliorare l'accessibilità in una pagina HTML, come usare bene ed in maniera strutturata i vari tag dell'HTML, l'utilizzo di testo alternativo per le immagini, un corretto utilizzo e dei moduli e una buona strutturalizzazione, un buon uso degli ARIA (Accessible Rich Internet Applications), una buona leggibilità del testo, ordine cronologico del contenuto, adattabilità del testo, accessibilità del testo e tesing del sito per controllare l'accessibilità del sito con strumenti tipo WAVE (Web Accessibility Evaluation Tool) o Lighthouse.

25. Che cos'è ARIA in HTML e a cosa serve?
   ***Aria in HTMl sta per Accessible Rich Internet Applications e serve a migliorare l'accessibilità delle applicazioni web per le persone con disabilità.

26. Come si crea un modulo in HTML?
   ***Il modulo, in HTML, si crea tramite il tag <form></form> che racchiude dentro di se gli elementi input del form. 

27. Quali sono i vari tipi di input che si possono usare in un modulo HTML?
   I tipi di input in un modilo html sono: il text, la password, email, il number, il checkbox, il radio button, textarea, il select, il file imput, submit button, il reset button e l'hidden button.

28. Che cos'è il metodo GET rispetto al metodo POST in un modulo?
   ***Il metodo get

29. Come si può validare l'input del modulo in HTML5?
   ***Si può validare il modulo in HTML5 con vari attributi che sono: required, pattern, min e max, type, novalidate, etc.

30. Che cos'è e come si utilizza il canvas in HTML?
   ***Il tag <canvas> in HTML fornisce uno spazio per disegnare grafica tramite script, di solito JavaScript. 

31. Quali sono le nuove caratteristiche introdotte in HTML5?
   ***Le caratteristiche che innovano HTML5 sono elementi semantici come <header>, <footer>, <article>, <section>, <nav>, <figure>, <figcaption>. Elementi multimediali come <audio> e <video>. Elementi grafici come <svg>, Api di geolocalizzazione, elementi di web Storage come sessionStorage e localStorage per consentire ai siti web di archiviare dati in modo persistente o di sessione lato client.
   Elementi API che consentono l'esecuzione di script in background. Utilizzo di WebSocket, che fornisce una comunicazione bidirezionale e full-duplex tra il browser e il server .Nuovi tipi di input come <input type="date">, <input type="email">, <input type="url">, e altri. Aggiunta di attributi di validazione dei form, come required e pattern.API di drag-and-drop per trascinamento e il rilascio di elementi con l'aggiunta di API di drag-and-drop. API di notifica che consentono ai siti web di inviare notifiche push al dispositivo dell'utente.

32. Che cos'è il web storage in HTML5?
    ***Il Web Storage in HTML5 è una tecnologia che consente ai siti web di archiviare dati localmente sul dispositivo di un utente. Ci sono 2 tipi di Web storage: Local storage e Session storage.

33. Che cos'è e come si utilizza l'elemento `<datalist>` in HTML?
    ***L'elemento <datalist> in HTML è un elenco di opzioni predefinite per un elemento di input <input> e serve per fornire suggerimenti o opzioni per aiutare gli utenti durante l'inserimento dei dati in un campo di input.


34. Come si può incorporare un file SVG in una pagina HTML?
    ***Un elemento SVG si può incorporare in una pagina HTML tramite i tag <svg> o <img>

35. Qual è la differenza tra `cookies`, `sessionStorage` e `localStorage`?
    ***la principale differenza tra questi tre meccanismi risiede nella durata di conservazione dei dati e nella portata dell'accesso.

36. Che cos'è la geolocalizzazione in HTML5 e come si utilizza?
    ***La geolocalizzazione in HTML5 è una funzionalità che consente ai browser web di ottenere informazioni sulla posizione geografica dell'utente attraverso il dispositivo che sta utilizzando. Per utilizzare la geolocalizzazione in HTML5, è possibile utilizzare l'API di geolocalizzazione che è integrata nei browser moderni.


37. Che cos'è il drag-and-drop in HTML5 e come si implementa?
   ***Il "drag-and-drop" in HTML5 si riferisce alla capacità di trascinare elementi HTML da una posizione e rilasciarli in un'altra all'interno di una pagina web. Per implementare il drag and drop in HTML5, è necessario utilizzare l'API di Drag and Drop fornita nativamente dal browser.

38. Come si può implementare la paginazione in un documento HTML?
39. Che cosa sono le meta tag e a cosa servono?
40. Come si imposta il charset in un documento HTML?
41. Qual è la differenza tra elementi `<b>` e `<strong>`?
42. Qual è la differenza tra elementi `<i>` e `<em>`?
43. Come si crea un elenco a definizioni in HTML?
44. Che cos'è un attributo globale in HTML?
45. Che cosa fa l'attributo `data-*` in HTML?
46. Come si implementa una barra di navigazione in HTML?
47. Come si crea un breadcrumb in HTML?
48. Che cos'è il semantic markup in HTML?
49. Come si utilizza l'elemento `<article>` in HTML5?
50. Come si utilizza l'elemento `<section>` in HTML5?
51. Come si utilizza l'elemento `<aside>` in HTML5?
52. Che cos'è e come si utilizza l'elemento `<footer>` in HTML5?
53. Che cos'è e come si utilizza l'elemento `<header>` in HTML5?
54. Come si implementa un layout a griglia con HTML?
55. Qual è lo scopo dell'elemento `<nav>` in HTML?
56. Come si possono creare forme personalizzate con HTML e CSS?
57. Che cos'è e come si utilizza l'elemento `<figure>` in HTML5?
58. Che cos'è l'elemento `<figcaption>` e come si utilizza?
59. Come si implementa l'ottimizzazione delle immagini in una pagina web?
60. Che cosa sono le responsive images in HTML5?
61. Come si utilizza l'elemento `<picture>` in HTML5?
62. Che cos'è il lazy loading delle immagini e come si implementa?
63.

Come si gestiscono i font web in HTML? 64. Che cos'è e come si utilizza l'elemento `<main>` in HTML5? 65. Che cosa sono e come si usano i Web Components? 66. Come si utilizza l'elemento `<template>` in HTML5? 67. Come si possono creare dei tooltip personalizzati con HTML e CSS? 68. Che cos'è un polyfill e a cosa serve? 69. Come si implementa l'animazione con HTML e CSS? 70. Che cos'è e come si usa l'attributo `role` in HTML? 71. Come si implementa l'accessibilità per le immagini in HTML? 72. Che cos'è e come si usa l'elemento `<progress>` in HTML5? 73. Che cos'è e come si usa l'elemento `<meter>` in HTML5? 74. Come si implementa una barra di ricerca in HTML? 75. Che cos'è un Document Type Definition (DTD) in HTML? 76. Come si utilizza l'elemento `<output>` in HTML5? 77. Che cos'è il cross-origin resource sharing (CORS) in HTML? 78. Come si imposta un favicon per un sito web? 79. Che cos'è e come si usa l'attributo `tabindex` in HTML? 80. Come si implementa un controllo di zoom personalizzato in una pagina web? 81. Che cos'è e come si usa l'elemento `<dialog>` in HTML5? 82. Come si può migliorare la leggibilità del testo in HTML? 83. Che cos'è e come si usa l'elemento `<mark>` in HTML5? 84. Come si possono creare tabelle responsive in HTML e CSS? 85. Che cos'è e come si usa l'elemento `<summary>` e `<details>` in HTML5? 86. Come si implementano le mappe interattive in HTML? 87. Che cos'è e come si usa l'elemento `<time>` in HTML5? 88. Come si possono gestire le icone in una pagina HTML? 89. Che cos'è e come si usa l'attributo `contenteditable` in HTML? 90. Come si può creare un layout multi-colonna in HTML e CSS? 91. Che cos'è e come si implementa il controllo ortografico in HTML? 92. Che cos'è un framework CSS e come interagisce con HTML? 93. Come si possono creare animazioni di testo in HTML e CSS? 94. Che cos'è e come si implementa un parallax scrolling in HTML e CSS? 95. Come si possono creare effetti di ombreggiatura in HTML e CSS? 96. Che cos'è e come si utilizza l'attributo `download` in HTML5? 97. Come si possono creare breadcrumb dinamici in HTML? 98. Che cos'è e come si usa l'attributo `pattern` in un input HTML? 99. Come si può ottimizzare una pagina web per la stampa utilizzando HTML e CSS? 100. Che cos'è e come si usa l'elemento `<noscript>` in HTML?
