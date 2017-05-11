# TYPO3 Extension BeLogin Images

[![Latest Stable Version](https://img.shields.io/packagist/v/svenjuergens/belogin_images.svg)](https://packagist.org/packages/svenjuergens/belogin_images)

Display random Background Images from different sources at you TYPO3 BackendLogin Page.

## Installation

Simply install the extension with Extension Manager or Composer
`composer require svenjuergens/belogin_images`
then take a Image Provider.

## Configuration

You can choose between Images from [Google ChromeCast](https://github.com/dconnolly/chromecast-backgrounds/), images from [Unsplash](https://source.unsplash.com/) or you set a folder on your Server with images.
![configuration1](https://raw.github.com/SvenJuergens/belogin_images/master/Documentation/configuration1.png)

If you want to use Unsplash you can build an URL on [https://source.unsplash.com/)](https://source.unsplash.com/)
![configuration2](https://raw.github.com/SvenJuergens/belogin_images/master/Documentation/configuration2.png)

On tab "Folder" set an Path to an folder with Images, from which a random one is displayed.
![configuration3](https://raw.github.com/SvenJuergens/belogin_images/master/Documentation/configuration3.png)

## Optional
Use `IPmask` in ExtensionManager settings to restrict the output to a specific IP.

## Example Output
![example1](https://raw.github.com/SvenJuergens/belogin_images/master/Documentation/example1.png)
![example2](https://raw.github.com/SvenJuergens/belogin_images/master/Documentation/example2.png)
