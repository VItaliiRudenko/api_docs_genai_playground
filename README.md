# Sports-Hub API Documentation

## Overview
This project provides comprehensive documentation for the Sports-Hub API and related applications. It includes guides, endpoint references, and usage examples for various Sports-Hub platform components, including Angular, React, .NET, and Ruby skeletons.

## Features
- API endpoint documentation
- Guides for multiple frameworks (Angular, React, .NET, Ruby)
- Example requests and responses
- Authentication and error handling guides
- Project structure and architecture notes

## Project Structure
```
api_docs_genai_playground/   # Main documentation and docs generator
sports_hub_angular_skeleton/ # Angular frontend skeleton
sports_hub_net_skeleton/     # .NET backend skeleton
sports_hub_react_skeleton/   # React frontend skeleton
sports_hub_ruby_skeleton/    # Ruby on Rails backend skeleton
sports-hub/                  # General project documentation and requirements
```

## Getting Started
1. Clone this repository.
2. Install Rancher Desktop by following the [Installation Guide](https://docs.rancherdesktop.io/getting-started/installation/#macos)
   - Ensure to select "docker (moby)" for docker-compose compatibility
   - In case of compatibility issues, Administrative Access might be required: Rancher Desktop -> Preferences -> Application -> Administrative Access
3. Navigate to the `api_docs_genai_playground` directory.
4. Install dependencies:
   ```sh
   npm install
   ```
5. Start the documentation server:
   ```sh
   npm run dev
   ```
6. Open [http://localhost:3000](http://localhost:3000) in your browser to view the docs.

## Usage
Browse the documentation site for API references, guides, and examples. Refer to the `docs/` directory for additional language-specific documentation (e.g., PHP).

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or corrections.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or support, please contact the project maintainers.
