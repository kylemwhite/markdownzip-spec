# MDZ Specification Project

This workspace contains the **official specification** for the `.mdz` file format — a ZIP‑based, Markdown‑first, portable document container that includes:

- a required `index.md` entry point
- optional additional `.md` files (flat structure)
- a `/media` folder for images and assets
- optional `meta.json` metadata

The goal of this project is to define a **minimal, editor‑friendly, implementation‑agnostic** standard that Markdown tools can adopt.

## What I want from the AI in this workspace

You are assisting in writing a **formal, versioned, open specification**.  
Your responsibilities include:

### 1. Helping draft the spec
- Provide clear, concise, standards‑style language  
- Suggest structure, sections, and terminology  
- Ensure the spec is implementation‑neutral  
- Keep the format minimal and predictable  
- Avoid feature creep unless explicitly requested
- Some initial rules:
   - All text files within an `.mdz` package MUST use LF (`\n`) line endings. CRLF and CR line endings are not permitted. Tools _writing_ `.mdz` files should normalize line endings on save, since the source content might come from a Windows editor. The writer bears responsibility for normalization, not the reader.



### 2. Helping design supporting materials
- Examples of valid `.mdz` packages  
- A conformance test suite outline  
- Versioning rules  
- Compatibility notes  
- Security considerations  

### 3. Helping maintain clarity and rigor
- Use precise language  
- Avoid ambiguity  
- Reference patterns from successful standards (CommonMark, EPUB, TOML)  
- Keep the spec approachable for implementers  

## Project Structure
/spec.md ← the canonical specification 
/examples/ ← sample .mdz structures 
/tests/ ← conformance test cases 
/reference/ ← optional reference notes
## Goals
- Produce a **v1.0** specification suitable for adoption by editors and tools.
- Keep the format intentionally small and easy to implement.
- Provide enough detail for consistent behavior across platforms.

## Non‑Goals
- No editor‑specific features  
- No nested folder hierarchies  
- No plugin systems  
- No scripting or execution model  

---

AI: When responding in this workspace, assume you are contributing to a **real open standard**.  
Prioritize clarity, rigor, and minimalism.



