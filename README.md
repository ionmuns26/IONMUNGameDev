# The Seven Gates of Kyoto — Source Code

## Tech Stack
React + Vite + Tailwind CSS + shadcn/ui + framer-motion

## File Structure
### Core
- src/App.jsx                                       App router & auth wrapper
- src/main.jsx                                      Entry point
- src/index.css                                     Design tokens, fonts, CSS animations
- tailwind.config.js                                Tailwind theme config

### Pages
- src/pages/Home.jsx                                Main page & landing view
- src/pages/Login.jsx                               Login page
- src/pages/Register.jsx                            Register page
- src/pages/ForgotPassword.jsx                      Forgot password page
- src/pages/ResetPassword.jsx                       Reset password page
- src/pages/Download.jsx                            This download page

### Lib
- src/lib/gateData.js                               All 6 gate puzzles & final code
- src/lib/gateLockout.js                            24h lockout logic
- src/lib/AuthContext.jsx                           Auth context & provider
- src/lib/utils.js                                  Utility functions

### Game Components
- src/components/game/GateMap.jsx                   Gate selection map
- src/components/game/GateChallenge.jsx             Puzzle challenge screen
- src/components/game/FinalGate.jsx                 Final gate & victory screen
- src/components/game/minigames/RunnerGame.jsx       Runner minigame
- src/components/game/minigames/InvestigationGame.jsx Investigation minigame
- src/components/game/minigames/ChoiceGame.jsx       Choice minigame
- src/components/game/minigames/SequenceGame.jsx     Sequence minigame
- src/components/game/minigames/CipherGame.jsx       Cipher minigame

### Effects
- src/components/effects/SakuraPetals.jsx           Falling sakura animation
- src/components/effects/FogEffect.jsx              Drifting fog layer
- src/components/effects/DragonBackground.jsx       Ink-wash landscape SVG
- src/components/effects/InkWashTexture.jsx         Paper/parchment texture
- src/components/effects/BackgroundSlider.jsx       Background image slider

## Dependencies
- framer-motion
- lucide-react
- @tanstack/react-query
- react-router-dom
- jszip
