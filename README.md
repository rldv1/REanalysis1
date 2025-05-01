# REanalysis Day 1
**ru.fieldtest.modemcaps** is an Android app that enables deep-level control of the Qualcomm cellular modem. Mostly this tool is designed for engineers and advanced users who need detailed insight and control over GSM/UMTS/LTE/NR modem behavior.

---

## 🔍 Code Analysis

The codebase is **heavily obfuscated**, likely to prevent reverse engineering. Key indicators:

- **Class and method names** are short and meaningless (e.g., `a`, `mo87a`, `c.a(...)`).
- **String constants** are dynamically resolved via long-integer keys and utf16 encoded string tables

#### Example:

![obraz](https://github.com/user-attachments/assets/8537d52c-5362-4590-8c51-70bd9db1f723)

This is a very interesting technique

![photo_2025-05-02_00-03-36](https://github.com/user-attachments/assets/2d3d141f-ff24-4fdd-b7ec-ac8999e2a724)

TODO
