## Improving performance for {% data variables.product.prodname_copilot_chat %}

{% data variables.product.prodname_copilot_chat_short %} can support a wide range of practical applications like code generation, code analysis, and code fixes, each with different performance metrics and mitigation strategies. To enhance performance and address some of the limitations of {% data variables.product.prodname_copilot_chat_short %}, there are various measures that you can adopt. For more information on the limitations of {% data variables.product.prodname_copilot_chat_short %}, see [Limitations of {% data variables.product.prodname_copilot_chat %}](/copilot/github-copilot-chat/copilot-chat-in-ides/about-github-copilot-chat-in-your-ide#limitations-of-github-copilot-chat).

### Keep your prompts on topic

{% data variables.product.prodname_copilot_chat_short %} is intended to address queries related to coding exclusively. Therefore, limiting the prompt to coding questions or tasks can enhance the model's output quality.

### Use {% data variables.product.prodname_copilot_chat_short %} as a tool, not a replacement

While {% data variables.product.prodname_copilot_chat_short %} can be a powerful tool for generating code, it is important to use it as a tool rather than a replacement for human programming. You should always review and test the code generated by {% data variables.product.prodname_copilot_chat_short %} to ensure that it meets your requirements and is free of errors or security concerns.

### Use secure coding and code review practices

While {% data variables.product.prodname_copilot_chat_short %} can generate syntactically correct code, it may not always be secure. You should always follow best practices for secure coding, such as avoiding hard-coded passwords or SQL injection vulnerabilities, as well as following code review best practices, to address {% data variables.product.prodname_copilot_chat_short %}'s limitations.

### Provide feedback

If you encounter any issues or limitations with {% data variables.product.prodname_copilot_chat_short %}, we recommend that you provide feedback through the **share feedback** link in the {% data variables.product.prodname_copilot_chat_short %} interface of your IDE. This can help the developers to improve the tool and address any concerns or limitations.

### Stay up to date

{% data variables.product.prodname_copilot_chat_short %} is a new technology and is likely to evolve over time. You should stay up to date with any updates or changes to the tool, as well as any new security risks or best practices that may emerge. Automated extension updates are enabled by default in {% data variables.product.prodname_vscode %}, {% data variables.product.prodname_vs %}, and the JetBrains suite of IDEs. For {% data variables.product.prodname_copilot_chat_dotcom %} you will always have access to the latest product experience. If you have automatic updates enabled, {% data variables.product.prodname_copilot_chat_short %} will automatically update to the latest version when you open your IDE. For more information on automatic updates in your IDE, see [the {% data variables.product.prodname_vscode %} documentation](https://code.visualstudio.com/docs/editor/extension-marketplace), [the {% data variables.product.prodname_vs %} documentation](https://learn.microsoft.com/en-us/visualstudio/ide/finding-and-using-visual-studio-extensions) and [the documentation for your JetBrains IDE](https://www.jetbrains.com/help).
