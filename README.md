# noodl-autocomplete-address-example
An example of using google places and maps api to create an autocomplete address field

## How to use

1. Download the files and open the folder in your favorite noodl editor flavor.
2. Open the project and edit SETTINGS > Custom Code > Head Code then insert your google api key that has access to maps and places.

```html
<script>
    init = () => console.log("places initializing")
</script>

<script
    src="https://maps.googleapis.com/maps/api/js?key={INSERT_KEY_HERE}&libraries=places&callback=init">
</script>
```

3. Run the project and test it out.

That's it, feel free to copy the component into your project.
