# hackActivities
it's not a new technique. I just wanted to check everything myself, аnd so I wrote 2 apks 

1. Bank app
In the first application manifest you can see that test bank application has 2 activities
The first activity is PIN input activity
The secont activity is secret data ("just secret text")

2. Hackers app
Using this apk we can bypass PIN activity because the second activity from bank app is an export activity.
```
  Intent intent = new Intent("vah13.com.bankapplicationformoney.Secret");
  startActivity(intent);
```


