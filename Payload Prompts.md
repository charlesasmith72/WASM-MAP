Thought for a couple of seconds


Here are the **updated prompt templates**, each one now explicitly calling out the required tool for the WAT use-case example per our Project Instruction:

# Payload Prompt Templates

## Standard Wasm Sections

1. **Custom:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Custom section payload breakdown.
   Remember: Custom sections (ID 0) must use a Binaryen.js WAT use-case example (parseBinary + setFeatures(All)), not wabt.js.
   ```

2. **Type:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Type section payload breakdown.
   Remember: Type is a core section; include a wabt.js WAT use-case example (parseWat, resolveNames, validate, toBinary, instantiate).
   ```

3. **Import:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Import section payload breakdown.
   Remember: Import is a core section; include a wabt.js WAT use-case example.
   ```

4. **Function:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Function section payload breakdown.
   Remember: Function is a core section; include a wabt.js WAT use-case example.
   ```

5. **Table:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Table section payload breakdown.
   Remember: Table is a core section; include a wabt.js WAT use-case example.
   ```

6. **Memory:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Memory section payload breakdown.
   Remember: Memory is a core section; include a wabt.js WAT use-case example.
   ```

7. **Global:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Global section payload breakdown.
   Remember: Global is a core section; include a wabt.js WAT use-case example.
   ```

8. **Export:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Export section payload breakdown.
   Remember: Export is a core section; include a wabt.js WAT use-case example.
   ```

9. **Start:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Start section payload breakdown.
   Remember: Start is a core section; include a wabt.js WAT use-case example.
   ```

10. **Element:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate an Element section payload breakdown.
    Remember: Element is a core section; include a wabt.js WAT use-case example.
    ```

11. **Code:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Code section payload breakdown.
    Remember: Code is a core section; include a wabt.js WAT use-case example.
    ```

12. **Data:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Data section payload breakdown.
    Remember: Data is a core section; include a wabt.js WAT use-case example.
    ```

13. **DataCount:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a DataCount section payload breakdown.
    Remember: DataCount is a core section; include a wabt.js WAT use-case example.
    ```

---

## Proposal-Based Sections / Features

1. **Exception Handling:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Exception Handling feature payload breakdown.
   Remember: this is a non-core feature; include a Binaryen.js WAT use-case example.
   ```

2. **Garbage Collection (GC) / Typed Objects:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Garbage Collection (GC) / Typed Objects feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

3. **Typed Function References:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Typed Function References feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

4. **Module Linking:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Module Linking feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

5. **Component Model (Interfaces & Components):**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Component Model (Interfaces & Components) feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

6. **Tail Calls:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Tail Calls feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

7. **Bulk Memory Operations:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Bulk Memory Operations feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

8. **Multi-Value Returns:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Multi-Value Returns feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

9. **Reference Types (funcref, externref):**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Reference Types (funcref, externref) feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

10. **Mutable Globals:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Mutable Globals feature payload breakdown.
    Remember: non-core feature; include a Binaryen.js example.
    ```

11. **Non-trapping Float-to-Int Conversions:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Non-trapping Float-to-Int Conversions feature payload breakdown.
    Remember: non-core feature; include a Binaryen.js example.
    ```

12. **Sign-Extension Operators:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Sign-Extension Operators feature payload breakdown.
    Remember: non-core feature; include a Binaryen.js example.
    ```

13. **Extended Constant Expressions:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate an Extended Constant Expressions feature payload breakdown.
    Remember: non-core feature; include a Binaryen.js example.
    ```

---

## Experimental / Flag-Gated Features

1. **Threads & Atomics:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Threads & Atomics feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

2. **SIMD (128-bit):**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a SIMD (128-bit) feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

3. **Relaxed SIMD:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Relaxed SIMD feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

4. **Multi-Memory:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Multi-Memory feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

5. **Memory64 (64-bit memories):**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Memory64 (64-bit memories) feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

6. **Annotations / Custom-Section Annotations:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate an Annotations / Custom-Section Annotations feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

7. **Code Metadata:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Code Metadata feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

8. **Target-Features Metadata:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Target-Features Metadata feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

9. **Source-Mapping URL Section:**

   ```text
   Using Type Section Payload Breakdown Template.md as the master outline,
   please generate a Source-Mapping URL Section feature payload breakdown.
   Remember: non-core feature; include a Binaryen.js example.
   ```

10. **Producers Metadata:**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Producers Metadata feature payload breakdown.
    Remember: non-core feature; include a Binaryen.js example.
    ```

11. **Relocation Sections (reloc.\*):**

    ```text
    Using Type Section Payload Breakdown Template.md as the master outline,
    please generate a Relocation Sections (reloc.*) feature payload breakdown.
    Remember: non-core feature; include a Binaryen.js example.
    ```
