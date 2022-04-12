# Let's create a grid of articles - cards like on a news page

In order for the cards to be well aligned in the grid regardless of how much text there is in the article content one needs to make the card a grid itself and make the button to be self aligned to the bottom

This is the css code which makes it tick for the article

```
.article {
    display: grid;
    align-items: start;
}

.article__button {
    align-self: end;
}
```

You can check what the alignment will look like when you comment out the ```.article__button```  ```align-self``` line.

_Happy_ Coding