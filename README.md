# summernote-ace-plugin
summernote plugin for ace editor

## Setup
 * Include summernote project script
 * Include ace from https://github.com/ajaxorg/ace-builds/
 * Include the script tag below in your document
```HTML
<script src="yourfolder/dist/summernote-ace-plugin.min.js"></script>
```

## Usage
 * Configuration summernote toolbar
```javascript
$('#summernote').summernote({
    // ace options
	ace: {
		aceTheme: 'ace/theme/dawn',
		aceMode: 'c_cpp',
		aceLineHeight: '32px',
		aceFontSize: '16px',
		aceModeSelectorLabel: 'select your language',
		aceCodeInputAreaLabel: 'input your code',
		aceCodeSubmitBtnLabel: 'Insert',
		aceModalTitle: 'Insert Code',
		aceModes: [
			'c/c++', 'java', 'javascript', 'perl', 'python', 'php', 'ruby',
			'sh', 'golang', 'julia', 'rust', 'scala', 'haskell', 'lisp', 'lua', 'sql',
			'coffee', 'typescript'
		],
	},
	toolbar: [
		['myplugin', ['aceCodeEditor']]
	],
});
```

## Demo
 * git clone git@github.com:wubin1989/summernote-ace-plugin.git
 * cd summernote-ace-plugin
 * bower install
 * open command line, type: open demo/index.html

## Contacts
* Email: 328454505@qq.com

## License
MIT
