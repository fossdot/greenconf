# Greenconf

A directory of vendors to organize eco-friendly conferences and meetups in India.

## Project Structure

- `site/` - Source files for development
- `static/` - Static assets (CSS, JS, images)
- `config.yml` - Site configuration
- `data.yml` - Vendor data
- `template.html` - HTML template
- `build.py` - Build script for generating development and production files

## Development

1. Run the development server:
```bash
python3 -m http.server 8000
```

2. Visit http://localhost:8000 in your browser

## Building

- For development (with localhost URLs):
```bash
./build.py
```

- For production (with GitHub Pages URLs):
```bash
./build.py --prod
```

The built files will be in the `root/` directory.

## License

Licensed under [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/). 