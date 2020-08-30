# videoprocessing-ios-objc

In this example DeepAR is used to process a prerecorded video from Camera Roll. This is a showcase how to use DeepAR in a off-screen, non-live rendering mode to process stream of images and then do something else with them. In this case create a new video using AVFoundation. Make sure to check DeepAR API docs for reference: https://help.deepar.ai/en/articles/4362326-ios-api-documentation

The example makes heavy usage of AVFoundation for encoding and decoding videos so make sure to read up on AVAssetReaderOutput and AVAssetWriterInput usage for this purpose.

To run the example
* Go to https://developer.deepar.ai, sign up, create the project and the iOS app, copy the license key and paste it to ViewController.m (instead of your_license_key_goes_here string)
* Download the SDK from https://developer.deepar.ai and copy the DeepAR.framework into quickstart-ios-objc folder