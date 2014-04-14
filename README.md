Psaltério
=========
Este é o repositório oficial das músicas do Psaltério (www.psalterio.net).
Todas as músicas estão no formato latex que permite criar uma impressão de qualidade tipográfica, exemplo:  [Separata ACRE 2014](https://github.com/psalterio/repository/blob/master/songbooks/acre-2014/separata_acre_2014.pdf?raw=true) e também gera a base de dados automaticamente para o novo site do psaltério (http://novo.psalterio.net/) e as novas mobile Apps (iOS7 e [Android](https://play.google.com/store/apps/details?id=net.psalterio.psalterioandroid)). É um verdadeiro 3 em 1 :)


Como ajudar
-----------
Precisamos de corrigir as músicas que foram convertidas em latex (o novo formato do Psaltério) para podermos lançar as novas mbile Apps e o novo site. Neste momento precisamos de ajuda para corrigir da música 51 à 165. Temos que corrigir usando o formato temporário em http://novo.psalterio.net. As músicas que aparecem com duas colunas (verde do lado esquerdo e azul-cinzento do lado direito) são as múscas que ainda não estão corrigidas. Cada música tem um "id" único, por exemplo a música 52 é a música "Estamos Unidos" e o link é http://novo.psalterio.net/52.


**Mini Tutorial para fazer correcções directamente no GitHub**  
(serve perfeitamente para fazer a maior parte das correcões):  
1 - Abrir directamente o link da musica no github. Exemplo:  
https://github.com/psalterio/repository/blob/master/songs/pt/agradecer.tex  
2 - login no github (criar uma conta se ainda não tens). Qualquer pessoa com conta no github pode submeter alterações, que depois são revistas e autorizadas.   
3 - carregar no botão “Edit” no canto superior direito  
4 - fazer as correcções necessárias   
5 - carregar no botão “Propose file change”  
6 - carregar no botão “Send Pull request”. Done!  
depois nós recebemos uma notificação de que existem alterações a fazer e podemos aprovar.


**Tutorial para fazer correcções no teu PC**  
um pouco mais complicado que o mini tutorial mas é melhor a longo termo para quem faz muitas correcções: https://www.youtube.com/watch?v=Eu-_wI-p-Hs



Lista do progresso das correções:
---------------------------------
**corrigidas com o scan** (1-50)

01,02,03,04,05,06,07,08,09,10,  
11,12,13,14,15,20,  
21,22,23,24,25,26,27,28,29,30,  
31,32,33,34,35,36,37,38,39,40,  
41,42,43,44,45,46,47,48,49,50,  

**corrigidas com o site** (51-165)



51,  
85,  
122,  
143,144,145,146,147,148,149,150,  
151,152,153,154,155,156,157,158,159,160,  
161,162,163,164,165  


outras coisas a fazer
---------------------
* converter todos os bemois ("b" em "&") 
* converter todos os acordes de sétima (7), quarta (4), etc para os respectivos sobreescritos
 * exemplo em latex sobrescrito (eu sei que parece complicado, mas depois de fazer uns quantos percebe-se melhor)
  * "D7" fica "**D$^{7}$**"
  * "D9 5+" fica "**D$^{9 5+}$**"
- corrigir a metrica e o alinhamento dos acordes
- comparar com as musicas originais do psalterio > scan_psalterio_original 


Latex
-----
As músicas neste repositório estão em formato latex. Estas são algumas das regras mais importantes para a formatação correcta das músicas e acordes em latex:
- acordes são sempre escritos no seguinte formato \\[acorde aqui]
 * exemplo \\[D]
- acorde com numero sobrescrito
 * "D7" fica "**D$^{7}$**"
 * "D9 5+" fica "**D$^{9 5+}$**"
 * 
 
Acordes no Psaltério
--------------------

Resumo do standard usado:
- C é um acorde de dó maior (dó, mi, sol)
- Cm é um acorde de dó menor (dó, mi-b, sol)
- C7+ é o acorde de sétima maior (dó, mi, sol, si). C7+ é o mesmo que Cmaj7 ou CM7 noutras notações.
- C4 é um acorde suspenso de quarta (dó, fá, sol). É o mesmo que Csus4 ou Csus noutras notações.
- C4(7) é um acorde de 4a suspensa com sétima menor (dó, fá, sol, si-b). Noutras notações aparece normalmente como C7sus4.

O standard dos acordes no psaltério está nestes mapas de acordes:
- [1](https://github.com/psalterio/repository/blob/master/songbooks/psalterio/scan_psalterio_original/0-3_mapa_acordes.jpg)
- [2](https://github.com/psalterio/repository/blob/master/songbooks/psalterio/scan_psalterio_original/0-4_mapa_acordes.jpg)
- [3](https://github.com/psalterio/repository/blob/master/songbooks/psalterio/scan_psalterio_original/0-5_mapa_acordes.jpg)
- [4](https://github.com/psalterio/repository/blob/master/songbooks/psalterio/scan_psalterio_original/0-6_mapa_acordes.jpg)

Links do Projecto
-----------------

- site oficial: http://www.psalterio.net
- wikipedia   : [http://pt.wikipedia.org/wiki/Psaltério](http://pt.wikipedia.org/wiki/Psalt%C3%A9rio)
- youtube     : https://www.youtube.com/user/psalterio7
- twitter : https://twitter.com/psalterio
- facebook: https://www.facebook.com/psalterio.pt
- [Android App](https://play.google.com/store/apps/details?id=net.psalterio.psalterioandroid)
