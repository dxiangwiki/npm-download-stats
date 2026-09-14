English | [简体中文](./README_zh.md)

# NPM Package Historical Total Download Query
A pure frontend web tool to query the total historical downloads of npm packages.

## Features
- Query download statistics for a single npm package
- Batch query all public packages by npm author username
- Automatically generate SVG trend charts for daily downloads
- Chinese / English bilingual UI switch
- Dark / Light theme toggle
- Save language and theme preferences to localStorage
- No backend required; uses official npm registry & download APIs

## Usage
1. Switch mode: `Single Package Query` / `Batch by Author`
2. Input package name or npm author username
3. Click the Query button
4. View cumulative download data and trend chart

> Notes:
> 1. Subject to npm official API rate limits. Batch queries for authors with many packages may partially fail.
> 2. Download statistics data is only available from around 2015.
> 3. Users in mainland China may encounter network timeouts when accessing the npm API.

## Deploy
You can deploy this project directly on GitHub Pages:
1. Fork or clone this repo
2. Enable GitHub Pages in repository settings, set source to the `main` branch / root folder
3. Visit your Pages website

## License
MIT License
Copyright (c) 2026 Dong Xiang
