# Music Machine - App Design

## Overview
Music Machine is a comprehensive music player app with YouTube integration, MP3 conversion, advanced equalizer, AI stem separation, and custom visualizations.

## Screen List

1. **Home / Now Playing** - Primary playback screen with visualizer
2. **Library** - Local music files browser
3. **YouTube Search** - Search and browse YouTube music
4. **Equalizer** - 30-point EQ with presets
5. **Stem Controls** - Instrument/vocal silencer interface
6. **Visualizer Settings** - Configure 22 visualizations
7. **AI Stem Visualizer Settings** - Configure 8 AI stem visualizations
8. **Download Manager** - Track YouTube MP3 conversions
9. **Settings** - App preferences and about

## Primary Content and Functionality

### Home / Now Playing Screen
- **Header**: "Music Machine" title at top
- **Now Playing**: Album art (or visualization when playing local files)
- **Track Info**: Song name, artist, duration
- **Playback Controls**: Play/pause, next/prev, seek bar
- **Visualization**: 22 custom visualizations (local files only, not YouTube videos)
- **Quick Access Buttons**: Equalizer, Stem Controls, Settings
- **Footer**: "Created by Jeremy Earl" + "© 2026"

### Library Screen
- **File Browser**: List of local audio files (MP3, WAV, etc.)
- **Search/Filter**: Find tracks by name or artist
- **Playback**: Tap to play, long-press for options
- **Downloaded YouTube MP3s**: Show converted files

### YouTube Search Screen
- **Search Bar**: Query YouTube for music
- **Results Grid**: Video thumbnails with titles
- **Preview**: Tap to play YouTube video (no visualization)
- **Download Button**: Convert to MP3 and save locally
- **Download Progress**: Show conversion status

### Equalizer Screen
- **30-Point Slider**: Frequency range 1-999 Hz
- **Presets**: Bass Boost, Treble Boost, Flat, Custom
- **Real-time Adjustment**: Changes apply during playback
- **Works with**: Local files AND YouTube videos

### Stem Controls Screen
- **Drum Silencer**: Slider to remove/reduce drums
- **Guitar Silencer**: Slider to remove/reduce guitars
- **Synth Silencer**: Slider to remove/reduce synths
- **Vocal Silencer**: Slider to mute/reduce vocals
- **AI-Powered**: Uses stem separation AI
- **Real-time Preview**: Hear changes immediately

### Visualizer Settings Screen
- **22 Visualization Styles**: Waveform, spectrum, geometric, particle, etc.
- **Customization Options**: Color, intensity, speed, size
- **Preview**: Live preview of selected visualizer
- **Only for Local Files**: Visualizations don't show for YouTube videos

### AI Stem Visualizer Settings Screen
- **8 AI Visualizations**: Each reacts to specific instrument/vocal
  1. Drum Visualizer
  2. Bass Visualizer
  3. Guitar Visualizer
  4. Vocal Visualizer
  5. Synth Visualizer
  6. Piano Visualizer
  7. Strings Visualizer
  8. Percussion Visualizer
- **Customization**: Color, size, animation style per visualizer
- **Real-time Reaction**: Responds to detected instrument frequencies

### Download Manager Screen
- **Active Downloads**: Show progress bars
- **Completed Downloads**: List of converted MP3s
- **File Size**: Display download/file size
- **Actions**: Pause, resume, cancel, delete

### Settings Screen
- **About**: App version, creator info
- **Theme**: Light/dark mode
- **Audio Quality**: Bitrate for YouTube conversions
- **Permissions**: Manage storage/media permissions
- **Clear Cache**: Remove temporary files

## Key User Flows

### Flow 1: Play Local Music
1. User opens app → Home screen
2. Tap "Library" tab
3. Select audio file
4. Playback starts → Visualization displays
5. User can adjust EQ or stem controls in real-time

### Flow 2: Download YouTube Music
1. User opens app → Home screen
2. Tap "YouTube Search" tab
3. Search for song
4. Tap video → Preview plays (no visualization)
5. Tap "Download" → Conversion starts
6. Once complete → Appears in Library
7. Can now play with visualization

### Flow 3: Use Equalizer
1. During playback (local or YouTube)
2. Tap "Equalizer" button
3. Adjust 30-point slider
4. Changes apply in real-time
5. Save as preset (optional)

### Flow 4: Silence Instruments/Vocals
1. During local file playback
2. Tap "Stem Controls"
3. Adjust sliders for drums, guitar, synth, vocals
4. AI separates stems and applies silencing
5. Hear changes immediately

### Flow 5: Customize Visualizations
1. During local file playback
2. Tap "Visualizer Settings"
3. Choose from 22 visualizations
4. Adjust color, speed, intensity
5. Preview updates live
6. Save preference

## Color Choices

- **Primary**: Deep Purple (#6B46C1) - Modern, music-focused
- **Accent**: Cyan (#06B6D4) - Energetic, tech-forward
- **Background**: Dark Gray (#1A1A1A) - Reduces eye strain during music sessions
- **Surface**: Charcoal (#2D2D2D) - Card/button backgrounds
- **Text**: Off-White (#F5F5F5) - High contrast
- **Success**: Lime Green (#84CC16) - Download complete
- **Warning**: Amber (#F59E0B) - Processing/converting

## Layout Principles

- **Portrait Orientation**: All screens optimized for 9:16 aspect ratio
- **One-Handed Usage**: Key controls in lower half of screen
- **Large Touch Targets**: Buttons minimum 48px height
- **Minimal Scrolling**: Prioritize visible content
- **Bottom Tab Bar**: Quick access to main sections
- **Modal Sheets**: Settings/controls slide up from bottom
- **Haptic Feedback**: Subtle vibration on interactions
