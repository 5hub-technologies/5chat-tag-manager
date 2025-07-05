# 5chat Google Tag Manager Template

A Google Tag Manager template for easily integrating [5chat.io](https://5chat.io) live chat software into your website.

## Overview

[5chat.io](https://5chat.io) is a performance-focused live chat software designed for websites that prioritizes user experience and website performance. This Google Tag Manager template provides a simple way to deploy 5chat on your website without manual code implementation.

### Key Features of 5chat

- **Ultra-fast performance**: Loads in <50ms with a <15kb bundle size
- **Performance-optimized**: Minimal impact on Core Web Vitals
- **AI-powered**: Automatic conversation tagging and real-time AI summaries
- **User-friendly**: Intuitive interface mimicking familiar messaging apps
- **Easy customization**: Customizable chat appearance and user metadata

## Installation

### Using Google Tag Manager (Recommended)

1. **Add the 5chat Template**
   - In Google Tag Manager, go to **Tags** > **New**
   - Click **Tag Configuration**
   - Search for "5chat" in the Community Template Gallery
   - Select the **5chat** template and click **Add to Workspace**

2. **Configure the Tag**
   - Enter your **Client Token** from your 5chat dashboard
   - Name your tag (e.g., "5chat Live Chat")

3. **Set Up Trigger**
   - Click **Triggering** and select **All Pages** trigger
   - This will load the chat widget on all pages of your website

4. **Publish**
   - Click **Save** and then **Submit** to publish your changes
   - Your 5chat widget will now be live on your website

### Getting Your Client Token

1. Sign up at [5chat.io](https://5chat.io)
2. Complete the onboarding process
3. In your 5chat dashboard, navigate to **Settings** > **Installation**
4. Copy your unique **Client Token**
5. Use this token in the Google Tag Manager template configuration

### Manual Installation

If you prefer to install 5chat manually without this template:

1. Visit [5chat.io](https://5chat.io)
2. Sign up for an account
3. Follow the integration instructions in your dashboard
4. Add the provided code snippet to your website

## Configuration

The template requires only one configuration option:

- **Client Token**: Your unique 5chat client token from your dashboard (required)

Get your Client Token from your 5chat dashboard under Settings > Installation.

## Documentation

- **5chat Documentation**: [https://5chat.io/en/docs](https://5chat.io/en/docs)
- **5chat Homepage**: [https://5chat.io](https://5chat.io)


## License

This template is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please:
1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Changelog

See `metadata.yml` for version history and changes.
