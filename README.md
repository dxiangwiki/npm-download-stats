# NPM Package Historical Total Download Query
A pure frontend web tool for query npm package total historical downloads.

## Features
- Single NPM package download statistics query
- Batch query all public packages by npm author name
- Auto generate daily download SVG trend chart
- Chinese / English bilingual switch
- Dark / Light theme toggle (with preview next mode)
- Data saved in localStorage: language & theme preference
- No backend required, use official npm registry & download API

## Usage
1. Switch mode: `Single Package Query` / `Batch by Author`
2. Input package name OR npm author username
3. Click Query button
4. View cumulative download data and trend chart

> Note:
> 1. API rate limit from npm official server. Batch query for author with many packages may partial fail.
> 2. Download statistics data only available starting around year 2015.
> 3. China mainland user may meet network timeout accessing npm API.

## Deploy
You can deploy this project on GitHub Pages directly:
1. Fork / clone this repo
2. Enable GitHub Pages from repo setting, set source to `main` branch / root folder
3. Access your pages website

## License
MIT License

Copyright (c) 2026 Dong Xiang
