# cordova-plugin-keep-awake

# Notes

I forked the repository due to little (if any) support from the original author for this plugin.
I tried to make it compatible with cordova 11 but only android side.
The original plugin has several problems completing the build process. The features are still in the testing phase.

## Original Readme

Using this plug-in, you can control the automatic sleep at any time.

## Installation

Install the plugin by adding it to your project's config.xml:

```
<plugin name="cordova-plugin-keep-awake" spec="https://github.com/snuffy/cordova-plugin-keep-awake" />
```

or by using cordova CLI

cordova plugin add cordova-plugin-firebasex


## Usage

```js

// start keep awaking
if (window.KeepAwake) {
  KeepAwake.start();
}

// stop keep awaking
if (window.KeepAwake) {
  KeepAwake.stop();
}
```