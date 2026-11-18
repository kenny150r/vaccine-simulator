# Herd Immunity Simulator

Live: https://kenny150r.github.io/vaccine-simulator/

A bouncing-ball outbreak simulator. Each ball is a person; contagious balls can infect others when they bounce into them. Adjust:

- **R₀** – how contagious the disease is
- **Vaccination rate** – share of people vaccinated
- **Vaccine efficacy** – share of vaccinated people who are actually protected
- **Case fatality rate** – share of infected people who die
- **Vaccine risk** – chance the vaccine itself kills the person who gets it (deaths per million doses)

Presets cover measles at different coverage levels, a smallpox-like disease, COVID-like and flu scenarios, and a few "lessons": the herd-immunity tipping point, why most cases can be among vaccinated people when coverage is high, a vaccine scare, and a hypothetical risky vaccine.

Below the simulation, two charts use the SIR final-size equation to show how total deaths per million (disease + vaccine) change with vaccination rate, and how vaccination rate × efficacy determine whether herd immunity is reached.

Single static `index.html`, no build step or dependencies. Educational tool, not medical advice.

## MMR and autism page

https://kenny150r.github.io/vaccine-simulator/mmr-safety.html

A visual summary of MMR vaccine safety research: sample sizes, effect estimates (forest plot), how each study controlled for bias, who funded it, and what happened to the studies commonly cited by anti-vaccine groups (Wakefield 1998, Uhlmann 2002, Singh 2002, Hooker 2014, Mawson 2017). Facts were checked against the original papers, retraction notices and official reports listed on the page.

## MMR side effects page

https://kenny150r.github.io/vaccine-simulator/mmr-side-effects.html

Every side effect of MMR with good evidence behind it, beyond autism: how often each happens (per million doses), when it appears, how serious it is, and how it compares with the same complication after measles, mumps or rubella. Includes the studies behind each number (design, sample, comparison group, bias controls, funding), the 2011 Institute of Medicine causality verdicts, who should not get MMR, how vaccine safety monitoring works, and ten common claims checked against primary sources (VAERS deaths, injury-compensation payouts, shedding, the package insert, fetal cell lines, the Merck mumps lawsuit, vaccinated-vs-unvaccinated surveys, immune amnesia, vitamin A, and 2025–2026 US policy changes).
