# Tower World – ASTRA Multi-Agent System (Lab 2 · Part 5)

This project implements an ASTRA-based intelligent agent situated in the **Tower World environment**.  
The agent controls a gripper to build block towers of arbitrary height using **practical reasoning**, **goal decomposition**, and **environmental perception**.

## 🧠 Key Concepts
- Agent programming with **ASTRA**
- Interaction with an external **EIS environment**
- Practical reasoning and means–end analysis
- Event-driven perception handling
- Autonomous construction of towers of variable height

## 🎯 Objectives
- Control a gripper to pick up and place blocks
- Build towers using declarative goals rather than hardcoded sequences
- Infer higher-level concepts such as `free(Block)` and `tower(...)`
- Generate and construct **random towers** once all blocks are available

## 🏗️ Features
- Supports towers of **any height**
- Uses **goal refinement** (`!tower`, `!on`, `!holding`, `!free`)
- Handles asynchronous environment actions with `wait(...)`
- Responds dynamically to environment events
- Fully Maven-based project structure

## 📁 Project Structure
