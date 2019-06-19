# Dash App

This is an example of an app built with Plotly's [Dash](https://plot.ly/products/dash/) framework.


## Quickstart

Create an environment with virtualenv or conda.
For conda,

```
conda create --name dash python=3.6
source activate dash
```

Install the stuff in `requirements.txt`.

```
pip install -r requirements.txt
```

This app requires a [mapbox](https://www.mapbox.com/) key for the map to render.
It needs to be assigned to the `MAPBOX_KEY` environment variable. 
The code will also read from a `.env` file.

Launch the app.

```
python app.py
```

Credits: https://github.com/timothyrenner/bigfoot-dash-app
