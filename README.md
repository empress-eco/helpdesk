<div align="center">
    <a href="https://empress.eco/">
        <img src="https://avatars.githubusercontent.com/u/46308912?s=96&v=4" height="50">
    </a>
    <h2>Empress Support</h2>
    <p align="center">
        <p>Empower your customers.</p>
    </p>

[https://empress.eco/app/support/](https://empress.eco/app/support/)

</div>


## About The Project

### Overview

Empress Support is your comprehensive solution for delivering seamless, efficient customer support. Built for businesses of all sizes, our platform enhances your support process, making it easy for customers to find help and resolve issues on their own.

### Key Features

- **Ticket Creation:** Create tickets from emails or directly from a help center.
- **Knowledge Base:** Equip your customers with a comprehensive, easy-to-navigate knowledge base for self-service support.
- **Task Automation:** Simplify your workflow with automated tasks such as agent assignment, and set up triggers for notifications.

## Getting Started

### Technical Stack and Setup Instructions

Empress Support is built with Node.js and leverages the yarn package manager. To get started, ensure you have these installed on your system:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

Clone the project using the following command:

```sh
git clone https://github.com/empress-eco/support.git
```

Once cloned, set up the project using these commands:

```sh
bench get-app helpdesk
bench new-site helpdesk.test
bench --site helpdesk.test install-app helpdesk
bench --site helpdesk.test add-to-hosts
```

Access Empress Support at http://helpdesk.test.

For development, run:

```sh
yarn
yarn dev
```
The development server will be available at http://localhost:8080.

## Usage

Empress Support is designed to be intuitive and easy to use. Manage customer issues, provide a comprehensive knowledge base for self-service, and automate repetitive tasks to enhance the efficiency of your customer service operations.

## Contribution Guidelines

We welcome community contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

We look forward to your input. Make sure to check out our issues page for upcoming features and bug fixes.

## License and Acknowledgements

This project is under the [MIT License](https://opensource.org/licenses/MIT). Your contributions are also licensed under the MIT License.

Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

Thank you to all our contributors and users for their support and feedback. Your participation helps us make Empress Support better. We appreciate your effort and look forward to growing together.
