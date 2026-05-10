# Aura Presence Engine

Aura is a local-first desktop AI agent project built with Tauri, Rust, React, TypeScript and SQLite. The goal is not to build a generic chat app, but to create a desktop AI companion that can understand long-term memory, tasks, mood, media state and workflow context in a multi-window local workspace.

## Project Overview

Aura focuses on three directions:

- Local-first desktop AI companion
- Multi-window workspace with persistent context
- Presence Engine for memory, reflection and proactive interaction

The project is designed around clear capability boundaries. It does not pretend unfinished abilities are complete, and it does not treat candidate sources or external links as completed actions.

## Current Engineering Scope

Current implemented or in-progress modules include:

- Local SQLite data layer
- Session and long-term memory system
- Today center and mood records
- Personality/profile context
- Media library scanning
- Audio and video player modules
- Aura Home and Dock workspace shell
- Agent toolchain and tool registry
- Presence Engine planning and implementation
- TreeHole / feed entry flow
- Privacy-centered presence interaction

## Stack

- Frontend: React 19, TypeScript, Vite, Zustand, Tailwind CSS
- Desktop runtime: Tauri 2
- Backend: Rust
- Data: SQLite
- Agent layer: local context builder, tool runtime, workflow graph, tool registry

## Current Development Status

This project is under active development and already has real engineering validation:

- Frontend build passes
- Rust test suite passes
- Agent runtime and workflow modules are implemented
- Presence commands and UI modules are in active iteration

## Why It Is Heavy On Token Usage

Aura is a long-context, multi-module engineering project. Development work frequently spans architecture design, frontend implementation, Rust/Tauri backend commands, SQLite schema work, agent tool design, prompt iteration, debugging, testing and documentation.

This is not a lightweight prompting workflow. It depends on sustained high-frequency model collaboration for real product development.

## Attached Proof

This repository is accompanied by:

- Build and test proof screenshots
- Core code page screenshots
- Project architecture and planning documents

## Notes

This public repository is used as a project proof page for developer program review. It does not include sensitive runtime secrets or private local data.
