# Photoshop Practical — Photo Enhancement (Before & After)

**Name:** Drishti
**Course:** BCA
**Software:** Adobe Photoshop

---

## Objective

To improve a hazy, flat landscape photograph using Photoshop's **adjustment layers, masks and filters**, and to present the result as a side-by-side **Before / After** comparison.

## About the Image

A person with a black backpack sits on a rock above a calm lake, looking toward forested mountains with snow-capped peaks and a small lakeside town.

| | Before | After |
|---|---|---|
| **Sky** | Pale, grey-white and washed out | Deep blue with clear white clouds |
| **Mountains** | Hazy, low contrast, bluish-grey | Sharp and detailed, rich shadows |
| **Forest** | Dull, muted green | Vivid, healthy green |
| **Lake** | Dark grey-green, flat | Bright turquoise with clear reflections |
| **Overall mood** | Cloudy and flat | Bright, clear and vibrant |

## Adjustments That Produce This Look

1. **Camera Raw Filter** (`Filter > Camera Raw Filter`): lift *Exposure* slightly, raise *Contrast*, reduce *Highlights*, lift *Shadows*, and add some *Dehaze* to cut through the mist over the mountains.
2. **Curves** (adjustment layer): a gentle S-curve to deepen shadows and brighten highlights.
3. **Levels** (adjustment layer): set the black and white points so the histogram uses the full tonal range.
4. **Vibrance / Hue-Saturation** (adjustment layers): boost the blues and greens. Use Vibrance first because it protects skin and already-saturated colours.
5. **Selective Color or Color Balance:** push the water towards teal and the foliage towards a fresher green.
6. **Layer masks:** paint on each adjustment layer's mask so the sky, mountains and water can be enhanced separately without affecting the person.
7. **Sharpening:** `Filter > Sharpen > Smart Sharpen` (or *Unsharp Mask*) on a merged copy for crisp mountain and building detail.

## Steps to Recreate

1. **Open the photo:** `File > Open`, then duplicate the Background layer (`Ctrl/Cmd + J`) so the original stays untouched.
2. **Convert to a Smart Object:** right-click the layer, then *Convert to Smart Object*, so filters stay editable.
3. **Apply Camera Raw Filter:** adjust exposure, contrast, highlights, shadows and dehaze.
4. **Add adjustment layers:** Curves, Levels and Vibrance / Hue-Saturation from the Layers panel.
5. **Mask the sky:** use *Select > Sky* (or the Quick Selection Tool), then apply the selection as a mask on a Hue-Saturation layer to deepen the blue.
6. **Protect the subject:** on the adjustment layers, paint black on the mask over the person so she keeps natural tones.
7. **Fine-tune colours:** use Selective Color for the water and forest.
8. **Sharpen:** stamp a merged layer (`Ctrl/Cmd + Alt + Shift + E`) and apply Smart Sharpen.
9. **Build the comparison:**
   - Create a new document wide enough for two photos.
   - Place the original on the left and the edited version on the right.
   - Add the labels "Before" and "After" with the Type Tool, using a handwritten-style font.
   - Keep a white background and equal spacing so the comparison looks fair.
10. **Save and export:**
    - `File > Save As` → `.psd` to keep all layers.
    - `File > Export > Export As` → `.jpg` or `.png` for submission.

## Suggested Layer Structure

```
Label - After              (Type)
Label - Before             (Type)
Sharpen (merged)           (Stamped layer)
Selective Color            (Adjustment)
Vibrance / Hue-Saturation  (Adjustment, masked)
Levels                     (Adjustment)
Curves                     (Adjustment)
Camera Raw Filter          (Smart Filter)
Photo (edited)             (Smart Object)
Photo (original)           (Reference copy)
Background                 (White fill)
```

## Learning Outcomes

- Learned the difference between destructive edits and **non-destructive editing** with adjustment layers and Smart Objects.
- Understood how **Curves, Levels and Vibrance** change tone and colour.
- Practised **layer masks** to apply an edit only to chosen parts of the picture.
- Learned how to reduce haze and bring out detail in landscape photos.
- Practised presenting a **Before / After** comparison clearly.

## Files

| File | Description |
|---|---|
| `before_after.psd` | Layered Photoshop source file |
| `before_after.jpg` | Exported comparison image |
| `README.md` | This document |

---

*Submitted by Drishti, BCA — Photoshop Practical*
