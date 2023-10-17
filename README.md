# EndToEndFlightPricePrediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [RenderAccount](https://render.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```conda create -p my_new_env python==3.10 -y```

### when your gunicorn app:app doesn't work try this on command prompt
```
waitress-serve src app:app
```

```A machine learning end to end flask web app deployed on heroku```

```Run the flight_price.ipynb file to create a pickle file. Then on the command line run the app.py file an http server will be provided. Copy paste it on the server and start predicting!!!```

### i was Facing this error while building this project
```ValueError: node array from the pickle has an incompatible dtype:
- expected: {'names': ['left_child', 'right_child', 'feature', 'threshold', 'impurity', 'n_node_samples', 'weighted_n_node_samples', 'missing_go_to_left'], 'formats': ['<i8', '<i8', '<i8', '<f8', '<f8', '<i8', '<f8', 'u1'], 'offsets': [0, 8, 16, 24, 32, 40, 48, 56], 'itemsize': 64}
- got     : [('left_child', '<i8'), ('right_child', '<i8'), ('feature', '<i8'), ('threshold', '<f8'), ('impurity', '<f8'), ('n_node_samples', '<i8'), ('weighted_n_node_samples', '<f8')]```

```to resolve this please see you scikit_learn version on both places you have to use same scikit_learn version and even see that sometimes people write scikit-learn instead of scikit_learn``` 