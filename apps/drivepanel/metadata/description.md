# DrivePanel

**DrivePanel** is a lightweight personal cloud drive (about 40 MB of RAM) built for the Raspberry Pi and any small home server. Its interface is in **English and Spanish** (it follows your browser and can be changed in Settings), with light and dark mode.

> **Important:** the first user who registers becomes the administrator. Create your account right after installing. Later accounts stay pending until the administrator approves them in **Users**.

## Features

- My Drive with folders, grid view with thumbnails or list view, search, rename, move and folder properties
- Upload files and whole folders, with chunked uploads, retries, duplicate warnings and live speed
- Photos grouped by month and by album, recent files, viewer for photos, video, PDF and text, and .zip download
- Trash with restore, also for files deleted over WebDAV
- Share with other users or with a public link that can expire
- Multiple users with admin approval, quotas and profile pictures
- Activity dashboard: uploads per day, disk usage, file types and live system status
- WebDAV per user at `/dav/`, so your phone can back up photos automatically
- Disk full warnings at 85 % and 95 % (configurable), in the web, in the Android app and, optionally, by Telegram
- Watch videos and listen to music without downloading them
- Installable on your phone as an app (PWA), plus an Android app

## Phone backup

Use a WebDAV app (FolderSync, PhotoSync...) with the server `http://<your-server>:8590/dav/` and your DrivePanel username and password.

## Recommended hardware

Raspberry Pi 4 or 5. The Pi 3 works, but with only 1 GB of memory it will be slow with photos, thumbnails and large uploads.

## Security

DrivePanel uses plain HTTP. Do not open its port on your router: use a VPN, or expose it through Runtipi with HTTPS.

## License

PolyForm Noncommercial 1.0.0. Free for personal, family, school and non-profit use; commercial use is not allowed.

[DrivePanel on GitHub](https://github.com/pctecnikk/drivepanel)
