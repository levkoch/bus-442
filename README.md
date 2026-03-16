Seattle Busses Final Project, Lev Kochergin & Sonya Outhred for UW 442 Data Visualization, Winter 2026, taught by Jeffrey Heer.

# Motivation
I don't live on campus, and I take the 271 from Bellevue to campus every day. It feels like the busses always make me wait ten minutes, regardless of which scheduled time I arrive by. As with any real-life systems, there are constant changes with traffic variantions, construction, congestion, and other daily mishaps that make running busses consistently a challenge. We wanted to investigate how much we can blame the busses for being inconsistent, and whether there is a more realistic arrival time for some of these stops.

# Design Rationale
We decided to split up the design into two major components: we wanted it to read as an article, where we can provide additional context about the Seattle bus system. This felt natural to the premise of the project. Additionally, the visualizations would first serve to familiarize readers with the Seattle bus system, and then allow them to explore whatever routes they are interested in. As there are many routes to choose from, it would have been infeasible to create a customized article experience for each of them, but having a picker allows for a custom visualization experience for everyone. The article uses a simple color palette of pink and blue, with additional bus colors provided from existing colors used by the Seattle Metro.

# References
The `kingcounty_transit` data is avaliable at `https://soundtransit.org/GTFS-KCM/google_transit.zip`. Lateness data from King County as requested by `https://github.com/rfoxall3/seattle_bus_data_project` from their Google Drive `https://drive.google.com/drive/folders/10L4VCDBqzbiX8hn5lLf72s7h0LZjxbg-`. Data processing inspired by `https://github.com/mattmakesmaps/gtfs-exploration/blob/main/notebooks/kc_metro/data-exploration-and-mapping.ipynb`.

UW Sustainability + bus promotion efforts: `https://sustainability.uw.edu/plan/dashboard/target-7-transportation`. King County bus statistics: `https://kingcounty.gov/en/dept/metro/travel-options/bus`. Bus favicon recolored from `https://commons.wikimedia.org/wiki/File:Bus-logo.svg`. Background maps from `https://openstreetmap.org`. The code for this article's visualizations were created with the help of Anthropic's Claude model `https://claude.ai` to assist with debugging and styling.

# Development Process
Lev worked on the inital map design for the overview map. We were inspired by a project which also rendered some stop locations, and used the dataset they found. He also wrote the article, did most of the rendering for the various routes, stops, and filter selections. Sonya worked on the lateness data processing, the third overall lateness visualization, and the project video showcase.
