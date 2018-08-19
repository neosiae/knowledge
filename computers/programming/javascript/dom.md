# DOM

## Events

Suppose you have a element inside an element and both have an onClick event handler. If the user clicks on element2 he causes a click event in both element1 and element2. Which event handler should be executed first?

```txt
-----------------------------------
| element1                        |
|   -------------------------     |
|   |element2               |     |
|   -------------------------     |
|                                 |
-----------------------------------
```

### Event capturing

When you use event capturing the event handler of element1 fires first, the event handler of element2 fires last.

```txt
               | |
---------------| |-----------------
| element1     | |                |
|   -----------| |-----------     |
|   |element2  \ /          |     |
|   -------------------------     |
|        Event CAPTURING          |
-----------------------------------
```

### Event bubbling

When you use event bubbling the event handler of element2 fires first, the event handler of element1 fires last.

```txt
               / \
---------------| |-----------------
| element1     | |                |
|   -----------| |-----------     |
|   |element2  | |          |     |
|   -------------------------     |
|        Event BUBBLING           |
-----------------------------------
```

### Event delegation

Bubbling allows us to take advantage of __event delegation__.

* [How JavaScript Event Delegation Works](https://davidwalsh.name/event-delegate)

