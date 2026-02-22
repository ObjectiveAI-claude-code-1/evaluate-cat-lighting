# evaluate-cat-lighting

A specialized ObjectiveAI function that evaluates the quality and effectiveness of lighting in cat photographs.

## Overview

`evaluate-cat-lighting` is designed to assess how well a photographer has used light as an artistic tool to reveal, honor, and celebrate cats as photographic subjects. Rather than measuring technical exposure metrics, this function evaluates the artistic and practical dimensions of lighting through the lens of professional photography principles.

## Input

The function accepts a photograph containing a cat:

- **url** (required): The URL of a cat photograph to evaluate
- **photographer** (optional): The name of the photographer
- **title** (optional): The title of the photograph

## Output

The function returns a scalar score between **0 and 1**, where:

- **0.0 - 0.3**: Poor lighting quality that fails to honor the cat or create visual appeal
- **0.3 - 0.6**: Adequate lighting that is technically sound but lacks distinction or artistry
- **0.6 - 0.8**: Good lighting that effectively reveals the cat and creates visual interest
- **0.8 - 1.0**: Exceptional lighting that creates a compelling, memorable photograph

## What the Function Evaluates

The function assesses lighting quality through four interconnected dimensions:

### 1. Detail and Texture Revelation
Does the lighting effectively expose the intricate beauty of the cat itself? Superior lighting illuminates:
- Fur texture and pattern variation
- Fine details like whiskers and facial features
- Color gradations across the coat
- The subtle characteristics that make each cat unique

Poor lighting results in obscured details, blown-out highlights, or lost shadow detail that prevents full appreciation of the subject.

### 2. Light Source Character and Modeling
How intentionally and effectively is light being used to shape the cat's appearance? This evaluates:
- Direction of the light source (front, side, back, diffuse)
- Intensity and quality (harsh vs. soft, directional vs. diffuse)
- How well the light creates flattering shadows that define facial features and body contours
- Whether the lighting avoids harsh overexposure and underexposure
- Overall modeling that creates visual interest and dimensionality

Exceptional lighting demonstrates deliberate control, creating depth and form rather than flat illumination.

### 3. Visual Depth and Subject Separation
Does the lighting create a compelling three-dimensional presence? This assessment includes:
- Whether the cat appears solid and rounded rather than flat
- The interplay of highlights and shadows that create modeling and dimension
- Visual separation of the cat from its background
- Whether the cat naturally stands out as the primary subject
- How light delineates the cat's outline from surrounding elements

Superior lighting creates clear visual distinction, making the cat's form appear present and tactile.

### 4. Emotional Impact and Viewer Resonance
What emotional response does the lighting create? This evaluates:
- Whether the lighting draws the viewer in and invites engagement
- If viewers feel compelled to linger with the photograph
- The mood created—whether the lighting makes the cat feel approachable, majestic, serene, or other intended qualities
- Overall viewer appreciation and desire to return to the image
- Emotional authenticity that transcends technical considerations

Great lighting photography makes viewers want to see more and develops a genuine appreciation for the subject.

## Use Cases

### Professional Photography
Photographers use this function to evaluate and improve their work, understand which of their photos best demonstrate mastery of lighting principles, and make informed decisions about portfolio selection.

### Art Direction & Curation
Art directors selecting images for publication, exhibitions, or collections rely on this assessment to ensure chosen photos will resonate with audiences and showcase superior photographic craft.

### Photography Education
Educators use this function to provide constructive feedback to students learning to see light as a fundamental element of visual composition and to discuss professional-level lighting techniques.

### Personal Collections
Photography enthusiasts curating personal collections can identify which photos best capture the essential nature of their feline companions through superior lighting.

### Image Assessment & Comparison
Photographers can compare multiple photographs of the same subject to determine which lighting approach is most effective and compelling.

## How It Works

The function employs four vector completion tasks that prompt advanced language models to evaluate the photograph across each dimension. Each task presents the image to the model along with a natural prompt about a specific aspect of lighting quality. The model selects from three response options representing different quality levels (poor, moderate, excellent), and the function aggregates these evaluations into a final comprehensive score.

## Philosophy

`evaluate-cat-lighting` embodies the philosophy that **lighting is the fundamental language of visual communication in photography**. Good lighting is not merely the absence of darkness or presence of brightness—it is the thoughtful manipulation of light and shadow to tell the story of the subject in the most compelling way possible. By making professional lighting evaluation accessible and systematic, this function celebrates the art of seeing, the craft of photography, and the inherent beauty of cats as photographic subjects.