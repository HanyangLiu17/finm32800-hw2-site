# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures

Daily date, symbol, open, high, low, close, and volume from Databento. Prices are in index points: 100 minus price is the implied monthly average EFFR in percentage points. Parent symbology also returns calendar spreads; filter to outright ZQ contracts before computing implied rates. These are daily OHLCV closes, not official settlement prices.


## DataFrame Glimpse

```
Rows: 11818
Columns: 7
$ date   <datetime[ns]> 2026-10-22 00:00:00
$ symbol          <str> 'ZQN7-ZQX7'
$ open            <f64> 5.0
$ high            <f64> 5.0
$ low             <f64> 5.0
$ close           <f64> 5.0
$ volume          <u64> 6


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Fed Funds, Futures, Monetary Policy, Fedwatch                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API: GLBX.MDP3, ohlcv-1d, ZQ.FUT parent symbology                                                   |
| Data available up to (min)     | 2026-10-22 00:00:00                                                             |
| Data available up to (max)     | 2026-10-22 00:00:00                                                             |
| Dataframe Path                 | C:\Users\Liuhanyang\Desktop\hw2-HanyangLiu17\_data\fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file://C:/Users/Liuhanyang/Desktop/hw2-HanyangLiu17/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-23 22:45:03           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

