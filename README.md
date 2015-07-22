# craft-spoon

Parameterized spoon model.

### Usage
```html
<craft>
    <craft name="spoon" module="craft-spoon"/>
    <spoon></spoon>
</craft>

### Parameters
- length: adjusts length of spoon

### Example
```html
<craft>
    <craft name="spoon" module="craft-spoon"/>
    <row spacing="2">
        <spoon length="15" transform="scale(2,2,2)"></spoon>
        <spoon length="20"></spoon>
        <spoon></spoon>
    </row>
</craft>
```

![example](example.png)