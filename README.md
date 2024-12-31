# Android Translation Layer Base App

This is a Flatpak base app for Android Translation Layer ([https://gitlab.com/android_translation_layer/android_translation_layer](https://gitlab.com/android_translation_layer/android_translation_layer)). It can be used to repackage Android applications as Flatpaks. For an example of doing this see the manifest of the NewPipe Flatpak ([https://github.com/flathub/net.newpipe.NewPipe](https://github.com/flathub/net.newpipe.NewPipe)).

## Usage as commandline application
The BaseApp can also be used directly as a commandline application with the following commands.

```bash
flatpak install io.gitlab.android_translation_layer.BaseApp
flatpak run io.gitlab.android_translation_layer.BaseApp ~/Downloads/application.apk
```

Keep in mind that the API implementation is far from complete, so any random untested application is unlikely to work out of the box.
