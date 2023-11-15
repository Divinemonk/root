# Contribution Guidelines

Thank you for your interest in contributing to our project! Follow the steps below to contribute:

<br>

## Contributing to Root Guides

### 1. Fork the Repository
- Click the "Fork" button at the top right of [this repository](https://github.com/Divinemonk/root_guides) to create your copy.

### 2. Clone the Repository
- Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/root_guides.git
```

### 3. Create a New Branch
- Create a new branch for your contribution:
```bash
git checkout -b feature/device-rooting
```

### 4. Add Your Root Guide
- In the `devices` directory, create a new folder for the rooted device. The folder name should include the manufacturer, model, and Android version. For example:
```bash
devices/xiaomi/redmi_note_11_android_12
```
- Inside the folder, create a Markdown file following this structure:

```markdown
# Root Guide for Redmi Note 11 running Android 12

## Prerequisites

- List any prerequisites or requirements for the rooting process.

## Steps

1. Step 1 details.
2. Step 2 details.
3. ...

## Additional Notes

- Any additional information or troubleshooting steps.
```

### 5. Commit Your Changes
- Save and commit your changes:
```bash
git add devices/xiaomi/redmi_note_11_android_12/redmi_note_11_android_12.md
git commit -m "Add rooting steps for Redmi Note 11 on Android 12"
```

### 6. Push Your Changes
- Push your changes to your forked repository:
```bash
git push origin feature/device-rooting
```

### 7. Create a Pull Request
- Open a pull request on [the original repository](https://github.com/divinemonk/root_guides). Provide a clear title and description.

### 8. Await Review
- Wait for the maintainers to review your pull request. Be responsive to feedback.

### 9. Stay Engaged
- Collaborate during the review process. Your contribution is appreciated!

Thank you for making our root guides better!
