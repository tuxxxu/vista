# VISTA

VISTA provides an open standard of prompts intended for AI image generation. It aims to create consistency, organization, and interoperability in the construction of visual scenes, facilitating the creation, sharing, and reuse of prompts.

The objective is to enable creators and developers to use a common and structured language to describe scenes.
This ensures that different image generation engines can interpret and reproduce the creator's intentions more faithfully.

### Groups and attributes
##### Info: General information about the prompt, such as the name and description of the scene.

| Attribute  | Description                    | Type   | Example                    |
|-----------|-------------|------|---------|
| name       | Name of the prompt or scene    | String | "Cinematic Street Stillness" |
| description| Detailed description of the scene | String | "Urban scene with a nostalgic atmosphere" |

---

##### Camera: Defines the technical capture settings of the scene.

| Attribute     | Description               | Type   | Example           |
|-----------|-------------|------|---------|
| model         | Type of camera            | String | "analog 35mm film" |
| lens_type     | Type of lens              | String | "wide-angle"      |
| focal_length  | Focal length of the lens  | Number | 35                |
| fstop         | Lens aperture             | Number | 1.8               |
| iso           | ISO sensitivity           | Number | 400               |
| shutter_speed | Shutter speed             | String | "1/60"            |
| aspect_ratio  | Image aspect ratio        | String | "4:3"             |

---

##### Style: Defines the aesthetics and creative references of the scene.

| Attribute  | Description                     | Type   | Example                   |
|-----------|-------------|------|---------|
| palette    | Color palette used              | String | "muted cinematic tones"   |
| lut        | Lookup Table for color grading  | String | "film stock LUT"          |
| year       | Year or era of aesthetic reference | Number | 1995                    |
| aesthetic  | Aesthetic or creative reference | String | "street photography style"|
| engine     | Engine/AI used for generation   | String | "Stable Diffusion"        |

---

##### Environment: Defines the environment where the scene takes place.

| Attribute  | Description                 | Type    | Example                 |
|-----------|-------------|------|---------|
| location   | Location or setting         | String  | "brick city sidewalk"    |
| outdoor    | Outdoor environment?        | Boolean | true                    |
| timeofday  | Time of day                | String  | "dusk"                  |
| weather    | Weather condition          | String  | "clear evening"         |
| setting    | Type of environment        | String  | "urban crowded atmosphere"|

---

##### Lighting: Lighting settings in the scene.

| Attribute   | Description                | Type   | Example       |
|-----------|-------------|------|---------|
| type        | Type of lighting           | String | "natural"     |
| direction   | Direction of light         | String | "side light"  |
| intensity   | Light intensity            | Number | 75            |
| temperature | Color temperature (K)      | Number | 3200          |
| color       | Color of the light         | String | "warm yellow" |
| softness    | Softness of the light      | String | "soft"        |
| contrast    | Contrast of the scene      | String | "high contrast"|
| shadows     | Description of shadows     | String | "moody shadows"|

---

##### Character: Information about characters.

| Attribute  | Description                | Type   | Example           |
|-----------|-------------|------|---------|
| pose       | Body position              | String | "standing still"  |
| expression | Facial expression          | String | "serious"         |
| clothing   | Clothing                   | String | "casual jacket"   |
| makeup     | Makeup                    | String | "natural look"    |
| hairstyle  | Hairstyle                  | String | "short messy hair"|

---

##### Composition: Organization and framing of the scene.

| Attribute     | Description                | Type    | Example              |
|-----------|-------------|------|---------|
| framing       | Type of framing            | String  | "overhead shot"      |
| perspective   | Camera perspective         | String  | "cinematic perspective"|
| focal_point   | Focal point of the scene   | String  | "one subject"        |
| rule_of_thirds| Use of the rule of thirds  | Boolean | true                |
| motion_blur   | Motion blur                | String  | "crowd rushing past" |

---

##### Effects: Visual effects applied to the scene.

| Attribute    | Description                   | Type   | Example                 |
|-----------|-------------|------|---------|
| color_grade  | Color grading style           | String | "moody cinematic tones" |
| grain        | Film grain intensity          | Number | 30                      |
| vignette     | Vignette intensity            | Number | 20                      |
| glow         | Glow intensity                | Number | 10                      |
| reflection   | Extra reflections             | String | "streetlight reflection"|
| lens_flare   | Lens flare                   | String | "subtle lens flare"     |
| dust         | Dust particles               | String | "light dust in air"     |
| fog          | Fog/smoke                    | String | "thin fog"              |
| light_leak   | Light leak                   | String | "subtle light leak"     |