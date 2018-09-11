# TF2 Outpost API

## On 11.9.2018. TF2 Outpost announced that is closing down till the end of the month. As a consequence, this library becomes obsolete.
## Thank you all for using it. [NuGet statistics](https://www.nuget.org/packages/TF2OutpostAPI/)

Easily fetch trades from the TF2Outpost.com website.

## Usage
This library supports .NET Core 2.0.

1. Install this library via NuGet.
2. To fetch a trade, initialize the TF2Outpost.API class and call FetchTrade method, like this:
```
var tf2OutpostAPI = new TF2Outpost.TF2OutpostAPI();
Trade tradeInfo = await tf2OutpostAPI.FetchTrade(1);

// All information about trade with id 1 is now in the tradeInfo object.
// Use it however you wish.
```
