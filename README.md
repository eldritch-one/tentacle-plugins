# Tentacle Plugins

Official engine and game plugins for [Tentacle](https://www.tentacle.live), the web app that connects your stream's chat, events, and tools into your virtual worlds.

Use these plugins to receive chat messages, stream events, custom events, set up custom controls, and more, directly from your project.

## Quickstart

Before installing any plugins, head to [tentacle.live](https://www.tentacle.live) and create your free account. The web app is what handles all communication between your streaming platforms and your project, so it needs to be running in your browser while you develop and stream.

Once you're signed in, pick your engine below.

> You can find a variety of video tutorials for the Tentacle plugins in our [YouTube channel](https://www.youtube.com/@TentacleApp).

### Unreal Engine

**Video walkthrough:** [Watch the Unreal Setup tutorial on YouTube](https://youtu.be/5ZWyncTiw7Y)

1. Download the latest plugin for your version of Unreal from the [Releases page](https://github.com/eldritch-one/tentacle-plugins/releases/latest).
2. Copy the `Tentacle` folder from the zip file into your Unreal project's `Plugins` directory (create `Plugins` if it doesn't exist).
3. Restart the Unreal Editor. The Tentacle plugin should appear in the Plugins list and be enabled by default. If it isn't, enable it from the Plugins dialog and restart again.
4. In your level, open the Place Actors panel, search for `Tentacle`, and drag the Tentacle actor into your scene. You only need one per project; if you use multiple levels, put it in a persistent level so the viewer cache survives level loads.
5. Hit Play. After a moment, the Unreal icon in the bottom-left of the Tentacle web app should light up green, confirming the connection.

That's it - you're ready to wire up chat, stream events, and custom controls in Blueprints or C++. See the [full Unreal documentation](https://www.tentacle.live/docs/GettingStarted/Unreal) for next steps.

### Unity

Coming soon.

## Examples

Each plugin release on the [Releases page](https://github.com/eldritch-one/tentacle-plugins/releases/latest) ships alongside example projects that demonstrate common use cases. They're a good starting point if you'd rather learn by reading working code than from docs, or you just want to start a new project from there.

## Documentation

Full documentation is available at [docs.tentacle.live](https://www.tentacle.live/docs).

## Feedback

Found a bug, want a new integration, or have a feature idea? Open an issue on this repo or send feedback through the in-app feedback system at [tentacle.live](https://www.tentacle.live).
