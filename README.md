# 📚 Strathon SDKs

Strathon SDKs - Multi-language SDK Monorepo

## 🎯 Overview

This repository contains official SDKs for the Strathon AI Trust Platform in multiple programming languages.

## 📦 Available SDKs

- **Go**: github.com/strathon/sdks/go
- **JavaScript/TypeScript**: @strathon/sdk
- **Python**: strathon-sdk
- **Java**: com.strathon:strathon-sdk

## 🚀 Quick Start

### Go

`go
import "github.com/strathon/sdks/go"

client := strathon.NewClient("your-api-key")
result, err := client.Safeguard(ctx, "user input")
`

### JavaScript/TypeScript

`javascript
import { StrathonClient } from '@strathon/sdk';

const client = new StrathonClient('your-api-key');
const result = await client.safeguard('user input');
`

### Python

`python
from strathon import StrathonClient

client = StrathonClient('your-api-key')
result = client.safeguard('user input')
`

### Java

`java
import com.strathon.StrathonClient;

StrathonClient client = new StrathonClient("your-api-key");
SafeguardResult result = client.safeguard("user input");
`

## 📚 Documentation

- [API Documentation](https://docs.strathon.com.br/api)
- [SDK Documentation](https://docs.strathon.com.br/sdks)
- [Examples](./examples/)
- [Authentication Guide](https://docs.strathon.com.br/authentication)

## 🤝 Contributing

Please read our [Contributing Guide](https://github.com/strathon/core-api/blob/main/CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.