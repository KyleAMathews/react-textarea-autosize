# react-textarea-autosize

Replacement for textarea component which uses jquery-autosize to grow textarea
as content grows:

    var Textarea = require('react-textarea-autosize');

    React.renderComponent(
      <div>
        <Textarea autosize></Textarea>
      </div>,
      document.body);

As you can see there's `autosize` boolean property which would activate
jquery-autosize plugin.

This component relies on jQuery to be globally accessible via `window.jQuery`.
