# KidSpirit Program Section

## Program

KidSpirit Programs Section code is available on the GitHub repo at [https://github.com/OSUKidSpirit/Programs-Section](https://github.com/OSUKidSpirit/Programs-Section)

Changes pushed to GitHub will be notified on Slack at **#04code** public channel

## Location

KidSpirit Programs Section code is currently only located in the Homepage at [kidspirit.oregonstate.edu](https://kidspirit.oregonstate.edu).

## Updating Code

### Page Changes

If the URL of the program pages changes, simply replace the URL of the respective program's link which is in the

```html
<a href="{{ REPLACE URL INSIDE HERE }}">
```

### Program Changes
If the program changes, do not change the grid number. Use the following format for the new program:

```html
  <div class="anthonian-grid-item">
    <a class="anthonian-a" href="{{ REPLACE WITH PAGE URL }}">
      <img src="{{ REPLACE WITH IMAGE URL }}" alt="{{ REPLACE WITH IMAGE DESCRIPTION }}" width="100%">
      <h2>{{ REPLACE WITH PROGRAM NAME }}</h2>
    </a>
  </div>
```

and add it to any location bewteen 

```html
<div class="anthonian-4-grid-container">
  {{ ANYWHERE IN HERE }}
</div>
```
