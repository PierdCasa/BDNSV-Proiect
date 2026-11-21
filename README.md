# T1 - Text-to-SQL

Construiți un lanț cu mai mulți pași (folosind LangChain sau alte biblioteci la alegere)
care:

 * primește o întrebare în limbaj natural;
 * generează o interogare SQL;
 * o execută;
 * rezumă rezultatul în limbaj natural.

## Trebuie sa:

Tratați întrebările ambigue sau vagi:
  - folosiți prompt engineering sau tehnici care țin cont de schemă pentru a ghida
LLM-ul;
  -  includeți contextul schemei în prompt.

Comparați generarea interogărilor SQL cu diferite LLM-uri:
  -  evaluați diferențele de acuratețe, sintaxă și logică ale interogărilor

Tratați erorile și optimizați pe baza feedbackului:
  - adăugați mecanisme de detectare și corectare a interogărilor SQL invalide;
  - implementați o buclă de feedback din partea utilizatorului (de exemplu,
    aprobare/respingere, corecturi);
  - opțional, explorați few-shot sau chain-of-thought prompting.

Testați soluția pe benchmark-uri cunoscute:
  - folosiți Spider sau BIRD pentru a măsura Exact match accuracy și Execution
accuracy.

## Interfață (opțional): o interfață web sau CLI simplă.
