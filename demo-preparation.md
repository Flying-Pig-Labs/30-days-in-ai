# Demo Preparation Guide

## Quick Demo Scripts for Each Tool

### Coding Tools

#### 1. Cursor (Anysphere)
**Demo**: Create a simple React component
```javascript
// Prompt: "Create a button component that changes color on hover"
const HoverButton = ({ children, onClick }) => {
  return (
    <button 
      className="hover-btn"
      onClick={onClick}
      style={{
        padding: '10px 20px',
        backgroundColor: '#007bff',
        color: 'white',
        border: 'none',
        borderRadius: '5px',
        cursor: 'pointer',
        transition: 'background-color 0.3s'
      }}
    >
      {children}
    </button>
  );
};
```

#### 2. Replit
**Demo**: Collaborative coding session
- Create new Python project
- Prompt: "Write a function that analyzes text sentiment using a simple word list"
- Show real-time collaboration features

#### 3. Bolt.new
**Demo**: Rapid prototype creation
- Prompt: "Create a todo app with add, delete, and mark complete functionality"
- Show speed of generation

### Data & Analytics Tools

#### Julius AI
**Sample Dataset** (CSV):
```csv
Month,Revenue,Customers,Region
Jan,50000,120,North
Feb,55000,135,North
Mar,48000,110,South
Apr,62000,145,North
May,58000,140,South
```
**Demo Prompts**:
- "What's the revenue trend over time?"
- "Which region performs better?"
- "Create a visualization of customer growth"

#### Databricks
**Demo**: 
- Show data ingestion workflow
- Simple ML model training example
- Data visualization capabilities

### Content Creation Tools

#### Captions
**Demo Script**:
"Today we're exploring amazing AI tools that use Claude. Each tool has unique capabilities that can transform how we work and create. Let's see how this voice becomes a professional video."

#### Gamma
**Demo Outline**:
```
Title: "The Future of AI-Powered Development"
- Slide 1: Introduction to Claude Tools
- Slide 2: Coding Revolution
- Slide 3: Productivity Gains
- Slide 4: Creative Applications
- Slide 5: What's Next?
```

#### InVideo
**Demo Prompt**: "Create a 30-second video introducing AI coding tools, upbeat tech style"

### Business Tools

#### Dust
**Demo Workflow**:
1. Set up team agent for "Meeting Summarizer"
2. Feed it sample meeting transcript
3. Show automated action items generation

#### Clay
**Demo**: 
- Import sample contact list
- Show enrichment capabilities
- Create relationship mapping

#### Highlight AI
**Sample Meeting Text**:
"Let's discuss the Q2 roadmap. We need to prioritize the mobile app launch, address the API performance issues, and plan the user feedback integration. Sarah will lead mobile, Mike handles API optimization, and Lisa coordinates user research."

### Specialized Tools

#### Harvey (Legal AI)
**Demo**: Contract analysis simulation
- Show document upload interface
- Demonstrate risk assessment features
- Privacy/compliance discussion

#### StudyFetch
**Demo**:
- Upload sample educational content
- Generate quiz questions
- Show spaced repetition features

## Live Demo Safety Nets

### If Tools Don't Work:
1. **Screenshots prepared** of each tool's interface
2. **Video recordings** of key features (30-60 seconds each)
3. **Documentation walkthroughs** as backup content

### Sample Prompts Ready:
- **Creative**: "Design a logo for a coffee shop called 'Binary Beans'"
- **Technical**: "Explain the difference between REST and GraphQL APIs"
- **Business**: "Analyze this sales data and suggest improvements"
- **Educational**: "Create a quiz about JavaScript fundamentals"

### Interaction Prompts for Chat:
- "What would you build with [current tool]?"
- "Have you used anything similar? How does it compare?"
- "Rate this tool 1-10 for your use case"
- "What's the biggest challenge this solves for you?"

## Technical Demo Requirements

### Screen Recording Setup:
- Record each successful demo for backup
- Prepare screen region capture for specific tools
- Have OBS scenes ready for different demo types

### Account Credentials:
```
Note: Create demo accounts with non-sensitive information
- Use consistent demo email: demo@[yourdomain].com
- Use simple passwords for live entry
- Have backup accounts ready
```

### Data Files Prepared:
1. **sample-data.csv** (for Julius AI, Databricks)
2. **meeting-transcript.txt** (for Highlight AI)
3. **contact-list.csv** (for Clay)
4. **demo-script.txt** (for Captions)
5. **presentation-outline.md** (for Gamma)

### Fallback Content:
If internet fails completely:
- Local presentation about Claude AI ecosystem
- Discussion of AI tool evaluation criteria
- Q&A about AI literacy and education
- Deep dive into the "special sauce" descriptions from README