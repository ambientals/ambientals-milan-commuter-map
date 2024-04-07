# Milan workforce commute maps

This project was inspired by the need to visualize access to mobility and housing in Milan and its surroundings from the perspective of the commuter workforce dependent on public transport. The goal is to assist in choosing a place to live, considering commutes of up to 40 minutes to Milan. The maps exclude internal routes within Milan, cities without railway stations, and routes from neighbouring cities exceeding the 40-minute time limit.

Currently, the project is incomplete, notably the static maps are missing the Blue metro line of Milan, while the dashboards are yet on a demo version. Future updates will include an automated data flow, ensuring updated information, as well as maps and dashboards that incorporate the Blue line.

## Data sources and technologies
Public transportation info was sourced from the *TravelTime* API, while housing info was gathered from various real estate web portals. A data cleaning, analysis, and visualization process was implemented using the following technologies:

- **Python and Excel**: For data extraction, manipulation, and loading.
- **qGIS**: For creating detailed static maps.
- **Power BI**: For interactive visualizations.

More details on all the data pipeline steps will be made available in the future.

## Using the offered data solutions
To explore the PowerBI demo dashboards available online, visit:
   - [This link](https://app.powerbi.com/view?r=eyJrIjoiZjdlZDExOTAtMWI2Yi00ZWM4LWI5ZTItNjhjZjRkNjZiZDY3IiwidCI6Ijc0NzRjNTYxLTNiYmUtNDVkYi05NTgyLWMzYzNkNTk2Zjc2MCIsImMiOjl9) for cities in the Milan Metropolitan region with the rail line as the map's base layer plus some cities useful info as cards.

![Overview Map](path/to/your/overview_map.png)

![Overview Map](path/to/your/overview_map.png)
   - [This link](https://app.powerbi.com/view?r=eyJrIjoiMmVlNmRkNmUtYjFkZi00ZGIzLWEzNTktMTkxNWEzMGUwYjgxIiwidCI6Ijc0NzRjNTYxLTNiYmUtNDVkYi05NTgyLWMzYzNkNTk2Zjc2MCIsImMiOjl9) for cities within a 40min train ride to Milan that have a train station plus their housing info, having the rail line as base map.

![Overview Map](path/to/your/overview_map.png)

![Overview Map](path/to/your/overview_map.png)

**Note**: Both are intended to be developed into a single unified one in the future.

To explore the static maps created in high resolution with qGIS, click [here](https://github.com/ambientals/milan-commuter-maps).

![Overview Map](path/to/your/overview_map.png)

![Overview Map](path/to/your/overview_map.png)

![Overview Map](path/to/your/overview_map.png)

To explore and modify the dashboards with PowerBI:
   - Download PowerBI from the official website.
   - Download the project files from the [repository](https://github.com/ambientals/milan-commuter-maps), open them in PowerBI, and adjust visibility through the controls.

To explore and modify the maps with qGIS:
   - Download qGIS from the official website.
   - Download the project files from the repository (to be added soon), open them in qGIS, and adjust visibility through the controls.

## License
This project is licensed under the Unlicense - see the [LICENSE](https://github.com/ambientals/milan-commuter-maps?tab=Unlicense-1-ov-file) file for details.
