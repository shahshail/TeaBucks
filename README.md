# TeaBucks
- This is simple online Tea order mock app.(Purpose for perform Espresso Test).
- User can select their favorite tea from different Teas.
- The user can also customize their tea using spinners and edit texts.
- Finally user can review their order and share their order via Email.

## Espresso Test
- Exspresso can help us to test variety of test components (e.g. Views, Intents, AdapterViews and Idling Resources).
- For this TeaBucks App, i have performed 4 different tests.

### AdapterView Test
- MenuActivity contains simple list of tea items with grid layout.
- In this test, I have performed **AdapterViews Test** with **onData** and **onView** methods to assure that app behaves correctly.

**1) onData**: onData method is responsible to load the adapter item we are interested in onto the screen before operating on it.

**2) onView**: onView() can handle most Views in our UI, Espresso does require a different method call when dealing with AdapterView widgets.

![atp txt](https://github.com/shahshail/TeaBucks/blob/master/test_1.png)

### Intent Test
- Two comman terms in ragards to intent testing are **Intent Stub** and **Intent Verification** 

**1) Intent Stub**: Intent stub is nothing but a small piece of code that acts as a fake response to an intent call during a test.

**2) Intent Verification**: In espresso, If we want to varify the intent data then we will use Intent Verification method. As the name implies, we intended what we send works properly.

![atp txt](https://github.com/shahshail/TeaBucks/blob/master/test_2.png)

![atp txt](https://github.com/shahshail/TeaBucks/blob/master/test_3.png)

### Idling Resources
- In order to count the time taken by the async task to perform operation in background, We implement Idkling Resources.
- With Idling Resources implementation the espresso will paus untill the background task is done. Then it will re-continue when the device is ideal. So this approach will give us an idle test results.

![atp txt](https://github.com/shahshail/TeaBucks/blob/master/test_4.png)

## Screens

#### Home Screen
![atp txt](https://github.com/shahshail/TeaBucks/blob/master/home.png)

#### Order Screen
![atp txt](https://github.com/shahshail/TeaBucks/blob/master/order.png)

#### Order Summary Screen
![atp txt](https://github.com/shahshail/TeaBucks/blob/master/summary.png)

#### Share Screen
![atp txt](https://github.com/shahshail/TeaBucks/blob/master/mail.png)





