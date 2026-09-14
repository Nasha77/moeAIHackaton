# SparkVIA — EduTech 2030

A prototype matching MOE schools to NPO/industry volunteer projects by student interest (MySkillsFuture sectors), releasable capacity, supervision, and the term calendar — instead of matching to individuals.

## Run it
Just open `index.html` in a browser. No build step, no dependencies — everything (data, matching engine, UI, both consoles) is in one file. All data shown is sample/test data.

## Two consoles
- **Organisation** — post a project, get an instant ranked shortlist of anonymised candidate schools (no names/locations), send the top matches to MOE.
- **MOE admin** — see every school's persona (top 3 interest sectors, capacity, supervisors, blackout dates), an interest heat map across the network, and a match queue to forward projects to schools and record their decisions.

## Match formula
`score = 0.50·interest fit + 0.20·capacity + 0.15·supervision + 0.15·calendar`

See the in-app "How is compatibility scored?" panel for the full breakdown.

Built with Claude.
