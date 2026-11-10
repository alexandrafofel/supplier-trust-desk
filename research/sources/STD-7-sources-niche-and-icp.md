# STD-7: Surse pentru alegerea nisei si ICP

Data accesului pentru toate sursele: 2026-11-10.
Tichet: STD-7. Epic: STD-1.

Fiecare sursa are un nivel de incredere:

- **P (primara)**: text legal sau organismul care detine standardul.
- **S (secundara)**: presa, firme de avocatura, asociatii de industrie.
- **V (vendor)**: firme care vand solutii. Se folosesc doar ca indiciu, nu ca dovada.

Coloana "Nisa" foloseste: **A** = furnizori auto tier 2-3, **I** = subcontractori industriali, **T** = furnizori IT si servicii IT.

## 1. Presiunea clientilor mari

| # | Sursa | Tip | Nisa | Ce sustine |
|---|---|---|---|---|
| 1 | [Directiva NIS2 (UE) 2022/2555, EUR-Lex](https://eur-lex.europa.eu/eli/dir/2022/2555) | P | I, T | Art. 21(2)(d) cere securitatea lantului de aprovizionare, inclusiv relatia cu furnizorii directi. Art. 21(3) cere evaluarea practicilor de securitate ale fiecarui furnizor direct. |
| 2 | [Regulamentul de punere in aplicare (UE) 2024/2690, EUR-Lex](https://eur-lex.europa.eu/eli/reg_impl/2024/2690/oj/eng) | P | T | Detaliaza masurile din Art. 21(2) pentru furnizorii digitali (cloud, servicii gestionate, centre de date etc.). |
| 3 | [OUG 155/2024 (copie PDF gazduita de UPT)](https://upt.ro/img/files/legislatie/2024/OUG_155_2024.pdf) | P | I, T | Transpunerea NIS2 in Romania. Include securitatea lantului de aprovizionare si relatia cu furnizorii directi. Sursa oficiala ramane Monitorul Oficial. |
| 4 | [RISI, tracker NIS2 Romania](https://www.risidata.com/regulations/nis2/countries/ro) | S | I, T | OUG 155/2024 a fost aprobata prin Legea 124/2025, in vigoare din 10 iulie 2025. Autoritate: DNSC. |
| 5 | [Clifford Chance, NIS2 pentru companii din Romania (dec. 2025)](https://www.cliffordchance.com/briefings/2025/12/navigating-nis2-cybersecurity-compliance-obligations-for-romanian-companies.html) | S | I, T | Context juridic actualizat pentru Romania. |
| 6 | [Regulamentul DORA (UE) 2022/2554, EUR-Lex](https://eur-lex.europa.eu/eli/reg/2022/2554/oj/eng) | P | T | Art. 28 la 30: bancile si entitatile financiare fac due diligence pe furnizorii TIC si impun clauze contractuale. Aplicabil din 17 ianuarie 2025. |
| 7 | [ENX, pagina TISAX](https://enx.com/en-US/TISAX/) | P | A | TISAX este mecanismul de evaluare si schimb folosit in industria auto, pe baza catalogului VDA ISA. |
| 8 | [ENX, "20000 TISAX Locations" (2025-12-09)](https://enx.com/news/20000%20TISAX%20locations) | P | A | Peste 20.000 de locatii evaluate cu etichete TISAX valide la nivel mondial. ENX nu publica impartirea pe tier. |
| 9 | [Docusnap, TISAX overview](https://www.docusnap.com/en/it-documentation/tisax-overview) | V | A | Cerinta coboara de la OEM la tier 1, apoi la tier 2 si tier 3. Marimea firmei nu conteaza. |
| 10 | [Orbiq, TISAX compliance guide](https://www.orbiqhq.com/eu-regulations/tisax-compliance) | V | A | AL2 este cerinta standard pentru majoritatea furnizorilor tier 1 si 2. Cu baza ISO 27001, AL2 vine in 3 la 6 luni. Fara baza, 9 la 12 luni. |
| 11 | [TUV NORD, conditii TISAX (PDF)](https://tuv-nord.com/fileadmin/Content/TUV_NORD_COM/TUEV_NORD_MEXICO/pdf/G-D-01-AnexoD-DescripciondeServiciosTISAX-Rev.00.pdf) | S | A | Regulile ENX nu permit reduceri formale ale efortului de evaluare TISAX pe baza unui certificat ISO 27001. |
| 12 | [Hard2bit, NIS2 pentru IMM furnizori](https://hard2bit.com/en/blog/nis2-practical-obligations-for-supplier-smes/) | V | I, T | Clientii reglementati transmit cerintele prin clauze de achizitie, chestionare si cereri de dovezi, chiar daca IMM-ul nu e reglementat direct. |

## 2. Buget si costul durerii

| # | Sursa | Tip | Nisa | Ce sustine |
|---|---|---|---|---|
| 13 | [Wolfia, costul real al chestionarelor manuale](https://www.wolfia.com/blog/the-real-cost-of-manual-security-questionnaire-responses) | V | T | Aproximativ 5,5 ore si 700 la 900 USD per chestionar de complexitate medie. Date SaaS din SUA. |
| 14 | [Petronella Tech, chestionare fara echipa de securitate](https://petronellatech.com/blog/vendor-security-questionnaire-guide-how-to-answer-without-a-security-team) | V | T | 20 la 40 de ore per chestionar fara proces. Aproximativ 80% din intrebari se repeta. Argument direct pentru banca de raspunsuri. |
| 15 | [Kolonell, chestionare pentru furnizori B2B (oct. 2026)](https://kolonell.com/en/blog/ai-vendor-security-questionnaire-response-automation-cost-2026) | V | A, I | Furnizorii care vand catre conturi mari primesc 30 la 60 de chestionare pe an, 6 la 12 ore fiecare. |
| 16 | [Wolfia, chestionare DORA 2026](https://wolfia.com/blog/dora-vendor-risk-questionnaire-requirements-for-2026) | V | T | Art. 28 si 29 DORA cer evaluare inainte de onboarding pentru orice furnizor TIC, indiferent de criticitate. |
| 17 | [Profit.ro, ACAROM](https://profit.ro/povesti-cu-profit/auto-transporturi/noul-presedinte-ford-otosan-craiova-ales-vicepresedinte-acarom-21114737) | S | A | ACAROM are 170 de membri, majoritatea producatori de componente, cu cifra de afaceri de peste 16 mld. EUR. |
| 18 | [Economica.net, ACAROM](https://www.economica.net/?p=539740) | S | A | Aproximativ 600 de furnizori de componente auto in Romania, cu 68 la 70% din cifra de afaceri a sectorului. |
| 19 | [Forbes Romania, productie auto 2025](https://www.forbes.ro/?p=482470) | S | A | Productia auto 2025: 545.510 unitati, cu 2,6% sub 2024. Indiciu de presiune pe costuri la furnizori. |

## 3. Canale inbound (fara apeluri)

| # | Sursa | Tip | Nisa | Ce sustine |
|---|---|---|---|---|
| 20 | [DIGITAL SME, ghid pentru furnizori NIS2](https://www.digitalsme.eu/digital-sme-launches-guide-to-position-smes-as-trusted-nis2-suppliers/) | S | I, T | Sondajul lor arata ca multe IMM-uri nu stiu ce li se cere de la clientii reglementati. Exista un NIS2 Hub. Canal posibil: continut si parteneriat cu asociatia. |
| 21 | [VDMA, grup de lucru NIS2 pentru IMM industriale](https://www.vdma.eu/groups-details/-/group/89454) | S | I | Grup dedicat firmelor industriale sub 500 de angajati. Canal posibil: comunitati de industrie, nu outreach direct. |
| 22 | [Bureau Veritas, webinar TISAX](https://certification.bureauveritas.com/webinar-introduction-tisax) | S | A | Publicul tinta numit: manageri de proiect, securitate si calitate la furnizori tier 1, 2 si 3. Ajuta la rolul care decide. |
| 23 | [Orbiq, sablon chestionar furnizor UE](https://www.orbiqhq.com/templates/eu-vendor-security-questionnaire) | V | I, T | Concurentii folosesc sabloane gratuite fara email ca lead magnet. Confirma modelul Gap Checker (STD-18). |

## Goluri de date

1. **Volume de cautare.** Nu am acces la Google Keyword Planner. Scorul "canale inbound" ramane calitativ pana cand Alexandra exporta volumele pentru 10 la 15 termeni per nisa.
2. **Buget per nisa.** Nu exista date publice despre cat cheltuie un IMM pe raspunsuri la chestionare in UE. Sursele 13 la 16 sunt de la vendori, majoritatea cu date din SUA.
3. **Numar de furnizori afectati.** ENX nu publica impartirea pe tier. Nu am gasit cifre pentru subcontractori industriali sau firme IT din Romania care primesc chestionare NIS2.
4. **Calitatea surselor vendor.** Sursele V au interes comercial. Nu se folosesc singure pentru cele 3 motive din AC.
