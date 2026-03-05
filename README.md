# esp-swift

Reusable ESP-IDF components that add [Embedded Swift](https://www.swift.org/documentation/embedded-swift/) support and tooling for ESP-IDF projects.

---

## Components

### [swift_support](swift_support/README.md)

Core component for using Swift in ESP-IDF:

- Configures the Swift compiler for RISC-V ESP targets
- Provides `idf_component_register_swift()` for integrating Swift sources into components
- Handles bridging headers for C/Swift interop

> [!IMPORTANT]
> swift_support is required for any Swift-based ESP-IDF component.

See **[swift_support/README.md](swift_support/README.md)** for usage, parameters, and examples.

---

## More examples

Additional Embedded Swift example projects (including LED blink, UART echo, and others) are in the [swift-embedded-examples](https://github.com/swiftlang/swift-embedded-examples) repository.
