# MacBook Air Streaming Setup Guide

## Hardware Requirements & Limitations

### MacBook Air Considerations
- **CPU**: M1/M2 handles streaming well, Intel may struggle with simultaneous encoding
- **RAM**: 8GB minimum for streaming + browser tabs, 16GB recommended
- **Storage**: Ensure 20GB+ free space for recordings
- **Thermal**: Monitor temperature, use cooling pad if available

### Webex Camera Setup
- **Camera**: Built-in FaceTime HD or external Webex/USB camera
- **Positioning**: Eye level, good lighting from front (not behind you)
- **Backup**: Phone as secondary camera via apps like EpocCam or Camo

## Software Setup

### 1. OBS Studio (Free - Recommended)
```bash
# Install OBS Studio
brew install --cask obs

# Install OBS plugins (optional but helpful)
brew install --cask obs-virtualcam
```

**OBS Configuration for MacBook Air**:
- **Resolution**: 1920x1080 (1080p)
- **Frame Rate**: 30 FPS (60 FPS if M1/M2 with good cooling)
- **Encoder**: Apple VT H264 Hardware Encoder (if available) or x264
- **Bitrate**: 6000 kbps for Twitch, 8000-10000 for YouTube
- **Audio**: 48kHz, 160 kbps

### 2. Alternative: Streamlabs Desktop
```bash
# Install Streamlabs
brew install --cask streamlabs-desktop
```

## Virtual vs In-Person Setup

### Option A: Both in Same Room
**Pros**: Natural interaction, easier technical setup
**Setup**:
- One MacBook Air as primary stream machine
- External monitor for tool demos
- Two microphones or shared USB microphone
- Wide-angle camera to capture both people

### Option B: Virtual Setup (Recommended for flexibility)
**Pros**: Each person controls their own audio/video, can share screens easily
**Setup**:
- **Primary streamer**: Runs OBS, manages stream
- **Co-host**: Joins via Zoom/Discord, shares screen when needed
- Use Discord/Zoom "Advanced" features to capture clean audio

## Detailed Setup Instructions

### 1. Install Required Software
```bash
# Core streaming software
brew install --cask obs
brew install --cask discord  # For co-host communication

# Utility apps
brew install --cask background-music  # Audio routing
brew install --cask loopback  # Advanced audio routing (paid)
brew install --cask cleanmymax  # Keep system performance up
```

### 2. OBS Scene Setup
Create these scenes in OBS:

#### Scene 1: "Intro/Outro"
- **Sources**: 
  - Camera (1920x1080, centered)
  - Text overlay with stream title
  - Background or logo

#### Scene 2: "Tool Demo Full Screen"
- **Sources**:
  - Window Capture (browser with tool)
  - Small camera overlay (bottom right, 320x240)

#### Scene 3: "Tool Demo with Co-host"
- **Sources**:
  - Window Capture (browser, 60% of screen)
  - Discord/Zoom window (remaining 40%)
  - Small camera overlay

#### Scene 4: "Discussion"
- **Sources**:
  - Camera (primary, 50% screen)
  - Discord/Zoom window (secondary, 50% screen)
  - Tool logo/info overlay

### 3. Audio Configuration

#### Single Person Setup
- **Microphone**: Built-in or USB microphone
- **Levels**: Peak around -12dB, never above -6dB
- **Filters**: Noise suppression, compressor, limiter

#### Virtual Co-host Setup
- **Discord setup**: 
  - Both join private Discord voice channel
  - Primary streamer captures Discord audio in OBS
  - Use "Stereo Mix" or Loopback for clean audio routing
- **Backup**: Record separate audio tracks for post-production

### 4. Internet & Performance Optimization

#### Internet Requirements
- **Upload speed**: Minimum 10 Mbps, recommended 20+ Mbps
- **Stability**: Use ethernet if possible, not WiFi
- **Backup**: Phone hotspot as backup internet

#### MacBook Air Performance Tips
```bash
# Close unnecessary apps
killall "Chrome Helper"
killall "Slack"
killall "Spotify"

# Monitor CPU usage
top -pid `pgrep obs`

# Free up RAM
sudo purge
```

### 5. Streaming Platform Setup

#### Twitch Configuration
1. Go to Twitch Creator Dashboard
2. Settings → Stream → Copy Stream Key
3. In OBS: Settings → Stream → Service: Twitch → Use Stream Key
4. Configure: Server (Auto), Stream Key (from Twitch)

#### YouTube Simultaneous Streaming (Optional)
- **Method 1**: Use Restream.io to broadcast to both platforms
- **Method 2**: Set up separate OBS profile for YouTube Live

## Troubleshooting Common Issues

### Performance Issues
- **High CPU**: Lower resolution to 720p, reduce frame rate to 24fps
- **Dropped frames**: Reduce bitrate to 4000 kbps
- **Overheating**: Use external cooling, close browser tabs
- **Audio sync**: Add audio delay in OBS (usually 200-500ms)

### Virtual Co-host Issues
- **Echo**: Use headphones, enable echo cancellation
- **Audio quality**: Have co-host use good microphone
- **Screen sharing**: Test beforehand, have backup recording method
- **Lag**: Allow extra time for communication delays

### Recording & Backup
```bash
# OBS Recording Settings
# Format: MP4
# Encoder: Same as stream
# Path: ~/Movies/Stream_Recordings/
```

## Pre-Stream Checklist

### 30 Minutes Before
- [ ] Close unnecessary applications
- [ ] Test internet speed (fast.com)
- [ ] Start OBS, verify all scenes work
- [ ] Test audio levels with co-host (if virtual)
- [ ] Check camera positioning and lighting
- [ ] Verify all tool websites are accessible

### 5 Minutes Before
- [ ] Start streaming to test (set as offline/unlisted)
- [ ] Final audio check
- [ ] Confirm co-host connection
- [ ] Load GitHub issues in browser tabs
- [ ] Set stream title and go live

### During Stream
- [ ] Monitor CPU/temperature in Activity Monitor
- [ ] Watch for dropped frames in OBS
- [ ] Keep water nearby (talking for hours is tiring)
- [ ] Have backup plan if primary Mac overheats

## Post-Stream Process

### Immediate (5 minutes)
- [ ] Stop recording and stream
- [ ] Save recording locally
- [ ] Export to YouTube (if using Twitch auto-export)
- [ ] Thank viewers on social media

### Within 24 Hours
- [ ] Upload edited version to YouTube
- [ ] Create highlights/clips
- [ ] Update GitHub issues with findings
- [ ] Plan next stream based on feedback

## Cost Breakdown

### Free Setup
- OBS Studio: Free
- Discord: Free
- Basic USB microphone: $30-50
- Total: Under $100

### Professional Setup
- OBS Studio: Free
- Loopback (audio routing): $99
- Good USB microphone: $100-200
- External camera: $100-300
- Lighting kit: $50-150
- Total: $350-750

## Emergency Backup Plans

### If MacBook Air Overheats/Fails
- Switch to phone streaming (Instagram Live, TikTok Live)
- Use co-host's machine as primary
- Reschedule and notify viewers immediately

### If Internet Fails
- Switch to phone hotspot
- Move to audio-only format temporarily
- Pivot to offline recording for later upload

### If Co-host Connection Fails
- Continue solo with pre-written notes
- Record co-host separately for post-production
- Use chat as replacement for co-host interaction