Demo Link: https://drive.google.com/file/d/1xNJ7jixEr2uS24F9tMjidE-ZoXjJy5rY/view?usp=drive_link
# Curiosity Compass - Parent-Child Learning Platform

A multiplayer riddle-solving game that combines playful AI engagement for children with comprehensive learning insights and safety measures for parents.

## 🎮 Child Experience

**Curiosity Compass** is an interactive riddle game where children:
- Take turns submitting objects (by typing or uploading images)
- AI generates age-appropriate riddles from those objects
- Other players try to guess the answer within a time limit
- Earn points for correct guesses and creative submissions
- Practice creativity, observation, persistence, and collaboration

## 👨‍👩‍👧‍👦 Parent Experience

### Learning Dashboard
Parents can access a comprehensive dashboard that provides:

**Session Summary:**
- Objects submitted by the child
- Riddles successfully solved
- Accuracy rate and learning progress
- Session duration and engagement metrics

**Skills Practiced:**
- **Creativity**: Through object submission and riddle creation
- **Observation**: Through analyzing riddles and finding answers
- **Persistence**: Through multiple attempts and problem-solving
- **Collaboration**: Through multiplayer gameplay and teamwork

**Learning Recap:**
- Detailed narrative summary of the learning session
- Specific examples of objects and riddles
- Assessment of engagement and learning objectives met

### Parent Access
- Simple parent code authentication (PARENT123, FAMILY456, LEARN789)
- Real-time session tracking and insights
- Easy switching between child and parent modes

## 🛡️ Content Safety & Trust

### Multi-Layer Safety System

**1. Content Validation**
- Real-time filtering of inappropriate content
- Age-appropriate word blacklist (weapons, violence, scary themes)
- Content complexity checks for 5-9 year old audience
- Whitelist of safe categories (animals, toys, food, nature, etc.)

**2. AI Prompt Engineering**
- Specially crafted prompts that emphasize educational value
- Explicit instructions for age-appropriate content generation
- Focus on learning and discovery rather than entertainment alone
- Built-in safety guardrails in the AI generation process

**3. Parental Oversight**
- Complete visibility into all child interactions
- Real-time content approval status
- Detailed logs of all objects submitted and riddles generated
- Transparent reporting on safety measures

### Safety Features
- ✅ All content pre-screened for age appropriateness
- ✅ Educational focus maintained throughout
- ✅ No external links or unsafe content
- ✅ Parent-controlled access and monitoring

## 🎯 Learning Objectives

The platform is designed to develop key skills in children aged 5-9:

**Cognitive Skills:**
- Critical thinking through riddle analysis
- Pattern recognition and logical reasoning
- Vocabulary building and language development
- Problem-solving and persistence

**Social Skills:**
- Collaborative gameplay and teamwork
- Communication and sharing ideas
- Taking turns and following rules
- Encouraging others and celebrating success

**Creative Skills:**
- Imagination through object selection
- Creative expression through riddle creation
- Visual thinking through image analysis
- Innovation and original thinking

## 🔧 Technical Implementation

### Content Safety Architecture
```javascript
const CONTENT_SAFETY = {
  safeCategories: ['animals', 'toys', 'food', 'clothing', 'furniture', 'vehicles', 'nature', 'sports', 'school', 'home', 'colors', 'shapes'],
  blacklistWords: ['weapon', 'gun', 'knife', 'violence', 'scary', 'monster', 'death', 'blood', 'adult', 'inappropriate'],
  validateContent: (content) => { /* Real-time validation */ },
  getSafePrompt: (objectDescription) => { /* AI prompt with safety constraints */ }
};
```

### Learning Metrics Tracking
- Real-time session data collection
- Skills-based progress tracking
- Parent-accessible learning insights
- Privacy-focused data handling

## 🚀 Getting Started

1. **For Children:**
   - Enter your name
   - Create a room or join an existing one
   - Start playing and learning!

2. **For Parents:**
   - Click "View Learning Dashboard" on the home page
   - Enter parent code: PARENT123, FAMILY456, or LEARN789
   - View real-time learning insights and progress

## 🔒 Privacy & Trust

- All session data is stored locally and securely
- Parent codes provide controlled access to learning data
- No personal information is collected beyond display names
- Content safety is maintained through multiple validation layers
- Transparent reporting on all safety measures

## 🎨 Design Philosophy

This platform embodies the core principle of **playful learning with parental trust**:

- **For Kids**: Engaging, fun, and educational gameplay that feels like play
- **For Parents**: Complete visibility, safety assurance, and learning insights
- **For Families**: Shared experiences that build trust and understanding

The goal is to create a safe, educational environment where children can explore, learn, and grow while giving parents the confidence and insights they need to support their child's learning journey.

---

*Built with React, Firebase, and Google's Gemini AI - designed for families who value both fun and learning.*