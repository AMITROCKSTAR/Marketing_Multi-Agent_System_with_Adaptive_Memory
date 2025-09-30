Scenario: 
Purple Merit's client requires an autonomous marketing system with multiple specialized agents 
collaborating to optimize lead management, campaign execution, and customer engagement. The 
system should be capable of learning and adapting from ongoing interactions to improve future 
marketing outreach. 
Task: 
Build a 3-agent collaborative marketing system: 
• Lead Triage Agent - Categorizes incoming marketing leads (e.g., Campaign Qualified, Cold 
Lead, General Inquiry)
 • Engagement Agent - Manages personalized outreach, email campaigns, social media 
interactions, and lead nurturing
 • Campaign Optimization Agent - Monitors campaign performance and adapts strategies or 
escalates to marketing managers for complex decisions
 Technical Requirements: 
• Implement MCP (Model Context Protocol) server/client for secure data access to marketing 
databases and analytics
 • Use JSON-RPC 2.0 for inter-agent communication
 • Support WebSocket and HTTP transport layers for real-time campaign updates
 • Create agent handoff protocols preserving conversation and campaign context
 • Include persistent memory for each agent to learn and improve marketing outreach
 Adaptive Learning Agent Memory 
Scenario: Design a sophisticated memory architecture to allow agents to adapt from customer 
interactions and improve over time.


Task: 
Develop memory systems including: 
• Short-term memory for current conversation contexts
 • Long-term memory for customer history and preferences
 • Episodic memory capturing successful problem-resolution patterns
 • Semantic memory using domain knowledge graphs
 Technical Requirements: 
• Memory consolidation algorithms
 • Graph databases for relationship and memory modeling
 • Optimization for memory retrieval and sharing
 • Memory compression to prevent overload
 Assessment Deliverables 
• Architecture Decision Records (ADRs) documenting key design choices
 • API documentation with OpenAPI specifications
 • Deployment runbooks for production operations
 • Agent interaction analysis with conversation flow diagrams
 • Security enhancement suggestions for production deployment
 • Scalability analysis focusing on handling a 10x load increase
 Deployment Setup - Production-Ready Configuration 
Prepare a detailed design, plan, and production-ready deployment configuration for a multi-agent 
system in either marketing or sales. Your deployment setup should strictly follow the specifications 
and content provided earlier, ensuring the final implementation aligns precisely with the outlined 
requirements. Describe your approach to managing the deployment lifecycle and how you would 
validate that the system operates as expected in a production environment. 
Documentation & Enhancement - Process Documentation 
Task: 
Create comprehensive system documentation and analysis including the following key 
deliverables: 
Purple Merit Technologies
 • Architecture Decision Records (ADRs): Detailed documents capturing major design 
decisions, their context, rationale, and impact on the system.
 • API Documentation: Complete specifications using OpenAPI standards to describe the 
interfaces, endpoints, and data models for the system's APIs.
 • Deployment Runbooks: Step-by-step operational manuals to deploy, configure, and maintain 
the system in production environments.
 • Agent Interaction Analysis with Conversation Flow Diagrams: Visual and analytical 
representations of how agents interact and manage conversations.
 • Security Enhancement Suggestions: Recommendations and plans to harden the system's 
security posture for production readiness.
 • Scalability Analysis for 10x Load Increase: Assessment and strategy to enable the system to 
handle a tenfold increase in load, identifying performance bottlenecks and optimization plans
