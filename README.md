# Sample

```js
var stylusFilesMap = [];
.
.
.
stylus : {
			compile : {
				options : {
					paths : ['node_modules/nib/lib'],
					urlfunc : 'embedurl', // use embedurl('test.png') in our code to trigger Data URI
					// embedding
					use : [require('fluidity') // use stylus plugin at compile time
					],
					import : [//  @import 'foo', 'bar/moo', etc. into every .styl file

					],
					compress : true
				},
				files : stylusFilesMap
			}
		}
```