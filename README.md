# White noise generator

Build your own white noise machine using your Raspbery Pi or similar device!

> A white noise machine is a mechanical device used primarily to help people sleep. They produce a monotonous 'white noise' sound similar to television static. Many people find this sound calming, allowing them to fall and stay asleep longer.

## Get started

**Join the open fleet**

Visit [balenaHub](https://hub.balena.io/tmigone/white-noise-generator) to get this project running on your device. No balenaCloud account needed!

**Create your own fleet**

To create your own fleet use the Deploy with balena button below (you'll need a free balenaCloud account)!

[![](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/balenalabs-incubator/white-noise-generator)


## Usage

Once your application has started visit `http://balena.local` or your device's local IP address to access the control dashboard. You'll be able to start and stop the white noise, set the volume and more!

**Configuration**

You can set the following environment variables to configure initial values for the project:
- `NOISE_TYPE`: Choose what type of white noise you want. Options are `white` or `ocean`. Defaults to `ocean`
- `NOISE_VOLUME`: Set the initial volume. Defaults to 40%.
- `AUDIO_OUTPUT`: Set the audio output device (headphone jack, HDMI, etc). For available options see [here](https://github.com/balenablocks/audio#environment-variables).