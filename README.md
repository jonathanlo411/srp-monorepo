# SRP Monorepo
Inside this repository holds services and applications related to [Shutoko Revival Project](https://shutokorevivalproject.com/) and its [leaderboard](https://hub.shutokorevivalproject.com/timing/). Inside this repo are two main applications and their services.

## Applications

### SRP Search
 SRP search is a way to search for a specific driver's times given their name. It uses the [srp-search](https://github.com/jonathanlo411/srp-search/tree/main) service.

### SRP Tracker
SRP Tracker is an application to view data trends in driver positions as well as view racing profiles. The following are the services it uses:
- [srp-tracker-frontend](https://github.com/jonathanlo411/srp-tracker-frontend/tree/main) - A simple frontend made using SvelteKit to display the charts and data.
- [srp-tracker-backend](https://github.com/jonathanlo411/srp-tracker-backend/tree/main) - A backend which runs cronjobs to scrape leaderboard data and serves as an API gateway to the data.
- [srp-profile-service](https://github.com/jonathanlo411/srp-profile-service/tree/main) - A service created to run analytics and create KPIs from driver lap times and data. 

## License
This project is licensed under the GNU General Public License. See `LICENSE` for more information.
