# JSONParsing Only for Practice.
Simple iOS app for parsing JSON data in Swift

In ViewController file find "getJsonFromFile()" method and replace the "example" with your json file name.

like:

let file = NSBundle.mainBundle().pathForResource("example", ofType: "json")

to

let file = NSBundle.mainBundle().pathForResource("myjsonfile.json", ofType: "json")
