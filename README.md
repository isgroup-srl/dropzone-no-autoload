# dropzone-no-autoload
A fork of https://github.com/enyo/dropzone that works with jQuery3

## Usage
You can only instance Dropzone programmatically, see the example below.

```
$(document).ready(function() {
	$('#upload-form').dropzone({
		paramName: 'myFiles', // Name of the file input
		maxFilesize: 1, // MB
		parallelUploads: 2
		uploadMultiple: true,
	});
});

```
