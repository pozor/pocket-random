# Randomix Accessibility Statement

Randomix is committed to ensuring digital accessibility for all users, including those with disabilities. This document outlines our accessibility features and compliance standards.

---

## 🎯 Compliance Standards

Randomix is designed to meet **WCAG 2.1 Level AA** (Web Content Accessibility Guidelines) standards, achieving a **10/10 accessibility score**.

### Standards Met:
- **WCAG 2.1 Level AA** - Web Content Accessibility Guidelines
- **iOS Accessibility Guidelines** - Apple's accessibility best practices
- **Section 508** - U.S. federal accessibility requirements (where applicable)

---

## ♿ Assistive Technologies Supported

Randomix is fully compatible with:

### Screen Readers
- **VoiceOver** (iOS) - Complete support with semantic labels
- All UI elements properly announced with context
- Navigation hints and gestures supported
- Results and history readable in context

### Visual Accessibility
- **Dynamic Type** - Respects iOS text size preferences
- **High Contrast** - All themes meet 4.5:1 minimum contrast ratio
- **Color Independence** - Information never conveyed by color alone
- **Bold Text** - Supports iOS bold text setting

### Motor Accessibility
- **Touch Targets** - Minimum 48×48px for all interactive elements
- **Reduced Motion** - Respects iOS reduced motion preferences
  - Disables shake-to-generate when enabled
  - Removes animated snow effects (Christmas theme)
  - Reduces UI animations
- **Motion Actuation (WCAG 2.5.4)** - Shake-to-generate is optional with UI alternative

### Cognitive Accessibility
- **Clear Language** - Simple, direct instructions
- **Consistent Navigation** - Tab-based structure with help on every screen
- **Error Prevention** - Validation with clear error messages
- **Undo Support** - History allows reviewing past results

---

## 🌟 Key Accessibility Features

### Universal Design
- **6 Languages**: English, Italian, French, German, Spanish, Portuguese (225+ translations)
- **4 Themes**: White, Dark, Modern, Christmas (all with proper contrast)
- **Offline-First**: No internet required, works anywhere

### Per-Screen Accessibility

#### Number Generator
- VoiceOver announces current range and settings
- Generated numbers announced immediately
- History items include timestamps and values
- Clear labels for all controls

#### Phrase Generator
- Each phrase in list announced with weight and probability
- CRUD operations fully accessible via VoiceOver
- Swipe actions announced clearly
- Results announced with context

#### Distribution Generator
- Distribution selector fully navigable
- Parameter inputs with clear labels and hints
- Statistics announced after generation
- Histogram data accessible (values read in history)

#### Settings
- All preferences accessible and announced
- Theme previews described
- Language changes reflected immediately

---

## 🐛 Reporting Accessibility Issues

Accessibility is a priority. If you encounter any barriers:

### How to Report
**[Report Accessibility Issue →](https://github.com/pozor/randomix/issues/new?template=bug_report.md)**

Please include:
- **Assistive Technology**: VoiceOver version, iOS version
- **Issue Description**: What doesn't work as expected
- **Screen/Feature**: Where the issue occurs
- **Steps to Reproduce**: How to encounter the issue
- **Expected Behavior**: What should happen

### Response Time
- Accessibility issues are **high priority**
- Target response: **24-48 hours**
- Target fix: **Next minor release** (or hotfix if critical)

---

## 📱 System Requirements

**Minimum for Accessibility Features:**
- iOS 13.4 or later (VoiceOver basic support)
- iOS 16.0 or later recommended (enhanced accessibility features)

**Supported Devices:**
- iPhone (all models supporting iOS 13.4+)
- iPad (all models supporting iOS 13.4+)
- iPod touch (7th generation or later)

---

## 🔄 Continuous Improvement

### Commitment
- Regular accessibility audits with each release
- User feedback drives improvements
- Testing with real assistive technology users
- Staying current with WCAG updates

### Recent Improvements (v1.0.0)
- ✅ Full VoiceOver semantic labels added
- ✅ Touch target sizes increased to 48×48px minimum
- ✅ Reduced motion support for shake gesture
- ✅ Color contrast ratios verified across all themes
- ✅ Dynamic Type support implemented
- ✅ 225+ accessibility strings translated

### Planned Enhancements
- Voice Control optimization
- Additional contrast themes (high contrast mode)
- Accessibility quick actions
- Enhanced haptic feedback options

---

## 📚 Resources

### Learn More About Accessibility
- [Apple Accessibility](https://www.apple.com/accessibility/)
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [iOS VoiceOver Guide](https://support.apple.com/guide/iphone/voiceover-iph3e2e415f)

### Randomix Documentation
- [Support](SUPPORT.md) - General help
- [FAQ](FAQ.md) - Common questions
- [Privacy Policy](PRIVACY_POLICY.md) - Data handling

---

## 📧 Contact

For accessibility-specific inquiries:

**GitHub:** [Open an Issue](https://github.com/pozor/randomix/issues)
**Email:** dev@brunettospinelli.it

---

## 🙏 Thank You

Thank you for helping make Randomix accessible to everyone. Your feedback makes the app better for all users.

---

**Last Updated:** November 2025
**App Version:** 1.0.0
**WCAG Level:** AA (2.1)

© 2025 Randomix. All rights reserved.
