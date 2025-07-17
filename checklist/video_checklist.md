# 📹 Checklist: Video Sending in Messenger

**Description:** Test checklist for video sending functionality in mobile messenger app (Telegram-like)

---

## ✅ Basic Tests for Sending Ready Video

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 1 | Send video by selecting from phone gallery | Video successfully sent |
| 2 | Send video file from device | Video successfully sent |
| 3 | Record and send video via chat button | Video recorded and sent |
| 4 | Preview video before sending | Video plays correctly |
| 5 | Add caption to video | Video sent with caption |
| 6 | Forward video from another chat | Video successfully forwarded |
| 7 | Send scheduled video message | Video sent according to scheduled time |

## 📱 Tests for Sending Video Both Through In-App Camera and Gallery

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 8 | Record video via chat button | Video recorded and sent |
| 9 | Trim/edit duration | Trimmed video sent with new duration |
| 10 | Send video with/without audio track | Video sent with/without audio |
| 11 | Use cancel button during recording | Recording interrupted, video not sent |
| 12 | Add cover to recorded video | Cover applied to video |
| 13 | Add caption to recorded video | Caption added to video |
| 14 | Change quality of video being sent | Video sent with smaller size |
| 15 | Crop video being sent | Video sent changed in dimensions after crop |
| 16 | Change orientation/angle of video when sending | Video sent with changed orientation |
| 17 | Make video mirrored before sending | Mirrored video sent |
| 18 | Check when editing video, changes to caption, duration and size | Resolution, duration and video size correctly displayed at top |

## ⭕ Sending Video via Circle

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 19 | Record short video via special button | Reel recorded and sent |
| 20 | Pause recording, resume | Recording paused, continues after pause |
| 21 | Switch camera (front/main) | Camera switches during recording |
| 22 | Enable screen lighting during recording | Screen illuminated for better lighting |
| 23 | Cancel sending circle | Recording cancelled, video not sent |
| 24 | Delete recorded circle | Recorded video deleted |

## 📚 Group Sending

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 25 | Send multiple videos as one album | Videos sent as group in one message |
| 26 | Send multiple videos as separate messages | Each video sent as separate message |
| 27 | Mixed sending (video + photo in group) | Media files sent as album |

## ⚠️ Interruption and Cancellation Tests

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 28 | Check pause button when sending video | Sending paused, then resumed |
| 29 | Cancel sending during upload | Sending cancelled, video not delivered |
| 30 | Cancel sending during upload and send again | New sending starts successfully, video delivered |
| 31 | Send scheduled video message | Video sent according to scheduled time |
| 32 | Interrupt sending with incoming call | Sending resumes after call ends |
| 33 | Interrupt sending with pop-up notifications from other apps | Sending continues in background |
| 34 | Interrupt sending by turning off phone | Sending resumes when turned on |
| 35 | Interrupt sending by internet loss | Sending resumes when connection restored |
| 36 | Sending with very slow internet | Video sent, but slowly |
| 37 | Switching between WiFi and mobile network during sending | Sending continues without interruption, after connection |

## 📼 Formats

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 38 | mp4 | Video successfully sent |
| 39 | avi | Video successfully sent |
| 40 | mov | Video successfully sent |
| 41 | mkv | Video successfully sent |
| 42 | webm | Video successfully sent |
| 43 | wmv | Video successfully sent |

## 📏 Limitations

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 44 | Send max size to regular user (2GB) | Video successfully sent |
| 45 | Send max size to VIP user (4GB) | Video successfully sent |
| 46 | Send more than 2GB to regular user | Error with offer to buy VIP or message about size limit exceeded |
| 47 | Send video exceeding maximum size | Error with message about size limit exceeded |
| 48 | Send very small size video | Video successfully sent |
| 49 | Send incorrect video format | Message about unsupported format |
| 50 | Delete file from phone during sending | Sending interrupted with corresponding notification |

## 🌐 Network Conditions

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 51 | Send via WiFi | Video successfully sent |
| 52 | Send via mobile network | Video successfully sent |
| 53 | Send with weak network signal | Video sent slowly but successfully |

## ✏️ Editing After Sending

| # | Test Case | Expected Result |
|---|-----------|----------------|
| 54 | Edit sent video | Video replaced with new one |
| 55 | Replace video with photo | Video replaced with photo |

---

**Created:** 2025  
**Version:** 1.0  
**Author:** Dmitrii Shokin  
**Platform:** Mobile (Android)  
**Total Test Cases:** 55