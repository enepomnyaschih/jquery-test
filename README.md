Demo for https://intellij-support.jetbrains.com/hc/en-us/community/posts/360009424120-Suggest-jQuery-import-in-TypeScript-files?page=1

Hosted at:

* https://enepomnyaschih.github.io/jquery-test/with-import.html
* https://enepomnyaschih.github.io/jquery-test/no-import.html

Guide:

1. Clone the repository.
1. `npm install`
1. `"node_modules/.bin/parcel" build --public-url . src/*.html` (on Unix, remove double quotes)
1. `"node_modules/.bin/serve" dist`
1. Open `http://localhost:5000/with-import` in Chrome or Firefox and observe "Hello!" message in console.
1. Open `http://localhost:5000/no-import` in Chrome or Firefox and observe an error message in console.
