# Tauri + SvelteKit + TypeScript

This template should help get you started developing with Tauri, SvelteKit and TypeScript in Vite.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Svelte](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer).

## Advantages of Axum for FastAPI Migration

- Similar syntax: Extractors are similar to FastAPI dependencies
- Type safety: Better than Python with compile-time validation
- Performance: ~10x faster than FastAPI
- Ecosystem: Integrates well with tokio (familiar async/await)
- Documentation: Good for those coming from Python

Recommendation: Start with Axum. It's the closest to FastAPI in terms of ergonomics and has excellent migration documentation.

Use `npm install ; npm run tauri dev` to build and run a simple SvelteKit App as a Desktop application on MacOS, Linux or Windows.

The executable wil be avaiable in `src-tauri/target/debug/my-tauri-app`
