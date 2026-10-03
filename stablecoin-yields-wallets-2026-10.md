# Дохідність на стейбли: Binance Wallet / OKX Wallet / Bitget Wallet

Стан на **3 жовтня 2026**. Цифри APR/APY взяті з новин, документації та агрегаторів (дати вказані).
Ставки плаваючі, тож перед депозитом перевір актуальне значення в самому гаманці.

**Бенчмарк:** ставка ФРС близько **3.6%** (вересень 2026), Sky Savings Rate (sUSDS) **3.60%**.
Усе, що для стейбла помітно вище **~6%**, означає або субсидію/промо від гаманця, або додатковий ризик
(леверидж, funding, молодий чейн, концентрація застави).

## Таблиця

Надійність оцінена суб'єктивно за шкалою 1–5 (5 = найнадійніше).

| # | Гаманець | Продукт / протокол | Актив, мережа | APR / APY (орієнтовно) | Звідки дохід | Надійність | Коментар / ризики |
|---|---|---|---|---|---|---|---|
| 1 | **Bitget Wallet** | Stablecoin Earn Plus (Aave v3) | USDC, Base | **≥10%** на перші $1k–10k (ліміт у джерелах різний), понад ліміт приблизно ставка Aave **~3.6%** | Відсотки Aave плюс субсидія Bitget | ⭐⭐⭐⭐ | Найкраще співвідношення ризику й доходу на невелику суму. Виведення миттєве. Субсидію можуть урізати, ліміт перевір в апці. Є Protection Fund на $300M. |
| 2 | **Bitget Wallet** | Gauntlet USDC Prime (Morpho, чейн Morph) | USDC, Morph L2 | **до ~18%** (запуск 3 серпня 2026, з інсентивами) | Позики під заставу bgBTC плюс інсентиви | ⭐⭐ | Висока ставка, бо молодий чейн і застава лише bgBTC (концентрація). Підходить тільки на невелику частку. |
| 3 | **Bitget Wallet** | Kamino (Solana) | USDC / USDT, Solana | база **~3–5%**, на старті були промо до 50% | Lending | ⭐⭐⭐⭐ | Kamino — топовий lending на Solana. Промо-ставки короткі. |
| 4 | **Bitget / OKX / Binance** | Aave v3 (Ethereum, Base, Arbitrum, BSC) | USDC / USDT | **~3.2–3.7%** (Ethereum 3.57%, Base 3.65%, вересень 2026) | Lending | ⭐⭐⭐⭐⭐ | Найнадійніший DeFi lending, проте дохід лише на рівні T-bills. |
| 5 | **OKX Wallet** | USDG Hold & Earn (просто тримати USDG) | USDG (Paxos) | **до 3.5%** | Резерви USDG / Global Dollar Network | ⭐⭐⭐⭐⭐ | Немає смарт-контрактного ризику протоколу, ризик лише емітента (регульований Paxos). Діють регіональні обмеження. |
| 6 | **OKX Wallet** | USDG на X Layer | USDG, X Layer | **до 3.85%** | Ті самі ревард-програми USDG | ⭐⭐⭐⭐ | Додається ризик L2 від OKX. |
| 7 | **OKX Wallet** | DeFi Earn → Morpho (Steakhouse / Gauntlet) | USDC / USDT, Ethereum / Base | **~4–4.3%** (Steakhouse USDC 4.25%) | Curated lending | ⭐⭐⭐⭐ | Хороший компроміс. Кампанія Katana (KAT) завершилась у травні 2026. |
| 8 | **OKX Wallet** | DeFi Earn → Ethena sUSDe | USDe, Ethereum | **~5.0%** (15 вересня 2026) | Funding perp-позицій (basis trade) | ⭐⭐⭐ | Дохід залежить від funding і може впасти до нуля. Був ризик депегу в стрес-сценаріях. |
| 9 | **OKX Wallet** | DeFi Earn → Sky sUSDS | USDS, Ethereum | **3.60%** | T-bills / RWA (Sky) | ⭐⭐⭐⭐ | Стабільна ставка, але не вища за ФРС. |
| 10 | **OKX Wallet** | Aave v3 на X Layer | USDT0, X Layer | **~0.65%** | Lending (низька утилізація) | ⭐⭐⭐⭐ | **Не варто**: ставка надто низька. |
| 11 | **Binance Wallet** | Kamino Vaults (DeFi tab, з 3 вересня 2026) | USDC (RockawayX), PYUSD (Sentora), Solana | база **~3–5%** плюс тимчасовий буст із пулу $300K | Curated lending плюс інсентиви | ⭐⭐⭐⭐ | Понад $100M депозитів з Binance Wallet за 9 днів. Буст тимчасовий. |
| 12 | **Binance Wallet** | Simple Yield → Venus | USDT / USDC, BNB Chain | **~2.1% / ~2.5%** | Lending | ⭐⭐⭐⭐ | Найбільший lending на BSC, але ставка низька. |
| 13 | **Binance Wallet** | Concrete USDT Vault | USDT, Ethereum | на запуску **до 8.5%**, зараз net **~2.25%** | Дельта-нейтральні стратегії (perp DEX, lending, AMM) | ⭐⭐⭐ | Ставка сильно впала, стратегія складна. Зараз невигідно. |
| 14 | **Binance Wallet** | Plume nBASIS (RWA) | стейбли → токенізовані T-bills / carry funds (Invesco, Bitwise) | **~3.5%** | RWA | ⭐⭐⭐ | Перший RWA у Binance Wallet. Перевір умови й строки виведення. |
| 15 | **Binance Wallet** | Lista DAO lending vaults (USD1 / USDT / U) | BNB Chain | змінна, свіжих даних немає | Lending (curators: Gauntlet, MEV Capital, Re7) | ⭐⭐⭐ | Були епізоди аномальних borrow rate і депег USDX у вкладених ринках. Ставку дивись в апці. |

> Довідково (це біржа, а не гаманець): Binance Simple Earn USDT ~1.5% + бонус 3% на перші 200 USDT,
> локи до ~6–7.7%; OKX Simple Earn ~3–5%; Bitget On-chain Earn (Morpho, Arbitrum): USDC до 12%, USDT 7%.

## Висновки

1. **Bitget Wallet Earn Plus (USDC на Base)**: найвигідніший варіант на суму до ліміту (≥10% на Aave плюс субсидія).
   Суму понад ліміт тут не тримай, бо далі йде звичайні ~3.6%.
2. **OKX Wallet USDG Hold** (до 3.5–3.85%): найпростіший і найменш ризиковий варіант, працює як «кеш».
3. **Morpho Steakhouse/Gauntlet через OKX DeFi Earn** (~4–4.3%) та **Aave** (~3.5%): основа для великих сум.
4. **sUSDe** (~5%): тільки частку й з розумінням funding-ризику.
5. **Gauntlet USDC Prime на Morph** (до 18%) та промо-бусти Kamino: тільки невелика ризикова частка (≤10–15%), і слідкуй за зміною ставки.
6. **Venus, Concrete і Aave на X Layer зараз невигідні**: ставка нижча за безризикову.

### Приклад розподілу
- 30–40%: Bitget Earn Plus (до ліміту), решта USDC іде нижче.
- 30–40%: Morpho Steakhouse / Aave (OKX або Bitget DeFi Earn).
- 10–20%: USDG у OKX Wallet (якщо доступно в регіоні).
- 10%: sUSDe.
- ≤10%: Gauntlet на Morph або Kamino з бустом.

Очікуваний блендований APY приблизно **5–6.5%**, залежно від суми (що більший депозит, то менша частка субсидованих 10%).

## Загальні ризики
- Ризик смарт-контрактів і оракулів, навіть в Aave/Morpho.
- Депег стейбла (USDe, USD1, USDG, PYUSD) і ризик емітента.
- Субсидовані ставки (Bitget 10%, бусти) можуть змінитися будь-коли.
- Молоді L2 (Morph, X Layer): ризик мосту і секвенсера.
- Регіональні обмеження (USDG rewards, деякі продукти недоступні для певних країн).

## Джерела
- Bitget Wallet Earn Plus: https://www.globenewswire.com/news-release/2025/09/09/3147275/0/en/bitget-wallet-partners-with-aave-to-launch-stablecoin-earn-plus-a-long-term-flexible-10-yield-product.html , https://web3.bitget.com/en/stablecoinEarn , https://cryptorank.io/news/feed/abcb4-bitget-wallet-stablecoin-earn-plus-10-percent-usdc
- Bitget / Gauntlet / Morph: https://www.blockhead.co/2026/08/07/bitgets-yield-vaults-on-morph-cross-55m-in-tvl-one-week-after-launch/ , https://ffnews.com/news/bitget-unlocks-institutional-defi-yield-for-125m-users-via-morph-gauntlet-and-morpho-partnership
- Bitget × Kamino: https://ffnews.com/newsarticle/cryptocurrency/bitget-wallet-solana-staking/
- Bitget × Morpho (біржа): https://www.bitget.com/blog/articles/bitget-morpho-arbitrum-upgraded-onchain-earn
- OKX USDG: https://web3.okx.com/learn/usdg-hold-earn , https://web3.okx.com/learn/usdg-xlayer , https://www.okx.com/en-us/learn/earn-apy-usdg
- OKX On-chain Earn / Aave X Layer: https://www.okx.com/en-us/help/launch-of-aave-usdt-eth-x-layer-on-chain-earn , https://aavescan.com/xlayer-v3/usdt0 , https://www.theblock.co/post/395594/aave-goes-live-okx-x-layer
- Binance Wallet Kamino: https://solanacompass.com/news/kamino-finance-vaults-go-live-on-binance-wallet-defi-tab-with-300k-rewards , https://solanacompass.com/news/kamino-vaults-cross-100m-in-deposits-from-binance-wallet-users
- Binance Wallet Concrete: https://www.galvnews.com/concrete-integrates-with-binance-wallet-to-enable-access-to-institutional-grade-usdt-yield/article_97351af3-9a71-5384-95ca-c8fd92d618d2.html , https://infoseemedia.com/blog/concrete-usdt-yield-in-binance/ , https://www.stakingrewards.com/defi/0x0e609b710da5e0aa476224b6c0e5445ccc21251e
- Binance Wallet Plume: https://www.crowdfundinsider.com/2026/07/290552-binance-wallet-integrates-plumes-yield-vault-opening-institutional-grade-rwa-opportunities-to-self-custody-users/
- Binance Wallet Simple Yield (Venus / Aave): https://www.binance.com/en/support/faq/what-are-yield-and-simple-yield-on-binance-web3-wallet-earn-3cd105b940ef4a438209be00b169126a
- Lista DAO: https://www.theblock.co/press-releases/lista-lending-goes-cross-chain-with-ethereum-launch-and-expands-curator-network-with-gauntlet-and-rockawayx-399420 , https://blockchain.news/flashnews/lista-dao-flags-abnormally-high-borrow-rates-in-mev-capital-usdt-vault-and-re7-labs-usd1-vault
- Aave / Morpho / sUSDS / sUSDe / ФРС: https://eco.com/support/en/articles/15182156-usdc-yield-in-2026-where-to-earn-interest-on-usdc , https://eco.com/support/en/articles/15197989-susds-yield-explained-2026-sky-s-savings-token , https://app.morpho.org/ethereum/vault/0xBEEF01735c132Ada46AA9aA4c54623cAA92A64CB/steakhouse-usdc
- Venus: https://www.kucoin.com/news/insight/USDC/6a5c96ffdd913100071cc98e
- Binance Earn (біржа): https://coinbureau.com/review/binance-earn-review
