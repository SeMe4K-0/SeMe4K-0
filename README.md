<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=C9D1D9&center=true&vCenter=true&width=650&lines=%D0%A1%D0%B5%D0%BC%D1%91%D0%BD%20%D0%94%D0%B0%D0%B2%D1%88%D0%B8%D1%86%20%2F%20SeMe4K-0;ML%20Engineer%20%C2%B7%20Competition%20ML;%D0%9C%D0%93%D0%A2%D0%A3%20%D0%B8%D0%BC.%20%D0%9D.%D0%AD.%20%D0%91%D0%B0%D1%83%D0%BC%D0%B0%D0%BD%D0%B0%2C%20%D0%98%D0%A35-74%D0%91" alt="Typing SVG" />

<br/><br/>

[![Резюме PDF](https://img.shields.io/badge/%F0%9F%93%84%20%D0%A0%D0%95%D0%97%D0%AE%D0%9C%D0%95-%D1%81%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20PDF-2ea44f?style=for-the-badge)](https://github.com/SeMe4K-0/SeMe4K-0/raw/main/cv.pdf)
[![Telegram](https://img.shields.io/badge/Telegram-@SeMe4KO0-229ED9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/SeMe4KO0)
[![Email](https://img.shields.io/badge/Email-s.davshits@yandex.ru-CC0000?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:s.davshits@yandex.ru)

</div>

---

**ML-инженер.** Временные ряды и причинность, computer vision, аудио и речь, LLM и безопасность AI-агентов.

**Временные ряды и табличные задачи** — прогноз поведения 250 000 пользователей на 30 дней
вперёд по 409 дням истории: якорная постановка «пользователь × дата», обучение прямо в шкале
метрики, ансамбль GRU и градиентного бустинга.

**Причинность и работа с данными** — uplift-моделирование на 45.8 млн покупок:
витрина признаков оконными функциями PostgreSQL из сырых чеков, метрики причинности
написаны руками, предрегистрация заморожена до первой модели, аудитор утечек доказан
мутационным тестом.

**Computer vision** — сегментация фаз на панорамах оптической микроскопии до 300 Мп с
интерпретируемым правилом вместо чёрного ящика и детекция на видеопотоке с инференсом
на устройстве через CoreML.

**Аудио** — разделение источников на Demucs с замером SDR/SIR/SAR через museval и
воспроизводимый бенчмарк пяти генеративных моделей музыки по FAD, FAD-inf и CLAP.

**LLM и AI-агенты** — guardrail-детектор атак на Trust & Safety политику (99.81 из 100
при старте 61.54), red team на извлечение секрета из системного промпта, и prompt-evals,
проверяющие устойчивость ответа к инъекциям.

## Достижения

| Год | Соревнование | Результат | Ссылка |
|------|------------|--------|---|
| 2026 | **E-CUP 2026 (Ozon)** — прогноз GMV пользователей на 30 дней · команда O3 | **14 место из 316** · RMSLE 1.6631 | [решение](https://github.com/SeMe4K-0/Ozon-ecup-2026-user-ltv) |
| 2026 | **Yandex ML Challenge** (Young & Yandex) — финал | **42 место из 100 финалистов** | [сертификат](certificates/2026-yandex-ml-challenge-42.pdf) |
| 2026 | **ШАД Яндекса** — интенсив AI Agents Security Week | Guardrail-детектор **99.81 / 100** (старт 61.54) · red team **71.43 / 100** | [сертификат](certificates/2026-shad-ai-agents-security-week.pdf) |
| 2026 | **Хакатон DatsSol** (DatsTeam) — бот управления колонией | **16 место из 166** | [решение](https://github.com/SeMe4K-0/Hackathon_DatsTeam) |
| 2026 | **Норникель AI Science Hack** — классификация руд по OM-изображениям | Финалист · macro-F1 **0.91** по типу срастаний | [решение](https://github.com/SeMe4K-0/OreScope) |

## Стек

<table>
<tr>
<td valign="top" width="25%">

**ML · Tabular**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-026E02?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2E5C8A?style=flat-square)
![statsmodels](https://img.shields.io/badge/statsmodels%20%C2%B7%20bootstrap-8CAAE6?style=flat-square)
![causal](https://img.shields.io/badge/uplift%20%C2%B7%20causal%20inference-6A0DAD?style=flat-square)

</td>
<td valign="top" width="25%">

**DL · CV · Audio**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![torchvision](https://img.shields.io/badge/torchvision-EE4C2C?style=flat-square)
![smp](https://img.shields.io/badge/segmentation--models--pytorch-4a4a4a?style=flat-square)
![albumentations](https://img.shields.io/badge/albumentations-8A2BE2?style=flat-square)
![Ultralytics](https://img.shields.io/badge/Ultralytics%20YOLO-00FFFF?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CoreML](https://img.shields.io/badge/CoreML-000000?style=flat-square&logo=apple&logoColor=white)
![torchaudio](https://img.shields.io/badge/torchaudio%20%C2%B7%20librosa-EE4C2C?style=flat-square)
![Demucs](https://img.shields.io/badge/Demucs%20%C2%B7%20museval-1f6feb?style=flat-square)

</td>
<td valign="top" width="25%">

**LLM · NLP**

![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![CLAP](https://img.shields.io/badge/CLAP%20%C2%B7%20MERT%20%C2%B7%20EnCodec-FFD21E?style=flat-square)
![TF-IDF](https://img.shields.io/badge/TF--IDF%20%C2%B7%20embeddings-F7931E?style=flat-square)
![Prompt](https://img.shields.io/badge/prompt%20engineering%20%C2%B7%20evals-4a4a4a?style=flat-square)
![Guardrails](https://img.shields.io/badge/guardrails%20%C2%B7%20red%20team-8B0000?style=flat-square)

</td>
<td valign="top" width="25%">

**Backend · Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%C2%B7%20PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%20%C2%B7%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git%20%C2%B7%20Git%20LFS-F05032?style=flat-square&logo=git&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td>
</tr>
</table>

## Проекты

**[X5 RetailHero Uplift](https://github.com/SeMe4K-0/X5-retailhero-uplift)** &nbsp;·&nbsp; Кому предложение меняет поведение
> 45.8 млн покупок в PostgreSQL, витрина на оконных функциях из сырых чеков (готовые агрегаты не используются) · dbt: staging → marts → audit, 42 теста · T/S/X-learner и метрики причинности (Qini, AUUC, uplift@k) написаны руками · **топ-10 % по отклику и топ-10 % по приросту пересекаются на 0.44 %** [0.26; 0.62] при случайном уровне 10 % · **Δ uplift@10 % = +9.53 п.п.** [+6.63; +12.54], бутстрап 2000 реплик · политика по отклику убыточна: точка окупаемости 4.67 п.п. против фактических 0.53 · предрегистрация заморожена до первой модели, аудитор утечек доказан мутационным тестом

**[Stem Separator](https://github.com/SeMe4K-0/Stem-separator)** &nbsp;·&nbsp; Разделение трека на 4 инструментальные дорожки
> Demucs (htdemucs) · REST API + Web UI + CLI · метрики через museval на MUSDB18-sample: **SDR vocals 9.34 dB, bass 9.90 dB** (выше типичных литературных для htdemucs), drums 5.75, other 3.88 · MPS/CUDA/CPU autodetect, chunked inference, SHA256-кэш · **3:17-трек за 14 с на M4 Pro (×14 realtime)** · 19/19 тестов, Docker Compose

**[FAD Benchmark](https://github.com/SeMe4K-0/Music-generation-fad-benchmark)** &nbsp;·&nbsp; Оценка генеративных моделей музыки · НИР МГТУ
> Сравнение 5 open-source text-to-music моделей (MusicGen, AudioLDM-M/L, MusicLDM, Riffusion) по FAD, **FAD-inf** (экстраполяция к N→∞, снимает смещение малой выборки), per-song FAD и CLAP Score · три эмбеддера: CLAP-LAION-Music, MERT-v1-95M, EnCodec · два референса: FMA-Pop и MTG-Jamendo · лидер зависит от референса: **AudioLDM-M на FMA-Pop (CLAP-FAD 0.039)**, **MusicLDM на MTG-Jamendo (0.0044)**

**[AI Team Assistant](https://github.com/SeMe4K-0/Ai-team-assistant)** &nbsp;·&nbsp; LLM-ассистент со строгим форматом ответа · [live demo](https://ai-assistant-beige-xi.vercel.app)
> Google Gemini через server-side route · **structured output через `responseSchema`** — JSON валиден по построению, парсинг в одну строку · системный промпт собирается из настроек тона и контекста команды · **prompt-evals**: скрипт прогоняет 4 синтетических запроса, включая **prompt-injection**, с проверкой структуры и content-инвариантов · параллельный RU/EN-запрос с кэшированием

**[Smoking Detection](https://github.com/SeMe4K-0/Smoking-detection-yolo-coreml)** &nbsp;·&nbsp; Детекция факта курения по видеопотоку, до инференса на устройстве
> YOLO26n на Smoking Person Detection (Roboflow), классы person / smoke · **mAP50 0.713 · mAP50-95 0.317 · Precision 0.744 · Recall 0.680** · факт курения фиксируется по пересечению bbox · экспорт в CoreML (.mlpackage) для iOS

---

<div align="center">

*Открыт к стажировкам и research-коллаборациям*

</div>
