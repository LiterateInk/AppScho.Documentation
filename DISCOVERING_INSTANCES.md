# Discovering Instances

You can discover instances using a simple [Google Dork](https://www.google.com/search?q=site:play.google.com+%22com.appscho.appschov2.%22).

```plaintext
site:play.google.com "com.appscho.appschov2."
```

You'll get a list of all the deployed apps on the Play Store.

Since every app has a bundle ID that starts with `com.appscho.appschov2.`, you can use this to discover the instance name.

## Known Instances

Using the Google Dork above, we retrieved a list of instances that are known to be deployed.

| ID | Name |
| -- | ---- |
| `unitoulon` | Université de Toulon |
| `digitalcampus` | GGE - Digital Campus |
| `scpoaix` | Sciences Po Aix |
| `essec` | ESSEC Business School |
| `regent` | Regent's University London |
| `iicp` | Narratiiv Inside |
| `icp` | ICP |
| `macromedia` | Galileo Global Education Germany |
| `esarc` | ESARC go |
| `merkure` | Merkure Live |
| `esigelec` | MyESIGELEC |
| `ueve` | OFIL UnivEvry |
| `unieiffel` | Université Gustave Eiffel |
| `esaip` | MyEsaip |
| `psb` | Paris School Of Business |
| `estp` | MyESTP |
| `emstra` | EM Strasbourg INSIDE |
| `wsfactory` | Web School Factory |
| `pstb` | PSTB |
| `epp` | MyEPP |
| `domus` | Nuova Accademia: MyDA |
| `ipp` | IP Paris Campus |
| `ieu` | Instituto de Estudios Universitarios |
| `hec` | HEC Paris |
| `eigsi` | My EIGSI |
| `alijia` | MyELIJE |
| `sciencespo` | Sciences Po |
| `lisaa` | LISAA Campus |
| `essca` | My ESSCA |
| `esg` | ESG Live |
| `mbs` | Montpellier Business School |
| `unimons` | Université de Mons |
| `uniassas` | Université Paris-Panthéon-Assas |
| `bsb` | Burgundy School of Business |
| `univangers` | Université d'Angers |
| `upjv` | Université de Picardie Jules Verne |
| `unilyon3` | Université Jean Moulin Lyon3 |
| `univpoitiers` | Université de Poitiers |
| `edhec` | EDHEC Business School |
| `uclouvain` | Université Catholique de Louvain |
| `ieseg` | IÉSEG Connect |
| `ucly` | My Ucly |
| `ubmont` | Université Bordeaux Montaigne |
| `unimes` | Université de Nîmes |

You can check if the app is still alive by going to `https://play.google.com/store/apps/details?id=com.appscho.appschov2.<id>`.

If the app is not found, it means that the instance is not deployed anymore.

It would be appreciated if you could PR this list with any new instance you find or if you find an instance that is not deployed anymore.
