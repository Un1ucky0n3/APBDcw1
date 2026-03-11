"pierwsze elo zelo" 
"mala zmiana na readme zad5"
cw5
  Dlaczego merge nie byl fast-forward? Pojawiły się nowe commity na mainie po tym jak mergowany branch odłączył się od maina
cw7
  1. Git wykona fast-forward gdy main nie ma zadnych nowych commitow od momentu odlaczenia sie brancha, merge zajdzie kiedy na      obu galeziach (marge i branch) zaszly jakies zmiany
  2. Merge łączy commity i zahcowuje ich historie, rebase uklada commity jednego brancha na koniec drugiego
  3. Konflikt został rozwiązany ręcznie w GUI Raidera, w oknie do mergowania.
