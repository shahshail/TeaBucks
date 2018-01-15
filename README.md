# TeaBucks
- This is simple online Tea order mock app.(Purpose for perform Espresso Test).
- User can select their favorite tea from different Teas.
- The user can also customize their tea using spinners and edit texts.
- Finally user can review their order and share their order via Email.

## Espresso Test
- Exspresso can help us to test variety of test components (e.g. Views, Intents, AdapterViews and Idling Resources).
- For this TeaBucks App, i have performed 4 different tests.

### MenuActivity Test
- MenuActivity contains simple list of tea items with grid layout.
- In this test, I have performed **AdapterViews Test** with **onData** and **onView** methods to assure that app behaves correctly.

**1) onData**: onData method is responsible to load the adapter item we are interested in onto the screen before operating on it.

**2) onView**: onView() can handle most Views in our UI, Espresso does require a different method call when dealing with AdapterView widgets.

![atp txt](https://github.com/shahshail/TeaBucks/test_1.png)
