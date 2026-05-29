# Paralele Istorice Publishing Dashboard

Public review site for the Paralele Istorice creator publishing workflow.

## What the app does

Paralele Istorice Publishing Dashboard helps the creator prepare and publish original short-form history videos to connected social platforms, including TikTok. The workflow lets the creator select an original video, review publishing metadata, edit the caption and hashtags, choose visibility and interaction settings, and explicitly approve the upload before anything is posted.

## TikTok integration

The TikTok integration uses Login Kit and the Content Posting API. After the creator connects their TikTok account, the app can show the connected account, prepare a Direct Post request, upload an approved video, poll publishing status, and report success or failure.

Requested scopes:

- `user.info.basic`
- `user.info.profile`
- `user.info.stats`
- `video.list`
- `video.publish`

## Publishing flow

1. The creator selects a local original short-form video.
2. The app loads campaign metadata: title, caption, hashtags, and platform notes.
3. The creator reviews and can edit the caption before publishing.
4. The creator reviews TikTok privacy and interaction settings.
5. The app shows a STOP preview and requires explicit approval before upload.
6. After approval, the app uploads the video and polls TikTok publishing status.

The app never publishes silently. Every post requires a visible preview and explicit creator confirmation.

## Review URLs

- Website: https://brewdwaf.github.io/
- Terms of Service: https://brewdwaf.github.io/terms.html
- Privacy Policy: https://brewdwaf.github.io/privacy.html

## Site verification

This repository hosts TikTok Developer URL-prefix verification files at the site root.
