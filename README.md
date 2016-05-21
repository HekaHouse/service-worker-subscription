# service-worker-subscription

`<service-worker-subscription>` A Polymer element to create a service worker subscription.

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/service-worker-subscription)

[Source](http://github.com/hekahouse/service-worker-subscription/)


## Install

    bower install --save HekaHouse/service-worker-subscription

## Example

    <service-worker-subscription
      subscription-key-path="https://YOUR-FIREBASE.firebaseio.com/subscriptions/SUBSCRIPTION-ID"
      subscription="{{subscriptionKey}}">
    </service-worker-subscription>

## Note

Upon successful subscription the subscription key is saved to Firebase under subscription key path

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

service-worker-subscription depends on

[firebase-input](https://heka-house-polymer-demos.firebaseapp.com/firebase-input)

## Related
