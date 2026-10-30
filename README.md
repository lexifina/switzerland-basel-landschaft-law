# Basel-Landschaft: law history in git

The law of the canton of Basel-Landschaft (Kanton Basel-Landschaft, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-bl/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

854 acts with 1921 versions so far: the cantonal constitution and acts, regulations, decrees, decisions and agreements from the systematic collection. The current-text additions below have one source-dated version each; earlier versions have not yet been reconstructed.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `100/` | Verfassung des Kantons Basel-Landschaft (SGS 100) | 12 | oldest version available, then each consolidated version: 1 April 2014 to 15 June 2026 |
| `103/` | Gesetz über die Aufnahme des Bezirks Laufen (SGS 103) | 1 | one version (the oldest available), 1 January 1994 |
| `104/` | Gesetz über die Gewaltentrennung (SGS 104) | 5 | as enacted, then each consolidated version: 1 July 2003 to 1 July 2023 |
| `105-haftungsgesetz/` | Gesetz über die Haftung des Kantons und der Gemeinden (SGS 105) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 April 2022 |
| `106-publg/` | Publikationsgesetz (SGS 106) | 1 | as enacted, 1 January 2023 |
| `107/` | Kantonales Statistikgesetz (SGS 107) | 1 | one version (the oldest available), 1 January 2013 |
| `108-eg-glg/` | Einführungsgesetz zum Gleichstellungsgesetz (SGS 108) | 1 | one version (the oldest available), 1 January 2011 |
| `109-behindertenrechtegesetz-bl-brg-bl/` | Gesetz über die Rechte von Menschen mit Behinderungen (SGS 109) | 1 | as enacted, 1 January 2024 |
| `110-bug-bl/` | Bürgerrechtsgesetz Basel-Landschaft (SGS 110) | 2 | oldest version available, then each consolidated version: 1 March 2014 to 1 January 2018 |
| `111-arg/` | Anmeldungs- und Registergesetz (SGS 111) | 5 | oldest version available, then each consolidated version: 1 June 2014 to 1 July 2032 |
| `112/` | Kantonales Gesetz über die Zwangsmassnahmen im Ausländerrecht (SGS 112) | 1 | one version (the oldest available), 1 January 2011 |
| `114-integrationsgesetz/` | Gesetz über die Einführung der Integrationsbestimmungen des Bundesgesetzes über die Ausländerinnen und Ausländer (SGS 114) | 1 | as enacted, 1 January 2008 |
| `116-gfs/` | Gesetz über die frühe Sprachförderung (SGS 116) | 1 | as enacted, 1 September 2024 |
| `120-gpr/` | Gesetz über die politischen Rechte (SGS 120) | 8 | oldest version available, then each consolidated version: 1 April 2014 to 1 May 2025 |
| `131-landratsgesetz/` | Gesetz über die Organisation und die Geschäftsführung des Landrats (SGS 131) | 8 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2025 |
| `140-regierungs-und-verwaltungsorganisationsgesetz-basel-landschaft-rvog-bl/` | Gesetz über die Organisation des Regierungsrats und der Verwaltung des Kantons Basel-Landschaft (SGS 140) | 6 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `150-personalgesetz/` | Gesetz über die Arbeitsverhältnisse der Mitarbeiterinnen und Mitarbeiter des Kantons (SGS 150) | 7 | oldest version available, then each consolidated version: 1 July 2013 to 1 August 2024 |
| `160-ombudsgesetz/` | Gesetz über die Ombudsperson (SGS 160) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2022 |
| `162-informations-und-datenschutzgesetz-idg/` | Gesetz über die Information und den Datenschutz (SGS 162) | 5 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `163-archivierungsgesetz/` | Gesetz über die Archivierung (SGS 163) | 1 | one version (the oldest available), 1 January 2013 |
| `164-e-government-gesetz-e-govg/` | Gesetz über die elektronische Geschäftsabwicklung und Kommunikation (SGS 164) | 4 | as enacted, then each consolidated version: 1 January 2022 to 14 March 2024 |
| `170-gerichtsorganisationsgesetz-gog/` | Gesetz über die Organisation der Gerichte (SGS 170) | 7 | oldest version available, then each consolidated version: 1 April 2014 to 1 January 2020 |
| `175-vwvg-bl/` | Verwaltungsverfahrensgesetz Basel-Landschaft (SGS 175) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 August 2024 |
| `178/` | Anwaltsgesetz Basel-Landschaft (SGS 178) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2025 |
| `180-gemeindegesetz-gemg/` | Gesetz über die Organisation und die Verwaltung der Gemeinden (SGS 180) | 11 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `185-fag/` | Finanzausgleichsgesetz (SGS 185) | 9 | oldest version available, then each consolidated version: 1 January 2013 to 12 September 2023 |
| `189/` | Gesetz über die Umsetzung NFA und die Lastenverteilung auf Kanton und Gemeinden (SGS 189) | 1 | as enacted, 1 January 2008 |
| `191/` | Kirchengesetz (SGS 191) | 3 | oldest version available, then each consolidated version: 1 May 2013 to 1 January 2020 |
| `211-eg-zgb/` | Gesetz über die Einführung des Zivilgesetzbuches (SGS 211) | 9 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2024 |
| `212-eg-or/` | Gesetz über die Einführung des Obligationenrechts (SGS 212) | 1 | one version (the oldest available), 1 January 2014 |
| `213-eg-bewg/` | Gesetz über die Einführung des Bundesgesetzes über den Erwerb von Grundstücken durch Personen im Ausland (SGS 213) | 2 | as enacted, then each consolidated version: 1 July 1988 to 1 January 2015 |
| `217/` | Notariatsgesetz (SGS 217) | 2 | as enacted, then each consolidated version: 1 November 2012 to 1 October 2020 |
| `223/` | Gesetz über die Behörden und das Verfahren bei Streitigkeiten aus Miete und Pacht von unbeweglichen Sachen (SGS 223) | 1 | one version (the oldest available), 1 April 2014 |
| `233-eg-schkg/` | Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (SGS 233) | 1 | one version (the oldest available), 1 April 2014 |
| `241-ubertretungsstrafgesetz-ustg/` | Gesetz über das kantonale Übertretungsstrafrecht (SGS 241) | 1 | one version (the oldest available), 1 January 2013 |
| `261-strafvollzugsgesetz-stvg/` | Gesetz über den Vollzug von Strafen und Massnahmen (SGS 261) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 April 2022 |
| `310-fhg/` | Finanzhaushaltsgesetz (SGS 310) | 6 | oldest version available, then each consolidated version: 1 October 2014 to 1 September 2025 |
| `311/` | Finanzkontrollgesetz Basel-Landschaft (SGS 311) | 3 | oldest version available, then each consolidated version: 1 April 2014 to 1 April 2022 |
| `314-public-corporate-governance-pcgg/` | Gesetz über die Beteiligungen (SGS 314) | 1 | as enacted, 1 January 2018 |
| `331-steuergesetz/` | Gesetz über die Staats- und Gemeindesteuern (SGS 331) | 11 | oldest version available, then each consolidated version: 1 April 2011 to 1 January 2023 |
| `332/` | Gesetz über die Einführung eines zweistufigen Instanzenzugs in Steuersachen (Staats- und direkte Bundessteuer) (SGS 332) | 1 | as enacted, 1 March 2006 |
| `334/` | Gesetz über die Erbschafts- und die Schenkungssteuer (SGS 334) | 1 | one version (the oldest available), 1 January 2013 |
| `341/` | Gesetz über die Motorfahrzeugsteuer (SGS 341) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 November 2020 |
| `342-hundegesetz/` | Gesetz über das Halten von Hunden (SGS 342) | 1 | one version (the oldest available), 1 January 2008 |
| `350-gvg-bl/` | Gebäudeversicherungsgesetz Basel-Landschaft (SGS 350) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `360-sbg/` | Staatsbeitragsgesetz (SGS 360) | 1 | as enacted, 1 January 2020 |
| `362-eg-kvg/` | Einführungsgesetz zum Bundesgesetz über die Krankenversicherung (SGS 362) | 6 | oldest version available, then each consolidated version: 1 January 2014 to 1 April 2023 |
| `363/` | Gesetz über die Nachzahlung von Pflegebeiträgen für das Jahr 2011 (SGS 363) | 1 | as enacted, 1 September 2015 |
| `365/` | Gesetz über Ausbildungsbeiträge (SGS 365) | 2 | oldest version available, then each consolidated version: 1 August 2014 to 1 January 2015 |
| `367/` | Gesetz über Beiträge an Schiessanlagen (SGS 367) | 1 | one version (the oldest available), 1 August 2003 |
| `371/` | Kantonalbankgesetz (SGS 371) | 2 | as enacted, then each consolidated version: 1 January 2005 to 1 January 2018 |
| `381/` | Gesetz betreffend das Bergbau-Regal (SGS 381) | 1 | as enacted, 28 May 1876 |
| `382/` | Gesetz über das Salzregal (SGS 382) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2015 |
| `400-rbg/` | Raumplanungs- und Baugesetz (SGS 400) | 14 | oldest version available, then each consolidated version: 1 October 2013 to 1 January 2024 |
| `404/` | Gesetz über die Abgeltung von Planungsmehrwerten (SGS 404) | 1 | as enacted, 1 May 2019 |
| `410/` | Gesetz über die Enteignung (SGS 410) | 3 | oldest version available, then each consolidated version: 1 April 2014 to 1 January 2019 |
| `415/` | Gesetz über Stand- und Durchgangsplätze für Fahrende (SGS 415) | 1 | as enacted, 1 July 2014 |
| `421/` | Rheinhafengesetz (SGS 421) | 2 | oldest version available, then each consolidated version: 1 May 2008 to 1 January 2015 |
| `430/` | Strassengesetz (SGS 430) | 6 | oldest version available, then each consolidated version: 1 January 2008 to 1 April 2022 |
| `445-wasserbaugesetz-wbaug/` | Gesetz über den Wasserbau und die Nutzung der Gewässer (SGS 445) | 1 | one version (the oldest available), 1 July 2014 |
| `454-grundwassergesetz/` | Gesetz über die Nutzung und den Schutz des Grundwassers (SGS 454) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2022 |
| `455-wasserversorgungsgesetz/` | Gesetz über die Wasserversorgung der basellandschaftlichen Gemeinden (SGS 455) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2015 |
| `480/` | Gesetz zur Förderung des öffentlichen Verkehrs (SGS 480) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2018 |
| `481-svg-bl/` | Strassenverkehrsgesetz Basel-Landschaft (SGS 481) | 2 | as enacted, then each consolidated version: 1 September 2012 to 1 July 2021 |
| `482-fahrdienstgesetz/` | Gesetz über Beiträge an Fahrdienste für mobilitätseingeschränkte Personen (SGS 482) | 1 | as enacted, 1 January 2024 |
| `490-eng-bl/` | Energiegesetz (SGS 490) | 4 | oldest version available, then each consolidated version: 1 July 2013 to 1 March 2025 |
| `493-2/` | Gesetz betreffend die Beteiligung des Kantons Basel-Landschaft an der Errichtung und am Betrieb des Kraftwerkes Birsfelden (SGS 493.2) | 1 | as enacted, 1 September 1950 |
| `501-standortforderungsgesetz/` | Gesetz zur Förderung der Standortqualität (SGS 501) | 2 | as enacted, then each consolidated version: 1 August 2007 to 1 October 2019 |
| `503-tourismusgesetz/` | Gesetz über die Förderung des Tourismus (SGS 503) | 1 | as enacted, 1 December 2003 |
| `504/` | Gesetz über die Ausrichtung von Mietzinsbeiträgen an die Mieterinnen und Mieter von Geschäftsräumlichkeiten im Zusammenhang mit dem Coronavirus (Covid-19) (SGS 504) | 1 | as enacted, 30 November 2020 |
| `510-lg-bl/` | Landwirtschaftsgesetz Basel-Landschaft (SGS 510) | 2 | oldest version available, then each consolidated version: 1 August 2010 to 1 January 2015 |
| `520-wildtier-und-jagdgesetz-wjg/` | Gesetz über den Schutz der wildlebenden Säugetiere und Vögel sowie deren Lebensräume und die Jagd (SGS 520) | 2 | oldest version available, then each consolidated version: 1 April 2013 to 1 January 2022 |
| `530/` | Fischereigesetz (SGS 530) | 1 | one version (the oldest available), 1 January 2013 |
| `540/` | Gastgewerbegesetz (SGS 540) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2015 |
| `541-kmu-entlastungsgesetz/` | Gesetz über die Reduktion der Regelungsdichte und den Abbau der administrativen Belastung für die kleinen und mittleren Unternehmen (KMU) (SGS 541) | 1 | as enacted, 6 June 2005 |
| `543-eg-bgs/` | Einführungsgesetz zum Bundesgesetz über Geldspiele (SGS 543) | 1 | as enacted, 1 January 2021 |
| `545/` | Gesetz betreffend öffentliche Filmvorführungen und Abgabe von elektronischen Trägermedien (SGS 545) | 1 | as enacted, 1 January 2013 |
| `546-gtap/` | Gesetz über den Betrieb von Taxis und anderen gewerbsmässigen Personentransporten (SGS 546) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 October 2020 |
| `547-ruhetagsgesetz-rtg/` | Gesetz über die öffentlichen Ruhetage und den Sonntagsverkauf (SGS 547) | 2 | oldest version available, then each consolidated version: 17 November 2011 to 1 December 2019 |
| `548-gasttaxengesetz/` | Gesetz über die Erhebung einer Gasttaxe (SGS 548) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `563-1/` | Dekret zum Bundesgesetz über das Messwesen (SGS 563.1) | 1 | one version (the oldest available), 1 January 2011 |
| `570-kwag/` | Kantonales Waldgesetz (SGS 570) | 1 | one version (the oldest available), 1 January 2007 |
| `600-kulturforderungsgesetz-kfg-bl/` | Gesetz über die Kulturförderung (SGS 600) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2024 |
| `630/` | Gesetz über die Sportförderung (SGS 630) | 2 | as enacted, then each consolidated version: 1 October 1991 to 1 March 2021 |
| `640/` | Bildungsgesetz (SGS 640) | 18 | oldest version available, then each consolidated version: 1 August 2014 to 1 August 2026 |
| `645/` | Schulgesundheitsgesetz (SGS 645) | 3 | oldest version available, then each consolidated version: 11 August 1997 to 1 August 2024 |
| `700-polg/` | Polizeigesetz (SGS 700) | 5 | oldest version available, then each consolidated version: 15 June 2014 to 1 January 2022 |
| `731-bevolkerungsschutzgesetz-bl-bsg-bl/` | Gesetz über den Bevölkerungsschutz im Kanton Basel-Landschaft (SGS 731) | 3 | as enacted, then each consolidated version: 1 September 2004 to 1 July 2022 |
| `732-zivilschutzgesetz-bl-zsg-bl/` | Gesetz über den Zivilschutz im Kanton Basel-Landschaft (SGS 732) | 1 | as enacted, 1 July 2022 |
| `760-fwg/` | Gesetz über die Feuerwehr (SGS 760) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `761-brand-und-naturgefahrenpraventionsgesetz-bnpg/` | Gesetz über die Prävention vor Schäden durch Brand- und gravitative Naturgefahren (SGS 761) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `780-usg-bl/` | Umweltschutzgesetz Basel-Landschaft (SGS 780) | 3 | oldest version available, then each consolidated version: 1 October 2014 to 1 January 2023 |
| `782/` | Gesetz über den Gewässerschutz (SGS 782) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `788/` | Gesetz über den Schutz der Bevölkerung vor Atomkraftwerken (SGS 788) | 1 | as enacted, 1 May 1980 |
| `790/` | Gesetz über den Natur- und Landschaftsschutz (SGS 790) | 1 | one version (the oldest available), 1 January 2007 |
| `791-dhg/` | Gesetz über den Denkmal- und Heimatschutz (SGS 791) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 July 2018 |
| `793-archaologiegesetz-archg/` | Gesetz über den Schutz und die Erforschung von archäologischen Stätten und Objekten (SGS 793) | 1 | one version (the oldest available), 1 January 2007 |
| `813/` | Gesetz über die steuerbegünstigten Arbeitsbeschaffungsreserven (SGS 813) | 1 | one version (the oldest available), 1 January 2010 |
| `814-gsa/` | Gesetz über die Bekämpfung der Schwarzarbeit (SGS 814) | 2 | as enacted, then each consolidated version: 14 February 2014 to 1 July 2021 |
| `815-flamag/` | Gesetz über die flankierenden Massnahmen im Arbeitsmarkt (SGS 815) | 2 | as enacted, then each consolidated version: 14 February 2014 to 1 July 2021 |
| `831-eg-ahvg-ivg-bl/` | Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und die Invalidenversicherung (SGS 831) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2018 |
| `833/` | Ergänzungsleistungsgesetz zur AHV und IV (SGS 833) | 6 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `834-pensionskassengesetz/` | Gesetz über die berufliche Vorsorge durch die Basellandschaftliche Pensionskasse (SGS 834) | 2 | as enacted, then each consolidated version: 1 March 2004 to 1 January 2015 |
| `837-avlg/` | Gesetz über die Arbeitsvermittlung und die Arbeitslosenversicherung (SGS 837) | 1 | one version (the oldest available), 1 August 2008 |
| `838/` | Einführungsgesetz zum Bundesgesetz über die Familienzulagen (SGS 838) | 1 | as enacted, 1 January 2010 |
| `842-wohnbauforderungsgesetz-wbfg/` | Gesetz über die Wohnbauförderung (SGS 842) | 2 | as enacted, then each consolidated version: 1 January 1991 to 1 January 2024 |
| `844-mietzinsbeitragsgesetz-mbg/` | Gesetz über die Ausrichtung von Mietzinsbeiträgen (SGS 844) | 2 | as enacted, then each consolidated version: 1 January 1998 to 1 January 2024 |
| `850-sozialhilfegesetz-shg/` | Gesetz über die Sozial- und die Jugendhilfe (SGS 850) | 9 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `852/` | Gesetz über die familienergänzende Kinderbetreuung (SGS 852) | 1 | as enacted, 1 January 2017 |
| `853-behindertenhilfegesetz-bhg/` | Gesetz über die Behindertenhilfe (SGS 853) | 1 | as enacted, 1 January 2017 |
| `856-frauenhausgesetz/` | Gesetz über Beiträge an Frauenhäuser und ähnliche Institutionen (SGS 856) | 1 | one version (the oldest available), 1 January 2011 |
| `901-gesg/` | Gesundheitsgesetz (SGS 901) | 9 | oldest version available, then each consolidated version: 1 January 2014 to 1 April 2026 |
| `902/` | Kinder- und Jugendzahnpflegegesetz (SGS 902) | 1 | as enacted, 11 August 1997 |
| `904/` | Gesetz über das Begräbniswesen (SGS 904) | 1 | one version (the oldest available), 1 January 2009 |
| `905-kaatg/` | Kantonales Alkohol- und Tabakgesetz (SGS 905) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 February 2020 |
| `915-eg-bgfap/` | Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (SGS 915) | 1 | as enacted, 1 July 2024 |
| `930/` | Spitalgesetz (SGS 930) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `931-spivg/` | Spitalversorgungsgesetz (SGS 931) | 1 | as enacted, 1 January 2019 |
| `941-apg/` | Altersbetreuungs- und Pflegegesetz (SGS 941) | 3 | oldest version available, then each consolidated version: 1 October 2014 to 1 April 2023 |
| `106-11-vo-publg/` | Verordnung zum Publikationsgesetz (SGS 106.11) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2023 |
| `106-51/` | Regierungsratsverordnung über die Information (SGS 106.51) | 1 | one version (the oldest available), 1 March 1978 |
| `107-11/` | Kantonale Statistikverordnung (SGS 107.11) | 6 | as enacted, then each consolidated version: 1 September 2008 to 1 February 2026 |
| `108-11-gleichstellungsverordnung/` | Verordnung zum Einführungsgesetz zum Gleichstellungsgesetz (SGS 108.11) | 1 | one version (the oldest available), 1 January 2011 |
| `108-31/` | Verordnung über den Schutz der sexuellen Integrität am Arbeitsplatz (SGS 108.31) | 2 | oldest version available, then each consolidated version: 1 October 2009 to 1 October 2021 |
| `109-11-vo-brg-bl/` | Verordnung zum Behindertenrechtegesetz Basel-Landschaft (SGS 109.11) | 1 | as enacted, 1 January 2024 |
| `109-21-vo-behif/` | Verordnung über die Fachstelle Behindertenrechte (SGS 109.21) | 1 | as enacted, 1 June 2026 |
| `111-12-vkgwr/` | Verordnung über das kantonale Gebäude- und Wohnungsregister (SGS 111.12) | 3 | as enacted, then each consolidated version: 1 November 2021 to 1 January 2026 |
| `112-10/` | Verordnung zum Bundesgesetz über die Ausländerinnen und Ausländer (SGS 112.10) | 3 | as enacted, then each consolidated version: 1 July 2013 to 1 January 2025 |
| `112-11/` | Verordnung über die Gebühren im Ausländerrecht (SGS 112.11) | 4 | oldest version available, then each consolidated version: 1 March 2013 to 1 January 2026 |
| `113-11/` | Verordnung über das Ausstellen von Ausweisen für Schweizer Staatsangehörige (SGS 113.11) | 3 | oldest version available, then each consolidated version: 1 June 2013 to 9 November 2026 |
| `113-12/` | Verordnung betreffend die Regelung des Kleingrenzverkehrs zwischen Frankreich und dem Kanton Basel-Landschaft (SGS 113.12) | 2 | oldest version available, then each consolidated version: 1 June 2003 to 1 January 2015 |
| `113-13/` | Verordnung betreffend die Regelung des Kleingrenzverkehrs zwischen der Bundesrepublik Deutschland und dem Kanton Basel-Landschaft (SGS 113.13) | 3 | oldest version available, then each consolidated version: 1 July 2013 to 1 January 2025 |
| `113-14/` | Verordnung über den Heimatschein (SGS 113.14) | 1 | one version (the oldest available), 1 March 2013 |
| `114-11-integrationsverordnung/` | Verordnung zum Integrationsgesetz (SGS 114.11) | 4 | oldest version available, then each consolidated version: 1 March 2013 to 1 January 2025 |
| `116-11-vo-gfs/` | Verordnung zum Gesetz über die frühe Sprachförderung (SGS 116.11) | 1 | as enacted, 1 September 2024 |
| `120-11-vo-gpr/` | Verordnung zum Gesetz über die politischen Rechte (SGS 120.11) | 5 | oldest version available, then each consolidated version: 1 September 2009 to 1 January 2024 |
| `131-111-hausordnung/` | Reglement betreffend Verhalten auf der Zuschauertribüne des Landratssaales (SGS 131.111) | 1 | as enacted, 10 May 2018 |
| `140-10/` | Verordnung über die Verteilung der Direktionen (SGS 140.10) | 9 | as enacted, then each consolidated version: 1 July 2007 to 1 October 2026 |
| `140-11-regierungs-und-verwaltungsorganisationsverordnung-basel-landschaft-rvov-bl/` | Verordnung zum Regierungs- und Verwaltungsorganisationsgesetz Basel-Landschaft (SGS 140.11) | 11 | oldest version available, then each consolidated version: 1 August 2013 to 1 January 2026 |
| `140-12/` | Verordnung über die Generalsekretären-Konferenz (SGS 140.12) | 3 | as enacted, then each consolidated version: 1 January 2002 to 1 July 2022 |
| `140-13-gever-verordnung/` | Verordnung über die Aktenführung und die Geschäftsverwaltung (SGS 140.13) | 3 | as enacted, then each consolidated version: 1 January 2003 to 1 January 2024 |
| `140-14/` | Verordnung betreffend Pflichtenheft des Planungs- und Strategieausschusses (SGS 140.14) | 3 | oldest version available, then each consolidated version: 1 July 2013 to 1 January 2018 |
| `140-15-vppm/` | Verordnung zum Projekt- und Projektportfolio-Management (SGS 140.15) | 5 | as enacted, then each consolidated version: 1 November 2012 to 1 February 2024 |
| `140-16/` | Verordnung über das Risikomanagement (SGS 140.16) | 2 | as enacted, then each consolidated version: 1 February 2014 to 1 January 2018 |
| `140-18-versicherungsverordnung-bl/` | Verordnung über das Versicherungswesen (SGS 140.18) | 1 | as enacted, 1 January 2021 |
| `140-21/` | Verordnung über die Zuständigkeitsordnung für die Unterzeichnung von Anweisungen (SGS 140.21) | 2 | oldest version available, then each consolidated version: 1 March 2013 to 1 January 2018 |
| `140-25/` | Verordnung über die Zuständigkeit für die Genehmigung von Gemeindenormen (SGS 140.25) | 7 | oldest version available, then each consolidated version: 1 September 2007 to 1 June 2026 |
| `140-31/` | Verordnung über das Mitberichtsverfahren und das Vernehmlassungsverfahren (SGS 140.31) | 5 | oldest version available, then each consolidated version: 1 September 2014 to 1 March 2026 |
| `140-32/` | Verordnung über die Anhörung der Gemeinden (SGS 140.32) | 2 | oldest version available, then each consolidated version: 1 July 2006 to 1 January 2018 |
| `140-41-kommissionsverordnung-kov/` | Verordnung über die regierungsrätlichen Kommissionen (SGS 140.41) | 2 | as enacted, then each consolidated version: 1 May 2015 to 1 September 2017 |
| `140-50-vodit/` | Verordnung Digitale Transformation (SGS 140.50) | 2 | as enacted, then each consolidated version: 1 February 2024 to 14 March 2024 |
| `140-51-informatikverordnung/` | Verordnung über die Informatik (SGS 140.51) | 2 | as enacted, then each consolidated version: 1 January 2003 to 1 March 2017 |
| `140-52/` | Verordnung über das IT-Forum Kanton-Gemeinden (SGS 140.52) | 1 | as enacted, 1 January 2019 |
| `140-61/` | Verordnung über das Übersetzungswesen (SGS 140.61) | 2 | as enacted, then each consolidated version: 1 June 2013 to 1 January 2018 |
| `140-91/` | Verordnung über die Administrativuntersuchung (SGS 140.91) | 1 | as enacted, 1 January 2018 |
| `140-551/` | Benutzungsreglement Informatikmittel (SGS 140.551) | 4 | as enacted, then each consolidated version: 1 January 2003 to 1 July 2022 |
| `140-611/` | Reglement zur Verordnung über das Übersetzungswesen (SGS 140.611) | 3 | as enacted, then each consolidated version: 1 January 2015 to 1 March 2021 |
| `141-20/` | Verordnung für die Bewertungskommission (SGS 141.20) | 2 | oldest version available, then each consolidated version: 1 October 2010 to 1 January 2021 |
| `142-53/` | Verordnung über die Fachstelle und die Kommission für Gleichstellung von Frau und Mann (SGS 142.53) | 2 | as enacted, then each consolidated version: 1 July 2000 to 1 May 2025 |
| `142-71/` | Verordnung über die Spitalseelsorge der Landeskirchen (SGS 142.71) | 1 | one version (the oldest available), 1 April 2012 |
| `142-110-rdo-fkd/` | Reglement zur Dienstordnung der Finanz- und Kirchendirektion (SGS 142.110) | 2 | as enacted, then each consolidated version: 1 June 2022 to 1 September 2022 |
| `142-111/` | Reglement über die Zuständigkeiten für Ausgabenbewilligungen in der Finanz- und Kirchendirektion (SGS 142.111) | 6 | as enacted, then each consolidated version: 1 January 2018 to 1 February 2025 |
| `143-49/` | Verordnung über das Forum Gesundheitsförderung Basel-Landschaft (SGS 143.49) | 1 | as enacted, 1 September 1990 |
| `143-51/` | Verordnung über die Gebühren der Volkswirtschafts- und Gesundheitsdirektion im Gesundheitsbereich (SGS 143.51) | 4 | as enacted, then each consolidated version: 1 April 2009 to 1 October 2019 |
| `143-61/` | Verordnung über die Kommission Naturgefahren (SGS 143.61) | 1 | as enacted, 1 January 2012 |
| `143-81/` | Verordnung über Arbeitssicherheit und Gesundheitsschutz (SGS 143.81) | 1 | as enacted, 1 January 2003 |
| `143-120-rdo-vgd/` | Reglement zur Dienstordnung der Volkswirtschafts- und Gesundheitsdirektion (SGS 143.120) | 4 | as enacted, then each consolidated version: 1 March 2019 to 15 April 2025 |
| `143-121/` | Reglement über die Zuständigkeiten für Ausgabenbewilligungen in der Volkswirtschafts- und Gesundheitsdirektion (SGS 143.121) | 7 | as enacted, then each consolidated version: 1 January 2018 to 15 April 2025 |
| `144-28/` | Verordnung über das Parkieren auf Staatsareal (SGS 144.28) | 2 | as enacted, then each consolidated version: 1 June 2012 to 1 January 2020 |
| `144-33/` | Verordnung über die Kommission zur Beurteilung von Risikoermittlungen (SGS 144.33) | 2 | as enacted, then each consolidated version: 1 August 1990 to 1 May 2019 |
| `144-121/` | Reglement über die Zuständigkeiten für Ausgabenbewilligungen in der Bau- und Umweltschutzdirektion (SGS 144.121) | 3 | as enacted, then each consolidated version: 1 January 2018 to 1 July 2025 |
| `144-271/` | Verordnung über die Gebühren zum Vollzug der Störfallverordnung, der Gefahrgutbeauftragtenverordnung, der Einschliessungsverordnung und der Freisetzungsverordnung (SGS 144.271) | 3 | oldest version available, then each consolidated version: 1 October 2009 to 1 May 2019 |
| `144-611/` | Verordnung über die Gebühren zum Vollzug der Luftreinhalte-Verordnung (LRV) und der Verordnung über den Schutz vor nichtionisierender Strahlung (NISV) (SGS 144.611) | 2 | oldest version available, then each consolidated version: 1 July 2012 to 1 January 2026 |
| `145-35/` | Verordnung über die Gebühren der Polizei Basel-Landschaft (SGS 145.35) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 December 2015 |
| `145-36/` | Verordnung über die Gebühren und besonderen Abgaben der Motorfahrzeugkontrolle (SGS 145.36) | 5 | oldest version available, then each consolidated version: 1 May 2013 to 1 July 2026 |
| `145-38/` | Verordnung über die Zuteilung von Kontrollschildern (SGS 145.38) | 1 | one version (the oldest available), 1 May 2013 |
| `145-52/` | Verordnung über die Gebühren des Amtes für Militär und Bevölkerungsschutz betreffend Schutzbauten (SGS 145.52) | 1 | as enacted, 1 October 2012 |
| `145-91-geonav/` | Verordnung über geografische Namen und Gebäudeadressen (SGS 145.91) | 2 | as enacted, then each consolidated version: 1 April 2011 to 1 November 2021 |
| `145-111/` | Reglement über die Zuständigkeiten für Ausgabenbewilligungen in der Sicherheitsdirektion (SGS 145.111) | 5 | as enacted, then each consolidated version: 1 January 2018 to 1 March 2025 |
| `146-96/` | Verordnung über den Jugendrat Baselland (SGS 146.96) | 1 | as enacted, 1 April 1998 |
| `146-110-reglement-bksd/` | Reglement zur Dienstordnung der Bildungs-, Kultur- und Sportdirektion (SGS 146.110) | 1 | as enacted, 1 January 2022 |
| `146-111/` | Reglement über die Zuständigkeiten für Ausgabenbewilligungen in der Bildungs-, Kultur- und Sportdirektion (SGS 146.111) | 4 | as enacted, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `146-551-gebuhrenverordnung-bmh/` | Verordnung über die Gebühren der Hauptabteilung Berufsbildung der Dienststelle Berufsbildung, Mittelschulen und Hochschulen (SGS 146.551) | 4 | as enacted, then each consolidated version: 1 April 2010 to 1 January 2026 |
| `147-13-vrg/` | Verordnung über die Raumnutzung im Regierungsgebäude (SGS 147.13) | 3 | as enacted, then each consolidated version: 1 January 1989 to 1 July 2025 |
| `147-111/` | Reglement über die Zuständigkeiten für Ausgabenbewilligungen in der Landeskanzlei (SGS 147.111) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 October 2024 |
| `150-11-personalverordnung/` | Verordnung zum Personalgesetz (SGS 150.11) | 14 | oldest version available, then each consolidated version: 1 January 2013 to 1 April 2026 |
| `150-12-personalorganisationsverordnung/` | Verordnung über die Personalorganisation des Kantons Basel-Landschaft (SGS 150.12) | 2 | as enacted, then each consolidated version: 1 July 2022 to 1 July 2023 |
| `150-21/` | Verordnung über den Umgang mit Personaldaten (SGS 150.21) | 2 | oldest version available, then each consolidated version: 1 May 2014 to 16 November 2015 |
| `151-11/` | Verordnung über den Sozialplan (SGS 151.11) | 3 | oldest version available, then each consolidated version: 1 December 2013 to 1 December 2024 |
| `153-11/` | Verordnung zur Arbeitszeit (SGS 153.11) | 12 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `153-12/` | Verordnung über die Lohnansprüche der Mitarbeiterinnen und Mitarbeiter bei Arbeitsunfähigkeit infolge Krankheit oder Unfalls (SGS 153.12) | 4 | oldest version available, then each consolidated version: 1 April 2013 to 1 June 2024 |
| `153-13/` | Verordnung über den Elternurlaub (SGS 153.13) | 4 | as enacted, then each consolidated version: 1 May 2011 to 1 January 2022 |
| `153-15/` | Verordnung über den Auslagenersatz (SGS 153.15) | 2 | oldest version available, then each consolidated version: 1 July 2014 to 1 August 2024 |
| `153-17/` | Verordnung über die Lohnzahlung beim Einsatz im Rahmen von öffentlichen Dienstleistungen (Öffentlichkeitsdiensten) (SGS 153.17) | 2 | oldest version available, then each consolidated version: 1 March 2007 to 1 January 2021 |
| `153-18/` | Verordnung über die Vergütung von Mandaten an unselbständig Erwerbende (SGS 153.18) | 9 | oldest version available, then each consolidated version: 1 January 2014 to 1 August 2026 |
| `155-11/` | Verordnung über die Vergütungen während der Ausbildung (SGS 155.11) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 8 September 2023 |
| `156-12/` | Verordnung über die Vergütungen für den Unterricht in den Weiterbildungskursen der gewerblich-industriellen Berufsschulen (SGS 156.12) | 1 | one version (the oldest available), 1 June 2013 |
| `156-95/` | Verordnung über die Lehrerinnen- und Lehrerfunktionen (SGS 156.95) | 2 | oldest version available, then each consolidated version: 23 January 2012 to 1 January 2021 |
| `157-22/` | Verordnung über die Entschädigungen für Verpflegungen in den staatlichen Anstalten und Betrieben (SGS 157.22) | 1 | one version (the oldest available), 1 January 1997 |
| `157-24/` | Verordnung über die Verwendung von Dienstfahrzeugen der kantonalen Verwaltung (SGS 157.24) | 1 | as enacted, 1 April 2004 |
| `158-12/` | Verordnung über die Vergütungen für die Inhaberinnen und Inhaber von Nebenämtern und für die Mitglieder von kantonalen Arbeitsgruppen (SGS 158.12) | 8 | oldest version available, then each consolidated version: 1 June 2013 to 1 January 2026 |
| `162-11-informations-und-datenschutzverordnung-idv/` | Verordnung zum Gesetz über die Information und den Datenschutz (SGS 162.11) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `162-51-vis/` | Verordnung über die Informationssicherheit (SGS 162.51) | 1 | one version (the oldest available), 1 January 2013 |
| `164-11-e-government-verordnung-vo-e-govg/` | Verordnung zum Gesetz über die elektronische Geschäftsabwicklung und Kommunikation (SGS 164.11) | 4 | as enacted, then each consolidated version: 1 January 2022 to 1 June 2026 |
| `170-31-gebuhrentarif-gebt/` | Verordnung über die Gebühren der Gerichte (SGS 170.31) | 4 | oldest version available, then each consolidated version: 1 November 2012 to 1 January 2021 |
| `170-111/` | Reglement über die Gerichtsverwaltung (SGS 170.111) | 2 | as enacted, then each consolidated version: 1 July 2014 to 1 June 2019 |
| `175-11-vo-vwvg-bl/` | Verordnung zum Verwaltungsverfahrensgesetz Basel-Landschaft (SGS 175.11) | 5 | oldest version available, then each consolidated version: 1 March 2013 to 1 February 2026 |
| `175-12/` | Verordnung über die Veröffentlichung von Verwaltungsentscheiden (SGS 175.12) | 1 | as enacted, 1 January 2008 |
| `175-13/` | Verordnung über Abschluss und Vollzug privatrechtlicher Verträge (SGS 175.13) | 5 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `175-14-vevv/` | Verordnung über den elektronischen Verkehr im Verwaltungsverfahren (SGS 175.14) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 June 2026 |
| `178-11/` | Verordnung über die Gebühren zum Anwaltsgesetz (SGS 178.11) | 2 | oldest version available, then each consolidated version: 1 August 2009 to 1 April 2017 |
| `178-111-anwaltsprufungsreglement/` | Reglement über die Anwaltsprüfung und die Erteilung des Anwaltspatentes (SGS 178.111) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2023 |
| `180-10-gemeinderechnungsverordnung-grv/` | Verordnung über die Rechnungslegung der Einwohnergemeinden (SGS 180.10) | 8 | oldest version available, then each consolidated version: 1 July 2014 to 1 November 2025 |
| `180-13-burgergemeinderechnungsverordnung/` | Verordnung über die Rechnungslegung der Bürgergemeinden und der Burgergemeinden (SGS 180.13) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `180-14/` | Verordnung über das Mutations- und Meldewesen (SGS 180.14) | 1 | one version (the oldest available), 1 January 2007 |
| `185-11-fav/` | Finanzausgleichsverordnung (SGS 185.11) | 10 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `191-21/` | Verordnung über die Rechnungslegung der Stiftung Kirchengut (SGS 191.21) | 3 | as enacted, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `191-211/` | Reglement über die Gebäude und Areale der Stiftung Kirchengut (SGS 191.211) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2020 |
| `191-212/` | Reglement über die Rückgabe von Gebäuden und Arealen an die Stiftung Kirchengut (SGS 191.212) | 1 | as enacted, 1 January 2020 |
| `211-12/` | Verordnung betreffend Kontrolle der Buchhaltung der Berufsbeistandschaften (SGS 211.12) | 1 | as enacted, 1 January 2013 |
| `211-19-kantonale-stiftungsaufsichtsverordnung/` | Verordnung über die kantonalen Aufgaben bei der Aufsicht über die Stiftungen der Gemeinden (SGS 211.19) | 1 | as enacted, 1 April 2022 |
| `211-53-kvav/` | Kantonale Verordnung über die amtliche Vermessung (SGS 211.53) | 3 | as enacted, then each consolidated version: 1 July 2012 to 1 November 2021 |
| `211-55/` | Verordnung über die Gebühren für die Nachführungsarbeiten in der amtlichen Vermessung (SGS 211.55) | 7 | oldest version available, then each consolidated version: 1 April 2011 to 1 January 2026 |
| `211-57-geogv/` | Gebührenverordnung für Geobasisdaten und Geodienste (SGS 211.57) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2015 |
| `211-58-kgeoiv/` | Kantonale Verordnung über Geoinformation (SGS 211.58) | 7 | oldest version available, then each consolidated version: 1 April 2010 to 1 June 2025 |
| `211-59-korebkv/` | Kantonale Verordnung über den Kataster der öffentlich-rechtlichen Eigentumsbeschränkungen (SGS 211.59) | 3 | as enacted, then each consolidated version: 1 January 2018 to 1 March 2022 |
| `211-61-gbv-bl/` | Grundbuchverordnung Basel-Landschaft (SGS 211.61) | 7 | oldest version available, then each consolidated version: 1 November 2012 to 1 January 2026 |
| `211-62/` | Verordnung über die Veröffentlichung von Eigentumsübertragungen (SGS 211.62) | 1 | one version (the oldest available), 1 August 2007 |
| `211-71-gebv/` | Verordnung über die Gebühren zum Zivilrecht (SGS 211.71) | 1 | one version (the oldest available), 1 January 2013 |
| `211-72/` | Verordnung über die Hinterlegung von Vorsorgeaufträgen (SGS 211.72) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 October 2020 |
| `211-91-vo-fuv/` | Verordnung über das Fundwesen und das Verwertungswesen (SGS 211.91) | 3 | oldest version available, then each consolidated version: 1 October 2013 to 1 October 2023 |
| `212-34/` | Verordnung über den Normalarbeitsvertrag für Hauspersonal (SGS 212.34) | 4 | oldest version available, then each consolidated version: 1 March 2013 to 1 January 2025 |
| `216-11/` | Verordnung zum Bundesgesetz über den Konsumkredit (SGS 216.11) | 1 | one version (the oldest available), 1 March 2013 |
| `217-11-notv/` | Notariatsverordnung (SGS 217.11) | 3 | as enacted, then each consolidated version: 1 July 2012 to 1 October 2023 |
| `217-13-notgebv/` | Verordnung über die Notariatsgebühren (SGS 217.13) | 1 | as enacted, 1 November 2012 |
| `223-11-mietverordnung/` | Verordnung zum Gesetz über die Behörden und das Verfahren bei Streitigkeiten aus Miete und Pacht von unbeweglichen Sachen sowie über die Allgemeinverbindlicherklärung von Rahmenmietverträgen (SGS 223.11) | 1 | one version (the oldest available), 1 January 2011 |
| `224-11/` | Verordnung betreffend Gebühren für die Vollstreckung von Entscheiden in Zivilsachen (SGS 224.11) | 1 | one version (the oldest available), 1 January 2011 |
| `231-31-bg-kke/` | Verordnung zum Bundesgesetz über internationale Kindesentführung und die Haager Übereinkommen zum Schutz von Kindern und Erwachsenen (SGS 231.31) | 1 | as enacted, 1 July 2009 |
| `232-11/` | Verordnung über die elektronische Überwachung zum Schutz gewaltbetroffener Personen (SGS 232.11) | 1 | as enacted, 1 January 2022 |
| `233-12/` | Verordnung über den Online-Zugriff auf die Protokolle und Register der Betreibungs- und Konkursämter (SGS 233.12) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `250-13/` | Verordnung über die Verfahrenskosten der Staatsanwaltschaft (SGS 250.13) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 July 2023 |
| `252-11/` | Verordnung zum Bundesgesetz über die Hilfe an Opfer von Straftaten (SGS 252.11) | 1 | one version (the oldest available), 1 January 2012 |
| `261-31/` | Verordnung über die Kosten des Straf- und Massnahmenvollzugs sowie von Untersuchungsgefangenen (SGS 261.31) | 1 | one version (the oldest available), 1 January 2014 |
| `261-41/` | Verordnung über den Straf- und Massnahmevollzug (SGS 261.41) | 1 | one version (the oldest available), 1 January 2012 |
| `261-42/` | Verordnung über den Vollzug von Freiheitsstrafen in der Form des Electronic Monitoring (SGS 261.42) | 1 | one version (the oldest available), 1 March 2013 |
| `261-51/` | Verordnung über die Bewährungshilfe Basel-Landschaft (SGS 261.51) | 1 | as enacted, 1 April 2013 |
| `261-61/` | Verordnung über die Gefängnisse und Polizeizellen (SGS 261.61) | 2 | oldest version available, then each consolidated version: 1 March 2013 to 1 April 2021 |
| `266-11-arxhofverordnung/` | Verordnung über das Massnahmenzentrum für junge Erwachsene Arxhof (SGS 266.11) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `310-11-vo-fhg/` | Finanzhaushaltsverordnung (SGS 310.11) | 15 | oldest version available, then each consolidated version: 1 March 2013 to 1 January 2026 |
| `310-12/` | Verordnung über die Vermögens- und Schuldenbewirtschaftung (SGS 310.12) | 1 | as enacted, 1 January 2016 |
| `314-11-pcgv/` | Verordnung zum Gesetz über die Beteiligungen (Public Corporate Governance) (SGS 314.11) | 3 | as enacted, then each consolidated version: 1 January 2018 to 1 November 2022 |
| `331-11/` | Verordnung zum Steuergesetz (SGS 331.11) | 16 | oldest version available, then each consolidated version: 1 July 2014 to 1 January 2026 |
| `331-13/` | Regierungsratsverordnung über das Verfahren für die Katasterneuschätzung 1983 (SGS 331.13) | 1 | as enacted, 1 February 1982 |
| `331-14/` | Verordnung über die Nachbesteuerung von Bausparkapital (SGS 331.14) | 1 | as enacted, 1 January 2013 |
| `331-16/` | Verordnung zur Quellensteuer (SGS 331.16) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `331-17/` | Verordnung über die Besteuerung der Liquidationsgewinne bei definitiver Aufgabe der selbständigen Erwerbstätigkeit (SGS 331.17) | 1 | as enacted, 1 January 2011 |
| `331-18/` | Verordnung über die Erteilung von Steuerauskünften mittels elektronischem Abrufverfahren (SGS 331.18) | 1 | as enacted, 1 January 2014 |
| `331-21/` | Verordnung über die elektronische Einreichung der Steuererklärung für natürliche Personen (SGS 331.21) | 1 | as enacted, 1 January 2023 |
| `334-11/` | Verordnung zum Gesetz über die Erbschafts- und die Schenkungssteuer (SGS 334.11) | 1 | one version (the oldest available), 1 May 2014 |
| `336-11/` | Verordnung über die Wehrpflichtersatzabgabe (SGS 336.11) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2025 |
| `336-21/` | Vollzugsverordnung zum Bundesgesetz über die direkte Bundessteuer (SGS 336.21) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2016 |
| `341-11/` | Verordnung zum Gesetz über die Motorfahrzeugsteuer (SGS 341.11) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `342-12/` | Verordnung über das Halten potenziell gefährlicher Hunde (SGS 342.12) | 1 | one version (the oldest available), 1 February 2013 |
| `350-11-gvv-bl/` | Verordnung zum Gebäudeversicherungsgesetz Basel-Landschaft (SGS 350.11) | 4 | oldest version available, then each consolidated version: 1 April 2011 to 1 May 2025 |
| `350-111-gebaudeversicherungsreglement-gebvr/` | Reglement über die obligatorische Versicherung der Gebäude (SGS 350.111) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `350-112-grundstuckversicherungsreglement-gstvr/` | Reglement über die obligatorische Versicherung der Grundstücke (SGS 350.112) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `350-113-zusatzversicherungsreglement-zvr/` | Reglement über die freiwilligen Zusatzversicherungen (SGS 350.113) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `350-114-tarifreglement-tr/` | Reglement über die Tarife der Basellandschaftlichen Gebäudeversicherung (SGS 350.114) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `360-11-sbv/` | Staatsbeitragsverordnung (SGS 360.11) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 February 2022 |
| `362-12-pramienverbilligungsverordnung-pvv/` | Verordnung über die Prämienverbilligung in der Krankenpflegeversicherung (SGS 362.12) | 12 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `362-13/` | Verordnung über die Übernahme der Verlustscheine in der obligatorischen Krankenpflegeversicherung (SGS 362.13) | 1 | as enacted, 1 January 2012 |
| `362-14/` | Verordnung über die Finanzierung von Pflegeleistungen (SGS 362.14) | 13 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `365-11/` | Verordnung zum Gesetz über Ausbildungsbeiträge (SGS 365.11) | 2 | oldest version available, then each consolidated version: 1 August 2014 to 1 July 2021 |
| `365-21/` | Verordnung über die Handschin-Stiftung (SGS 365.21) | 3 | oldest version available, then each consolidated version: 7 September 1999 to 1 January 2025 |
| `365-31/` | Reglement für die Verwaltung der Wehrli-Stiftung des Birsecks (SGS 365.31) | 3 | as enacted, then each consolidated version: 9 May 1978 to 16 October 2018 |
| `366-14/` | Verordnung über die Benutzung des Künstlerateliers des Kantons Basel-Landschaft in der Cité Internationale des Arts in Paris (SGS 366.14) | 1 | as enacted, 1 July 1987 |
| `367-11/` | Verordnung über Beiträge an Schiessanlagen (SGS 367.11) | 1 | one version (the oldest available), 1 March 2013 |
| `369-11/` | Verordnung über den Swisslos Sportfonds (SGS 369.11) | 7 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2024 |
| `369-12-sportpreisverordnung/` | Verordnung über den Baselbieter Sportpreis und die Anerkennungs- und Förderpreise für den Leistungs-, Breiten-, Gesundheits- und Vereinssport (SGS 369.12) | 1 | one version (the oldest available), 1 April 2004 |
| `369-14/` | Verordnung über den Preis für Baselbieter Freiwilligenarbeit im Sozialbereich (SGS 369.14) | 2 | oldest version available, then each consolidated version: 1 May 2014 to 1 October 2023 |
| `371-11/` | Verordnung zum Kantonalbankgesetz (SGS 371.11) | 2 | oldest version available, then each consolidated version: 1 December 2011 to 1 December 2015 |
| `400-11-rbv/` | Verordnung zum Raumplanungs- und Baugesetz (SGS 400.11) | 14 | oldest version available, then each consolidated version: 15 July 2014 to 1 April 2026 |
| `406-12/` | Verordnung über Fuss- und Wanderwege (SGS 406.12) | 1 | as enacted, 1 November 2010 |
| `414-11/` | Regierungsratsverordnung über einführende Massnahmen über die Raumplanung (SGS 414.11) | 1 | as enacted, 1 January 1980 |
| `420-11-vo-eg-ivob/` | Verordnung zum Einführungsgesetz zur Interkantonalen Vereinbarung über das öffentliche Beschaffungswesen (SGS 420.11) | 4 | oldest version available, then each consolidated version: 1 August 2012 to 1 January 2026 |
| `421-14/` | Verordnung über den Feuerschutz in den Tankanlagen der Rheinhäfen des Kantons Basel-Landschaft (SGS 421.14) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 March 2022 |
| `421-15/` | Verordnung über den Zuständigkeitsbereich der Hafenpolizei im Ordnungsbussenverfahren im Strassenverkehr (SGS 421.15) | 1 | as enacted, 1 February 1995 |
| `421-16/` | Verordnung über Entwässerungs- und Abwasseranlagen des Rheinhafens Au, Muttenz (SGS 421.16) | 1 | as enacted, 22 January 2003 |
| `425-11/` | Verordnung über die Gebühren der Baubewilligungsbehörden (SGS 425.11) | 1 | as enacted, 1 May 2014 |
| `427-11/` | Verordnung über Bewilligungs- und Kontrollgebühren im Abfallwesen (SGS 427.11) | 1 | as enacted, 1 July 2007 |
| `430-11/` | Verordnung über die Gebühren zum Strassengesetz (SGS 430.11) | 1 | one version (the oldest available), 1 January 2010 |
| `435/` | Verordnung über die Offenhaltung der Versorgungsrouten für Ausnahmetransporte (SGS 435) | 1 | one version (the oldest available), 1 January 2008 |
| `445-11-wbauv/` | Wasserbauverordnung (SGS 445.11) | 3 | as enacted, then each consolidated version: 1 January 1991 to 1 January 2023 |
| `455-11/` | Verordnung über die Wasserversorgung sowie die Nutzung und den Schutz des Grundwassers (SGS 455.11) | 3 | as enacted, then each consolidated version: 1 February 1998 to 1 April 2022 |
| `481-11/` | Verordnung zum Strassenverkehrsgesetz Basel-Landschaft (SGS 481.11) | 3 | as enacted, then each consolidated version: 1 September 2012 to 1 May 2023 |
| `481-12/` | Verordnung über Reklamen (SGS 481.12) | 2 | as enacted, then each consolidated version: 1 January 1997 to 1 July 2015 |
| `481-13/` | Verordnung über den Online-Zugriff auf die Fahrzeugzulassungsdaten der Motorfahrzeugkontrolle (SGS 481.13) | 4 | as enacted, then each consolidated version: 1 March 2014 to 1 April 2026 |
| `481-16/` | Verordnung über Betriebswegweiser, andere besondere Wegweiser und Hinweissignale (SGS 481.16) | 1 | one version (the oldest available), 1 July 2014 |
| `482-11-vo-fahrdienstgesetz/` | Verordnung zum Gesetz über Beiträge an Fahrdienste für mobilitätseingeschränkte Personen (SGS 482.11) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 October 2026 |
| `487-2/` | Verordnung über das Wasserskifahren unterhalb Rheinfelden (SGS 487.2) | 1 | as enacted, 1 October 1977 |
| `487-11/` | Verordnung über die Kleinschifffahrt (SGS 487.11) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2015 |
| `489-11-lkv/` | Verordnung über den Leitungskataster (SGS 489.11) | 1 | as enacted, 1 July 2010 |
| `490-10-enfv-bl/` | Energieförderverordnung (SGS 490.10) | 5 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `490-11-env-bl/` | Energieverordnung (SGS 490.11) | 8 | oldest version available, then each consolidated version: 23 January 2013 to 1 March 2025 |
| `490-20/` | Verordnung über Rohrleitungsanlagen mit einem Betriebsdruck bis 5 bar (SGS 490.20) | 1 | as enacted, 1 January 2005 |
| `501-01/` | Verordnung zur Regelung der überdirektionalen Zusammenarbeit im Bereich der Standortförderung (SGS 501.01) | 1 | as enacted, 1 June 2016 |
| `505-11-hartefallverordnung-bl/` | Verordnung über Härtefallmassnahmen für Unternehmen im Zusammenhang mit Covid-19 (SGS 505.11) | 4 | as enacted, then each consolidated version: 29 January 2021 to 1 April 2021 |
| `505-12-schutzschirmverordnung-bl/` | Verordnung über Massnahmen für Publikumsanlässe im Zusammenhang mit Covid-19 (SGS 505.12) | 2 | as enacted, then each consolidated version: 1 July 2021 to 1 May 2022 |
| `505-13-hartefallverordnung-2022-bl/` | Verordnung über Härtefallmassnahmen für Unternehmen im Zusammenhang mit Covid-19 im Jahr 2022 (SGS 505.13) | 2 | as enacted, then each consolidated version: 1 March 2022 to 22 March 2022 |
| `510-12/` | Verordnung über die Direktzahlungen, die Betriebsanerkennungen, die Betriebshelfer- und Landdienste (SGS 510.12) | 1 | one version (the oldest available), 1 January 2014 |
| `511-11/` | Verordnung zum Bundesgesetz vom 4. Oktober 1991 über das bäuerliche Bodenrecht (BGBB) (SGS 511.11) | 1 | one version (the oldest available), 1 August 2010 |
| `513-11/` | Verordnung über die landwirtschaftliche Pacht (SGS 513.11) | 1 | as enacted, 1 July 1998 |
| `514-11/` | Verordnung über die Investitionshilfen in der Landwirtschaft (SGS 514.11) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 February 2025 |
| `515-11-bodenverbesserungsverordnung-bov/` | Verordnung über die Durchführung von Bodenverbesserungen (SGS 515.11) | 1 | one version (the oldest available), 1 January 2014 |
| `516-11/` | Verordnung über die Tierzucht und den Viehabsatz (SGS 516.11) | 1 | one version (the oldest available), 1 August 2011 |
| `516-31/` | Verordnung über den Pflanzenbau (SGS 516.31) | 3 | oldest version available, then each consolidated version: 1 July 2014 to 1 May 2025 |
| `520-11-wildtier-und-jagdverordnung-wjv/` | Verordnung über den Schutz der wildlebenden Säugetiere und Vögel sowie deren Lebensräume und die Jagd (SGS 520.11) | 4 | oldest version available, then each consolidated version: 1 May 2014 to 1 November 2026 |
| `521-11/` | Verordnung über die Jagdprüfung (SGS 521.11) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 April 2020 |
| `530-11/` | Verordnung zum Fischereigesetz (SGS 530.11) | 1 | one version (the oldest available), 1 April 2011 |
| `540-11/` | Verordnung zum Gastgewerbegesetz (SGS 540.11) | 1 | one version (the oldest available), 1 March 2013 |
| `540-12/` | Verordnung über den Fähigkeitsausweis und gleichwertige Nachweise zur Führung eines gastwirtschaftlichen Betriebes (SGS 540.12) | 3 | oldest version available, then each consolidated version: 1 March 2013 to 1 December 2021 |
| `541-11/` | Verordnung zum Gesetz über die Reduktion der Regelungsdichte und den Abbau der administrativen Belastung für die kleinen und mittleren Unternehmen (KMU) (SGS 541.11) | 1 | as enacted, 1 October 2006 |
| `542-31/` | Verordnung zum Bundesgesetz über das Gewerbe der Reisenden (SGS 542.31) | 2 | as enacted, then each consolidated version: 1 January 2003 to 1 July 2025 |
| `543-11-vo-eg-bgs/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über Geldspiele (SGS 543.11) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `543-12/` | Verordnung über den Swisslos-Fonds (SGS 543.12) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 August 2025 |
| `543-42/` | Verordnung über den Swisslos-Spielsucht-Fonds (SGS 543.42) | 1 | as enacted, 1 January 2021 |
| `545-11/` | Verordnung zum Gesetz betreffend öffentliche Filmvorführungen und Abgabe von elektronischen Trägermedien (SGS 545.11) | 1 | as enacted, 1 January 2013 |
| `546-11-vgtap/` | Verordnung zum Gesetz über den Betrieb von Taxis und anderen gewerbsmässigen Personentransporten (SGS 546.11) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 October 2020 |
| `547-11-ruhetagsverordnung-rtv/` | Verordnung über die öffentlichen Ruhetage und den Sonntagsverkauf (SGS 547.11) | 2 | oldest version available, then each consolidated version: 1 March 2012 to 1 December 2019 |
| `548-11-gasttaxenverordnung/` | Verordnung zum Gesetz über die Erhebung einer Gasttaxe (SGS 548.11) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 November 2019 |
| `564-1/` | Verordnung über den Vollzug der eidgenössischen Preisvorschriften (SGS 564.1) | 1 | one version (the oldest available), 1 January 2012 |
| `570-11-kwav/` | Kantonale Waldverordnung (SGS 570.11) | 5 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2018 |
| `570-12/` | Verordnung über die Investitionskredite in der Forstwirtschaft (SGS 570.12) | 1 | as enacted, 1 December 1999 |
| `600-11-kulturforderverordnung-kfv/` | Verordnung über die Kulturförderung (SGS 600.11) | 4 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `615-11/` | Verordnung über die Vergütung und Gebühren des kantonalen Veterinärdienstes (SGS 615.11) | 1 | one version (the oldest available), 1 June 2013 |
| `615-12-tierschutzverordnung/` | Verordnung über den Tierschutz (SGS 615.12) | 1 | one version (the oldest available), 1 July 2010 |
| `630-11/` | Verordnung über die Sportförderung (SGS 630.11) | 2 | as enacted, then each consolidated version: 1 June 2006 to 1 March 2021 |
| `640-21-laufbahnverordnung/` | Verordnung über die schulische Laufbahn (SGS 640.21) | 19 | oldest version available, then each consolidated version: 1 August 2014 to 1 August 2026 |
| `640-31/` | Verordnung über den Erwerb und die Entflechtung der Eigentumsverhältnisse von Schulbauten (SGS 640.31) | 1 | as enacted, 1 August 2011 |
| `640-32/` | Verordnung über die Miete von Schulanlagen (SGS 640.32) | 1 | as enacted, 1 August 2011 |
| `640-33-vo-sal/` | Verordnung über den Betrieb der Schuladministrationslösung SAL (SGS 640.33) | 3 | as enacted, then each consolidated version: 1 July 2021 to 1 January 2025 |
| `640-41/` | Verordnung für die Musikschule (SGS 640.41) | 3 | oldest version available, then each consolidated version: 1 August 2014 to 1 August 2024 |
| `640-43/` | Verordnung über die Privatschulen und die private Schulung (SGS 640.43) | 4 | as enacted, then each consolidated version: 1 August 2018 to 1 August 2026 |
| `640-45/` | Verordnung über die Beiträge an die Kosten des Privatschulbesuchs (SGS 640.45) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 August 2025 |
| `640-51/` | Verordnung über die spezielle Förderung von sportbegabten Jugendlichen (SGS 640.51) | 6 | oldest version available, then each consolidated version: 1 November 2008 to 1 August 2024 |
| `640-71-verordnung-sonderpadagogik-vo-sopa/` | Verordnung über die Spezielle Förderung, die Sonderschulung und die heilpädagogische Früherziehung (SGS 640.71) | 8 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2026 |
| `640-211/` | Reglement über die Leistungsbeurteilung an der Volksschule des Kantons Basel-Landschaft (SGS 640.211) | 3 | as enacted, then each consolidated version: 1 August 2022 to 1 August 2025 |
| `640-211a/` | Reglement betreffend Durchführung der Leistungstests (Check P3, P5, S2 und S3) für die Volksschule Basel-Landschaft (SGS 640.211a) | 2 | as enacted, then each consolidated version: 1 August 2016 to 1 August 2025 |
| `640-213/` | Reglement über die Leistungsbeurteilung an den basellandschaftlichen Gymnasien (SGS 640.213) | 6 | as enacted, then each consolidated version: 15 August 2005 to 1 August 2026 |
| `640-214/` | Reglement über die Notengebung an den berufsbildenden Schulen des Kantons Basel-Landschaft (SGS 640.214) | 2 | as enacted, then each consolidated version: 1 August 2007 to 1 March 2021 |
| `640-221/` | Reglement über Aufnahmen und Übertritte (SGS 640.221) | 4 | as enacted, then each consolidated version: 1 August 2014 to 1 January 2024 |
| `641-11/` | Verordnung für den Kindergarten und die Primarschule (SGS 641.11) | 13 | oldest version available, then each consolidated version: 1 August 2014 to 1 August 2025 |
| `642-11/` | Verordnung für die Sekundarschule (SGS 642.11) | 14 | oldest version available, then each consolidated version: 1 August 2014 to 1 August 2026 |
| `642-15/` | Verordnung über den Mittagstisch an der Sekundarschule (SGS 642.15) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 August 2024 |
| `643-11/` | Verordnung über das Gymnasium (Maturitätsschule und Fachmittelschule) (SGS 643.11) | 13 | oldest version available, then each consolidated version: 1 August 2014 to 1 January 2026 |
| `643-15/` | Verordnung über den Besuch von Schulen der Sekundarstufe II im Kanton Basel-Stadt durch Schülerinnen und Schüler der Einwohnergemeinden Allschwil und Schönenbuch (SGS 643.15) | 2 | oldest version available, then each consolidated version: 1 August 2007 to 1 January 2022 |
| `643-21/` | Verordnung über die Maturitätsprüfungen (SGS 643.21) | 4 | oldest version available, then each consolidated version: 1 August 2014 to 1 August 2024 |
| `643-23-vo-bm/` | Verordnung über die Berufsmaturität des Kantons Basel-Landschaft (SGS 643.23) | 3 | as enacted, then each consolidated version: 1 January 2015 to 1 August 2026 |
| `643-31/` | Verordnung über die Abschlussprüfungen der Fachmittelschule an den Gymnasien (SGS 643.31) | 8 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2026 |
| `643-49/` | Verordnung über das Nachdiplomstudium zur Sekundarlehrerin oder zum Sekundarlehrer Kanton Basel-Landschaft, Niveau A (SGS 643.49) | 1 | as enacted, 1 August 2003 |
| `643-51/` | Verordnung über die Organisation des interkantonalen bilingualen gymnasialen Bildungsgangs der Kantone Basel-Landschaft und Jura (SGS 643.51) | 1 | as enacted, 1 August 2017 |
| `643-161/` | Reglement über die Übertrittsbedingungen der Schülerinnen und Schüler aus dem Fricktal an die basellandschaftlichen Gymnasien (SGS 643.161) | 2 | as enacted, then each consolidated version: 1 August 2005 to 1 August 2018 |
| `645-11-schulgesundheitsverordnung/` | Verordnung zum Schulgesundheitsgesetz (SGS 645.11) | 2 | oldest version available, then each consolidated version: 1 July 2007 to 1 August 2019 |
| `645-13/` | Verordnung über die arbeitsmedizinische Untersuchung der Lernenden (SGS 645.13) | 1 | as enacted, 1 July 2005 |
| `645-21/` | Verordnung über den Schulpsychologischen Dienst (SGS 645.21) | 2 | as enacted, then each consolidated version: 1 August 2008 to 1 August 2021 |
| `645-30/` | Verordnung über den Schulsozialdienst auf der Primarstufe (SGS 645.30) | 1 | as enacted, 1 April 2021 |
| `645-31/` | Verordnung über den Schulsozialdienst auf der Sekundarstufe I und II (SGS 645.31) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2024 |
| `645-41/` | Verordnung über die Berufs-, Studien- und Laufbahnberatung (SGS 645.41) | 2 | as enacted, then each consolidated version: 1 July 2021 to 1 August 2025 |
| `645-61-lehrmittelverordnung/` | Verordnung über die Lehrmittel, Schulmaterialien und Unterrichtshilfen für die Volksschulen (SGS 645.61) | 4 | oldest version available, then each consolidated version: 12 August 1996 to 1 January 2023 |
| `645-71-vo-sb/` | Verordnung über die Schulbibliotheken (SGS 645.71) | 2 | as enacted, then each consolidated version: 1 August 2006 to 1 April 2026 |
| `646-40-vo-az-lp/` | Verordnung über den Berufsauftrag und die Arbeitszeit von Lehrpersonen (SGS 646.40) | 6 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2024 |
| `646-41-vo-akk/` | Verordnung über die Amtliche Kantonalkonferenz der Lehrerinnen und Lehrer des Kantons Basel-Landschaft (SGS 646.41) | 3 | as enacted, then each consolidated version: 1 August 2005 to 18 January 2021 |
| `647-12/` | Verordnung für die Schulleitung und die Schulsekretariate (SGS 647.12) | 12 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2026 |
| `648-11/` | Verordnung über das Raumprogramm für Sekundarschulanlagen (SGS 648.11) | 2 | oldest version available, then each consolidated version: 1 July 2013 to 1 April 2021 |
| `681-11/` | Verordnung für die Berufsbildung (SGS 681.11) | 15 | oldest version available, then each consolidated version: 1 August 2014 to 1 January 2026 |
| `681-13/` | Verordnung über die Höhe der Beiträge des Kantons an Institutionen, Einrichtungen und Veranstaltungen der Berufsbildung (SGS 681.13) | 2 | as enacted, then each consolidated version: 1 January 1989 to 1 January 2022 |
| `681-16-prufungsverordnung/` | Verordnung über die Organisation und Durchführung der Qualifikationsverfahren der beruflichen Grundbildung (SGS 681.16) | 6 | oldest version available, then each consolidated version: 1 June 2013 to 1 January 2026 |
| `686-13/` | Verordnung über die landwirtschaftliche berufliche Grundbildung und die Vorlehre hauswirtschaftlicher Richtung (SGS 686.13) | 2 | as enacted, then each consolidated version: 1 August 2010 to 1 January 2022 |
| `686-14/` | Verordnung über die land- und hauswirtschaftliche Weiterbildung und Beratung sowie die Führung einer Tagungsstätte am Ebenrain (SGS 686.14) | 1 | one version (the oldest available), 1 April 2012 |
| `687-12/` | Regierungsratsverordnung über die Ausbildung und die Lehrabschlussprüfung der hauswirtschaftlichen Angestellten im Kollektivhaushalt (Spital) (SGS 687.12) | 1 | as enacted, 1 March 1984 |
| `687-13/` | Verordnung über die Berufsschule für Pflege (SGS 687.13) | 1 | one version (the oldest available), 1 April 2000 |
| `688-11/` | Verordnung der GDK über die Anerkennung und Nachprüfung von ausländischen Berufsqualifikationen in Osteopathie (SGS 688.11) | 1 | as enacted, 22 November 2012 |
| `688-221-raka/` | Reglement des Schweizerischen Roten Kreuzes (SRK) über die Anerkennung kantonaler Ausbildungsabschlüsse (SGS 688.221) | 1 | as enacted, 1 July 1999 |
| `688-222/` | Reglement der GDK für die interkantonale Prüfung von Osteopathinnen und Osteopathen in der Schweiz (SGS 688.222) | 1 | as enacted, 1 January 2007 |
| `689-12/` | Verordnung über die Gebühren für die Höhere Fachschule ICT (HF ICT) (SGS 689.12) | 1 | as enacted, 1 August 2019 |
| `691-11-awebiv-bl/` | Verordnung über die Allgemeine Weiterbildung Basel-Landschaft (SGS 691.11) | 2 | as enacted, then each consolidated version: 1 November 2017 to 1 January 2020 |
| `700-11-polizeiverordnung-polv/` | Verordnung zum Polizeigesetz (SGS 700.11) | 11 | oldest version available, then each consolidated version: 1 July 2013 to 1 April 2025 |
| `700-21/` | Verordnung über das Lage- und Führungsinformationssystem LAFIS (SGS 700.21) | 1 | as enacted, 1 August 2021 |
| `702-11/` | Verordnung über das Schiessen am Banntag (SGS 702.11) | 1 | as enacted, 1 January 1999 |
| `702-12/` | Verordnung über die Zuständigkeiten zum Vollzug der Massnahmen gegen Gewalt anlässlich von Sportveranstaltungen (SGS 702.12) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2025 |
| `703-11/` | Verordnung über das Halten gefährlicher Tiere (SGS 703.11) | 1 | one version (the oldest available), 1 July 2004 |
| `704-11/` | Verordnung zum Bundesgesetz über Waffen, Waffenzubehör und Munition (SGS 704.11) | 1 | one version (the oldest available), 1 March 2013 |
| `721-12/` | Verordnung über das militärische Disziplinarwesen (SGS 721.12) | 3 | oldest version available, then each consolidated version: 1 July 2013 to 1 November 2025 |
| `731-11-vo-bsg-bl/` | Verordnung zum Bevölkerungsschutzgesetz im Kanton Basel-Landschaft (SGS 731.11) | 4 | oldest version available, then each consolidated version: 1 March 2013 to 1 June 2024 |
| `732-11-vo-zsg-bl/` | Verordnung zum Zivilschutzgesetz im Kanton Basel-Landschaft (SGS 732.11) | 4 | as enacted, then each consolidated version: 1 July 2022 to 1 January 2026 |
| `760-11-fwv/` | Verordnung über die Feuerwehr (SGS 760.11) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `761-11-brand-und-naturgefahrenpraventionsverordnung-bnpv/` | Verordnung über die Prävention vor Schäden durch Brand- und gravitative Naturgefahren (SGS 761.11) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2018 |
| `761-111-beitragsreglement-br/` | Reglement über Beiträge an freiwillige Schutzmassnahmen (SGS 761.111) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 January 2025 |
| `780-11-usv/` | Verordnung über den Umweltschutz (SGS 780.11) | 3 | oldest version available, then each consolidated version: 15 July 2014 to 1 January 2026 |
| `781-11/` | Verordnung über die Gebühren für Vollzugsaufgaben im Bereich Lärmschutz (SGS 781.11) | 2 | as enacted, then each consolidated version: 1 April 1998 to 1 April 2020 |
| `781-12-smog-verordnung/` | Verordnung über die Massnahmen zur Reduktion der Feinstaubbelastung in der Luft bei austauscharmen Wetterlagen (SGS 781.12) | 2 | as enacted, then each consolidated version: 1 March 2007 to 1 January 2026 |
| `782-11-kgschv/` | Kantonale Gewässerschutzverordnung (SGS 782.11) | 4 | oldest version available, then each consolidated version: 1 April 2012 to 1 July 2023 |
| `784-11/` | Verordnung über die Entsorgung von Kühlgeräten (SGS 784.11) | 1 | as enacted, 1 June 1990 |
| `784-22/` | Verordnung über Preise für die Entsorgung von Abfällen und speziellen Abwässern (SGS 784.22) | 1 | one version (the oldest available), 1 January 2013 |
| `786-14-vvesa/` | Verordnung über die Verschärfung von Emissionsbegrenzungen für stationäre Anlagen (SGS 786.14) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `786-211-vfkg/` | Verordnung über die Feuerungskontrolle der Gemeinden (SGS 786.211) | 4 | oldest version available, then each consolidated version: 1 September 2011 to 1 January 2026 |
| `787-11/` | Verordnung über die Gebühren des Chemiewehr-Stützpunkts des Kantons Basel-Landschaft (SGS 787.11) | 2 | as enacted, then each consolidated version: 1 October 2004 to 1 January 2015 |
| `790-001/` | Reglement der Natur- und Landschaftsschutzkommission (NLK) (SGS 790.001) | 1 | as enacted, 1 May 2020 |
| `790-11-artenschutzverordnung/` | Verordnung über den Schutz der einheimischen Pflanzen- und Tierarten (SGS 790.11) | 1 | one version (the oldest available), 1 January 2012 |
| `790-31/` | Verordnung über die Förderung der Biodiversität und Landschaftsqualität im Landwirtschaftsgebiet (SGS 790.31) | 2 | as enacted, then each consolidated version: 1 January 2002 to 24 March 2015 |
| `790-401/` | Regierungsratsverordnung über die Aufnahme des Feuchtbiotopes Hefleten, Zunzgen, in das Inventar der geschützten Naturdenkmäler (SGS 790.401) | 2 | as enacted, then each consolidated version: 20 September 1977 to 28 September 2024 |
| `790-402/` | Regierungsratsverordnung über die Aufnahme des Feuchtbiotopes Eimatt, Rümlingen, in das Inventar der geschützten Naturdenkmäler (SGS 790.402) | 2 | as enacted, then each consolidated version: 26 September 1977 to 28 September 2024 |
| `790-403/` | Verordnung über das Naturschutzgebiet «Reinacherheide», Reinach und Arlesheim (SGS 790.403) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `790-404/` | Verordnung über das Naturschutzgebiet «Andil», Liesberg (SGS 790.404) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-405/` | Verordnung über das Naturschutzgebiet «Chilpen», Diegten (SGS 790.405) | 2 | oldest version available, then each consolidated version: 1 May 2007 to 28 September 2024 |
| `790-406/` | Regierungsratsverordnung über den Naturschutzweiher Brunnmatt in Bubendorf (SGS 790.406) | 2 | as enacted, then each consolidated version: 18 September 1979 to 28 September 2024 |
| `790-408/` | Regierungsratsverordnung über 2 Naturschutzgebiete in Buus (SGS 790.408) | 2 | as enacted, then each consolidated version: 1 April 1980 to 28 September 2024 |
| `790-409/` | Regierungsratsverordnung über das Naturschutzgebiet Herzogenmatt in Binningen (SGS 790.409) | 2 | as enacted, then each consolidated version: 17 February 1981 to 28 September 2024 |
| `790-410/` | Verordnung über das Naturschutzgebiet «Tal», Anwil und Rothenfluh (SGS 790.410) | 2 | oldest version available, then each consolidated version: 1 May 2007 to 28 September 2024 |
| `790-411/` | Verordnung über das Naturschutzgebiet «Sulzgrube» in Muttenz (SGS 790.411) | 2 | as enacted, then each consolidated version: 1 February 1993 to 28 September 2024 |
| `790-412/` | Verordnung über das Naturschutzgebiet «Steingruebe», Wittinsburg (SGS 790.412) | 2 | as enacted, then each consolidated version: 1 February 1994 to 28 September 2024 |
| `790-413/` | Verordnung über das Naturschutzgebiet «Schöntal-Weiher», Langenbruck (SGS 790.413) | 2 | as enacted, then each consolidated version: 1 May 1994 to 28 September 2024 |
| `790-414/` | Verordnung über das Naturschutzgebiet «Firmach-Heidengräbern», Wintersingen (SGS 790.414) | 2 | as enacted, then each consolidated version: 1 November 1994 to 28 September 2024 |
| `790-415/` | Verordnung über das Naturschutzgebiet «Schanz-Walten», Diegten, Eptingen und Läufelfingen (SGS 790.415) | 3 | oldest version available, then each consolidated version: 1 May 1999 to 10 September 2025 |
| `790-416/` | Verordnung über das Naturschutzgebiet «Edlisberg-Meiersberg», Oberdorf und Waldenburg (SGS 790.416) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-417/` | Verordnung über das Naturschutzgebiet «Wildenstein», Bubendorf (SGS 790.417) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-418/` | Verordnung über das Naturschutzgebiet «Dürstelberg», Langenbruck (SGS 790.418) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 22 December 2022 |
| `790-419/` | Verordnung über das Naturschutzgebiet «Oltme», Liesberg (SGS 790.419) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-420/` | Verordnung über das Naturschutzgebiet «Eichen», Bretzwil (SGS 790.420) | 2 | oldest version available, then each consolidated version: 1 October 2014 to 28 September 2024 |
| `790-421/` | Verordnung über das Naturschutzgebiet «Tenniker Fluh - Sangeten», Tenniken (SGS 790.421) | 2 | as enacted, then each consolidated version: 1 November 1998 to 28 September 2024 |
| `790-422/` | Verordnung über das Naturschutzgebiet «Stellihübel - Furtboden», Seltisberg (SGS 790.422) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-423/` | Verordnung über das Naturschutzgebiet «Dürrain», Muttenz (SGS 790.423) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 2 December 2025 |
| `790-424/` | Verordnung über das Naturschutzgebiet «Fröschenegg», Muttenz (SGS 790.424) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 2 December 2025 |
| `790-425/` | Verordnung über das Naturschutzgebiet «Wartenberg», Muttenz (SGS 790.425) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 2 December 2025 |
| `790-426/` | Verordnung über das Naturschutzgebiet «Rütihard-Rothallen», Muttenz (SGS 790.426) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 2 December 2025 |
| `790-427/` | Verordnung über das Naturschutzgebiet «Richtiflue», Waldenburg (SGS 790.427) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-428/` | Verordnung über das Naturschutzgebiet «Esel», Waldenburg (SGS 790.428) | 2 | oldest version available, then each consolidated version: 1 April 2011 to 28 September 2024 |
| `790-429/` | Verordnung über das Naturschutzgebiet «Rehhag», Waldenburg, Oberdorf und Bennwil (SGS 790.429) | 2 | oldest version available, then each consolidated version: 1 May 2014 to 28 September 2024 |
| `790-430/` | Verordnung über das Naturschutzgebiet «Chapfflüeli», Waldenburg (SGS 790.430) | 3 | oldest version available, then each consolidated version: 1 April 2011 to 29 November 2024 |
| `790-431/` | Verordnung über das Naturschutzgebiet «Wasserfalle - Roti Flue», Diegten und Eptingen (SGS 790.431) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 6 December 2024 |
| `790-432/` | Verordnung über das Naturschutzgebiet «Rutenrain», Diegten (SGS 790.432) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 6 December 2024 |
| `790-433/` | Verordnung über das Naturschutzgebiet «Ränggen», Diegten (SGS 790.433) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 6 December 2024 |
| `790-434/` | Verordnung über das Naturschutzgebiet «Rebhalde-Rehhag», Diepflingen und Gelterkinden (SGS 790.434) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-435/` | Verordnung über das Naturschutzgebiet «Rüti», Wittinsburg (SGS 790.435) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-436/` | Verordnung über das Naturschutzgebiet «Chastelenflue», Arboldswil (SGS 790.436) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-437/` | Verordnung über das Naturschutzgebiet «Brocheni Flue», Waldenburg (SGS 790.437) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-438/` | Verordnung über das Naturschutzgebiet «Dürrenberg», Waldenburg (SGS 790.438) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-439/` | Verordnung über das Naturschutzgebiet «Oerlenberg», Waldenburg (SGS 790.439) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-440/` | Verordnung über das Naturschutzgebiet «Steingraben», Hemmiken (SGS 790.440) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-441/` | Verordnung über das Naturschutzgebiet «Meistelberg-Bohlberg», Liesberg (SGS 790.441) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-442/` | Verordnung über das Naturschutzgebiet «Schöntalfluh-Spittelweid», Langenbruck (SGS 790.442) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-443/` | Verordnung über das Naturschutzgebiet «Wisenberg», Häfelfingen (SGS 790.443) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-444/` | Verordnung über das Naturschutzgebiet «Teufleten», Häfelfingen (SGS 790.444) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-446/` | Verordnung über das Naturschutzgebiet «Deigsberg», Lauwil (SGS 790.446) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-448/` | Verordnung über das Naturschutzgebiet «Wischberg», Ormalingen und Rothenfluh (SGS 790.448) | 2 | oldest version available, then each consolidated version: 1 April 2010 to 28 September 2024 |
| `790-449/` | Verordnung über das Naturschutzgebiet «Zangenweidli», Gelterkinden (SGS 790.449) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-450/` | Verordnung über das Naturschutzgebiet «Häxenblätz-Brangboden», Bretzwil (SGS 790.450) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-451/` | Verordnung über das Naturschutzgebiet «Binzenberg-Chüeweid», Bretzwil und Reigoldswil (SGS 790.451) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-452/` | Verordnung über das Naturschutzgebiet «Balsberg», Bretzwil (SGS 790.452) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-453/` | Verordnung über das Naturschutzgebiet «Ramstein-Aleten», Bretzwil und Lauwil (SGS 790.453) | 3 | as enacted, then each consolidated version: 30 January 2002 to 28 September 2024 |
| `790-454/` | Verordnung über das Naturschutzgebiet «Riedberg-Stierenberg», Bretzwil (SGS 790.454) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-455/` | Verordnung über das Naturschutzgebiet «Ämmenegg-Ulmet», Bretzwil und Lauwil (SGS 790.455) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-456/` | Verordnung über das Naturschutzgebiet «Grammel», Lausen (SGS 790.456) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-457/` | Verordnung über das Naturschutzgebiet «Widenhölzli», Gemeinde Reigoldswil (SGS 790.457) | 2 | as enacted, then each consolidated version: 13 January 2003 to 28 September 2024 |
| `790-458/` | Verordnung über das Naturschutzgebiet «Rifenstein-Horniflue», Gemeinden Reigoldswil und Titterten (SGS 790.458) | 2 | as enacted, then each consolidated version: 13 January 2003 to 28 September 2024 |
| `790-459/` | Verordnung über das Naturschutzgebiet «Gillen», Reigoldswil (SGS 790.459) | 2 | as enacted, then each consolidated version: 13 January 2003 to 28 September 2024 |
| `790-460/` | Verordnung über das Naturschutzgebiet «Baberten», Reigoldswil und Titterten (SGS 790.460) | 2 | as enacted, then each consolidated version: 13 January 2003 to 28 September 2024 |
| `790-461/` | Verordnung über das Naturschutzgebiet «Geissrain», Gemeinde Reigoldswil (SGS 790.461) | 2 | as enacted, then each consolidated version: 13 January 2003 to 28 September 2024 |
| `790-462/` | Verordnung über das Naturschutzgebiet «Bürtenflue-Ängiberg», Lauwil und Reigoldswil (SGS 790.462) | 2 | as enacted, then each consolidated version: 13 January 2003 to 28 September 2024 |
| `790-463/` | Verordnung über das Naturschutzgebiet «Sonnenberg», Maisprach (SGS 790.463) | 2 | as enacted, then each consolidated version: 14 April 2003 to 28 September 2024 |
| `790-464/` | Verordnung über das Naturschutzgebiet «Schleipfet», Gemeinde Oltingen (SGS 790.464) | 2 | as enacted, then each consolidated version: 1 May 2005 to 28 September 2024 |
| `790-465/` | Verordnung über das Naturschutzgebiet «Ermitage-Chilchholz», Arlesheim (SGS 790.465) | 3 | as enacted, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-466/` | Verordnung über das Naturschutzgebiet «Chienberg», Böckten, Gelterkinden, Rickenbach, Sissach und Wintersingen (SGS 790.466) | 2 | as enacted, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-467/` | Verordnung über das Naturschutzgebiet «Farnsberg», Rickenbach und Ormalingen (SGS 790.467) | 2 | as enacted, then each consolidated version: 1 January 2007 to 28 September 2024 |
| `790-468/` | Verordnung über das Naturschutzgebiet «Rumpel-Chlapfen», Oltingen (SGS 790.468) | 2 | as enacted, then each consolidated version: 1 May 2007 to 28 September 2024 |
| `790-469/` | Verordnung über das Naturschutzgebiet «Chrindel», Rünenberg, Rümlingen und Häfelfingen (SGS 790.469) | 2 | as enacted, then each consolidated version: 1 January 2008 to 28 September 2024 |
| `790-470/` | Verordnung über das Naturschutzgebiet «Scheidegg», Rünenberg (SGS 790.470) | 2 | as enacted, then each consolidated version: 1 January 2008 to 28 September 2024 |
| `790-471/` | Verordnung über das Naturschutzgebiet «Blauenweide», Blauen (SGS 790.471) | 2 | as enacted, then each consolidated version: 1 January 2008 to 28 September 2024 |
| `790-472/` | Verordnung über das Naturschutzgebiet «Farnsberg», Buus (SGS 790.472) | 2 | as enacted, then each consolidated version: 1 February 2009 to 28 September 2024 |
| `790-473/` | Verordnung über das Naturschutzgebiet «Rugen», Buus (SGS 790.473) | 2 | as enacted, then each consolidated version: 1 February 2009 to 28 September 2024 |
| `790-474/` | Verordnung über das Naturschutzgebiet «Schönenberg», Buus und Maisprach (SGS 790.474) | 2 | as enacted, then each consolidated version: 1 February 2009 to 28 September 2024 |
| `790-475/` | Verordnung über das Naturschutzgebiet «Allmetgraben», Buus (SGS 790.475) | 2 | as enacted, then each consolidated version: 1 February 2009 to 28 September 2024 |
| `790-476/` | Verordnung über das Naturschutzgebiet «Tannenboden-Allmet», Lampenberg (SGS 790.476) | 2 | as enacted, then each consolidated version: 1 February 2009 to 28 September 2024 |
| `790-477/` | Verordnung über das Naturschutzgebiet «Dittinger Weide und Dittinger Wald», Dittingen (SGS 790.477) | 2 | as enacted, then each consolidated version: 1 March 2009 to 28 September 2024 |
| `790-478/` | Verordnung über das Naturschutzgebiet «Bogental-Geitenberg», Lauwil (SGS 790.478) | 2 | as enacted, then each consolidated version: 1 April 2009 to 28 September 2024 |
| `790-479/` | Verordnung über das Naturschutzgebiet «Neuligen», Anwil (SGS 790.479) | 2 | as enacted, then each consolidated version: 1 July 2009 to 28 September 2024 |
| `790-480/` | Verordnung über das Naturschutzgebiet «Kleinfegg», Pfeffingen (SGS 790.480) | 2 | as enacted, then each consolidated version: 1 January 2010 to 28 September 2024 |
| `790-481/` | Verordnung über das Naturschutzgebiet «Eital-Summerholden», Tecknau und Wenslingen (SGS 790.481) | 3 | as enacted, then each consolidated version: 1 March 1997 to 28 September 2024 |
| `790-482/` | Verordnung über das Naturschutzgebiet «Martiswald», Roggenburg (SGS 790.482) | 2 | as enacted, then each consolidated version: 1 January 2010 to 28 September 2024 |
| `790-483/` | Verordnung über das Naturschutzgebiet «Studenweid», Liedertswil (SGS 790.483) | 2 | as enacted, then each consolidated version: 1 February 2010 to 28 September 2024 |
| `790-484/` | Verordnung über das Naturschutzgebiet «Landschachen-Huppergruben», Bubendorf und Lausen (SGS 790.484) | 2 | as enacted, then each consolidated version: 1 July 2010 to 28 September 2024 |
| `790-485/` | Verordnung über das Naturschutzgebiet «Gipsgrube Zeglingen», Zeglingen (SGS 790.485) | 2 | as enacted, then each consolidated version: 1 July 2010 to 28 September 2024 |
| `790-486/` | Verordnung über das Naturschutzgebiet «Zinggibrunn», Muttenz (SGS 790.486) | 2 | as enacted, then each consolidated version: 1 January 2011 to 28 September 2024 |
| `790-487/` | Verordnung über das Naturschutzgebiet «Strickrain», Sissach (SGS 790.487) | 2 | as enacted, then each consolidated version: 1 January 2011 to 28 September 2024 |
| `790-488/` | Verordnung über das Naturschutzgebiet «Bitzenhalde», Läufelfingen (SGS 790.488) | 2 | as enacted, then each consolidated version: 1 January 2011 to 28 September 2024 |
| `790-489/` | Verordnung über das Naturschutzgebiet «Vorderer Wisenberg», Läufelfingen (SGS 790.489) | 2 | as enacted, then each consolidated version: 1 January 2011 to 28 September 2024 |
| `790-490/` | Verordnung über das Naturschutzgebiet «Löffelberg-Baanholz», Liesberg (SGS 790.490) | 2 | as enacted, then each consolidated version: 1 April 2011 to 28 September 2024 |
| `790-491/` | Verordnung über das Naturschutzgebiet «Falkeflue», Duggingen (SGS 790.491) | 2 | as enacted, then each consolidated version: 1 April 2011 to 28 September 2024 |
| `790-492/` | Verordnung über das Naturschutzgebiet «Breiten», Läufelfingen (SGS 790.492) | 2 | as enacted, then each consolidated version: 1 April 2011 to 28 September 2024 |
| `790-493/` | Verordnung über das Naturschutzgebiet «Wasserfallen», Reigoldswil und Waldenburg (SGS 790.493) | 2 | as enacted, then each consolidated version: 1 April 2011 to 28 September 2024 |
| `790-494/` | Verordnung über das Naturschutzgebiet «Gebstelli», Roggenburg (SGS 790.494) | 2 | as enacted, then each consolidated version: 1 August 2011 to 28 September 2024 |
| `790-495/` | Verordnung über das Naturschutzgebiet «Berg», Roggenburg (SGS 790.495) | 2 | as enacted, then each consolidated version: 1 August 2011 to 28 September 2024 |
| `790-496/` | Verordnung über das Naturschutzgebiet «Chlini Asp», Roggenburg (SGS 790.496) | 2 | as enacted, then each consolidated version: 1 August 2011 to 28 September 2024 |
| `790-497/` | Verordnung über das Naturschutzgebiet «Ziegelei Oberwil», Oberwil (SGS 790.497) | 2 | as enacted, then each consolidated version: 1 August 2011 to 28 September 2024 |
| `790-498/` | Verordnung über das Naturschutzgebiet «Büttenenloch-Stapflen», Ettingen (SGS 790.498) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-499/` | Verordnung über das Naturschutzgebiet «Amselfels», Ettingen (SGS 790.499) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-500/` | Verordnung über das Naturschutzgebiet «Fürstenstein», Ettingen (SGS 790.500) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-501/` | Verordnung über das Naturschutzgebiet «Redelsflue», Röschenz (SGS 790.501) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-502/` | Verordnung über das Naturschutzgebiet «Challhollen», Röschenz (SGS 790.502) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-503/` | Verordnung über das Naturschutzgebiet «Lange Rai», Röschenz (SGS 790.503) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-504/` | Verordnung über das Naturschutzgebiet «Brunnhollen», Röschenz (SGS 790.504) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-505/` | Verordnung über das Naturschutzgebiet «Forstweid», Röschenz (SGS 790.505) | 2 | as enacted, then each consolidated version: 1 January 2012 to 28 September 2024 |
| `790-506/` | Verordnung über das Naturschutzgebiet «Zwischenflüe-Brunnenstig», Niederdorf und Lampenberg (SGS 790.506) | 2 | as enacted, then each consolidated version: 1 July 2012 to 22 December 2022 |
| `790-507/` | Verordnung über das Naturschutzgebiet «Gugger», Niederdorf (SGS 790.507) | 2 | as enacted, then each consolidated version: 1 July 2012 to 28 September 2024 |
| `790-508/` | Verordnung über das Naturschutzgebiet «Leisenberg», Oberdorf (SGS 790.508) | 2 | as enacted, then each consolidated version: 1 July 2012 to 28 September 2024 |
| `790-509/` | Verordnung über das Naturschutzgebiet «Thommeten», Oberdorf (SGS 790.509) | 2 | as enacted, then each consolidated version: 1 July 2012 to 28 September 2024 |
| `790-510/` | Verordnung über das Naturschutzgebiet «Dielenberg-Hangelimatt», Oberdorf und Niederdorf (SGS 790.510) | 2 | as enacted, then each consolidated version: 1 July 2012 to 28 September 2024 |
| `790-511/` | Verordnung über das Naturschutzgebiet «Uf Geren», Laufen (SGS 790.511) | 2 | as enacted, then each consolidated version: 1 October 2012 to 28 September 2024 |
| `790-512/` | Verordnung über das Naturschutzgebiet «Mittler Stürmen», Laufen (SGS 790.512) | 2 | as enacted, then each consolidated version: 1 October 2012 to 28 September 2024 |
| `790-513/` | Verordnung über das Naturschutzgebiet «Hüttenboden», Laufen (SGS 790.513) | 2 | as enacted, then each consolidated version: 1 October 2012 to 28 September 2024 |
| `790-514/` | Verordnung über das Naturschutzgebiet «Schlossberg», Burg (SGS 790.514) | 2 | as enacted, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-515/` | Verordnung über das Naturschutzgebiet «Blüttenenchöpfli-Chaselboden», Burg (SGS 790.515) | 2 | as enacted, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-516/` | Verordnung über das Naturschutzgebiet «Bilsteinflue-Nünbrunnen», Langenbruck und Waldenburg (SGS 790.516) | 2 | as enacted, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-517/` | Verordnung über das Naturschutzgebiet «Bärelöcher», Laufen und Röschenz (SGS 790.517) | 2 | as enacted, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-518/` | Verordnung über das Naturschutzgebiet «Strickhübel», Röschenz (SGS 790.518) | 2 | as enacted, then each consolidated version: 1 January 2013 to 28 September 2024 |
| `790-519/` | Verordnung über das Naturschutzgebiet «Roti Flue - Dübach», Rothenfluh (SGS 790.519) | 2 | as enacted, then each consolidated version: 1 March 2013 to 28 September 2024 |
| `790-520/` | Verordnung über das Naturschutzgebiet «Zigflue», Oltingen (SGS 790.520) | 2 | as enacted, then each consolidated version: 1 January 2014 to 28 September 2024 |
| `790-521/` | Verordnung über das Naturschutzgebiet «Allschwiler Wald», Allschwil (SGS 790.521) | 3 | as enacted, then each consolidated version: 14 April 2003 to 28 September 2024 |
| `790-522/` | Verordnung über das Naturschutzgebiet «Roter Herd», Bennwil (SGS 790.522) | 2 | as enacted, then each consolidated version: 1 May 2014 to 28 September 2024 |
| `790-523/` | Verordnung über das Naturschutzgebiet «Harzflue», Bennwil (SGS 790.523) | 2 | as enacted, then each consolidated version: 1 May 2014 to 28 September 2024 |
| `790-524/` | Verordnung über das Naturschutzgebiet «Amerika», Hölstein (SGS 790.524) | 2 | as enacted, then each consolidated version: 1 May 2014 to 28 September 2024 |
| `790-525/` | Verordnung über das Naturschutzgebiet «Eggwald-Looch», Ramlinsburg (SGS 790.525) | 2 | as enacted, then each consolidated version: 1 May 2014 to 28 September 2024 |
| `790-526/` | Verordnung über das Naturschutzgebiet «Homberg», Läufelfingen und Buckten (SGS 790.526) | 2 | as enacted, then each consolidated version: 1 March 2015 to 28 September 2024 |
| `790-527/` | Verordnung über das Naturschutzgebiet «Helfenbergrüttenen», Langenbruck (SGS 790.527) | 2 | as enacted, then each consolidated version: 1 October 2016 to 28 September 2024 |
| `790-528/` | Verordnung über das Naturschutzgebiet «Schafmatt», Oltingen (SGS 790.528) | 2 | as enacted, then each consolidated version: 1 October 2017 to 28 September 2024 |
| `790-529/` | Verordnung über das Naturschutzgebiet «Blüemlisalp», Waldenburg (SGS 790.529) | 2 | as enacted, then each consolidated version: 1 January 2018 to 28 September 2024 |
| `790-530/` | Verordnung über das Naturschutzgebiet «Birshollen», Laufen (SGS 790.530) | 2 | as enacted, then each consolidated version: 1 August 2018 to 28 September 2024 |
| `790-531/` | Verordnung über das Naturschutzgebiet «Holzmatt», Biel-Benken (SGS 790.531) | 2 | as enacted, then each consolidated version: 1 August 2018 to 28 September 2024 |
| `790-532/` | Verordnung über das Naturschutzgebiet «Holznacht», Waldenburg und Langenbruck (SGS 790.532) | 2 | as enacted, then each consolidated version: 1 October 2018 to 28 September 2024 |
| `790-533/` | Verordnung über das Naturschutzgebiet «Hag», Dittingen (SGS 790.533) | 2 | as enacted, then each consolidated version: 15 December 2020 to 28 September 2024 |
| `790-534/` | Verordnung über das Naturschutzgebiet «Schellenberg», Langenbruck (SGS 790.534) | 2 | as enacted, then each consolidated version: 15 December 2020 to 28 September 2024 |
| `790-535/` | Verordnung über das Naturschutzgebiet «Hümpeli», Füllinsdorf (SGS 790.535) | 2 | as enacted, then each consolidated version: 1 December 2021 to 28 September 2024 |
| `790-536/` | Verordnung über das Naturschutzgebiet «Ramschberg-Zettel», Arisdorf und Füllinsdorf (SGS 790.536) | 2 | as enacted, then each consolidated version: 1 December 2021 to 28 September 2024 |
| `790-537/` | Verordnung über das Naturschutzgebiet «Eileten-Dumberg», Arisdorf (SGS 790.537) | 2 | as enacted, then each consolidated version: 16 December 2021 to 28 September 2024 |
| `790-538/` | Verordnung über das Naturschutzgebiet «Bärenfels», Arisdorf (SGS 790.538) | 2 | as enacted, then each consolidated version: 16 December 2021 to 28 September 2024 |
| `790-539/` | Verordnung über das Naturschutzgebiet «Albachhollen», Liesberg (SGS 790.539) | 2 | as enacted, then each consolidated version: 18 December 2021 to 28 September 2024 |
| `790-540/` | Verordnung über das Naturschutzgebiet «Chestel», Liesberg (SGS 790.540) | 2 | as enacted, then each consolidated version: 18 December 2021 to 28 September 2024 |
| `790-541/` | Verordnung über das Naturschutzgebiet «Erhollen-Chlummen», Liesberg (SGS 790.541) | 2 | as enacted, then each consolidated version: 18 December 2021 to 28 September 2024 |
| `790-542/` | Verordnung über das Naturschutzgebiet «Hell», Liesberg (SGS 790.542) | 2 | as enacted, then each consolidated version: 18 December 2021 to 28 September 2024 |
| `790-543/` | Verordnung über das Naturschutzgebiet «Liesbergweid-Tannig», Liesberg (SGS 790.543) | 2 | as enacted, then each consolidated version: 18 December 2021 to 28 September 2024 |
| `790-544/` | Verordnung über das Naturschutzgebiet «Röserental», Liestal (SGS 790.544) | 2 | as enacted, then each consolidated version: 18 December 2021 to 28 September 2024 |
| `790-545/` | Verordnung über das Naturschutzgebiet «Sunnenrain», Zwingen (SGS 790.545) | 1 | as enacted, 1 December 2022 |
| `790-546/` | Verordnung über das Naturschutzgebiet «Chlus», Blauen (SGS 790.546) | 1 | as enacted, 22 December 2022 |
| `790-547/` | Verordnung über das Naturschutzgebiet «Radme-Hanslifels-Chällengraben», Blauen (SGS 790.547) | 1 | as enacted, 22 December 2022 |
| `790-548/` | Verordnung über das Naturschutzgebiet «Mittlere St. Romay», Lauwil (SGS 790.548) | 1 | as enacted, 6 December 2024 |
| `790-549/` | Verordnung über das Naturschutzgebiet «Buechholde», Lausen (SGS 790.549) | 1 | as enacted, 27 May 2025 |
| `790-550/` | Verordnung über das Naturschutzgebiet «Bodenmatt», Ormalingen (SGS 790.550) | 2 | as enacted, then each consolidated version: 1 November 1995 to 28 September 2024 |
| `790-551/` | Verordnung über das Naturschutzgebiet «Dürstel», Langenbruck (SGS 790.551) | 1 | as enacted, 7 January 2026 |
| `790-552/` | Verordnung über das Naturschutzgebiet «Rehhagweid-Lauchweid», Langenbruck und Eptingen (SGS 790.552) | 1 | as enacted, 7 January 2026 |
| `791-11/` | Verordnung über die Vergütung von Naturschutzmassnahmen im Wald (SGS 791.11) | 1 | as enacted, 1 July 1998 |
| `791-22/` | Regierungsratsverordnung über die Inventarisation und Sicherstellung erhaltenswerter Gegenstände und Bauteile in Liegenschaften, die vom Kanton übernommen werden (SGS 791.22) | 1 | as enacted, 1 September 1976 |
| `793-11-archvo/` | Verordnung zum Archäologiegesetz (SGS 793.11) | 1 | as enacted, 1 November 2005 |
| `814-11-vsa/` | Verordnung über die Bekämpfung der Schwarzarbeit (SGS 814.11) | 2 | as enacted, then each consolidated version: 14 February 2014 to 1 July 2021 |
| `815-11-flamav/` | Verordnung über die flankierenden Massnahmen im Arbeitsmarkt (SGS 815.11) | 1 | as enacted, 1 July 2021 |
| `822-10-arbeitsgesetzvollzugsverordnung/` | Verordnung zum Vollzug des eidgenössischen Arbeitsgesetzes (SGS 822.10) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `823-11/` | Verordnung zu den Bundesverordnungen über die Arbeits- und Ruhezeit der berufsmässigen Motorfahrzeugführer und -führerinnen sowie der Führer von leichten Motorwagen zum gewerbsmässigen Personentransport (SGS 823.11) | 1 | as enacted, 1 March 1996 |
| `831-11-eg-ahvg-ivg-bl/` | Verordnung zum Einführungsgesetz über die Alters-, Hinterlassenen- und Invalidenversicherung (SGS 831.11) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `833-11-erganzungsleistungsverordnung-elv-bl/` | Verordnung zum Ergänzungsleistungsgesetz zur AHV und IV (SGS 833.11) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `834-11-garantieverordnung/` | Verordnung über die Kantonsgarantie zugunsten der Pensionskasse für deren Ausfinanzierungsforderungen gegenüber Arbeitgebenden (SGS 834.11) | 1 | as enacted, 20 May 2014 |
| `834-12-poolingverordnung/` | Verordnung über die Darlehen an Arbeitgebende für die Ausfinanzierung der Forderungen der Pensionskasse (SGS 834.12) | 1 | as enacted, 20 May 2014 |
| `837-21/` | Verordnung über die Tripartite Kommission (TPK) für die Regionalen Arbeitsvermittlungszentren (RAV) (SGS 837.21) | 2 | as enacted, then each consolidated version: 1 January 2003 to 1 July 2026 |
| `837-22/` | Verordnung über die Übertragung von Aufgaben der kantonalen Amtsstelle an die Regionalen Arbeitsvermittlungszentren und die Logistik-Stelle für arbeitsmarktliche Massnahmen (SGS 837.22) | 2 | oldest version available, then each consolidated version: 1 September 2014 to 1 April 2025 |
| `838-11-eg-famzv/` | Verordnung zum Einführungsgesetz vom 7. Mai 2009 zum Bundesgesetz über die Familienzulagen (SGS 838.11) | 1 | as enacted, 1 January 2010 |
| `838-111/` | Verordnung über die Entschädigung für die Führung der Zweigstellen der kantonalen Ausgleichskasse und Familienausgleichskasse (SGS 838.111) | 1 | as enacted, 1 January 1991 |
| `842-11-wohnbauforderungsverordnung-wbfv/` | Verordnung über die Wohnbauförderung (SGS 842.11) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `844-11-vo-mbg/` | Verordnung zum Mietzinsbeitragsgesetz (SGS 844.11) | 2 | as enacted, then each consolidated version: 1 July 2023 to 1 January 2024 |
| `850-11-shv/` | Sozialhilfeverordnung (SGS 850.11) | 11 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `850-12-bvv/` | Verordnung über die Bevorschussung und die Vollstreckungshilfe für Unterhaltsbeiträge (SGS 850.12) | 1 | one version (the oldest available), 1 January 2013 |
| `850-14-heimverordnung/` | Verordnung über die Bewilligung und Beaufsichtigung von Heimen (SGS 850.14) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 December 2019 |
| `850-15/` | Verordnung über die Kinder- und Jugendhilfe (SGS 850.15) | 8 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `850-19-kav/` | Kantonale Asylverordnung (SGS 850.19) | 9 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `850-21/` | Verordnung über die Konsultativkommission Sozialhilfe (SGS 850.21) | 2 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2025 |
| `851-7/` | Verordnung über Schwangerschaftsberatungsstellen (SGS 851.7) | 1 | as enacted, 1 July 1985 |
| `852-11/` | Verordnung über die familienergänzende Kinderbetreuung (SGS 852.11) | 1 | as enacted, 1 January 2017 |
| `853-11-bhv/` | Verordnung über die Behindertenhilfe (SGS 853.11) | 5 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2025 |
| `901-11-amtsarztetarif/` | Verordnung über den amtsärztlichen Tarif (SGS 901.11) | 1 | as enacted, 1 April 1995 |
| `901-13/` | Verordnung über die Ausrichtung einer Inkonvenienzentschädigung bei Hausgeburten und ambulanten Wochenbettbetreuungen (SGS 901.13) | 1 | as enacted, 1 January 2016 |
| `901-32/` | Verordnung über die Bezeichnung einer unabhängigen Instanz gemäss Artikel 13 des Transplantationsgesetzes (SGS 901.32) | 1 | as enacted, 1 April 2013 |
| `901-41-adv/` | Verordnung über die Alkohol- und Drogentherapien (SGS 901.41) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `901-115/` | Reglement über die Kontrolle der hygienischen Flusswasserqualität bei gut frequentierten Badeplätzen (SGS 901.115) | 1 | as enacted, 15 June 1990 |
| `902-11/` | Verordnung über die Inkraftsetzung des Kinder- und Jugendzahnpflegegesetzes vom 19. September 1996 und von zwei Dekretsänderungen (SGS 902.11) | 1 | as enacted, 31 December 1996 |
| `902-12-verordnung-kieferorthopadie/` | Verordnung über die subventionswürdigen kieferorthopädischen Leistungen im Bereich der Kinder- und Jugendzahnpflege (SGS 902.12) | 2 | as enacted, then each consolidated version: 11 August 1997 to 31 March 2015 |
| `902-13/` | Verordnung über den Taxpunktwert für die Kinder- und Jugendzahnpflege (SGS 902.13) | 2 | as enacted, then each consolidated version: 1 May 2002 to 20 June 2018 |
| `912-12/` | Verordnung über die Stellvertreterzulage der Chefarzt-Stellvertreter und -Stellvertreterinnen und der Leitenden Ärzte und Ärztinnen der kantonalen Krankenanstalten (SGS 912.12) | 1 | as enacted, 1 January 1991 |
| `913-11-arzneimittelverordnung/` | Verordnung über den Verkehr mit Arzneimitteln (SGS 913.11) | 1 | one version (the oldest available), 1 July 2013 |
| `914-12/` | Verordnung über die Berufe im Gesundheitswesen (SGS 914.12) | 3 | oldest version available, then each consolidated version: 1 July 2010 to 1 January 2025 |
| `914-13-vzh/` | Verordnung über die Zulassung und Höchstzahlen (SGS 914.13) | 1 | as enacted, 1 July 2025 |
| `915-11-verordnung-ausbildungsforderung-pflege-vo-eg-bgfap/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (SGS 915.11) | 2 | as enacted, then each consolidated version: 1 April 2022 to 1 July 2024 |
| `921-14/` | Regierungsratsverordnung über den Rahmentarif für Ärzte und Krankenkassen (SGS 921.14) | 1 | as enacted, 1 May 1985 |
| `930-11-spitaltax-und-tarifverordnung/` | Verordnung über die Taxen und Tarife der kantonalen Krankenhäuser (SGS 930.11) | 1 | one version (the oldest available), 1 January 2012 |
| `931-11-spivv/` | Verordnung zum Spitalversorgungsgesetz (SGS 931.11) | 1 | as enacted, 1 October 2019 |
| `934-11/` | Verordnung über die Organisation des Kranken- und Rettungstransports (SGS 934.11) | 3 | oldest version available, then each consolidated version: 1 July 2013 to 1 July 2026 |
| `934-21/` | Verordnung über die Leichentransporte (SGS 934.21) | 1 | as enacted, 1 July 2026 |
| `955-51/` | Verordnung über den Vollzug der eidgenössischen Chemikaliengesetzgebung (SGS 955.51) | 1 | as enacted, 1 February 2009 |
| `961-121/` | Reglement über den Desinfektorentarif (SGS 961.121) | 1 | as enacted, 1 July 1985 |
| `971-11-gebuhrenverordnung-labor-und-inspektorate/` | Verordnung über die Gebühren des Amts für Lebensmittelsicherheit und Veterinärwesen im Bereich Labor und Inspektorate (SGS 971.11) | 2 | as enacted, then each consolidated version: 1 February 2006 to 1 January 2026 |
| `972-11-lebensmittelverordnung/` | Verordnung über den Vollzug der Bundesgesetzgebung über Lebensmittel und Gebrauchsgegenstände (SGS 972.11) | 1 | one version (the oldest available), 1 July 2004 |
| `980-11/` | Verordnung über die Tierseuchenbekämpfung (SGS 980.11) | 3 | oldest version available, then each consolidated version: 1 February 2010 to 1 January 2024 |

### Additional current-text acts

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `100-1/` | Beschluss betreffend Bestimmung der basellandschaftlichen Kantonsfarbe (SGS 100.1) | 1 | oldest version available, 1836-02-02 |
| `100-11/` | Regierungsratsbeschluss betreffend die Bezeichnung des amtlichen Kantonswappens (SGS 100.11) | 1 | oldest version available, 1948-03-09 |
| `101/` | Vertrag über die Aufnahme des bernischen Amtsbezirks Laufen und seiner Gemeinden Blauen, Brislach, Burg im Leimen­tal, Dittingen, Duggin­gen, Grellingen, Laufen, Liesberg, Nenzlingen, Roggenburg, Röschenz, Wah­len, Zwingen in den Kanton Basel-Landschaft (SGS 101) | 1 | oldest version available, 1994-01-01 |
| `102/` | Vereinbarung über die Anpassung des Laufentalvertrages vom 10. Februar 1983 (SGS 102) | 1 | oldest version available, 1994-01-01 |
| `111-11/` | Anmeldungs- und Registerverordnung (SGS 111.11) | 1 | oldest version available, 2026-07-01 |
| `113-112/` | Vereinbarung über die Zusammenarbeit der Kantone Basel-Stadt und Basel-Landschaft bei der Erfassung von biometrischen Daten für Schweizerpässe (SGS 113.112) | 1 | oldest version available, 2020-07-01 |
| `131-1/` | Dekret zum Gesetz über die Organisation und die Geschäftsführung des Landrats (SGS 131.1) | 1 | oldest version available, 2026-01-01 |
| `131-2/` | Landratsbeschluss betreffend die Ausübung des Begnadigungsrechtes (SGS 131.2) | 1 | oldest version available, 1971-07-01 |
| `131-9/` | Vereinbarung über die Interparlamentarische Konferenz der Nordwestschweiz (SGS 131.9) | 1 | oldest version available, 2023-02-25 |
| `141-11/` | Geschäftsordnung des Regierungsrates (SGS 141.11) | 1 | oldest version available, 2021-07-01 |
| `142-11/` | Dienstordnung der Finanz- und Kirchendirektion (SGS 142.11) | 1 | oldest version available, 2026-04-01 |
| `143-12/` | Dienstordnung der Volkswirtschafts- und Gesundheitsdirektion (SGS 143.12) | 1 | oldest version available, 2026-06-01 |
| `144-12/` | Dienstordnung der Bau- und Umweltschutzdirektion (SGS 144.12) | 1 | oldest version available, 2026-01-01 |
| `144-211/` | Pflichtenheft für die Aufgaben des Amts für Orts- und Regionalplanung im Rahmen der Schulplanung (SGS 144.211) | 1 | oldest version available, 2022-01-01 |
| `144-221/` | Weisung über die Energiesparmassnahmen in der kantonalen Verwaltung (SGS 144.221) | 1 | oldest version available, 1978-01-01 |
| `145-11/` | Dienstordnung der Sicherheitsdirektion (SGS 145.11) | 1 | oldest version available, 2026-07-01 |
| `145-37/` | Vereinbarung über die interkantonalen Polizeieinsätze (SGS 145.37) | 1 | oldest version available, 2006-11-09 |
| `146-11/` | Dienstordnung der Bildungs-, Kultur- und Sportdirektion (SGS 146.11) | 1 | oldest version available, 2026-08-01 |
| `147-11/` | Dienstordnung der Landeskanzlei (SGS 147.11) | 1 | oldest version available, 2024-11-25 |
| `148-11/` | Übereinkommen zwischen dem Schweizerischen Bundesrat, der Regierung der Bundesrepublik Deutschland, der Regierung der französischen Republik und der Regierung des Grossherzogtums Luxemburg über die grenzüberschreitende Zusammenarbeit zwischen Gebietskörperschaften und örtlichen öffentlichen Stellen (SGS 148.11) | 1 | oldest version available, 2004-07-02 |
| `148-12/` | Vereinbarung zur Gründung des Oberrheinrates (SGS 148.12) | 1 | oldest version available, 1997-12-16 |
| `149-01/` | Vereinbarung zwischen dem Kanton Basel-Stadt und dem Kanton Basel-Landschaft über die Zusammenarbeit der Behörden (SGS 149.01) | 1 | oldest version available, 2012-01-01 |
| `149-5/` | Vereinbarung über die Organisation und die Führung der Regionalplanung beider Basel (SGS 149.5) | 1 | oldest version available, 2004-07-01 |
| `149-10/` | Vereinbarung über die Einsetzung einer gemeinsamen Ethikkommission Nordwest- und Zentralschweiz (SGS 149.10) | 1 | oldest version available, 2014-01-01 |
| `149-11/` | Interkantonale Vereinbarung über die hochspezialisierte Medizin (SGS 149.11) | 1 | oldest version available, 2009-01-01 |
| `149-21/` | Vereinbarung über die Konferenz der Kantonsregierungen (SGS 149.21) | 1 | oldest version available, 1993-10-08 |
| `149-41/` | Vereinbarung über die Nordwestschweizer Regierungskonferenz (SGS 149.41) | 1 | oldest version available, 2025-07-01 |
| `149-61/` | Vereinbarung über die Zusammenarbeit der Kantone Basel-Stadt und Basel-Landschaft in der projektorientierten Kunst- und Kulturförderung (SGS 149.61) | 1 | oldest version available, 2024-07-01 |
| `149-72/` | Interkantonale Vereinbarung über die Harmonisierung der Baubegriffe (SGS 149.72) | 1 | oldest version available, 2010-08-02 |
| `149-91/` | Rahmenvereinbarung für die interkantonale Zusammenarbeit mit Lastenausgleich (SGS 149.91) | 1 | oldest version available, 2007-05-11 |
| `149-95/` | Vereinbarung der Kantone Basel-Landschaft und Bern über den Vollzug der Bundesgesetzgebung über das Bergführerwesen und Anbieten weiterer Risikoaktivitäten (SGS 149.95) | 1 | oldest version available, 2014-01-01 |
| `150-1/` | Dekret zum Personalgesetz (SGS 150.1) | 1 | oldest version available, 2026-08-01 |
| `157-31/` | Weisung zur Gleichstellung von Frau und Mann in der kantonalen Verwaltung (SGS 157.31) | 1 | oldest version available, 2021-01-01 |
| `170-1/` | Dekret zum Gesetz über die Organisation der Gerichte (SGS 170.1) | 1 | oldest version available, 2026-04-01 |
| `170-112/` | Geschäfts- und Organisationsreglement der Gerichte des Kantons Basel-Landschaft (SGS 170.112) | 1 | oldest version available, 2023-02-01 |
| `178-112/` | Tarifordnung für die Anwältinnen und Anwälte (SGS 178.112) | 1 | oldest version available, 2014-01-01 |
| `180-12/` | Regierungsratsbeschluss betreffend die Wappen der basellandschaftlichen Gemeinden (SGS 180.12) | 1 | oldest version available, 1952-11-06 |
| `189-1/` | Dekret über die Umsetzung NFA und die Lastenverteilung auf Kanton und Gemeinden (SGS 189.1) | 1 | oldest version available, 2008-01-01 |
| `191-1/` | Kirchendekret (SGS 191.1) | 1 | oldest version available, 2007-01-01 |
| `191-2/` | Dekret über die Stiftung Kirchengut (SGS 191.2) | 1 | oldest version available, 2020-01-01 |
| `191-11/` | Regierungsratsbeschluss betreffend die Zugehörigkeit der Kantonseinwohner zu den drei Landeskirchen des Kantons Basel-Landschaft (SGS 191.11) | 1 | oldest version available, 1950-12-01 |
| `191-12/` | Regierungsratsbeschluss betreffend die Wahl der Pfarrer in den drei Landeskirchen des Kantons Basel-Landschaft (SGS 191.12) | 1 | oldest version available, 1957-07-23 |
| `192-111/` | Vereinbarung zwischen der Evangelisch-reformierten, der Römisch-katholischen und der Christkatholischen Landeskirche des Kantons Basel-Landschaft betreffend die Erhebung der Kirchensteuern bei konfessionell gemischten Familien und eingetragenen Partnerschaften (SGS 192.111) | 1 | oldest version available, 2007-01-01 |
| `194/` | Verfassung der Evangelisch-reformierten Kirche des Kantons Basel-Landschaft (SGS 194) | 1 | oldest version available, 2022-01-01 |
| `194-1/` | Konkordat betreffend die gemeinsame Ausbildung der evangelisch-reformierten Pfarrerinnen und Pfarrer und ihre Zulassung zum Kirchendienst (SGS 194.1) | 1 | oldest version available, 2004-01-01 |
| `195-1/` | Vereinigungs-Urkunde (SGS 195.1) | 1 | oldest version available, 1815-11-07 |
| `195-2/` | Übereinkunft wegen der Wiederherstel­lung und neuen Umschrei­bung des Bist­hums Basel (SGS 195.2) | 1 | oldest version available, 1828-03-26 |
| `195-3/` | Übereinkunft zwischen den hohen Ständen Lucern, Bern, Solothurn und Zug für die Organisation des Bisthums Basel (SGS 195.3) | 1 | oldest version available, 1828-03-26 |
| `195-4/` | Bulle des Papstes Leo XII. "Inter praecipua" vom 7. Mai 1828 betreffend Wiederherstellung und Reorganisation des Bistums Basel (SGS 195.4) | 1 | oldest version available, 1828-05-07 |
| `195-5/` | Beitritts-Erklärung zu dem neu organisirten Bisthum Basel (SGS 195.5) | 1 | oldest version available, 1829-10-06 |
| `195-6/` | Konkordat betreffend die Verhältnisse und Rechte des Staates in Kirchensachen (SGS 195.6) | 1 | oldest version available, 1834-05-30 |
| `196/` | Verfassung der Römisch-katholischen Landeskirche des Kantons Basel-Landschaft (SGS 196) | 1 | oldest version available, 2025-01-01 |
| `197/` | Verfassung der Christkatholischen Landeskirche des Kantons Basel-Landschaft (SGS 197) | 1 | oldest version available, 1984-01-01 |
| `211-1/` | Dekret über das Zivilstandswesen (SGS 211.1) | 1 | oldest version available, 2018-07-01 |
| `211-2/` | Vertrag über die BVG- und Stiftungsaufsicht beider Basel (SGS 211.2) | 1 | oldest version available, 2012-01-01 |
| `211-5/` | Dekret über die Kostentragung der amtlichen Vermessung (SGS 211.5) | 1 | oldest version available, 2013-01-01 |
| `211-201/` | Ordnung über die Stiftungsaufsicht (SGS 211.201) | 1 | oldest version available, 2023-01-01 |
| `211-501/` | Vertrag zwischen dem Bund und den Kantonen betreffend der Abgeltung und der Modalitäten des Austauschs von Geobasisdaten des Bundesrechts unter Behörden (SGS 211.501) | 1 | oldest version available, 2016-10-01 |
| `212-31/` | Normalarbeitsvertrag für landwirtschaftliche Arbeitsverhältnisse im Kanton Basel-Landschaft (SGS 212.31) | 1 | oldest version available, 2020-01-01 |
| `212-35/` | Normalarbeitsvertrag für die wohngemeinschaftliche Betreuung (SGS 212.35) | 1 | oldest version available, 2025-01-01 |
| `221/` | Einführungsgesetz zur Schweizerischen Zivilprozessordnung (SGS 221) | 1 | oldest version available, 2025-08-01 |
| `221-2/` | Dekret zum Bundesgesetz betreffend die Arbeit in den Fabriken vom 18. Juni 1914 (SGS 221.2) | 1 | oldest version available, 2011-01-01 |
| `233-1/` | Konkordat über die Gewährung gegenseitiger Rechtshilfe zur Vollstreckung öffentlichrechtlicher Ansprüche (SGS 233.1) | 1 | oldest version available, 1979-01-01 |
| `242/` | Einführungsgesetz zur Schweizerischen Jugendstrafprozessordnung (SGS 242) | 1 | oldest version available, 2022-01-01 |
| `250/` | Einführungsgesetz zur Schweizerischen Strafprozessordnung (SGS 250) | 1 | oldest version available, 2022-01-01 |
| `250-1/` | Dekret zum Einführungsgesetz zur Schweizerischen Strafprozessordnung (SGS 250.1) | 1 | oldest version available, 2024-01-01 |
| `252-111/` | Vertrag über die Opferberatungsstellen beider Basel (SGS 252.111) | 1 | oldest version available, 2009-01-01 |
| `261-2/` | Konkordat der Kantone der Nordwest- und Innerschweiz über den Vollzug von Strafen und Massnahmen (SGS 261.2) | 1 | oldest version available, 2008-01-01 |
| `265-111/` | Übereinkunft betreffend die Polizeitransporte (SGS 265.111) | 1 | oldest version available, 1980-01-01 |
| `271/` | Gesetz über die Verfassungs- und Verwaltungsprozessordnung (SGS 271) | 1 | oldest version available, 2024-01-01 |
| `311-111/` | Pflichtenheft des Begleitausschusses Finanzkontrolle (SGS 311.111) | 1 | oldest version available, 2019-09-25 |
| `331-1/` | Dekret zum Steuergesetz (SGS 331.1) | 1 | oldest version available, 2011-04-01 |
| `331-2/` | Dekret über den Steuerfuss (SGS 331.2) | 1 | oldest version available, 2026-01-01 |
| `331-15/` | Regierungsratsbeschluss über die pauschale Steueranrechnung (SGS 331.15) | 1 | oldest version available, 2005-01-01 |
| `331-19/` | Vereinbarung zwischen dem Schweizerischen Bundesrat und der Regierung der Französischen Republik über die Besteuerung der Erwerbseinkünfte von Grenzgängern (SGS 331.19) | 1 | oldest version available, 1986-12-18 |
| `336-3/` | Dekret zum Bundesgesetz über die Verrechnungssteuer (SGS 336.3) | 1 | oldest version available, 2011-07-01 |
| `338-1/` | Konkordat zwischen den Kantonen der Schweizerischen Eidgenossenschaft über den Ausschluss von Steuerabkommen (SGS 338.1) | 1 | oldest version available, 1949-10-06 |
| `338-11/` | Gegenrechtsvereinbarungen über die Steuerbefreiung für Zuwendungen an gemeinnützige und wohltätige Einrichtungen (SGS 338.11) | 1 | oldest version available, 2008-05-26 |
| `350-1/` | Dekret zum Gebäudeversicherungsgesetz Basel-Landschaft (SGS 350.1) | 1 | oldest version available, 2023-01-01 |
| `361-12/` | Vereinbarung über Beiträge an das Ausbildungszentrum für das Strafvollzugspersonal (SGS 361.12) | 1 | oldest version available, 1980-12-18 |
| `362-1/` | Dekret über die Einkommensobergrenzen und den Prozentanteil in der Prämienverbilligung (SGS 362.1) | 1 | oldest version available, 2014-01-01 |
| `365-13/` | Interkantonale Vereinbarung zur Harmonisierung von Ausbildungsbeiträgen (SGS 365.13) | 1 | oldest version available, 2013-03-01 |
| `365-511/` | Weisung über die Staatsbeiträge an die Fortbildungskurse für Lehrer an den basellandschaftlichen Volksschulen und Kindergärten (SGS 365.511) | 1 | oldest version available, 1987-02-10 |
| `365-515/` | Vereinbarung über die Abgeltung der unterrichtsbezogenen Dienst­leistungen zugunsten der Schulen des Kantons Basel-Landschaft (SGS 365.515) | 1 | oldest version available, 1994-01-01 |
| `366-15/` | Vertrag zwischen den Kantonen Basel-Landschaft und Basel-Stadt über die Abgeltung kultureller Zentrumsleistungen (SGS 366.15) | 1 | oldest version available, 2022-01-01 |
| `371-1/` | Dekret über die Festsetzung des Zertifikats- und Dotationskapitals der Basellandschaftlichen Kantonalbank (SGS 371.1) | 1 | oldest version available, 2008-11-01 |
| `381-2/` | Vertrag zwischen dem Kanton Basel-Landschaft und der Schweizer Salinen AG über die Rechte an den Salzlagern und Solen im Kanton Basel-Landschaft (SGS 381.2) | 1 | oldest version available, 2026-01-01 |
| `381-3/` | Zusatzprotokoll zum Konzessionsvertrag vom 30. Oktober 1962 / 29. März 1963 (SGS 381.3) | 1 | oldest version available, 1963-03-29 |
| `381-4/` | Zusatz zum Konzessionsvertrag (SGS 381.4) | 1 | oldest version available, 1976-01-01 |
| `381-6/` | Zusatz zum Konzessionsvertrag (SGS 381.6) | 1 | oldest version available, 1989-03-09 |
| `381-21/` | Regierungsratsbeschluss betreffend die Verschmelzung der Saline Schweizerhalle mit den Aargauischen Salinen Rheinfelden und Ryburg (SGS 381.21) | 1 | oldest version available, 1909-06-16 |
| `381-51/` | Regierungsratsbeschluss betreffend Schürfkonzession (SGS 381.51) | 1 | oldest version available, 1974-09-03 |
| `382-1/` | Dekret zum Gesetz vom 7. Juni 1971 über das Salzregal (SGS 382.1) | 1 | oldest version available, 2015-01-01 |
| `382-2/` | Interkantonale Vereinbarung über den Salzverkauf in der Schweiz (SGS 382.2) | 1 | oldest version available, 1975-10-01 |
| `382-11/` | Regierungsratsbeschluss betreffend die Festsetzung der Salzverkaufspreise (SGS 382.11) | 1 | oldest version available, 1973-05-15 |
| `386-1/` | Konzession zum Bau und Betrieb einer Eisenbahn von Liestal nach Waldenburg eventuell Langenbruck (SGS 386.1) | 1 | oldest version available, 1870-04-19 |
| `386-2/` | Landratsbeschluss betreffend die Benützung von Strassenterrain zum Bau und Betrieb einer Birsigtalbahn (SGS 386.2) | 1 | oldest version available, 1975-01-01 |
| `386-3/` | Landratsbeschluss betreffend Erteilung einer Bewilligung zur Benutzung öffentlicher Strassen an die BLT Baselland Transport AG für den Betrieb der Linie 10 (SGS 386.3) | 1 | oldest version available, 1980-06-29 |
| `386-4/` | Landratsbeschluss betreffend Erteilung einer Bewilligung zur Benützung öffentlicher Strassen an die BLT Baselland Transport AG für den Betrieb der Linie 11, Basel – Reinach – Aesch (SGS 386.4) | 1 | oldest version available, 1984-01-01 |
| `386-5/` | Landratsbeschluss betreffend Benützung von Strassenterrain zum Bau und Betrieb der basellandschaftlichen Überlandbahn Strecke St. Jakob–Muttenz (SGS 386.5) | 1 | oldest version available, 1975-01-01 |
| `386-6/` | Landratsbeschluss betreffend Erteilung der Bewilligung zur Benützung öffentlicher Strassen an den Kanton Basel-Stadt für den Betrieb von Stras­senbah­nen (SGS 386.6) | 1 | oldest version available, 1971-07-01 |
| `402/` | Regierungsratsbeschluss betreffend Bauten und Anlagen mit besonders starker Verkehrserzeugung (SGS 402) | 1 | oldest version available, 1974-03-12 |
| `420/` | Einführungsgesetz zur interkantonalen Vereinbarung über das öffentliche Beschaffungswesen (SGS 420) | 1 | oldest version available, 2024-01-01 |
| `420-001/` | Pflichtenheft des Beirats für das öffentliche Beschaffungswesen (SGS 420.001) | 1 | oldest version available, 2024-01-01 |
| `420-12/` | Interkantonale Vereinbarung über das öffentliche Beschaffungswesen (SGS 420.12) | 1 | oldest version available, 2003-01-01 |
| `420-121/` | Interkantonale Vereinbarung über das öffentliche Beschaffungswesen (SGS 420.121) | 1 | oldest version available, 2021-07-01 |
| `421-1/` | Staatsvertrag über die Zusammenlegung der Rheinschifffahrtsdirektion Basel und der Rheinhäfen des Kantons Basel-Landschaft zu einer Anstalt öffentlichen Rechts mit eigener Rechtspersönlichkeit unter dem Namen «Schweizerische Rheinhäfen» («Ports Rhénans Suisses», «Swiss Rhine Ports») (SGS 421.1) | 1 | oldest version available, 2008-01-01 |
| `421-13/` | Hafenordnung für die Rheinhäfen beider Basel (SGS 421.13) | 1 | oldest version available, 2011-01-01 |
| `421-17/` | Gebührentarif der Schweizerischen Rheinhäfen (SGS 421.17) | 1 | oldest version available, 2017-01-01 |
| `437/` | Regierungsratsbeschluss betreffend Gebührenerhebung für Sondertransporte (SGS 437) | 1 | oldest version available, 1976-07-01 |
| `454-1/` | Dekret über die Gebühren für Gewässernutzungen (SGS 454.1) | 1 | oldest version available, 2005-01-01 |
| `456/` | Landratsbeschluss betreffend die Fortleitung von Frischwasser aus der Hard (erste Etappe) Genehmigung des generellen Projektes (SGS 456) | 1 | oldest version available, 1961-05-18 |
| `480-1/` | Vereinbarung über die Basler Verkehrs-Betriebe und die BLT Baselland Transport AG (SGS 480.1) | 1 | oldest version available, 1995-01-01 |
| `480-111/` | Vereinbarung über die Beitragsleistung an Fahrten von mobilitätseingeschränkten Personen (SGS 480.111) | 1 | oldest version available, 2016-01-01 |
| `481-5/` | Vereinbarung betreffend die Motorfahrzeugprüfstation beider Basel (SGS 481.5) | 1 | oldest version available, 1979-01-09 |
| `481-51/` | Vereinbarung über die Gebühren der Motorfahrzeugprüfstation beider Basel (SGS 481.51) | 1 | oldest version available, 2024-10-01 |
| `481-52/` | Vereinbarung zwischen den Kantonen Basel-Stadt, Basel-Landschaft und Aargau über die Durchführung der amtlichen Nachkontrollen von Fahrzeugen (SGS 481.52) | 1 | oldest version available, 1997-07-01 |
| `483-1/` | Dekret über das Angebot im regionalen Personenverkehr (SGS 483.1) | 1 | oldest version available, 2020-10-02 |
| `486-1/` | Dekret betreffend die kantonale Zuständigkeitsordnung zum Eidg. Luftfahrtgesetz (SGS 486.1) | 1 | oldest version available, 2015-01-01 |
| `486-21/` | Vereinbarung betreffend Zusammenarbeit bei der Wahrung der schweizerischen Interessen auf dem binationalen Flughafen Basel-Mülhausen (SGS 486.21) | 1 | oldest version available, 1998-06-11 |
| `486-31/` | Vereinbarung zwischen den Kantonen Basel-Stadt und Basel-Landschaft über die Fluglärmkommission und die Ombudsstelle für Fluglärmklagen (SGS 486.31) | 1 | oldest version available, 2011-07-01 |
| `487/` | Interkantonale Vereinbarung zwischen den Kantonen Basel-Stadt, Basel-Landschaft und Aargau in Rheinschiffahrts- und Hafenangelegenheiten (SGS 487) | 1 | oldest version available, 1997-01-01 |
| `490-1/` | Dekret zum Energiegesetz (SGS 490.1) | 1 | oldest version available, 2024-10-01 |
| `493/` | Verleihung für die Errichtung einer Wasserkraftanlage im Rhein bei Birsfelden (SGS 493) | 1 | oldest version available, 1951-01-01 |
| `493-1/` | Verleihung für die Erweiterung der Wassernutzung des Rheins beim Kraftwerk Birsfelden (SGS 493.1) | 1 | oldest version available, 1963-05-15 |
| `493-21/` | Vertrag zwischen dem Kanton Basel-Landschaft und dem Kanton Basel-Stadt betreffend Gründung einer Aktiengesellschaft zum Bau und Betrieb einer Wasserkraftanlage bei Birsfelden (SGS 493.21) | 1 | oldest version available, 1950-09-01 |
| `494/` | Vereinbarung zwischen den Kantonen Basel-Landschaft (BL) und Basel-Stadt (BS) betreffend die Berechnung des Wasserzinses des Kraftwerkes Augst an den Kanton BL und des Wasserzinses des Kraftwerks Birsfelden an die Kantone BS und BL (SGS 494) | 1 | oldest version available, 1973-10-16 |
| `495/` | Regierungsratsbeschluss betreffend Vollzug des Artikels 44 des Bundesgesetzes betreffend die elektrischen Schwach- und Starkstromanlagen (SGS 495) | 1 | oldest version available, 1903-02-01 |
| `510-13/` | Vereinbarung zwischen dem Kanton Basel-Landschaft und dem Kanton Basel-Stadt betreffend den Vollzug des eidgenössischen Landwirtschaftsrechtes (SGS 510.13) | 1 | oldest version available, 2020-01-01 |
| `515-12/` | Weisungen des Regierungsrates betreffend Schätzungen und Bewertungen sowie Restkostenverteilung bei Felderregulierungen (Gesamtmeliorationen) (SGS 515.12) | 1 | oldest version available, 2013-07-01 |
| `516-34/` | Vereinbarung über die Zusammenarbeit zwischen dem Kanton Solothurn und dem Kanton Basel-Landschaft betreffend den Vollzug von Massnahmen im Rebbau (SGS 516.34) | 1 | oldest version available, 2008-01-01 |
| `523-12/` | Regierungsratsbeschluss betreffend die Reservationsgebiete in der Gemeinde Augst, Zone Kraftwerk-Stausee und Ergolz (SGS 523.12) | 1 | oldest version available, 1960-01-12 |
| `523-13/` | Regierungsratsbeschluss betreffend Natur-, Jagd- und Vogelschutzreservat im Rutschgebiet unter der Fluh (Parzelle 988 im Büchlihau), Gemeinde Füllinsdorf (SGS 523.13) | 1 | oldest version available, 1960-02-16 |
| `523-14/` | Regierungsratsbeschluss betreffend Schaffung eines Vogelschutzreservates in der Gemeinde Muttenz (SGS 523.14) | 1 | oldest version available, 1960-03-01 |
| `523-15/` | Regierungsratsbeschluss betreffend Schaffung eines Naturschutzreservates an der Birs in der Gemeinde Münchenstein (SGS 523.15) | 1 | oldest version available, 1960-03-22 |
| `530-5/` | Übereinkunft betreffend die Ausübung des Fischfanges in den interkantonalen Fischgewässern von Holderbank (Kanton Solothurn) und Langen­bruck (Kanton Basel-Landschaft), dem Augstbach und dem Musbächlein, abgeschlossen zwischen dem Regierungsrat des Kantons Solothurn und dem Regierungsrat des Kan­tons Basel-Land­schaft (SGS 530.5) | 1 | oldest version available, 1963-05-01 |
| `543-3/` | Interkantonale Vereinbarung betreffend die gemeinsame Durchführung von Geldspielen (SGS 543.3) | 1 | oldest version available, 2021-01-01 |
| `543-4/` | Gesamtschweizerisches Geldspielkonkordat (SGS 543.4) | 1 | oldest version available, 2021-01-01 |
| `543-41/` | Zusatzvereinbarung zur Interkantonalen Vereinbarung über die Aufsicht sowie die Bewilligung und Ertragsverwendung von interkantonal oder gesamtschweizerisch durchgeführten Lotterien und Wetten vom 7.1.2005 (IVLW) (SGS 543.41) | 1 | oldest version available, 2019-02-01 |
| `546-112/` | Taxi-Tarifordnung (SGS 546.112) | 1 | oldest version available, 2009-01-01 |
| `562-1/` | Dekret betreffend das Verfahren bei Gewährleistung im Viehhandel (SGS 562.1) | 1 | oldest version available, 2011-01-01 |
| `562-3/` | Interkantonale Vereinbarung zum Abbau technischer Handelshemmnisse (SGS 562.3) | 1 | oldest version available, 2003-02-04 |
| `566-1/` | Dekret über explosionsgefährliche Stoffe (SGS 566.1) | 1 | oldest version available, 2015-01-01 |
| `570-1/` | Dekret über die Bewilligung für Veranstaltungen im Wald (SGS 570.1) | 1 | oldest version available, 1999-01-01 |
| `571-12/` | Vereinbarung über das Amt für Wald und Wild beider Basel (AfWW beider Basel) (SGS 571.12) | 1 | oldest version available, 2025-01-01 |
| `601-115/` | Tarifordnung Archäologie und Museum Basel-Landschaft (SGS 601.115) | 1 | oldest version available, 2013-01-01 |
| `601-116/` | Tarifordnung Römerstadt Augusta Raurica (SGS 601.116) | 1 | oldest version available, 2013-01-01 |
| `604-111/` | Tarifordnung für die Kantonsbibliothek Baselland (SGS 604.111) | 1 | oldest version available, 2024-10-08 |
| `615-111/` | Vereinbarung über eine gemeinsame Tierversuchskommission der Kantone Basel-Stadt, Basel-Landschaft und Aargau (SGS 615.111) | 1 | oldest version available, 1998-01-01 |
| `640-111/` | Lehrpläne der Schulen des Kantons Basel-Landschaft (SGS 640.111) | 1 | oldest version available, 2002-09-18 |
| `642-1/` | Dekret über die Sekundarschulkreise und Sekundarschulstandorte (SGS 642.1) | 1 | oldest version available, 2024-08-01 |
| `643-12/` | Vertrag über das Regionale Gymnasium Laufental-Thierstein (SGS 643.12) | 1 | oldest version available, 2014-08-01 |
| `645-1/` | Dekret über die Unterstellung der nicht mehr schulpflichtigen Schüler und Lehrlinge unter den gesundheitlichen Dienst (SGS 645.1) | 1 | oldest version available, 1997-08-11 |
| `649-1/` | Konkordat über die Schulkoordination (SGS 649.1) | 1 | oldest version available, 1970-12-14 |
| `649-2/` | Regionales Schulabkommen über die gegenseitige Aufnahme von Auszubildenden und Ausrichtung von Beiträgen (SGS 649.2) | 1 | oldest version available, 2026-08-01 |
| `649-6/` | Interregionale Vereinbarung über Beiträge an ausseruniversitäre Bildungsanstalten im tertiären Bereich (SGS 649.6) | 1 | oldest version available, 1994-08-01 |
| `649-7/` | Interkantonale Vereinbarung über die Anerkennung von Ausbildungsabschlüssen (SGS 649.7) | 1 | oldest version available, 2014-09-01 |
| `649-11/` | Interkantonale Vereinbarung über die Harmonisierung der obligatorischen Schule (SGS 649.11) | 1 | oldest version available, 2010-09-26 |
| `649-12/` | Interkantonale Vereinbarung über die Zusammenarbeit im Bereich der Sonderpädagogik (SGS 649.12) | 1 | oldest version available, 2011-01-01 |
| `649-22/` | Vertrag zwischen den Kantonen Aargau, Basel-Landschaft, Basel-Stadt und Solothurn über die Fachhochschule Nordwestschweiz (FHNW) (SGS 649.22) | 1 | oldest version available, 2012-01-01 |
| `649-71/` | Gebührenverordnung der Schweizerischen Konferenz der kantonalen Gesundheitsdirektorinnen und -direktoren (GDK) (SGS 649.71) | 1 | oldest version available, 2009-05-14 |
| `649-222/` | Vereinbarung zwischen den Kantonen Basel-Landschaft und Basel-Stadt über die Trennung der bikantonalen Verantwortung für die Rentnerinnen und Rentner der ehemaligen Fachhochschule beider Basel (FHBB) und der ehemaligen Hochschule für Pädagogik und Soziale Arbeit beider Basel (HPSA-BB) im Rahmen der Anschlussverhältnisse zur Basellandschaftlichen Pensionskasse (BLPK) und der Anschlussverträge zur Pensionskasse Basel-Stadt (PKBS) (SGS 649.222) | 1 | oldest version available, 2011-01-01 |
| `649-611/` | Interkantonale Fachschulvereinbarung (SGS 649.611) | 1 | oldest version available, 2000-08-01 |
| `649-612/` | Interkantonale Vereinbarung über Beiträge an die Bildungsgänge der höheren Fachschulen (SGS 649.612) | 1 | oldest version available, 2014-01-01 |
| `649-711/` | Anerkennungsreglemente der Schweizerischen Konferenz der kantonalen Erziehungsdirektoren (EDK) (SGS 649.711) | 1 | oldest version available, 2012-09-01 |
| `649-911/` | Vereinbarung zwischen der Erziehungs- und Kulturdirektion des Kantons Basel-Landschaft und dem Erziehungsdepartement des Kantons Jura über den Besuch des fremdsprachigen zehnten Schuljahres durch Schülerinnen und Schüler aus den Vereinbarungskantonen (SGS 649.911) | 1 | oldest version available, 2001-08-01 |
| `649-912/` | Vereinbarung zwischen dem Kanton Basel-Landschaft und dem Kanton Jura über den gemeinsamen gymnasialen bilingualen Bildungsgang am Regionalen Gymnasium Laufental-Thierstein in Laufen und am Lycée cantonal in Porrentruy (SGS 649.912) | 1 | oldest version available, 2017-08-01 |
| `660-1/` | Interkantonale Vereinbarung über den schweizerischen Hochschulbereich (SGS 660.1) | 1 | oldest version available, 2015-01-01 |
| `662-2/` | Interkantonale Fachhochschulvereinbarung (FHV) ab 2005 (SGS 662.2) | 1 | oldest version available, 2005-10-01 |
| `662-5/` | Dekret über die Arbeitsverhältnisse der Fachhochschulen (SGS 662.5) | 1 | oldest version available, 2004-02-01 |
| `664-1/` | Vertrag zwischen den Kantonen Basel-Landschaft und Basel-Stadt über die gemeinsame Trägerschaft der Universität Basel (SGS 664.1) | 1 | oldest version available, 2022-01-01 |
| `664-3/` | Interkantonale Vereinbarung über die Beiträge an die Ausbildungskosten von universitären Hochschulen (SGS 664.3) | 1 | oldest version available, 2022-01-01 |
| `664-12/` | Vereinbarung über das Immobilienwesen der Universität Basel (SGS 664.12) | 1 | oldest version available, 2022-01-01 |
| `664-155/` | Stiftungsstatut der Stiftung Volkshochschule und Senioren-Universität beider Basel (VHS BB) (SGS 664.155) | 1 | oldest version available, 2002-09-25 |
| `665-1/` | Vertrag zwischen den Kantonen Basel-Landschaft und Basel-Stadt über die gemeinsame Trägerschaft des Schweizerischen Tropen- und Public Health-Instituts (SGS 665.1) | 1 | oldest version available, 2017-01-01 |
| `681-22/` | Interkantonale Vereinbarung über die Beiträge an die Ausbildungskosten in der beruflichen Grundbildung (SGS 681.22) | 1 | oldest version available, 2007-08-01 |
| `683-21/` | Vertrag zwischen dem Kaufmännischen Verband Baselland und dem Kanton Basel-Landschaft über die Führung der Schulen des Kaufmännischen Verbands Baselland (SGS 683.21) | 1 | oldest version available, 2023-01-01 |
| `684-12/` | Vertrag zwischen aprentas und dem Kanton Basel-Landschaft über die Führung einer Berufsfachschule (SGS 684.12) | 1 | oldest version available, 2014-07-01 |
| `687-14/` | Vertrag zwischen den Kantonen Basel-Landschaft und Basel-Stadt über die Abgeltung der Kosten der nichtakademischen Berufsausbildungen im Gesundheitswesen auf Sekundarstufe II und auf Tertiärstufe (SGS 687.14) | 1 | oldest version available, 2005-01-01 |
| `687-20/` | Regionales Schulabkommen über die Finanzierung der Aus- und Weiterbildung für Gesundheitsberufe (SGS 687.20) | 1 | oldest version available, 2001-01-01 |
| `700-12/` | Konkordat über die polizeiliche Zusammenarbeit in der Nordwestschweiz (SGS 700.12) | 1 | oldest version available, 1996-05-15 |
| `700-13/` | Konkordat über Errichtung und Betrieb einer interkantonalen Polizeischule Hitzkirch (SGS 700.13) | 1 | oldest version available, 2004-12-08 |
| `700-14/` | Interkantonale Vereinbarung (bzw. Konkordat) über die computergestützte Zusammenarbeit der Kantone bei der Aufklärung von Gewaltdelikten (SGS 700.14) | 1 | oldest version available, 2011-07-01 |
| `700-15/` | Vereinbarung zur Harmonisierung der Polizeiinformatik in der Schweiz (SGS 700.15) | 1 | oldest version available, 2012-05-31 |
| `700-16/` | Interkantonale bzw. interbehördliche Vereinbarung über den Datenaustausch zum Betrieb von Lage- und Analysesystemen im Bereich der seriellen Kriminalität (SGS 700.16) | 1 | oldest version available, 2019-12-11 |
| `700-17/` | Vereinbarung zwischen dem Bund und den Kantonen über die Harmonisierung und die gemeinsame Bereitstellung der Polizeitechnik und -informatik in der Schweiz (SGS 700.17) | 1 | oldest version available, 2021-01-01 |
| `700-18/` | Vereinbarung zwischen den Kantonen und dem Bund über die Harmonisierung der Informatik in der Strafjustiz (SGS 700.18) | 1 | oldest version available, 2025-07-01 |
| `702-14/` | Konkordat über Massnahmen gegen Gewalt anlässlich von Sportveranstaltungen (SGS 702.14) | 1 | oldest version available, 2010-01-01 |
| `719-1/` | Vereinbarung über die Polizeitätigkeit auf der Autobahn N 2 (SGS 719.1) | 1 | oldest version available, 1986-01-01 |
| `719-21/` | Vereinbarung zwischen den Kantonen Basel-Landschaft und Aargau über die Polizeitätigkeit auf den Autobahnen A2 und A3 (SGS 719.21) | 1 | oldest version available, 1996-11-01 |
| `719-31/` | Vereinbarung über die grenzüberschreitende polizeiliche Zusammenarbeit in den Kantonen Basel-Stadt und Basel-Landschaft (SGS 719.31) | 1 | oldest version available, 2018-01-01 |
| `719-411/` | Vereinbarung über die Bikantonale Geschäftsstelle Eventverkehr St. Jakob (SGS 719.411) | 1 | oldest version available, 2022-06-14 |
| `761-1/` | Dekret über die Sorgfaltspflicht bei Feuerungsanlagen (SGS 761.1) | 1 | oldest version available, 2018-01-01 |
| `782-2/` | Dekret über den Generellen Entwässerungsplan (SGS 782.2) | 1 | oldest version available, 1997-01-01 |
| `783-21/` | Vertrag über die Ableitung der Abwässer des basellandschaftlichen Gebietes von Olsberg, Gemeinde Arisdorf, in die Abwasserreinigungsanlage Olsberg AG (SGS 783.21) | 1 | oldest version available, 1971-12-17 |
| `783-22/` | Vereinbarung über die Durchleitung von Abwässern aus den basellandschaftlichen Gemeinden Arisdorf, Giebenach und Augst durch die aargauische Gemeinde Kaiseraugst sowie die Ableitung der Abwässer der Gemeinde Kaiseraugst in die basellandschaftliche Abwasserreinigungsanlage (ARA) Rhein, Pratteln (SGS 783.22) | 1 | oldest version available, 1988-09-21 |
| `783-31/` | Vertrag zwischen dem Kanton Basel-Stadt und dem Kanton Basel-Landschaft betreffend die gemeinsame Durchführung von Gewässer­schutzmassnahmen (SGS 783.31) | 1 | oldest version available, 1975-09-02 |
| `783-32/` | Vertrag zwischen 1. Kanton Basel-Stadt, vertreten durch den Regierungsrat, der Regierungsrat gleichzeitig handelnd für die Einwohnergemeinde der Stadt Basel; 2. Kanton Basel-Landschaft, vertreten durch den Regierungsrat; 3. Ciba-Geigy AG, in Basel; 4. F. Hoffmann-La Roche & Co. AG, in Basel; 5. Sandoz AG, in Basel; betreffend gemeinsame Durchführung von Gewässerschutzmassnahmen (SGS 783.32) | 1 | oldest version available, 1980-09-01 |
| `783-33/` | Vertrag betreffend den gemeinsamen Betrieb von Abwasserreinigungsanlagen (SGS 783.33) | 1 | oldest version available, 2007-01-01 |
| `783-51/` | Vereinbarung über die Ableitung von Abwässern aus den Gemeinden Hofstetten-Flüh, Metzerlen-Mariastein (nur Dorfteil Mariastein), Bättwil und Witterswil des Abwasserverbandes Leimental SO in die neue Abwasserreinigungsanlage Birsig in Therwil. (SGS 783.51) | 1 | oldest version available, 1991-12-03 |
| `783-52/` | Vertrag zwischen dem Kanton Basel-Landschaft, vertreten durch den Regierungsrat, und der Einwohnergemeinde Holderbank (SO), vertreten durch den Gemeinderat, über die gemeinsame Durchführung der Abwassersanierung für Langenbruck (BL) und Holderbank (SO) (SGS 783.52) | 1 | oldest version available, 1977-10-17 |
| `783-53/` | Vertrag über die Ableitung der Abwässer der Einwohnergemeinde Dornach und deren Reinigung in den basellandschaftlichen Abwasserreinigungsanlagen Birs 1 und Birs 2 (ARA Birs 1 und ARA Birs 2) (SGS 783.53) | 1 | oldest version available, 2004-01-01 |
| `783-54/` | Vertrag über die Ableitung der Abwässer der Einwohnergemeinde Gempen und deren Reinigung in den basellandschaftlichen Abwasserreinigungsanlagen Birs 1 und Birs 2 (ARA Birs 1 und ARA Birs 2) (SGS 783.54) | 1 | oldest version available, 2004-01-01 |
| `783-55/` | Vertrag über die Ableitung der Abwässer der Einwohnergemeinde Hochwald und deren Reinigung in den basellandschaftlichen Abwasserreinigungsanlagen Birs 1 und Birs 2 (SGS 783.55) | 1 | oldest version available, 2004-01-01 |
| `783-56/` | Vertrag über die Ableitung der Abwässer der Einwohnergemeinde Nuglar-St. Pantaleon (Ortsteile St. Pantaleon, Neu-Nuglar und Orismühle) und deren Reinigung in der basellandschaftlichen Abwasserreinigungsanlage Ergolz 2 (ARA Ergolz 2) (SGS 783.56) | 1 | oldest version available, 2006-01-01 |
| `784-9/` | Vereinbarung zwischen den Kantonen Basel-Stadt und Basel-Landschaft über die Annahme von Abfällen in der Kehrichtverwertungsanlage Basel und der Deponie Elbisgraben (SGS 784.9) | 1 | oldest version available, 2019-10-01 |
| `786-131/` | Vereinbarung über die Kontrolle der Industriefeuerungen (SGS 786.131) | 1 | oldest version available, 1988-02-24 |
| `791-21/` | Regierungsratsbeschluss betreffend die Anlegung und Inventarisierung von lokalen Sammlun­gen von Altertümern durch Gemeinden, öffent­lich-rechtliche Korpora­tio­nen, wissen­schaftliche Vereini­gungen und private Personen (SGS 791.21) | 1 | oldest version available, 1937-10-02 |
| `792-1/` | Vertrag über die Römerstadt Augusta Raurica (SGS 792.1) | 1 | oldest version available, 2026-01-01 |
| `822-12/` | Weisungen betreffend die Beschäftigung von Jugendlichen unter 15 Jahren für Arbeiten im Walde (SGS 822.12) | 1 | oldest version available, 1967-09-12 |
| `824-1/` | Dekret zum Bundesgesetz über die Heimarbeit (SGS 824.1) | 1 | oldest version available, 2011-01-01 |
| `834-1/` | Dekret über die berufliche Vorsorge durch die Basellandschaftliche Pensionskasse (SGS 834.1) | 1 | oldest version available, 2019-01-01 |
| `834-3/` | Dekret über die berufliche Vorsorge für Mitglieder des Regierungsrates und über die Lohnleistungen beim Ausscheiden aus dem Amt (SGS 834.3) | 1 | oldest version available, 2015-01-01 |
| `834-400/` | Ordnung über die berufliche Vorsorge (SGS 834.400) | 1 | oldest version available, 2025-07-01 |
| `836-1/` | Dekret zum Bundesgesetz über die Unfallversicherung (SGS 836.1) | 1 | oldest version available, 2015-01-01 |
| `837-31/` | Vereinbarung der Kantone Basel-Landschaft und Solothurn über die Abtretung von Aufgaben aus dem AVIG-Vollzug vom Kanton Solothurn an den Kanton Basel-Landschaft (SGS 837.31) | 1 | oldest version available, 2004-01-01 |
| `853-111/` | Vertrag zwischen den Kantonen Basel-Landschaft und Basel-Stadt über die Nutzung und Abgeltung ambulanter Angebote der Behindertenhilfe und allfälliger Folgekosten (SGS 853.111) | 1 | oldest version available, 2017-01-01 |
| `855-2/` | Interkantonale Vereinbarung für soziale Einrichtungen (SGS 855.2) | 1 | oldest version available, 2020-06-01 |
| `901-12/` | Regierungsratsbeschluss betreffend Ruhegehalt der Hebammen (SGS 901.12) | 1 | oldest version available, 1959-04-07 |
| `902-121/` | Weisung zu den nicht subventionsberechtigten konservierenden Behandlungen (Negativliste) in der Kinder- und Jugendzahnpflege (SGS 902.121) | 1 | oldest version available, 1997-08-11 |
| `904-12/` | Vertrag über die Kremation von Leichen aus dem Kanton Basel-Landschaft und die Abdankung im Krematorium der Stadt Basel (SGS 904.12) | 1 | oldest version available, 1975-01-28 |
| `906-111/` | Vereinbarung zwischen dem Kanton Basel-Stadt und dem Kanton Basel-Landschaft über das Krebsregister beider Basel (SGS 906.111) | 1 | oldest version available, 2019-01-01 |
| `915-111/` | Vereinbarung über die Zusammenarbeit der Kantone Basel-Stadt und Basel-Landschaft bei der Gewährung von Ausbildungsbeiträgen im Pflegebereich (SGS 915.111) | 1 | oldest version available, 2024-10-22 |
| `921-91/` | Vertrag zwischen der Rennbahnklinik in Muttenz und dem Ver­band Basellandschaftlicher Krankenkassen (SGS 921.91) | 1 | oldest version available, 1981-07-01 |
| `923/` | Regierungsratsbeschluss betreffend die Tarife der ärzt­lichen Leistungen und der Arzneien für die Behandlung der bei der Schweizerischen Unfallversicherungs­anstalt Versicherten (SGS 923) | 1 | oldest version available, 1916-09-14 |
| `923-11/` | Vereinbarung über den Taxpunktwert (SGS 923.11) | 1 | oldest version available, 1982-10-01 |
| `926-21/` | Vereinbarung über den Taxpunktwert (SGS 926.21) | 1 | oldest version available, 2000-01-01 |
| `928-11/` | Vertrag zwischen der Schweizerischen Zahnärzte-Gesellschaft und der Union Schweizerischer Krankenkassenverbände (SGS 928.11) | 1 | oldest version available, 1979-01-01 |
| `928-13/` | Vereinbarung zwischen der Schweizerischen Zahnärztegesellschaft (SSO) und dem Konkordat der Schweizerischen Krankenkassen (KSK) über den Taxpunktwert (SGS 928.13) | 1 | oldest version available, 1991-05-15 |
| `930-001/` | Staatsvertrag zwischen den Kantonen Basel-Stadt und Basel-Landschaft betreffend Planung, Regulation und Aufsicht in der Gesundheitsversorgung (SGS 930.001) | 1 | oldest version available, 2019-07-01 |
| `930-1/` | Dekret über die Betriebsstandorte des Kantonsspitals Baselland (KSBL) (SGS 930.1) | 1 | oldest version available, 2021-01-01 |
| `930-131/` | Vertrag für halbprivatversicherte Patientinnen und Patienten (SGS 930.131) | 1 | oldest version available, 1998-01-01 |
| `930-132/` | Vertrag für die ambulante Behandlung (SGS 930.132) | 1 | oldest version available, 2006-01-01 |
| `930-133/` | Vertrag für die stationäre Behandlung von grundversicherten Patienten (SGS 930.133) | 1 | oldest version available, 2008-01-01 |
| `930-134/` | Vertrag für die Physio- und Ergotherapie, Logopädie und Ernährungsberatung (SGS 930.134) | 1 | oldest version available, 2002-01-01 |
| `932-4/` | Staatsvertrag zwischen den Kantonen Basel-Stadt und Basel-Landschaft über das Universitäts-Kinderspital beider Basel (SGS 932.4) | 1 | oldest version available, 2013-01-01 |
| `932-41/` | Statuten des Universitäts-Kinderspitals beider Basel (SGS 932.41) | 1 | oldest version available, 2004-02-06 |
| `934-13/` | Vereinbarung zwischen dem Kanton Basel-Landschaft und dem Kanton Basel-Stadt über die gegenseitige Benützung von Einrichtungen des koordinierten Sanitätsdienstes (SGS 934.13) | 1 | oldest version available, 1978-02-01 |
| `934-400/` | Vereinbarung über die Aufnahme von Patientinnen und Patienten aus dem Kanton Basel-Landschaft in die Chrischonaklinik (SGS 934.400) | 1 | oldest version available, 2009-01-01 |
| `941-11/` | Altersbetreuungs- und Pflegeverordnung (SGS 941.11) | 1 | oldest version available, 2026-01-01 |
| `941-14/` | Vertrag betreffend Leistungen und Tarife bei Aufenthalt im Pflegeheim im Rahmen der obligatorischen Krankenpflegeversicherung KVG (SGS 941.14) | 1 | oldest version available, 2008-01-01 |
| `951-5/` | Vereinbarung der nordwestschweizerischen Kantone über die Führung eines regionalen Heilmittelinspektorates (SGS 951.5) | 1 | oldest version available, 2003-07-16 |
| `953-1/` | Dekret über die Betäubungsmittel (SGS 953.1) | 1 | oldest version available, 2015-01-01 |
| `963-13/` | Vertrag zwischen der Sanitätsdirektion des Kantons Basel-Landschaft und dem Erziehungsdepartement des Kantons Basel-Stadt betreffend Überlassung von Leichen an die normal-anatomische Anstalt der Universität Basel (SGS 963.13) | 1 | oldest version available, 1948-09-15 |
| `973-111/` | Konvention über das nationale Fremdstoffuntersuchungsprogramm (SGS 973.111) | 1 | oldest version available, 2020-01-01 |
| `980-112/` | Vereinbarung betreffend den Einsatz der Seuchenwehr des Kantons Basel-Landschaft zur Ereignisbewältigung bei Tierseuchen auf dem Gebiet des Kantons Basel-Stadt (SGS 980.112) | 1 | oldest version available, 2013-05-21 |

## Source

The SGS (systematic collection) of the canton, published by the canton at <https://bl.clex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (GS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (GS), with an e-mail address that cannot exist (`<act key>@bl.clex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
