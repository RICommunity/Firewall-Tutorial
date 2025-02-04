# AI Firewall-Tutorial

The Robust Intelligence AI Firewall is a model-agnostic, external guardrail that secures LLM-powered applications from prompt injection, PII extraction, and other harmful actions and content. Informed by our proprietary threat intelligence, it validates model inputs and outputs in real-time and can be configured to block or modify undesired responses.

This notebook is a tutorial for using the AI Firewall Python SDK. For complete setup and documentation of the Firewall, please see the user guide.

### Install the SDK
The legacy Firewall SDK is included in the Robust Intelligence RIME SDK. You can install it via pip  as shown here:

`pip install rime-sdk==2.10.16`

Note: If you run into issues, check to see if there is a newer 2.10 patch version  to install here: https://pypi.org/project/rime-sdk/

See Firewall SDK and REST API, above, for more information about the SDK.
