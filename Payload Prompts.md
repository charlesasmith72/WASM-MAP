# Payload Prompt Templates

## Standard Wasm Sections

1. **Custom:**

   ```text
   Please generate a Custom section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` (including the custom section directly in the WAT) before any parse or instantiate calls.
     • Use **Binaryen.js only** to parse and emit binary (e.g. `Binaryen.parseText(wat)` → `module.emitBinary()`), and never call any high-level helper like `setFeatures(All)`.
     • Follow the Type Section template structure exactly (bytes → table → example → mapping).

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Custom section payload breakdown.
   ```

2. **Type:**

   ```text
   Please generate a Type section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** (parseWat, resolveNames, validate, toBinary, instantiate).
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Type section payload breakdown.
   ```

3. **Import:**

   ```text
   Please generate an Import section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Import section payload breakdown.
   ```

4. **Function:**

   ```text
   Please generate a Function section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Function section payload breakdown.
   ```

5. **Table:**

   ```text
   Please generate a Table section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Table section payload breakdown.
   ```

6. **Memory:**

   ```text
   Please generate a Memory section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Memory section payload breakdown.
   ```

7. **Global:**

   ```text
   Please generate a Global section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Global section payload breakdown.
   ```

8. **Export:**

   ```text
   Please generate an Export section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Export section payload breakdown.
   ```

9. **Start:**

   ```text
   Please generate a Start section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Start section payload breakdown.
   ```

10. **Element:**

    ```text
    Please generate an Element section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate an Element section payload breakdown.
    ```

11. **Code:**

    ```text
    Please generate a Code section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Code section payload breakdown.
    ```

12. **Data:**

    ```text
    Please generate a Data section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Data section payload breakdown.
    ```

13. **DataCount:**

    ```text
    Please generate a DataCount section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a DataCount section payload breakdown.
    ```

---

## Proposal-Based Sections / Features

1. **Exception Handling:**

   ```text
   Please generate an Exception Handling feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` (including any custom directives) before any parse or instantiate calls.
     • Use **Binaryen.js only** to parse and emit binary, and never call any high-level helper like `setFeatures(All)`.
     • Follow the Type Section template structure exactly (bytes → table → example → mapping).

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Exception Handling feature payload breakdown.
   ```

2. **Garbage Collection (GC) / Typed Objects:**

   ```text
   Please generate a Garbage Collection (GC) / Typed Objects feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` (including any custom directives) before any parse or instantiate calls.
     • Use **Binaryen.js only** to parse and emit binary, and never call any high-level helper.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Garbage Collection (GC) / Typed Objects feature payload breakdown.
   ```

3. **Typed Function References:**

   ```text
   Please generate a Typed Function References feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` (including any custom directives) before any parse or instantiate calls.
     • Use **Binaryen.js only** to parse and emit binary, and never call any high-level helper.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Typed Function References feature payload breakdown.
   ```

4. **Module Linking:**

   ```text
   Please generate a Module Linking feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as a single JavaScript string constant named `const wat` (including any custom directives) before any parse or instantiate calls.
     • Use **Binaryen.js only** to parse and emit binary, and never call any high-level helper.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Module Linking feature payload breakdown.
   ```

*(Prompts continue similarly for the remaining Proposal-Based and Experimental features.)*
