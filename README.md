# Félix Jeanrichard

Embedded systems engineer · PCB designer · hardware prototyper

Based in Switzerland. Electronics student at CPNE. Building hardware with a long-term product mindset.

<p align="left">
	<img src="https://img.shields.io/badge/Embedded%20Systems-111827?style=flat-square&labelColor=0f172a&color=94a3b8" alt="Embedded Systems" />
	<img src="https://img.shields.io/badge/PCB%20Design-111827?style=flat-square&labelColor=0f172a&color=94a3b8" alt="PCB Design" />
	<img src="https://img.shields.io/badge/RF%20Systems-111827?style=flat-square&labelColor=0f172a&color=94a3b8" alt="RF Systems" />
	<img src="https://img.shields.io/badge/Prototyping-111827?style=flat-square&labelColor=0f172a&color=94a3b8" alt="Prototyping" />
</p>

---

## About

I am a young electronics student at CPNE in Switzerland, and I have been interested in electronics since I was very young.

I build embedded products that sit at the intersection of electronics, firmware, mechanics, and industrial design.

My work is centered on systems that have to feel coherent as products, not just function as prototypes. That means careful PCB design, deliberate firmware architecture, practical enclosure thinking, and rapid iteration.

Outside the bench, I fly FPV drones, do orienteering, and stay close to hands-on technical work. Those interests shape how I think about control, timing, precision, and field-tested design.

## Background

- Electronics student at CPNE
- Based in Switzerland
- Interested in electronics from a young age
- FPV drone pilot
- Orienteering enthusiast
- Focused on practical, real-world engineering

## Technical interests

- Embedded electronics and low-level firmware
- PCB architecture and board bring-up
- Microcontrollers and real-time control
- IoT and wireless communication systems
- RF links, synchronization, and low-power design
- 3D design, prototyping, and mechanical integration
- Product-oriented hardware development

## Stack

| Layer | Tools and technologies |
| --- | --- |
| Firmware | C++, C, PlatformIO |
| Hardware | ESP32, STM32, embedded peripherals, custom PCB design |
| EDA | Altium Designer |
| Mechanical | Onshape, 3D design, prototyping |
| Systems | IoT, RF communication, distributed embedded nodes |

## Featured projects

### OrbitDeck

A modular productivity and control device designed as a serious hardware product.

- Hall effect 3D mouse input
- Stream Deck-style programmable shortcut buttons
- Custom firmware and embedded electronics
- Custom PCB design
- Product-focused industrial design

### Virtual Pacer System

A wireless pacing platform for athletics tracks built around distributed embedded nodes.

- RF mesh communication
- Synchronized pacing lights
- Real-time wireless timing
- Low-power electronics
- Scalable communication architecture

## Engineering journey

Hardware work for me has followed a clear progression:

1. Learn the constraints of circuits, firmware, and debugging.
2. Build prototypes that prove the system, not just the idea.
3. Integrate electronics, mechanics, and interaction into a single product.
4. Treat every project as a foundation for something manufacturable and maintainable.

That progression is still the core of how I work: measured, technical, and product-aware.

## Current focus

- Refining embedded product architecture
- Building cleaner PCB and firmware pipelines
- Designing stronger RF and low-power systems
- Improving enclosure and mechanical integration
- Documenting projects in a more rigorous engineering format
- Developing a technical portfolio that reflects real product work

## GitHub stats

## Gallery — Selected board renders & prototypes

Below are cleaned, captioned images that illustrate typical work: PCB layouts, rendered board views, and a prototype photo. Replace the placeholders in `assets/renders` and `assets/photos` with your optimized images.

<p align="center">
	<img src="assets/renders/orbitdeck_top_render.png" alt="OrbitDeck top render" width="760" style="margin:8px; border-radius:6px; box-shadow: 0 6px 18px rgba(0,0,0,0.25);" />
</p>

**OrbitDeck — system view**: top render showing controller area, button array, and major RF/clock routing.

<p align="center">
	<img src="assets/renders/virtualpacer_pcb_01.png" alt="Virtual Pacer board layout" width="640" style="margin:8px; border-radius:6px; box-shadow: 0 6px 18px rgba(0,0,0,0.20);" />
	<img src="assets/renders/power_stage_detail.png" alt="Power stage detail" width="320" style="margin:8px; border-radius:6px; box-shadow: 0 6px 18px rgba(0,0,0,0.20);" />
</p>

**Virtual Pacer System — PCB and power stage**: dense routing, connector arrays, and power conversion section.

<p align="center">
	<img src="assets/photos/prototype_photo_01.jpg" alt="Prototype assembled board" width="760" style="margin:8px; border-radius:6px; box-shadow: 0 6px 18px rgba(0,0,0,0.18);" />
</p>

**Prototype — assembled board**: real-world photo of a prototype used during bring-up and testing.

Suggested filenames and captions (place under `assets/renders/` and `assets/photos/`):

- `orbitdeck_top_render.png` — orbit deck top render (1200px wide for hero)
- `virtualpacer_pcb_01.png` — virtual pacer PCB layout
- `power_stage_detail.png` — close-up of power stage and converters
- `prototype_photo_01.jpg` — prototype PCB assembled photo (keep as JPG)

Image export recommendations (quick commands):

1. Hero renders (PNG, lossless, 1200px wide):

```
magick input.png -resize 1200x -strip -colorspace sRGB -unsharp 0x0.5 -quality 95 orbitdeck_top_render.png
```

2. Detailed renders (PNG, 800–1000px wide):

```
magick input.png -resize 900x -strip -colorspace sRGB -contrast -unsharp 0x0.5 virtualpacer_pcb_01.png
```

3. Prototype photos (JPG, 1200px on longest edge, mild contrast/crop):

```
magick photo.jpg -resize 1200x -strip -auto-orient -sharpen 0x0.8 -quality 88 prototype_photo_01.jpg
```

Why these steps: PNG preserves render detail and vector-like edges; JPG is fine for workbench photos. Use slight unsharp/contrast to make traces and labels readable at small sizes.

If you want, I can:

- generate a hero image layout and add it to the repo (I will need the original high-res images uploaded),
- generate thumbnails for each image and update the README with linked lightbox HTML,
- or create a dedicated `docs/gallery.md` with higher-resolution embedded images for project pages.

<table>
	<tr>
		<td>
			<img src="https://github-readme-stats.vercel.app/api?username=Felix-JRDB&show_icons=true&hide_border=true&theme=github_dark&rank_icon=github" alt="GitHub stats" />
		</td>
		<td>
			<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Felix-JRDB&layout=compact&hide_border=true&theme=github_dark" alt="Top languages" />
		</td>
	</tr>
</table>

## Contact

Instagram : @felix.jrdb

Open to serious hardware collaboration, technical conversations, and sponsor discussions.
