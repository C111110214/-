
# 🚨 Inner Wheel Alert GitHub Pages Frontend

This is the frontend for the Raspberry Pi inner wheel warning system.

## 🔧 Setup Instructions

1. Host this HTML on GitHub Pages (public repository required).
2. Make sure your Raspberry Pi is running the Flask server on `http://192.168.1.166:5000`.
3. The webpage will fetch alerts from `/get_warning` every second.
4. Replace the IP in `index.html` with your Pi's local IP if needed.

## 📦 Files

- `index.html`: Main alert display page (auto-refresh every second)
- `.nojekyll`: Prevent GitHub Pages from treating the repo as Jekyll site

## 🌐 Example Deployment

Once deployed: `https://your-username.github.io/inner-wheel-alert/`
