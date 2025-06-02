# greenconf

- [greenconf](https://fossdot.github.io/greenconf) - A directory of vendors to organize eco-friendly conferences and meetups in India


## Contributing

Want to add a new vendor or update existing information? Here's how you can contribute:

1. Fork the repository:
   - Go to https://github.com/fossdot/greenconf
   - Click the "Fork" button in the top right
   - This creates your own copy of the repository

2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/greenconf.git
   cd greenconf
   ```

3. Install dependencies:
   ```bash
   pip3 install dirmaker
   ```

4. Make your changes:
   - Edit `data.yml` to add/update vendor information
   - Follow the existing format in the file
   - Make sure to include all required fields

5. Test your changes locally:
   ```bash
   dirmaker --build
   cd site
   python3 -m http.server 8000
   ```
   Visit http://localhost:8000 to preview

6. Commit and push:
   ```bash
   git add data.yml
   git commit -m "Add [vendor name]" # or "Update [vendor name]"
   git push origin main
   ```

7. Create a Pull Request:
   - Go to https://github.com/fossdot/greenconf
   - Click "Pull requests" > "New pull request"
   - Select "compare across forks"
   - Select your fork and branch
   - Click "Create pull request"
   - Fill in the description template
   - Submit!

We'll review your contribution and merge it if everything looks good. Thank you for helping make conferences more eco-friendly! 🌱

## License

Licensed under [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) 