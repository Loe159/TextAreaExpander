
## TextAreaExpander plugin for jQuery
### v1.0
Expands or contracts a textarea height depending on the
quatity of content entered by the user in the box.

By Craig Buckler, Optimalworks.net

As featured on SitePoint.com:
http://www.sitepoint.com/blogs/2009/07/29/build-auto-expanding-textarea-1/

Please use as you wish at your own risk.

### Usage:

From JavaScript, use:
    $(<node>).TextAreaExpander(<minHeight>, <maxHeight>);
    where:
      <node> is the DOM node selector, e.g. "textarea"
      <minHeight> is the minimum textarea height in pixels (optional)
      <maxHeight> is the maximum textarea height in pixels (optional)

Alternatively, in you HTML:
    Assign a class of "expand" to any <textarea> tag.
    e.g. <textarea name="textarea1" rows="3" cols="40" class="expand"></textarea>

    Or assign a class of "expandMIN-MAX" to set the <textarea> minimum and maximum height.
    e.g. <textarea name="textarea1" rows="3" cols="40" class="expand50-200"></textarea>
    The textarea will use an appropriate height between 50 and 200 pixels.