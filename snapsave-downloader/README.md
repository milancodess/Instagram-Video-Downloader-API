# snapsave-downloader

## Overview
snapsave-downloader is a JavaScript package created to simplify the process of downloading videos from Instagram and Facebook. With a focus on simplicity and efficiency, this tool allows you to integrate video downloading capabilities seamlessly into your web applications.

## Features
- **Cross-Platform Compatibility:** Download videos from both Instagram and Facebook using JavaScript, making it easy to integrate into various web environments.
- **Straightforward Integration:** Incorporate snapsave-downloader into your web projects effortlessly to enhance your video downloading functionalities.
- **Lightweight and Fast:** Enjoy a quick and responsive download process without unnecessary complexity, ensuring optimal performance.
- **User-Friendly:** Designed with a user-friendly interface, snapsave-downloader provides an intuitive experience for hassle-free video downloads.

## Getting Started
1. Install snapsave-downloader using npm: `❌| not published on npm yet`.
2. Import the package in your JavaScript file.
3. Use the provided functions to download videos from Instagram and Facebook effortlessly.

## Example
```js
git clone https://github.com/milanproo/snapsave-downloader
const snapsave = require('./snapsave-downloader');
let URL = await snapsave("https://www.instagram.com/tv/CdmYaq3LAYo/")
console.log(URL)
```
## Output Example
```
{
  developer: '@Milan Bhandari',
  status: true,
  data: [
    {
      thumbnail: 'https://d.rapidcdn.app/d?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1cmwiOiJodHRwczovL3Njb250ZW50LmNkbmluc3RhZ3JhbS5jb20vdi90NTEuMjg4NS0xNS8zNDIxMzI5OTFfMTM5MzQxNjczMTM5Mjk4MF80ODU0MzQ3ODMwMDQyNzk2MjEzX24ud2VicD9zdHA9ZHN0LWpwZ19lMzVfczY0MHg2NDBfc2gwLjA4Jl9uY19odD1zY29udGVudC5jZG5pbnN0YWdyYW0uY29tJl9uY19jYXQ9MSZfbmNfb2hjPVZGRGhEelhfQzhBQVgtMkNJcHMmZWRtPUFQczE3Q1VCQUFBQSZjY2I9Ny01JmlnX2NhY2hlX2tleT1NekE0TlRBNU5EWTBNVEUxTnpNMU16RXdOZyUzRCUzRC4yLWNjYjctNSZvaD0wMF9BZkNuR3lLTGlaX3JQbHR3WkgteVB2SVoyd203UEpNQXZ1c2VNenMyaU5zRjR3Jm9lPTY0NUY4QkRGJl9uY19zaWQ9OTc4Y2I5IiwiZmlsZW5hbWUiOiJTbmFwc2F2ZS5hcHBfMzQyMTMyOTkxXzEzOTM0MTY3MzEzOTI5ODBfNDg1NDM0NzgzMDA0Mjc5NjIxM19uLmpwZyJ9._pjrTGjnWBJIAOhxRb7uYDu-AsdR5uUmlptUXmYdYMM',
      url: 'https://scontent.cdninstagram.com/v/t51.2885-15/342132991_1393416731392980_4854347830042796213_n.webp?se=7&stp=dst-jpg_e35&_nc_ht=scontent.cdninstagram.com&_nc_cat=1&_nc_ohc=VFDhDzX_C8AAX-2CIps&edm=APs17CUBAAAA&ccb=7-5&ig_cache_key=MzA4NTA5NDY0MTE1NzM1MzEwNg%3D%3D.2-ccb7-5&oh=00_AfD44I7oxMmi9HPX5oAALWH_gJti4Wg5wZmmjFx0uskMkw&oe=645F8BDF&_nc_sid=978cb9&dl=1'
    }
  ]
}
```

## Contributions
Contributions are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [Apache-2.0 license](LICENSE) - see the [LICENSE](LICENSE) file for details.

---

Get started with snapsave-downloader in your JavaScript projects and enhance your video downloading experience on the web!
