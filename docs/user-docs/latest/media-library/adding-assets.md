---
title: Adding assets to the Media Library - Strapi User Guide
description:
canonicalUrl:
---

<!-- TODO: update SEO -->

# Adding assets

The Media Library displays all assets uploaded in the application, either via the [Media Library](/user-docs/latest/media-library/introduction-to-media-library.md) or the [Content Manager](/user-docs/latest/content-manager/writing-content.md#filling-up-fields) when managing a media field.

Assets can be added to the Media Library by clicking the **Add new assets** button.

A variety of media types and extensions are supported by the Media Library:

| Media type | Supported extensions                                          |
|------------|---------------------------------------------------------------|
| Image      | - JPEG<br>- PNG<br>- GIF<br>- SVG<br>- TIFF<br>- ICO<br>- DVU |
| Video      | - MPEG<br>- MP4<br>- Quicktime<br>- WMV<br>- AVI<br>- FLV     |
| Audio      | - MP3<br>- WAV<br>- OGG                                       |
| File       | - CSV<br>- ZIP<br>- PDF<br>- Excel<br>- JSON                  |

![🏞 screenshot - "Add new assets" popup]()

To add new assets to the media library:

1. Click the **Add new assets** button.
2. Choose whether you want to upload the new asset from your computer or from an URL:
    - from the computer, either drag & drop the asset directly or browse files on your system,
    - from an URL, type or copy and paste an URL(s) in the _URL_ field, making sure multiple URLs are separated by carriage returns, then click **Next**.
3. (optional) Click the edit button ![Edit icon](../assets/icons/edit.svg) to view asset metadata and define an _Alternative text_ and a _Caption_ for the asset (see [editing assets](#editing-assets)).
4. (optional) Add more assets by clicking **Add new assets** and going back to step 2.
5. Click on **Upload x assets to the library** (where x represents the number of new assets to be added).

::: caution Drag'n'drop bug
There currently is a bug preventing the use of the drag & drop feature on Firefox and Chrome. Our team is currently working on solving this issue.
:::

## Editing assets

![🏞 screenshot - "Details" popup]()

- overlay control buttons
  - delete asset
  - download asset
  - copy link to asset
  - (optional, image files) crop image
- view & edit metadata
  - view file metadata
  - edit alternative text and caption
- replace media
