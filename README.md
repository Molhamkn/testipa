# Test App

Simple iOS app with a text box.

## How to Use

1. **Push to GitHub**: Create a repo and push this code
2. **Run Workflow**: Go to Actions → Build iOS IPA → Run workflow
3. **Download IPA**: Download from the workflow artifacts
4. **Install**: Use TrollStore to install the unsigned IPA

## Development

```bash
# Install dependencies
npm install

# Add iOS platform (on macOS)
npx cap add ios

# Run in browser
npx cap serve

# Sync changes
npx cap sync
```
