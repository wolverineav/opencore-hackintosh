# USB Port Mapping

## USB Controllers

| USB Controller Name | Raw ACPI Path | Canonical ACPI Path |
| ------------------- | ------------- | ----------------- |
| XHC0 | IOService:/AppleACPIPlatformExpert/PCI0@0/AppleACPIPCI/BXBR@1,2/IOPP/BYUP@0/IOPP/BYD8@8/IOPP/XHC0@0,3/XHC0@61000000 | PCI0.BXBR.BYUP.BYD8.XHC0 |
| XHC2 | IOService:/AppleACPIPlatformExpert/PCI0@0/AppleACPIPCI/BXBR@1,2/IOPP/BYUP@0/IOPP/BYD8@8/IOPP/XHC2@0,1/XHC2@20000000 | PCI0.BXBR.BYUP.BYD8.XHC2 |
| XHC3 | IOService:/AppleACPIPlatformExpert/PCI0@0/AppleACPIPCI/GP13@8,1/IOPP/XHC3@0,3/XHC3@60000000 | PCI0.GP13.XHC3 |

## USB Ports

### Top - USB 3.2 - 10Gbps

| USB Controller | Port Name | Type | Port Description |
| -------------- | --------- | ---- | ---------------- |
| XHC2 | PRT1 | 3 | Rear USB 3.2 Type A, 2.0 Personality, Top Row, 1 |
| XHC2 | PRT7 | 3 | Rear USB 3.2 Type A, 3.0 Personality, Top Row, 1 |
| XHC2 | PRT2 | 3 | Rear USB 3.2 Type A, 2.0 Personality, Top Row, 2 |
| XHC2 | PRT8 | 3 | Rear USB 3.2 Type A, 3.0 Personality, Top Row, 2 |

### Middle - USB 3.1 - 5Gbps

| USB Controller | Port Name | Type | Port Description |
| -------------- | --------- | ---- | ---------------- |
| XHC3 | PRT1 | 3 | Rear USB 3.1 Type A, 2.0 Personality, Mid Row, 1 |
| XHC3 | PRT5 | 3 | Rear USB 3.1 Type A, 3.0 Personality, Mid Row, 1 |
| XHC3 | PRT2 | 3 | Rear USB 3.1 Type A, 2.0 Personality, Mid Row, 2 |
| XHC3 | PRT6 | 3 | Rear USB 3.1 Type A, 3.0 Personality, Mid Row, 2 |
| XHC3 | PRT3 | 3 | Rear USB 3.1 Type A, 2.0 Personality, Mid Row, 3 |
| XHC3 | PRT7 | 3 | Rear USB 3.1 Type A, 3.0 Personality, Mid Row, 3 |
| XHC3 | PRT4 | 3 | Rear USB 3.1 Type A, 2.0 Personality, Mid Row, 4 |
| XHC3 | PRT8 | 3 | Rear USB 3.1 Type A, 3.0 Personality, Mid Row, 4 |

### Lower - USB 3.2 - 10Gbps

| USB Controller | Port Name | Type | Port Description |
| -------------- | --------- | ---- | ---------------- |
| XHC2 | PRT3 | 3 | Rear USB 3.2 Type A, 2.0 Personality, Low Row, 1 |
| XHC2 | PRT9 | 3 | Rear USB 3.2 Type A, 3.0 Personality, Low Row, 1 |
| XHC0 | PRT3 | 10 | Rear USB 3.2 Type C, 2.0 Personality, Low Row, 2 |
| XHC0 | PRT9 | 10 | Rear USB 3.2 Type C, 3.0 Personality, Low Row, 2 |
| XHC0 | PRT4 | 10 | Rear USB 3.2 Type C, 2.0 Personality, Low Row, 2, Flipped |
| XHC0 | PT10 | 10 | Rear USB 3.2 Type C, 3.0 Personality, Low Row, 2, Flipped |
