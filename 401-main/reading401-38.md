# Redux - Asynchronous Actions


[Home](/README.md) | [Back](/401-main/401TableofContents.md)

Questions:

1. How granular should your reducers be?
    - as much as you want it to be
1. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
    - Con. You want them to focus on one thing
1. Name a strategy for preventing the above
    - clear action names


Vocab: 

- store: holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action
- combined reducers: a helper function that combines multiple reducers for use

preview:

I am taking the L this week. Feeling really burnt out.
