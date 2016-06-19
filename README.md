# ckeditor-emailvideo-plugin
CKEditor plugin for embedding video in email

Use this plugin to add video as a clickable video link with thumbnil image.

#Configuration

1) Add this plugin in ckeditor toolbar configuration in ckeditor/config.js

config.toolbar_Full = [
		.................
        ['Image','Video','oembed',`'emailvideo'`,'Flash','Table','HorizontalRule','PageBreak'],
        .................
    ];


2) Use this Plugin while using CKEditor (Your own JS)
	CKEditor configration

            extraPlugins: 'emailVideo',
            filebrowserVideoBrowseUrl: `Some valid video browse url`,

So the emailVideo plugin will appear in CKEditor toolbar.
Click to add a clicable video with thumbil image placeholder.
