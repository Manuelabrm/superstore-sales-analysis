 Analiză Vânzări — Superstore Sales Dashboard

*Context
Am folosit dataset-ul public "Superstore Sales" (Kaggle) pentru a analiza
performanța vânzărilor pe categorii, produse și evoluție în timp,
răspunzând la întrebări concrete de business.

* Întrebări de business
1. Care e performanța generală a vânzărilor?
2. Ce categorii/produse generează cele mai mari vânzări?
3. Există sezonalitate în vânzări?

 *Metodologie
- Explorare inițială a datelor: SQL (SQLite) — verificare structură,
agregări de bază (SUM, GROUP BY pe categorii)
- Curățare, modelare și vizualizare completă: Power BI (Power Query
pentru transformare date, DAX pentru măsuri, dashboard interactiv)


*Insight-uri principale
1. Vânzările totale ating 2.261.536,78 lei, din 9.800 de tranzacții,
cu o valoare medie de 230,77 per tranzacție.
2. Technology e categoria dominantă, urmată de Furniture și Office
Supplies, care au valori apropiate între ele.
3. Canon imageCLASS 2200 Advanced Copier e cel mai vândut produs
individual, cu 61.599,82 — semnificativ peste următorul produs
din top.
4. Vânzările ating un vârf clar în noiembrie (~280K), posibil legat
de sezonul de sărbători/Black Friday, cu un minim în februarie
(~130K).

* Recomandare de business
Dat fiind vârful din noiembrie, o campanie de stoc/promoții concentrată
pe Technology în perioada octombrie-noiembrie ar putea capitaliza pe
tendința deja existentă.

## Tehnologii folosite
SQL (SQLite), Power BI Desktop
