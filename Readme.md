# Jak určit jazyk

1. Podle parametru v url - Není nutný config v site.json
    * /cs
    * /en
    
    V site.json by se pouze urcil default lang a to je vse.
    
    * Výhody: Minimální konfigurace, na nic se nezapomene
    * Nevýhody: Není možné dělat url typu /volna-mista /vacancies bez zadaneho jazyku
    
2. Podle konfigu v site.json

    U definice stranky pribude polozka lang, kde se urci o jaky jazyk se jedná
    Kompletní správa na straně CD
    
    V site.json se musi urcit default jazyk + dopsat langs ke strankam
    
    * Výhody: Velka možnost konfigurace. Muzu si zvolit, zda chci /en/vacancies, nebo /vacancies
    * Nevýhody: Musím duplikovat/triplikovat pocet stranek v site.json. Sice pouzivaji stejnou sablonu, ale musim jednotlive stranky definovat vícekrat.