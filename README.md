# About

- Dark mode

## 0. Three version for each popup_app

- POPUP
    Need to include info of how to unblock the popup on settings for [Chrome](), [Edge](), [Safari]() ,[Firefox]()
- **NO POPUP**
    - Deskptop  Version: Due to the blokage of popups on modern browse by default,
    - Mobile Version - It will also have a mobile version, that will immitate the window adjestment.


## 1. Tech

### 1.1 Pop-up

A browser pop-up is a small window that appears over or outside the main browser window, often triggered by user actions like clicking a button or link.

The basic method involves the `window.open()` function, which allows you to specify the URL, window name, and window features (such as size and toolbars).

```js
function openPopup(url) {
  window.open(url, 'popupWindow', 'width=400,height=300,scrollbars=yes,resizable=yes');
}
```

To trigger the `js` above, you might use a button or link on your `html`:
```html
<a href="popup-app.html" onclick="openPopup(this.href); return false;">Open Pop Up App</a>
```

### 1.2 Sound (Theremin)

Digital sound processing adjusted by multiple parameters

## 2. Pop Up Apps

### 2.1 Ruler

On the ruler the user can select two formats, one will be on the top of the ruller and the other will be on the bottom:
inch, nm, micrometers, cm, km, milles, light years

### 2.2 Area

User can select:
1. Hectare (10^4 m2)
1. Square meters
1. Imperial
1. [Pyeong/坪/평](https://en.wikipedia.org/wiki/Pyeong) (= 3.306... m2)

have scale for the user to select, for example: 1:1000, 1:20

Also have cubic measures, and it will make the window have a depth, and looks like a cube.

### 2.3 Screen Power calculator

1. The user input the brightness and the type of screen is using.

Calculate more or less how much wattage is comsuming the pop up window,

The user have a color wheel to adjust. Which may change the wattage consumption depending on the screen type.

### 2.4 Theremin

#### How the windows resize works

The Wide is the pitch. The height is vibrato, tremolo, echo(can be adjusted by the user)

It will be a line the will thicken or slim depending on the user window wideness.

The line will wave at different speeds and amplitutes according to the windows height and fx.

#### Design

##### Retro amp design.

Include On/off power lights. Volume, Gain, Overdrive, High, Low Knobs.

##### Parameters change

**Heightness**: Each parameter [tremolo/echo/vibrato] will change not only the output sound but also visually: tremolox is wavy, echo is amplify, vibrato is botty.

**Wideness**: Change the thickness like it is an elastic band.

### 2.5 PopUp Basque Pelota Game

Basque_pelota  play it by resizing a POPUP window on a browser

[Basque Pelota](https://en.wikipedia.org/wiki/Basque_pelota)  play it by resizing a POPUP window.
(You only need a finger to play it, come on, is easy.)

Screen and Viewport Dimensions [code](https://codepen.io/dudleystorey/pen/pRqyoQ)

### 2.6 Geo/Social displayer

Source from various: IMF, CIA, World Bank...

#### Option 1: User adjust window

User select two parameters for the wide and height.
Then when user adjust

##### How it works

#### Option 2: User adjust country

Then the window will be adjust automatically according the countries heigh and wide parameters.

##### How it works

1. Users select the parameters for the wide and the height parameters.

2. User adjust the country with the arrows in the keyboards: up/down for heightnes and l/r for wideness. The wideness of the window adjust the [wide_number] and can be any [parameter] land areatotal gdp of a country.
The height is the population

3. According to the parameters, In the middle will be the [wide number] divided by [height number]
