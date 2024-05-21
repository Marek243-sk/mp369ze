# Repozitár so zdrojovými kódmi a dátami na bakalársku prácu
Repozitár obsahuje 2 .ipynb súbory a 1 .csv súbor s dátami

## grafy.ipynb
V súbore sú vutvorené histogramy a boxploty pre jednotlivé atribúty datasetu, na záver korelačná matica. Súbor slúži na pochopenie dát.

## Modelovanie.ipynb
V súbore najprv dochádza k predspracovaniu dát, následne sa rozdelí dataset na trénovaciu a testovaciu podmnožinu a vytvárajú sa modely:
  - Náhodný les
  - Rozhodovací strom
  - Logistická regresia
  - MLP Classifier
Potom dochádza k nadvzorkovaniu trénovacej podmnožiny a opätovnému vytvoreniu rovnakých modelov.

Na záver fázy modelovania sa vytvárajú ďalšie modely:
  - Easy Ensemble Classifier
  - Balanced Bagging Classifier
  - Bagging Classifier
  - Adaptive Boosting Classifier

Sú vypočítané metriky:
  - AUC
  - ROC
  - matica zámen
  - úspešnosť, presnosť, návratnosť, F1 skóre

Jednotlivým prípadom z matice zámen sú pridelené váhy a vypočítalo sa skóre každého modelu.

Následne sa vizualizovali výsledky modelov na metrikách.
