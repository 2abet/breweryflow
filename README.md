# Brewery Process Optimization with Node-RED

This project utilizes IBM i-UG's Node-RED environment to optimize brewery processes through the automation of IIoT variables. It integrates various flows to control and monitor the stages of the brewing process, ensuring efficient management of resources and real-time data tracking.

## Project Architecture

This Node-RED application interfaces with IBM DB2 databases to manage process data. It includes functionalities such as:
- Monitoring temperatures and adjustments in the brewing tanks.
- Dynamically updating database records based on the brewing process stages.
- Displaying real-time data on the UI dashboard.

Nodes used include function nodes for logic, database nodes for DB2 interactions, and UI nodes to display information like gauges and tables.

## Getting Started

### Prerequisites
- Node-RED instance set up on IBM i-UG.
- Access to IBM DB2 database.
- Node-RED dashboard installed.

### Installation

1. **Import Node Flows:**
   - Open your Node-RED instance.
   - Click the menu at the top right corner (three horizontal lines) and select 'Import'.
   - Paste the JSON flow data from `BREWERY_flows.json` and click 'Import'.

2. **Configure Database Nodes:**
   - Double-click each DB2 node to configure the database settings.
   - Enter your database credentials and save.

### Usage

Start the flow and access the Node-RED dashboard via `<your-node-red-url>/ui` to view real-time data and controls. Use the dashboard to:
- Monitor key metrics such as temperature and production volume.
- Adjust parameters via UI controls to optimize the brewing process.

## Contributing

Contributions to enhance the functionality or efficiency of this project are welcome. Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Authors

- **Arabambi Akinyemi E.** - *Improvements and Automation* - [2abet](https://github.com/2abet)
- **Mike Ryan and Josh Ryan** - *Initial brewery process* - [Josh Ryan]([https://github.com/2abet](https://github.com/JoshRyanEOG/i-UG_Education_Node-Red)

## Acknowledgments

- Thanks to IBM i-UG's Node-RED team for support and collaboration opportunities.
- My lovely wife.
- My parents
- My fellow Node-RED colleagues

