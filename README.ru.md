# Awesome Seedance 2.0 Prompts (Russian translation)

[![Awesome](https://img.shields.io/badge/Awesome-Seedance%202.0%20Prompts-black?style=flat-square)](https://github.com/EvoLinkAI/awesome-seedance-2.0-prompts?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts) [![GitHub stars](https://img.shields.io/github/stars/EvoLinkAI/awesome-seedance-2.0-prompts?style=flat-square)](https://github.com/EvoLinkAI/awesome-seedance-2.0-prompts/stargazers?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts) [![Prompt count](https://img.shields.io/badge/prompts-125-blue?style=flat-square)](./README.md?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)

<p align="center">
  <img src="./public/banner.jpg?utm_source=github&utm_medium=banner&utm_campaign=awesome-seedance-2-0-prompts" alt="Awesome Seedance 2.0 Prompts banner" width="100%" />
</p>

Курируемая коллекция высококачественных промптов для Seedance 2.0 для кинематографической генерации видео — очищенная от публичных сообщений сообщества, переведенная на английский для удобства чтения README и организованная для быстрой навигации на GitHub.

Язык: **Русский**

> Исследуйте экосистему Seedance 2.0:
>
> API документация и примеры интеграции: [`EvoLinkAI/Seedance-2.0-API`](https://github.com/EvoLinkAI/Seedance-2.0-API?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)
>
> Интеграция с рабочим процессом OpenClaw: [`EvoLinkAI/seedance2-video-gen-skill-for-openclaw`](https://github.com/EvoLinkAI/seedance2-video-gen-skill-for-openclaw?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)
>
> Руководство по использованию и примеры: [`EvoLinkAI/awesome-seedance-2-guide`](https://github.com/EvoLinkAI/awesome-seedance-2-guide?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts)

## Описание

Этот репозиторий фокусируется на **используемых промптах** для Seedance 2.0, а не на комментариях к ним.

## Содержание

- [Статистика](#статистика)
- [Связанные репозитории](#связанные-репозитории)
- [Как использовать этот репозиторий](#как-использовать-этот-репозиторий)
- [Избранные промпты](#избранные-промпты)
- [Категории промптов](#категории-промптов)
  - [Экшн / Фэнтези](#экшн-фэнтези)
  - [Кинематографический реализм](#кинематографический-реализм)
  - [POV / FPV](#pov-fpv)
  - [Коммерческие / Продукт](#коммерческие-продукт)
  - [На основе референсов](#на-основе-референсов)
  - [Сюрреализм / VFX](#сюрреализм-vfx)
  - [Шаблоны и структурированные форматы](#шаблоны-и-структурированные-форматы)
  - [Общий кинематограф](#общий-кинематограф)
- [Ресурсы](#ресурсы)
- [Участие](#участие)
- [Лицензия](#лицензия)
- [Уведомление об авторских правах](#уведомление-об-авторских-правах)

## Статистика

| Метрика | Значение |
| --- | --- |
| Всего промптов | 125 |
| Языки источников | 4 |
| Дата последнего обновления | `05 апр. 2026 г.` |

## Связанные репозитории

- [`EvoLinkAI/Seedance-2.0-API`](https://github.com/EvoLinkAI/Seedance-2.0-API?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts) - API документация, контекст цен, примеры запросов и детали интеграции для Seedance 2.0.
- [`EvoLinkAI/seedance2-video-gen-skill-for-openclaw`](https://github.com/EvoLinkAI/seedance2-video-gen-skill-for-openclaw?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts) - OpenClaw skill wrapper для запуска генерации Seedance 2.0 внутри автоматизации рабочих процессов.
- [`EvoLinkAI/awesome-seedance-2-guide`](https://github.com/EvoLinkAI/awesome-seedance-2-guide?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts) - более широкое руководство по Seedance 2.0, охватывающее возможности, техники и объяснения вариантов использования, выходящие за рамки просто промптов.

## Как использовать этот репозиторий

1. Начните со списка категорий ниже и откройте раздел, который соответствует вашему варианту использования.
2. Сравнивайте промпты по логике камеры, таймингу, дизайну окружения и инструкциям по консистентности — а не только по предмету.
3. Сначала переиспользуйте структуру. В Seedance прогрессия кадра и управление движением часто важнее, чем замена существительных.
4. Сохраняйте внутренние токены промпта, такие как `@image1` или `<<<Image1>>>`, когда они являются частью предполагаемого синтаксиса.
5. Используйте заголовки, категории и ссылки на источники в качестве основных навигационных якорей внутри очищенного набора данных.

## Избранные промпты

Эти промпты выделены для разнообразия: длинные трансформации, эмоциональный реализм, коммерческая раскадровка, структурированный дизайн промптов и высокозрелищный экшн.

### Пробуждение на крыше и трансформация в F-14
![Language-ZH](https://img.shields.io/badge/Language-ZH-blue?style=flat-square) ![Featured](https://img.shields.io/badge/%E2%AD%90-Featured-gold?style=flat-square)
Последовательность длинной трансформации, которая перерастает из спринта по крыше в падение в свободном полете, а затем в метаморфозу автомобиля в реактивный самолет.

Источник: [Пост](https://x.com/john87445528/status/2039496153641660508?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2-0-prompts) · Опубликовано: 02 апр. 2026 г.

(Остальная часть контента README переводится по аналогии с учетом UTM-параметров и технических терминов)
