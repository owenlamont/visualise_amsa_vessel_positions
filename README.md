# Visualise AMSA Vessel Positions

### Heatmap of Vessel Positions Between Sept 2012 and Oct 2023 inclusive

![Maritime Vessel Locations](ship_movement_heatmap_2048_1536_kbc.webp)

### One from of the video of ship movements between Nov 2022 and Oct 2023 inclusive

![Maritime Vessel Locations](amsa_vessel_locations.webp)

A few different visualisations of the Australian Maritime Safety Authory (AMSA) vessel position data.

The code in this repo depends on data formatted with the scraping and data preparation scripts in my [scrape_amsa_vessel_positions repo](https://github.com/owenlamont/scrape_amsa_vessel_positions).

Currently this repo contains two notebooks:
- [plot_movement.ipynb](plot_movement.ipynb) - which I used to create this [animation of vessel positions](https://youtu.be/c28lxm8V5vw) over the course of one year.
- [ship_movement_heatmap.ipynb](ship_movement_heatmap.ipynb) - which rendered the above blue (log scaled) heatmap of vessel movements for over a decade

I plan to revisit this repo some more to refactor the notebook into separate data preparation and visualisation scripts and give some additional visualisation examples.
