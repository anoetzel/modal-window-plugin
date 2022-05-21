# About the plugin

Modal window with animation, that you can change by writing the attributes `data-animation="animationName" data-speed="animationSpeed"` on the button that triggers the modal window. These attributes are optional. The default values are `data-animation="fade" data-speed="300"`.

The trigger-button and the modal window you should connent by `data-path` and `data-target` that both have the same value.

The modal window has focus and can be handled with keyboard.

If you have elements on the page with `position: fixed` you should add them the class `fix-block`, so you will avoid a window transformation by opening or closing the modal window.