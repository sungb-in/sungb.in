# [네이버 강연] Jetpack Compose A to Z 

AOSP 코드 모음

---

# UI

### LookaheadLayout

- [LookaheadLayout](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/ui/ui/src/commonMain/kotlin/androidx/compose/ui/layout/LookaheadLayout.kt;l=39-98)
- [LookaheadLayoutScope](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/ui/ui/src/commonMain/kotlin/androidx/compose/ui/layout/LookaheadLayout.kt;l=100-148)
- [LookaheadLayoutCoordinates](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/ui/ui/src/commonMain/kotlin/androidx/compose/ui/layout/LookaheadLayoutCoordinates.kt;l=30-46)
- [LayoutCoordinates](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/ui/ui/src/commonMain/kotlin/androidx/compose/ui/layout/LayoutCoordinates.kt;l=25-100)

### Animation

- [animateColorAsState](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/SingleValueAnimation.kt;l=35-67)
- [spring](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation-core/src/commonMain/kotlin/androidx/compose/animation/core/AnimationSpec.kt;l=524-539)
- [tween](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation-core/src/commonMain/kotlin/androidx/compose/animation/core/AnimationSpec.kt;l=510-522)
- [easing](https://cs.android.com/androidx/platform/tools/dokka-devsite-plugin/+/master:testData/compose/source/androidx/compose/animation/core/Easing.kt)
- [keyframes](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation-core/src/commonMain/kotlin/androidx/compose/animation/core/AnimationSpec.kt;l=392-508)
- [repeatable](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation-core/src/commonMain/kotlin/androidx/compose/animation/core/AnimationSpec.kt;l=554-582)
- [infiniteRepeatable](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation-core/src/commonMain/kotlin/androidx/compose/animation/core/AnimationSpec.kt;l=596-619)
- [snap](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation-core/src/commonMain/kotlin/androidx/compose/animation/core/AnimationSpec.kt;l=632-638)
- [AnimatedContent](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/AnimatedContent.kt;l=70-137)
- [ContentTransform](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/AnimatedContent.kt;l=139-199)
- [EnterTransition](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/EnterExitTransition.kt;l=67-137)
- [ExitTransition](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/EnterExitTransition.kt;l=139-213)
- [SizeTransform](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/AnimatedContent.kt;l=215-235)
- [AnimatedContentScope](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/AnimatedContent.kt;l=262-523)
- [with](https://cs.android.com/androidx/platform/frameworks/support/+/androidx-main:compose/animation/animation/src/commonMain/kotlin/androidx/compose/animation/AnimatedContent.kt;l=252-260)