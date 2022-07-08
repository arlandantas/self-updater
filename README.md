# Self-updater
A simple project that creates a self-update page with arguments from URL.

### Page URL
`https://arlandantas.github.io/self-updater?t=TIMEOUT&title=PAGETITLE#PAGEURL`
- `PAGEURL` - The URL to page that will be loaded
- `TIMEOUT` (optional) - The time in seconds that page will be refreshed (if not present "600" [10 minutes] will be considered)
- `PAGETITLE` (opitional) - The page/tab browser title (if not present "Arlan Dantas | Self-updater" will be considered)

### Example
[https://arlandantas.github.io/self-updater?t=20&title=Arlan Dantas#https://arlandantas.github.io](https://arlandantas.github.io/self-updater?t=20&title=Arlan%20Dantas#https://arlandantas.github.io)