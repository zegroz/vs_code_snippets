# Create your own Visual Studio Code snippets

Visual Studio Code snippets

Windows: **File > Preferences** <br />
macOS: **Code > Preferences** <br /> <br />
vs_code_snippets.code-snippets 
```json
{
	"log output": {
		"scope": "javascript,typescript",
		"prefix": ["logout", "log-output"],
		"body": ["console.log(`${element}: \\${${element}}`);"],
		"description": "A console log output"
	},
	"Print to console": {
	"scope": "javascript,typescript",
	"prefix": "logomatik",
	"body": [
		"console.log(`$1: ${$1}`);"
	],
	"description": "Log output to console"
	},
	"Create a component": {
	"scope": "javascript,typescript",
	"prefix": "component",
	"body": [
		"@Options({",
			"\t  name: '$1',",
			"\t  components: {",
			"\t  ",
			"\t  },",
			"\t  props: {",
			"\t  ",
			"\t  },",
			"\t  emits: {",
			"\t  ",	
			"\t  },",
		"})",
		"export default class $1 extends Vue { $2}"
	],
	"description": "Create a component"
	},
	"Create a class": {
	"scope": "javascript,typescript",
	"prefix": "newClass",
	"body": [
		"export class $1 {",
			"\t  ",
			"\t  public $2: $3;",
			"\t  ",
			"\t  constructor($2: $3) {",
			"\t \t  this.$2 = $2 ?? $4;",
			"\t  }",
		"}"
	],
	"description": "Create a class"
	}
}
```
location:
```
C:\Users\[UserName]\AppData\Roaming\Code\User\snippets\vs_code_snippets.code-snippets

```
![grafik](https://user-images.githubusercontent.com/5676113/165905586-888cebb4-526e-41db-b7f7-c678203cb70a.png)
