Це генеративний веб-синтезатор, що перетворює реальні дані космічної погоди на живий звук.
Сонце, магнітосфера Землі та рентгенівське випромінювання стають не метафорою, а прямими модуляторами аудіо-рушія.

У реальному часі такі параметри, як:
швидкість сонячного вітру
щільність протонів
рівень X-ray випромінювання
стан геомагнітного поля
впливають на базову частоту, глибину модуляції, фільтрацію та просторові ефекти.

🔊 Звуковий рушій
Синтез побудований на Web Audio API та складається з:
атмосферного синус-осцилятора
басового дрону на трикутній хвилі

Сигнал проходить крізь багатошарову FX-матрицю:
Ring Mod → Phaser → Glitch → Vowel Formant Filter (A-I-U) → Saturation → Tremolo → Chorus → Stereo Width → Ping-Pong Delay → Convolution Reverb

🥁 Ритм
Окреме ядро — 4-канальний драм-секвенсор
(Kick / Perc / Snare / Hat),
усі звуки синтезуються алгоритмічно (осцилятори + шум), без семплів.

🌌 Режим симуляції
Якщо реальні космічні дані недоступні, система автоматично переходить у режим симуляції, генеруючи псевдовипадкові сигнали для збереження динаміки та демонстрації поведінки системи.

Це не інструмент для контролю.
Це інструмент для спостереження.
------------------------------------------------------------------------------
sun.modular.ibonarium.live.performance

This is a generative web synthesizer that transforms real-time space weather data into sound.
Solar activity, Earth’s magnetosphere, and X-ray radiation are not symbolic — they act as direct modulation sources.

In real time, parameters such as:
solar wind speed
proton density
X-ray flux
geomagnetic field activity
continuously affect base frequency, modulation depth, filtering, and spatial processing.

🔊 Sound Engine
Built entirely with the Web Audio API, the engine consists of:
an atmospheric sine oscillator
a bass drone based on a triangle wave
The signal flows through a deep FX matrix:
Ring Mod → Phaser → Glitch → Vowel Formant Filter (A-I-U) → Saturation → Tremolo → Chorus → Stereo Width → Ping-Pong Delay → Convolution Reverb

🥁 Rhythm Core
A dedicated 4-channel drum sequencer
(Kick / Perc / Snare / Hat),
with fully synthesized sounds (oscillators + noise buffers), no samples.

🌌 Simulation Mode
When live space weather data is unavailable, the system automatically switches to Data Simulation Mode, generating pseudo-random signals to preserve motion and demonstrate system behavior.

This is not an instrument for control.
It is an instrument for listening to systems larger than us.

--------------------------
