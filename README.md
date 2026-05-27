DEADLINE:
    cercare un dataset entro le 10:30am 

ideas, brainstorming?
    ho pensato di cercare un dataset che si tratti di giochi in generali. ho trovato dei open datasets su kaggle: 
    volevo trattare di questi argomenti: 
    no istg i wanted to do this :(- sport NBA - Quanti italiani giocano a basket e dove, e se in questi ultimi anni è cresciuto in vari posti
    nah too much math- gioco d'azzardo - quanto gli italiani spendono in slot, scommesse
    videogiochi YES - esports in italia sta crescendo? quante persone seguono e partecipano in italia rispetto ad altri paesi internazionali

Domande che mi sono posto:
videogiochi: esports in italia- sta crescendo? quante persone seguono e partecipano in italia rispetto ad altri paesi internazionali e soldi accumulati

Esports in Italia: 

    Dal Covid ad oggi:
        2020 durante il covid l'interesse per gli esports è cresciuto molto, sia di spettatori che partecipanti
        2022 è sceso di 10% 
        2024 è crescita

    Giochi piu popolari:
        LOL
        Valorant
        CS:GO
        Fortnite
        FIFA/ FC
        Age of Empire 2 (per curiosità)
    
    Soldi 
        Il mercato degli esports ha guadagnato molti soldi negli ultimi anni. 
        I premi dei tornei sono cresciuti molto dal 1998 ad oggi e continuano a crescere ogni anno.
    
    Piattaforme
        Twitch
        Youtube

    Dataset che ho usato:

    Kaggle - Esports Earnings 1998–2023 (dati su premi, giochi e paesi): https://www.kaggle.com/datasets/rankirsh/esports-earnings utilizzerò solo dal 2019(covid) ad oggi
    IIDEA - Dati su spettatori e piattaforme italiane: https://iideassociation.com/wp-content/uploads/2024/11/2024-Italian-Esports-Report_Market-Streaming-Trends.pdf 

    Esports Italiano rispetto esports internazionale:
    E' ancora molto piccola rispetto ai paesi come Corea del Sud, USA ma la crescita è alto.


ho creato il repository eSports_in_Italia 

installazioni di tutte le cose necessarie lib/ csv 
    pip install pandas numpy matplotlib seaborn scikit-learn
    importato anche i 2 csv generical e historical esports data


Contenuto file genericalesportsdata.csv:
    Game =Nome del gioco
    ReleaseDate =Anno di uscita del gioco
    Genre =Tipo di gioco
    TotalEarnings =Totale soldi vinti in tutti i tornei sia online che in presenza
    OfflineEarnings =Soldi vinti solo nei tornei in presenza 
    PercentOffline =Percentuale dei guadagni che vengono da tornei in presenza
    TotalPlayers =Num. totale di giocatori professionisti
    TotalTournaments =Numero totale di tornei svolti

Contenuo file historicalesportsdata.csv:
    Date =Mese e anno del torneo
    Game =Nome del gioco
    Earnings =Soldi incassati in quel mese per quel gioco
    Players =Numero di giocatori in quel mese
    Tournaments =Numero di tornei in quel mese


