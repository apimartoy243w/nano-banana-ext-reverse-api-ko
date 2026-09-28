# Nano Banana Ext — 리버스 route (한국어)

> **1K $0.0125** · model ID `gemini-2.5-flash-image-preview` · **리버스/역설계** route.

**[요금 보기](https://go.apimart.ai/k-2a99ef)** · **[API 키 발급](https://go.apimart.ai/k-d1d0c0)**

nano-banana-ext-reverse-api-ko 는 **리버스** Nano Banana Ext 라우트입니다. 호출 ID 는 `gemini-2.5-flash-image-preview` 이며, 공식 라우트 (`nano-banana (gemini-2.5-flash-image-preview-official)`) 와 병행 제공되어 단가가 더 낮습니다.。

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.0125 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gemini-2.5-flash-image-preview","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **리버스** | `gemini-2.5-flash-image-preview` | 1K $0.0125 |
| 공식 라우팅 | `nano-banana (gemini-2.5-flash-image-preview-official)` | official list price, billed at ×0.8 group ratio |


## Keywords

`nano-banana-ext` · `gemini-2.5-flash-image-preview` · `리버스` · `역설계` · `AI API 게이트웨이` · `API 중계` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

