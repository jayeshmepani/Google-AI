# Comprehensive Catalogue of Google AI, ML & Data Science Products

_Updated: June 24, 2026_

> **Verification standard (June 24, 2026):** Every original line was reviewed. Fast-changing claims—model availability, launch/status, subscriptions, APIs, deprecations, and regional access—were rechecked against Google/DeepMind/Google Cloud/Google for Developers primary sources. Announced-but-not-released items are explicitly labelled; experimental availability can still vary by account, age, language, and country.

---

## 🎨 **Creative & Media Generation AI**

### **Image Generation & Editing**

**1. ImageFX**

- **Link**: https://labs.google/fx
- **Description**: Text-to-image generator powered by Imagen 3/4 with interactive prompt exploration
- **Features**:
  - "Expressive chips" to tweak prompts interactively
  - Photorealistic or stylized high-quality images
  - SynthID watermarking on all outputs
  - **2026 Update**: Added "Seed Styles" to allow consistent variation exploration from specific generations
- **Availability**: 110+ countries, 37 languages

**2. Nano Banana (Gemini 2.5 Flash Image)**

- **Link**: https://aistudio.google.com/models/gemini-2-5-flash-image
- **Description**: Fast, low-latency image generation (Nickname for **Gemini 2.5 Flash Image**)
- **Features**:
  - Very quick generations for rapid iteration
  - Text rendering (signs, labels) in multiple languages
  - Blend up to 14 images into one coherent composition
- **Used in**: Gemini app, Google Search, Google Photos, Google Ads, NotebookLM
- **Statistics**: 5+ billion images generated as of late 2025

**3. Nano Banana Pro (Gemini 3 Pro Image)**

- **Link**: https://gemini.google/overview/image-generation
- **Description**: Advanced "thinking" image generator (Nickname for **Gemini 3 Pro Image**)
- **Features**:
  - Up to 4K resolution output
  - Better consistency across a series of images
  - Maintain resemblance of up to 5 people in one scene
  - Finer control over color grading, lighting, and local edits
  - Localized editing capabilities
- **Access**: Gemini Pro/Ultra tiers and selected Google products

**4. Nano Banana 2**

- **Link**: https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/
- **Description**: Next-generation image generation model combining Pro quality with Flash speed (technically Gemini 3.1 Flash Image)
- **Features**:
  - High-quality image generation with faster results (2-3x faster than Pro)
  - Improved performance over previous versions
  - Available across Gemini app and Google Search
  - Supports SynthID watermarking
  - Advanced world knowledge and improved text rendering
  - Better subject consistency and production-ready specifications
  - **2026 Update**: Now the default model across Google products
- **Access**: Developers can build with Nano Banana 2 via API
- **Announced**: February 26, 2026
- **Comparison**: 2-3x faster than Nano Banana Pro; now default model across Google products

**5. Whisk**

- **Link**: https://labs.google/fx
- **Description**: Visual-prompt tool using images instead of text for generation (image-to-image)
- **Features**:
  - Drag in "subject", "scene", and "style" images to control output
  - Whisk Animate: turn images into short videos via Veo 3
  - Powered by Gemini + Imagen 3
- **Availability**: 140+ countries

**6. GenType**

- **Link**: https://labs.google/gentype
- **Description**: AI tool for creating custom alphabets and letterforms
- **Features**:
  - Generate themed typefaces from text prompts (e.g., "chrome cyberpunk", "dripping neon")
  - 3D, textured, or illustrative styles
  - Download assets for creative projects
- **Powered by**: Imagen
- **Availability**: Google Labs

**7. Gemini Canvas**

- **Link**: https://gemini.google/overview/canvas/
- **Description**: AI workspace for image/code creation integrated with Gemini
- **Features**:
  - Draft documents or create custom tools within Google Search
  - Build study guides by uploading class notes and sources
  - Project planning and research organization
  - Image and code creation workspace
  - Transform reports into interactive content
- **Availability**: All US users in English (March 2026 rollout)
- **Announced**: March 2026

**8. Dream Track**

- **Link**: https://support.google.com/youtube/answer/14151606
- **Description**: YouTube Shorts AI music powered by Lyria
- **Features**:
  - AI music generation for YouTube Shorts creators
  - Integration with Lyria 3 for advanced music creation
  - Creator-focused music tools
- **Availability**: YouTube creators
- **Integration**: YouTube Music AI Tools, Music AI Sandbox

### **Video Generation & Filmmaking**

**9. Veo 3 & Veo 3.1**

- **Link**: https://deepmind.google/models
- **Description**: Google's flagship state-of-the-art video generation models
- **Features**:
  - High-quality video up to 1080p with realistic physics
  - Generate videos up to 8 seconds or longer
  - Native audio generation (sound effects, ambient noise, dialogue)
  - Frames-to-Video: extend image sequences
  - Ingredients-to-Video: combine masks, depth maps, etc.
  - **Veo 3.1** (October 2025/January 2026):
    - 4K output support
    - Vertical video generation for YouTube Shorts (9:16 aspect ratio)
    - Upscale to 1080p or 4K
    - Better consistency and enhanced native audio
    - Reference image capabilities (portrait and landscape)
    - Scene extension for seamless transitions
    - More expressive and creative outputs
    - 20% better motion quality
  - **Veo 3.1 Fast** (January 2026):
    - 2x faster generation for rapid iteration
    - Same quality as Veo 3.1 with reduced latency
- **Access**: Flow, Gemini app, Vertex AI, Gemini API
- **Statistics**: 275+ million videos generated by late 2025

**10. Veo 3.1 Lite**

- **Link**: https://blog.google/innovation-and-ai/technology/ai/veo-3-1-lite
- **Description**: Most cost-effective Veo model for high-volume applications
- **Features**:
  - Reduced latency and lower compute cost (<50% of Veo 3.1 Fast)
  - Optimized for 720p/1080p rapid-iteration clips
  - Text-to-Video and Image-to-Video support
- **Access**: Gemini API, Google AI Studio
- **Announced**: March 31, 2026

**11. Flow (formerly VideoFX)**

- **Link**: https://labs.google/fx (Flow) / https://labs.google/flow/about
- **Description**: AI filmmaking tool for creating cinematic clips and scenes
- **Features**:
  - Scene-by-scene storyboarding and generation
  - Camera controls, Scenebuilder, scene extension
  - Camera path and style control
  - Native audio generation with Veo 3
  - Integrates with Nano Banana for concept frames
  - Flow TV for viewing community creations
  - Create high-fidelity images and instantly use as building blocks for video generation
  - Updated interface for easier asset management (February 2026)
  - New editing features for cinematic storytelling
- **Availability**: Google AI Pro and Ultra subscribers (140+ countries)
- **Statistics**: 275+ million videos generated by late 2025
- **Updates**: February 2026 - Added new ways to create images and videos in a single workspace

**12. Google Flow for Workspace Accounts**

- **Link**: https://support.google.com/flow/
- **Description**: Google Flow can be used with supported Google Workspace accounts when the organization and administrator settings permit access
- **Verified scope**:
  - Flow is a standalone Google creative studio for generating and editing videos and images
  - Workspace administrators can manage eligibility, access, and organizational controls
  - Projects, credits, models, and supported features are documented in the official Flow Help Center
- **Correction**: The earlier claim that Flow generated cinematic videos directly inside Docs and Sheets was not supported by official Google documentation and was removed
- **Availability**: Depends on Workspace edition, administrator settings, country, age, and Google AI plan

**13. Flow TV**

- **Description**: Community gallery and feed to browse Flow-generated videos from other users
- **Use**: Discover and explore AI-generated video content, inspiration for creators

### **Music & Audio Generation AI**

**14. MusicFX**

- **Link**: https://labs.google/fx/tools/music-fx
- **Description**: Text-to-music generation tool, successor to MusicLM
- **Features**:
  - Generate music loops up to 70 seconds
  - Create instrumentals from text prompts
  - Adjust mood, tempo, and instrumentation
  - SynthID watermarking on all outputs
- **Powered by**: Lyria model
- **Availability**: Limited set of countries (initially US, Australia, New Zealand, Kenya; expanding)
- **Statistics**: 10+ million tracks created

**15. Lyria 3 & Lyria 3 Pro**

- **Link**: https://blog.google/innovation-and-ai/products/gemini-app/lyria-3/
- **Description**: Most advanced music generation tool from Google DeepMind
- **Features**:
  - **Lyria 3**: 30-second tracks with vocals/instruments and custom cover art
  - **Lyria 3 Pro** (March 25, 2026): Generate tracks up to 3 minutes; structural awareness (intros, verses, choruses)
- **Access**: Gemini app, Google Vids, Vertex AI
- **Announced**: February 18, 2026

**16. Gemini 3.1 Flash TTS**

- **Link**: https://ai.google.dev/models/gemini-flash-tts
- **Description**: Next-generation text-to-speech model for expressive, natural AI speech
- **Features**:
  - Granular control over vocal style, pacing, tone, and accent via audio tags
  - Supports 70+ languages; multi-speaker dialogue functionality
- **Announced**: April 15, 2026

**17. ProducerAI**

- **Link**: https://blog.google/innovation-and-ai/models-and-research/google-labs/producerai/
- **Description**: Music creation partner for refining lyrics and melodies
- **Features**:
  - Helps turn imagination into dynamic, comprehensive songs
  - Refines lyrics and melody
  - Music creation assistance
- **Availability**: Google Labs
- **Announced**: February 2026

**18. MusicFX DJ**

- **Link**: https://labs.google/fx/tools/music-fx-dj
- **Description**: Live, interactive real-time AI music mixing and jamming tool
- **Features**:
  - Mix multiple prompts and stems in real time
  - Control genre, intensity, arrangement live (DJ-style)
  - Real-time control sliders for mixing genres and instruments
- **Collaboration**: Built with input from Jacob Collier
- **Availability**: Same regions as MusicFX

**19. Music AI Sandbox**

- **Link**: https://labs.google/fx
- **Description**: Professional music creation tools for musicians and creators
- **Features**:
  - AI-powered composition, arrangement, and vocal tools
  - Advanced music generation capabilities
  - Used by professional musicians for creative exploration
- **Integration**: YouTube creator tools
- **Powered by**: Lyria + YouTube

**20. Instrument Playground**

- **Description**: Interactive AI experiment for playing sounds from global instruments
- **Features**:
  - Explore unusual instrument sounds
  - Cultural fusion generation
  - Real-time audio synthesis
- **Availability**: Google Arts & Culture / Labs

**21. Viola the Bird**

- **Link**: https://labs.google
- **Description**: AI cello-inspired instrument as interactive art piece
- **Features**:
  - Play music without musical skills via animated bird character
  - Real-time audio synthesis demonstration
  - Playful demo of AI audio generation
- **Creator**: Artist David Li
- **Availability**: Google Labs

### **Text & Creative Writing AI**

**22. TextFX**

- **Link**: https://textfx.withgoogle.com
- **Description**: Creative writing tools suite powered by PaLM 2 (Legacy)
- **Features**: 10 creative modules including:
  - Simile, Explode, Unexpect, Chain
  - POV, Alliteration, Acronym, Scene, Unfold
  - Designed for writers and lyricists
- **Collaboration**: Developed with Lupe Fiasco
- **Availability**: Google Labs

**23. Verse by Verse**

- **Link**: https://sites.research.google/versebyverse/
- **Description**: AI poetry composition tool
- **Features**:
  - Write poems with AI "muses" trained on classic poets
  - Styles inspired by Emily Dickinson, Robert Frost, and others
  - Co-write poems with AI suggestions
- **Availability**: Google Arts & Culture

**24. Gemini Storybook**

- **Link**: (Gemini app, "Storybook" feature)
- **Description**: Generates short, ~10-page illustrated children's stories from a prompt
- **Features**:
  - Custom characters, style, and length
  - Page-by-page images + narrative
  - Export/share as a story to read on phones or tablets
- **Availability**: Inside Gemini app (regions follow Gemini availability)

---

## 🤖 **AI Agents & Assistants**

**25. Gemini App (Core Assistant)**

- **Link**: https://gemini.google
- **Description**: Main AI chat assistant interface and primary access point to Gemini models
- **Features**:
  - Access to Gemini 2.5 Flash, 2.5 Pro, and Gemini 3
  - Chat, code, research capabilities
  - Image generation with Nano Banana Pro
  - Video generation with Veo
  - Deep Think reasoning
  - Optional connection to Gmail, Docs, Drive, Calendar
  - Deep Research on paid tiers
  - **Personal Intelligence**: Connect Google apps for personalized experiences (January 2026)
  - **Auto Browse**: Gemini can browse the web autonomously for you (January 2026)
  - Free SAT practice tests for students (January 2026)
- **Availability**: Android, iOS, web (global)
- **Statistics**: 500+ million users

**26. Gemini for Mac**

- **Description**: Native macOS app for Gemini
- **Features**: Accessible via Option + Space shortcut; window sharing and screen awareness
- **Launched**: April 15, 2026

**27. Gems**

- **Link**: https://gemini.google/gems
- **Description**: Custom versions of Gemini that you can create and customize
- **Features**:
  - Create custom AI experts for specific topics
  - Give specific instructions and personalities
  - Share Gems with others
  - Similar to custom GPTs
- **Availability**: Gemini Advanced subscribers

**28. Gemini Live**

- **Link**: https://gemini.google (within Gemini app)
- **Description**: Real-time voice and multimodal conversation mode
- **Features**:
  - Natural, low-latency voice conversations
  - Multimodal understanding (voice, text, images)
  - Live camera and voice input in supported regions
  - Video input: Share your camera to show Gemini your surroundings (March 2026)
  - Gemini can now "see" with real-time video understanding
  - Screen sharing capabilities
- **Integration**: Gemini app
- **Update**: March 2026 - Expanded video capabilities with world-facing camera

**29. Project Mariner**

- **Link**: https://deepmind.google/models/project-mariner/
- **Description**: Google DeepMind research prototype for browser-based agentic tasks
- **Features**:
  - Navigate websites and complete multi-step browser workflows
  - Run up to 10 tasks concurrently in supported access tiers
  - Demonstrates computer-use and web-agent capabilities later reused across Google products
- **Availability (verified June 24, 2026)**: Still listed by Google as an active research prototype for eligible Google AI Ultra users, with region/account restrictions
- **Status correction**: **Not discontinued.** Earlier June drafts claiming a May 4, 2026 shutdown were unsupported and have been removed
- **Caution**: Experimental agents can make mistakes; review actions before confirming purchases, submissions, or account changes

**30. Project Astra**

- **Link**: https://labs.google
- **Description**: Universal AI assistant with multimodal capabilities (Google's "universal agent" concept)
- **Features**:
  - Video understanding and screen sharing
  - 10-minute memory retention
  - Understands what your camera sees plus context and conversation history
  - Works across Android phones and prototype glasses
  - Integrates Search, Maps, and Lens
- **Status**: Trusted tester program; features rolling out across AI Mode and Gemini

**31. Jules**

- **Link**: https://ai.google.dev/aistudio / https://jules.google.com
- **Description**: Autonomous AI coding agent powering multiple Google developer experiences
- **Features**:
  - Reads entire codebases and understands context
  - Performs coding tasks autonomously
  - Plans tasks, edit files, run tests, draft pull requests
  - GitHub integration
  - Asynchronous operation in cloud VM
  - Audio changelogs
  - **Suggested Tasks**: Proactively scans code and proposes improvements (December 2025)
  - **Scheduled Tasks**: Automate routine development work (December 2025)
  - **Render integration**: Self-healing deployments for faster fix (December 2025)
  - **Jules Tools**: Lightweight command-line interface (October 2025)
  - **Jules API**: Integrate Jules directly into your own systems (October 2025)
  - **Graduated from beta**: Now generally available (February 2026)
- **Powered by**: Gemini 2.5 Pro (upgraded to Gemini 2.5 in August 2025)
- **Access**: Public beta worldwide (free during beta); enhanced access on AI Ultra
- **Integration**: Gemini Code Assist, CLI, and other dev tools

**32. Deep Research & Deep Research Max**

- **Link**: https://blog.google/technology/google-labs/notebooklm-deep-research-file-types
- **Description**: Evolution of autonomous research agents built on Gemini 3.1 Pro
- **Features**:
  - Multi-step research planning and execution
  - **Deep Research Max** (April 21, 2026): Autonomous research agent for exhaustive, offline research with MCP (Model Context Protocol) support
  - Structured reports with citations; exportable to Google Docs
  - 83.5% success rate on WebVoyager benchmark
- **Availability**: Gemini Advanced, Gemini API (Interactions API)
- **Status**: Public preview (April 2026)

**33. Notebooks in Gemini**

- **Link**: https://blog.google/innovation-and-ai/products/gemini-app/notebooks-gemini-notebooklm/
- **Description**: Project management tool to organize chats and files for complex projects
- **Features**:
  - Seamless sync with NotebookLM; organizes complex research into specific project folders
  - Allows higher source limits and cross-app access
- **Launched**: April 8, 2026

**34. Skills in Chrome**

- **Description**: Feature to save and reuse AI prompts as one-click tools in the Chrome browser
- **Features**:
  - Library of ready-to-use Skills for tasks (e.g., recipe macros, gift selection)
  - Built on Chrome's Gemini integration
- **Launched**: April 14, 2026

---

## 📚 **Learning & Knowledge AI Tools**

**35. NotebookLM**

- **Link**: https://notebooklm.google
- **Description**: AI-powered research and note-taking assistant grounded in your own sources
- **Features**:
  - Process up to 50 sources (PDFs, Google Docs, Sheets, websites, YouTube, audio, images)
  - Audio Overviews: podcast-style summaries with two AI hosts
  - Interactive Audio Overviews: join the conversation
  - Video Overviews with narration (80+ languages)
  - Cinematic Video Overviews generation
  - Deep Research for multi-step web + source analysis
  - Mind Maps, study guides, FAQs, timelines, flashcards
- **Powered by**: Gemini
- **Availability**: 200+ countries and territories
- **Languages**: Reports in **80+ languages**; audio/video in **dozens of languages** (both expanding)
- **Premium**: NotebookLM Plus for enterprises
- **Updates**: March 4, 2026 - Added Cinematic Video Overviews feature

**36. Illuminate**

- **Link**: https://illuminate.google.com
- **Description**: AI podcasting tool for scientific and academic content
- **Features**:
  - Converts research papers into podcast-style dialogues
  - Creates two-person conversations about scientific content
  - Focuses on arxiv.org scientific papers and academic content
- **Status**: Experimental (waitlist)

**37. Learn Your Way (formerly Learn About)**

- **Link**: https://learnyourway.withgoogle.com
- **Description**: Interactive learning tool that transforms content into personalized experiences
- **Features**:
  - Transforms arbitrary content (text, videos) into engaging learning experiences
  - Personalized pacing, dynamic format
  - Quizzes and visual explanations
  - Save past sessions for continued learning
- **Availability**: Google Labs

**38. Little Language Lessons**

- **Link**: https://labs.google
- **Description**: Bite-sized language learning through real-world scenarios
- **Features**:
  - Scenario-based lessons in 12+ languages
  - Local slang and phrases
  - Camera-based lesson generation
  - Mobile-style short lessons using real-life scenarios
- **Availability**: Google Labs

**39. Shiffbot**

- **Link**: https://labs.google
- **Description**: Creative coding learning assistant embedded in p5.js web editor
- **Features**:
  - Teaches coding with Dan Shiffman's playful style
  - Conversational help for creative coding
  - Playful, educational approach
- **Collaboration**: With educator Dan Shiffman
- **Availability**: Google Labs

**40. Woolaroo**

- **Link**: https://g.co/woolaroo
- **Description**: Language preservation tool using AI photo-translation
- **Features**:
  - Identifies objects in photos
  - Provides names in endangered/indigenous languages
  - Helps preserve endangered languages
- **Status**: Open-source

**41. Career Dreamer**

- **Link**: https://blog.google/outreach-initiatives/grow-with-google/a-new-experiment-to-help-people-explore-more-career-possibilities
- **Description**: Career exploration and planning tool
- **Features**:
  - AI-suggested career paths based on skills and interests
  - Explores possible careers and roles from your profile
  - Personalized career recommendations
- **Availability**: US-only (Grow with Google / Labs)

**42. Google Skills**

- **Link**: https://grow.google/ai
- **Description**: AI upskilling program with Gemini certifications
- **Features**:
  - AI training courses for individuals and businesses
  - Professional certificates in AI
  - Hands-on practice with Gemini
  - Focus on practical AI skills for the workplace
- **Availability**: Global (Grow with Google)

---

## 💼 **Business & Productivity AI**

**43. Pomelli**

- **Link**: https://blog.google/technology/google-labs/pomelli
- **Description**: AI marketing assistant tool for small and medium-sized businesses
- **Features**:
  - Analyzes website to create "Business DNA" profile (tone, imagery, palette)
  - Generates on-brand social media campaigns
  - Creates campaign ideas and ready-to-edit assets for social and marketing
  - Custom fonts, images, color palettes
- **Developed by**: Google Labs + Google DeepMind
- **Availability**: US, Canada, Australia, New Zealand (English-only initially)

**44. Retail AI Tools**

- **Description**: New suite of AI tools to help retailers seize the AI opportunity
- **Features**:
  - AI-powered retail solutions
  - Help retailers integrate AI into their operations
  - Shopping assistance and product discovery tools
- **Announced**: January 2026 (AI Impact Summit in India)
- **Launch Event**: AI Impact Summit in India (February 2026)

**45. Mixboard**

- **Link**: https://labs.google/mixboard
- **Description**: AI-powered concepting board and moodboard tool
- **Features**:
  - Visual canvas for idea exploration
  - Drop references and explore visual/idea variations
  - Expand and refine creative concepts
  - Pinterest-style AI tool for rapid iteration
- **Powered by**: Gemini 2.5 Flash + on-device Nano variants
- **Availability**: Google Labs

**46. Opal**

- **Link**: https://opal.withgoogle.com
- **Description**: No-code AI app builder for creating AI mini-apps
- **Features**:
  - Build AI mini-apps with natural language ("vibe coding")
  - Describe app behavior and Opal builds flows and UI
  - Visual workflow editor
  - Chain together prompts, models, and tools
  - Share and deploy apps instantly via shareable links
- **Availability**: 160+ countries (expanded from US-only in mid-2025)

**47. Gemini for Google Workspace**

- **Link**: https://workspace.google.com
- **Description**: AI features integrated into Google productivity applications
- **Features**:
  - AI in Gmail: draft and refine emails, summarize threads
  - AI in Docs: "Help me create" and "Match writing style" from other docs
  - AI in Sheets: Generate entire spreadsheets and "Fill with Gemini" tool
  - AI in Slides: Auto-create theme-matching slides
  - AI in Drive: Natural language Q&A about documents
- **Update**: March 10, 2026

**48. Security AI Workbench & Gemini in Security Operations**

- **Link**: https://cloud.google.com/security/ai
- **Description**: Gemini-powered tools for SOC teams and threat intelligence
- **Includes**:
  - **Security AI Workbench**: Platform for security analysis
  - **Gemini in Security Operations**: Summarize alerts, generate investigations
  - **Threat Intelligence**: Gemini-backed experiences in Mandiant & Chronicle
- **Use**: Enterprise security and threat analysis

**49. Google Vids**

- **Link**: https://workspace.google.com/products/vids/
- **Description**: AI-powered video creation tool for workplace presentations and training
- **April 2026 Update**: Integrated Veo 3.1 and Lyria 3 Pro; added directable AI avatars with precision placement
- **Democratization**: Free tier offers 10 video generations/month to all Google account holders
- **Features**:
  - Convert documents or prompts into narrated videos
  - Generate video storyboards
  - Suggest stock footage and add voiceovers
- **Integration**: Google Workspace

**50. Gemini in Google Ads**

- **Link**: https://ads.google.com
- **Description**: Gemini-powered tool for auto-optimizing ad campaigns and assets
- **Features**:
  - Generates high-quality ad copy and images
  - Analyzes campaign performance
  - Suggests optimizations for better ROI
  - Conversational interface for campaign management
- **Availability**: Global enterprise (Google Ads)

**51. AI features in Google Analytics 4**

- **Link**: https://analytics.google.com
- **Description**: AI for data insights and automation in Google Analytics
- **Features**:
  - Automated insights and trend detection
  - Natural language querying of data
  - Predictive analytics for user behavior
  - Automated report generation
- **Availability**: Google Analytics 4 users

---

## 🔍 **Search & Visual AI Features**

### **Search Enhancements**

**52. AI Overviews**

- **Link**: https://search.google/intl/en-IN/ways-to-search/ai-overviews
- **Description**: Auto-generated AI answer blocks at the top of Google Search results
- **Features**:
  - Summarized answers with supporting links
  - Tables, step-by-step instructions, and visual layouts
  - Quick comprehensive answers
  - Now powered by Gemini 3 (January 2026)
  - Ask follow-up questions directly from the AI Overview
  - Seamless transition to AI Mode for deeper exploration
- **Statistics**: Used by 2+ billion people per month by 2025

**53. AI Mode in Search**

- **Link**: https://blog.google/products/search/gemini-3-ai-mode-more-countries
- **Description**: Full conversational "AI view" of Search (Gemini integrated into Search)
- **Features**:
  - Interactive simulations and tools
  - Rich, conversational answers
  - Deep Search capabilities
  - Shopping mode, research-style outputs
  - Multi-step reasoning and agentic capabilities
  - Powered by Gemini 3 (January 2026 upgrade)
  - Now includes Gemini 3 Flash and Pro (expanded from late 2025)
- **Powered by**: Gemini 3 Pro (for AI Pro/Ultra users); lighter models for free users
- **Availability**: Available in **~180 countries** (English first, expanding)
- **Statistics**: Approximately 100 million users as of mid-2025

**54. Deep Search**

- **Description**: Thorough, research-style search mode with enhanced capabilities
- **Features**:
  - Multi-step query planning and reasoning
  - More thorough search flow
  - Deeper web exploration
  - Comprehensive results with sources
- **Integration**: AI Mode in Search

**55. Canvas in AI Mode**

- **Link**: https://blog.google/products-and-platforms/products/search/ai-mode-canvas-writing-coding/
- **Description**: AI-powered canvas for organizing projects and research in Google Search
- **Features**:
  - Draft documents or create custom tools within Google Search
  - Build study guides by uploading class notes and sources
  - Project planning and research organization
  - Integrates with AI Mode in Search
- **Availability**: All US users in English
- **Announced**: March 2026

**56. Web Guide**

- **Description**: AI-organized search results layout
- **Features**:
  - Grouped explanations with supporting links
  - Structured information presentation
  - AI organizes the SERP into sections
- **Integration**: Google Search

**57. Shop with AI Mode**

- **Description**: AI-enhanced shopping experience in Search
- **Features**:
  - Conversational shopping queries ("find breathable black running shoes under $100")
  - Product discovery, guidance, and comparisons
  - Visual try-on experiments
  - Price comparisons and recommendations
- **Integration**: Google Search

**58. Search Live**

- **Description**: Real-time conversational search using your camera
- **Features**:
  - Point camera and talk to Search about what you see
  - Interactive environment understanding
  - Real-time visual + conversational search
- **Based on**: Project Astra technology
- **Status**: Coming soon

**59. Say What You See**

- **Link**: https://labs.google
- **Description**: AI art prompt guessing game
- **Features**:
  - Decode AI-generated art
  - Guess the prompts behind images
  - Learn prompt engineering through play
- **Availability**: Search Labs

### **Photos & Visual AI Tools**

**60. Ask Photos**

- **Link**: https://photos.google.com
- **Description**: AI-powered photo search and interaction using natural language
- **Features**:
  - Natural language photo search
  - Find specific memories and information
  - "Ask" button for image conversations
  - Example: "Show me our best beach sunsets where my daughter is holding an ice cream"
- **Powered by**: Gemini
- **Availability**: 100+ countries, 17 languages

**61. Google Lens with AI**

- **Link**: https://lens.google
- **Description**: Visual search with advanced AI enhancements
- **Features**:
  - Lens: Identify objects, translate text, shop products
  - Circle to Search: Draw around anything on screen to search
  - Create mode: Uses Nano Banana to transform or generate images
  - Instant image transformation
- **Availability**: Android and iOS

**62. Google Photos AI Features**

- **Link**: https://photos.google.com
- **Features Include**:
  - **Magic Editor**: Advanced AI photo editing
  - **Magic Eraser**: Remove unwanted objects and people
  - **Photo Unblur**: Sharpen blurry images with AI
  - **Best Take**: Combine best expressions from multiple shots
  - **Portrait Light**: Adjust lighting after photo capture
  - **Photo to Video**: Animate still photos into videos
  - **Remix**: Artistic style transformation
- **Technology**: Uses Google's vision models, Nano Banana, and Imagen
- **Availability**: Google Photos app, enhanced features on Pixel devices

**63. AI Wallpaper**

- **Description**: Custom wallpaper generation from text prompts
- **Features**:
  - Prompt-based wallpapers
  - Generative "styles" for home and lock screens
  - Personalized device backgrounds
- **Availability**: Android devices and Pixel phones

---

## 👨‍💻 **Developer AI Tools & Platforms**

### **Design & UI AI Tools**

**64. Stitch 2.0 "Vibe Design"**

- **Link**: https://stitch.withgoogle.com
- **Description**: AI-powered UI design tool evolved into a comprehensive design platform
- **Features**:
  - Infinite canvas for exploration
  - Multi-screen generation (up to 5 linked screens)
  - Design agent for suggested improvements
  - Voice control for real-time canvas edits
  - Code export: HTML/CSS with Tailwind-friendly classes
- **Update**: March 18, 2026
- **Availability**: Free, Google Labs

### **Development Platforms & IDEs**

**65. Google AI Studio**

- **Link**: https://aistudio.google.com
- **Description**: Web-based platform for AI development and prototyping
- **Features**:
  - Prompt testing and experimentation
  - Playground UI with structured templates
  - Starter Apps gallery (12+ apps)
  - Vibe coding with natural language
  - Native code editing
  - API key generation for Gemini API
  - Model testing (Gemini, Imagen, Veo)
- **Availability**: Free for developers worldwide

**66. AI Agent Finder**

- **Link**: https://aistudio.google.com
- **Description**: Directory for discovering and building AI agents
- **Features**:
  - Browse pre-built agents for various tasks
  - Discover agent templates and capabilities
  - Integrated directly into AI Studio
  - Accelerates agent development workflow
- **Availability**: Google AI Studio users

**67. Project IDX**

- **Link**: https://idx.dev
- **Description**: AI-first cloud-based integrated development environment
- **Features**:
  - Build full-stack web and multiplatform apps
  - Gemini built directly into the editor
  - In-editor chat, code completions, code actions
  - Real-time previews
  - Code completion and debugging assistance
- **Availability**: Developers

**68. Core ML Frameworks**

- **Description**: Essential libraries for building and deploying AI models
- **Includes**:
  - **TensorFlow**: Flagship framework for training and serving
  - **JAX**: High-performance numerical computing & autodiff
  - **Keras**: High-level API running on TF, JAX, PyTorch
  - **TensorFlow Lite**: On-device ML runtime
  - **MediaPipe**: Real-time perception pipelines (vision, audio)
- **Use**: Foundational infrastructure for Google AI and external developers

**69. Gemini in Chrome & DevTools**

- **Link**: https://developer.chrome.com/docs/devtools/ai
- **Description**: AI features built directly into the Chrome browser and DevTools
- **Features**:
  - Console Insights: Explain errors and warnings in DevTools
  - Help me write: AI writing assistance in web fields
  - AI-powered history search
  - Built-in Nano model for local web AI features
- **Availability**: Chrome desktop users

**70. Google Antigravity**

- **Link**: https://antigravity.google
- **Description**: Agentic development platform for complex workflows
- **Features**:
  - Manage multiple autonomous agents
  - Complex agentic architectures
  - Agents interact with editor, terminal, and browser
  - Orchestrates agents for building complex agent workflows
- **Introduced**: Alongside Gemini 3
- **Availability**: Developers

**71. Firebase Studio**

- **Link**: https://firebase.google.com/docs/studio
- **Description**: Agentic development environment for building full-stack AI apps
- **Features**:
  - App Prototyping agent
  - 60+ pre-built templates
  - Native code workspace
  - Genkit support (Python, Go)
  - Firebase integration
  - GUI for building AI-powered applications
- **Availability**: Preview

### **Code Understanding & Automation AI**

**72. Code Wiki**

- **Link**: https://codewiki.google
- **Description**: AI-native auto-generated documentation tool for code repositories
- **Features**:
  - Automatically scans repositories and produces structured documentation
  - Keeps documentation in sync with latest commits
  - Includes diagrams, cross-links, and architecture views
  - Gemini chat grounded in the generated wiki
  - Updates continuously after each code change
- **Status**: Public preview for open-source repos; CLI extension planned for private repos

**73. Gemini CLI (Consumer Transitioned to Antigravity CLI)**

- **Link**: https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/
- **Description**: Google's earlier community/consumer command-line AI agent, now superseded for individual users by Antigravity CLI
- **Transition date**: June 18, 2026
- **Current status**:
  - Free, Google AI Pro, and Google AI Ultra individual requests stopped being served through Gemini CLI on June 18, 2026
  - Enterprise Gemini Code Assist / Gemini CLI access remains supported under enterprise arrangements
  - Individual developers should migrate to **Antigravity CLI**
- **Historical capabilities**: Terminal chat, repository interaction, command execution, tools, MCP integrations, and coding workflows

**74. Gemini Code Assist**

- **Link**: https://codeassist.google
- **Description**: IDE-integrated coding assistant for professional developers
- **Features**:
  - VS Code and JetBrains integration
  - Cloud console integration
  - Context-aware suggestions, refactors, and explanations
  - Powered by latest Gemini models
  - Tightly integrated with Google Cloud and Git
  - Customized for coding tasks
- **Availability**: Google AI Pro/Ultra subscribers

**75. Gemini Cloud Assist**

- **Link**: https://cloud.google.com/products/gemini
- **Description**: AI assistant in Cloud Console for designing, deploying, and operating workloads
- **Features**:
  - Propose and refine architectures
  - Generate IaC snippets and configs
  - Debug deployment issues and logs
  - Optimize cost and performance recommendations
- **Integration**: Google Cloud Console

**76. Google Colab (with Gemini)**

- **Link**: https://colab.google
- **Description**: Online Python notebook environment with AI assistance
- **Features**:
  - Free GPU/TPU access for ML experimentation
  - Collaborative coding
  - AI/ML experimentation environment
  - Integrated Gemini assistance for code help
  - Inline Gemini coding assistance
- **Availability**: Free tier + paid plans (Colab Pro)

**77. Genkit**

- **Link**: https://firebase.google.com/docs/genkit/overview
- **Description**: Open-source framework for building agentic AI applications
- **Features**:
  - Python and Go support
  - Firebase integration
  - Build complex AI applications with agent workflows
- **Integration**: Firebase Studio, Vertex AI

### **APIs & Cloud AI Infrastructure**

**78. Gemini API**

- **Link**: https://ai.google.dev
- **Description**: REST/gRPC API for accessing Gemini models
- **Features**:
  - Access to all Gemini models (1.x, 2.5, 3)
  - Multimodal input support (text, vision, audio, video)
  - Function calling and tool use
  - Long context windows (up to 2 million tokens for some tiers)
  - Multimodal capabilities
- **Availability**: Developers worldwide

**79. Vertex AI**

- **Link**: https://cloud.google.com/products/ai
- **Description**: Enterprise AI platform on Google Cloud
- **Features**:
  - Access to Gemini, Imagen, Veo models
  - Third-party models available
  - Vertex Model Garden
  - Agent Builder
  - Enterprise-grade features (security, compliance, scale)
  - Training, deployment, and orchestration tools
- **Availability**: Google Cloud customers

**80. Gemini in BigQuery & Looker**

- **Link**: https://cloud.google.com/bigquery/docs/gemini-for-bigquery
- **Description**: AI-assisted data analytics and exploration
- **Features**:
  - SQL generation and explanation
  - Natural language data exploration in Looker
  - Schema understanding and code assistance
- **Availability**: Google Cloud customers

**81. Dialogflow / CCAI**

- **Link**: https://cloud.google.com/dialogflow
- **Description**: Conversational AI platform for building chatbots and voice agents
- **Features**:
  - Natural language understanding
  - Multi-channel deployment
  - Contact center AI integration
  - Now heavily integrated with Gemini
- **Use**: Enterprise customer service, IVR systems, chatbots
- **Availability**: Google Cloud customers

**82. Document AI**

- **Link**: https://cloud.google.com/document-ai
- **Description**: Platform to process and transform unstructured documents into structured data
- **Features**:
  - OCR and document parsing
  - Automated data extraction
  - Classification and analysis
  - Custom document processors
- **Use**: Enterprise document processing workflows
- **Availability**: Google Cloud customers

**83. Speech, Text & Translation APIs**

- **Link**: https://cloud.google.com/products/ai
- **Description**: Suite of AI APIs for speech and language processing
- **Includes**:
  - **Speech-to-Text**: Convert audio to text
  - **Text-to-Speech**: Generate natural speech
  - **Translation AI**: Translate between languages
  - **Natural Language API**: Text analysis and understanding
- **Use**: Build applications with voice and language capabilities
- **Availability**: Google Cloud customers

**84. Cloud AI Vertical APIs**

- **Description**: Specialized pre-trained models for specific industries and tasks
- **Includes**:
  - **Vision API & Video Intelligence API**: Image and video analysis
  - **Contact Center AI (CCAI)**: Customer service automation (Dialogflow CX)
  - **Retail API**: Search and recommendations for e-commerce
  - **Translation Hub**: Enterprise-grade translation
- **Availability**: Google Cloud

---

## 🎮 **Experimental & Niche AI Tools**

**85. Doppl**

- **Link**: https://labs.google/doppl
- **Description**: Virtual fashion try-on application
- **Features**:
  - Upload full-body photos
  - Try on different outfits virtually
  - Generate animated clips showing outfits
  - Outputs stills and animations
- **Availability**: Android and iOS (limited regions)

**86. Food Mood**

- **Description**: Recipe generator based on mood and cultural fusion
- **Features**:
  - Fusion-style meal ideas
  - Mood-based cooking inspiration
  - Combine two countries for unique fusion dishes
  - Generates recipe with AI image of the result
- **Status**: Experimental
- **Availability**: Google Arts & Culture

**87. Talking Tours**

- **Description**: AI-generated audio tour generator for locations and museums
- **Features**:
  - Create custom audio tours
  - Auto-generated museum and location guides
- **Status**: Experimental
- **Availability**: Google Arts & Culture

**88. National Gallery Mixtape**

- **Link**: https://labs.google
- **Description**: Art-to-music experience that converts artwork into sound
- **Features**:
  - Drag paintings to hear their "sound"
  - Generates personalized soundtracks from artwork
  - Art-to-music conversions
  - Similar to MusicFX DJ for visual art
- **Availability**: Google Arts & Culture / Labs

**89. Portraits**

- **Link**: https://labs.google
- **Description**: AI chatbots based on real experts and authors
- **Features**:
  - Chat with AI replicas of experts (Kim Scott, Matt Dicks)
  - Get advice, feedback, and perspectives
  - Learn from expert knowledge and experience
- **Availability**: Google Labs

---

## 🧪 **Legacy/Archive AI Experiments**

**90. AI Test Kitchen**

- **Description**: Original platform for testing early AI experiments
- **Features**:
  - Early access to MusicFX, ImageFX, TextFX predecessors
  - Access to new experimental tools
- **Availability**: Limited regions
- **Status**: Legacy platform; most active experiments moved to labs.google

**91. Experiments with Google**

- **Link**: https://experiments.withgoogle.com
- **Description**: Archive of historical AI and tech experiments
- **Features**:
  - Historical showcase of past experiments
  - TensorFlow Lite experiments
  - Educational collections
  - Magenta and quirky TensorFlow demos
- **Status**: Archive (active development moved to labs.google)

---

## 🧠 **Core AI/ML Models & Research**

### **Foundation Models**

**92. Gemini Model Family**

- **Link**: https://ai.google.dev/gemini-api/docs/models
- **Description**: Google's multimodal model family spanning reasoning, coding, agents, audio, images, video, and efficient deployment
- **Current public highlights (June 24, 2026)**:
  - **Gemini 3.5 Flash**: Generally available; frontier agentic/coding performance
  - **Gemini 3.1 Pro**: High-capability reasoning model
  - **Gemini 3.1 Flash-Lite**: Generally available, cost/scale optimized
  - **Gemini 3.1 Flash Image (Nano Banana 2)** and **Gemini 3 Pro Image (Nano Banana Pro)**: Generally available native visual models
  - **Gemini Omni Flash**: Rolling out as the first Gemini Omni model for multimodal-to-video creation/editing
- **Announced, not yet generally available as of June 24, 2026**: **Gemini 3.5 Pro**; Google said at I/O 2026 that it was still in development and planned for a later rollout
- **Developer access**: Gemini API, Google AI Studio, Antigravity, Android Studio, Vertex AI / Gemini Enterprise depending on model

**93. Gemini 3.1 Pro**

- **Link**: https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-1-pro
- **Description**: Smarter model for complex problem-solving
- **Features**:
  - More than double the reasoning performance of 3 Pro
  - Designed for tasks where simple answers aren't enough
  - Visual explanations, data synthesis, creative projects
  - Available to developers, enterprises, and consumers
- **Access**: Gemini API, Vertex AI, Gemini app, NotebookLM
- **Announced**: February 2026

**94. Gemini 3.1 Flash-Lite**

- **Link**: https://ai.google.dev/gemini-api/docs/models/gemini-3.1-flash-lite
- **Description**: Low-latency, cost-efficient multimodal model optimized for high-frequency lightweight and agentic workloads
- **Inputs**: Text, image, video, audio, and PDF
- **Use cases**: High-volume extraction, classification, transformation, moderation support, routing, and latency-sensitive applications
- **Verified status**: Generally available since May 7, 2026
- **Lifecycle**: The preview endpoint was shut down May 25, 2026; use the stable `gemini-3.1-flash-lite` model ID
- **Pricing/limits**: Consult the live Gemini API pricing and rate-limit pages; fixed prices and leaderboard scores were removed because they are volatile

**95. Gemini 3 Deep Think (Updated)**

- **Link**: https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-deep-think/
- **Description**: Specialized reasoning mode for science, research, and engineering
- **Features**:
  - Major upgrade for modern science/engineering challenges
  - Works with messy/incomplete data
  - Achieves 48.4% on Humanity's Last Exam (without tools)
  - 84.6% on ARC-AGI-2 (verified by ARC Prize Foundation)
  - 3455 Elo on Codeforces
  - Gold-medal level on 2025 International Math Olympiad
  - Excels in physics and chemistry Olympiads
- **Access**: Gemini app (Google AI Ultra subscribers), early access via API
- **Announced**: February 12, 2026

**96. Gemini Audio**

- **Description**: Native end-to-end audio understanding and generation capabilities
- **Features**:
  - Direct speech-to-speech processing (no text intermediate)
  - Understands tone, emotion, and nuance
  - Generates expressive speech in real-time
- **Use**: Powers Gemini Live and NotebookLM Audio Overviews

**97. Imagen 3 & Imagen 4 (API Deprecation Status)**

- **Link**: https://ai.google.dev/gemini-api/docs/deprecations
- **Description**: Google's dedicated text-to-image model line; newer native Gemini image models now cover many generation/editing workflows
- **Verified status (June 24, 2026)**:
  - Imagen 4 API models are marked deprecated, with shutdown scheduled for **August 17, 2026**
  - Developers should check the live deprecations page and migrate to supported native Gemini image models where appropriate
  - Gemini 3.1 Flash Image and Gemini 3 Pro Image GA variants replaced their preview endpoints; preview endpoints were scheduled to shut down June 25, 2026
- **Historical use**: ImageFX, enterprise image generation, and visual creative workflows

**98. PaLM 2 Family (Sunset April 2026)**

- **Note**: Replaced by Gemini family models.

**99. Lyria**

- **Link**: https://deepmind.google/models
- **Description**: Advanced music generation model from Google DeepMind
- **Features**:
  - Rich vocals and arrangement capabilities
  - Real-time interactive music creation
  - Professional-grade music generation
- **Use**: Powers MusicFX, MusicFX DJ, Music AI Sandbox

**100. Gemma 4 Family**

- **Link**: https://deepmind.google/models/gemma/gemma-4
- **Description**: Fourth-generation open-weight model family released under Apache 2.0 license
- **Variants**:
  - **31B Dense**: Flagship open model (Top 3 open models on Arena.ai)
  - **26B A4B**: Mixture of Experts (MoE), activates ~4B per token
  - **E4B / E2B**: Effective 4B/2B sizes optimized for on-device/edge deployment
- **Key Features**:
  - **Thinking variants**: Built-in step-by-step reasoning
  - Native multi-modal processing (Text, Image, Audio)
  - 256K context window; supported in AICore for Android
- **Announced**: April 2, 2026
- **License**: Apache 2.0

**101. Gemini Robotics-ER 1.6**

- **Link**: https://deepmind.google/blog/gemini-robotics-er-1-6/
- **Description**: Embodied reasoning model for robotics (Boston Dynamics collaboration)
- **Features**:
  - Enhanced spatial logic and multi-view understanding
  - **Instrument reading**: Capability to read analog gauges and sight glasses
  - Precision task planning and success detection
- **Availability**: Gemini API, Google AI Studio
- **Announced**: April 14, 2026

**102. TimesFM**

- **Link**: https://github.com/google-research/timesfm
- **Description**: Foundation model for time-series forecasting
- **Features**:
  - Pretrained on large time-series datasets
  - Outperforms classical baselines on forecasting tasks
  - Zero-shot forecasting capabilities
- **Integration**: BigQuery ML, Google Cloud

**103. LearnLM**

- **Link**: https://deepmind.google/technologies/learnlm
- **Description**: Family of models fine-tuned for learning and education
- **Features**:
  - Grounded in educational research
  - Powers learning features in Gemini, YouTube, and Search
  - Conversational tutoring capabilities
- **Use**: Education-focused applications

**104. SynthID**

- **Link**: https://deepmind.google/technologies/synthid
- **Description**: Digital watermarking technology for AI-generated content (image/video/audio/text)
- **Features**:
  - Imperceptible watermarks for images, audio, video, and text
  - Helps identify AI-generated content
  - Maintains content quality while adding authentication
  - Remains detectable after cropping, resizing, filtering, and compression
  - Public detector portal for verification (synthid.google.com)
  - Embedded in 20B+ pieces of content across Google AI tools
- **Use**: Embedded in ImageFX, MusicFX, Veo, Lyria, Gemini outputs for content authenticity
- **Best For**: Content authenticity verification, AI transparency, copyright protection
- **Pricing**: Free detection | Watermarking included with Google AI tools
- **Comparison**: Only multi-modal watermarking solution; embedded in 20B+ pieces of content

### **Specialized Research Models**

**105. Genie 3 / Project Genie**

- **Link**: https://deepmind.google/models/genie/
- **Description**: Google DeepMind world-model research for generating interactive environments from prompts and images
- **Features**:
  - Creates explorable, temporally consistent virtual worlds
  - Supports interactive movement and environment response
  - Research platform for world simulation and embodied/agent research
- **Product access**: **Project Genie** is listed as a Google AI Ultra experiment for eligible adult users in supported regions
- **Status**: Active research/experimental product; not a conventional game engine or generally available production API

**106. AlphaFold**

- **Link**: https://deepmind.google/technologies/alphafold
- **Description**: Revolutionary protein structure prediction system
- **Features**:
  - Predicts 3D structure of proteins and biological molecules
  - Breakthrough in computational biology
  - Drug discovery applications
- **Status**: Research breakthrough from Google DeepMind
- **Impact**: Major scientific advancement in biology

**107. AlphaGenome**

- **Link**: https://deepmind.google/blog/alphagenome-ai-for-better-understanding-the-genome/
- **Description**: AI tool for identifying genetic drivers of disease
- **Features**:
  - Predicts how mutations disrupt gene regulation
  - Helps decode DNA's "dark matter" (noncoding regions)
  - Applications in rare disease diagnosis and cancer research
- **Announced**: January 28, 2026
- **Status**: Research tool from Google DeepMind

**108. Aletheia**

- **Description**: Autonomous mathematics research agent
- **Features**:
  - Built on Gemini Deep Think
  - Generator-Verifier-Reviser (GVR) architecture
  - Iterative proof generation and verification
  - Bridges competition math to professional research
- **Announced**: February 12, 2026
- **Status**: Research agent from Google DeepMind

**109. Gemini Robotics**

- **Description**: Vision-language-action model for robotics applications
- **Features**:
  - Designed for robotics control and understanding
  - Enables more capable and helpful robots
  - Multimodal robot interaction
- **Status**: Research project

**110. Magenta**

- **Link**: https://magenta.tensorflow.org
- **Description**: Deep learning research project exploring AI in art and music
- **Features**:
  - Open-source tools for artists and musicians
  - Music generation and art creation experiments
  - Historical ML creative tools
- **Status**: Research/Archive project

**111. MusicLM**

- **Description**: Earlier text-to-music research model
- **Features**:
  - Pioneering music generation from text
  - Foundation for later music tools
- **Status**: Research model; evolved into MusicFX and Lyria

---

## 📱 **AI Integration & Ecosystem Features**

### **Maps & Location AI**

**112. Immersive View in Google Maps**

- **Link**: https://maps.google.com
- **Description**: AI-powered 3D visualization of routes and locations
- **Features**:
  - 3D fly-throughs of routes
  - AI-powered environment visualization
  - Route previews with realistic rendering
  - Weather and traffic predictions
- **Use**: Enhanced navigation planning and exploration
- **Availability**: Select cities globally, expanding

**113. Maps AI Features**

- **Link**: https://maps.google.com
- **Features**:
  - Semantic search: "quiet cafes with WiFi and outdoor seating"
  - Natural language place queries
  - Route summaries and recommendations
  - AI-powered place insights
- **Integration**: Google Maps app

### **Smart Home AI**

**114. Google Home Premium**

- **Description**: Smart home subscription tier with extended AI features
- **Features**:
  - Gemini integration for smart home control
  - 30 days event history (extended from standard)
  - Enhanced routines and automation
  - Advanced voice control
  - **Gemini describes live camera feeds**: AI can now understand and describe what's happening in real-time on your cameras (March 2026)
- **Availability**: Subscription service

**115. Gemini in Google Home**

- **Description**: AI-powered smart home control with Gemini
- **Features**:
  - Describe live camera feeds using Gemini AI
  - Natural language control of smart home devices
  - Understand context and provide intelligent responses
- **Announced**: March 3, 2026

### **YouTube AI Features**

**116. Dream Screen**

- **Description**: AI-generated backgrounds for YouTube Shorts
- **Features**:
  - Custom video backgrounds from text prompts
  - Green screen replacement with AI
  - Creator-focused generative backgrounds
- **Availability**: YouTube Shorts creators

**117. Dream Track & YouTube Music AI Tools**

- **Description**: AI-assisted music generation for YouTube creators
- **Features**:
  - Music generation tools powered by Lyria
  - Creator-focused music creation
  - Integration with Music AI Sandbox
- **Availability**: YouTube creators, Music AI Sandbox

**118. YouTube Aloud**

- **Link**: https://aloud.area120.google.com
- **Description**: AI-powered dubbing and translation tool for creators
- **Features**:
  - Automatically dub videos into other languages
  - High-quality synthetic voice dubbing
  - Review and edit transcripts before dubbing
- **Availability**: YouTube creators (expanding)

**119. YouTube Deepfake Disclosure Tools**

- **Link**: https://support.google.com/youtube/answer/14323336
- **Description**: Tools for labeling and managing AI-generated content on YouTube
- **Features**:
  - Mandatory disclosure labels for realistic synthetic content
  - Privacy request process for AI-generated likenesses
  - Content Credentials support for authenticity
- **Availability**: Global YouTube creators

### **Android & Device AI Features**

**120. Circle to Search**

- **Description**: On-screen visual search for Android devices
- **Features**:
  - Search anything on your screen instantly
  - Draw around objects, text, or areas to search
  - No app switching required
  - Multi-object recognition (February 2026)
  - Virtual try-on capabilities (March 2026)
- **Powered by**: Gemini Nano (on-device)
- **Availability**: Android devices with Gemini Nano support (Pixel 10, Galaxy S26)

**121. On-device Gemini Nano**

- **Description**: On-device AI models for Android and Chrome
- **Features**:
  - Notification summaries
  - Smart reply suggestions
  - Offline AI capabilities
  - Privacy-preserving on-device processing
- **Use**: Powers Circle to Search, notification features, offline AI
- **Availability**: Select Android devices (Pixel 8+, select flagships)

**122. Android AI Features**

- **Features Include**:
  - **Recorder summaries**: AI transcription and summarization
  - **Call screening**: AI-powered spam and call filtering
  - **Smart compose**: Writing suggestions across apps
  - **Live translate**: Real-time translation in calls
- **Availability**: Android devices, enhanced on Pixel

**123. Accessibility AI Features**

- **Description**: AI-powered tools for accessibility and inclusion
- **Features**:
  - **Live Caption**: Real-time captioning for media
  - **Live Transcribe**: Speech-to-text for conversations
  - **Project Relate**: Custom speech models for non-standard speech
  - **TalkBack**: AI-enhanced screen reader
- **Availability**: Android and Chrome

**124. Google Essentials (Windows app)**

- **Description**: Integrated Google experience for Windows PCs
- **Features**:
  - Access Gemini, Photos, and Messages from the desktop
  - Play Games on PC
  - Seamless cross-device integration
- **Availability**: Select Windows PCs (HP, etc.)

---

## 💰 **AI Subscription Plans & Access Tiers**

**125. Free Gemini Tier**

- **Link**: https://gemini.google
- **Description**: Free access to core Gemini capabilities
- **Includes**:
  - Access to Gemini 2.5 Flash
  - Basic Imagen 4 image generation
  - Some Veo video generation (limited)
  - NotebookLM with smaller limits
  - Basic Google Search AI features
- **Availability**: Global (with regional variations)

**126. Google AI Plus (around $7.99/month US)**

- **Link**: https://one.google.com/about/plans
- **Description**: Consumer AI subscription (mid-tier)
- **Includes**:
  - Access to Gemini 3 Pro
  - 200GB cloud storage
  - Nano Banana Pro access
  - Veo 3 Fast
  - Lyria 3 music generation
  - Integration with Gmail, Docs, Sheets
  - 50% off for first 2 months (promotional)
- **Availability**: 35+ countries including US (launched January 27, 2026)

**127. Google AI Pro (around $19.99/month US)**

- **Link**: https://one.google.com/about/plans
- **Description**: Consumer AI subscription (previously branded as Google One AI Premium) and other AI benefits
- **Includes**:
  - Higher limits on all Gemini models
  - Gemini 2.5 Pro and limited Gemini 3 Pro access
  - AI Mode in Search with Gemini 3 Pro
  - Flow: 100 video generations per month
  - Whisk with Veo 3 access
  - Jules with higher limits
  - Enhanced NotebookLM features
  - Nano Banana Pro image generation
  - Deeper Gmail/Docs/Drive integration
  - Approximately 2TB cloud storage bundled
  - **Google Cloud credits** for building and deploying AI applications (January 2026)
  - Developer Program premium benefits
- **Availability**: Most countries globally

**128. Google AI Ultra**

- **Link**: https://blog.google/products-and-platforms/products/google-one/google-ai-subscriptions/
- **Description**: Google's highest consumer AI subscription tier, with the highest limits and early access across Gemini and creative/agentic products
- **Verified I/O 2026 highlights**:
  - Higher Gemini and Antigravity limits than Pro (Google announced a 5× tier; some markets/accounts may expose other variants)
  - Gemini 3.5 Flash and priority access to newer models/features
  - Google Antigravity, Flow, Flow Music, Gemini Spark, Project Genie, and other eligible experiments depending on region
  - 20 TB cloud storage in the newly announced US plan
  - YouTube Premium Lite in the announced US bundle
- **Project Mariner**: Still included for eligible users where available
- **Availability/pricing**: Varies by country, account, age, and plan variant; verify on Google One before purchase

**129. Enterprise / Workspace / Vertex SKUs**

- **Link**: https://cloud.google.com/vertex-ai/pricing
- **Description**: Business and enterprise-focused AI access
- **Includes**:
  - **Gemini Enterprise**: Workspace add-on for businesses
  - **Vertex AI**: Usage-based pricing for cloud customers
  - **Workspace Gemini**: Seat-based subscriptions
  - Custom enterprise agreements
  - Advanced security and compliance features
- **Availability**: Through Google Cloud and Workspace sales

---

## 🌐 **Platform Hubs & Access Points**

**130. Google Labs**

- **Link**: https://labs.google
- **Description**: Central hub for AI experiments and early-access features
- **Purpose**: Test and provide feedback on experimental AI tools before wide release
- **Contents**: 35+ active experiments (rotating)
- **Access**: Free with Google account (age requirements vary by region)

**131. labs.google/fx**

- **Link**: https://labs.google/fx
- **Description**: Sub-hub focused on creative generative tools
- **Contents**: ImageFX, MusicFX, Flow, Whisk, TextFX, GenType
- **Focus**: Creative AI experiments for media generation

**132. Search Labs**

- **Link**: https://labs.google.com/search
- **Description**: Early-access program for experimental Search features
- **Contents**: AI Overviews variants, Search Live, experimental search experiences
- **Purpose**: Test new search capabilities before general rollout

**133. Google AI**

- **Link**: https://ai.google
- **Description**: Main portal for Google AI products and information
- **Purpose**: Overview of AI capabilities, product information, and access points
- **Contents**: Product showcase, research papers, developer resources

---

## 📊 **Key Statistics & Scale**

### **User Adoption**

- **Gemini App**: ~650 million users globally (late 2025, approximate)
- **AI Overviews**: **Statistics**: Served billions of queries (availability expanding)
- **AI Mode**: Available in ~180 countries
- **NotebookLM**: Millions of users across 200+ countries and territories (approximate)

### **Content Generation**

- **Flow**: Generated hundreds of millions of videos (approximate)
- **Nano Banana**: 5+ billion images generated (late 2025) (approximate)
- **MusicFX**: 10+ million tracks created (approximate)
- **ImageFX**: Available in 110+ countries

### **Language & Regional Coverage**

- **NotebookLM**: Reports in 80+ languages; audio/video in many languages
- **ImageFX**: 37 languages supported
- **AI Mode**: Available in ~180 countries (English, expanding)
- **Most tools**: Available in 140-180 countries (varies by tool)

---

## 🌍 **Availability & Regional Notes**

### **Geographic Restrictions**

- **US-Only or restricted features**:
  - Project Mariner (eligible Google AI Ultra accounts; availability varies)
  - Career Dreamer
  - Some I/O 2026 experiments, including Gemini Spark at launch
- **Limited Regional Availability**:
  - MusicFX: Initially US, Australia, New Zealand, Kenya (expanding)
  - Some Labs experiments: Regional limitations apply
- **Global Rollouts**:
  - AI Mode: ~180 countries (English, expanding)
  - Opal: 160+ countries (as of 2025)
  - NotebookLM: 200+ countries and territories

### **Age Requirements**

- Most Labs experiments: 13+ or 18+ depending on region and local regulations
- Workspace features: Set by organization administrators
- Consumer features: Per Google account age requirements

### **Language Support**

- **English**: Full support across all products
- **Major languages**: 37-80+ languages depending on specific tool
- **Expanding**: Continuous addition of new languages

### **Access Requirements**

- **Google Account**: Required for most services
- **Subscription**: Required for Pro/Ultra features
- **Waitlist**: Some features require waitlist signup (e.g., Project Mariner, Illuminate)
- **Regional availability**: Some features gated by country/region

---

## 🆕 **Verified Google I/O 2026 & June 2026 Additions**

> The following entries were missing from the April 22 repository snapshot. Availability statements reflect public Google sources checked through June 24, 2026.

### **Models, Creation & Personal Intelligence**

**134. Gemini 3.5 Flash**

- **Link**: https://ai.google.dev/gemini-api/docs/models
- **Description**: First generally available model in the Gemini 3.5 family, focused on frontier agentic and coding performance
- **Access**: Gemini API, Google AI Studio, Antigravity, Android Studio, Gemini Enterprise, AI Mode, and rolling out in the Gemini app
- **Announced**: May 19, 2026

**135. Gemini Omni / Gemini Omni Flash**

- **Link**: https://blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements/
- **Description**: “Create anything from any input” multimodal model family, launching first with video generation and conversational editing
- **Inputs**: Text, images, video, and audio references
- **Access**: Rolling out globally to eligible Google AI Plus/Pro/Ultra users in Gemini and Flow; also announced for YouTube Shorts and YouTube Create for eligible users

**136. Gemini Spark**

- **Description**: New proactive Gemini experience announced at I/O 2026 for creating personalized, interactive briefings and experiences
- **Initial access**: Trusted testers / eligible Ultra users in the United States; broader availability subject to rollout

**137. Daily Brief**

- **Description**: Personalized daily summary experience announced for Google AI subscribers
- **Initial rollout**: Adults in the United States, with expansion planned

**138. Neural Expressive UI**

- **Description**: Google research/product direction for interfaces that dynamically adapt their structure and presentation to the user's task
- **Status**: Announced at I/O 2026; availability varies by product experiment

### **Search, Commerce & Agents**

**139. Search Information Agents**

- **Description**: Agentic Search capability designed to gather, compare, and synthesize information across the web
- **Availability**: Google announced a summer 2026 rollout beginning with Pro and Ultra subscribers
- **Status**: Announced; do not treat as fully rolled out until visible in the user's account

**140. Generative UI & Antigravity in Search**

- **Description**: Search can generate interactive visual interfaces and, in supported experiences, invoke Antigravity-backed agentic workflows
- **Announced**: Google I/O 2026

**141. Universal Cart & Universal Commerce Protocol (UCP)**

- **Description**: Google commerce infrastructure for agent-assisted product discovery and checkout across participating merchants
- **Status**: Announced at I/O 2026; merchant/region support varies

### **Developer & Agent Platform**

**142. Google Antigravity 2.0**

- **Link**: https://antigravity.google/
- **Description**: Major update to Google's agent-first development platform
- **Features**: Long-running/async tasks, multi-agent workflows, stronger planning, subagents, hooks, artifacts, and desktop/CLI coordination

**143. Antigravity CLI**

- **Link**: https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/
- **Description**: Agent-first command-line tool replacing Gemini CLI for individual/free/Pro/Ultra users
- **Availability**: Available to everyone; consumer migration completed June 18, 2026

**144. Antigravity SDK**

- **Description**: Developer kit for embedding Antigravity agents and workflows into applications and internal systems
- **Status**: Announced at I/O 2026; consult current developer documentation for access

**145. Managed Agents in the Gemini API**

- **Link**: https://ai.google.dev/gemini-api/docs/changelog
- **Description**: Public-preview service for autonomous, stateful agents in secure Google-hosted Linux sandboxes
- **Released**: May 19, 2026

**146. WebMCP**

- **Description**: Web platform work that lets websites expose structured actions and capabilities to compatible AI agents
- **Status**: Announced at I/O 2026; implementation support is evolving

**147. Modern Web Guidance for AI Agents**

- **Description**: Guidance and tooling intended to make websites more understandable, accessible, and operable by AI agents
- **Status**: Developer initiative announced at I/O 2026

**148. Chrome DevTools for Agents**

- **Description**: Agent-oriented browser debugging and inspection capabilities for building and testing web agents
- **Status**: Announced at I/O 2026

**149. AI Studio Mobile App & Expanded App Building**

- **Link**: https://aistudio.google.com/
- **Description**: Mobile access and expanded end-to-end app-building workflow announced for Google AI Studio
- **Features announced**: Android app generation, Workspace integration, Play Console/Test Track paths, free deployment allowances, and export to Antigravity

### **Communication, Workspace & Media**

**150. AI Inbox**

- **Description**: Agentic inbox experience that prioritizes and helps act on important messages/tasks
- **Availability**: Announced as a Google AI subscription benefit; rollout varies

**151. Gmail Live**

- **Description**: Live, conversational assistance inside Gmail for understanding and acting on email context
- **Status**: Announced at I/O 2026

**152. Google Pics**

- **Description**: New AI-native visual creation and editing experience announced for trusted testers, with a broader rollout planned
- **Status**: Trusted-test phase as of June 24, 2026

**153. Docs Live**

- **Description**: Live conversational collaboration with Gemini inside Google Docs
- **Status**: Announced at I/O 2026

**154. Talk to Keep**

- **Description**: Conversational interaction with Google Keep notes
- **Status**: Announced at I/O 2026

**155. Flow Agent**

- **Link**: https://labs.google/flow/about
- **Description**: Agentic creative collaborator inside Flow for planning and producing media workflows
- **Status**: Announced at I/O 2026

**156. Flow Tools**

- **Description**: Reusable creative tools/workflows inside Flow for image, video, and asset production
- **Status**: Announced at I/O 2026

**157. Google Flow Music**

- **Description**: Music-creation environment built around Google's generative music models and professional creative controls
- **Availability**: Included among eligible Google AI Ultra benefits; access varies by region/account

**158. Ask YouTube**

- **Description**: Conversational feature for asking questions about video content and discovering relevant moments/information
- **Status**: Announced at I/O 2026

### **Science, Research & Trust**

**159. Gemini for Science**

- **Description**: Research-focused Gemini environment for scientific reasoning and discovery workflows
- **Status**: Announced at I/O 2026

**160. Hypothesis Generation**

- **Description**: Scientific agent capability for proposing testable hypotheses from literature, data, and research context
- **Status**: Announced research capability

**161. Computational Discovery**

- **Description**: Tools/agents for planning and running computational scientific investigations
- **Status**: Announced research capability

**162. Literature Insights**

- **Description**: Research synthesis capability for extracting patterns and evidence across scientific literature
- **Status**: Announced at I/O 2026

**163. Science Skills**

- **Description**: Specialized reusable capabilities for scientific analysis and research tasks
- **Status**: Announced at I/O 2026

**164. Paper Assistant Tool (PAT) & ScholarPeer**

- **Description**: Research-writing and peer-feedback assistance announced for scientific workflows
- **Status**: Experimental/research access; not a replacement for expert peer review

**165. SynthID Verification + C2PA Content Credentials**

- **Link**: https://deepmind.google/technologies/synthid/
- **Description**: Expanded provenance verification combining SynthID detection with C2PA Content Credentials for supported AI-generated media
- **Update**: Google highlighted verification/provenance expansion at I/O 2026

### **Additional Missing Items Added from June 2026 Review**

**166. Magic Cue**

- **Description**: Proactive contextual assistant feature for Pixel devices that surfaces relevant app information and suggested actions based on what the user is doing
- **Scope**: Pixel-first device intelligence; exact availability varies by device generation, region, and supported app integrations
- **Category note**: Fits the Android/device AI layer even though it also overlaps with Gemini-powered assistance

**167. Vertex AI Agent Engine**

- **Link**: https://cloud.google.com/vertex-ai/generative-ai/docs/agent-engine/overview
- **Description**: Managed runtime and operational layer for deploying, running, and scaling production AI agents on Google Cloud
- **Relationship to nearby entries**: Complements Vertex AI and Managed Agents in the Gemini API rather than replacing them

**168. Agent Development Kit (ADK)**

- **Link**: https://google.github.io/adk-docs/
- **Description**: Google's open framework for building multi-step AI agents with tools, state, and deployable workflows
- **Integration**: Used alongside Vertex AI and related Google agent infrastructure for custom agentic applications

**169. Agent2Agent Protocol (A2A)**

- **Link**: https://developers.googleblog.com/en/announcing-the-agent2agent-protocol-a2a/
- **Description**: Open interoperability protocol initiated by Google for communication between agents across vendors, systems, and runtimes
- **Status**: Standards/protocol entry rather than a consumer-facing product

---

## ⚠️ **Developer Model Lifecycle Snapshot (Verified June 24, 2026)**

| Model/API family                            | Verified state                                 | Action                                                                          |
| ------------------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------- |
| Gemini 3.5 Flash                            | Generally available                            | Use current stable model ID                                                     |
| Gemini 3.1 Flash-Lite                       | Generally available                            | Replace preview ID                                                              |
| Gemini 3.1 Flash Image / Gemini 3 Pro Image | GA                                             | Preview endpoints scheduled to shut down June 25, 2026                          |
| Gemini 2.0 Flash / Flash-Lite               | Shut down June 1, 2026                         | Migrate immediately                                                             |
| Imagen 4 API models                         | Deprecated; shutdown scheduled August 17, 2026 | Migrate to supported image models                                               |
| Veo 2 / Veo 3 / Veo 3 Fast API models       | Scheduled shutdown June 30, 2026               | Migrate to Veo 3.1 variants                                                     |
| Veo 3.1 Lite                                | Preview                                        | Use for lower-cost/high-throughput workflows where preview terms are acceptable |

## 📅 **Update Information**

**Last Updated**: June 24, 2026

**Update Frequency**: Google Labs experiments are updated frequently. New tools are regularly added, and experimental features may be:

- Graduated to production (e.g., NotebookLM, MusicFX)
- Discontinued if not successful
- Integrated into main Google products
- Expanded to new regions and languages

**Version Changes**:

- **June 2026 verification pass**:
  - Added Gemini 3.5 Flash, Gemini Omni Flash, Antigravity 2.0/CLI/SDK, Managed Agents, I/O 2026 Search/Workspace/media/science announcements, and provenance updates
  - Added the still-missing Magic Cue, Vertex AI Agent Engine, Agent Development Kit (ADK), and Agent2Agent Protocol (A2A)
  - Corrected Project Mariner: active restricted research prototype, not discontinued
  - Corrected Gemini CLI: consumer transition completed June 18, 2026; enterprise support remains
  - Added official API deprecation/shutdown snapshot
  - Marked Gemini 3.5 Pro as announced/in development rather than publicly available
- **May 2026**:
  - Google I/O 2026 announcements across models, Search, agents, commerce, media, Workspace, science, Android XR, and trust/provenance
  - Gemini 3.5 Flash GA and Managed Agents public preview
  - Native Gemini image models moved to GA variants
- **April 2026 and earlier**:
  - Retained historical entries where still useful; current status fields take precedence over older launch notes

---

## 🔗 **Primary Access Points Summary**

| Access Point            | URL                                  | Purpose                                               |
| ----------------------- | ------------------------------------ | ----------------------------------------------------- |
| **Google Labs**         | https://labs.google                  | Experimental AI tools hub                             |
| **Creative Tools (fx)** | https://labs.google/fx               | Image, music, video generation                        |
| **Gemini Chat**         | https://gemini.google                | Main AI assistant interface                           |
| **AI Studio**           | https://aistudio.google.com          | Developer prototyping platform                        |
| **NotebookLM**          | https://notebooklm.google            | Research assistant                                    |
| **Stitch**              | https://stitch.withgoogle.com        | UI design tool                                        |
| **Code Wiki**           | https://codewiki.google              | Code documentation                                    |
| **Vertex AI**           | https://cloud.google.com/products/ai | Enterprise AI platform                                |
| **Gemini API**          | https://ai.google.dev                | Developer API access                                  |
| **Google Cloud AI**     | https://cloud.google.com/products/ai | Cloud AI services                                     |
| **DeepMind**            | https://deepmind.google/models       | Research models info                                  |
| **Search Labs**         | https://labs.google.com/search       | Early-access program for experimental Search features |

---

## 📚 **Primary Sources Used for the June 2026 Refresh**

- Google I/O 2026 announcement index: https://blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements/
- Gemini API release notes: https://ai.google.dev/gemini-api/docs/changelog
- Gemini API deprecations: https://ai.google.dev/gemini-api/docs/deprecations
- Gemini API models: https://ai.google.dev/gemini-api/docs/models
- Gemini CLI → Antigravity CLI transition: https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/
- Google AI subscription updates: https://blog.google/products-and-platforms/products/google-one/google-ai-subscriptions/
- Project Mariner / AI Ultra help: https://support.google.com/a/answer/16345165
- Veo 3.1 API documentation: https://ai.google.dev/gemini-api/docs/video
- SynthID: https://deepmind.google/technologies/synthid/

## 📝 **Important Notes**

1. **Experimental Status**: Many Labs features are experimental and may change or be discontinued
2. **Pricing Variability**: Subscription prices vary by country; US pricing shown as reference
3. **Feature Availability**: Not all features available in all regions; check specific tool pages for your location
4. **Access Tiers**: Some features require paid subscriptions (Pro/Ultra)
5. **Waitlists**: New experimental features often have waitlists before general availability
6. **Beta Status**: Many tools marked as "beta" or "preview" with ongoing development
7. **Integration Changes**: Features frequently integrated into main Google products from Labs
8. **Google Products Only**: This catalogue includes only Google-developed AI/ML products and services

---

_This catalogue covers **169 numbered Google AI/ML/Data Science products, services, models, experiments, and platform features**. The June 24, 2026 revision prioritizes official primary-source status over speculative launch claims; availability, pricing, quotas, and experiments remain subject to change._
