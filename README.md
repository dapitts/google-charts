# google-charts

## Install

After cloning the repo, several Node.js modules will need to be installed in the `/src` directory using the `npm install` command:

```
$ npm install connect serve-static
```

## Run

Next, start the server:

```
$ node chart-server.js
```

## View

In your favorite browser, type the following URL in the address bar:

```
127.0.0.1:8080
```

Or, you can serve up a specific Google chart:

```
127.0.0.1:8080/google-line-chart.html
```

## TBD

Improve the tooltip. The ChartWrapper class makes it rather difficult (but not impossible) to customize the tooltip.
