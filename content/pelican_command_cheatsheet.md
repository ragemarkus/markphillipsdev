
# Pelican Command Cheatsheet

## General Commands

1. **Create a new site**:
   ```bash
   pelican-quickstart
   ```

2. **Generate site**:
   ```bash
   pelican content
   ```

3. **Regenerate site on changes**:
   ```bash
   pelican content -r
   ```
   
4. **Preview site**:
   ```bash
   pelican --listen
   ```

5. **Publish site**:
   ```bash
   pelican content -s publishconf.py
   ```

## Content Management

1. **Specify content path**:
   ```bash
   pelican /path/to/content
   ```

2. **Specify output path**:
   ```bash
   pelican /path/to/content -o /path/to/output
   ```

3. **Specify configuration file**:
   ```bash
   pelican /path/to/content -s /path/to/config.py
   ```

## Debugging and Development

1. **Show help**:
   ```bash
   pelican --help
   ```

2. **Verbose output**:
   ```bash
   pelican /path/to/content -v
   ```

3. **Debug output**:
   ```bash
   pelican /path/to/content -D
   ```

4. **Ignore cache**:
   ```bash
   pelican /path/to/content --ignore-cache
   ```

## Themes and Plugins

1. **Specify theme**:
   ```bash
   pelican /path/to/content -t /path/to/theme
   ```

2. **List available plugins**:
   ```bash
   pelican-plugins
   ```

## Server Commands

1. **Start a simple HTTP server**:
   ```bash
   pelican --listen
   ```

2. **Specify server address and port**:
   ```bash
   pelican --listen --port 8000 --bind 127.0.0.1
   ```

## Miscellaneous

1. **Clear output directory**:
   ```bash
   pelican content --delete-output-directory
   ```

2. **Relative URLs**:
   ```bash
   pelican content -r --relative-urls
   ```

3. **Print version**:
   ```bash
   pelican --version
   ```
