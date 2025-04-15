# command to install shopify globally

npm install -g @shopify/cli@latest

# command to check version

shopify version

# shopify theme pull -h (give us flag values to perform other actions)

# shopify theme pull -e development

→ Fetches live theme files to your computer.

# shopify theme dev -e development

→ Live edits & auto-syncs changes.

# shopify theme pull -d


Command	Purpose
shopify theme pull -d	Download live theme changes (from admin or collaborators) to your local machine.
shopify theme push -d	Upload local changes to your Shopify store.
shopify theme dev -d	Start a live-sync dev server (auto-refreshes changes locally and on the store).
shopify theme serve	Run a local preview server (no real-time sync with the store).