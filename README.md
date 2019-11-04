# proceduralSite: Build a site based off of a config file 🚀

## Features

-   ### Live reloading as data changes
-   ### Can adapt to any amount of charts and data
-   ### Charts can be customized

## Startup

### Prerequisites: Yarn must be installed on your system

### To launch:

```
yarn install
yarn run dev
```

## Config file format

```
{
    "chartName": {
        "labels": ["Data label", "Another label", ...],
        "color": ["Exciting color", "Mundane color", ...],
        "data": ["Big number", "Small number", ...]
    },
    ...
}
```
