# @dappnode/schemas

This package provides JSON schemas for the dappnode files **setup wizard**, **manifest** and **docker-compose** as well as its JSON schema validation functions to ensure the file provided is valid and follows the specifications.

## Installation

To add this package as a dependency in your project, use the following command:

```bash
npm install @dappnode/schemas

```

## Usage

To utilize the validation functions for the JSON schemas:

```typescript
import {
  validateComposeSchema,
  validateManifestSchema,
  validateSetupWizardSchema,
} from "@dappnode/types";
```

## Contributing

1. Fork the repository and clone it to your local machine.
2. Navigate to the project directory and install the dependencies:

   ```bash
   npm install

   ```

3. Make your changes or additions to the code.
4. Build the project:

   ```bash
   npm run build

   ```

5. Commit and push your changes to your fork.
6. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
