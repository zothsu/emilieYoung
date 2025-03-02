# README

## Emilie Young - Birth Doula Portfolio

This is the professional portfolio for Emilie Young, a Birth Doula serving the greater Portland, Oregon area since 2018. The site is built with Hugo to ensure speed, security, and easy maintenance.

### Features
- Clean, responsive design
- Testimonials carousel
- Secure and optimized hosting
- Simple content updates via `hugo.yaml`

## TODO

### Testimonials
- Add details for testimonials in `hugo.yaml`
- Implement a film strip-style carousel for testimonials, allowing users to cycle through manually and automatically advance every 7 seconds
- Upload client photos to Cloudinary (login with GitHub)

### Services
- Add a dedicated services page
- List and describe available doula services
- Include a pricing section (if applicable)
- Add a contact form for service inquiries

### Bugs
- The main photo is not displaying correctly

## Setup & Development

### Prerequisites
Ensure you have the following installed before getting started:
- [Hugo](https://gohugo.io/getting-started/installing/)
- [Go](https://go.dev/doc/install)
- [Node.js](https://nodejs.org/) (if using npm-based dependencies)
- A [Cloudinary](https://cloudinary.com/) account for image hosting

### Running Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/emilie-young-portfolio.git
2. Navigate to project directory:
    ```sh
    cd emilieYoung
    ```
3. Start Hugo development server
    ```sh
    hugo server -D
    ```
4. Open your browser and go to http://localhost:1313/

### Deployment on Hostinger

This project is deployed using Hostinger. To deploy updates or make changes, follow these steps:

1. Build the Static Files. This will generate the static site in the `public/` directory.

```sh
hugo --minify
```

2. Upload to Hostinger
    1. Log in to your Hostinger account.
    2. Navigate to the File Manager or use FTP to upload files.
    3. Replace the existing files in the public directory with the new ones.
        Alternative: Deploy via Git (if using Git-based deployment)
    4. Open your website in a browser to ensure the changes are live.
        If caching issues occur, clear the cache from Hostinger’s control panel.

## Contributing

If you would like to contribute, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
