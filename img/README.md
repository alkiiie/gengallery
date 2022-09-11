## Uploading photos

When you upload photos, please take note of the insert available in the dev folder, as they are tried and testedto properly work with the index code.

The insert should be placed within the `viewer` class, under `appViewer`, like so:

```html

        <div class="viewerdisplay" id="appViewer">
            <div class="viewer">

                <div class="imagecont" id="image[]">
                    <img src="img/[].png" alt="Image []" class="image">
                </div>

            </div>
        </div>

```

Under `img` folder, the images uploaded should be numbered `01,02,03` corresponding to the order you want to display them in.

Images are displayed left-to-right, amount of images displayed on a single row depends on the width of the viewing device.