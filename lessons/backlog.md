# Backlog

What was deliberately left out, and why it is not being done now.

## How to write a line

```markdown
- **What.** Why it is needed. Why not now.
```

Three fields and not one more. **"Why not now" matters most of the two others:** it is what
separates a decision from forgetfulness. A line without it comes back as a reproach six weeks
later, when nobody remembers whether it was weighed or dropped.

## Lines

- **The plan of fifteen sections.** The navigation titles and the glossary cannot be written
  until the sections are known. Not now: the plan of sections is the Architect's to approve,
  and inventing fifteen names while typing the first two pages would fix the shape of the
  whole site as a side effect of step 1.
- **The glossary (`ru/glossary.html`).** A reader needs one place for SLI, SLO, error budget,
  percentile, cardinality. Not now: it follows the plan of sections, because a glossary
  assembled before the sections duplicates terms the sections will introduce.
- **English, Ukrainian and German.** Three languages are stubs pointing at the Russian pages.
  Not now: they follow the acceptance of the Russian original, so a returned page is retyped
  once instead of four times.
- **Pages `ru/02.html` ... `ru/15.html`, the three example pages and the question banks.**
  The site is only useful whole. Not now: step 1 proves the shape of a page and the claim
  mechanism on two pages, and that proof is cheaper to return than fifteen.
- **The mechanism that executes PromQL claims (`promtool` or `prometheus` in `docker`).**
  Any PromQL line on a page has to be run before it is published. Not now: nothing is pulled
  into the system without the Architect's word, and the first topic can be carried by
  arithmetic on the Python standard library alone.

## Строки смены 20.10.2026

- **Пятнадцать названий разделов в разметке и в навигаторе.** План принят и записан в
  `lessons/step-1.md`, но страницы и навигатор всё ещё говорят «Раздел N», и читатель видит
  метки. Не сейчас: смена ставила планы на четыре сайта, а перенос названий в 68 страниц -
  это отдельная поставка с пересборкой меты и проверкой, и половина переноса хуже метки.
- **Текст страниц.** Сайт без текста не сайт. Не сейчас: решение Conductor'а на эту смену -
  четыре живых скелета с планом дороже одной страницы текста на одном сайте.
- **Словарь понятий.** Термины подсвечиваются на страницах скриптом `assets/terms.js`, и без
  словаря подсветка нема. Не сейчас: словарь пишется из терминов написанных страниц, а
  страниц ещё нет; придуманный заранее словарь придётся переписывать.
- **Английская, украинская и немецкая версии.** Серия обещает четыре языка. Не сейчас:
  перевод идёт с принятого русского оригинала, иначе переводится черновик.
- **Платформа для примеров 10-12.** Панель, SLO и разбор инцидента показываются на чём-то
  конкретном, а сайт теперь не вендорский. Не сейчас: выбор вендора или локального стенда
  (Prometheus и Grafana в `docker`) - решение Conductor'а, а до разделов 07-09 примеры не нужны.
- **`search = SLO` в `site.conf`.** Сейчас стоит `Раздел`: слово дымового теста обязано
  находиться сегодня. Не сейчас: меняется вместе с первой написанной страницей.
- **Судьба папки `courses/newrelic`.** Она заштампована до поправки, когда пятым сайтом ещё
  считался `newrelic`. Не сейчас: удалять её или оставить - решение Conductor'а, и это не
  решение исполнителя смены.
