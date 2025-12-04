# Test Cases – YouTube Web (Desktop)

## TC-001 – Open YouTube Home Page
**Steps**
1. Open Chrome
2. Navigate to https://www.youtube.com
**Expected Result**
Home page loads with logo, sidebar, search bar, and video thumbnails.

---

## TC-002 – Basic Search Functionality
**Steps**
1. Type “lofi hip hop” in the search bar
2. Press Enter
**Expected Result**
Relevant search results appear.

---

## TC-003 – Empty Search Input
**Steps**
1. Click the search bar
2. Leave it empty
3. Press Enter
**Expected Result**
Page remains stable; no errors or navigation changes.

---

## TC-004 – Play a Video
**Steps**
1. Select a video from the results
**Expected Result**
Video loads and begins playing.

---

## TC-005 – Pause and Resume
**Steps**
1. Play a video
2. Click the Pause button
3. Click the Play button
**Expected Result**
Video pauses and resumes normally.

---

## TC-006 – Seek Functionality
**Steps**
1. While playing, click a later timestamp on the progress bar
**Expected Result**
Playback jumps smoothly to the new time.

---

## TC-007 – Volume Control
**Steps**
1. Hover over volume icon
2. Set volume to 0
3. Set volume back to max
**Expected Result**
Volume mutes and increases correctly.

---

## TC-008 – Fullscreen Mode
**Steps**
1. Click the Fullscreen icon
2. Press Esc
**Expected Result**
Fullscreen toggles on/off without issues.

---

## TC-009 – Navigate to Channel
**Steps**
1. On a video page, click the channel name
**Expected Result**
Channel page loads with banner, videos, and navigation tabs.

---

## TC-010 – Sidebar Navigation
**Steps**
1. On home page, click “Shorts” or “Subscriptions”
**Expected Result**
Correct section loads with appropriate content.

---

## TC-011 – Window Resize (Responsive UI)
**Steps**
1. Resize browser window to narrow width
**Expected Result**
UI adjusts without overlapping or broken elements.

---

## TC-012 – Invalid Search Input
**Steps**
1. Search for “asdlkjasdlj12312”
**Expected Result**
YouTube shows “No results” or limited fallback content; no errors.
