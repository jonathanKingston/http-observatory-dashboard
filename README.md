# HTTP Observatory Dashboard

This dashboard provides a metrics dashboard to see the status of the [Observatory](https://observatory.mozilla.org/) for each link.


## Install

```
pip install -r requirements.txt
```

## Running

Running `make devserver` will make a live dev environment that can be loaded in the browser and refreshes every time you change templates or run `make generate`.

Running `make generate` fetches the reports from the Observatory.

```
cd httpobsdashboard;
make generate;
make devserver;
```

## Configuring

Configuring the dashboard is simple, edit the JSON files `httpobsdashboard/conf/` the main files is `sites.json`.

To modify the meaning of scores for websites edit `deviations.json`. 
