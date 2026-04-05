[English](./README.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Deutsch](./README.de.md) | [Français](./README.fr.md) | [Türkçe](./README.tr.md) | [繁體中文](./README.zh-TW.md) | [简体中文](./README.zh-CN.md) | [Русский](./README.ru.md)

# 멋진 Seedance 2.0 프롬프트

[![Awesome](https://img.shields.io/badge/Awesome-Seedance%202.0%20Prompts-black?style=flat-square)](https://github.com/EvoLinkAI/awesome-seedance-2.0-prompts) [![GitHub stars](https://img.shields.io/github/stars/EvoLinkAI/awesome-seedance-2.0-prompts?style=flat-square)](https://github.com/EvoLinkAI/awesome-seedance-2.0-prompts/stargazers) [![Prompt count](https://img.shields.io/badge/prompts-125-blue?style=flat-square)](./README.md)

<p align="center">
  <img src="./public/banner.jpg" alt="Awesome Seedance 2.0 Prompts banner" width="100%" />
</p>

영화 같은 비디오 생성을 위한 고품질 Seedance 2.0 프롬프트를 엄선해 모은 컬렉션입니다. 공개 커뮤니티 게시물에서 정제하고, README 가독성을 위해 영어로 번역했으며, GitHub에서 빠르게 탐색할 수 있도록 구성했습니다.

언어: **한국어**

> 더 넓은 Seedance 2.0 생태계를 둘러보세요:
>
> API 문서 및 통합 레퍼런스: [`EvoLinkAI/Seedance-2.0-API`](https://github.com/EvoLinkAI/Seedance-2.0-API)
>
> OpenClaw 워크플로 통합: [`EvoLinkAI/seedance2-video-gen-skill-for-openclaw`](https://github.com/EvoLinkAI/seedance2-video-gen-skill-for-openclaw)
>
> 엔드투엔드 사용 가이드 및 예시: [`EvoLinkAI/awesome-seedance-2-guide`](https://github.com/EvoLinkAI/awesome-seedance-2-guide)

## 설명

이 저장소는 프롬프트에 대한 해설이 아니라 Seedance 2.0의 **실제로 사용할 수 있는 프롬프트**에 초점을 맞춥니다.


## 목차

- [통계](#통계)
- [관련 저장소](#관련-저장소)
- [이 저장소 사용 방법](#이-저장소-사용-방법)
- [추천 프롬프트](#추천-프롬프트)
- [프롬프트 카테고리](#프롬프트-카테고리)
  - [액션 / 판타지](#액션--판타지)
  - [영화적 리얼리즘](#영화적-리얼리즘)
  - [POV / FPV](#pov--fpv)
  - [상업 / 제품](#상업--제품)
  - [레퍼런스 기반](#레퍼런스-기반)
  - [초현실 / VFX](#초현실--vfx)
  - [템플릿 및 구조화 형식](#템플릿-및-구조화-형식)
  - [일반 시네마틱](#일반-시네마틱)
- [리소스](#리소스)
- [기여](#기여)
- [라이선스](#라이선스)
- [저작권 고지](#저작권-고지)

## 통계

| 지표 | 값 |
| --- | --- |
| 전체 프롬프트 | 125 |
| 원본 언어 수 | 4 |
| 최신 소스 날짜 | `05 Apr 2026` |

## 관련 저장소

- [`EvoLinkAI/Seedance-2.0-API`](https://github.com/EvoLinkAI/Seedance-2.0-API) - Seedance 2.0용 API 레퍼런스, 가격 맥락, 요청 예시, 통합 세부 정보를 제공합니다.
- [`EvoLinkAI/seedance2-video-gen-skill-for-openclaw`](https://github.com/EvoLinkAI/seedance2-video-gen-skill-for-openclaw) - 워크플로 자동화 안에서 Seedance 2.0 생성을 실행하기 위한 OpenClaw skill wrapper입니다.
- [`EvoLinkAI/awesome-seedance-2-guide`](https://github.com/EvoLinkAI/awesome-seedance-2-guide) - 단순 프롬프트를 넘어 기능, 기법, 사용 사례 설명까지 다루는 더 폭넓은 Seedance 2.0 가이드입니다.

## 이 저장소 사용 방법

1. 아래 카테고리 목록에서 시작해 자신의 사용 사례에 맞는 섹션을 여세요.
2. 프롬프트는 소재만이 아니라 카메라 로직, 타이밍, 환경 설계, 일관성 지침까지 기준으로 비교하세요.
3. 우선 구조를 재사용하세요. Seedance에서는 명사를 바꾸는 것보다 샷 전개와 모션 제어가 더 중요할 때가 많습니다.
4. `@image1` 또는 `<<<Image1>>>` 같은 프롬프트 내부 토큰이 의도된 문법의 일부라면 그대로 유지하세요.
5. 정리된 데이터셋 안에서는 제목, 카테고리, 소스 링크를 주요 탐색 앵커로 활용하세요.

## 추천 프롬프트

이 프롬프트들은 롱폼 변신, 감정적 리얼리즘, 상업용 스토리보드 작업, 구조화된 프롬프트 설계, 대형 스펙터클 액션 등 다양한 측면을 대표하도록 골랐습니다.

### 옥상 각성에서 F-14 변신까지
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
옥상 질주에서 자유낙하 포착, 자동차에서 제트기로의 변태로 점층적으로 확장되는 롱폼 변신 시퀀스입니다.

출처: [게시물](https://x.com/john87445528/status/2039496153641660508) · 게시일: 02 Apr 2026

```text
Chapter 1 (0-15 seconds): Rooftop Awakening · Running and Leaping Down (Front to Back View). Style: rugged primitive realism using a 35mm handheld film camera, with natural grain and subtle shake. The dazzling direct sunlight of Chongqing noon creates high-contrast shadows and lens flares. Camera: a single continuous third-person handheld follow shot with no cuts, starting from a low front angle and smoothly transitioning to an over-the-shoulder / back view, following the protagonist Image 1 throughout. Atmosphere: high-altitude winds howl, dust and mist fly, and cloth, hair, and mechanical parts all show realistic physical motion. Sound effects: metallic echoes of mechanical high heels striking concrete, heavy rhythmic breathing, howling wind, operating mechanical joints, violent fabric flapping, sudden silence at the instant of the leap, followed by a high-speed wind-cutting shriek during descent. [Visual Reference / Description]: fully preserve the elegant female character from the reference image, wearing a white suit, silver mechanical chest plate and neck collar, silver mechanical hands, and silver high-heeled boots, with long straight black ponytail, delicate facial features, and large earrings. Physical features and clothing details must remain fully consistent. The scene takes place on the rooftop of Raffles City Chongqing, surrounded by skyscrapers, with the broad Yangtze River visible in the distance. [Timeline per Second] 0-4s: [Front Start] The handheld camera captures her full body from a low front angle. She stands at the rooftop edge, looking directly into the camera with a calm, determined expression. The mechanical cervical spine catches the noon sunlight, and her ponytail lifts in the high wind. She slowly turns around. 4-9s: [Over-the-Shoulder Follow · Full Sprint] The camera switches to an over-the-shoulder perspective and follows closely. She sprints across the concrete platform. Her mechanical high heels spark against metal with each step. The hem of the suit and the mechanical spine exoskeleton whip violently in the airflow. Dust kicks up from the roof, and the cloth simulation stays highly realistic. 9-12s: [Leaping Down] She suddenly jumps off. The instant her feet leave the ground, the camera dips slightly and switches to a fast downward tracking view. Her suit billows violently in the extreme airflow. The glass curtain walls of Raffles City streak upward on both sides, and motion blur erupts intensely. [Style and Quality Enhancement] Realistic 8K quality, ultra-fine mechanical texture and cloth physics, cinematic lighting and contrast, perfect motion blur, high dynamic range, no artifacts, coherent multimodal physical effects, stable cinematic image.

Chapter 2 (0-15 seconds): Freefall · Purple AITO M7 Enters the Frame. Style: rugged realism, 35mm handheld camera, natural grain, subtle organic shake. Camera: primarily handheld follow shots, with quick cuts between the protagonist's falling perspective and the ground car-chase perspective to create extreme tension. Maintain full real-time speed, with no slow motion. Lighting: dazzling high-contrast sunlight at Chongqing noon, strong reflections on the glass curtain walls of Raffles City, and heat haze rising from the road. Sound effects: wind-cutting shriek intensifies continuously -> engine roar approaching from a distance -> sharp tire friction on asphalt -> cyber-energy hum -> metallic thud at the moment of impact -> dull compression as four wheels land -> engine roar continues and grows stronger. [Visual Reference / Description] The protagonist remains the same female character from the reference image, preserving all details. Scene: on the Chongqing ramp road below Raffles City, a purple AITO M7 drives at high speed. It uses the upward slope of the ramp to launch naturally and precisely catch the protagonist as she falls from the rooftop. No slow-motion close-ups at any point; keep the rhythm realistic, high-speed, and cinematic. [Timeline per Second] Continuing from Video 1 and extending by 15 seconds. 0-4s: [Extreme Speed Fall · Overlooking the Ground] Protagonist Image 1 falls at high speed while maintaining a balanced gliding posture with both arms spread. The camera locks onto her back. The curtain walls of Raffles City streak upward on both sides, the ground rapidly expands, and motion blur becomes extreme. The frame quickly inserts a ground view: a purple AITO M7 races along the ramp road below Raffles City. The car emits a cyber blue-purple glow, the engine roars, and the tires leave two black marks on the asphalt. 4-9s: [Ramp Launch · Trajectory Intersection] The purple AITO M7 charges to the top of the ramp. Using the ramp's inertia, the front of the car lifts into the air and the sunroof slides open instantly. The camera alternates rapidly between the falling protagonist and the climbing AITO M7. She keeps a high-speed falling posture with arms spread, and the AITO M7 keeps accelerating up the ramp. The two trajectories converge rapidly, compressing time to the limit and maximizing tension. 9-11s: [Last Second · Posture Change · Precise Entry] With only one second left before the sunroof, the protagonist instantly pulls in her outstretched arms and sharply changes from a horizontal gliding posture to a vertical upright posture. Her legs point straight down toward the open sunroof of the airborne purple AITO M7. The action is swift, decisive, and completely without hesitation. In the next instant, she drops vertically into the open sunroof and lands in the driver's seat at extremely high speed. No slow motion at any point; the impact is realistic and violent. 11-13s: [Four Wheels Landing · Maintaining Drive] The body of the car compresses slightly under the force of catching her. All four wheels slam back to the asphalt. The suspension violently absorbs the double impact. Immediately after landing, the engine roar rises further. Without slowing or stopping, all four tires scrape the asphalt, leaving new black marks, and continue driving at full speed. 13-15s: [Stable Inside Car · Energy Accumulation] The AITO M7 continues high-speed driving. The camera tracks close to the side from a low angle as blue-purple energy patterns spread from the four wheels across the body. The sound of mechanical transmission rises subtly from the underside and keeps strengthening. The body vibrates slightly during the high-speed run. The precursor energy of the coming transformation surges and churns beneath the paint. [Style and Quality Enhancement] Realistic 8K quality, ultra-fine mechanical details and energy-light textures, cinematic volumetric light and heat haze, perfect speed blur, HDR glow, no artifacts, full real-time speed, no slow motion.

Chapter 3 (0-15 seconds): AITO M7 Transforms -> Becomes an F-14 -> Protagonist Stands on the Aircraft Back and Takes Off. Style: rugged realism, 35mm handheld film aesthetic, natural grain, subtle shake. Camera: multi-angle follow coverage including ground tracking, low angle close to the ground, aircraft side view, and protagonist first-person view, all following the aircraft tightly throughout the transformation. Transformation details must remain clearly visible. Atmosphere: light smoke and heat haze drift across the Chongqing road. Cyber blue-purple light refracts between buildings. Noon sunlight produces dazzling reflections and strong shadows across the metal surfaces. Sound effects: engine roar surges -> metal skin bursts and folds -> deep hydraulic tremor as the wings unfold -> metallic gripping sound as the protagonist climbs the exterior -> cockpit seal pops and is immediately drowned by wind noise -> explosive ignition of twin engines -> piercing shriek as the F-14 takes off and breaks the air -> powerful high-altitude wind overtakes the entire soundscape. [Visual Reference / Description] The purple AITO M7 completes a full transformation while driving on the Chongqing road, changing from a car into an F-14 fighter jet, as shown in Image 2. During the transformation, the protagonist clings to and climbs along the aircraft exterior in a dangerous and exposed position. She finally stands centered on the back of the F-14, legs slightly apart to stabilize her balance. Her white suit and ponytail whip violently in the extreme airflow. The F-14 takes off directly from the Chongqing road, and the protagonist remains standing firmly on its back. [Timeline per Second] 0-4s: [Road Acceleration · Transformation Start] The AITO M7 accelerates rapidly along the Chongqing road. Body panels burst open one after another and unfold. The hood rolls upward and becomes mechanical structure. The doors fold outward. The metal skin cracks along structural lines, revealing the cold mechanical interior. The protagonist climbs dangerously toward the top of the aircraft while gripping the transforming metal skeleton. She jumps and shifts position in sync with the aircraft's changing shape. The camera tracks every detail from close to the side of the aircraft. 4-6s: [Wings Unfold · Engines Fully Reassemble] The F-14's iconic swept wings snap open from the folded state and lock into place. The camera captures a low-angle near-ground full view of the wing deployment. Heat haze and dust are blasted up by the airflow from the wings. The twin engine nacelles violently reassemble into jet structures, emitting blue-purple thrust flames. The exhaust scorches the road surface. By now, the protagonist has climbed to the center of the aircraft's back, feet planted firmly, standing upright as the transformation completes. 6-8s: [Protagonist Stands on Aircraft Back · Takes Off] The instant the transformation completes, the protagonist stands fully upright on the back of the F-14. The hem of her white suit flies up in the strong airflow, and her ponytail extends horizontally. The silver mechanical parts reflect the noon sun intensely. The F-14's twin engines ignite at full power. The aircraft surges forward, the front wheel lifts, and the rear wheels leave the asphalt at the last possible moment. The nose pitches upward, carrying the protagonist into the Chongqing sky while she remains standing on its back. 8-15s: [Takeoff and Low City Skim · Protagonist Holds Position] The F-14 climbs vertically, then abruptly lowers its nose and skims over Chongqing at ultra-low altitude.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 일본 교실 속 속삭임 로맨스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
15초 분량의 시네마틱 일본 드라마풍 순애·썸 분위기 단편으로, 초현실적 품질과 오후 텅 빈 교실의 따뜻한 황금빛 햇살이 특징입니다,...

출처: [게시물](https://x.com/JiahaoYang_art/status/2033119940216344616) · 게시일: 15 Mar 2026

```text
15-second cinematic Japanese drama pure love ambiguous short film, ultra-realistic quality, warm golden sunlight in an empty classroom in the afternoon, spilling through the blinds onto the side-by-side desks, fine dust motes slowly floating in the light beams, old wooden desks, extremely natural subtle movements, breathing, and eye tension, characters maintain consistent faces, clothing, and hairstyles throughout without deformation, drift, or artifacts, real slight chest rise and fall synchronized with breathing, shallow depth of field, creamy blurred background, warm film grain, 8K sharp, Japanese youth restrained heart-fluttering suffocating atmosphere.
0-4 seconds: Extremely slow push-in shot from a medium shot of the desktop to a close-up of the two people's side profiles sitting side-by-side. A pure girl in a summer school uniform is focused on writing notes with her head down, long black hair and stray hairs by her ears are gently lifted by a slight breeze, long eyelashes cast subtle shadows, skin is naturally pink and tender, a slight, unintentional upturn of the corner of her mouth in concentration, light and even breathing.
4-9 seconds: Switch to a close-up of the boy. His school uniform collar is slightly loose, he props his elbow on the desk and secretly turns his head to gaze at her, his eyes filled with gentle, restrained affection and tenderness, pupils slightly dilated, his Adam's apple gently rolls. Suddenly noticing her pen pause, he quickly and flusteredly turns his head to pretend to look at his own notes, his earlobes quickly turn slightly red, his fingertips tremble slightly as he grips the pen, occasionally glancing at her from under his bangs, his breathing is slightly disordered, and his lips are tightly pressed in an effort to remain calm.
9-15 seconds: Extreme close-up of both faces in the same frame, slow-motion eyes suddenly meet: the girl slowly turns her head, first showing a dazed surprise, then quickly and shyly lowers her head for 0.3 seconds, gently biting her lower lip, her cheeks and earlobes instantly bloom with cherry blossom pink, her moist eyelashes timidly look up to meet his gaze again, while softly and shyly whispering, "...What are you looking at?"; the boy freezes completely, his pupils dilate, and he is stunned for 0.4 seconds, then flusteredly and quietly stutters in response, "N-nothing...". The girl whispers even quieter, biting her lip and peeking at him again, continuing to whisper, "...Liar.". The boy pauses, then gently sighs and whispers, "...Just looking at you.", the corner of his mouth slowly curls up into a shy, gentle, crooked smile, fine lines appear at the corners of his eyes, and his breathing noticeably deepens. An invisible current seems to pull the ambiguous tension between their faces, sharing each other's breathing temperature, the background completely melts into layers of creamy, dreamy light spots, warm halos, and fine air particles.
Lip synchronization is natural and precise, emotional micro-tremors and breathing are synchronized, dialogue is low-energy whispering with a shy tone, natural short pauses between 200-400 milliseconds, the mouth only moves slightly when speaking, without exaggeration or robotic feel, perfect natural lip-sync and emotional authenticity.
Overall Sound Effects: Distant summer cicada chirping faintly, the soft scratching sound of the pen touching the paper, the almost inaudible low-frequency pulse of their heartbeats, finally fading into a very light, airy piano. The dialogue is completely naturally integrated into the scene as whispers, the girl's voice is soft and shy, the boy transitions from flustered stuttering to gentle.
Character identity is maintained throughout, real subtle head tilts, eye movements, and breathing synchronization, no text, watermarks, or subtitles, pure Japanese style youth secret crush heart-fluttering suspense.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### LaFerrari 광고 스토리보드
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
정교한 카메라 움직임과 프리미엄 제품 표면 표현에 초점을 맞춘 럭셔리 슈퍼카 광고용 샷별 스토리보드입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039932977287979053) · 게시일: 03 Apr 2026

```text
Supercar commercial cinematography storyboard

Shot 1 (1.5s): Opening frame on the supercar from the front, showcasing its signature aggressive face.

Shot 2 (1s): Close shot. The virtual camera slowly orbits around the emblem without spinning in a full circle, emphasizing the Ferrari prancing-horse logo.

Shot 3 (1.5s): Close shot, angled view of the LaFerrari's distinctive butterfly door from the side of the car, with a slow orbiting move that emphasizes the body lines.

Shot 4 (1s): Camera moves to the rear for a close shot, then slowly pulls backward using a Hitchcock dolly-zoom effect for visual impact.

Shot 5 (1s): Close shot of the car's side mirror with a slow orbiting move.

Shot 6 (1s): Camera slowly pushes forward using a low-angle advancing move. The car remains still, showing strong perspective, shifting light and shadow, professional automotive cinematography, deep background, cinematic composition, stable visual center, and high-definition live-action quality.

Shot 7 (1s): Lateral track move. The camera sweeps parallel across the LaFerrari body. The car stays completely still as the frame glides smoothly. Side lighting traces the waistline, includes wheel close-ups, delicate reflections, a premium feel, cinematic movement, and clean composition.

Shot 8 (1s): Top-down angle. The camera slowly descends. Static supercar, perfect body proportions, top-light texture, clean ground reflections, aerial-feel movement, the car remains still, symmetrical composition, luxurious texture, 8K ultra-realistic, advertising-grade image.

Shot 9 (1s): Slow push-in close-up from the full car toward the headlights / wheel / waistline. The car remains still. Macro detail, shifting light and shadow, cinematic shallow depth of field, premium texture, sharp detail, commercial photography.

Notes:

No transitions are needed between shots.

No people should appear in the frame.

Highest image quality: 8K.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### "위치"
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
"location": "Tokyo Cityscape (Night)", "duration": "10s", "prompt": "A cinematic POV shot riding an invisible rollercoaster through Tokyo at night. A...

출처: [게시물](https://x.com/TechTalkNAVI/status/2039941029265355123) · 게시일: 03 Apr 2026

```text
{
 "location": "Tokyo Cityscape (Night)",
 "duration": "10s",
 "prompt": "A cinematic POV shot riding an invisible rollercoaster through Tokyo at night. A glowing neon rail 'creates itself' milliseconds before the camera hits it, weaving through the steel structures of Tokyo Tower and nearby buildings. As the camera passes, each building it touches instantly transforms into a stack of glowing cubes that rotate and re-assemble. The shot ends with the camera diving straight down into a sea of neon lights, which turns into a giant QR code or a logo just before the screen goes black.",
 "vfx_focus": [
 "Procedural rail generation",
 "Dynamic environment transformation (Geometry nodes style)",
 "Extremely high-speed camera motion with light streaks"
 ]
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 유성 각성 전쟁 히로인
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
100% 실사 촬영 질감, Hollywood IMAX 블록버스터 품질, 자연광과 그림자, 차가운 다큐멘터리 스타일, 흐린 날의 자연광이 특징입니다,...

출처: [게시물](https://x.com/ChrisTheNerv/status/2040043939109953944) · 게시일: 03 Apr 2026

```text
100% real-life shooting texture, Hollywood IMAX blockbuster quality, natural light and shadow, cold documentary style, natural light on a cloudy day, handheld one-shot throughout, breathing shake, random focus shift, 16:9 widescreen.
【Scene Environment】
A destroyed city street extending into the distance. On both sides are ruined concrete buildings, exposed rebar, shattered windows, and some buildings are still burning, with orange flames and black smoke rising. Abandoned cars are scattered on the cracked asphalt road, several of which are burning. The sky is gloomy gray, with smoke and dust suspended in the air. Multiple meteorites streak across the sky with long trails of fire and dense smoke. In the background, terrified civilians scatter among the ruins, some falling, others dragging the injured.
【Main Character】
Chinese beauty, deep red hair tied in a loose, messy bun, with a few strands hanging by her face. Fair skin, sharp features, defined jawline, natural makeup, detailed eye makeup. Attire: Black long leather trench coat over a black vest, black denim mini skirt, black flat combat boots, no belt, wearing black futuristic gauntlets on both hands. Expression is tense and restrained, slightly painful, with slightly furrowed brows—eyes filled with despair and strong will.
【15-Second One-Shot · Awakening Strike Version】
0-2 seconds · Awakening
Low-angle shot, framing her upper body and face, looking up at her standing alone in the center of the destroyed street. The wind blows her black leather trench coat. She opens her lips and screams in Japanese: "Kakusei shiro!" She suddenly opens her right hand, and the black futuristic gauntlet crackles. Purple crystal-textured electric arcs burst from her arm and gauntlet. Air compresses inward, and space warps and distorts. The shockwave emits a low sonic boom. Purple rune lines appear and circulate around her body.
2-5 seconds · Eruption
The camera begins to orbit around her. Dark gold cracks burst from her chest, and thick golden liquid oozes out like blood. She screams in pain. Purple mist and fine electric arcs shoot outward. All her clothing tears open and explodes from the inside, burning into ash—leaving nothing. Organic armor fragments shoot outward, then retract unnaturally to reattach to her body. Purple patterns symmetrically spread across her face. A crack opens on her cheek, revealing pulsating purple light underneath. Simultaneously, multiple mechanical arm-like appendages violently burst from her back—dark metallic texture, blade-shaped, spreading outward like devil's wings. Sparks, blue electric arcs, and golden energy particles explode from the eruption point. The camera captures the complete unfolding from behind—her silhouette outlined against the gray sky, mechanical appendages spread like a fan. The eruption sound is like tearing metal mixed with arc discharge.
5-8 seconds · Growth
Organic matter seeps from her body, the surface shimmering with iridescent light. White armor plates collide and fuse, leaving burn marks. The armor extends downward, completely engulfing and replacing her flat combat boots, forming white and dark purple interwoven armored boots, locking into place with tiny sparks. She grits her teeth and lets out a painful roar. The core in her chest flickers like embers. Purple-black metal spreads over her face, forming an uneven mask, the left eye covered before the right. Compound eyes begin to form, irregularly flashing with liquid light medium. The camera continues to orbit around her.
8-12 seconds · Completion
The camera continues to slowly orbit her. The mask completely seals. Horn-like structures grow upward from the top of her head, burning with purple-gold flames. One compound eye glows steadily, the other flickers with unstable current. The armor is interwoven with white and dark purple, uneven and covered in battle damage, with glowing purple cracks oozing light fluid. Mechanical appendages sway slightly behind her. Each armor plate emits a crisp metallic click when locked, followed by distinct mechanical reset sounds. She slowly lowers her head to examine her hands—the knuckles of the white and dark purple interwoven armored gauntlets seep purple light. She slowly raises her head to look straight ahead, and the compound eyes suddenly glow fully.
12-15 seconds · Supersonic Charge
The camera rapidly retreats. She pushes off the ground with her feet, and the asphalt instantly explodes into a deep crater. A violent purple energy explosion spreads outward from the takeoff point, sending gravel and asphalt fragments flying into the air. She shoots into the air at supersonic speed, charging directly towards the camera—a conical sonic boom cloud forms behind her, the mechanical appendages are flattened backward by the airflow, and the image generates strong dynamic blur. Her figure grows larger and closer, filling the entire frame. A purple energy trail drags behind her. In the final frame, her armored faceplate almost hits the lens, the compound eyes glow scarlet red, and the screen suddenly cuts to black.
【Ambient Sound】
Low sonic boom during awakening, tearing metal and arc discharge sounds, painful screams, crisp metallic clicks, heavy metal sounds of mechanical appendages unfolding, crackling sounds of burning in the background and distant explosions, the final supersonic charge accompanied by the sound of the takeoff explosion, sonic boom impact, and rapidly approaching wind pressure. Everything falls silent the moment the screen cuts to black.
【Physical Texture Enhancement】
Real light and shadow, visible skin texture on the face before transformation, visible real wear and tear on the leather trench coat before transformation. Mechanical appendages possess physical weight and inertia—they sway slightly after unfolding, not rigidly fixed. The armor plates are interwoven with white and dark purple, with visible scratches, welding marks, and uneven edges—not clean and smooth. All movements are steady and powerful, full of pain but resolute—she awakens while enduring. Occasional slight camera shake, pure handheld follow-shot feel.
【Sound Design】
Layered progression from the scream activation to the explosive mechanical eruption, escalating to the takeoff point explosion and the sonic boom of the supersonic charge, finally cutting abruptly to silence. The entire sequence exudes absolute power. Generate sound effects only, no music.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 구름 동굴 검영
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
속도감, 충격감, 대규모 신화적 무협 에너지를 위해 설계된 톈먼산 배경의 wuxia 원테이크 스펙터클입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039865857179013318) · 게시일: 03 Apr 2026

```text
[Cloud Cave Sword Shadow · Heavenly Gate Bloody Battle]
— One-shot sequence at Tianmen Mountain, Zhangjiajie
Core Style: Tsui Hark's new style Wuxia blockbuster, one-shot sequence, high frame rate, 4K ultra-clear.

Tone: Tsui Hark's bright tone, “Cold Jade Blue-Black + Amber Flowing Light.” High contrast, mountain mist acts as a soft light filter, sharpening character outlines, DaVinci industrial-grade color grading.

Scene: Tianmen Mountain, Zhangjiajie (Wacky terrain of Western Hunan. Tianmen Cave opens, swallowing clouds and mist; 999 steps of the Heavenly Ladder hang vertically on the cliff, like a path to heaven; stone forests and pillars cluster like sharp swords, plank roads are faintly visible amidst surging clouds, birds do not cross).

Camera Movement Trajectory:
Low-angle upward shot (emphasizing the natural danger) → Rapid push toward the cave entrance → 180° horizontal pan (showing intense fight on the plank road) → Dive down → Slowly pull back to center → Backlit close-up.

Shot Script:
0-4 seconds [Opening Stance · Heavenly Gate Cloud Surge]:

Movement: Extreme low-angle upward shot, the camera rapidly swoops up and over the Heavenly Ladder from the bottom.

Visuals: Character face reference @[Image 1] Wuxia swordsman attire (white clothes like snow, low-pressed bamboo hat, holding a long sword) stands alone in the center of the 999 steps.

Action: Strong winds whip up the surrounding clouds and mist. [Image 1] holds the sword hilt with the right hand, and the left hand forms a sword-finger gesture across the bridge of the nose. The camera pulls back to show the Tianmen Cave behind him, resembling a giant eye of the heavens.

4-8 seconds [Fierce Battle · Suspended Ladder Interception]:

Movement: 180° orbiting pan.

Visuals: More than ten assassins in tight suits swing down from both sides, clinging to the cliff like monkeys.

Action: [Image 1] touches the steps with his toes, his body spinning upside down. (Tsui Hark-style slow-motion dynamics) The sword remains sheathed, using the sheath as a stick to point, parry, and strike. The air current shakes the rainwater on the steps into mist. The camera rapidly orbits, capturing afterimages and the sparks of metal impact.

8-11 seconds [Breaking the Formation · Traversing the Stone Forest]:

Movement: The camera follows the character diving, passing through a stone archway into the cliffside plank road.

Visuals: Assassins set up a steel wire trap.

Action: [Image 1]'s long sword finally unsheathes (the blade reflects amber sunlight), executing a sweeping strike. The sword energy transforms into a blue-black arc of light, cutting the steel wires. The snapping wires rebound and shatter cliff rocks. He dodges and weaves on the narrow plank road, his figure intersecting with the stone pillars, blending virtual and real.

11-15 seconds [Closing Stance · Mist Dissipates on the Lonely Peak]:

Movement: The camera slowly pulls out from the cave entrance, widening the view to reveal the abyss.

Visuals: Paper talismans (or dead leaves) flutter in the wind. [Image 1] stands at the edge of the Tianmen Cave, with a sea of clouds below his feet.

Action: He performs a sword flourish and sheathes the sword, placing it on his back. Sunlight streams through the Tianmen Cave, creating a massive Tyndall effect.

Freeze Frame: The camera pushes in for an extreme close-up. A drop of blood drips from the edge of the bamboo hat, tracing his jawline. His eyes are sharp as lightning, with the vast landscape in the background.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 7장 이미지 심리스 모핑 시퀀스
![Language-JA](https://img.shields.io/badge/Language-JA-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
7장의 정지 이미지를 하나의 통제된 연속 변신 샷으로 바꾸는 재사용 가능한 모핑 템플릿입니다.

출처: [게시물](https://x.com/YaReYaRu30Life/status/2039474680235741681) · 게시일: 01 Apr 2026

```text
[Basic Settings]
structure: Single continuous shot (no cuts)
progression: Morphing 7 images sequentially
visibility: Each image is clearly recognizable for only an instant (no stopping required)
transition: Always smooth and continuous
style: Cinematic, high-definition, dynamic, no flicker
[Prompt Body]
Start from <<<Image1>>>.
The footage proceeds in a completely seamless single shot, continuously transforming in the order of <<<Image1>>> -> <<<Image2>>> -> <<<Image3>>> -> <<<Image4>>> -> <<<Image5>>> -> <<<Image6>>> -> <<<Image7>>>.
The overall scene is not static; morphing occurs within a dynamic video where the camera is constantly moving.
However, the recognizability of the subject is maintained, and the composition is controlled to prevent collapse.
Each image has a peak state where it is clearly visible for an instant within the flow, but there is no stopping or holding.
Everything is expressed as a continuous "evolution within motion."
[Transformation Logic (Fixed order, no duplication)]
<<<Image1>>> -> <<<Image2>>>:
The camera begins transformation while smoothly pushing in forward
Gradual change in the order of outline -> parts -> color -> texture
Fine particle decomposition -> reconstruction
<<<Image2>>> -> <<<Image3>>>:
Tracking movement where the camera flows horizontally
The structure is rewritten by light scanning
Emitting lines flow, and the shape continuously changes
* Particle expression is prohibited
<<<Image3>>> -> <<<Image4>>>:
Orbit movement where the camera circles around the subject
The shape is stretched and transformed by spatial distortion and lens warp
<<<Image4>>> -> <<<Image5>>>:
The camera slightly pulls back and changes perspective (light dolly out + angle change)
The subject melts like liquid and is reformed while flowing
<<<Image5>>> -> <<<Image6>>>:
The camera accelerates momentarily, adding momentum to the movement
The subject fragments, scatters in space, and then reassembles into a new form
<<<Image6>>> -> <<<Image7>>>:
The camera stabilizes while converging back toward the center
Energy converges at the center and integrates into the final form through light and waves
[Camera Behavior (Important)]
- Always moving but controlled movement
- Allowed:
  - Push-in / Pull-out
  - Horizontal tracking
  - Orbit (circling)
  - Light perspective change
- Prohibited:
  - Sudden blur
  - Loss of subject
  - Unnatural jumps
[Constraints (Important)]
- Cut editing prohibited (complete single shot)
- Reuse of the same effect prohibited
- Flicker, noise, and breakdown prohibited
- Subject position / scale should not be significantly disrupted
- Each image must achieve a clearly visible state at least once
- All changes must be continuous and meaningful structural transformations
[Enhancement Keywords]
dynamic camera movement
cinematic motion flow
smooth continuous morphing
temporal coherence
high detail preservation
consistent subject identity
seamless transformation flow
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 폴더블 스마트폰 패션 광고
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
그라데이션 폴더블 스마트폰을 위해 macro 디테일, 날카로운 컷, 프리미엄한 모션 언어를 담은 상업용 fashion-tech 프롬프트입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039157138002780202) · 게시일: 01 Apr 2026

```text
Product: Color-shifting gradient foldable smartphone (e.g., light purple to ice blue gradient)

Style: Trendy fashion, energetic fast pace, high-end texture, no people, minimalist light and shadow, fashionable trend style
Tones: High-saturation contrasting colors, light purple gradient frosted glass texture, clean and bright, cinematic light and shadow
Camera Language: Macro close-up, fast rotating camera movement, orbiting camera movement, handheld dynamic camera movement, push-pull quick cuts, smooth transitions
Tempo: 15 seconds tight quick cut, beat-synced editing, sharp transitions

Visual Content:
The light purple gradient foldable phone rapidly rotates against a pure black background, with light flowing across the body; macro close-ups of the ultra-thin hinge structure, the glass texture of the outer screen, the brushed metal close-up of the camera module, and the extremely thin side bezel; quick cuts showing the moment the phone unfolds from folded state, the visual impact of the inner screen's ultra-narrow bezel; paired with simple trendy scenes such as a minimalist office desk, an art gallery corner, late-night city neon, or a trendy collectible display case; fashionable and energetic. No models throughout, focusing only on the product.

Sound Effects: Trendy electronic drum beats, metallic clinks, mechanical click sound of the screen unfolding, beat-synced sound effects
Quality: 4K high definition, commercial advertisement quality, smooth dynamics, vibrant colors
Requirements: Fast pace, tight transitions, high-end fashion, youthful energy, no people appearing.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 프롬프트 카테고리

| 카테고리 | 설명 | 수량 | 예시 ID |
| --- | --- | --- | --- |
| 액션 / 판타지 | 전투, 추격, anime, wuxia, 크리처, 대형 시네마틱 스펙터클 프롬프트입니다. | 21 | `#23`, `#33`, `#37`, `#41`, `#44`, `#45` |
| 영화적 리얼리즘 | 분위기, 몸짓, practical light, 설득력 있는 카메라 움직임에 초점을 둔 grounded live-action 프롬프트입니다. | 2 | `#48`, `#76` |
| POV / FPV | 카메라의 운동감에 초점을 둔 1인칭, drone-like, body-mounted, 몰입 우선 프롬프트입니다. | 16 | `#4`, `#5`, `#6`, `#10`, `#11`, `#40` |
| 상업 / 제품 | 광고, 패션, 라이프스타일, 제품, 프리미엄 브랜드 스타일 프롬프트입니다. | 24 | `#8`, `#9`, `#13`, `#15`, `#19`, `#22` |
| 레퍼런스 기반 | 이미지 레퍼런스, 캐릭터 일관성, 프레임 간 제어에 의존하는 프롬프트입니다. | 12 | `#12`, `#16`, `#21`, `#30`, `#51`, `#62` |
| 초현실 / VFX | 변형과 스펙터클을 중심으로 한 추상적, 불가능한, stylized, 효과 중심 프롬프트입니다. | 8 | `#14`, `#54`, `#85`, `#95`, `#99`, `#100` |
| 템플릿 및 구조화 형식 | 재사용 가능한 프롬프트 골격, JSON 스타일 스펙, 고도로 구조화된 프롬프트 형식입니다. | 17 | `#17`, `#20`, `#26`, `#29`, `#56`, `#64` |
| 일반 시네마틱 | 위의 더 좁은 범주에는 딱 맞지 않지만 범용 레퍼런스로 유용한 프롬프트입니다. | 25 | `#1`, `#2`, `#3`, `#7`, `#18`, `#25` |

## 액션 / 판타지

전투, 추격, anime, wuxia, 크리처, 대형 시네마틱 스펙터클 프롬프트입니다.

### 프롬프트 23
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
16:9 가로 화면, 스트리트 랩 MV 스타일, 네온 보라와 파란색의 차가운 톤, 폭발적으로 쿨하고 사나운 분위기. 0-3초: medium shot push-in, 도시...

출처: [게시물](https://x.com/songguoxiansen/status/2033175478765289598) · 게시일: 15 Mar 2026

```text
16:9 horizontal screen, street rap MV style, neon purple and blue cool tones, explosive cool and fierce atmosphere. 0-3 seconds: Medium shot push-in, city street night scene with flashing neon lights, an 80-year-old silver-haired woman stands in front of a graffiti wall, short silver-white hair styled in a neat slick-back, distinct square face contour, sword-like eyebrows slanting towards the temples, eyes sharp like electricity, wrinkles at the corners of her eyes like badges of time, a confident smile on the corner of her mouth, wearing a black leather jacket over a white printed T-shirt (large black letters "YOLO" on the chest) + black cargo pants + white high-top sneakers, a thick gold chain necklace around her neck, silver bracelet on her wrist, holding up a microphone with both hands, strong drum beats of the BGM start, the old woman's eyes sharpen, and her lips open to start Rap. 3-7 seconds: Medium shot + close-up switch, the old woman starts rapping, with an extremely strong sense of rhythm, her silver hair flying with her head-nodding movements, one hand holding the microphone, the other hand making gestures to match the rhythm—index finger pointing at the camera, palm cutting the rhythm up and down, making hip-hop gestures, movements are smooth and flowing, eyes sharp and looking directly at the camera, wrinkles vividly jumping with her expression, lips opening and closing rapidly to spit out lyrics: [Rap Lyrics] "Eighty-year-old legs, can jump better than you! Silver hair flowing, this is my pride! Don't call me old, my Flow is better than yours, when you were playing rap, I was listening to disco!" (Fast speed, strong rhythm, fierce attitude) Quick cuts: facial close-ups, hand movements, full-body swaying, side silhouettes, synchronized with the BGM beat. 7-11 seconds: Dance segment, the camera pulls back to show the full body, the old woman starts dancing—first the classic hip-hop bounce, then a neat street dance freeze, followed by a body wave transmitting from the shoulders to the toes, and then a quick footwork workout, movements are clean and sharp, silver hair flies under the neon lights, the leather jacket flutters in the air, she continues to Rap while dancing: [Rap Lyrics] "Legs and feet are nimble, speed is not slow, my lyrics are carved in time! You play with phones, I play with beats, eighty years of life, written into this verse!" (Faster rhythm, stronger tone) Low-angle upward shot + 360-degree surrounding shot, capturing the old woman's cool and fierce dance moves. 11-15 seconds: Climax ending, the old woman makes a cool turn, her silver hair arcs in the air, she faces the camera and makes a "shush" gesture with her finger, then her lips move closer to the microphone, singing the last line in a low, magnetic voice: [Reality Lyrics] "Time never defeats a beauty, I just changed the way I experience youth..." (Slow rhythm, deep emotion, lingering finish) The camera slowly pushes in for a close-up of the old woman's eyes, the wrinkles at the corners of her eyes are all stories, her gaze is still sharp yet with a hint of kindness, the BGM abruptly stops at the climax, the frame freezes on the old woman's cool yet slightly gentle smile, vignetting + neon purple light halo.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 검은 고양이 사막 무술 결투
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
15초 오리지널 사막 무술 단편: 연노란 모래가 하늘을 뒤덮는 사막 한가운데, 가벼운 갑옷을 입은 검은 고양이 전사가 홀로 서 있습니다,...

출처: [게시물](https://x.com/nopinduoduo/status/2039915824216261101) · 게시일: 03 Apr 2026

```text
15-second Original Desert Martial Arts Short Film: A black cat warrior in light armor stands alone in a desert where yellow sand is flying all over the sky, facing the pursuers. The shots combine slow motion and fast editing; under backlight, the yellow sand rolls like ink mist. The character's movements are elegant yet ferocious, with tattered but flowing robes. Holding a short weapon, he shuttles and counterattacks at high speed. The overall tone is cold, lonely and oppressive, with high-end colors and obvious shallow depth of field, just like a high-quality oriental martial arts movie.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 【핵심 포인트】
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
live-action anime 각색 · 호흡법 결전 (15초 · 초열혈 특수효과 버전) 【핵심 포인트】: Water Breathing (Blue...

출처: [게시물](https://x.com/johnAGI168/status/2021610292979876208) · 게시일: 11 Feb 2026

```text
Live-Action Anime Adaptation · Breathing Technique Decisive Battle (15 seconds · Super Burning Special Effects Version)
【Core Focus】: Water Breathing (Blue Water Dragon) VS Thunder Breathing (Golden Lightning), live-action extreme speed duel.

【Style】: Hollywood live-action anime adaptation film quality, dark samurai style, 4K ultra-clear, extreme fast cuts, explosive particle light effects, no gore.
【Duration】: 15 seconds
【Scene】: Misty forest under the moonlight, muddy ground, falling leaves.

[00:00-00:05] Shot 1: Water Melody Prelude · Starting Stance (Sense of charging)
Visuals: A young samurai wearing a green and black checkered haori (jacket), lowering his center of gravity under the moonlight, gripping his sword with both hands.
Action: He takes a deep breath, and the surrounding air instantly solidifies. As he draws his sword, a giant blue water dragon, condensed from high-pressure water flow, appears out of thin air, rotating rapidly around his body and blade, emitting the roar of flowing water.
Special Effects Details: The water flow has a realistic sense of splashing, illuminating the dark forest.

[00:05-00:10] Shot 2: Thunder Flash · Charge (Sense of extreme speed)
Visuals: The opponent, a blonde swordsman wearing a yellow triangular patterned haori, is crouched extremely low, adopting the posture of Iaijutsu (sword drawing technique).
Action: The ground suddenly explodes, and he instantly transforms into a dazzling golden lightning afterimage, refracting and charging through the forest in a "Z" shape at a speed undetectable by the naked eye.
Special Effects Details: Golden electric arcs and scorched fallen leaves remain in the places he passes.

[00:10-00:15] Shot 3: Water and Thunder Collision · Final Sound (Ultimate move clash)
Visuals: Extreme speed collision. The young samurai swings the giant blue water dragon down to meet the attack, and the blonde swordsman, transformed into lightning, crashes into him head-on.
Action: The two swords violently collide in the center of the frame.
Special Effects Spectacle: The blue water dragon and the golden lightning instantly explode, forming a massive water-thunder energy storm that spreads outwards. The surrounding large trees are snapped in half by the energy wave, and mud and light obscure the camera. The scene ends in an extremely dazzling blue, yellow, and white light.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### anime 초고속 컷 테스트 — 10초 안에 20개의 하드 컷 (0
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
anime 초고속 컷 테스트입니다. 10초 안에 20개의 하드 컷으로 구성되며(컷당 0.5초, fade-in/fade-out 없음, 전환 없음), 0.0초부터 0.5초까지는 컷 1 —...

출처: [게시물](https://x.com/tebasaki3D/status/2039903531415552048) · 게시일: 03 Apr 2026

```text
Anime high-speed cut test — 20 hard cuts in 10 seconds (0.5 seconds per cut, no fade-in/fade-out, no transitions).
[0.0 seconds to 0.5 seconds]: Cut 1 — Close-up. Anime Girl A: Long crimson hair, vivid green eyes. Winks at the camera.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 기름때 묻은 정비공의 수리 장면
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
기름때 묻은 정비공이 심하게 덜컹거리는 고물차를 마치 무술 대결처럼 고치는 장면입니다. 렌치가 날아가고, 스파크 플러그가 칼처럼 던져지며, 보닛은...

출처: [게시물](https://x.com/sebatheepan/status/2040079840754205010) · 게시일: 03 Apr 2026

```text
Watch a grease-stained mechanic fix 
a violently rattling junker like it’s a martial arts fight. 

Wrenches flying, spark plugs thrown like knives, hood slammed with a thunderous boom. 

From rusty disaster to purring monster in seconds.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 45
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
불타는 전장에서 목숨을 잃은 사무라이가 다른 세계의 아기로 깨어나는 단편입니다. 전반부는 치열한 전장 전투이고...

출처: [게시물](https://x.com/sailorv321/status/2040127822908596305) · 게시일: 03 Apr 2026

```text
A short film about a samurai who loses his life on a burning battlefield and wakes up as a baby in another world.
The first half is a fierce battle on a battlefield covered in mud and flames. The young samurai challenges his final duel, seems to win for a moment, but is ultimately cut down and falls. His vision tilts low, and his consciousness fades as he is enveloped in fire and smoke.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 50
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
과장된 비율, 날카로운 kung-fu 축구 안무, 통제된 리듬 에너지가 특징인 stylized 3D 애니메이션입니다. CHARACTERS - Football master: ...

출처: [게시물](https://x.com/johnAGI168/status/2039924160567058725) · 게시일: 03 Apr 2026

```text
Stylized 3D animation with exaggerated proportions, sharp kung-fu-soccer choreography, and controlled rhythmic energy. CHARACTERS - Football master: an impeccably focused martial-arts soccer prodigy in a fitted training top, wrapped wrists, tapered athletic pants, and classic football boots. Piercing gaze. Every movement follows a precise rhythm: pause -> burst -> lock. Theatrical, hypnotic, absolute master of the field. - Opponent goalkeeper: tense, exhausted, intimidated, standing before the goal line under immense pressure. ENVIRONMENT Futuristic night football stadium with glowing floodlights, wet grass, drifting mist, roaring crowd silhouettes, dramatic contrast. MOOD Aggressive precision. Football master = total control. Goalkeeper = anxious, overwhelmed. TIMELINE 0:00-0:02 (Close-up) The ball rests at the player's feet. He taps it lightly once, then rolls his ankle and snaps into a low martial stance, one hand extended, one foot pinning the ball, energy coiling before release. 0:02-0:05 (Action sequence) He flicks the ball high into the air. Launching upward, he strikes it in mid-air with a flurry of kung-fu kicks and spinning leg strikes, each impact perfectly controlled. The ball accelerates, glowing with spiraling energy trails like a dragon sphere. 0:05-0:08 (Tracking shot) He lands and sprints forward with impossible precision footwork, dribbling through multiple defenders in braided arcs, body feints, sweeping turns, and explosive step-overs. The camera tracks low and fast as the glowing ball never leaves his control. 0:08-0:11 He plants his foot, twists his waist, and unleashes a violent, rhythmic power shot. The kick lands with a percussive burst, grass and mist exploding outward, the ball becoming a blazing comet with frosted vapor and shockwave ripples. 0:11-0:13 The goalkeeper dives desperately as the ball curves through the air in a smoking arc, slicing through the frame with dragon-fire energy, then smashes into the top corner of the net. 0:13-0:15 FINAL REVEAL The net whips violently. Smoke and light dissipate. The glowing ball settles in the goal. The goalkeeper lies stunned. The football master stands in silence, turns away calmly, and flicks his wrist as the crowd erupts. Epic, ultra-detailed, cinematic, premium animation, powerful lighting, heroic finish.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 대사 (오버랩)
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
고대 황실 서재를 배경으로 한 빠른 템포의 코미디 패러디 Seedance 2 단편입니다. 한나라풍 황금 용포를 입고 진시황으로 분장한 주황색 고양이가 앉아...

출처: [게시물](https://x.com/drjoetw/status/2039905967597613558) · 게시일: 03 Apr 2026

```text
A fast-paced comedic parody Seedance 2 short set in an ancient imperial study. An orange cat dressed as Qin Shi Huang in Han-style golden dragon robes sits behind a large desk. Gray mice in minister outfits line up, each stepping forward with scrolls. The cat barely looks and scribbles messy, meaningless brush strokes, moving faster and faster.

Dialogue (overlapping): Mice: “Your Majesty, urgent matter!” “National crisis!” Cat: “Approved. Next. Whatever.”

Suddenly, the cat slams the desk and shouts, “ENOUGH!!” He stands up and kicks the mice one by one, sending them flying like rockets. Final shot: he smugly adjusts his robe and strides out, saying, “This empire runs perfectly.”

Camera: fast cuts, whip pans, strong motion blur, 0.6–1.2s pacing, ending in slow motion. Tone: absurd, exaggerated, high-energy comedy.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 일본 anime
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
일본 anime입니다. 대사는 일본어이고, 구름이 흐릅니다. 소녀가 걷고, 귀엽게 점프한 뒤, 빨간 스위치를 누릅니다. 폭발하는 순간 잠시...

출처: [게시물](https://x.com/_3912657840/status/2040018529441730815) · 게시일: 03 Apr 2026

```text
Japanese anime. Dialogue in Japanese. Flowing clouds. A girl walks, jumps cutely, and hits a red switch. At the moment of the explosion, it briefly becomes black and white high contrast, then flame-colored high contrast. The tower in the background explodes violently, creating a flame backlight high contrast. The girl says, "Haa~!?" Surprised by the explosion.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 15초 오리지널 원소 전투 단편
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 오리지널 원소 전투 단편: 얼음으로 뒤덮인 화산 산맥 위에서, 용암 흑요석 갑옷을 입은 전사가 정면으로 충돌합니다...

출처: [게시물](https://x.com/ZikinArt/status/2040006818953322644) · 게시일: 03 Apr 2026

```text
15-second Original Elemental Battle Short Film: On an ice-covered volcanic mountain range, a warrior in lava obsidian armor collides head-on with an opponent who controls cold crystal power. Under their feet are snow-covered cracked lava; in the air, there are simultaneous flame roars, ice crystal shatters, steam eruptions and storm howls. The camera quickly switches between close-ups of armor textures, ice crystals, ground cracks and the ultimate collision moment, and finally ends with a steam explosion engulfing the screen, featuring a strong "fire vs. ice" visual conflict.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 파베르제 판타지 에그 애니메이션
![Language-ES](https://img.shields.io/badge/Language-ES-blue?style=flat-square)
매우 디테일한 시네마틱 4K 애니메이션 비디오로, 몽환적이고 에테리얼한 공간에 마법이 깃든 Faberge 스타일 부활절 달걀이 떠다니며, 정교한 금빛 세공과...

출처: [게시물](https://x.com/ShamiWeb3/status/2040096061835059412) · 게시일: 03 Apr 2026

```text
Highly detailed cinematic 4K animated video, precious enchanted Faberge-style Easter eggs floating in a dreamy ethereal space, ornate golden filigree and glowing runes on creamy porcelain and jewel-toned shells, semi-transparent eggs revealing intricate animated miniature fantasy
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 77
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
원소 전투를 다룬 오리지널 15초 단편입니다. 얼음으로 뒤덮인 화산 산맥에서, 화산 흑요석 갑옷을 입은 전사가 정면으로 충돌합니다...

출처: [게시물](https://x.com/David_eficaz/status/2039966320414937236) · 게시일: 03 Apr 2026

```text
Original 15-second short film about an elemental battle: In a volcanic mountain range covered in ice, a warrior in volcanic obsidian armor clashes head-on with an opponent who controls the power of cold crystal. Cracked, snow-covered lava stretches beneath their feet; in the air, flames roar, ice crystals shatter, steam erupts, and storms howl. The camera rapidly alternates close-ups of the armor textures, ice crystals, cracks in the ground, and the culminating moment of the clash, finally ending with an explosion of steam that floods the screen, creating a strong visual conflict between fire and ice.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 79
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
대낮의 ultra cinematic sci-fi 판타지 결투로, 빛나는 에너지 블레이드를 든 전사가 거대하고 무시무시한 크리처를 차분하고 집중된 상태로 마주합니다,...

출처: [게시물](https://x.com/CharaspowerAI/status/2040013966986957144) · 게시일: 03 Apr 2026

```text
ultra cinematic sci-fi fantasy duel in daylight, a warrior wielding a glowing energy blade stands facing a massive terrifying creature, calm and focused, ready for an intense high-speed confrontation

Dynamic cinematic system, mix of tracking shots + fast orbit moves + whip pans, seamless transitions masked by blade motion, impacts, and energy bursts, fluid continuous sequence with alternating real-time and slow motion highlights

(0-3s) wide establishing shot, warrior standing still, energy blade ignites with bright glow, creature approaching aggressively, tension builds
(3-6s) creature lunges forward, warrior reacts instantly with precise sidestep, fast blade strike, fluid defensive movement
(6-9s) high-speed combat exchange, warrior chaining fast strikes and evasions, blade leaving light trails, creature attacking with powerful sweeping motions, camera orbiting rapidly
(9-12s) slow motion highlight, warrior leaps and spins mid-air, energy blade slicing through space, creature reacting to impact, debris and dust suspended
(12-15s) final clash, creature charges, warrior channels force-like energy push combined with forward strike, massive impact sending shockwave across environment

Open landscape under bright daylight, minimal clutter, ground reacting to impacts, dust and debris enhancing motion and scale
Ultra realistic, high-end cinematic action, precise choreography, glowing energy blade effects, strong contrast lighting, fluid motion, intense speed, epic scale, no distortion, no stretching
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 15초 연속 원테이크 액션 시퀀스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 연속 원테이크 액션 시퀀스입니다. 컷 없음. 장면 전환 없음. 어두운 시네마틱 판타지 리얼리즘, 짙은 숲 그림자, 안개 레이어, 역동적인...

출처: [게시물](https://x.com/Artedeingenio/status/2039997977897435190) · 게시일: 03 Apr 2026

```text
15-second continuous single-shot action sequence.
No cuts. No scene transitions.

Dark cinematic fantasy realism, dense forest shadows, fog layers, dynamic camera, strong motion weight, grounded creature physics

Scene Structure

Dense forest → cliff edge → open valley

0–3s —
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 82
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
벚꽃 산맥이 내려다보이는 석양의 절벽 위에 홀로 선 사무라이가 꽃잎이 바람에 흩날리는 가운데 마지막을 위해 천천히 katana를 뽑습니다...

출처: [게시물](https://x.com/Alin_Reaper05/status/2040042931172655384) · 게시일: 03 Apr 2026

```text
A lone samurai stands on a cliff overlooking cherry blossom mountains at sunset, wind blowing petals around him, he slowly draws his katana for the last time, single tear on his face, slow cinematic crane shot rising above him as sun sets, emotional widescreen, ultra-realistic, like Ghost of Tsushima + The Last Samurai, warm golden tones, heartbreaking moment
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 88
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
대담한 공중 로그가 bio-mechanical 글라이더를 타고 혼란스러운 공중 섬 바자르를 가르며 급강하하고, 공중 상인 사이를 유연하게 누비며 회피합니다...

출처: [게시물](https://x.com/sebatheepan/status/2039723026124575231) · 게시일: 02 Apr 2026

```text
A daring aerial rogue diving on a bio-mechanical glider through a chaotic floating-island bazaar, weaving effortlessly through airborne merchants, dodging passing airships, flocking griffins, and tethered trading posts. He plummets past crumbling stone arches, busy rope bridges, and cascading waterfalls, barrel-rolling through narrow gaps with precision and style. Cinematic tracking shots follow his descent, enhanced by dynamic motion blur and ethereal dappled sunlight reflecting off crystal formations and mist. The sky-city pulses with an energetic fantasy vibe—flapping wings, shouting vendors, and nonstop vertical motion. Ultra-realistic detail with an epic high-fantasy action aesthetic, capturing speed, agility, and fearless momentum through the clouds.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 소녀가 용을 타는 초고속 비행 액션 장면
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
소녀가 용을 타는 초고속 비행 액션 장면입니다. 높은 프레임 수의 24FPS 일본 풀컬러 anime 스타일이며, 파란 용과 빨간 용 두 마리가 등장합니다,...

출처: [게시물](https://x.com/naoyuki_okada/status/2039573038392614995) · 게시일: 02 Apr 2026

```text
A super high-speed flight action scene of a girl riding a dragon. High number of frames, 24FPS Japanese full-color anime.
Two dragons, one blue and one red, are flying high above the clouds. They are flying faster than 100 km/h, cutting through the wind and passing between the clouds. A sense of freedom, liberation from anything that might interfere, and speed.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 15초 오리지널 사막 무술 단편
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 오리지널 사막 무술 단편: 연노란 모래가 하늘을 뒤덮는 사막 한가운데, 가벼운 갑옷을 입은 검은 고양이 전사가 홀로 서 있습니다,...

출처: [게시물](https://x.com/NimEshed/status/2039816152222949829) · 게시일: 02 Apr 2026

```text
15-second Original Desert Martial Arts Short Film: A black cat warrior in light armor stands alone in a desert where yellow sand is flying all over the sky, facing the pursuers. The shots combine slow motion and fast editing; under backlight, the yellow sand rolls like ink mist. The character’s movements are elegant yet ferocious, with tattered but flowing robes. Holding a short weapon, he shuttles and counterattacks at high speed. The overall tone is cold, lonely and oppressive, with high-end colors and obvious shallow depth of field, just like a high-quality oriental martial arts movie.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 15초 하이퍼리얼 대서사 전쟁 블록버스터
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 분량의 hyper-realistic 대서사 전쟁 블록버스터입니다. 스타일은 rugged realism, 35mm handheld 필름 미학, 자연스러운 grain, 미세한 흔들림이며, 항우가...

출처: [게시물](https://x.com/john87445528/status/2039348028574744685) · 게시일: 01 Apr 2026

```text
A 15-second hyper-realistic epic war blockbuster. Style: rugged realism, 35mm handheld film aesthetic, natural grain, subtle shake. Xiang Yu, the Hegemon-King of Western Chu, wearing the armor from Image 2, riding the horse from Image 1, holding a 13-foot 7-inch Overlord Spear, in a famous scene of slaughter on an ancient battlefield, leading a small number of soldiers against thousands of enemy troops in a display of lonely bravery. Scene 1: One-shot, low-angle ground-level slow follow of the horse's hooves, panning up to a close-up of Xiang Yu's face, showing bloodstains, resolute eyes, and a roaring expression as he shouts: “Zhai Xiaoniao,” give me back my money; Scene 2: Low-angle follow shot of Xiang Yu charging on horseback, leading the way; Generate only fighting sound effects and environmental sounds, no background music.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 망가진 오피스 커피 브레이크 샷 1
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Office Coffee Break Gone WrongShot 1: 모던한 오픈 플랜 사무실에서 버튼업 셔츠를 입은 지친 직장인이 책상에 앉아 커피를 마십니다. 차분한 medium shot,...

출처: [게시물](https://x.com/Dheepanratnam/status/2039387346706001941) · 게시일: 01 Apr 2026

```text
Office Coffee Break Gone WrongShot 1: Tired office worker in a button-up shirt sips coffee at his desk in a modern open-plan office. Calm medium shot, fluorescent lights, papers everywhere.Shot 2: He spills a drop — the coffee suddenly animates into a hyper-caffeinated coffee monster with espresso eyes and foam tentacles.Shot 3: Low-angle shot: The monster rampages across desks, flinging staplers and keyboards in realistic arcs while the worker dodges in panic.Shot 4: Fast-paced tracking shot through the office as coworkers scream and dive under tables, papers flying like confetti with accurate physics.Shot 5: Climax: Worker grabs a fire extinguisher and blasts the monster, turning it back into harmless foam. He sits exhausted, now covered in foam, as everyone claps slowly
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 15초 연속 원테이크 액션 시퀀스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 연속 원테이크 액션 시퀀스입니다. 컷 없음. 장면 전환 없음. 시네마틱 판타지 리얼리즘, 대형 크리처 애니메이션, 화염 시뮬레이션,...

출처: [게시물](https://x.com/Artedeingenio/status/2039333445403287777) · 게시일: 01 Apr 2026

```text
15-second continuous single-shot action sequence.
No cuts. No scene transitions.

Cinematic fantasy realism, large-scale creature animation, fire simulation, smoke, embers, dramatic lighting, atmospheric depth, dynamic camera tracking

Weighty creature movement, believable scale,
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 영화적 리얼리즘

분위기, 몸짓, practical light, 설득력 있는 카메라 움직임에 초점을 둔 grounded live-action 프롬프트입니다.

### 현대 일본
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
현대 일본. 도쿄만의 고층 건물 화재를 배경으로 한 15초 live-action 다큐멘터리 스타일 영상입니다. BGM 없음. 자막 없음. 환경음만...

출처: [게시물](https://x.com/kuranoayashi/status/2040055299835650266) · 게시일: 03 Apr 2026

```text
Modern Japan. A 15-second live-action documentary-style video set during a high-rise building fire in Tokyo Bay. 
No BGM. No subtitles. Only environmental sounds, radio, wind, fire, and people's voices from the scene.
---
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 76
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
0-5초: 깊게 몸을 숙인 공기역학 자세의 여성 다운힐 롱보더를 따라가는 dynamic low-angle tracking shot입니다. 급경사 산길을 질주하며 눈부시고 강렬한...

출처: [게시물](https://x.com/Dheepanratnam/status/2039982273076810119) · 게시일: 03 Apr 2026

```text
[0-5s] Dynamic low-angle tracking shot pacing a female downhill longboarder in a deep aerodynamic tuck speeding down a steep mountain pass. Blinding, intense directional sunlight hits her profile, generating stark, elongated, pitch-black shadows onto the sheer, rough-hewn ancient stone cliff walls to her right. The atmosphere is adrenaline-fueled with high-contrast, dramatic lighting. 

[5-10s] The camera smoothly tilts up and racks focus entirely to the cliff face, filling the frame with her razor-sharp shadow mimicking her fluid slalom carves across the weathered, pitted limestone architecture, creating a mesmerizing optical illusion of a dark silhouette dancing along the ancient masonry. 

[10-15s] A rapid whip-pan and macro snap-zoom abruptly shifts the camera down to street level for an ultra-realistic extreme close-up of the longboard's vibrant polyurethane wheels executing a heavy sideways drift. Thick, volumetric white friction smoke billows from the wheels as they violently grind against the highly textured, sun-baked granular black asphalt, highlighting raw kinetic energy and photorealistic surface materiality.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## POV / FPV

카메라의 운동감을 중심으로 설계된 1인칭, drone-like, body-mounted, 몰입 우선 프롬프트입니다.

### 가슴 장착형 위장 추격 시퀀스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
hyper-realistic 8K 해상도의 아드레날린 넘치는 single-take POV 액션 시퀀스입니다. 카메라는 camouflage 조거 팬츠를 입은 남성의 가슴에 장착되어...

출처: [게시물](https://x.com/genel_ai/status/2039538309790404797) · 게시일: 02 Apr 2026

```text
A hyper-realistic, 8K resolution, adrenaline-fueled single-take POV action sequence. The camera is chest-mounted on a man wearing camouflage joggers and worn-out black-and-white sneakers. He stands on the dizzying edge of a rusted skyscraper, 1000 feet above a crystalline turquoise ocean. No clouds, no haze—just a sheer, terrifying vertical drop into the deep blue.
[The Initial Freefall]
The sequence begins with a sudden, heart-stopping leap into a 20-meter vertical freefall. The camera points directly at his feet as the sea surface rushes toward the lens. A deafening, high-pitched whistling 'Hyuo' wind screams past the microphone. Just before the impact, he catches a lower rusted horizontal bar with both hands—white wristband visible—and swings his body forward to land on a tiny vertical pole.
[The Rhythmic Jumps & The Near-Death Slip]
He immediately begins a rhythmic series of high-speed jumps:
Jump 1: A clean, agile spring to a second vertical pole 2 meters away.
Jump 2: A rapid leap to a thin, rusted horizontal pipe.
Jump 3 (The Slip): As he jumps toward the third vertical pole, his right sneaker completely misses the mark and slides off the rusted metal. The camera tilts violently over the edge, staring straight down at the 1000-foot abyss. He lets out a sharp, panicked gasp. For a terrifying second, his body leans into the void, but he desperately claws at the pole with his fingers, his boots scrambling against the side until he manages to hook his leg and haul himself back up.
Jump 4: Still trembling, he forces a frantic, heavy-breathing leap to the next bar to keep the momentum.
Jump 5: A final, explosive long-distance jump to a swaying metal platform. He lands with a heavy, jarring metallic 'Clang', his body hunching low, gripping the vibrating metal for dear life.
[The Ending]
The camera remains in a low, fetal position on the final bar, shaking from the adrenaline. No dialogue. The audio is a visceral layer of the aggressive 'Hyuo' wind, his intense, ragg
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 상하이 사이버펑크 시티 시즐 릴
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
cyberpunk 에너지, FPV 움직임, 음식 macro shot, 상업적 polished 감각을 결합한 프리미엄 상하이 시티 몽타주입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039498800801398911) · 게시일: 02 Apr 2026

```text
You can try this:

A 15-second Hollywood-level Shanghai city fast-cut video. Style: a fusion of cyberpunk and modern Haipai aesthetics, cinematic teal-and-orange color grading, 8K ultra-HD.
Shot sequence:
1. The Lujiazui skyline trio cuts through dawn clouds and mist in a dramatic helicopter dive shot.
2. The camera rapidly pushes toward the Bund's historic buildings, revealing detailed stone textures.
3. An FPV craft races through neon-lit night streets and sweeps past the Oriental Pearl Tower.
4. Timelapse of the spiral approach bridge of Nanpu Bridge, with golden car-light trails converging into rings.
5. An aerial shot glides smoothly past the Wukang Building beneath plane-tree shadows.
6. Macro close-up: a steaming basket of Nanxiang soup dumplings is lifted by chopsticks, the broth trembling inside.
7. High-speed montage flashback: Shikumen alleyways, the maglev train, Yuyuan traditional architecture, and the modern skyline flash by rapidly.
Requirements: extremely dynamic camera movement, FPV aerial motion, macro cinematography, and silky transitions.
Mood: energetic, futuristic, premium, fast-paced. Combine wide city views with fine details to emphasize the city's pulse and a commercial-advertising texture. 4K, realistic style, smooth motion.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 저주받은 사무라이 일관성 액션 프롬프트
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
레퍼런스 캐릭터의 얼굴, 헤어스타일, 의상 실루엣, 신체 비율을 엄격히 따라야 합니다. 정체성이나 얼굴 구조를 바꾸면 안 됩니다. 고정된...

출처: [게시물](https://x.com/Just_sharon7/status/2040685931858907646) · 게시일: 05 Apr 2026

```text
Strictly follow the reference character’s face, hairstyle, outfit silhouette, and body proportions. Do not change identity or facial structure. Fixed appearance: glowing dark eyes, torn black samurai kimono, traditional katana, black cursed smoke slowly leaking from the body, flowing shadow energy aura, calm but cruel expression, supernatural high-speed movement, consistent identity and physical appearance throughout the entire scene. Strictly follow the reference character’s face, hairstyle, outfit silhouette, and body proportions. Do not change identity or facial structure. Fixed appearance: glowing dark eyes, torn black samurai kimono, traditional katana, black cursed smoke slowly leaking from the body, flowing shadow energy aura, calm but cruel expression, supernatural high-speed movement, consistent identity and physical appearance throughout the entire scene. Hyper-realistic cinematic action, Unreal Engine quality, fast-paced 12s sequence. Cursed lone samurai (strict consistency: female Japanese, long tied black hair, pale skin, glowing dark eyes, torn black kimono armor, katana, black cursed smoke, shadow aura, calm ruthless expression). Environment: abandoned temple shrine at night, broken torii gates, shattered statues, debris, moonlight + dim lanterns, dust and wind, dozens of enemies, dark gritty tone. Camera: aggressive tracking, whip pans, blade POV, high-speed motion, no slow motion. Action: 0–3s: Samurai stands surrounded → instant iaijutsu draw → dark energy slash cuts multiple enemies. 3–6s: High-speed dashes, shadow afterimages, rapid slashes, enemies fall, debris flying. 6–9s: Close combat, parries, teleport-like strikes, circular slashes clearing groups. 9–12s: Final spinning slash → massive dark wave → enemies freeze then collapse → silence, smoke fading.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 손오공 전장 신성 구출
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
시네마틱하고 hyper-dynamic한 빠른 multi-shot 시퀀스로, 서사적인 신화 전장, IMAX 필름 시뮬레이션, 35mm Panavision 렌즈, f/4, 강한 시네마틱...

출처: [게시물](https://x.com/drjoetw/status/2040661051948323129) · 게시일: 05 Apr 2026

```text
Cinematic hyper-dynamic fast-paced multi-shot sequence, epic mythological battlefield, IMAX film simulation, 35mm Panavision lens, f/4, heavy cinematic color grading, dramatic contrast between dark necrotic tones and radiant golden divine light.
Shot 1: Extreme close-up on Sun Wukong’s face, covered in dirt and blood, golden eyes flickering with exhaustion yet defiance. His fur is matted, his breathing heavy. He kneels in the center of a ruined battlefield, his golden staff cracked and planted into the ground for support. Around him, countless skeletal warriors slowly close in, their hollow eyes glowing with eerie green fire.
Shot 2: Rapid shaky handheld shot circling Wukong. The skeletal army tightens its formation, bones clattering, rusted weapons scraping. Wukong struggles to stand, gripping his staff, as the undead swarm prepares to strike from all directions.
Shot 3: Low-angle shot from behind Wukong. Just as the skeletons lunge forward, a faint golden glow begins to emerge behind him, cutting through the darkness like dawn breaking through a storm.
Shot 4: Sudden explosive bloom of radiant golden light. A towering Buddha manifestation appears behind Wukong, विशाल and serene, radiating infinite divine energy. The battlefield is instantly bathed in warm, overwhelming golden luminosity.
Shot 5: Fast upward tilt. Rows upon rows of celestial soldiers materialize in the sky and on the ground behind the Buddha—heavenly generals clad in ornate golden armor, divine banners flowing, weapons shining with sacred light.
Shot 6: Whip-pan across the battlefield. The skeletons freeze mid-attack, their bodies trembling under the pressure of the divine aura. Golden light surges outward like a tidal wave.
Shot 7: Ultra-fast sequence of disintegration shots. The skeletal army is instantly reduced to ash—bones crack, dissolve, and scatter into glowing dust, evaporating into nothingness under the overwhelming holy radiance.
Shot 8: Wide epic drone pull-back. Wukong stands silhouett
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### Y2K 풀파티 캠코더 몽타주
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
MiniDV 질감, 장난기 있는 party 비트, 빠르고 향수를 자극하는 몽타주 에너지를 담은 Y2K 풀파티 캠코더 시퀀스입니다.

출처: [게시물](https://x.com/johnAGI168/status/2040628800422322359) · 게시일: 05 Apr 2026

```text
[Style] Millennium retro pool party (Y2K Pool Party), MiniDV camcorder texture, overexposed warm yellow highlights, film grain, VHS interference lines, fast beat-synced editing.
[Duration] 15 seconds.
[Scene] A 2000s American backyard pool party under blazing sun, with glaring light reflections on the water, folding lounge chairs, a silver CD player, rainbow inflatable floats, and a plastic whale.
[Characters] A group of Y2K-styled girls: low-rise bikinis, belly chains, colorful plastic sunglasses, butterfly clips, and glossy glitter lips.
[00:00-00:01.5] Shot 1: explosive water emergence (Close-up / Pullback)
A DV startup blue screen flashes with a red REC dot. Extreme face close-up: a girl wearing colorful plastic sunglasses bursts up from underwater, flipping wet hair into an arc of water in slow motion. Water droplets splash onto the lens. She laughs straight into the DV camera as the sunlight blows out to pure white.
[00:01.5-00:03] Shot 2: poolside parade (Low Angle / Right Pan)
A low waist-height right pan tracks three girls in sheer cover-ups walking across wet tiles holding canned drinks. One of them takes a selfie with a flip phone. Thick platform flip-flops slap against the ground.
[00:03-00:04.5] Shot 3: push into the pool (Dutch Angle)
Dutch-angle medium shot. One girl shoves her friend into the pool from behind. A soda can flies out, the body crashes into the water, spray explodes everywhere, and the girl who pushed her bends over laughing.
[00:04.5-00:06] Shot 4: FPV dive (FPV Drone Dive)
An FPV shot dives from above, skimming over the water. The girls lie sunbathing on floats. Someone raises a disposable camera and flashes directly into the lens.
[00:06-00:07] Shot 5: ice into the cup (Macro / Still)
Macro static shot. Ice cubes drop into a plastic cup, orange liquid splashes upward, and the hand holding the cup wears colorful rubber bracelets. Sunlight passes through the liquid and casts caustic light patterns.
[00:07-00:08.5] Shot 6: dance follow shot (Tracking / Backward Follow)
The camera tracks backward while locking onto the face. A girl with wet hair stuck to her cheeks and butterfly clips dances through the crowd in a woven bikini. Her hoop earrings swing as she smiles straight at the lens.
[00:08.5-00:10] Shot 7: diving silhouette (Worm's Eye / Push-in)
A worm's-eye push-in captures a girl launching from the diving board as a silhouette. The sun bursts into lens flare, and water droplets turn into points of light in the air.
[00:10-00:11.5] Shot 8: cheers (Close-up / Left Pan)
Fast left pan. Two girls clink red plastic cups together, liquid splashing out in golden arcs while they squint and laugh.
[00:11.5-00:13] Shot 9: DJ over-shoulder (OTS / Pull-in)
Push in from behind the DJ's shoulder. In the foreground, fingers press the silver CD player's button. In the background, the girls splash water wildly in rhythm, and the backlit spray becomes a curtain of golden rain.
[00:13-00:15] Shot 10: golden wide freeze frame (Extreme Wide / Crane Rise)
A rapid crane rise opens the entire pool party in golden-hour warm light, full of people and inflatable toys, with the water shimmering like broken gold. Overlay a DV timestamp reading "08/15/2000 PM 5:47" and freeze the frame with a flickering VHS pause effect.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 40
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
시네마틱 CG 광고 퀄리티의 ultra-realistic 1인칭 POV로, 고속 원테이크 카메라 움직임과 강한 시각적 임팩트를 담습니다. 카메라는 내부에서 튀어나오며...

출처: [게시물](https://x.com/xingsthatmatter/status/2040190310043812035) · 게시일: 03 Apr 2026

```text
Cinematic CG ad quality, ultra-realistic, first-person POV, high-speed one-take camera movement, strong visual impact.

The camera bursts out from inside image1, the Tesla card, as the card spins forward at high speed. The camera stays tight to its edge, tracking it through city
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 43
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
안개 자욱한 중세 전장을 향해 돌진하는 1인칭 POV 승마 샷입니다. 화면 아래에는 말의 검은 갈기와 귀가 보이고...

출처: [게시물](https://x.com/simple__dev/status/2039935077912826240) · 게시일: 03 Apr 2026

```text
"First-person POV horseback riding shot charging across a misty, fog-covered medieval battlefield. The horse's black mane and ears are visible at the bottom of frame as the rider gallops forward. Fallen soldiers lie on the muddy grass. Cavalry riders on horseback emerge from the dense fog on all sides. A mounted knight in chainmail armor swings an axe directly at the camera. Dark, desaturated color palette, overcast grey sky, gritty medieval war film aesthetic reminiscent of epic battle sequences. Handheld camera movement with natural motion blur."
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 익스트림 클로즈업
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
과장된 시네마틱 긴장감과 코믹한 payoff가 있는 매우 극적인 fast-cut anime MV입니다. 1930년대 도쿄 논, 진흙 질감, 폭풍우 치는 하늘, extreme...

출처: [게시물](https://x.com/drjoetw/status/2040036596897222773) · 게시일: 03 Apr 2026

```text
A highly dramatic, fast-cut anime MV with exaggerated cinematic tension and comedic payoff. 1930s Tokyo rice paddies, muddy textures, stormy sky. Extreme sense of falling urgency using rapid cuts, POV distortion, speed ramps, spinning camera, impact zooms. Dramatic orchestral music escalating non-stop, then sudden comedic release at the end. No dialogue, no voice-over. Each shot 0.6–1.2s.

0–0.8s (HOOK)
Extreme close-up: muddy water surface. Ripple expands → reflection shows a white tiger falling from the sky at insane speed.

0.8–1.6s
SMASH CUT → tiger tumbling mid-air, body spinning violently, wind tearing fur.

1.6–2.4s
POV tiger → ground rushing upward extremely fast. Rice paddies distort with speed.

2.4–3.2s
Cut → orange cat in muddy farmer clothes, calmly planting rice. Slow, peaceful motion.

3.2–4.0s
Back to tiger → extreme close-up eyes, panic rising. Sunglasses slightly slipping.

4.0–4.8s
Rapid micro-cuts: sky spin → ground zoom → cat step → sky spin → distance collapsing fast.

4.8–5.6s
Top-down shot → tiger perfectly aligned to crash into orange cat.

5.6–6.4s
Tiger yanks parachute → explosive deploy → instant violent spinning chaos.

6.4–7.2s
Camera rotates 360° with tiger. Horizon flips. Ground now dangerously close.

7.2–8.0s
Parachute unstable → cords under extreme tension. Tiger loses control completely.

8.0–8.8s
Tiger panic peaks → aggressively twists cords into a tight yarn-ball knot.

8.8–9.6s
Parachute collapses → freefall speed doubles. Sound compresses into heartbeat rhythm.

9.6–10.4s
Ultra-fast dive shot → motion blur streaks. Orange cat grows rapidly in frame.

10.4–11.2s
Cut → cat finally senses something. Slight head turn.

11.2–12.0s (IMPACT BUILD)
Extreme close-up: tiger face in silent scream → smash zoom toward ground.

12.0–12.8s (IMPACT)
Massive muddy explosion. Water and mud burst upward in slow motion.

12.8–13.6s
Mud rain falls. Silence. Shapes slowly appear through the splash.

13.6–14.2s (REVEAL)
White tiger sitting on top of the orange cat’s back, slightly dazed but intact.

14.2–15.0s (COMEDIC PAYOFF)
Close-up: orange cat’s face, completely covered in mud, eyes half-open, extremely annoyed.
White tiger casually adjusts sunglasses while sitting on him.
Freeze frame → dramatic music abruptly cuts.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 빠르고 심리스한 16
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
서로 연결된 다섯 개의 샷으로 빠르고 심리스한 16:9 비행 POV 시퀀스를 구성합니다. Shot 1: 멀리 나무문이 보이는 어두운 고대 석조 복도 내부에서 시작해...

출처: [게시물](https://x.com/aisavvy1/status/2040054688054382972) · 게시일: 03 Apr 2026

```text
Create a fast, seamless 16:9 flying POV sequence with five linked shots.
Shot 1: Start inside a dark ancient stone corridor with a wooden door at the far end. Fly straight toward it at high speed. As the camera reaches the door, it begins to swing open, revealing a gap of bright blue ocean behind it. End mid-opening.
Shot 2: Continue through the opening door into the ocean. Fly forward through fish, bubbles, light rays, and underwater plants. A giant fish approaches and opens its mouth directly in front of the camera. End inside its mouth.
Shot 3: The darkness inside the fish’s mouth becomes the dark interior of a large stainless steel kitchen hood or service opening. Fly forward into a busy high-end restaurant kitchen with chefs, flames, steam, pans, and plated dishes. Fly low over the counter. End with the glowing opening of a large industrial oven filling the frame.
Shot 4: Continue into the glowing oven as it transforms into a volcanic lava tunnel with molten light and black rock. Fly through the tunnel. End with a bright circular stone opening filling the frame.
Shot 5: Continue through the circular opening into a Mediterranean cliffside village above the sea. Fly fast between terraces, rooftops, arches, and sunlit walls toward the ocean. End with a wide sea-facing reveal.
Fast, smooth, continuous movement. No flying device, shadow, or reflection. Cinematic.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 환경
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
환경: 해질녘 포위 공격을 받는 거대한 중세 판타지 도시. 돌 탑, 대성당 첨탑, 좁은 골목이 지평선까지 뻗고, 불길이...

출처: [게시물](https://x.com/LudovicCreator/status/2039983776206344231) · 게시일: 03 Apr 2026

```text
**Environment:**

A massive medieval-fantasy city under siege at dusk. Stone towers, cathedral spires, and narrow streets stretch toward the horizon while fire spreads through rooftops and smoke rises into the orange evening sky. Wind currents swirl between the tall buildings.

**Action:**

15.0s sequence from the first-person perspective of a colossal dragon in flight. The viewer sees the edges of scaled wings occasionally entering frame as the dragon glides between towers. Heat shimmer ripples from its throat with every breath.

At the 2-second mark the dragon dives sharply between two cathedral spires.

Stone gargoyles and stained-glass windows rush past at extreme speed.

The dragon unleashes a stream of fire across a city wall below, igniting entire streets.

Velocity Ramp choreography: the moment the dragon pulls up from the dive slows dramatically — embers, sparks, and falling debris suspended in mid-air — before snapping back as the dragon bursts through a collapsing tower.

**Camera:**

Fast aerial predator POV weaving through the skyline, banking sharply between towers and rooftops.

**Style & Constraints:**

Photorealistic fire simulation, volumetric smoke, cinematic sunset lighting, realistic wing turbulence and debris physics, 8K resolution.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 탄산음료 컵 속으로 떨어지는 얼음 조각의 1인칭 POV
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
탄산음료 컵 속으로 떨어지는 얼음 조각의 1인칭 POV입니다. 얼음 조각은 거품 이는 탄산 액체의 바다로 추락하고, 거대한 기포가 마치...

출처: [게시물](https://x.com/LudovicCreator/status/2039623813080416486) · 게시일: 02 Apr 2026

```text
First-person POV of an ice cube dropped into a glass of soda.

The cube crashes into a bubbling ocean of carbonated liquid.

Gigantic bubbles rise like balloons around the cube.

A lemon slice floats overhead like a glowing sun.

The ice cube slowly melts as the drink level lowers.

Finally the cube slides toward a straw vortex and disappears.

Macro drink environment POV, carbonation bubble storms, melting ice transformation, cinematic macro realism, 4K.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 거칠고 날것의 handheld 35mm 필름 미학과 자연스러운 필름 그레인
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
자연스러운 필름 grain이 살아 있는 거칠고 날것의 handheld 35mm 필름 미학입니다. 이른 아침의 밝은 햇빛이 창문을 통해 들어와 실내에 날카로운 그림자를 만들고...

출처: [게시물](https://x.com/AngelNwoha/status/2039792884841591009) · 게시일: 02 Apr 2026

```text
Gritty, raw handheld 35mm film aesthetic with natural film grain. Bright early-morning sunlight streaming through windows, creating sharp indoor shadows. Controlled handheld tracking shot (3rd person POV, over-the-shoulder), stabilized cinematic motion with subtle natural shake.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 10초 photorealistic 시네마틱 POV 비디오
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
10초 분량의 photorealistic 시네마틱 POV 비디오입니다. 검은 짧은 보브 헤어, 곧은 머리, 자연스럽고 세련된 메이크업을 한 20대 초반의 일본인 여성이 등장하고...

출처: [게시물](https://x.com/umitsuru_fire/status/2039295650039554051) · 게시일: 01 Apr 2026

```text
10-second photorealistic cinematic POV video. A Japanese woman in her early 20s with a black short bob hairstyle, straight hair, natural refined makeup, and a white blouse sits inside a Ferris wheel gondola at night near the top. Outside the window is a beautiful city nightscape
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 종말 이후의 초미래 메가시티가 폭풍 속에서 깨어난다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
종말 이후의 초미래 메가시티가 폭풍 속에서 깨어납니다. 검은 구름이 도시를 짓누르고, 거대한 전함이 하늘에서 천천히 내려옵니다,...

출처: [게시물](https://x.com/johnAGI168/status/2039380975801471305) · 게시일: 01 Apr 2026

```text
A super futuristic megacity after the apocalypse awakens in a storm. Dark clouds press down on the city. Giant battleships slowly descend from the sky, piercing through thunderclouds. The city's high-rise buildings are interwoven with neon lights and fire. Countless drones and armored vehicles shuttle rapidly through the streets. A distant energy tower erupts with dazzling blue electric arcs. The camera dives from high altitude into the city canyon, then rapidly pushes through falling debris and flames, finally settling on the back of a lonely hero wearing a black trench coat, standing on the edge of a skyscraper overlooking the entire burning city. Cinematic lighting, IMAX epic feel, ultra-high detail, stunning composition, strong volumetric light, realistic explosion smoke and dust, epic disaster movie atmosphere, extreme realism, top Hollywood visual effects.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 스타일: Ultra-realistic 산업 timelapse
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
스타일: Ultra-realistic 산업 timelapse, 페이싱: 매우 빠름(hyperlapse 느낌), 카메라: 약간의 시네마틱 움직임이 있는 대부분 고정 구도(slider/drone 느낌)...

출처: [게시물](https://x.com/craftian_keskin/status/2039415621960499603) · 게시일: 01 Apr 2026

```text
Style: Ultra-realistic industrial timelapse
Pacing: Extremely fast (hyperlapse feel)
Camera: Mostly fixed with slight cinematic motion (slider/drone feel)
Lighting: Bright factory lights, metallic reflections
Audio: Captivating cinematic electronic/industrial music (no dialogue)

[00:00–00:03] — Bare Frame

Shot 1 (wide, static)

Empty car chassis suspended on assembly line
Conveyor begins moving

Workers enter frame rapidly (timelapse speed)
Tools flashing, sparks briefly

[00:03–00:06] — Structure Builds

Shot 2 (slight side angle)

Doors, internal components appear quickly
Technicians blur in motion

Robotic arms assisting (fast, precise movements)
Parts snapping into place rapidly

[00:06–00:09] — Complexity Grows

Shot 3 (closer view)

Wiring, dashboard, engine components installed

Hands moving at hyper speed
Panels closing, interior forming

[00:09–00:12] — Exterior Completion

Shot 4 (dynamic angle)

Body panels attach
Wheels snap into place

Car begins to look complete
Motion blur emphasizes speed

[00:12–00:15] — Final Form

Shot 5 (hero shot)

Fully assembled car rolls forward

Lights flick on
Clean, finished vehicle

End moment:

Camera holds briefly as car exits frame
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 116
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
시네마틱한 하드 액션 블록버스터 영화 스타일입니다. 해질녘 일본 도심의 붕괴된 대로에서 거대한 몬스터가 건물을 무너뜨리고, 먼지와 불꽃이 튀며...

출처: [게시물](https://x.com/Yuupapa_free/status/2039329682492121547) · 게시일: 01 Apr 2026

```text
cinematic, heavy action blockbuster film, Japanese city center, collapsed main street at dusk. A giant monster is knocking down buildings, dust, sparks, rubble, and black smoke are flying, and a Japanese high school girl in a uniform is desperately running towards the camera. Cut 1 (0.0s-2.5s): low angle tracking shot following the high school girl from the front as she retreats. Her hair and skirt are violently fluttering, the ground shakes from the monster's footsteps behind her, cars overturn, and window glass shatters. Her face shows determination amidst fear. Cut 2 (2.5s-3.7s): close-up of her feet. With every step she runs, black metal frames and pink glowing lines deploy onto her legs, rapidly equipping from her thighs to her shins and boots. Sparks and fine energy particles, mechanical transformation. Cut 3 (3.7s-4.8s): close-up of her hands. As she swings her arms, armor forms around her forearms, wrists, and fingertips, with pink light strips running through the gaps in the black armor. Cut 4 (4.8s-6.0s): close-up of her abdomen and chest. Abdominal inner wear, chest armor, and shoulder units lock sequentially, and the central core pulses pink with her breathing. Rack focus shows the detail of the armor. Cut 5 (6.0s-7.0s): close-up of her head. As her hair flies, a helmet deploys from the sides and back, enveloping her face line, and finally the visor closes while glowing. eyes visible through translucent visor. whip pan completes the transformation. Cut 6 (7.0s-8.8s): wide shot. After running a few steps at high speed, the transformed girl skids to a halt, scattering sparks and fragments, twists her body, and faces the monster. She thrusts one hand forward, and a pink spherical energy vortex converges on the device on the back of her hand, drawing in surrounding rubble. Cut 7 (8.8s-10.5s): over-the-shoulder shot capturing the monster, and she silently fires an energy blast all at once. A thick pink shockwave runs straight through, piercing the monster's chest. Cut 8 (10.5s-12.0s): super large explosion. The monster is blown to smithereens, fragments and smoke fly into the sky, and the giant body collapses. The final shot is a hero shot, the high school girl in a black and pink powered suit standing with the explosion behind her. dramatic backlight, debris, heat haze, high contrast, realistic destruction, dynamic motion blur, no BGM, no dialogue
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 상업 / 제품

광고, 패션, 라이프스타일, 제품, 프리미엄 브랜드 스타일 프롬프트입니다.

### Perfume 스타일 anime 트리오 댄스 스테이지
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
기계적인 정밀함, 빠른 컷, 청보라 concert 조명으로 구동되는 sync형 anime idol 댄스 스테이지 프롬프트입니다.

출처: [게시물](https://x.com/ShadeLurk/status/2040671186984796632) · 게시일: 05 Apr 2026

```text
PR [Topview]
#TopviewAI #Seedance2
Dance

prompt:
Three anime girls perform Perfume-style formation dance on an illuminated stage. Each girl performs different assigned choreography, but all movements are locked to the exact same beat with mechanical precision. The camera cuts rapidly between full shots and medium shots every 0.7-1.0 seconds, occasionally switching to side angles and overhead angles. The structure follows a call-and-response pattern between the three dancers. The choreography ranges from sharp upright arm work to low crouching floor sweeps. Blue-white spotlights carve through purple haze. LED panels pulse with blue-to-purple gradients. Triangular formation.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 다크 판타지 교회 결투
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
오리지널 다크 판타지 액션 단편: 허물어진 교회 안에서 흰옷의 전사와 검은 갑주의 상대가 최후의 전투를 벌입니다...

출처: [게시물](https://x.com/ZaraIrahh/status/2040667542390190245) · 게시일: 05 Apr 2026

```text
Original Dark Fantasy Action Short Film: Inside a dilapidated church, a white-clad warrior and a black-armored opponent launch their final battle amid an atmosphere like a chorus. Stained glass shatters, moonlight penetrates the smoke and dust, and benches are overturned. The camera switches between high-angle overhead shots and low-angle upward shots, focusing on showing the sense of space of the religious building, the sense of oppression of the characters, and the temperament of a fateful decisive battle, just like the climax segment of an original fantasy animated film. A strong hook in the first 2 seconds, stable main body, coherent actions, movie-level composition, real light and shadow, epic sense, strong emotion, high-definition details, suitable for social media communication, avoiding copyrighted characters, avoiding brand logos, and completely original design.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 다크 판타지 신사 전각 결투
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
오리지널 일본풍 다크 판타지 액션 단편: 낡은 신사 전각 안에서 흰 로브의 전사와 검은 갑주의 사무라이가 맞붙습니다...

출처: [게시물](https://x.com/MiraMusic_AI/status/2040595365096034700) · 게시일: 05 Apr 2026

```text
Original Japanese-Style Dark Fantasy Action Short Film:
Inside a dilapidated shrine hall, a white-robed warrior and a black-armored samurai engage in their final battle amid an atmosphere reminiscent of ritual chanting. Wooden beams creak, paper screens tear apart, and fragments scatter as moonlight filters through drifting dust and smoke. Tatami mats are disrupted and scattered across the floor.
The camera alternates between high-angle overhead shots and low-angle upward perspectives, emphasizing the spatial depth of traditional Japanese architecture, the oppressive tension surrounding the characters, and the solemn intensity of a fateful duel—evoking the climactic moment of an original Japanese fantasy animated film.
A strong hook within the first 2 seconds, followed by a stable and cohesive progression. Fluid, continuous action with cinematic composition, realistic lighting and shadow, an epic atmosphere, intense emotional weight, and high-definition detail. Designed for social media engagement. Avoids copyrighted characters and brand logos, ensuring a completely original creation.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 일본 과자 광고 펀치라인
![Language-JA](https://img.shields.io/badge/Language-JA-blue?style=flat-square)
다음은 15초 분량의 일본 과자 광고입니다. Shot 1 (3s): 한 남자가 상점가를 걷습니다. 그가 지나가자 두 주부가 "다 떨어졌대"라고 속삭입니다...

출처: [게시물](https://x.com/aigeboku/status/2040562471027782017) · 게시일: 04 Apr 2026

```text
Here it is.

A 15-second Japanese snack commercial.
Shot 1 (3s): A man walks through a shopping street. As he passes, two housewives whisper, "It's out."
Shot 2 (3s): The man turns around, slightly concerned by the two women, and an old man holding a newspaper says, "Is it out?"
Shot 3 (3s): Slightly flustered, the man looks at his smartphone, and a YouTube influencer says, "It's out!"
Shot 4 (3s): The man rushes into a Japanese convenience store. The clerk says, "It's out!" while holding the new snack package used in Shot 5.
Shot 5 (3s): Close-up of the new snack package. Narration: "It's out! New release!"
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### Seedance 2용 시네마틱 무술 시퀀스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Seedance 2용 시네마틱 무술 시퀀스 프롬프트로, 대낮에 어두운 stylized 복장을 입은 맹인 shaolin monk가 벌이는 무술 대결을 다룹니다...

출처: [게시물](https://x.com/CharaspowerAI/status/2040376349504815467) · 게시일: 04 Apr 2026

```text
Cinematic Martial Art Sequence for Seedance 2
PROMPT
cinematic martial arts confrontation in broad daylight, a blind shaolin monk wearing a dark, stylized combat outfit inspired by legendary fighters stands calm and centered, eyes closed, surrounded by multiple hostile creatures emerging from a traditional Japanese landscape
Ultra cinematic choreography coverage, mix of slow dolly-ins + orbit moves + whip pans, transitions masked by body motion and impacts, alternating real-time and slow motion, continuous fluid sequence
(0-2s) wide establishing shot, monk standing still in center, wind moving fabric, creatures circling, tension builds
(2-4s) slow push-in close-up on monk’s face, eyes closed, subtle head tilt sensing movement
(4-6s) sudden attack from first creature, monk reacts instantly, precise sidestep + redirection, fluid motion
(6-8s) chained combat sequence, monk engages multiple opponents, spinning strikes, controlled movements, each impact sending creatures flying backward with stylized motion
(8-10s) slow motion highlight: mid-air dodge + counter sequence, cloth movement and body rotation emphasized, creatures suspended briefly before being thrown away
(10-12s) final burst of speed, monk flows through remaining opponents in one continuous movement, camera orbiting rapidly, enemies collapsing or being thrown aside
Traditional Japanese environment, open landscape with temples, wooden structures, distant mountains, clear daylight, subtle wind movement, dust and debris reacting to motion
Ultra realistic, high-end martial arts film choreography, precise body mechanics, cinematic slow motion, strong contrast lighting, volumetric atmosphere, fluid transitions, intense but controlled physical interaction, no distortion, no stretching
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### Grok에게 같은 영상을 만들게 했지만 결과는 설득력이 없었다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Grok에게 같은 영상을 만들게 했지만 결과는 설득력이 없었습니다. Grok의 렌더링에는 어떤 "리얼리즘"이 부족합니다. Seedance 2.0은 단연 최고의 비디오...

출처: [게시물](https://x.com/Viafin23/status/2025901411221774788) · 게시일: 23 Feb 2026

```text
I asked Grok to produce the same video, but the result wasn't convincing. Grok's rendering lacks a certain "realism."
Seedance 2.0 is by far the best video generator.
💡PROMPT:
Ultra-realistic cinematic sequence of a golden eagle launching from a rocky cliff at dawn, wings extending with visible feather separation and aerodynamic drag. The bird glides forward, banking left to avoid a suspended construction crane cable, then sharply ascends to clear a rooftop antenna array. Subtle wing flex under air resistance, primary feathers bending independently with realistic airflow interaction. Breath vapor faintly visible in cold morning air during close pass.
Camera tracks parallel at mid-distance using a stabilized aerial rig, slight natural vibration from wind turbulence. Background reveals a dense urban skyline with morning haze diffusion and directional sunlight from low east angle casting elongated shadows across glass facades. Wind displaces loose dust and paper debris across rooftops as the eagle’s downdraft interacts with the environment.
The eagle approaches a modern concrete high-rise rooftop. Momentum gradually decreases through controlled wing beats, talons extending forward with visible muscle tension and micro-adjustments for balance. It lands firmly on a large metallic rooftop sign reading “Ambition.” Talons grip the metal surface causing slight vibration and audible metallic resonance. Body weight shifts forward then stabilizes. Feathers settle naturally. The eagle scans the horizon with subtle head micro-movements and blinking.
Maintain stable temporal continuity. Avoid unnatural frame interpolation. No exaggerated slow motion. Real-world physics, accurate weight transfer, authentic bird anatomy, environmental reaction to force.
#Seedance2_0
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 일본 교실 속 속삭임 로맨스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 분량의 시네마틱 일본 드라마풍 순애·썸 분위기 단편으로, 초현실적 품질과 오후 텅 빈 교실의 따뜻한 황금빛 햇살이 특징입니다,...

출처: [게시물](https://x.com/JiahaoYang_art/status/2033119940216344616) · 게시일: 15 Mar 2026

```text
15-second cinematic Japanese drama pure love ambiguous short film, ultra-realistic quality, warm golden sunlight in an empty classroom in the afternoon, spilling through the blinds onto the side-by-side desks, fine dust motes slowly floating in the light beams, old wooden desks, extremely natural subtle movements, breathing, and eye tension, characters maintain consistent faces, clothing, and hairstyles throughout without deformation, drift, or artifacts, real slight chest rise and fall synchronized with breathing, shallow depth of field, creamy blurred background, warm film grain, 8K sharp, Japanese youth restrained heart-fluttering suffocating atmosphere.
0-4 seconds: Extremely slow push-in shot from a medium shot of the desktop to a close-up of the two people's side profiles sitting side-by-side. A pure girl in a summer school uniform is focused on writing notes with her head down, long black hair and stray hairs by her ears are gently lifted by a slight breeze, long eyelashes cast subtle shadows, skin is naturally pink and tender, a slight, unintentional upturn of the corner of her mouth in concentration, light and even breathing.
4-9 seconds: Switch to a close-up of the boy. His school uniform collar is slightly loose, he props his elbow on the desk and secretly turns his head to gaze at her, his eyes filled with gentle, restrained affection and tenderness, pupils slightly dilated, his Adam's apple gently rolls. Suddenly noticing her pen pause, he quickly and flusteredly turns his head to pretend to look at his own notes, his earlobes quickly turn slightly red, his fingertips tremble slightly as he grips the pen, occasionally glancing at her from under his bangs, his breathing is slightly disordered, and his lips are tightly pressed in an effort to remain calm.
9-15 seconds: Extreme close-up of both faces in the same frame, slow-motion eyes suddenly meet: the girl slowly turns her head, first showing a dazed surprise, then quickly and shyly lowers her head for 0.3 seconds, gently biting her lower lip, her cheeks and earlobes instantly bloom with cherry blossom pink, her moist eyelashes timidly look up to meet his gaze again, while softly and shyly whispering, "...What are you looking at?"; the boy freezes completely, his pupils dilate, and he is stunned for 0.4 seconds, then flusteredly and quietly stutters in response, "N-nothing...". The girl whispers even quieter, biting her lip and peeking at him again, continuing to whisper, "...Liar.". The boy pauses, then gently sighs and whispers, "...Just looking at you.", the corner of his mouth slowly curls up into a shy, gentle, crooked smile, fine lines appear at the corners of his eyes, and his breathing noticeably deepens. An invisible current seems to pull the ambiguous tension between their faces, sharing each other's breathing temperature, the background completely melts into layers of creamy, dreamy light spots, warm halos, and fine air particles.
Lip synchronization is natural and precise, emotional micro-tremors and breathing are synchronized, dialogue is low-energy whispering with a shy tone, natural short pauses between 200-400 milliseconds, the mouth only moves slightly when speaking, without exaggeration or robotic feel, perfect natural lip-sync and emotional authenticity.
Overall Sound Effects: Distant summer cicada chirping faintly, the soft scratching sound of the pen touching the paper, the almost inaudible low-frequency pulse of their heartbeats, finally fading into a very light, airy piano. The dialogue is completely naturally integrated into the scene as whispers, the girl's voice is soft and shy, the boy transitions from flustered stuttering to gentle.
Character identity is maintained throughout, real subtle head tilts, eye movements, and breathing synchronization, no text, watermarks, or subtitles, pure Japanese style youth secret crush heart-fluttering suspense.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 권장 설정 모드
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
권장 설정 모드: Standard | 해상도: 720p | 길이: 15초. 100% 실사 인물 애니메이션. 밝은 대낮. 도시 광장. 빠른 조명 변화. 높은...

출처: [게시물](https://x.com/MiraMusic_AI/status/2039096342749016145) · 게시일: 31 Mar 2026

```text
[Recommended Settings] Mode: Standard | Resolution: 720p | Duration: 15 seconds. 100% real-person animation. Bright daytime. City square. Fast lighting. High energy. Explosive atmosphere. Strong rhythm. High-energy version of three-person street dance. Fast dancing. Show-off moves. Quick rhythm. Full participation. Jumps and rolls. Explosive power. Intense three-person performance. [0-1s: Overhead view, quick cut-in] Camera: Fast shot. Full view of the square. Three people in the center. Strong music explosion. Dynamic shot. [1-4s: Medium shot, quick circling] Camera: Fast rotating circle. High-energy basic moves. Quick rhythm starts. Fast switching between high and low angles. [4-7s: Multi-angle low angle] Camera: Rapid switching of multiple angles. Knee-high ↔ wide angle. Fast footwork. Complex high-difficulty stepping. [7-9s: Character 1 burst] Camera: Fast zoom. Close-up of the face. Character 1 intense solo. Explosive power. Fast rotation. [9-11s: Character 2 burst] Camera: Fast angle switch. Close-up of the face. Character 2 intense solo. Show-off moves. High energy. [11-13s: Character 3 burst] Camera: Ultra-fast shot. Close-up of the face. Character 3 intense solo. Highest energy. Jumps and rolls. [13-15s: Wide shot, explosive ending] Camera: Fast zoom out. Full view of the square. Three people synchronize explosively. Climax. Music climax. Freeze-frame smile. [Features] Fast rhythm. Multi-angle rapid switching. High-energy music. Explosive power. Excited audience. Suitable for a party.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### LaFerrari 광고 스토리보드
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
정교한 카메라 움직임과 프리미엄 제품 표면 표현에 초점을 맞춘 럭셔리 슈퍼카 광고용 샷별 스토리보드입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039932977287979053) · 게시일: 03 Apr 2026

```text
Supercar commercial cinematography storyboard

Shot 1 (1.5s): Opening frame on the supercar from the front, showcasing its signature aggressive face.

Shot 2 (1s): Close shot. The virtual camera slowly orbits around the emblem without spinning in a full circle, emphasizing the Ferrari prancing-horse logo.

Shot 3 (1.5s): Close shot, angled view of the LaFerrari's distinctive butterfly door from the side of the car, with a slow orbiting move that emphasizes the body lines.

Shot 4 (1s): Camera moves to the rear for a close shot, then slowly pulls backward using a Hitchcock dolly-zoom effect for visual impact.

Shot 5 (1s): Close shot of the car's side mirror with a slow orbiting move.

Shot 6 (1s): Camera slowly pushes forward using a low-angle advancing move. The car remains still, showing strong perspective, shifting light and shadow, professional automotive cinematography, deep background, cinematic composition, stable visual center, and high-definition live-action quality.

Shot 7 (1s): Lateral track move. The camera sweeps parallel across the LaFerrari body. The car stays completely still as the frame glides smoothly. Side lighting traces the waistline, includes wheel close-ups, delicate reflections, a premium feel, cinematic movement, and clean composition.

Shot 8 (1s): Top-down angle. The camera slowly descends. Static supercar, perfect body proportions, top-light texture, clean ground reflections, aerial-feel movement, the car remains still, symmetrical composition, luxurious texture, 8K ultra-realistic, advertising-grade image.

Shot 9 (1s): Slow push-in close-up from the full car toward the headlights / wheel / waistline. The car remains still. Macro detail, shifting light and shadow, cinematic shallow depth of field, premium texture, sharp detail, commercial photography.

Notes:

No transitions are needed between shots.

No people should appear in the frame.

Highest image quality: 8K.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 열혈 anime 최후의 결투
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
테스트해본 결과입니다: 오리지널 열혈 결투 anime 단편으로, 두 최강의 전사가 공중 유적과 천둥번개를 배경으로 최후의 결투를 벌입니다. 이 작품은...

출처: [게시물](https://x.com/gkxspace/status/2039894982434111716) · 게시일: 03 Apr 2026

```text
Tested it:

Original Hot-Blooded Duel Anime Short Film: Two top warriors launch their final duel against the backdrop of aerial ruins and thunderstorms. The camera emphasizes extreme speed, intense energy collisions and a sense of oppression from the characters. When moves are released, the surrounding buildings, clouds and debris are simultaneously affected by the force. The actions are like the top-level battle animation of TV anime, with theater-level color grading and lens language, focusing on highlighting the "highly intense, exciting, and blockbuster-like" vibe. A strong hook in the first 2 seconds, with a stable main body, coherent actions, movie-level composition and light and shadow, real texture, epic sense, strong emotion, high-definition details, suitable for social media communication. Completely original characters, worldview, costumes, weapons and moves, no copyright risks, and no use of well-known IPs, celebrity faces, brand logos or existing elements.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 35
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Hollywood 오뜨 꾸뛰르 판타지 블록버스터 스타일, 8K ultra-clear, Photorealistic, 하이패션 에디토리얼 스타일, Unreal Engine 5 fluid 렌더링, 시각적...

출처: [게시물](https://x.com/johnAGI168/status/2025849650654122348) · 게시일: 23 Feb 2026

```text
[Style] Hollywood Haute Couture Fantasy blockbuster, 8K ultra-clear, Photorealistic, High-fashion Editorial Style, Unreal Engine 5 fluid rendering, visual illusion. [Duration] 15 seconds. [Scene] An endless, real-life Salar de Uyuni (Sky Mirror) salt flat. The sky is filled with oppressive dark clouds, and the ground perfectly reflects everything like a mirror, with the overall picture presenting a minimalist, cool tone. [00:00-00:05] Shot 1: Haute Couture Entrance and Porcelain Skin. Camera position: Extremely low-angle upward shot, ultra-telephoto lens zoom-in. Action: An Asian female model with a highly recognizable, high-fashion face walks coolly on the water surface. Effect: She is wearing not fabric, but a long dress made of flowing, real Liquid Blue-and-White Porcelain. As she walks, the skirt makes a crisp collision sound like real ceramic, with a flowing luster on the surface. The traditional blue-and-white patterns move across the white porcelain-textured skirt as if alive. [00:05-00:10] Shot 2: Physical Shattering and Ink-wash Descent. Camera position: Extreme close-up of the face, focus rapidly pulls back. Action: The model suddenly stops, stares coldly at the camera, and snaps her fingers crisply. Effect: The moment the fingers snap, her blue-and-white porcelain dress does not fall, but instantly explodes into thousands of extremely photorealistic Ink-wash Swallows. These swallows carry real water droplets and ink marks, dragging black fluid afterimages in the air, spinning frantically around her. [00:10-00:15] Shot 3: Dimensional Dissolution and Abyss Reflection. Camera position: High-altitude overhead shot, camera rapidly rotates and descends. Action: The swarm of ink-wash swallows plunges into the mirrored lake water beneath the model's feet. Effect: The surface tension of the originally solid salt lake instantly disappears. The entire extremely realistic world begins to violently bleed and dissolve like concentrated ink dropped into clear water. The real dark clouds and the model's figure transform entirely into an extremely grand 3D Fluid Ink Vortex, completely swallowing the camera into a black and white interwoven abyss.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 캐릭터
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Modern Rural Aesthetics 스타일의 시네마틱 commercial 품질로, Sony A7S3/cinema camera 촬영, 4K/8K ultra-clear, Extreme Macro, 자연스럽고 투명한...

출처: [게시물](https://x.com/johnAGI168/status/2021818021354848258) · 게시일: 12 Feb 2026

```text
[Style]
Modern Rural Aesthetics, Cinematic Commercial quality, shot with Sony A7S3/cinema camera, 4K/8K ultra-clear, Extreme Macro, natural transparent lighting, healing ASMR, no historical costume drama feel.

[Scene]
A well-maintained modern farmhouse open kitchen, background is a lush vegetable garden, bright sunshine.

[Character]
Modern Rural Creator, black long hair casually tied up with a wooden hairpin, wearing a dark blue comfortable linen outfit, clear makeup, focused and peaceful eyes.

[Shot Details]
[00:00-00:05] Shot 1: Morning Harvest (The Freshness)
Visuals: High-definition close-up. Morning sunlight hits the plants with side backlighting.
Action: The Creator's bare hands (long, clean fingers) pick a bright red tomato with glistening dew drops from the vine.
Details: Extremely sharp focus, clearly showing the fuzz on the tomato surface and the trajectory of sliding water droplets. Background is blurred high-quality green.

[00:05-00:10] Shot 2: Extreme Craftsmanship (The Craft)
Visuals: Indoor stove area, full of life but spotless.
Action: The Creator is cutting vegetables, movements are skilled and precise (non-performance nature).
Details: Macro lens captures the moment the knife blade slices through the ingredients, juice splattering. Then switches to the orange flame flickering in the earthen stove, light and shadow are warm and real.

[00:10-00:15] Shot 3: Tranquil Time (The Moment)
Visuals: Full shot/Medium shot.
Action: A delicate home-cooked dish is placed on the wooden long table in the yard. The Creator sits down quietly, gently tidies a stray hair, and picks up a bite of food.
Atmosphere: Steam slowly rises against the backlight, the scene is so quiet you can almost hear the wind, showcasing the ultimate sense of relaxation modern people yearn for.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 카메라
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
밤의 시네마틱 street racing 시퀀스로, 고성능 차 안의 집중한 드라이버가 스티어링 휠을 움켜쥐고, 강렬한 시선과 도시의 불빛이...

출처: [게시물](https://x.com/CharaspowerAI/status/2039651574297792688) · 게시일: 02 Apr 2026

```text
cinematic street racing sequence at night, a focused driver inside a high-performance car grips the steering wheel, intense eye focus, city lights reflecting on windshield, tension building before sudden acceleration

camera: rapid multi-angle system with seamless transitions, interior close-up → over-the-shoulder → exterior tracking → low ground shots, ultra dynamic camera movement, whip pans + speed ramp transitions + motion blur masking cuts, continuous flow illusion

(0-2s) interior close-up on driver, hand tightens on gear shift, subtle breathing, dashboard lights glowing
(2-4s) over-the-shoulder shot, road ahead stretching into neon-lit city, engine vibration building
(4-6s) extreme close-up on finger pressing NOS button, instant ignition reaction
(6-8s) explosive acceleration, camera snaps to exterior side tracking shot, car launches forward with violent speed surge
(8-10s) ultra low ground shot near asphalt, wheels spinning at extreme velocity, environment streaking past
(10-12s) high-speed chase through tight streets, sharp turns, camera whip pans between angles, reflections and light trails enhancing speed

Dense urban night environment, wet asphalt reflecting neon lights, tunnel passages, street lights streaking, high-speed city atmosphere
Ultra realistic, fast and furious inspired energy, photorealistic lighting, intense motion blur, high contrast neon reflections, cinematic depth of field, extreme sense of speed, fluid transitions, no distortion, no stretching
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 49
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
아시아 슈퍼모델과 럭셔리 스포츠카가 등장하는 톱티어 commercial 품질의 비주얼 블록버스터를 생성하며, 감독급 스토리보드를 요구합니다...

출처: [게시물](https://x.com/johnAGI168/status/2039984306085327298) · 게시일: 03 Apr 2026

```text
Generate a visual blockbuster featuring an Asian supermodel and luxury sports cars with top-tier commercial quality, requiring director-level storyboard arrangement and a fast-paced, high-end rhythm. 0-2 seconds: [Macro to Micro] The opening uses an extreme push-in shot, instantly cutting from the sharp headlights of the sports car with delayed afterimages to a close-up of the pupils of the top Asian supermodel, showcasing the ultimate Oriental charm. 2-5 seconds: [LOCKED-ON SHOT] The camera locks onto the model's profile, tracking her with a lateral pan (Tracking Shot) as she walks confidently and elegantly. The model wears a high-fashion silk evening gown, her hair slightly moving in the wind, against a background of a blurred neon urban viaduct. 5-8 seconds: [360-degree Orbit Shot] The model stands at the center intersection of three sports cars, and the camera quickly orbits around her at a low angle. Use slow motion (slow-motion processing) to capture her cold, stunning glance back, with eyes possessing strong aggression and high-end appeal. 8-10 seconds: [Low-angle Hero Shot] The camera quickly pulls back from a ground perspective to a full view. The model stands proudly in the center of the luxury car cluster. The composition presents perfect symmetrical aesthetics, with light focusing on the face, displaying queen-like dominance. Visual Style: Extreme cinematic realism, 2.35:1 widescreen. The overall color tone leans towards cool Teal & Orange, with natural film grain and soft highlights. The character's skin texture is delicate and natural, possessing the makeup and styling quality of a top luxury magazine. Sound Design: Heavy bass electronic ambient music. Sound effects must sync with the camera cuts (Swish sound effects), and the visual rhythm should breathe with the music beats. Control Instructions: Lock the facial features and high-end makeup of the Asian model, ensuring character consistency across various shots; action transitions must be smooth without stuttering; light and shadow should produce real-time physical reflections as the model moves.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 57
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
android 소녀가 오작동을 일으킨 뒤 악한 연구소를 차례차례 파괴합니다. 험상궂은 얼굴의 사악한 박사가 그녀를 뒤쫓고...

출처: [게시물](https://x.com/aiehon_aya/status/2040187587889905861) · 게시일: 03 Apr 2026

```text
An android girl malfunctions and proceeds to destroy an evil research lab one after another. The evil boss, a doctor with a bad face, chases the girl, shouting, "Waaah! Stop it! Please stop it!!" but the girl doesn't stop and continues to destroy things while laughing. In the end, there is a big explosion, and the lab is destroyed without a trace. The girl yawns and says, "Job complete," and falls asleep right there. The doctor kneels down, utterly dejected.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 포지티브 프롬프트
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Positive Prompt: 오리지널 액션 게임 콘셉트 트레일러입니다. 주인공은 네온으로 붕괴된 도시를 가로지르며, 길가의 잔해는 고장 난...

출처: [게시물](https://x.com/adrianaia_/status/2039972811067031657) · 게시일: 03 Apr 2026

```text
Positive Prompt: Original action game concept trailer. The protagonist travels through a neon ruined city, where the debris by the road emits faulty advertising lights, and mechanical guards fall from the faults of high-rise buildings. After dodging with a slide, the protagonist pulls out a folding energy blade. The camera is like an AAA game debut trailer, with third-person follow, rapid switching between close-up and ultra-wide shots, strong rhythm and distinct scene layers. It finally stops at the silhouette of the boss's appearance, creating a strong feeling of "wanting to play this game". Negative Restrictions: No Cyberpunk 2077 logos, no well-known game UI, no existing game character outlines. A strong hook in the first 2 seconds, stable main body, coherent actions, movie-level composition, real light and shadow, epic sense, strong emotion, high-definition details, suitable for social media communication, avoiding copyrighted characters, avoiding brand logos, and completely original design.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 오리지널 다크 판타지 액션 단편
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
오리지널 다크 판타지 액션 단편: 허물어진 교회 안에서 흰옷의 전사와 검은 갑주의 상대가 최후의 전투를 벌입니다...

출처: [게시물](https://x.com/Rufus87078959/status/2039949879607197828) · 게시일: 03 Apr 2026

```text
Original Dark Fantasy Action Short Film: Inside a dilapidated church, a white-clad warrior and a black-armored opponent launch their final battle amid an atmosphere like a chorus. Stained glass shatters, moonlight penetrates the smoke and dust, and benches are overturned. The camera switches between high-angle overhead shots and low-angle upward shots, focusing on showing the sense of space of the religious building, the sense of oppression of the characters, and the temperament of a fateful decisive battle, just like the climax segment of an original fantasy animated film. A strong hook in the first 2 seconds, stable main body, coherent actions, movie-level composition, real light and shadow, epic sense, strong emotion, high-definition details, suitable for social media communication, avoiding copyrighted characters, avoiding brand logos, and completely original design.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 00:00-00:04 Shot 1: 팔로우 샷
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
00:00-00:04 Shot 1: 팔로우 샷. 연기 자욱한 지하 rave club에서 붉은 기계 척추가 드러난 여성 cyborg가 군중 사이를 걸어갑니다. 그녀는...

출처: [게시물](https://x.com/IamEmily2050/status/2040213294443847933) · 게시일: 03 Apr 2026

```text
[00:00-00:04] Shot 1: Follow shot. In a smoky underground rave club, a female cyborg with an exposed red mechanical spine walks through the crowd. She suddenly turns around, her delicate white porcelain face beginning to convulse violently. [00:04-00:10] Shot 2: Close-up to mid-shot. The cyborg's porcelain face doesn't just split; it is violently shattered from the inside like an eggshell. A massive amount of thick, black viscous fluid erupts outward as an alien head with rusted metallic fangs and multiple mandibles forces its way out of her neck. Simultaneously, her red mechanical spine violently tears through her back, mutating into a giant, multi-jointed metallic scorpion tail dripping with corrosive acid. [00:10-00:15] Shot 3: Wide shot. The club's lighting turns a sickly fluorescent green. The alien tail violently impales the dance floor, suspending the cyborg's ruined body in mid-air as it emits an ear-piercing, non-human shriek. The surrounding crowd is paralyzed with absolute terror, pinned against the walls by webs of black organic matter. Extreme biomechanical horror, terrifying VFX mixing flesh and metal.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 유성 각성 전쟁 히로인
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
100% 실사 촬영 질감, Hollywood IMAX 블록버스터 품질, 자연광과 그림자, 차가운 다큐멘터리 스타일, 흐린 날의 자연광이 특징입니다,...

출처: [게시물](https://x.com/ChrisTheNerv/status/2040043939109953944) · 게시일: 03 Apr 2026

```text
100% real-life shooting texture, Hollywood IMAX blockbuster quality, natural light and shadow, cold documentary style, natural light on a cloudy day, handheld one-shot throughout, breathing shake, random focus shift, 16:9 widescreen.
【Scene Environment】
A destroyed city street extending into the distance. On both sides are ruined concrete buildings, exposed rebar, shattered windows, and some buildings are still burning, with orange flames and black smoke rising. Abandoned cars are scattered on the cracked asphalt road, several of which are burning. The sky is gloomy gray, with smoke and dust suspended in the air. Multiple meteorites streak across the sky with long trails of fire and dense smoke. In the background, terrified civilians scatter among the ruins, some falling, others dragging the injured.
【Main Character】
Chinese beauty, deep red hair tied in a loose, messy bun, with a few strands hanging by her face. Fair skin, sharp features, defined jawline, natural makeup, detailed eye makeup. Attire: Black long leather trench coat over a black vest, black denim mini skirt, black flat combat boots, no belt, wearing black futuristic gauntlets on both hands. Expression is tense and restrained, slightly painful, with slightly furrowed brows—eyes filled with despair and strong will.
【15-Second One-Shot · Awakening Strike Version】
0-2 seconds · Awakening
Low-angle shot, framing her upper body and face, looking up at her standing alone in the center of the destroyed street. The wind blows her black leather trench coat. She opens her lips and screams in Japanese: "Kakusei shiro!" She suddenly opens her right hand, and the black futuristic gauntlet crackles. Purple crystal-textured electric arcs burst from her arm and gauntlet. Air compresses inward, and space warps and distorts. The shockwave emits a low sonic boom. Purple rune lines appear and circulate around her body.
2-5 seconds · Eruption
The camera begins to orbit around her. Dark gold cracks burst from her chest, and thick golden liquid oozes out like blood. She screams in pain. Purple mist and fine electric arcs shoot outward. All her clothing tears open and explodes from the inside, burning into ash—leaving nothing. Organic armor fragments shoot outward, then retract unnaturally to reattach to her body. Purple patterns symmetrically spread across her face. A crack opens on her cheek, revealing pulsating purple light underneath. Simultaneously, multiple mechanical arm-like appendages violently burst from her back—dark metallic texture, blade-shaped, spreading outward like devil's wings. Sparks, blue electric arcs, and golden energy particles explode from the eruption point. The camera captures the complete unfolding from behind—her silhouette outlined against the gray sky, mechanical appendages spread like a fan. The eruption sound is like tearing metal mixed with arc discharge.
5-8 seconds · Growth
Organic matter seeps from her body, the surface shimmering with iridescent light. White armor plates collide and fuse, leaving burn marks. The armor extends downward, completely engulfing and replacing her flat combat boots, forming white and dark purple interwoven armored boots, locking into place with tiny sparks. She grits her teeth and lets out a painful roar. The core in her chest flickers like embers. Purple-black metal spreads over her face, forming an uneven mask, the left eye covered before the right. Compound eyes begin to form, irregularly flashing with liquid light medium. The camera continues to orbit around her.
8-12 seconds · Completion
The camera continues to slowly orbit her. The mask completely seals. Horn-like structures grow upward from the top of her head, burning with purple-gold flames. One compound eye glows steadily, the other flickers with unstable current. The armor is interwoven with white and dark purple, uneven and covered in battle damage, with glowing purple cracks oozing light fluid. Mechanical appendages sway slightly behind her. Each armor plate emits a crisp metallic click when locked, followed by distinct mechanical reset sounds. She slowly lowers her head to examine her hands—the knuckles of the white and dark purple interwoven armored gauntlets seep purple light. She slowly raises her head to look straight ahead, and the compound eyes suddenly glow fully.
12-15 seconds · Supersonic Charge
The camera rapidly retreats. She pushes off the ground with her feet, and the asphalt instantly explodes into a deep crater. A violent purple energy explosion spreads outward from the takeoff point, sending gravel and asphalt fragments flying into the air. She shoots into the air at supersonic speed, charging directly towards the camera—a conical sonic boom cloud forms behind her, the mechanical appendages are flattened backward by the airflow, and the image generates strong dynamic blur. Her figure grows larger and closer, filling the entire frame. A purple energy trail drags behind her. In the final frame, her armored faceplate almost hits the lens, the compound eyes glow scarlet red, and the screen suddenly cuts to black.
【Ambient Sound】
Low sonic boom during awakening, tearing metal and arc discharge sounds, painful screams, crisp metallic clicks, heavy metal sounds of mechanical appendages unfolding, crackling sounds of burning in the background and distant explosions, the final supersonic charge accompanied by the sound of the takeoff explosion, sonic boom impact, and rapidly approaching wind pressure. Everything falls silent the moment the screen cuts to black.
【Physical Texture Enhancement】
Real light and shadow, visible skin texture on the face before transformation, visible real wear and tear on the leather trench coat before transformation. Mechanical appendages possess physical weight and inertia—they sway slightly after unfolding, not rigidly fixed. The armor plates are interwoven with white and dark purple, with visible scratches, welding marks, and uneven edges—not clean and smooth. All movements are steady and powerful, full of pain but resolute—she awakens while enduring. Occasional slight camera shake, pure handheld follow-shot feel.
【Sound Design】
Layered progression from the scream activation to the explosive mechanical eruption, escalating to the takeoff point explosion and the sonic boom of the supersonic charge, finally cutting abruptly to silence. The entire sequence exudes absolute power. Generate sound effects only, no music.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 구름 동굴 검영
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
속도감, 충격감, 대규모 신화적 무협 에너지를 위해 설계된 톈먼산 배경의 wuxia 원테이크 스펙터클입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039865857179013318) · 게시일: 03 Apr 2026

```text
[Cloud Cave Sword Shadow · Heavenly Gate Bloody Battle]
— One-shot sequence at Tianmen Mountain, Zhangjiajie
Core Style: Tsui Hark's new style Wuxia blockbuster, one-shot sequence, high frame rate, 4K ultra-clear.

Tone: Tsui Hark's bright tone, “Cold Jade Blue-Black + Amber Flowing Light.” High contrast, mountain mist acts as a soft light filter, sharpening character outlines, DaVinci industrial-grade color grading.

Scene: Tianmen Mountain, Zhangjiajie (Wacky terrain of Western Hunan. Tianmen Cave opens, swallowing clouds and mist; 999 steps of the Heavenly Ladder hang vertically on the cliff, like a path to heaven; stone forests and pillars cluster like sharp swords, plank roads are faintly visible amidst surging clouds, birds do not cross).

Camera Movement Trajectory:
Low-angle upward shot (emphasizing the natural danger) → Rapid push toward the cave entrance → 180° horizontal pan (showing intense fight on the plank road) → Dive down → Slowly pull back to center → Backlit close-up.

Shot Script:
0-4 seconds [Opening Stance · Heavenly Gate Cloud Surge]:

Movement: Extreme low-angle upward shot, the camera rapidly swoops up and over the Heavenly Ladder from the bottom.

Visuals: Character face reference @[Image 1] Wuxia swordsman attire (white clothes like snow, low-pressed bamboo hat, holding a long sword) stands alone in the center of the 999 steps.

Action: Strong winds whip up the surrounding clouds and mist. [Image 1] holds the sword hilt with the right hand, and the left hand forms a sword-finger gesture across the bridge of the nose. The camera pulls back to show the Tianmen Cave behind him, resembling a giant eye of the heavens.

4-8 seconds [Fierce Battle · Suspended Ladder Interception]:

Movement: 180° orbiting pan.

Visuals: More than ten assassins in tight suits swing down from both sides, clinging to the cliff like monkeys.

Action: [Image 1] touches the steps with his toes, his body spinning upside down. (Tsui Hark-style slow-motion dynamics) The sword remains sheathed, using the sheath as a stick to point, parry, and strike. The air current shakes the rainwater on the steps into mist. The camera rapidly orbits, capturing afterimages and the sparks of metal impact.

8-11 seconds [Breaking the Formation · Traversing the Stone Forest]:

Movement: The camera follows the character diving, passing through a stone archway into the cliffside plank road.

Visuals: Assassins set up a steel wire trap.

Action: [Image 1]'s long sword finally unsheathes (the blade reflects amber sunlight), executing a sweeping strike. The sword energy transforms into a blue-black arc of light, cutting the steel wires. The snapping wires rebound and shatter cliff rocks. He dodges and weaves on the narrow plank road, his figure intersecting with the stone pillars, blending virtual and real.

11-15 seconds [Closing Stance · Mist Dissipates on the Lonely Peak]:

Movement: The camera slowly pulls out from the cave entrance, widening the view to reveal the abyss.

Visuals: Paper talismans (or dead leaves) flutter in the wind. [Image 1] stands at the edge of the Tianmen Cave, with a sea of clouds below his feet.

Action: He performs a sword flourish and sheathes the sword, placing it on his back. Sunlight streams through the Tianmen Cave, creating a massive Tyndall effect.

Freeze Frame: The camera pushes in for an extreme close-up. A drop of blood drips from the edge of the bamboo hat, tracing his jawline. His eyes are sharp as lightning, with the vast landscape in the background.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 98
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"비에 젖은 철길을 따라 좁은 산악 협곡을 질주하는 극적인 low-angle tracking shot입니다. 양옆으로 어두운 바위 절벽이 솟아 있고...

출처: [게시물](https://x.com/ImperfectEngel/status/2039796558238286329) · 게시일: 02 Apr 2026

```text
"Dramatic low-angle tracking shot speeding along rain-slicked train tracks through a narrow mountain gorge. Dark rocky cliff walls rise on both sides, with overhead bridges and power lines crossing above. Moody overcast sky. The camera rushes forward at high speed. Two women — one with pink hair in all-black tactical gear, the other in a white bodysuit — fight on top of the moving train, exchanging martial arts blows as sparks fly. Dynamic action choreography, dark teal-grey color grade, cinematic speed and motion blur, sci-fi action film aesthetic."
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 112
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Hollywood 영화급 commercial 블록버스터 품질, handheld 촬영, 미세한 카메라 흔들림, 빠른 montage 편집으로, 장면 전체가 에너지와...

출처: [게시물](https://x.com/johnAGI168/status/2039277115690877430) · 게시일: 01 Apr 2026

```text
Hollywood movie-level commercial blockbuster quality, handheld photography, slight camera shake, fast-paced montage editing, the scene is full of energy and oppression, no subtitles appear.
The open-plan office hall of a luxurious securities company in Manhattan, USA, in the 1990s. Hundreds of young male brokers in suits densely fill the entire space. American flags hang around, ribbons fall in the air, and the entire hall is plunged into a religious ritual-like collective frenzy.
00:00-00:04 Wide-frame panoramic push-in shot: A powerful middle-aged male protagonist in a suit stands on top of a desk, arms spread, cheering loudly, shouting: "I am not leaving! We are not leaving!" Hundreds of employees below him respond wildly, waving their arms, pounding desks, hugging each other, the hall roaring and shaking. Handheld camera powerfully pushes towards the crowd, creating an overwhelming sense of presence.
00:04-00:09 Quick cut switch: Close-up of the protagonist above the chest, slightly sweaty, eyes burning, lips forcefully shouting: "They want to take it all away from you — ARE YOU GONNA LET THEM?!" The dialogue cue switches to close-ups of employees—young faces contorted in extreme excitement. Some are crying, some are tearing off their ties, some are jumping on tables and howling in response: "NO!!!"
00:09-00:15 The protagonist single-handedly pounds his chest, raising his other fist high, saying the last sentence in a low, forceful voice: "This is who we are." The camera suddenly pulls back from the close-up to a panoramic view—the hundreds of people in the hall erupt in the highest climax of shouting at the same moment. Ribbons pour down, the camera slightly tilts up to capture the protagonist's silhouette standing against the light at the top of the crowd, freezing in that high-energy moment where heroism and madness coexist.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### (폴리지오테스코 웬즈데이)
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
(Poliziottesco Wednesday): Detective Rossi: Deep Heat (Commissario Rossi: la polizia in crisi nera). 범죄 물결이 도시를 덮쳤고 경찰은 좀처럼...

출처: [게시물](https://x.com/ChrisGwinnLA/status/2039456415111393356) · 게시일: 01 Apr 2026

```text
(Poliziottesco Wednesday): Detective Rossi: Deep Heat (Commissario Rossi: la polizia in crisi nera). 
A crime wave has hit the city and the cops can't seem to get it together. Detective Rossi has had enough of the bureaucracy and the politicians tying his men's hands (and freeing the criminals to terrorize the city again!) - but can one hardnosed cop make a difference in a world gone mad? Maybe this nosey journalist can become an important ally!
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 폴더블 스마트폰 패션 광고
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
그라데이션 폴더블 스마트폰을 위해 macro 디테일, 날카로운 컷, 프리미엄한 모션 언어를 담은 상업용 fashion-tech 프롬프트입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2039157138002780202) · 게시일: 01 Apr 2026

```text
Product: Color-shifting gradient foldable smartphone (e.g., light purple to ice blue gradient)

Style: Trendy fashion, energetic fast pace, high-end texture, no people, minimalist light and shadow, fashionable trend style
Tones: High-saturation contrasting colors, light purple gradient frosted glass texture, clean and bright, cinematic light and shadow
Camera Language: Macro close-up, fast rotating camera movement, orbiting camera movement, handheld dynamic camera movement, push-pull quick cuts, smooth transitions
Tempo: 15 seconds tight quick cut, beat-synced editing, sharp transitions

Visual Content:
The light purple gradient foldable phone rapidly rotates against a pure black background, with light flowing across the body; macro close-ups of the ultra-thin hinge structure, the glass texture of the outer screen, the brushed metal close-up of the camera module, and the extremely thin side bezel; quick cuts showing the moment the phone unfolds from folded state, the visual impact of the inner screen's ultra-narrow bezel; paired with simple trendy scenes such as a minimalist office desk, an art gallery corner, late-night city neon, or a trendy collectible display case; fashionable and energetic. No models throughout, focusing only on the product.

Sound Effects: Trendy electronic drum beats, metallic clinks, mechanical click sound of the screen unfolding, beat-synced sound effects
Quality: 4K high definition, commercial advertisement quality, smooth dynamics, vibrant colors
Requirements: Fast pace, tight transitions, high-end fashion, youthful energy, no people appearing.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 레퍼런스 기반

이미지 레퍼런스, 캐릭터 일관성, 프레임 간 제어에 의존하는 프롬프트입니다.

### 스켈레톤 피아니스트 미니어처 디오라마 공연
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
유령으로 가득한 미니어처 디오라마 속 stylish 스켈레톤 소녀가 주인공인 whimsical clay-animation 피아노 공연입니다.

출처: [게시물](https://x.com/tea_story_hoshi/status/2040614786933887043) · 게시일: 05 Apr 2026

```text
I tried adapting it. The details still need more tuning, but the fact that it produced a good result in one pass is impressive.

<prompt>
Subject:
Subject 1: A cute and stylish skeleton girl. She wears a navy sailor-style jacket, a pink pleated skirt, and a wide-brimmed hat adorned with a small skull. Her skeleton fingers are highly flexible, delicate, and expressive. For consistency in appearance and character, please refer to the reference image.
Environment:
A high-quality 3D miniature diorama with a whimsical clay-animation style. A small white grand piano sits on a stage with a stone-like texture. Several friendly glowing white ghosts with simple black eyes, shaped like draped fabric, surround her. The setting is a dreamlike blue architectural space. Warm, fantastical light emanates from the ghosts and small lanterns. Toy-like texture.
Mood:
Eccentric, elegant, cozy, and slightly eerie. The performance is deliberate rather than chaotic, creating a magical and graceful impression.
Timeline:
[00:00-00:02] Shot 1: Wide-angle POV, slow push-in. A skeletal girl sits elegantly at the white grand piano on the stone stage. She raises her skeletal hands, slightly tucks her posture, snaps her head up to look straight ahead, and begins playing smoothly. Audio: a beautiful, elegant classical piano intro.
[00:02-00:03] Shot 2: Hard cut to a medium shot. Stable gimbal movement. She is fully in control of the melody. Her skeletal fingers press the keys with clear, readable motion in a smooth flowing cycle. Friendly glowing white ghosts sway and bounce gently in time with the rhythm. Audio: a fast-paced rhythmic classical piano melody perfectly synchronized with her finger movement.
[00:03-00:07] Shot 3: Slight tracking close-up focused on her face and the piano keys. She ends the performance with a dramatic finale and lifts her hands from the keys as the ghosts glow more brightly in the warm light. She turns toward the camera and gives a gentle nod. Audio: the final elegant piano chord re
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 폭풍의 배 위 공주 vs 크라켄
![Language-JA](https://img.shields.io/badge/Language-JA-blue?style=flat-square)
선박 physics, kraken 파괴, 영웅적인 검격 시퀀스를 결합한 폭풍우 바다 배경의 anime 액션 프롬프트입니다.

출처: [게시물](https://x.com/applete77191758/status/2040450526819807277) · 게시일: 04 Apr 2026

```text
This might not be perfect, but I thought it could still be useful, so I'm sharing it.
(Feel free to modify it.)

I turned internet search on for the first half.
It felt like the camera work got better with it on.

#TopviewAI #Seedance2
-----------------------------------
A cinematic, high-intensity anime sequence set on a pirate ship in a violent storm at night. Strong emphasis on physical realism, dramatic lighting, and dynamic camera control.

Environment & Physics
Heavy rain, strong wind, turbulent ocean <<<Image4>>>

Visible whitecaps continuously forming and breaking.
Ship motion:
Pitching (forward/back tilt)
Rolling (side tilt)
Deck instability affects all character movement (staggering, slipping)
Water spray, wet reflective surfaces, rope tension reacting to motion
Lighting (lightning effects)
Lightning functions as:
Rim light
Strobe effect
Creates sharp shadows, silhouettes, and dramatic reveals
Princess Setup <<<Image2>>>

Princess starts near the mast
Visibly anxious, struggling to balance due to pitching
Subtle stagger and unstable footing
Kraken Emergence & First Impact
<<<Image3>>>
Ocean splits, tentacles erupt through crest waves
Tentacles wrap the ship and slam the deck
Reaction:
Princess staggers
Crew panics: shouting, slipping, colliding
Destruction
Tentacle breaches the hull
Wood splinters, debris bursts
Interior partially floods
Movement to Attack Position
Princess regains footing
Grabs fallen knight's sword
Moves toward the bow only during the attack phase
Camera: aggressive tracking with ship pitching
Heroic Attack Sequence (insert slow motion)
Pre-Attack Build
Lightning flash -> freeze-like tension
Camera begins a slow zoom-in with easing toward the princess
Leap (slow motion starts)
Princess jumps
IMPORTANT:
Enter slow motion (about 0.3-0.5 seconds)
Rain droplets, hair tips, and cloth edges become visible in detail
Lightning acts as a strobe, freezing micro-movements
Slash (maximum zoom)
At the peak of motion:
Camera:
Ease-in zoom -> accelerate into a fast zoom
Action:
Sword swings
Effect:
Bright sword trail / afterimage
Clean, sharp "slash" feeling / impact frame
Motion blur + light streaks
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 메이드 블레이드 댄스: Mei vs Coco
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
두 캐릭터와 각자의 무기, 움직임 로직, 카메라 설정, 컷별 안무를 정의한 구조화된 결투 프롬프트입니다.

출처: [게시물](https://x.com/MiraMusic_AI/status/2040281710957666770) · 게시일: 04 Apr 2026

```text
Title: "Maid Blade Dance - Mei vs. Coco"
Duration: "15 seconds"
Input:
A: "<<<Image1>>>"
B: "<<<Image2>>>"
Characters:
A:
Name: "Kirishima Mei"
Weapon: "Blade of Bewilderment (black-purple)"
B:
Name: "Sakuraba Coco"
Weapon: "Ribbon Spear (silver + red ribbon)"
Movement Core:
A: ["high-speed multi-hit slashes", "black-purple aura", "multiple blur afterimages"]
B: ["high-speed spear rotation", "silver-white aura", "spiral ribbon motion"]
Environment:
Location: "Japanese-style mansion corridor (moonlit, shoji-screen background)"
Lighting: "moonlight blue + shoji orange"
Atmosphere: "black and white dust"
Camera: "24mm to 70mm. High-speed tracking + sudden stops. Slow motion at impact (0.3x speed)."
Cuts:
- Cut: 1
Duration: "1.5 seconds"
Action: "Mei (left) and Coco (right) face each other from 10 meters apart. Mei half-draws her sword."
Camera: "slow horizontal pan (24mm)"
- Cut: 2
Duration: "1.5 seconds"
Action: "Mei fully draws the sword. A black-purple aura flashes for an instant. Mei moves straight toward Coco with afterimages."
Camera: "ultra-fast dolly-in toward Mei (50mm)"
- Cut: 3
Duration: "2 seconds"
Action: "Coco spins at high speed around the spear shaft. Mei's consecutive slashes strike the spear. White-blue sparks burst out. The ribbon spreads outward with centrifugal force."
Camera: "rotation centered on Coco (45mm)"
- Cut: 4
Duration: "1.5 seconds"
Action: "Mei holds her sword at chest height. Coco holds her spear horizontally. They read each other's next move."
Camera: "lateral tracking with anticipation (35mm)"
- Cut: 5
Duration: "2 seconds"
Action: "Mei unleashes seven consecutive slashes. Each slash leaves a trail of black light. Coco sweeps the ribbon to intercept, and the ribbon wipes away the black trails in white arcs."
Camera: "high-speed tracking pan toward Mei (50mm)"
- Cut: 6
Duration: "1.5 seconds"
Action: "Mei delivers a huge diagonal slash. The black-purple aura sweeps across half the screen. Coco braces her spear diagonally to receive it."
Camera: "track Mei's arc from a diagonal angle (50mm)"
- Cut: 7
Duration: "2 seconds"
Action: "Coco rotates her body while changing her spear stance. She thrusts three times at high speed in succession. Mei knocks them away with her blade."
Camera: "flash dolly-in plus rotation toward Coco (40mm)"
- Cut: 8
Duration: "2.5 seconds"
Action: "Sword and spear collide head-on. Sparks explode violently (black-purple vs. white-blue). Their hair ripples. Dust spreads outward in a radial burst."
Camera: "static, centered on the point of impact (70mm)"
Effect: "slow motion 0.3x"
- Cut: 9
Duration: "1.5 seconds"
Action: "Mei and Coco are blown several meters backward, drop to one knee, and glare at each other."
Camera: "pull backward away from both at the same time (35mm)"
- Cut: 10
Duration: "1 second"
Action: "Mei swings her sword once more. Coco resets her spear. They enter the starting stance for the next round."
Camera: "slow pull-back (24mm)"
Loop: "black and white dust separates and spirals. The battle continues forever."
Notes:
- "Mei: straight, sharp motion. Coco: curved, flowing motion."
- "Black-purple vs. white-blue sparks define their personalities."
- "Moonlight and shoji screens reinforce the Japanese duel atmosphere."
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 종말적 옥상 피아노 이별
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
유성이 도시를 파괴하는 가운데 소녀가 옥상 피아노 앞에서 노래하는 종말적 music-video 프롬프트입니다.

출처: [게시물](https://x.com/liyue_ai/status/2040062803076341872) · 게시일: 03 Apr 2026

```text
Core theme: realism | grand epic scale | apocalyptic aesthetics | live-action performance
[Character and basic setup]
Character: use [@Image 1] as the reference. Reproduce the facial features, face shape, and hairstyle 100 percent. No beautification. Height: 1.75 meters.
Base outfit: black thin turtleneck sweater.
Scene: create an apocalyptic music video about a girl playing piano on a rooftop in the ruins of a city under a meteor shower. The background city is being struck by meteors. She plays and sings a farewell song to the world, and in the end disappears in the firelight of a meteor hitting her exact position.
Core content:
- The girl quietly plays piano and sings in the city ruins.
- Massive meteor-shower destruction, with many meteors falling one after another, all trailing long flames.
- Destruction effects must be shocking and realistic.
- Strong contrast between the girl's performance and the catastrophic background.
- A tragic yet beautiful ending of destruction, but it should not look painful.

Lyrics: "The wind is burning, the clouds are fleeing, the clock of the end times rings softly. Dust returns to earth, wind returns afar. My heart is calm as I go toward the end." (end on a high note)
Special requirements:
- Grand scale with shocking destruction effects.
- Strong contrast between the girl's singing performance and the background impact.
- A tragic, beautiful ending filled with apocalyptic aesthetics.
- The song's emotion should rise continuously from weak to strong, with a slow lyrical rhythm.
[Atmosphere and image quality]
Simulated equipment: IMAX film camera with Panavision C-series lenses, including simulated motion blur.
Color and tonality: Hollywood teal-and-orange tone, low saturation. Generate the footage in a realistic visual style.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### CINEMATIC 8mm Fisheye lens, FPV racing drone camera, hyper-fluid motion
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
CINEMATIC 8mm Fisheye 렌즈, FPV racing drone 카메라, hyper-fluid motion. 롱보드를 탄 @Image 1 (Lanky Knight, red coat)과 @Image 2 (가파른 해안 산악...)를 사용합니다.

출처: [게시물](https://x.com/itsPixieVerse/status/2040030453298811099) · 게시일: 03 Apr 2026

```text
[CINEMATIC] 8mm Fisheye lens, FPV racing drone camera, hyper-fluid motion. [@Image 1] (Lanky Knight, red coat) on a longboard. [@Image 2] (Steep coastal mountain road).
0-3s: [Extreme high-speed follow] [@Image 1] carves down the steep asphalt. The camera mimics an FPV drone, flying inches from the ground at blinding speed. The red coat whips violently in the wind.
3-6s: [360-degree barrel roll] [@Image 1] hits a hairpin turn, leaning horizontally. The camera executes a dizzying, hyper-fluid 360-degree roll over his head, maintaining focus on his armor reflecting the bright sky.
6-10s: [Under-board swoop & launch] [@Image 1] hits a ramp, launching into the air. The camera aggressively swoops underneath the board, capturing the massive ocean drop, before tilting up as [@Image 1] backflips.
10-15s: [Impact & rapid pull-back] [@Image 1] lands flawlessly, wheels smoking. The camera snaps backward in a rapid reverse-dolly motion, showcasing the majestic landscape as [@Image 1] speeds away.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 주체
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
주체: @Image 1 Photorealistic Image reference. 전문 스턴트맨이자 kung-fu 마스터가 전신을 사용한 고속의 실전형 kung-fu를 수행합니다. 움직임은...

출처: [게시물](https://x.com/YaReYaRu30Life/status/2039971048305930643) · 게시일: 03 Apr 2026

```text
Subject:@Image 1 Photorealistic
Image reference. A professional stuntman and kung-fu master performing full-body, high-speed, functional kung-fu.

Movement Rule:

Constant full-speed forward
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### Ray tracing, Unreal Engine render, 폭우 속 작은 마을
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Ray tracing, Unreal Engine render, 폭우 속 작은 마을. @image1 캐릭터는 동일한 헤어스타일, 의상, realistic skin, 어두운 조명, IMAX...

출처: [게시물](https://x.com/Gwsubsa/status/2040193631341174792) · 게시일: 03 Apr 2026

```text
Ray tracing, Unreal Engine render, small town in heavy rain. @image1 character with identical hairstyle, outfit, realistic skin, dim lighting, IMAX cinematic, 35mm lens, 4:3 ratio, grey-blue low saturation, film grain, soft god-rays, cold expression, smooth motion, glowing sword trail. 1–3s: Camera tilts up from feet to full body; rain splashes burst under steps. 3–6s: Close-up feet stepping forward, blue shockwave spreads; world desaturates, rain freezes mid-air; camera pulls back, blue aura flows from body. 6–9s: Upper-body close-up; hands gather at chest, suspended rain forms water sword; blue light converges, droplets create massive sphere. 9–12s: Side face close-up; faint blue glow, slash upward; sword dissolves, arc energy explodes with rain; camera follows sky cut, clouds split; golden dragon and fire dragon emerge flying.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 달 위 편의점 야간 근무
![Language-JA](https://img.shields.io/badge/Language-JA-blue?style=flat-square)
real-zasuko-2.0-character-sheet-dx.png를 캐릭터 레퍼런스로 사용합니다. 먼저 달 위 외딴 편의점을 보여주는 wide cinematic shot으로 시작한 뒤...

출처: [게시물](https://x.com/zasuko_michiksa/status/2039650311212872036) · 게시일: 02 Apr 2026

```text
Use `real-zasuko-2.0-character-sheet-dx.png` as the character reference. Start with a wide cinematic shot of the lonely convenience store on the moon before cutting inside. Create a photorealistic 15-second surreal live-action video of Michikusa Zasuko working a night shift at a convenience store.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 옥상 각성에서 F-14 변신까지
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
옥상 질주에서 자유낙하 포착, 자동차에서 제트기로의 변태로 점층적으로 확장되는 롱폼 변신 시퀀스입니다.

출처: [게시물](https://x.com/john87445528/status/2039496153641660508) · 게시일: 02 Apr 2026

```text
Chapter 1 (0-15 seconds): Rooftop Awakening · Running and Leaping Down (Front to Back View). Style: rugged primitive realism using a 35mm handheld film camera, with natural grain and subtle shake. The dazzling direct sunlight of Chongqing noon creates high-contrast shadows and lens flares. Camera: a single continuous third-person handheld follow shot with no cuts, starting from a low front angle and smoothly transitioning to an over-the-shoulder / back view, following the protagonist Image 1 throughout. Atmosphere: high-altitude winds howl, dust and mist fly, and cloth, hair, and mechanical parts all show realistic physical motion. Sound effects: metallic echoes of mechanical high heels striking concrete, heavy rhythmic breathing, howling wind, operating mechanical joints, violent fabric flapping, sudden silence at the instant of the leap, followed by a high-speed wind-cutting shriek during descent. [Visual Reference / Description]: fully preserve the elegant female character from the reference image, wearing a white suit, silver mechanical chest plate and neck collar, silver mechanical hands, and silver high-heeled boots, with long straight black ponytail, delicate facial features, and large earrings. Physical features and clothing details must remain fully consistent. The scene takes place on the rooftop of Raffles City Chongqing, surrounded by skyscrapers, with the broad Yangtze River visible in the distance. [Timeline per Second] 0-4s: [Front Start] The handheld camera captures her full body from a low front angle. She stands at the rooftop edge, looking directly into the camera with a calm, determined expression. The mechanical cervical spine catches the noon sunlight, and her ponytail lifts in the high wind. She slowly turns around. 4-9s: [Over-the-Shoulder Follow · Full Sprint] The camera switches to an over-the-shoulder perspective and follows closely. She sprints across the concrete platform. Her mechanical high heels spark against metal with each step. The hem of the suit and the mechanical spine exoskeleton whip violently in the airflow. Dust kicks up from the roof, and the cloth simulation stays highly realistic. 9-12s: [Leaping Down] She suddenly jumps off. The instant her feet leave the ground, the camera dips slightly and switches to a fast downward tracking view. Her suit billows violently in the extreme airflow. The glass curtain walls of Raffles City streak upward on both sides, and motion blur erupts intensely. [Style and Quality Enhancement] Realistic 8K quality, ultra-fine mechanical texture and cloth physics, cinematic lighting and contrast, perfect motion blur, high dynamic range, no artifacts, coherent multimodal physical effects, stable cinematic image.

Chapter 2 (0-15 seconds): Freefall · Purple AITO M7 Enters the Frame. Style: rugged realism, 35mm handheld camera, natural grain, subtle organic shake. Camera: primarily handheld follow shots, with quick cuts between the protagonist's falling perspective and the ground car-chase perspective to create extreme tension. Maintain full real-time speed, with no slow motion. Lighting: dazzling high-contrast sunlight at Chongqing noon, strong reflections on the glass curtain walls of Raffles City, and heat haze rising from the road. Sound effects: wind-cutting shriek intensifies continuously -> engine roar approaching from a distance -> sharp tire friction on asphalt -> cyber-energy hum -> metallic thud at the moment of impact -> dull compression as four wheels land -> engine roar continues and grows stronger. [Visual Reference / Description] The protagonist remains the same female character from the reference image, preserving all details. Scene: on the Chongqing ramp road below Raffles City, a purple AITO M7 drives at high speed. It uses the upward slope of the ramp to launch naturally and precisely catch the protagonist as she falls from the rooftop. No slow-motion close-ups at any point; keep the rhythm realistic, high-speed, and cinematic. [Timeline per Second] Continuing from Video 1 and extending by 15 seconds. 0-4s: [Extreme Speed Fall · Overlooking the Ground] Protagonist Image 1 falls at high speed while maintaining a balanced gliding posture with both arms spread. The camera locks onto her back. The curtain walls of Raffles City streak upward on both sides, the ground rapidly expands, and motion blur becomes extreme. The frame quickly inserts a ground view: a purple AITO M7 races along the ramp road below Raffles City. The car emits a cyber blue-purple glow, the engine roars, and the tires leave two black marks on the asphalt. 4-9s: [Ramp Launch · Trajectory Intersection] The purple AITO M7 charges to the top of the ramp. Using the ramp's inertia, the front of the car lifts into the air and the sunroof slides open instantly. The camera alternates rapidly between the falling protagonist and the climbing AITO M7. She keeps a high-speed falling posture with arms spread, and the AITO M7 keeps accelerating up the ramp. The two trajectories converge rapidly, compressing time to the limit and maximizing tension. 9-11s: [Last Second · Posture Change · Precise Entry] With only one second left before the sunroof, the protagonist instantly pulls in her outstretched arms and sharply changes from a horizontal gliding posture to a vertical upright posture. Her legs point straight down toward the open sunroof of the airborne purple AITO M7. The action is swift, decisive, and completely without hesitation. In the next instant, she drops vertically into the open sunroof and lands in the driver's seat at extremely high speed. No slow motion at any point; the impact is realistic and violent. 11-13s: [Four Wheels Landing · Maintaining Drive] The body of the car compresses slightly under the force of catching her. All four wheels slam back to the asphalt. The suspension violently absorbs the double impact. Immediately after landing, the engine roar rises further. Without slowing or stopping, all four tires scrape the asphalt, leaving new black marks, and continue driving at full speed. 13-15s: [Stable Inside Car · Energy Accumulation] The AITO M7 continues high-speed driving. The camera tracks close to the side from a low angle as blue-purple energy patterns spread from the four wheels across the body. The sound of mechanical transmission rises subtly from the underside and keeps strengthening. The body vibrates slightly during the high-speed run. The precursor energy of the coming transformation surges and churns beneath the paint. [Style and Quality Enhancement] Realistic 8K quality, ultra-fine mechanical details and energy-light textures, cinematic volumetric light and heat haze, perfect speed blur, HDR glow, no artifacts, full real-time speed, no slow motion.

Chapter 3 (0-15 seconds): AITO M7 Transforms -> Becomes an F-14 -> Protagonist Stands on the Aircraft Back and Takes Off. Style: rugged realism, 35mm handheld film aesthetic, natural grain, subtle shake. Camera: multi-angle follow coverage including ground tracking, low angle close to the ground, aircraft side view, and protagonist first-person view, all following the aircraft tightly throughout the transformation. Transformation details must remain clearly visible. Atmosphere: light smoke and heat haze drift across the Chongqing road. Cyber blue-purple light refracts between buildings. Noon sunlight produces dazzling reflections and strong shadows across the metal surfaces. Sound effects: engine roar surges -> metal skin bursts and folds -> deep hydraulic tremor as the wings unfold -> metallic gripping sound as the protagonist climbs the exterior -> cockpit seal pops and is immediately drowned by wind noise -> explosive ignition of twin engines -> piercing shriek as the F-14 takes off and breaks the air -> powerful high-altitude wind overtakes the entire soundscape. [Visual Reference / Description] The purple AITO M7 completes a full transformation while driving on the Chongqing road, changing from a car into an F-14 fighter jet, as shown in Image 2. During the transformation, the protagonist clings to and climbs along the aircraft exterior in a dangerous and exposed position. She finally stands centered on the back of the F-14, legs slightly apart to stabilize her balance. Her white suit and ponytail whip violently in the extreme airflow. The F-14 takes off directly from the Chongqing road, and the protagonist remains standing firmly on its back. [Timeline per Second] 0-4s: [Road Acceleration · Transformation Start] The AITO M7 accelerates rapidly along the Chongqing road. Body panels burst open one after another and unfold. The hood rolls upward and becomes mechanical structure. The doors fold outward. The metal skin cracks along structural lines, revealing the cold mechanical interior. The protagonist climbs dangerously toward the top of the aircraft while gripping the transforming metal skeleton. She jumps and shifts position in sync with the aircraft's changing shape. The camera tracks every detail from close to the side of the aircraft. 4-6s: [Wings Unfold · Engines Fully Reassemble] The F-14's iconic swept wings snap open from the folded state and lock into place. The camera captures a low-angle near-ground full view of the wing deployment. Heat haze and dust are blasted up by the airflow from the wings. The twin engine nacelles violently reassemble into jet structures, emitting blue-purple thrust flames. The exhaust scorches the road surface. By now, the protagonist has climbed to the center of the aircraft's back, feet planted firmly, standing upright as the transformation completes. 6-8s: [Protagonist Stands on Aircraft Back · Takes Off] The instant the transformation completes, the protagonist stands fully upright on the back of the F-14. The hem of her white suit flies up in the strong airflow, and her ponytail extends horizontally. The silver mechanical parts reflect the noon sun intensely. The F-14's twin engines ignite at full power. The aircraft surges forward, the front wheel lifts, and the rear wheels leave the asphalt at the last possible moment. The nose pitches upward, carrying the protagonist into the Chongqing sky while she remains standing on its back. 8-15s: [Takeoff and Low City Skim · Protagonist Holds Position] The F-14 climbs vertically, then abruptly lowers its nose and skims over Chongqing at ultra-low altitude.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### Character reference @Image 1을 실사 live-action 스타일로 변환
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Character reference @Image 1을 실사 live-action 스타일로 변환합니다. 모델 체형, 차가운 백색 피부, 가느다란 팔, 도드라진 가슴과 엉덩이. 15초...

출처: [게시물](https://x.com/Adam38363368936/status/2039646077230698743) · 게시일: 02 Apr 2026

```text
Character reference @[Image 1], convert to real-person live-action style. Model figure, cool white skin, slender arms, prominent bust and hips.
15-second handheld video with a sense of breathing, Japanese film style, warm orange backlight at dusk, slight film grain, low saturation color tone, no subtitles, no dialogue.
Environment: Sunset, under a concrete overpass, occasional vehicles passing on the road, pedestrian overpass, elevated road, main road traffic, warm orange backlight at dusk, flowing light and shadow from traffic.
Camera Movement: Handheld slight shaking throughout, sense of breathing, natural follow-up, no stabilizer, realistic cinematic feel.
Shot Breakdown (15 shots in 15 seconds):
00:00 | Shot 1: Handheld full body fixed, girl leaning sideways against a concrete railing, one hand on the railing; foreground is the leaning full-body posture, background is blurred traffic and warm yellow dusk, relaxed atmosphere.
00:01 | Shot 2: Handheld full body slight push-in, girl stands up and stretches her arms upwards, a shallow smile on her lips but emptiness in her eyes; foreground is backlit hair and stretching motion, background is blurred steel structure and flowing light spots, light and yet melancholic.
00:02 | Shot 3: Handheld full body follow shot, girl lightly jumps forward; foreground is the jumping dynamic, background is the bridge deck and blurred traffic, youthful and easygoing.
00:03 | Shot 4: Handheld close-up shot, girl brushes her bangs in side backlight, eyelashes dyed gold; foreground is the side face and hand, background is blurred railing and traffic, lazy and gentle.
00:04 | Shot 5: Handheld close-up of hands, fingertips lightly tracing the rough railing; foreground is fingertips and texture, background is dense traffic and warm orange dusk, delicate action.
00:05 | Shot 6: Handheld full body horizontal move, girl sits on the ground looking down at the traffic, eyes vacant; foreground is the sitting full body, background is moving car lights and steel structure, slightly heavy emotion.
00:06 | Shot 7: Handheld close-up slow push-in, girl looks up at the sky, the smile fades, showing sadness; foreground is the quiet face, background is the twilight clouds and buildings, restrained emotion.
00:07 | Shot 8: Handheld full body fixed, girl stands up and stretches her back, backlight outlines her silhouette; foreground is the stretching posture, background is concrete structure and traffic, lonely and clean.
00:08 | Shot 9: Handheld close-up shot; foreground is the tie and hands, background is blurred railing, gentle and fragile.
00:09 | Shot 10: Handheld close-up of eyes, eyelashes clearly defined in backlight, eyes hiding secrets; foreground is the light and shadow on the eyes, background is blurred dusk, delicate emotion.
00:10 | Shot 11: Handheld full body follow shot, girl turns and runs lightly; foreground is the running posture, background is the bridge corner, returning to easygoing.
00:11 | Shot 12: Handheld full body side move, girl runs past the corner, her figure cut by light and shadow; foreground is the light and dark silhouette, background is flowing light spots, realistic handheld feel.
00:12 | Shot 13: Handheld close-up shot, girl briefly smiles while looking down; foreground is the light and shadow on the lips, background is blurred railing, bright emotion.
00:13 | Shot 14: Handheld full body slow push-in, girl walks towards the end of the bridge and stretches her arms pointing into the distance; foreground is the backlit full body, background is the city dusk, quiet and healing.
00:14 | Shot 15: Handheld full body freeze frame, girl turns her back to the camera looking at the city, mixing ease and sadness; foreground is the back view of the flowing skirt, background is the vast dusk and river of cars, ending with negative space.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 형식
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
FORMAT: 15s / free rhythm / 1 MATCH CUT / CONTINUOUS MOVE UNTIL MATCH CUT + IMMEDIATE ACTION FROM FIRST FRAME SUBJECTS: A lone sword-bearing woman in...

출처: [게시물](https://x.com/aimikoda/status/2039380910278115454) · 게시일: 01 Apr 2026

```text
FORMAT: 15s / free rhythm / 1 MATCH CUT / CONTINUOUS MOVE UNTIL MATCH CUT + IMMEDIATE ACTION FROM FIRST FRAME

SUBJECTS: A lone sword-bearing woman in weathered fur and leather fights a massive polar bear with desperate,
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 7장 이미지 심리스 모핑 시퀀스
![Language-JA](https://img.shields.io/badge/Language-JA-blue?style=flat-square)
7장의 정지 이미지를 하나의 통제된 연속 변신 샷으로 바꾸는 재사용 가능한 모핑 템플릿입니다.

출처: [게시물](https://x.com/YaReYaRu30Life/status/2039474680235741681) · 게시일: 01 Apr 2026

```text
[Basic Settings]
structure: Single continuous shot (no cuts)
progression: Morphing 7 images sequentially
visibility: Each image is clearly recognizable for only an instant (no stopping required)
transition: Always smooth and continuous
style: Cinematic, high-definition, dynamic, no flicker
[Prompt Body]
Start from <<<Image1>>>.
The footage proceeds in a completely seamless single shot, continuously transforming in the order of <<<Image1>>> -> <<<Image2>>> -> <<<Image3>>> -> <<<Image4>>> -> <<<Image5>>> -> <<<Image6>>> -> <<<Image7>>>.
The overall scene is not static; morphing occurs within a dynamic video where the camera is constantly moving.
However, the recognizability of the subject is maintained, and the composition is controlled to prevent collapse.
Each image has a peak state where it is clearly visible for an instant within the flow, but there is no stopping or holding.
Everything is expressed as a continuous "evolution within motion."
[Transformation Logic (Fixed order, no duplication)]
<<<Image1>>> -> <<<Image2>>>:
The camera begins transformation while smoothly pushing in forward
Gradual change in the order of outline -> parts -> color -> texture
Fine particle decomposition -> reconstruction
<<<Image2>>> -> <<<Image3>>>:
Tracking movement where the camera flows horizontally
The structure is rewritten by light scanning
Emitting lines flow, and the shape continuously changes
* Particle expression is prohibited
<<<Image3>>> -> <<<Image4>>>:
Orbit movement where the camera circles around the subject
The shape is stretched and transformed by spatial distortion and lens warp
<<<Image4>>> -> <<<Image5>>>:
The camera slightly pulls back and changes perspective (light dolly out + angle change)
The subject melts like liquid and is reformed while flowing
<<<Image5>>> -> <<<Image6>>>:
The camera accelerates momentarily, adding momentum to the movement
The subject fragments, scatters in space, and then reassembles into a new form
<<<Image6>>> -> <<<Image7>>>:
The camera stabilizes while converging back toward the center
Energy converges at the center and integrates into the final form through light and waves
[Camera Behavior (Important)]
- Always moving but controlled movement
- Allowed:
  - Push-in / Pull-out
  - Horizontal tracking
  - Orbit (circling)
  - Light perspective change
- Prohibited:
  - Sudden blur
  - Loss of subject
  - Unnatural jumps
[Constraints (Important)]
- Cut editing prohibited (complete single shot)
- Reuse of the same effect prohibited
- Flicker, noise, and breakdown prohibited
- Subject position / scale should not be significantly disrupted
- Each image must achieve a clearly visible state at least once
- All changes must be continuous and meaningful structural transformations
[Enhancement Keywords]
dynamic camera movement
cinematic motion flow
smooth continuous morphing
temporal coherence
high detail preservation
consistent subject identity
seamless transformation flow
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 초현실 / VFX

변형과 스펙터클을 중심으로 한 추상적이고, 불가능하며, stylized되고, 효과가 강한 프롬프트입니다.

### 무중력 Katana 전투
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Seedance 2.0 무중력 전투 장면입니다. 음악까지 함께 레퍼런스로 넣으면 놀랄 만큼 비트도 잘 따라갑니다. prompt:

출처: [게시물](https://x.com/MiraMusic_AI/status/2040584525781364874) · 게시일: 05 Apr 2026

```text
Seedance 2.0

Zero-gravity combat scene.
If you also reference music, it can follow the beat surprisingly well.

prompt:

A continuous 15-second single-shot action sequence with no cuts or transitions.

Japanese-inspired anime action aesthetics, featuring a cool-toned palette of icy whites and soft blue illumination, with fragments drifting weightlessly in space. Dynamic movement, cinematic framing, and a dramatic atmosphere.

Scene:
A pristine, ethereal white environment where gravity has collapsed. The space feels surreal and dreamlike, filled with soft glowing light and floating debris suspended in midair, creating an otherworldly cinematic mood.

0-3s -- rising tension
The camera glides slowly through the space.
A lone character floats calmly, poised with a katana.

3-6s -- sudden motion
Opponents propel themselves off surfaces, closing in from multiple directions in zero gravity.

6-10s -- fluid combat
Movement unfolds in all directions.
She rotates gracefully midair, delivering precise, flowing strikes.
The camera follows her in a smooth, tumbling motion.

10-13s -- acceleration
She catches a surface briefly, then launches forward with force.
A rapid sequence of strikes disperses the surrounding opponents.

13-15s -- stillness
Figures drift slowly in silence.
She regains balance, floating motionless as the scene holds on a final frame.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 항공 샷
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Whale in the Clouds — 시네마틱한 초현실 서사 단편으로, ultra-realistic magical realism 스타일입니다. 늦은 오후의 해안 도시, 따뜻한 햇살과 바다 안개가...

출처: [게시물](https://x.com/chaosdotjpg/status/2040203827249398086) · 게시일: 03 Apr 2026

```text
Whale in the Clouds — A cinematic surreal epic short film, ultra-realistic magical realism. Late afternoon, a coastal city. Warm sunlight, sea mist swirling, towering cumulus clouds. Everything is calm… until the sky suddenly grows heavy.
Aerial shot: skyline,
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 85
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
완전히 새까만 심해에서 잠수부가 가만히 떠 있고, 한 줄기 빛이 어둠을 가릅니다. 생물발광의 결이 그의 몸 위로 퍼지기 시작하며...

출처: [게시물](https://x.com/AIARTGALLARY/status/2039964736419479576) · 게시일: 03 Apr 2026

```text
A diver floats motionless in pitch-black ocean depth, a single beam of light cutting through the dark. Bioluminescent veins begin threading across their body in accelerated time, skin shifting to iridescent obsidian scales, limbs fusing into massive finned appendages. The figure swells to monstrous proportions, displacing water in shockwave pulses. Final shot: a colossal sea creature dissolving into the abyss. WETA-level underwater VFX, deep teal and void-black tones.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 현실이 갈라진다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
변화하는 반투명 기하 구조로 이루어진 거대한 인간형 존재가 메가시티 스카이라인 위에 나타나고, 그 몸은 겹쳐진 차원 평면들로 구성됩니다...

출처: [게시물](https://x.com/LudovicCreator/status/2039768597241725132) · 게시일: 02 Apr 2026

```text
A towering humanoid entity made of shifting translucent geometry appears above a megacity skyline, its body composed of overlapping dimensional planes reflecting alternate realities — hook at second two: the entity opens both hands and a vertical dimensional tear slices through the city.

Reality splits.

Two versions of the city begin occupying the same space.

Buildings phase through each other as competing timelines collide.

The destruction is dimensional and structural: streets fold into mirrored corridors, cars fall sideways into parallel gravity planes, and skyscrapers fragment into geometric shards as their alternate versions misalign.

Every movement of the entity widens the rift.

Entire districts slide into adjacent dimensions.

The gauntlet unfolds through a skyline progressively divided between worlds: street level where pedestrians phase between realities → mid-rise districts where buildings overlap in transparent duplicates → rooftop where entire towers rotate into perpendicular universes.

Aircraft vanish into dimensional folds.

Bridges twist into impossible angles.

Chase-cam flying through intersecting city layers as gravity shifts between realities.

Velocity ramp when the dimensional rift expands wide enough to swallow an entire city block.

Cut to aerial: the megacity now exists as two overlapping worlds drifting apart.

The dimensional entity stands between them.

Diegetic prismatic dimensional light reflecting through fractured architecture and overlapping skylines, cinematic multiverse distortion effects, particle fragments of shattered reality, 4K.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 비 내리는 지하 골목 합체
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Rainy Underground Alley Merge는 비 내리는 좁은 지하 서비스 골목에서 벌어지는 15초 초현실 호러로, 웅덩이에 반사되는 네온 사인과 피어오르는 증기가 특징입니다...

출처: [게시물](https://x.com/Dheepanratnam/status/2039796932562838010) · 게시일: 02 Apr 2026

```text
Rainy Underground Alley Merge
15-second surreal horror in a narrow rainy underground service alley, neon signs reflecting on puddles, steam rising from grates. 
[0-1.5s] Shot 1: Wide tracking shot, young woman in black leather jacket walks cautiously through rain, breath visible,
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 비디오 프롬프트
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
비디오 프롬프트 Quantum Reality Fracture on City Street (Interdimensional Rift VFX)는 비에 젖은 거리 위에서 벌어지는 시네마틱 15초 고예산 sci-fi 호러 시퀀스입니다...

출처: [게시물](https://x.com/Dheepanratnam/status/2039651240909435242) · 게시일: 02 Apr 2026

```text
Video prompt

Quantum Reality Fracture on City Street (Interdimensional Rift VFX)

Cinematic 15-second high-budget sci-fi horror sequence on a rain-slicked downtown city street at blue hour, towering skyscrapers and frozen traffic, epic scale 

[0-1.5s] Shot 1: Epic wide crane
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 눈이 갑자기 열린다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
캐릭터 눈의 cinematic anime 클로즈업 샷으로, extreme macro 구도에서 속눈썹과 피부 질감이 보이고, 부드러운 호흡 움직임 속에 눈이 천천히 감기며 차분하고...

출처: [게시물](https://x.com/roco_kn_roco/status/2039323186127630710) · 게시일: 01 Apr 2026

```text
cinematic anime close-up shot of a character's eye, extreme macro, eyelashes and skin texture visible, soft breathing motion, eye slowly closing, calm and silent atmosphere, subtle ambient light reflection on eyelid

the eye is fully closed, slight twitch, micro camera push-in, tension building, no effects yet, natural realism

the eye suddenly opens

inside the iris: completely unknown abstract pattern, non-human geometry, fractal layers, asymmetric rotating structures, liquid-metal texture mixed with glowing particles, colors shifting between deep violet, cyan, and iridescent hues

energy distortion spreads from the pupil outward, like reality bending, subtle glitch + fluid simulation fusion (not digital glitch, more organic distortion), light leaking from inside the eye

thin energy veins extend across the sclera (white of the eye), faint luminescent cracks

camera continues slow push-in, reflections in the eye show impossible space (like another dimension or abstract void)

ultra detailed anime style, cinematic lighting, high contrast, no cartoon exaggeration, elegant and mysterious, no text
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 공중에 떠 있는 용암 강 위에서 충돌한다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
검은 암석 섬들이 공중에 떠 있는 용암 강 위에 매달린 폭포처럼 흐르는 초현실적 화산 하늘 세계입니다. 하늘은 타오르고...

출처: [게시물](https://x.com/LudovicCreator/status/2039258991809773666) · 게시일: 01 Apr 2026

```text
A surreal volcanic sky realm where islands of black rock float above rivers of molten lava flowing through the air like suspended waterfalls. The sky burns with deep crimson clouds illuminated by lightning storms.

**Action:**

15.0s sequence. A blazing phoenix composed of flowing flame and glowing embers spirals upward through the volcanic sky. Opposing it is a massive storm griffin whose wings generate violent wind currents and lightning arcs.

They clash mid-air above a floating lava river. The phoenix dives through the griffin’s storm vortex while fire and lightning collide violently.

Velocity Ramp choreography: a lightning claw strike freezes in ultra-slow motion as sparks and embers scatter through the air before snapping back to real time as both creatures spiral downward.

**Camera:**

Fast aerial tracking through lava-lit clouds, briefly passing behind a floating rock formation before revealing the full aerial duel.

**Style & Constraints:**

Photorealistic fire simulation, volumetric storm clouds, ray-traced lava glow, cinematic lightning illumination, stable geometry, 8K.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 템플릿 및 구조화 형식

재사용 가능한 프롬프트 골격, JSON 스타일 스펙, 고도로 구조화된 프롬프트 형식입니다.

### 초대형 항공모함의 대재앙 침몰
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
항공모함 붕괴 대재앙, 거대한 폭풍 파도, 무거운 practical 파괴 디테일에 초점을 맞춘 군사 재난 프롬프트입니다.

출처: [게시물](https://x.com/johnAGI168/status/2040432247094870343) · 게시일: 04 Apr 2026

```text
How does it look?

Seedance 2.0 text-to-video prompt below:

{"lang":"en","prompt":"Style and atmosphere: apocalyptic naval destruction, with low-saturation steel blue and gunmetal gray as the primary palette. Amber explosions and aviation-fuel flames tear through the gray field. Towering storm cumulonimbus clouds are lit from within by lightning. Rain lines cut across every surface. Telephoto compression layers destruction on top of destruction. Live-action brutal aesthetics--no clean CG gloss, only grit, weight, and mass. Motion description: an extreme long aerial drone pullback shows a supercarrier catastrophically listing to port in monstrous waves, with the flight deck tilted beyond forty-five degrees and seawater washing across it as a white sheet of surf. Three fighter jets break free of their tie-down chains at the same time, sliding sideways across the slick steel deck. Their landing gear scrapes metal and throws long chains of sparks, and the first jet flips over the deck edge into the churning gray sea. Hard cut to a handheld medium low-angle shot from water level looking upward--the carrier's hull towers overhead like a collapsing skyscraper. Barnacle-covered steel plates groan and bend, rivets eject one after another like automatic gunfire, and a structural crack splits open from the middle of the hull, with shockwaves rippling across the metal skin. Seawater pours through the widening rupture. Cut to a stable circling wide tracking shot--the carrier breaks in two at the fracture point, the bow plunging forward into a giant swell while the stern rises toward the sky, exposing propellers still spinning in the air. Tons of seawater cascade off the lifted stern like a cluster of waterfalls. Aviation fuel ignites on the sea surface--flames spread outward in a widening ring across the water, and twisted black smoke columns rise into the storm. An abnormal twenty-meter wave surges in from the left side of frame and slams head-on into the tilting bow. White spray explodes sixty meters into the air and swallows the entire forward structure. Static description: catastrophic structural failure of a Nimitz-class supercarrier. North Atlantic storm conditions--fifteen-meter swells, horizontal rain, and sixty-knot winds blowing the wave crests into mist. Thundercloud base at three hundred meters with internal lightning illumination. The flight deck is littered with loose aircraft, broken tie-down chains, and seawater. The hull is split open at the center, exposing interior deck layers. Aviation fuel burns on the sea surface. An abnormal giant wave approaches from port."}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 기억 파편의 재구성
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"effectid": "ethereal02", "title": "Reconstruction of Memory Shards", "visualstyle": "Abstract Cinematic / Art Installation", "duration": "10s",

출처: [게시물](https://x.com/TechTalkNAVI/status/2040327899606306840) · 게시일: 04 Apr 2026

```text
{
 "effect_id": "ethereal_02",
 "title": "Reconstruction of Memory Shards",
 "visual_style": "Abstract Cinematic / Art Installation",
 "duration": "10s",
 "prompt": "A mesmerizing slow-motion shot of thousands of irregularly shaped crystal shards suspended in a void. Each shard acts as a perfect miniature prism, reflecting a different hyper-realistic sunset or starry night inside it. As if pulled by an unseen force, they begin to drift toward a central point, forming a perfect sphere. When they touch, they do not collide but merge seamlessly like liquid glass. The sphere ignites into a blindingly beautiful, soft internal pulse of pure white light, casting fractal patterns of light and shadow everywhere. Photorealistic glass rendering, intense reflection and refraction simulation, poetic atmosphere.",
 "vfx_technical_details": {
  "glass_shader": "Sub-surface scattering with complex refraction and dispersion (Abbe numbers).",
  "particle_attractor": "Force-field-based particle convergence with smooth merging simulation.",
  "lighting": "Dynamic HDR environment mapping inside each shard, with a strong internal light source upon merge."
 }
}

#capcutgenai
#capcutjapandiscord
#CapCutSeedance2
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 블루프린트에서 현실로 – 단층 주택 변환
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"videoprompt": "duration": "15 seconds", "title": "Blueprint to Reality – Single-Story House Transformation", "style": "Architectural visualization,...

출처: [게시물](https://x.com/craftian_keskin/status/2039053365666037902) · 게시일: 31 Mar 2026

```text
{
 "video_prompt": {
 "duration": "15 seconds",
 "title": "Blueprint to Reality – Single-Story House Transformation",
 "style": "Architectural visualization, photoreal, modern farmhouse exterior, clean cinematic motion",

 "blueprint_reference": {
 "floors": 1,
 "footprint_shape": "Irregular L-plus-T shape",
 "layout_zones": {
 "top_left": "Master bedroom with large en-suite (double vanity, bathtub, shower, toilet)",
 "top_center": "Open lounge / sitting area with plants",
 "top_right": "Secondary bedroom + full bathroom",
 "center_left": "Walk-in closet / laundry adjacent to master bath",
 "center": "Open-plan kitchen with island, connected to dining room",
 "center_right": "Family room / playroom with colorful seating",
 "right": "Covered outdoor terrace / patio (open to sky)",
 "bottom_center": "Entry foyer leading to interior",
 "bottom_left": "Double attached garage (2-car, open indoor space, roofed)",
 "bottom_right_upper": "Bedroom 3 with shared bathroom",
 "bottom_right_lower": "Bedroom 4 with small private patio (open to sky)",
 "bottom_right_corner": "Small outdoor lounge / garden corner (open to sky)"
 }
 },

 "roof_rules": {
 "all_interior_rooms": "Fully covered with roof — master bedroom, all secondary bedrooms, bathrooms, kitchen, dining, family room, lounge, garage, foyer, hallways",
 "outdoor_spaces": "Open to sky — right-side terrace, bottom-right small patio, garden corner",
 "garage": "Roofed as part of main structure, no skylight"
 },

 "exterior_style_reference": {
 "roof_type": "Standing seam dark charcoal / black metal roof, low-to-mid pitch",
 "facade": "Light beige / warm white board-and-batten vertical siding",
 "trim": "Dark brown / black window frames and fascia",
 "garage_door": "Dark modern panel garage door, double-wide",
 "covered_porch": "Covered front entry and right-side patio with exposed wood beam columns",
 "windows": "Large black-framed rectangular windows matching each room's position"
 },

 "sequence": [
 {
 "time": "0:00–0:02",
 "action": "Clean white background. Crisp 2D top-down colored floor plan appears — exact layout with all rooms labeled, walls in bold black, rooms color-coded in warm wood tones and blue for bathrooms, gray for garage."
 },
 {
 "time": "0:02–0:05",
 "action": "Camera slowly pulls back. Floor plan glows softly. Thin white grid lines appear beneath the plan, establishing ground plane. Room walls begin to gently pulse, ready to rise."
 },
 {
 "time": "0:05–0:09",
 "action": "Walls begin extruding upward from the 2D plan — all interior walls rise simultaneously, preserving exact footprint. Garage walls, bedroom walls, k
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 무술 오뜨 꾸뛰르 재단사
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
럭셔리 스튜디오 안에서 couture 제작 과정을 정밀 전투처럼 연출한 하이패션 무술 재단 프롬프트입니다.

출처: [게시물](https://x.com/Adam38363368936/status/2037359552849666514) · 게시일: 27 Mar 2026

```text
SUBJECTS:
Character: a female haute couture tailor with an extremely lean build, arm muscles taut like steel wire, and eyes as cold and sharp as needles.
Wardrobe: a dark tactical vest incorporating qipao elements, bare arms, forearms wrapped with dark red silk bracers to increase friction, long slender fingers with metallic fingertip guards.
Movement style: a fusion of Wing Chun's short explosive power and Tai Chi's circular flow. The movement follows the rhythm of charge -> explosive strike -> instant stillness, emphasizing finger burst power and the tension of silk in the air.

ENVIRONMENT:
A dim, luxurious private studio. The background is a full wall of redwood spool racks, where thousands of color blocks create geometric beauty. In the center stands a giant black marble cutting table with a mirror-like surface. Above it hangs a single focused industrial cold light. Tiny fiber particles float in the air.

MOOD:
Extremely focused, elegant, ceremonial, and deadly. Her movements are as precise as a surgeon's, creating a highly oppressive visual sensation.

TIMELINE:
0:00-0:02: close-up / wide-angle POV. The tailor braces both hands on the black marble table and lowers her head in complete stillness. The camera rushes in at extreme speed. She suddenly raises her head and locks eyes with the lens. Her right hand snatches through empty air and catches a bolt of dark purple heavy silk that slides across the tabletop like a serpent.

0:02-0:05: rapid edit / handheld feel. The tailor throws the silk into the air. She moves like an afterimage, holding long silver shears in her right hand, performing a blind cut the instant the silk begins to fall. This is not ordinary tailoring--each cut carries the force of a martial-arts strike. The shears slice the air with a sharp tearing sound, and the fabric edge is perfectly clean and undisturbed.

0:05-0:07: moving shot. She side-steps to the far end of the worktable. With a sweep of one hand, several steel needles leap up from a pin cushion and hover in midair. She pushes with internal force, and the needles shoot like hidden weapons into distant hanging garment patterns. The needle tails tremble with a metallic ring.

0:07-0:10: continuous shot. The tailor begins controlling thread. She pulls out a gold filament and wraps it through the gaps of her fingers, manipulating the silk like puppet strings so it folds and forms itself automatically in midair. Every finger flick crackles with spark-like static electricity. She slams the table with her elbow, making the presser foot bounce upward, and catches it instantly, locking it onto the fabric.

0:10-0:12: match cut. The tailor spins sharply in place, and the hem of her outer garment spreads like a circular formation. She brings both hands together and yanks the formed suit collar tight. The final gold thread draws a perfect arc in the air and stitches itself shut. The action cuts from extreme speed into extreme slow motion.

0:12-0:15: stable POV. Dust settles. She lifts the finished gown with one hand and snaps it open in front of the camera. The lens focuses on the exquisite embroidery at the collar. She flicks a button with her nail--the button vibrates. She then turns and walks into the shadows, leaving only her back as the frame is completely covered by an expensive perfume mist that rises and fades out cleanly.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 형식
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
FORMAT: 15s / 145 BPM / 15 SHOTS / beat-synced routine SUBJECT: @image1. WARDROBE: Sleep tee and lounge shorts at home. Tailored jacket, fitted top,...

출처: [게시물](https://x.com/aimikoda/status/2040200435986817039) · 게시일: 03 Apr 2026

```text
FORMAT: 15s / 145 BPM / 15 SHOTS / beat-synced routine

SUBJECT: @[image1].
WARDROBE: Sleep tee and lounge shorts at home. Tailored jacket, fitted top, trousers, and lace-up shoes outside.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### "위치"
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"location": "Tokyo Cityscape (Night)", "duration": "10s", "prompt": "A cinematic POV shot riding an invisible rollercoaster through Tokyo at night. A...

출처: [게시물](https://x.com/TechTalkNAVI/status/2039941029265355123) · 게시일: 03 Apr 2026

```text
{
 "location": "Tokyo Cityscape (Night)",
 "duration": "10s",
 "prompt": "A cinematic POV shot riding an invisible rollercoaster through Tokyo at night. A glowing neon rail 'creates itself' milliseconds before the camera hits it, weaving through the steel structures of Tokyo Tower and nearby buildings. As the camera passes, each building it touches instantly transforms into a stack of glowing cubes that rotate and re-assemble. The shot ends with the camera diving straight down into a sea of neon lights, which turns into a giant QR code or a logo just before the screen goes black.",
 "vfx_focus": [
 "Procedural rail generation",
 "Dynamic environment transformation (Geometry nodes style)",
 "Extremely high-speed camera motion with light streaks"
 ]
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### "위치"
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"location": "Nishi-Shinjuku Skyscraper District (near Tokyo Metropolitan Government Building)", "duration": "10s", "prompt": "A wide cinematic shot of the...

출처: [게시물](https://x.com/TechTalkNAVI/status/2039928267323658399) · 게시일: 03 Apr 2026

```text
{
 "location": "Nishi-Shinjuku Skyscraper District (near Tokyo Metropolitan Government Building)",
 "duration": "10s",
 "prompt": "A wide cinematic shot of the Tokyo Metropolitan Government Building at sunset. As a deep bass sound hits, the massive twin towers begin to stretch and compress vertically like an accordion in perfect rhythm. Despite the rubber-like stretching, the glass and concrete textures remain perfectly sharp and realistic. The surrounding skyscrapers join the movement, swaying and leaning toward the center as if the entire city is dancing to a hidden beat. Reflection on the windows shifts realistically with the deformation.",
 "vfx_focus": [
 "Non-rigid body deformation (Squash and Stretch)",
 "Real-time reflection mapping during mesh warp",
 "Atmospheric depth and sunset lighting"
 ]
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 별빛 그림자 / 성진 실루엣
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"sceneid": 4, "title": "Starlight Shadow / Stardust Silhouette", "duration": "10s", "visualstyle": "Fantasy / High-End Commercial",

출처: [게시물](https://x.com/TechTalkNAVI/status/2039904725639037110) · 게시일: 03 Apr 2026

```text
{
 "scene_id": 4,
 "title": "Starlight Shadow / Stardust Silhouette",
 "duration": "10s",
 "visual_style": "Fantasy / High-End Commercial",
 "prompt": "A person walks by a clean white wall in a bright, sunlit gallery. Their shadow follows them, but then gracefully stops and starts performing a rhythmic, elegant dance. The shadow is made of soft, shimmering dark-blue particles. As the person reaches out to high-five the wall, the shadow hand gently emerges into the 3D world as a translucent, glowing crystalline form, meeting the person's hand with a soft trail of light.",
 "vfx_technical_details": {
 "camera_work": "Smooth, cinematic tracking shot with a focus on the interaction point.",
 "shadow_FX": "Particle-based shadow simulation with soft edges and internal luminescence.",
 "transition_FX": "Seamless 2D-to-3D transition using a translucent glass shader and light trail effects.",
 "lighting": "Bright, warm afternoon sunlight to contrast with the cool-toned magical shadow."
 },
 "key_elements": [
 "Independent dancing silhouette",
 "Shimmering particle effects",
 "Translucent crystalline 3D hand",
 "Magical and inspiring atmosphere"
 ]
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 대상
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
SUBJECTS: Main Subject: A parkour expert in POV perspective, defined by visible arms, hands, forearms, shoe tips, lower knees, grips, hand placements, wall...

출처: [게시물](https://x.com/0xbisc/status/2040041171460968728) · 게시일: 03 Apr 2026

```text
SUBJECTS:

Main Subject: A parkour expert in POV perspective, defined by visible arms, hands, forearms, shoe tips, lower knees, grips, hand placements, wall runs, precise landings, slides, landing cushioning, and weight shifts.

Style: Painterly 3D, stylized on real human anatomy
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 형식
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
FORMAT: 15s / 180 BPM / ONE CONTINUOUS SHOT / 360 POV downhill stair run, viral energy, max chaos SUBJECTS: First-person cyclist, handlebars and front wheel...

출처: [게시물](https://x.com/aimikoda/status/2039827756083540361) · 게시일: 02 Apr 2026

```text
FORMAT: 15s / 180 BPM / ONE CONTINUOUS SHOT / 360 POV downhill stair run, viral energy, max chaos

SUBJECTS: First-person cyclist, handlebars and front wheel flashing low in frame during drops and hard turns. Vendors, laundry, scooters, dogs, chickens, cars, and
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### "프롬프트"
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"prompt": "Cinematic, hyper-realistic or stylized 3D/2.5D rendering of food and characters, with strong motion and dynamic camera work. Vibrant, saturated...

출처: [게시물](https://x.com/Just_sharon7/status/2039725656393875580) · 게시일: 02 Apr 2026

```text
{
 "prompt": "Cinematic, hyper-realistic or stylized 3D/2.5D rendering of food and characters, with strong motion and dynamic camera work. Vibrant, saturated color grading with warm food tones (reds, oranges, yellows) contrasted by dramatic shadows or neon accents. Sweeping pans, close-ups on textures, slow-motion impacts, quick cuts. High detail on food surfaces including glossy sauces, steam, crumbs, splashes, and expressive character faces. Short, loopable or 'wait-for-it' format with satisfying payoff. Ultra-realistic textures, volumetric lighting, film grain, cinematic composition.",
 "style": {
 "render_type": "3D/2.5D",
 "lighting": "volumetric, cinematic",
 "color_grading": "vibrant, warm tones with dramatic shadows",
 "camera": "dynamic, sweeping pans, close-ups, slow-motion, quick cuts",
 "detail": "hyper-realistic textures, high detail food surfaces, expressive faces",
 "format": "short, loopable, satisfying payoff"
 },
 "resolution": "2K",
 "aspect_ratio": "9:16",
 "stylize": 250,
 "version": "2.0"
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 형식
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
FORMAT: 15s / single continuous impossible camera move / no dialogue STYLE: High-end commercial kitchen during dinner rush, gleaming stainless steel, flying...

출처: [게시물](https://x.com/Dheepanratnam/status/2039568902481387645) · 게시일: 02 Apr 2026

```text
FORMAT: 15s / single continuous impossible camera move / no dialogue STYLE: High-end commercial kitchen during dinner rush, gleaming stainless steel, flying ingredients, photorealistic micro-to-macro cinematic 8K 

Shot 01 (0:00–2:00): Camera starts at floor level on anti-slip
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### "구도"
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"shot": "composition": "POV time-freeze with hands moving through frozen environment", "lens": "ultra-wide cinematic lens with subtle distortion",...

출처: [게시물](https://x.com/CharaspowerAI/status/2039704453784191201) · 게시일: 02 Apr 2026

```text
{
 "shot": {
 "composition": "POV time-freeze with hands moving through frozen environment",
 "lens": "ultra-wide cinematic lens with subtle distortion",
 "camera_movement": "slow walk, precise hand movements, sudden time release burst"
 },
 "subject": {
 "description": "person moving while everything else is frozen mid-action",
 "wardrobe": "hands visible",
 "props": "frozen people, objects mid-air, suspended debris"
 },
 "scene": {
 "location": "busy city street",
 "time_of_day": "day",
 "environment": "people frozen mid-motion, objects suspended in air"
 },
 "visual_details": {
 "action": "walk through frozen crowd, move objects, sudden time resumes explosively",
 "special_effects": "time freeze particles, motion snap release",
 "hair_clothing_motion": "fabric still then snapping with time"
 },
 "cinematography": {
 "lighting": "clean daylight with sharp shadows",
 "color_palette": "natural tones with crisp contrast",
 "tone": "mind-bending, cinematic"
 },
 "audio": {
 "music": "slow ambient then explosive drop",
 "ambient": "silence then sudden chaos",
 "sound_effects": "time snap, object movement",
 "mix_level": "contrast silence and burst"
 }
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 형식
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
FORMAT: 15s / handheld close + slow cuts / 5 beats / sci-fi drama — astronaut's first spacewalk, orbital silence SUBJECTS: An astronaut, 40s, in a white EVA...

출처: [게시물](https://x.com/BrennanErbz/status/2039579736301781215) · 게시일: 02 Apr 2026

```text
FORMAT: 15s / handheld close + slow cuts / 5 beats / sci-fi drama — astronaut's first spacewalk, orbital silence SUBJECTS: An astronaut, 40s, in a white EVA suit with a gold-visored helmet, tethered to the exterior of a space station, performing the first moments of a spacewalk.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 대상
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
SUBJECTS: Subject 1: Adult male, Western casual everyday home and outing attire, short jacket, basic T-shirt, long pants, everyday shoes; lean build,...

출처: [게시물](https://x.com/0xbisc/status/2039673040787956123) · 게시일: 02 Apr 2026

```text
SUBJECTS:
Subject 1: Adult male, Western casual everyday home and outing attire, short jacket, basic T-shirt, long pants, everyday shoes; lean build, natural and efficient movements.
Subject 2: Golden Retriever, large head, broad chest, thick, fluffy fur; overall short and round
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 스타일라이즈드 3D 바버숍 변신 시퀀스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
"title": "Stylized 3D Barbershop Transformation Sequence", "style": "Stylized 3D animation with exaggerated cartoon proportions, cinematic...

출처: [게시물](https://x.com/ShamiWeb3/status/2039372124079669655) · 게시일: 01 Apr 2026

```text
{
 "title": "Stylized 3D Barbershop Transformation Sequence",
 "style": "Stylized 3D animation with exaggerated cartoon proportions, cinematic martial-arts-inspired choreography, rhythmic musical energy, ultra-smooth motion, expressive physics",

 "characters": {
 "dr_eraser": {
 "description": "Lean, almost skeletal barber-scientist with long fingers and oversized glasses that slip down his nose. Wears a bright yellow lab coat filled with strange tools (mini vacuum, magnifying glass, combs, razors, quirky gadgets).",
 "movement_style": "step → pause → spin, precise, calm, orchestral control over chaos"
 },
 "patient_plush": {
 "description": "Huge, soft, teddy-bear-like client with wild messy hair, extremely long drooping beard, and a stained oversized sweater.",
 "emotion": "nervous, trembling, comically overwhelmed, eyes tracking every movement"
 }
 },

 "environment": {
 "location": "Whimsical cartoon barbershop",
 "details": "Oversized mirrors reflecting exaggerated motion, warm golden lighting, steam curling like soft clouds, gleaming tools, hair accumulating like fluffy clouds"
 },

 "mood": "Absurd precision vs comedic fear; controlled elegance vs chaotic nervous energy",

 "timeline": [
 {
 "time": "0:00-0:02",
 "shot": "Close-up",
 "action": "Patient Plush shown with wild hair and massive beard. Dr. Eraser dramatically pulls oversized scissors, spins them on finger, snaps toward camera. Coat flares like wings. Plush reacts in exaggerated shock."
 },
 {
 "time": "0:02-0:05",
 "shot": "Mirror medium shot",
 "action": "Scissors cut rhythmically. Hair falls like confetti. Glasses magnify strands. Beard and hair begin transforming. Plush grips chair, eyes dart nervously."
 },
 {
 "time": "0:05-0:08",
 "shot": "Tracking shot",
 "action": "Scissors disappear. A giant straight razor appears like a sword. Beard shaved in stylized strips. Foam bursts like fireworks. Plush closes eyes tightly."
 },
 {
 "time": "0:08-0:11",
 "shot": "Slow motion",
 "action": "Hot towel spins through air, lands perfectly, then removed in one sharp motion revealing smooth skin. Plush touches face in disbelief."
 },
 {
 "time": "0:11-0:13",
 "shot": "Styling sequence",
 "action": "Pomade applied with theatrical precision. Hair reshaped into shiny cartoon-perfect style. Talc brush creates glowing powder cloud."
 },
 {
 "time": "0:13-0:15",
 "shot": "Final reveal",
 "action": "Chair spins to mirror. Patient Plush fully transformed. He touches face in awe. Dr. Eraser stands behind, spins scissors once, snaps them shut, nods confidently."
 }
 ],
}
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 대상
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
SUBJECTS: Subject 1: First-person perspective hands (rendered in Monet impressionist oil painting brushwork, soft skin tones with no hard edges; both hands...

출처: [게시물](https://x.com/0xbisc/status/2039332336643248317) · 게시일: 01 Apr 2026

```text
SUBJECTS:
Subject 1: First-person perspective hands (rendered in Monet impressionist oil painting brushwork, soft skin tones with no hard edges; both hands continuously hold the oar and perform extremely slow and even rowing motions, with stretched rhythm and natural pauses)
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 일반 시네마틱

위의 더 좁은 범주에는 딱 맞지 않지만 강력한 범용 레퍼런스로 유용한 프롬프트입니다.

### 봄바람 기억의 시
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
장난기 가득한 어린 시절 장면에서 호숫가의 성찰적 우수로 이어지고 시적인 title card로 끝나는 향수 어린 계절 기억 영화입니다.

출처: [게시물](https://x.com/liyue_ai/status/2038993496225591731) · 게시일: 31 Mar 2026

```text
Overall style: fresh and healing, warm nostalgic mood, with warm green and light blue as the main palette. Soft, clear light and shadow, gentle and delicate atmosphere.
Background music: soft instrumental music (piano + bamboo flute), slow rhythm, emotions building layer by layer.
1. Wide shot. A summer afternoon. Sunlight filters through leaves and casts dappled shadows. Beside a clear stream, a group of barefoot children chase and play, splashing water as laughter echoes across the fields. Slow lateral move. Sound: crisp children's laughter, flowing water, soft wind.
2. Medium shot. Children run after colorful butterflies, fingertips lightly brushing their wings. Pink-and-yellow butterflies dance among wildflowers and circle around the children. Follow shot with slight rotation. Sound: fluttering wings, children giggling.
3. Close shot. A child crouches by the rice field and reaches out to catch a frog. Startled, the frog croaks and jumps away into the deeper rice stalks, making the leaves sway gently. Static camera. Sound: frog croaks, children's excited shouts.
4. Wide shot. The playful scene of the children is wrapped in soft light. The overall brightness gradually lowers and begins a fade transition as the colors slowly blur. Camera slowly pulls back and fades out. Background music softens, environmental sound fades.
5. Long shot. On a blue stone by the lakeside, a young man sits alone in silence. Behind him are clear lake water and distant green trees. The frame is peaceful and still. Slow push-in. Gentle instrumental music returns, with soft wind.
6. Extreme close-up. A close-up of the young man's eyes. There is a faint melancholy in them, yet also warmth and remembrance as he looks toward the lake. Static close-up. No extra sound effects, instrumental music only.
7. Medium shot. Following the young man's gaze, children are seen playing on a small boat on the lake. The oars cut through the water and create ripples. Camera slowly pans toward the lake. Sound: children playing, oars in the water.
8. Upward wide shot. White clouds drift slowly across the sky and gradually fade away, as if saying goodbye to old times. Slow upward tilt. The instrumental music slows and the mood elevates.
9. Wide shot. The entire frame gradually darkens. Light and shadow recede. The lakeside and the young man's silhouette become hazy. Static shot as the image darkens. Instrumental music fades to silence.
10. Close-up. At the center of the screen, neat and elegant Song-style Chinese text appears: "If the spring breeze still pities the flowers, could it allow me to be young again?" The text remains as the frame freezes. Text fades in. No sound effect. End on the text.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 하이힐 비트 싱크 패션 클로즈업
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
클로즈업된 힐 움직임, 스타킹 질감, 정밀한 카메라 타이밍을 중심으로 구축된 매우 정교한 beat-synced 패션 프롬프트입니다.

출처: [게시물](https://x.com/TingFengAIAI/status/2038904225548149011) · 게시일: 31 Mar 2026

```text
Beauty beat-sync sequence:

0.0-1.3 seconds: close-up of nude CL high heels at the ankle on a marble floor, wrapped in premium gray sheer stockings that fit smoothly without wrinkles. A single sharp heel tap sound lands at 0.1 seconds. One 35-year-old Chinese woman wears premium gray ultra-thin stockings, nude Christian Louboutin heels, and a black satin long dress. She performs an ankle extension for 0.6 seconds and a heel-tap beat move for 0.2 seconds, timed precisely to 0.1-second accuracy.
1.3-5.0 seconds: the camera slowly pushes in with smooth, even motion and no shake, then cuts instantly to a gray-stocking foot close-up with strong camera-contrast in a 0.1-second switch, then instantly cuts to an extreme waist-and-abdomen close-up. The cut lands with another synchronized heel sound. The woman performs an arm extension for 0.7 seconds and a step accent for 0.4 seconds.
5.0-12.0 seconds: the camera performs a slight orbit, tracking the beat precisely with the movement range and no extra shake. It alternates between waist-abdomen close-ups and gray-stocking calf close-ups. The woman performs a turn for 0.9 seconds and a backbend accent for 0.5 seconds. The heels stay stable, the movement stays precise, and the stocking texture remains clearly visible. Heel sounds hit in sync with the turn and backbend.
12.0-15.0 seconds: freeze on a triple-layer close-up composition: waist-abdomen line close-up + gray-stocking leg close-up + red-sole heel close-up. A total of 22 beat points across the full sequence. The timing is relaxed but precise. Camera motion, heel sounds, and beat points are tightly aligned to maximize Seedance 2.0 performance.
--ar 16:9 --motion 8, soft-focus white light + glow, extremely premium look with strong control.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 아이 방에서의 미니 스케이트보드 탈출
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
아이 방 바닥 위에서 미니어처 소녀가 아주 작은 스케이트보드를 타고 지면 바로 위를 스치듯 고속으로 달립니다. 모든 것이 거대하게 스케일되어 있어...

출처: [게시물](https://x.com/anson7956/status/2038846411253657939) · 게시일: 31 Mar 2026

```text
On the floor of a child's bedroom, a miniature girl rides a tiny skateboard at high speed, skimming just above the ground. Everything is scaled so massively that full-size toys and furniture feel gigantic. The camera follows closely from a low angle in a near one-take style, continuously moving deeper into the background. The video uses an ultra-wide lens, motion blur, depth of field, and cinematic lighting.
The speed increases in three stages.
In the first stage, she races through narrow passages like canyons between Lego city buildings, weaving agilely through blocks.
In the second stage, a giant ball rolls toward her from the front. She slips through the narrow gap between the ball and the wall, barely avoids falling blocks, and brushes past the tires of a moving miniature car.
In the third stage, she bursts through the gap between the pages of a picture book as the wind is about to close it, ducks beneath the armpit of a swaying plush toy, and finally leaps into the small gap of a toy box lid just before it shuts, disappearing into the darkness at top speed.
This is a thrilling, heart-pounding video packed with near escapes. The setting is a realistic child's room, using a miniature perspective to create an immersive, theme-ride-like experience that fully exploits giant obstacles and tiny gaps.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 안드로이드 직장인에서 해변 광고로의 변신
![Language-JA](https://img.shields.io/badge/Language-JA-blue?style=flat-square)
다음과 같습니다: shot1 (3s): sci-fi 분위기의 미래형 오피스 플로어. 안드로이드 여성 직장인이 무표정하게 공간을 걸어갑니다. shot2 (3s):...

출처: [게시물](https://x.com/BarlowHakusyaku/status/2040673309181018522) · 게시일: 05 Apr 2026

```text
Here it is:
shot1 (3s): A futuristic office floor with a sci-fi atmosphere. An android office woman walks through the floor expressionlessly.
shot2 (3s): The android office woman operates a holographic UI while working at her desk.
shot3 (3s): She hands a USB drive to her robot boss, and the neon words "Job done!" float above her hand.
shot4 (3s): The android woman spins, turns her back on the robot boss, and starts running, transforming into a smiling human woman.
shot5 (3s): The transformed woman sits on a beach chair by the sea in a summer dress. At the end, she presents a canned drink labeled "Relaxation time" to the camera like an advertisement, with splashing water exploding in the background.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 흔들리는 bbs를 가진 5명의 여성이 세상을 구한다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
흔들리는 bbs를 가진 5명의 여성이 세상을 구한다

출처: [게시물](https://x.com/mikeymansta/status/2040380590818730418) · 게시일: 04 Apr 2026

```text
5 women with jiggly b**bs save the world
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 25
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
날것의 휴대폰 촬영 영상, 세로 handheld 샷, shaky cam, 거친 질감. 해질녘 전설적인 Rucker Park 농구 코트에서, 체격이 큰 노년의...

출처: [게시물](https://x.com/techhalla/status/2039114930461549008) · 게시일: 31 Mar 2026

```text
Raw mobile phone footage, vertical handheld shot, shaky cam, grainy texture. At the legendary Rucker Park basketball court at dusk, a heavy-set elderly woman in a floral dress and sneakers is dribbling a basketball against
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 28
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
소방관이 집 안으로 들어갑니다. 3초 지점에서는 가구가 불타는 집 내부를 걷고 있고, 5초 지점에서는...

출처: [게시물](https://x.com/AITalesNBH/status/2039072522650423445) · 게시일: 31 Mar 2026

```text
The firefighter is entering the house, at the 3-second mark the firefighter is walking inside the house with furniture in fire around him, at the 5-second mark a burning tree piece falls in front of him, at the 8-second mark he finds a 3 old baby in a baby bed, the baby is coughing, the firefighter lifts the baby and hugs it, the firefighter gets out of the house, he gives the baby to an ambulance personnel
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 고전 의상 변신 쇼케이스
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square)
하드 컷 의상 전환을 사용해 리드미컬한 미적 쇼케이스로 연출한 멀티룩 고전 의상 변신 프롬프트입니다.

출처: [게시물](https://x.com/johnAGI168/status/2040058721158467975) · 게시일: 03 Apr 2026

```text
You can generate the same style of video without using the @ symbol as well.

Seedance 2.0 all-purpose reference prompt below:

[Section 1: Gentle beauty appears] Time: 0-3 seconds. Framing and camera: static medium shot, no camera movement. Female styling and costume: long hair over the shoulders, ancient-style golden crown and dangling hair ornaments, fair skin and red lips. Show three outfits during this section: 1. black strapless long dress with red edging, gold embroidery, and a pearl tassel waist belt; 2. white robe with red sleeves over a gold-embroidered strapless top; 3. pure red slit dress with a red-and-gold embroidered dudou. Movement and expression: both arms dance with the rhythm, fingertips soft and graceful, expression gentle and seductive. Sound: ancient-style transformation BGM. Effects and environment: hard-cut outfit changes on the beat. Purple carpet, folding screen, and candle stands in the background, with purple mist throughout.
[Section 2: Cold elegance shift] Time: 3-6 seconds. Framing and camera: static medium shot. Female styling and costume: hairstyle and makeup unchanged. Show two outfits: 1. white robe and black skirt, black strapless top with intricate gold-and-blue embroidery and a high slit; 2. pink gauze outer layer over a pale blue and white floral-embroidered long dress. Movement and expression: arms rise and fall to cover the face and then open out, body light and graceful, expression turning poised and cool. Sound: ancient-style transformation BGM. Effects and environment: hard-cut transformation on the beat. Alternating warm and cool outfits with strong contrast.
[Section 3: Lively turn] Time: 6-11 seconds. Framing and camera: static medium shot. Female styling and costume: pink translucent gauze outer robe over a black-and-gold patterned strapless dress, with a thin purple sash at the waist. Movement and expression: back turned, then glance over the shoulder, raise one hand lightly, affectionate eyes, lively and playful pose. Sound: ancient-style transformation BGM. Effects and environment: hard-cut transition. Pink and purple lighting cross through drifting smoke.
[Section 4: High-frequency glamour] Time: 11-15 seconds. Framing and camera: static medium shot. Female styling and costume: rapidly cycle through three outfits: 1. deep red strapless long dress with a red-and-gold waist belt; 2. pure white wide-sleeved plain robe with a white belt; 3. pink-and-white split-color dress with light-blue bird embroidery on the chest. Movement and expression: both hands swing up and down in stacked motion with urgent drum hits, larger movement range, full commanding presence. Sound: ancient-style transformation BGM. Effects and environment: ultra-fast beat-synced outfit switching. Multiple colors hit in rapid succession, pushing visual extravagance to a climax.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 밤의 긴자, 미래 cyberpunk
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
밤의 긴자, 미래 cyberpunk. 여성 닌자는 광학 위장으로 투명하게 숨어 있습니다. 그녀는 적 닌자를 쓰러뜨리고, 첫 공격 이후에는...

출처: [게시물](https://x.com/ChiakiAkagi/status/2040232705477255363) · 게시일: 04 Apr 2026

```text
Ginza at night, future cyberpunk.
A female ninja is hiding, made transparent by optical camouflage.
She defeats an enemy ninja.
After the first attack, the optical camouflage is released.
The enemy ninja clones into three.
They fight moving at high speed with motion blur and afterimages.
The female ninja's punch sends the ninja flying, crashing into a neon sign high above.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 점퍼의 이야기들
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
점퍼의 이야기들. 원할 때마다 장소에서 장소로 점프할 수 있는 한 명의 우주비행사에 대한 이야기입니다.

출처: [게시물](https://x.com/starks_arq/status/2040036602018451721) · 게시일: 03 Apr 2026

```text
stories of a hopper. 

1 astronaut that's able to hop from location to location, anytime he wants.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 수상한 남자가 시부야 스크램블 교차로 한가운데 서 있다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
수상한 남자가 시부야 스크램블 교차로 한가운데 서 있습니다. 그의 주변 사람들은 그를 중심으로 time-lapse처럼 지나가고, 그가...

출처: [게시물](https://x.com/roco_kn_roco/status/2039962871149584691) · 게시일: 03 Apr 2026

```text
A suspicious man stands in the center of Shibuya scramble crossing. People around the man walk and cross like a time-lapse, centered around him. When he raises his right hand straight up and snaps his fingers, a wave occurs, and everyone except him stops moving like a mannequin.

Used Prompt 2
Protagonist: Hiromu, Age 19
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 미학
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
미학: 붐비는 사람들로 가득한 어선 갑판 한가운데서 들어 올린 휴대폰. 오디오: 바다 바람과 경쟁하는 베이스, 선체에 부딪히는 파도 소리...

출처: [게시물](https://x.com/maxescu/status/2040095139511636166) · 게시일: 03 Apr 2026

```text
aesthetic: phone held up in the middle of a packed crowd on the deck of a fishing boat
 audio: bass competing with ocean wind, waves crashing against the hull
 timeline:
 - "0-5s: Phone camera on the deck of a fishing boat at sea. Golden hour. The deck is PACKED
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 소녀가 디지털 터널을 빠르게 추락한다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
소녀가 디지털 터널을 빠르게 추락합니다. 소녀는 공포에 질려 허우적거리고, 위아래 좌우로 뒤틀리는 터널을 통과하며...

출처: [게시물](https://x.com/_3912657840/status/2039911660656484590) · 게시일: 03 Apr 2026

```text
A girl falls rapidly through a digital tunnel. The girl is panicking and flailing. She passes through a tunnel that twists and turns up, down, left, and right, then falls straight down. She lands softly on a rainbow cloud in a fancy world overflowing with light. She looks up and sees a large, rainbow-shining sun glowing in the sky. Backlight.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 비주얼
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
장면: Skytree가 "초대형 railgun"으로 변형되어 우주를 향해 빛의 탄환을 발사합니다. 비주얼: 1단계에서 타워 외벽은...

출처: [게시물](https://x.com/TechTalkNAVI/status/2040100728627454339) · 게시일: 03 Apr 2026

```text
Scene: The Skytree transforms into a "super massive railgun" and fires a light projectile towards space.

Visuals:

First Stage: The exterior of the tower is purged, exposing complex superconducting coils inside. Intense discharge phenomena surround the area.

Middle Stage: As energy is charged, the entire power of Sumida Ward is sucked into the tower, causing a city-wide blackout. Only the tower glows white.

Final Stage: Firing. A pillar of light pierces the stratosphere, forming a giant aurora ring in space.

Lighting/Color: Cold white, purple discharge. Contrast between silence and roar.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### Hollywood 영화 예고편
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Hollywood 영화 예고편입니다. 평범한 미국 고등학생이 영웅으로 변신해 싸우는 Marvel 스타일 액션 영화이며, 이를 만들고 싶습니다...

출처: [게시물](https://x.com/SSSS_CRYPTOMAN/status/2040217171918516475) · 게시일: 03 Apr 2026

```text
A Hollywood movie trailer. A Marvel-style action movie where an ordinary American high school student transforms into a hero and fights. I want to create various scenes with multi-cuts. The title is CRYPTOMAN
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 시네마틱 세로형 9
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
시네마틱 세로형 9:16 비디오입니다. Tangled의 두 버전 Rapunzel이 숲속 흙길 위에서 카메라를 향해 나란히 걸어옵니다. 왼쪽에는 원작 버전이...

출처: [게시물](https://x.com/Mayz1169/status/2039982387703296044) · 게시일: 03 Apr 2026

```text
Cinematic vertical 9:16 video. Two versions of Rapunzel from Tangled walk side by side toward the camera on a forest dirt path. On the LEFT: the original Disney 3D animated Rapunzel — large expressive cartoon eyes, stylized face with Disney animation proportions, luminous long
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 해안 도시 옆 피오르드로 거대한 빙하 절벽이 붕괴한다
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
해안 도시 옆 피오르드로 거대한 빙하 절벽이 붕괴합니다. 떨어진 얼음은 대규모 수괴 변위 파동을 일으켜 항구를 향해 밀려오고...

출처: [게시물](https://x.com/LudovicCreator/status/2040100791822721300) · 게시일: 03 Apr 2026

```text
A giant glacier wall collapses into a fjord beside a coastal city.

The falling ice triggers a massive water displacement wave that surges toward the harbor.

Camera sweeps over the collapsing glacier before racing toward the city as the water wall crashes into buildings and docks.

Icebergs smash through streets as the city floods.

Glacier collapse megaflood, iceberg destruction chaos, cinematic polar disaster scale, 4K.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 달빛 아래 피아노 추격전, 그곳에서 쥐는
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
달빛 아래 피아노 추격전에서 쥐는 피아노 전체를 함정으로 바꿉니다. 무슨 일이 벌어지나면, 쥐는 건반 위를 달리며 장난스러운 음을 만들고, 고양이는...

출처: [게시물](https://x.com/Dheepanratnam/status/2040060221733609969) · 게시일: 03 Apr 2026

```text
A moonlit piano chase where the mouse
turns the whole instrument into a trap.

What happens The mouse runs across piano keys, making playful notes. 

The cat stalks across the piano lid. The cat lunges, but the mouse slips into the piano. 

The cat gets nearly caught by the closing lid. Inside the piano, the mouse runs through strings and hammers. The cat’s tail gets plucked like an instrument. 

The cat crashes into the keyboard section, causing a chaotic musical explosion. Final gag: the mouse presses one neat final note while the cat pops out wearing sheet music on its head.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 15초 연속 원테이크 카툰 시퀀스
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
15초 연속 원테이크 카툰 시퀀스입니다. 컷 없음. 장면 전환 없음. 부드러운 수채화 일러스트 스타일, 파스텔 색감, 온화한 질감이 특징입니다...

출처: [게시물](https://x.com/Artedeingenio/status/2040054705183723711) · 게시일: 03 Apr 2026

```text
15-second continuous single-shot cartoon sequence.

No cuts. No scene transitions.

Soft watercolor illustration style, pastel colors, gentle textures, hand-drawn outlines, dreamy lighting, calm and magical tone

Scene:

A small animal character walking through a quiet meadow.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 프롬프트 83
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
Victorian 시대의 비행 비공정들이 황동 기어와 거대한 프로펠러를 달고 석양의 구름 낀 산맥 위에서 전투를 벌입니다. 대포가 발사되고, 해적들이 줄에 매달려...

출처: [게시물](https://x.com/Alin_Reaper05/status/2040017612105556403) · 게시일: 03 Apr 2026

```text
Victorian-era flying airships with brass gears and giant propellers battling over a cloudy mountain range at sunset, cannons firing, pirates swinging on ropes between ships, intricate mechanical details, sweeping aerial tracking shot with parallax, warm steampunk color palette, ultra-detailed, like Howl’s Moving Castle meets Pirates of the Caribbean, epic action.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 미학
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
미학: 날것의 35mm handheld, 고지대의 태양 안개. 끊기지 않는 연속 tracking shot 하나. 컷 없음. 모두 실시간. 오디오: 끊임없이 이어지는 제트 엔진 굉음...

출처: [게시물](https://x.com/maxescu/status/2039639805592502504) · 게시일: 02 Apr 2026

```text
aesthetic: Raw 35mm handheld, high altitude sun haze. One unbroken continuous tracking shot. No cuts. All real time. audio: Full constant jet engine roar, wind blast, no other sound. 

timeline: 
- 0-3s: Normal guy in baggy cargo shorts and flip flops is standing perfectly
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 깊은 산속 고대 사원의 외부
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
2.35:1 와이드스크린, 24fps, 시네마틱 품질. 깊은 산속 고대 사원의 외부를 다룹니다. 카메라는 밀려드는... 속에서 사원 지붕을 내려다봅니다.

출처: [게시물](https://x.com/cdexsta/status/2039559243284844649) · 게시일: 02 Apr 2026

```text
2.35:1 widescreen, 24fps, cinematic quality.
Exterior of an ancient temple in the deep mountains. The camera overlooks the temple roof amidst surging clouds, with mottled tiles and rising mist. The scene cuts to the interior, where a middle-aged monk sits cross-legged, with an ancient Buddha statue and flickering candlelight behind him. The camera slowly rotates 360 degrees, panning from the monk's side to a front close-up, capturing his slightly closed eyes and calm breathing.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 극적인 조명의 역사 장면
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
극적인 조명의 역사 장면입니다. 0-3초 오프닝 샷: 새벽의 콘스탄티노플을 향해 베네치아 갤리 함대가 접근하고, 대포가 불을 뿜습니다. 거대한 도시가...

출처: [게시물](https://x.com/AskVenice/status/2039570736239595726) · 게시일: 02 Apr 2026

```text
Historical scene with dramatic lighting.

[0-3 seconds]
Opening shot: Venetian galley fleet approaches Constantinople at dawn, cannons blazing. Massive city walls loom in background, Byzantine banners fluttering defiantly.

[3-6 seconds]
Quick cut: Ottoman cannon
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 로켓 서프
![Language-ES](https://img.shields.io/badge/Language-ES-blue?style=flat-square)
ROCKET SURF. 스타일: 거친 Cine Verite, 35mm handheld, 자연스러운 흔들림. 연속 tracking shot. 컷 없음. 모두 실시간. 조명: 밝은 고지대의 태양광...

출처: [게시물](https://x.com/maxescu/status/2039308020006396033) · 게시일: 01 Apr 2026

```text
ROCKET SURF.
STYLE: Gritty Cine Verite, 35mm handheld, natural shake. Continuous tracking shot. No cuts. All real-time.

LIGHTING: Bright, high-altitude sun, pure blue sky.

AUDIO: Rocket engine roar, wind, fiberglass creak.

TIMELINE: 0-3s:
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

### 대사
![Language-EN](https://img.shields.io/badge/Language-EN-blue?style=flat-square)
검은 머리에 질감 있는 빨간 드레스를 입은 단 한 명의 스탠드업 코미디언 @Image 1이 스포트라이트를 받는 무대 @Image 2 위에 서 있습니다. 과장되고 유머러스한...

출처: [게시물](https://x.com/Adam38363368936/status/2039286911265800297) · 게시일: 01 Apr 2026

```text
A single stand-up comedian @[Image 1] with black hair, wearing a textured red dress, standing on a spotlighted stage @[Image 2]. Exaggerated and humorous expression, lively eyes, confident and rhythmic tone.
Dialogue: Have you noticed that people nowadays say they are 'lying flat,' but their bodies are more competitive than anyone else's! My friend constantly claims to be 'Buddhist-style'—not fighting or competing—yet their speed when grabbing red envelopes is so fast I can't even see it clearly! I just want to ask: Is your 'Buddhist-style' so effective that even the Buddha would want to send you a rocket?
Actions and Expressions:
 
- When saying “lying flat”: Spreading hands, looking helpless
​
- When saying “grabbing red envelopes”: Quickly flicking hands, performing a super-fast hand motion, eyes wide open
​
- Ending: Shrugging, grinning broadly, maximizing interaction
Scene: Black stand-up stage, strong spotlight illuminating the person, blurred silhouettes of the audience below, atmosphere of laughter, slight camera push-in, cinematic lighting, strong stage presence, real-shot texture, fast pace, 15-second short video effect. Shallow depth of field, enhanced light and shadow contrast, scene detail reconstruction, digital noise elimination, 4K high-definition quality.
```

**[바로 사용해보기 ->](https://evolink.ai/seedance-2-0?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)**

## 리소스

- 데이터셋 기준 원본: [`../seedance_2_prompt.json`](../seedance_2_prompt.json)
- 기여 가이드: [`./CONTRIBUTING.md`](./CONTRIBUTING.md)
- 저장소 계획 레퍼런스: [`../repo-structure.md`](../repo-structure.md)
- API 레퍼런스: [`EvoLinkAI/Seedance-2.0-API`](https://github.com/EvoLinkAI/Seedance-2.0-API)
- OpenClaw skill: [`EvoLinkAI/seedance2-video-gen-skill-for-openclaw`](https://github.com/EvoLinkAI/seedance2-video-gen-skill-for-openclaw)
- 실전 가이드: [`EvoLinkAI/awesome-seedance-2-guide`](https://github.com/EvoLinkAI/awesome-seedance-2-guide)

## 기여

프롬프트를 추가하거나 정리하기 전에 [`CONTRIBUTING.md`](./CONTRIBUTING.md)를 읽어 주세요. 핵심 규칙은 단순합니다. 실행 가능한 프롬프트는 남기고, 주변의 소셜 노이즈는 제거하며, README 메타데이터를 정리된 데이터셋과 동기화하세요.

## 라이선스

최종 오픈소스 라이선스 파일은 아직 추가되지 않았습니다. 결정되기 전까지는 이 저장소를 항목별 원본 출처 표기를 보존한 큐레이션 레퍼런스 컬렉션으로 취급해 주세요.

## 저작권 고지

이 저장소는 공개 웹 소스에서 수집한 Seedance 2.0 프롬프트 예시를 큐레이션합니다.

- 가능한 경우 프롬프트 출처는 attribution 링크와 함께 보존됩니다.
- 이 저장소는 학습, 프롬프트 연구, 워크플로 레퍼런스를 위한 것입니다.
- 원본 프롬프트 텍스트의 저작권은 원저자에게 있습니다.
- 어떤 항목을 수정하거나 삭제해야 한다면 관련 소스 링크와 함께 이슈를 열거나 pull request를 제출해 주세요.
