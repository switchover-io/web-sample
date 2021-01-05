# Switchover Web Sample

Simple example to show you how to use Switchover directly in the browser (vanilla JS)

## Configuration

Before we can start you have to edit the `index.html`:

1. Open the `index.html` with you favorite editor (e.g. Visual Studio Code)
2. Replace the `SDK_KEY` and `TOGGLE_NAME` with your environment specific SDK Key and you toggle name:
```html
<script>
const sdkKey = 'SDK_KEY';
const toggle = 'TOGGLE_NAME';
...
</script>
```

3. Save and open the file with you favorite browser

## Usage

By default every new feature toggle is deactived by default. To see the feature in action you have to activate you flag in the enviroment.

## Where to find the SDK Key?

Go to your environment (e.g. development) and copy your SDK-Key:

![Switchover SDK Key](/doc/copy_sdk_key.jpg)