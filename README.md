# currency-converter
Currency Converter Application

The project requirements:
1. The **main** branch for releases.
2. The **dev** branch for development
3. If you want to add the new feature, fork the dev branch.
4. Branches naming: **sf-mpd-currency-000000-Name-of-the-task**.
5. Commit messages naming: **CRM:Curr-The present simple message [MPD-TaskNumber]**
6. After finishing the a feature development create MR.


Project tasks
1. Frontend:
- create LWC components similar to Currency Converter App: https://dev.to/karkranikhil/build-7-real-time-salesforcelwc-projects-25el;
- the component must have input amount, converting and converted currency, result and a convert button;
- Pressing "Convert" button invokes Apex controller and passes amount, currencies and gets a result.
- add the component to the Home tab.

2. Backend:
- Apex controller gets  amount, currencies and returns the result;
- uses Rest API to get curency rates https://exchangeratesapi.io
- think about how to prevent using all 250 requests limit per month.
