# GPT Image 2 to Seedance product-video workflow

Separate product-image preparation from motion generation. This helps when a video model needs a clean, consistent first frame before it can produce convincing movement.

**Pipeline:** product brief → approved keyframe → motion prompt → short video → narration and localization.

## 1. Lock the product brief

```text
Product:
Audience:
Single benefit:
Required product details:
Details that must not change:
Setting and camera framing:
Aspect ratio:
Final call to action:
```

## 2. Generate the keyframe

```text
Create a production-ready first frame for a [DURATION]-second product video.

Product: [PRODUCT]
Composition: [SHOT SIZE, ANGLE, SUBJECT POSITION]
Environment: [SETTING]
Lighting: [DIRECTION AND QUALITY]
Brand constraints: [COLORS, MATERIALS, LOGO RULES]
Motion space: leave clear space toward [DIRECTION] for [ACTION].

Preserve the exact product shape, controls, proportions, label placement,
materials, and color. Do not add text, accessories, duplicate products,
hands, reflections, or packaging unless specified.
```

Approve product fidelity before continuing. Do not try to repair an incorrect product only through a motion prompt.

## 3. Animate with Seedance

```text
Use the supplied image as the identity and composition anchor.

0–3 seconds: [OPENING ACTION AND CAMERA]
3–7 seconds: [PRODUCT BENEFIT DEMONSTRATION]
7–10 seconds: [FINAL REVEAL AND CLEAN END FRAME]

Keep geometry, materials, label position, and color unchanged. Use
physically believable motion and one continuous visual idea. No extra
objects, text, logo mutations, duplicate products, identity drift,
sudden cuts, or unexplained camera jumps.
```

Start with one short shot. Add shots only after the product remains stable.

## 4. Add explanation and localization

Add narration only after the visual result is approved. Keep product claims grounded in the approved brief. Leadde can be used for the structured narration, presenter, caption, and multilingual stage: [create a business video](https://leadde.ai/?utm_source=github&utm_medium=workflow&utm_campaign=image-to-seedance).

Record the exact model/version, date, input image, prompt, duration, aspect ratio, output, and correction prompt. A dated record is more useful than an undocumented claim of quality.

