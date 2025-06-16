# Info-Vis Datastory

Stappen om dingen aan te passen:

Als je de hoofdpagina wilt aanpassen:
1. Open 'docs/notebook.ipynb'. Raak verder niets aan.

2. Maak de aanpassingen in de notebook die je wilt maken.

3.1: Als je plaatjes toe wilt voegen, maak in InfoVis_Datastory/docs een map 'images' en plak ze hier in.

3.2 Als je csv's toevoegt, voeg ze toe in InfoVis_Datastory/docs.

4. run in de terminal 'conda activate jupyterbook'

5. Run via terminal weer 'jupyter-book build .' evt met --all tussen build en . als je geen verandering ziet.

6. Check lokaal of het werkt. Doe opnieuw stap 5 als dit niet zo is. Nog steeds niet, check de code. Zo ja, git commit etc.


Als je een nieuwe pagina/hoofdstuk/etc wilt maken, doe dit in plaats van stap 1
0. Maak een nieuwe branch waar je dit op gaat proberen.
1. Maak een nieuw ipynb bestand, bijvoorbeeld door een van de bestaande te kopiëren en aan te passen naar wens
2. VOORDAT JE VERDER GAAT, open '_toc.yml'. Onder 'chapters:', maak een nieuwe line met exact dit "- file: docs/FILENAAM"
ga verder zoals normaal.



