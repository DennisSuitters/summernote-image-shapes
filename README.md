# summernote-image-shapes
A plugin for the [Summernote](https://github.com/summernote/summernote/) WYSIWYG editor.

Adds a dropdown to choose from Bootstrap image shapes (Thanks to [MarcosBL](https://github.com/MarcosBL)).

### Installation

#### 1. Include JS

Include the following code after including Summernote:

```html
<script src="summernote-image-shapes.js"></script>
```

#### 2. Supported languages
Currently available in English and Brazilian Portuguese!

#### 3. Summernote options
Finally, customize the Summernote image popover.

```javascript
$(document).ready(function() {
    $('#summernote').summernote({
        popover: {
            image: [
                ['custom', ['imageShapes']],
                ['imagesize', ['imageSize100', 'imageSize50', 'imageSize25']],
                ['float', ['floatLeft', 'floatRight', 'floatNone']],
                ['remove', ['removeMedia']]
            ],
        },
        lang: 'en-US'
    });
});
```

#### 4. Check out our other Summernote Plugins via our main Github page.
- [Diemen Design](https://github.com/DiemenDesign/)
