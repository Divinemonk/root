# Contribution Guidelines

Thank you for considering contributing to our project! We appreciate your efforts in sharing your knowledge. Please follow the guidelines below to contribute:

## Contributing to Root Guides

If you have successfully rooted any device and would like to share the steps with the community, follow these steps:

1. Fork this repository to your GitHub account.

2. Clone the forked repository to your local machine:
   ```bash
   git clone https://github.com/divinemonk/root
Create a new branch for your contribution:

bash
Copy code
git checkout -b feature/device-rooting
In the root directory of the repository, create a new file with the following naming convention:

Copy code
devices/{company}/{device_name}_{android_version}.md
Replace {company}, {device_name}, and {android_version} with the relevant information. For example, xiaomi/redmi_note_11_android_12.md.

Add the rooting steps in Markdown format to the file you created. Use the following template:

markdown
Copy code
# Root Guide for {Device Name} running Android {Android Version}

## Prerequisites
- List any prerequisites or requirements for the rooting process.

## Steps

1. Step 1 details.
2. Step 2 details.
3. ...

## Additional Notes
- Any additional information or troubleshooting steps.
Save the file.

Commit your changes with a meaningful commit message:

bash
Copy code
git add devices/{company}/{device_name}_{android_version}.md
git commit -m "Add rooting steps for {Device Name} running Android {Android Version}"
Push your changes to your GitHub repository:

bash
Copy code
git push origin feature/device-rooting
Create a pull request from your forked repository to the original repository.

In the pull request description, provide a brief summary of the rooting steps and any additional information.

Wait for the maintainers to review your contribution. You may be asked to make changes or provide more details.

Thank you for contributing! Your knowledge sharing helps the community grow.
