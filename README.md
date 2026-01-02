# E-commerce-Agent

# Meta-Agent Orchestrator - POC Implementation

## 📋 Project Overview
An AI-powered orchestration system that resolves conflicts between autonomous e-commerce bots using LLM reasoning.

**Problem**: Three bots (PriceBot, InventoryBot, PromoBot) make conflicting decisions that could harm business
**Solution**: Meta-Agent Orchestrator detects conflicts, uses AI reasoning for resolution, and provides transparent explanations

## 🎯 POC Requirements Met

### Part 1: Conflict Resolution Engine (40%)
- ✅ Direct, Resource, Timing, Margin, Cascade conflicts
- ✅ LLM reasoning, not hardcoded rules
- ✅ Business calculations (margin, stockout risk)

### Part 2: Reasoning Engine (30%)
- ✅ Step-by-step reasoning trace
- ✅ Multiple resolution options evaluated
- ✅ Level 1-3 complexity handling
- ✅ Creative solutions beyond approve/reject

### Part 3: Self-Correction Loop (20%)
- ✅ Feedback processing
- ✅ Pattern learning
- ✅ Confidence adjustment

### Part 4: Technical Requirements (10%)
- ✅ All API endpoints implemented
- ✅ <3 second response time
- ✅ FastAPI + Python
- ✅ Gemini AI integration

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Gemini API key (optional - simulation mode available)

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/meta-agent-orchestrator.git
cd meta-agent-orchestrator

# Install dependencies
pip install -r requirements.txt

# Set up environment
cp .env.example .env
# Add your Gemini API key to .env
