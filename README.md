# Herd Immunity Simulator

Live: https://kenny150r.github.io/vaccine-simulator/

A bouncing-ball outbreak simulator. Each ball is a person; contagious balls can infect others when they bounce into them. Adjust:

- **R₀** – how contagious the disease is
- **Vaccination rate** – share of people vaccinated
- **Vaccine efficacy** – share of vaccinated people who are actually protected
- **Case fatality rate** – share of infected people who die

Presets cover measles at different coverage levels, a smallpox-like disease, COVID-like and flu scenarios, and a few "lessons" (the herd-immunity tipping point, and why most cases can be among vaccinated people when coverage is high).

Below the simulation, two charts use the SIR final-size equation to show how deaths per million change with vaccination rate, and how vaccination rate × efficacy determine whether herd immunity is reached.

Single static `index.html`, no build step or dependencies. Educational tool, not medical advice.
