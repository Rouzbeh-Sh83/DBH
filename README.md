# DBH
Analyse i Spyder fra DBH data base.
Det analyse til 5 år har jeg gjort.
Totalen økte med ca. 968 enheter, eller 6 %.
Master vokste mest, fra 1 849 til 2 788 (+51 %).
Videreutdanning falt kraftig, fra 397 til 135 (−66 %).
Bachelor er stabil rundt 9 100–9 800.
streamlit>=1.35
pandas>=2.0
pyarrow>=15
requests>=2.31
openai>=1.40
Filen  åpner og kjører i Spyder er agent_app.py.  

De andre filene:

dbh_client.py og llm_agent.py er hjelpefiler. agent_app.py henter dem inn med import. Det trenger ikke åpne dem, men de må ligge i samme mappe.
requirements.txt  viser hvilke pakker som må installeres. Kjør dette én gang i Spyder-konsollen (eller i Anaconda Prompt):
 Viktig : pip install -r requirements.txt
__pycache__ lager Python selv. 

Slik gjør vi det i Spyder:

Åpne agent_app.py (File → Open).
Sett arbeidsmappen til Agent_Mappe. Spyder gjør vanligvis dette automatisk når du kjører en fil derfra. Hvis ikke, bruker du mappeikonet øverst til høyre.
Trykk F5 for å kjøre.

 Står det import streamlit øverst i agent_app.py? Da fungerer det ikke å trykke F5. Du må i stedet skrive dette i Anaconda Prompt, inne i mappen:

streamlit run agent_app.py
