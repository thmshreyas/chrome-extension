# chrome-extension

We have created a simple chrome extension which gives random jokes whenever you click on it.

# How-It-Works

The file manifest.json contains the name ,version  browser action (popup since all chrome extension use this feature), icons and permissions .
Manifest.json file renders the popup.html file which is styled in a decent manner.
The popup.html is linked to a javascript file where we have  used a api called icanhazdadjoke which gives random jokes in json format and we have parsed the joke from that json data and displyed it in the active  tab

