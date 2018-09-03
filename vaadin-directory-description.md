[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinincubator-paginator.svg)](https://vaadin.com/directory/component/vaadinincubator-paginator)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-paginator.svg)](https://vaadin.com/directory/component/vaadinincubator-paginator)

# &lt;incubator-paginator&gt;

[&lt;incubator-paginator&gt;](https://vaadin.com/directory/component/vaadinincubator-element) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-paginator/master/screenshot.png" width="200" alt="Screenshot of incubator-paginator">](https://vaadin.com/directory/component/vaadinincubator-element)

## Example Usage

```html
  <incubator-paginator header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-paginator>
```
