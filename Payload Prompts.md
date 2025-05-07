# Payload Prompt Templates

## Standard Wasm Sections

1. **Custom:**

   ```text
   Please generate a Custom section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js only** (call `setFeatures(All)`; no WABT.js).
     • Follow the Type Section template structure exactly (bytes → table → example → mapping).

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Custom section payload breakdown.
   ```

2. **Type:**

   ```text
   Please generate a Type section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** (parseWat, resolveNames, validate, toBinary, instantiate).
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Type section payload breakdown.
   ```

3. **Import:**

   ```text
   Please generate an Import section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Import section payload breakdown.
   ```

4. **Function:**

   ```text
   Please generate a Function section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Function section payload breakdown.
   ```

5. **Table:**

   ```text
   Please generate a Table section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Table section payload breakdown.
   ```

6. **Memory:**

   ```text
   Please generate a Memory section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Memory section payload breakdown.
   ```

7. **Global:**

   ```text
   Please generate a Global section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Global section payload breakdown.
   ```

8. **Export:**

   ```text
   Please generate an Export section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Export section payload breakdown.
   ```

9. **Start:**

   ```text
   Please generate a Start section payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **wabt.js** for the WAT example.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Start section payload breakdown.
   ```

10. **Element:**

    ```text
    Please generate an Element section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate an Element section payload breakdown.
    ```

11. **Code:**

    ```text
    Please generate a Code section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Code section payload breakdown.
    ```

12. **Data:**

    ```text
    Please generate a Data section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Data section payload breakdown.
    ```

13. **DataCount:**

    ```text
    Please generate a DataCount section payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **wabt.js** for the WAT example.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a DataCount section payload breakdown.
    ```

## Proposal-Based Sections / Features

1. **Exception Handling:**

   ```text
   Please generate an Exception Handling feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only (call `setFeatures(All)`; no WABT.js).
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Exception Handling feature payload breakdown.
   ```

2. **Garbage Collection (GC) / Typed Objects:**

   ```text
   Please generate a Garbage Collection (GC) / Typed Objects feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Garbage Collection (GC) / Typed Objects feature payload breakdown.
   ```

3. **Typed Function References:**

   ```text
   Please generate a Typed Function References feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Typed Function References feature payload breakdown.
   ```

4. **Module Linking:**

   ```text
   Please generate a Module Linking feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Module Linking feature payload breakdown.
   ```

5. **Component Model (Interfaces & Components):**

   ```text
   Please generate a Component Model (Interfaces & Components) feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Component Model (Interfaces & Components) feature payload breakdown.
   ```

6. **Tail Calls:**

   ```text
   Please generate a Tail Calls feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Tail Calls feature payload breakdown.
   ```

7. **Bulk Memory Operations:**

   ```text
   Please generate a Bulk Memory Operations feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Bulk Memory Operations feature payload breakdown.
   ```

8. **Multi-Value Returns:**

   ```text
   Please generate a Multi-Value Returns feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Multi-Value Returns feature payload breakdown.
   ```

9. **Reference Types (funcref, externref):**

   ```text
   Please generate a Reference Types (funcref, externref) feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Reference Types (funcref, externref) feature payload breakdown.
   ```

10. **Mutable Globals:**

    ```text
    Please generate a Mutable Globals feature payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **Binaryen.js** only.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Mutable Globals feature payload breakdown.
    ```

11. **Non-trapping Float-to-Int Conversions:**

    ```text
    Please generate a Non-trapping Float-to-Int Conversions feature payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **Binaryen.js** only.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Non-trapping Float-to-Int Conversions feature payload breakdown.
    ```

12. **Sign-Extension Operators:**

    ```text
    Please generate a Sign-Extension Operators feature payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **Binaryen.js** only.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Sign-Extension Operators feature payload breakdown.
    ```

13. **Extended Constant Expressions:**

    ```text
    Please generate an Extended Constant Expressions feature payload breakdown.
    Must-Haves:
      • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
      • Use **Binaryen.js** only.
      • Follow the Type Section template structure exactly.

    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate an Extended Constant Expressions feature payload breakdown.
    ```

## Experimental / Flag-Gated Features

1. **Threads & Atomics:**

   ```text
   Please generate a Threads & Atomics feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Threads & Atomics feature payload breakdown.
   ```

2. **SIMD (128-bit):**

   ```text
   Please generate a SIMD (128-bit) feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a SIMD (128-bit) feature payload breakdown.
   ```

3. **Relaxed SIMD:**

   ```text
   Please generate a Relaxed SIMD feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Relaxed SIMD feature payload breakdown.
   ```

4. **Multi-Memory:**

   ```text
   Please generate a Multi-Memory feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Multi-Memory feature payload breakdown.
   ```

5. **Memory64 (64-bit memories):**

   ```text
   Please generate a Memory64 (64-bit memories) feature payload breakdown.
   Must-Haves:
     • Declare the entire WAT snippet inline as `const wat = …` before any parse or instantiate calls.
     • Use **Binaryen.js** only.
     • Follow the Type Section template structure exactly.

   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Memory64 (64-bit memories) feature payload breakdown.
   ```

6. **Annotations / Custom-Section Annotations:**

   ```text
   Please generate an Annotations / Custom-Section Annotations feature payload breakdown.
   Must-Haves:
   ```
