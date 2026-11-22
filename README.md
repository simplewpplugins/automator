# authomator

## Description

Git Auto Publisher Dummy Plugin is a lightweight WordPress plugin created to test the automated GitHub publishing process using WP Local GitHub Publisher.

This plugin was auto published by the Git Auto Publisher tool from a local machine.

The plugin demonstrates how WordPress plugin code can be uploaded, versioned, committed, and published to GitHub automatically, including version-specific branches, Git tags, release notes, and downloadable ZIP assets.

This plugin is intended for development and testing purposes only.

## Installation

1. Download the `git-auto-publisher.zip` file.
2. Log in to your WordPress admin dashboard.
3. Navigate to **Plugins → Add New Plugin → Upload Plugin**.
4. Select the downloaded ZIP file.
5. Click **Install Now**.
6. Activate **Git Auto Publisher dummy plugin**.

Alternatively, extract the ZIP file into the `/wp-content/plugins/` directory and activate it from the WordPress Plugins page.

No additional configuration is required.

## Usage

This plugin is intended to demonstrate and test the automated GitHub release workflow.

### How to Use

1. Install and activate the plugin on a local WordPress installation.
2. Open **GitHub Publisher** in the WordPress dashboard.
3. Create a project with the slug `git-auto-publisher`.
4. Configure the GitHub repository URL and Personal Access Token.
5. Upload the plugin ZIP file.
6. Enter the version number `1.0.0`.
7. Provide the release title, release notes, and README documentation.
8. Enable Git tag creation and ZIP attachment.
9. Click **Publish Release**.

After publishing, verify that GitHub contains the updated `main` branch, `v1.0.0` branch, release tag, and downloadable ZIP file.

The dummy plugin itself does not provide any WordPress functionality.

## Changelog

### 1.0.1 — 2026-11-22

## Version 1.0.0 – Initial Release

This is the first release of the **Git Auto Publisher Dummy Plugin**, created to test automated GitHub publishing from a local WordPress installation.

### Features
- Basic WordPress plugin structure.
- Compatible with the WP Local GitHub Publisher tool.
- Includes WordPress plugin headers and documentation.
- Supports automated Git commits, version branches, tags, and GitHub Releases through the publishing tool.

### Testing Objectives
- Verify automatic code publishing to GitHub.
- Verify creation of the `v1.0.0` branch and tag.
- Verify generation of the GitHub Release.
- Verify ZIP attachment to the release.
- Verify automatic README.md generation.

**Note:** This is a dummy plugin for testing purposes only. It does not add functionality to WordPress.

## 1.0.0 – Initial Release

- Created the initial dummy WordPress plugin.
- Added standard WordPress plugin headers.
- Added Simple Plugins as the plugin author.
- Added plugin documentation.
- Prepared the plugin for automated GitHub publishing.
- Established the initial version for testing future updates.
