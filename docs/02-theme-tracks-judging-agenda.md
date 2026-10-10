# Touch Grass — Theme, Tracks, Judging and Agenda
## A 24-hour youth hackathon · November 7–8, 2026

Prepared October 7, 2026. Updated October 10, 2026.

> **Changed October 10: the format is now broad, on the model of Stanford's TreeHacks.** Five tracks: **Healthcare, Sustainability, Education, Humanity, AI.** Software only. There is no problem list, as at TreeHacks: teams build anything inside a track. The old problem bank in section 4 is background only. Sections 1 to 4 below are kept as background for the Healthcare and Sustainability tracks. Finals: the five track winners, plus one wildcard if the scores call for it, present on stage, so five or six teams speak. Awards across all tracks: Most Creative, Most Impactful, Most Technically Complex.

---

## 1. The name and the theme

**Name: Touch Grass.** Online it means "go outside, log off, breathe." In Ulaanbaatar the joke turns serious: going outside in January is a health decision, and the ground, the water and the stove are too. The name says the thesis in two words and sounds like something students chose, which is the point for a youth event. Use it with the straight subtitle so partners know what it is.

**Working line:** *"The air we breathe, the water we drink, the ground we live on, the winters we survive."*
**Shorter:** *Healthy city. Build it.*
**Mongolian:** *Амьсгалах агаар, уух ус, амьдрах газар, давах өвөл.*

The theme is environmental health in Mongolia, city and countryside: health problems that have an environmental cause and a technical fix within reach of a student team in 24 hours. Four in five deaths in the country are from noncommunicable diseases, and the environment people live in drives much of that. Every track pairs one environmental cause with one health outcome, so "health" and "environment" are never separate menus; a project must touch both to be in scope.

Why this theme works for both audiences:

- **For participants** it is wide. Six tracks, 24 problem statements, any technology: web, mobile, hardware, data, AI, maps, SMS. A first-timer can build an alert bot; a strong team can forecast hospital admissions from station data.
- **For sponsors** it is concrete. Each track is a named problem with a number attached, and each prototype is a claim that the problem can be worked on. A bank, a telecom, a hospital or an insurer can each point to the track that touches its customers.
- **For the country** it is timely. Winter starts the week of the event: the air season in the cities, the dzud season on the steppe.

---

## 2. How the tracks prevent overlap

Three mechanisms, all cheap to run:

1. **Problem statements, not themes.** Teams do not pick "air pollution." They pick one of four statements inside the track, each with a named user and a verb. "Help a parent decide whether a child walks to school today" and "Help a school principal decide when to keep classes indoors" are different products.
2. **The track board.** At team formation on Saturday, each team claims one statement on a public board. A statement closes after three claims. Teams that share a statement must declare a different target user or approach on the board, in one line, before 14:00.
3. **The rubric rewards fit, not ambition.** Twenty percent of the score is "solves the stated problem for the stated user." A beautiful product aimed at nobody loses to a rough one aimed at the right person.

Expected spread for 55 teams: about 9 per track, 2 to 3 per statement.

---

## 3. The six tracks

Each track lists the problem, the evidence a judge can cite, where the data is, example directions, and which sponsors fit. Sources are at the end of the document.

### Track 1 · Clean air, healthy lungs
**Problem.** Winter PM2.5 in Ulaanbaatar has reached a daily average of 687 µg/m³, 27 times the WHO guideline. Pneumonia is the second leading cause of death for children under five, and admissions rise with the particle count. Exposure is unequal: ger-district households, children walking to school, outdoor workers.
**Data.** Hourly station data from agaar.mn and agaar.gov.mn; OpenAQ mirrors; Sentinel-5P satellite NO₂ and aerosol; NSO health and population data via opendata.1212.mn; health statistics at 1313.mn.
**Directions.** Personal or school exposure alerts; a "walk or ride today" decision tool for parents; low-cost sensor networks for classrooms; indoor-air guidance for gers by stove type; masks and purifier guidance matched to budget.
**Sponsor fit.** Air purifier and HVAC retailers, hospitals and clinics, insurers, telecoms for SMS alerts, pharmacies.

### Track 2 · Safe heat
**Problem.** After raw coal was banned in 2019, acute carbon monoxide poisoning cases rose as much as 50-fold in the districts with the ban; 779 deaths from carbon monoxide were counted between 2017 and 2024. The cause is behavior and ventilation around briquettes, and the fix is prevention and fast response.
**Data.** Published studies on the 2019 outbreak and the post-ban period; emergency service public statements; NSO housing and heating data; weather data from weather.gov.mn, since poisoning peaks on the coldest nights.
**Directions.** Low-cost CO detector designs and distribution tools; a cold-night SMS warning to households by khoroo; a briquette-lighting guide delivered where people actually look; a symptom checker that routes to 103; mapping of poisoning incidents against temperature for emergency staffing.
**Sponsor fit.** Insurers, fuel and heating companies, emergency services, telecoms, hardware retailers.

### Track 3 · Ground and water
**Problem.** Ulaanbaatar's seven districts hold about 145,000 pit latrines. One study found 88 percent of ger-area soils bacterially contaminated and E. coli in a 47-metre well, and tied soil contamination to diarrhoeal disease in children under five. Separate studies find heavy-metal risk to children above permissible limits near industrial sites.
**Data.** Published soil and groundwater studies; city water utility data; NSO household water-source data; satellite and open-street data for ger districts.
**Directions.** Well-water testing logistics and a results map residents can read; latrine upgrade tracking and financing tools; hygiene behavior nudges for households with children; a soil-risk map for schools and kindergartens.
**Sponsor fit.** Water and beverage companies, construction and sanitation firms, banks for upgrade financing, UNICEF-type partners.

### Track 4 · Waste and health
**Problem.** The city produces thousands of tonnes of waste a day; about a fifth is recycled, 7 percent is illegally dumped, and the ger areas with the fewest services carry the most of it. Landfill communities, informal waste pickers, hazardous household waste such as batteries and medical waste all sit between environment and health.
**Data.** City waste and recycling statistics; landfill locations; studies on household waste behavior; the SPRIM plastic-recycling program data.
**Directions.** Collection routing for ger areas; sorting incentives that work without deposits; hazardous household waste pickup; waste-picker safety and income tools; medical waste tracking for clinics.
**Sponsor fit.** Recycling companies, retailers, beverage and packaging companies, city waste agency.

### Track 5 · Climate shocks
**Problem.** Mongolia has warmed 1.59 degrees since 2005, nearly three times the global rate. Six major dzuds in a decade; 8.1 million animals died in the winter of 2023 to 2024. The health side is cold-wave injuries and deaths, herder mental health after livestock loss, interrupted care in remote soums, and summer heat in the city.
**Data.** NAMEM weather and forecasts; Red Cross and WHO dzud reports; NSO livestock and population data; satellite snow and vegetation indices.
**Directions.** Cold-wave and heat health alerts by soum; herder mental-health check-in lines over SMS or voice; telehealth triage for remote families during dzud; heat-risk maps for the city's elderly.
**Sponsor fit.** Insurers, telecoms with rural coverage, banks with herder customers, Red Cross and UN partners.

### Track 6 · Health data and early warning
**Problem.** The environmental data and the health data exist in separate systems. Hospitals do not see the pollution forecast; the pollution agency does not see admissions. Nobody forecasts the pediatric surge a week ahead.
**Data.** agaar.mn station history; health statistics at 1313.mn and the Health Development Center; NSO API; weather history.
**Directions.** Forecasting pediatric respiratory admissions from air and weather data; a hospital surge-planning dashboard; a public environmental-health index for the city; a citizen-science sensor registry; open datasets cleaned and documented for the next team.
**Sponsor fit.** Banks and fintechs with data teams, telecoms, health insurers, hospitals, software companies.

---

## 4. The problem bank

Twenty-four statements, four per track. Each states a problem and who has it, never the solution, so two teams on the same statement can build very different things. Teams claim one; three claims close a statement.

**Track 1 · Clean air**
1. **Walk, bus or stay home?** — On smoggy mornings, parents guess whether it is safe for their kids to be outside. Help them stop guessing.
2. **Recess indoors?** — Schools decide on outdoor breaks and PE with little to go on, and parents question every call. Help schools make the call.
3. **Which purifier is worth it?** — Families on a tight budget can't tell which masks, purifiers or habits actually protect them. Help them spend wisely.
4. **Tomorrow's coughs, today** — Clinics get hit by waves of children with breathing problems on bad-air days. Help them see the wave coming.

**Track 2 · Safe heat**
5. **The coldest-night problem** — Carbon monoxide poisoning peaks on the coldest nights, in homes that heat with briquettes. Help those homes get through the night.
6. **A CO alarm people can afford** — Most homes that need a carbon monoxide alarm don't have one, because the shop price is around 100,000 tugrik. Change that.
7. **Headache or poisoning?** — Early carbon monoxide poisoning feels like a headache, so people wait too long. Help them recognise it and get help fast.
8. **Where should the ambulances be?** — Emergency services respond to poisonings after the call. Help them get ahead of the busiest nights.

**Track 3 · Ground and water**
9. **Is my well OK?** — Families who drink from wells rarely know if the water is safe. Help them find out, and know what to do next.
10. **The latrine problem** — Ulaanbaatar has around 145,000 pit latrines, and nobody has a clear picture of which ones leak. Help fix that.
11. **Can the kids play here?** — Kindergartens and schools don't know if the ground their children play on is contaminated. Help them find out.
12. **Clean hands, zero budget** — Diarrhoeal disease hits young children hardest in homes without running water. Help families protect them with what they have.

**Track 4 · Waste**
13. **Garbage day you can trust** — In ger areas the garbage truck is unpredictable, so waste piles up or gets dumped. Help households and collectors line up.
14. **Sell the bottles** — Recyclables end up in the trash because sorting and selling them is a hassle. Make it worth it.
15. **Where do dead batteries go?** — Batteries, old medicine and chemicals go in the household bin. Help them go somewhere safe.
16. **Safer picking, better pay** — Informal waste pickers do dangerous work for little money. Make their work safer or better paid.

**Track 5 · Climate shocks**
17. **Before the dzud hits** — Herders often learn about a deadly cold spell too late to protect the herd. Help them prepare in time.
18. **Someone to talk to** — Losing livestock to a dzud is losing a livelihood, and help is far away. Support herders' mental health, even on a basic phone.
19. **Snowed-in** — When roads close, remote soums are cut off from hospitals. Help local doctors and families cope with medical emergencies.
20. **Heat-wave check** — Summer heat waves are getting worse, and older people living alone are most at risk. Help keep them safe.

**Track 6 · Health data**
21. **Forecast the hospital** — Hospitals can't see a rush of patients coming even when the air and weather data could warn them. Build that warning.
22. **One number for the news** — People hear about air, weather and illness separately. Give the public one clear picture of environmental health.
23. **Can we trust this sensor?** — Cheap air sensors are everywhere, and some of them are wrong. Help tell good data from bad.
24. **Leave a dataset behind** — Air, weather and health data sit in different places and formats. Join them so the next team can build on them.

Track sponsors may replace one statement in their track with their own, agreed by October 28.

---

## 5. Rules and judging

**Eligibility.** Students aged 14 to 20 enrolled in a secondary school, university or college in Mongolia. Under-18s bring a signed parental consent form covering the overnight. Organizers, judges and mentors do not compete.

**Teams.** Two to four people. Form before the event or at team formation Saturday 12:30. One team per person, one submission per team, one track per team.

**Building.** Everything is built between Saturday 13:00 and Sunday 13:00. Public libraries, frameworks, APIs, templates, AI assistants and open datasets are allowed; say what you used. Pre-existing code, work by people not on the team, and copying another team are not allowed. Judges may inspect repository history.

**Ownership.** Teams own what they build. Copyright is theirs automatically and transfers only by written agreement. Sponsors and organizers get no rights; we ask before publicizing a project beyond the results post.

**Code of conduct.** Respect, no harassment, no alcohol, drugs or smoking, venue rules, quiet hours 01:00 to 06:00, single-gender supervised sleeping rooms, no leaving the building 22:00 to 07:00 without a parent. Organizers act immediately, up to removal.

**Submission, Sunday 13:00 sharp.** Project page on [Devpost or form] with: track, the problem and who has it, what it does, a live demo plus a 2-minute video or screenshots as backup, repository link, tools and data used.

**Rubric, each criterion scored 1 to 5, weights in brackets.**

| Criterion | Weight | 5 looks like |
|---|---|---|
| Solves a real problem for real people | 20% | the people the team names could use this tomorrow |
| Technical difficulty and soundness | 20% | real engineering, works under questioning |
| Use of evidence and data | 15% | real Ulaanbaatar data or studies, correctly used |
| Completeness of the demo | 15% | the core flow runs live, end to end |
| Design and usability | 15% | usable without explanation by the target user |
| Creativity | 15% | an approach the judges have not seen |

**Process.** Each track has a panel of three judges: one engineer or scientist, one professional from the track's field (healthcare, environment, education, social work or AI), one sponsor representative. From 13:30 to 15:00 Sunday the panel visits every team in its track at the table: 3 minutes demo, 2 minutes questions. Judges score independently; scores are averaged. The highest team per track (five), plus the highest non-winner if the judges agree its score is close to a winner's, present on stage for 5 minutes each: five or six finalists. The full panel of 15 scores the finals on the same rubric for the overall top three. Ties: 3-minute discussion, then the higher "solves a real problem" score wins. No judge scores a team from their own school or company.

**Prizes.** A cash pool for the overall top three of at least 5,000,000 MNT, split 50 / 30 / 20, paid to the team by Uram Enerel with 5 percent personal income tax withheld. The pool grows with every prize-pool sponsor; the final size is announced on October 26, after commitments close. Internal target 15,000,000. Six track awards: certificates plus whatever the track sponsor puts up. Three awards across all tracks, as at Stanford's TreeHacks: Most Creative, Most Impactful and Most Technically Complex, each with a certificate and a prize from a prize sponsor; the full judging panel picks them. A team can win one placed prize and one track or cross-track award.

---

## 6. Agenda

24 hours of hacking, Saturday 13:00 to Sunday 13:00. Venue access needed Saturday 10:00 to Sunday 18:30. **Plan B** if overnight is refused: Saturday 11:00 to 21:00 and Sunday 09:00 to 17:00, submissions Sunday 13:00, everything else unchanged.

### Saturday November 7

| Time | What |
|---|---|
| 10:00 | Organizers arrive. 55 tables, 60 power strips, signage, check-in desk, projector and wifi test, sleeping rooms labeled, track board up |
| 10:30 | Volunteers and day mentors arrive; 15-minute briefing |
| 11:00 | Doors. Check-in on four lines by surname. Snacks and water out |
| 12:00 | Opening, 30 minutes: welcome from Hackathon Mongolia; Uram Enerel and [government body]; title sponsor 5 min; the six tracks in one minute each by their sponsors or the organizers; rules, schedule, safety and overnight rules |
| 12:30 | Team formation: solo participants pitch for 60 seconds; teams write their name under a track on the board |
| 13:00 | **Hacking starts.** Clock starts. Lunch boxes at tables |
| 14:00 | Track board closes |
| 14:30 | Workshop 1, 30 min: "Where Ulaanbaatar's health and environment data actually is," with live API calls |
| 16:00 | Mentor hour: mentors walk every table |
| 17:30 | Workshop 2, 30 min: "How to demo in 3 minutes" |
| 19:00 | Dinner |
| 20:30 | Mini-event, 20 min |
| 21:00 | Sign-out window: under-18s going home leave with their pickup, logged |
| 22:00 | Night briefing for the overnight adult shift; quiet zone opens |
| 23:30 | Midnight snack |

### Overnight

| Time | What |
|---|---|
| 01:00 | Halfway time check. Quiet hours begin: no music, no mic. Sleeping rooms open. Two adults awake per 100 participants, one floor walk every 30 minutes, night mentor on call in the chat |
| 06:30 | Lights up, coffee out |
| 07:00 | Breakfast |

### Sunday November 8

| Time | What |
|---|---|
| 09:00 | Day shift takes over; sleeping rooms cleared by 09:30 |
| 10:00 | Participants who went home are back. Three-hour time check; what a submission needs |
| 11:00 | Judges arrive. Judge briefing, 30 min, side room: rubric, track assignments, timing |
| 12:00 | One-hour warning. Submission form on screen |
| 12:15 | Lunch at tables |
| 12:45 | Fifteen-minute warning |
| 13:00 | **Submission deadline. Hacking stops.** Tables stay set for judging |
| 13:15 | Judging instructions to everyone |
| 13:30 | Track judging at tables: each panel visits its 9 teams, 5 minutes each, timekeeper per panel |
| 15:00 | Scores tallied by two people independently; eight finalists announced |
| 15:15 | Finals: 8 teams × 5 minutes on stage, full panel scoring |
| 16:00 | Judges deliberate; audience: sponsor thanks |
| 16:20 | Awards: Most Creative, Most Impactful, Most Technically Complex, five track awards presented by track sponsors, then third, second and first from the cash pool, first presented by the title sponsor |
| 16:50 | Group photo. Survey link on screen |
| 17:00 | Close. Pickups at the door; adult lead stays until the last participant leaves |
| 17:30 | Cleanup; venue handed back by 18:30 |

---

## 7. Participants, mentors, judges

**Participants.** Target 260 registrations for 220 attending; cap at 300 with a waitlist. Mostly secondary school students, plus first- and second-year university students, from 25+ institutions; most participants are under 18. Recruitment runs through the website and the organizers' own networks, not through schools. Participation is 45,000 MNT per person, paid to Uram Enerel NGO. Registration opens October 17 and closes November 3.

**Mentors, 20.** University students and engineers, at least two per track, three willing to stay past midnight. Ask by October 16, confirm by October 30.

**Judges, 15.** Three per track (five tracks): one engineer or data scientist, one health or environment professional (Uram Care's network, MNUMS, hospitals, the air pollution agency, environmental NGOs), one sponsor representative. Ask by October 16, confirm by October 30, brief on November 6 and again at 11:00 on the day.

**Workshop speakers, 2.** One for data sources, one for demos. Can be mentors.

---

## Sources

- UNICEF, "Mongolia's air pollution crisis: a call to action to protect children's health" (PM2.5 of 687 µg/m³, pneumonia as second leading cause of under-five death) — unicef.org/eap
- isee.mn, 2025 annual PM2.5 average 17.9 vs 25.7 — isee.mn/n/88989
- Air-quality monitoring portal — agaar.gov.mn and agaar.mn
- "Carbon monoxide poisoning following a ban on household use of raw coal, Mongolia," PMC10300773 (50-fold rise, pre- and post-ban counts)
- The Diplomat, Feb 2025, parliamentary working group count of 779 deaths 2017–2024
- "Soil microbial contamination and its impact on child diarrheal disease incidence in Ulaanbaatar" (144,992 pit latrines, 88 percent of ger-area soils contaminated, E. coli at 47 m)
- "Ecological and human health risk assessment of heavy metal pollution in the soil of the ger district in Ulaanbaatar," IJERPH 2020
- SWITCH-Asia SPRIM program; municipal solid waste study (72.5 percent to formal sites, 20.5 percent recycled, 7 percent illegally dumped)
- ADB Climate Risk Country Profile Mongolia; Red Cross dzud appeal; Al Jazeera, March 2024 (warming 1.59 °C since 2005; 8.1 million animals lost 2023–24)
- Open data: opendata.1212.mn, opendata.gov.mn/api/3, 1313.mn, data.humdata.org WHO Mongolia indicators
