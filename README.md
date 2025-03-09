# Camera Motion Card

A custom card for Home Assistant that allows configuring camera motion detection windows.

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

## Features

- Draw motion detection windows directly on camera feed
- Configure up to 4 detection windows
- Adjust sensitivity and threshold for each window
- Real-time window status display

## Installation

1. Install via HACS by adding this repository as a custom repository
   - HACS > Menu > Custom repositories
   - URL: `karatecarter/camera-motion-card`
   - Category: `Frontend`
2. Add the card to your dashboard
   - Click the "+" button to add a new card
   - Search for "Camera Motion Card"
   - Select your camera entity

## Usage

1. Select a camera from the dropdown when configuring the card
2. Use the numbered buttons to select a window
3. Draw the window on the camera feed by clicking and dragging
4. Adjust settings using the controls below the camera feed

## Options

| Name | Type | Default | Description |
| ---- | ---- | ------- | ----------- |
| entity | string | Required | Camera entity ID |

## Support

If you find this card helpful, consider:
- Starring the repository
- Reporting any issues you find
- Contributing to the code