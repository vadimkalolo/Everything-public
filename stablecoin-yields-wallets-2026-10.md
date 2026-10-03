# Куди закинути стейбли: фінальна таблиця (жовтень 2026)

Стан на **3 жовтня 2026**. Ставки взяті з новин, документації протоколів і агрегаторів
(здебільшого знімки за серпень–вересень 2026). Живі API (DefiLlama, Aave, Morpho, Kamino) і сторінки гаманців
із середовища були недоступні, тому **перед депозитом звір ставку в апці**.

**Бенчмарк:** ставка ФРС ~**3.6%**, Sky Savings Rate **3.60%**. Вище **~6%** на стейблі означає або субсидію від гаманця
чи протоколу, або додатковий ризик.

**Позначки ризику:** 🟢 низький · 🟡 середній · 🟠 підвищений · 🔴 високий

---

## A. Продукти всередині гаманців

Тільки те, що є в самих гаманцях (Bitget **Wallet**, OKX **Wallet**, Binance **Wallet**), біржові Earn сюди не входять.

| Гаманець | Продукт / протокол | Актив, мережа | APR / APY | Звідки дохід | Ліквідність | Ризик | Головні ризики / коментар |
|---|---|---|---|---|---|---|---|
| **Bitget Wallet** | Stablecoin Earn Plus (Aave v3) | USDC, Base | **≥10%** до ліміту (у джерелах $1k або $10k), понад ліміт ~3.6% | Aave + субсидія Bitget Wallet | Миттєво | 🟢 | Смарт-контракти Aave і мережа Base. Субсидію можуть урізати будь-коли. Є Protection Fund на $300M. **Найкращий варіант у гаманцях.** |
| **Bitget Wallet** | Gauntlet USDC Prime (Morpho, мережа Morph) | USDC, Morph L2 | **до ~18%** на старті (серпень 2026), зараз імовірно нижче | Позики під заставу bgBTC + інсентиви | Залежить від утилізації | 🟠 | Молодий L2 (міст, секвенсер). Застава лише bgBTC. Інсентиви тимчасові. |
| **Bitget Wallet** | Kamino | USDC / USDT, Solana | ~**3–5%** (на старті були промо) | Lending | Майже миттєво | 🟡 | Ризики Kamino і Solana. Промо-ставки тримаються недовго. |
| **Bitget Wallet** | Aave (мультичейн) | USDC / USDT | ~**3.5%** | Lending | Миттєво | 🟢 | Дохід на рівні ставки ФРС. |
| **OKX Wallet** | USDG Hold & Earn | USDG | **до 3.5%** | Ревард-програма USDG (Paxos / Global Dollar) | Миттєво (просто тримаєш) | 🟢 | Ризик лише емітента. У березні 2026 ставку знизили з 5%. Є регіональні обмеження. |
| **OKX Wallet** | USDG на X Layer | USDG, X Layer | **до 3.85%** | Ревард-програма USDG | Клейм щотижня | 🟡 | Додається ризик L2 від OKX. |
| **OKX Wallet** | DeFi Earn → Morpho Steakhouse / Gauntlet | USDC / USDT, Ethereum / Base | ~**4–4.3%** | Curated lending | Залежить від утилізації | 🟢🟡 | Ризики куратора і смарт-контрактів Morpho. |
| **OKX Wallet** | DeFi Earn → Aave v3 (Ethereum / Base / Arbitrum) | USDC / USDT | ~**3.5–3.7%** | Lending | Миттєво | 🟢 | Еталон надійності. |
| **OKX Wallet** | DeFi Earn → Aave на X Layer | USDT0 | ~**0.65%** | Lending | Миттєво | 🟡 | ❌ Ставка надто низька, не варто. |
| **Binance Wallet** | Kamino Vaults (DeFi tab) | USDC (RockawayX), PYUSD (Sentora), Solana | ~**3–5%** база (Sentora PYUSD показувала ~7% з бустом) | Curated lending / RWA | Майже миттєво | 🟡 | **Буст-кампанія (30 днів від 3 вересня) закінчується ~3 жовтня.** |
| **Binance Wallet** | Simple Yield → Aave | USDC / USDT | ~**3.5%** | Lending | Миттєво | 🟢 | Те саме, що Aave напряму. |
| **Binance Wallet** | Simple Yield → Venus | USDT / USDC, BNB Chain | ~**2.1–2.5%** | Lending | Миттєво | 🟡 | ❌ Ставка низька. |
| **Binance Wallet** | Plume nBASIS | стейбли → токенізовані T-bills / carry funds (Invesco, Bitwise) | ~**3.5%** | RWA | Вікно викупу | 🟡 | Ризики RWA-емітента і мережі Plume. |
| **Binance Wallet** | Concrete USDT Vault | USDT, Ethereum | ~**2.25%** (на старті до 8.5%) | Дельта-нейтральні стратегії | Залежить від стратегії | 🟠 | ❌ Складна стратегія при низькій ставці. |
| **Binance Wallet** | Lista DAO vaults | USD1 / USDT / U, BNB Chain | свіжих даних немає | Lending | Залежить від утилізації | 🟠 | Були стрибки borrow rate. Депег USDX зачепив суміжні ринки. |

---

## B. Поза цими гаманцями

Це DeFi-протоколи, які працюють з будь-яким self-custody гаманцем (Bitget, OKX чи Binance Wallet через dApp-браузер або WalletConnect), а також кілька CeFi-варіантів.

| Де | Продукт | Актив, мережа | APR / APY | Звідки дохід | Ліквідність | Ризик | Головні ризики / коментар |
|---|---|---|---|---|---|---|---|
| **Jupiter Lend** | USDC Earn | USDC, Solana | **~5.5%** (середнє за 30 днів ~4.8%) | Lending | Майже миттєво | 🟡 | Найбільший lending на Solana ($2.4B депозитів). Протокол відносно новий. |
| **Fluid** | USDC lending | USDC, Ethereum / Arbitrum | **~5.2%** (Ethereum), ~4.4% (Arbitrum) | Lending (smart collateral / debt) | Залежить від утилізації | 🟡 | Команда Instadapp. Механіка складніша, ніж в Aave. |
| **Maple** | syrupUSDC / syrupUSDT | USDC / USDT, Ethereum | **~5.0%** | Overcollateralized позики інституціоналам (off-chain) | Черга на виведення (зазвичай години–дні) | 🟡 | Кредитний ризик позичальників і ризик Maple. Найбільший USDC-пул ($2.6B). |
| **Ethena** | sUSDe | USDe, Ethereum | **~5–5.4%** (середнє за 30 днів ~4.1%) | Funding rate на ф'ючерсах (basis) | Анстейк 7 днів або swap | 🟠 | Негативний funding, ризик бірж-контрагентів, депег у стрес-сценаріях. |
| **Pendle** | PT-sUSDe / PT-USDe | Ethereum | **~5% фіксовано** до дати експірації | Фіксація майбутньої дохідності | До експірації (або продати PT з ризиком ціни) | 🟠 | Ризик USDe плюс ризик Pendle. Добре підходить, щоб зафіксувати ставку. |
| **Falcon** | sUSDf | USDf | ~**6–9%** (дані на березень 2026, ставка плаваюча) | Funding / basis, різна застава | Кулдаун на анстейк | 🔴 | Синтетичний долар, CeDeFi-модель. Є бусти з локом на 3–12 місяців. |
| **Kamino** (напряму) | K-Lend USDC | USDC, Solana | **~1.6–7.2%** (залежить від ринку) | Lending | Майже миттєво | 🟡 | Обирай Main market. Isolated markets ризиковіші. |
| **HyperEVM** (Felix, HyperLend) | USDC lending | USDC, Hyperliquid EVM | **~3–8%**, у волатильні періоди вище | Lending під плечі трейдерів | Залежить від утилізації | 🟠 | Молода екосистема. Ризик мосту і смарт-контрактів. |
| **Aave на Plasma** | USDT0 supply | USDT0, Plasma | **~3.7%** | Lending (утилізація 92%) | Може бути обмежена при високій утилізації | 🟡 | Молода мережа Plasma. |
| **Spark** | sUSDC | USDC, Ethereum / L2 | **~3.65%** | Sky Savings Rate | Миттєво | 🟢 | Ризики Sky / Spark. |
| **Sky** | sUSDS | USDS, Ethereum | **3.60%** | T-bills / RWA / CDP | Миттєво | 🟢 | Ризик governance Sky. |
| **Ondo** | USDY | Ethereum / Solana та ін. | **~3.5%** | Казначейські облігації США | Mint/redeem з KYC, вторинний ринок | 🟢 | Не для США. Потрібен KYC на mint. |
| **Coinbase** (CeFi) | USDC Rewards | USDC | **~4.1%** (4.5% з Coinbase One) | Шеринг доходу від резервів USDC | Миттєво | 🟢🟡 | Кастодіальний варіант. Доступність залежить від регіону. |
| **Coinbase** (on-chain) | USDC Lend через Morpho (Steakhouse) | USDC, Base | **~4–6%**, на старті було до 10.8% | Curated lending + MORPHO | Залежить від утилізації | 🟡 | Обмеженого регіону (США без NY, Бермуди та ін.). |

---

## Топ-вибір (ризик / дохід)

1. **Bitget Wallet Earn Plus (USDC на Base)**: **≥10%** на суму до ліміту. Перша сума йде сюди.
2. **Jupiter Lend USDC (~5.5%)** і **Fluid USDC (~5.2%)**: найвища ставка без субсидій серед перевірених lending-протоколів.
3. **Maple syrupUSDC (~5%)**: стабільно, але виведення може зайняти час.
4. **Morpho Steakhouse (~4.25%) / Aave (~3.6%)**: найнадійніша основа для великих сум.
5. **USDG в OKX Wallet (до 3.5%)**: простий «кеш» без ризику DeFi-протоколу.
6. **Pendle PT (~5% фіксовано)**: якщо хочеш зафіксувати ставку на кілька місяців.
7. ⚠️ sUSDe, sUSDf, Gauntlet на Morph, HyperEVM: тільки невелика ризикова частка.
8. ❌ Не варто: Venus, Concrete, Aave на X Layer, а також промо-бусти після завершення кампанії.

## Приклад розподілу (наприклад, $20k)

| Частка | Куди | APR | Ризик |
|---|---|---|---|
| ліміт Earn Plus (до $10k) | Bitget Wallet Earn Plus | ~10% | 🟢 |
| 25% | Jupiter Lend USDC або Fluid USDC | ~5.2–5.5% | 🟡 |
| 20% | Maple syrupUSDC | ~5% | 🟡 |
| 20% | Morpho Steakhouse / Aave | ~3.6–4.3% | 🟢 |
| 10% | sUSDe або Pendle PT | ~5% | 🟠 |
| решта | USDG в OKX Wallet (кеш) | ~3.5% | 🟢 |

Очікуваний блендований APY **~5.5–7%**. На менших сумах вище (більшу частку дає субсидія Bitget), на більших нижче.

## Загальні ризики

- **Смарт-контракти та оракули**: стосується навіть Aave і Morpho. Не тримай усе в одному протоколі.
- **Депег стейбла**: USDe, USDf, USD1, USDG, PYUSD. Найнадійніші USDC та USDT.
- **Субсидовані та промо-ставки** (Bitget 10%, бусти Kamino чи Morpho) можуть зникнути без попередження.
- **Молоді мережі** (Morph, X Layer, Plasma, HyperEVM): ризик мосту і секвенсера.
- **Ліквідність**: при утилізації 90%+ виведення може бути тимчасово недоступне. Maple, Ethena і Pendle мають затримки або ризик ціни.
- **Регіони і KYC**: USDG rewards, Coinbase, Ondo доступні не всім.
- **Фішинг**: заходь у протоколи тільки з офіційних посилань. Після роботи відкликай апруви (revoke).

## Джерела

**Bitget Wallet**
- Earn Plus × Aave: https://www.globenewswire.com/news-release/2025/09/09/3147275/0/en/bitget-wallet-partners-with-aave-to-launch-stablecoin-earn-plus-a-long-term-flexible-10-yield-product.html
- Сторінка продукту: https://web3.bitget.com/stablecoinEarn
- CryptoRank про Earn Plus: https://cryptorank.io/news/feed/abcb4-bitget-wallet-stablecoin-earn-plus-10-percent-usdc
- Gauntlet на Morph (TVL після запуску): https://www.blockhead.co/2026/08/07/bitgets-yield-vaults-on-morph-cross-55m-in-tvl-one-week-after-launch/
- Morph × Gauntlet × Morpho: https://ffnews.com/news/bitget-unlocks-institutional-defi-yield-for-125m-users-via-morph-gauntlet-and-morpho-partnership
- Kamino: https://ffnews.com/newsarticle/cryptocurrency/bitget-wallet-solana-staking/

**OKX Wallet**
- USDG Hold & Earn: https://web3.okx.com/learn/usdg-hold-earn
- USDG на X Layer: https://web3.okx.com/learn/usdg-xlayer
- Зниження ставки USDG: https://cryptobriefing.com/okx-usdg-apy-us-vip-rewards/
- Aave на X Layer: https://aavescan.com/xlayer-v3/usdt0 , https://www.theblock.co/post/395594/aave-goes-live-okx-x-layer
- On-chain Earn: https://www.okx.com/en-us/learn/what-is-okx-onchain-earn

**Binance Wallet**
- Kamino, запуск: https://solanacompass.com/news/kamino-finance-vaults-go-live-on-binance-wallet-defi-tab-with-300k-rewards
- Kamino, $100M депозитів: https://solanacompass.com/news/kamino-vaults-cross-100m-in-deposits-from-binance-wallet-users
- Concrete: https://www.galvnews.com/concrete-integrates-with-binance-wallet-to-enable-access-to-institutional-grade-usdt-yield/article_97351af3-9a71-5384-95ca-c8fd92d618d2.html , https://www.stakingrewards.com/defi/0x0e609b710da5e0aa476224b6c0e5445ccc21251e
- Plume nBASIS: https://www.crowdfundinsider.com/2026/07/290552-binance-wallet-integrates-plumes-yield-vault-opening-institutional-grade-rwa-opportunities-to-self-custody-users/
- Simple Yield: https://www.binance.com/en/support/faq/what-are-yield-and-simple-yield-on-binance-web3-wallet-earn-3cd105b940ef4a438209be00b169126a
- Lista DAO: https://blockchain.news/flashnews/lista-dao-flags-abnormally-high-borrow-rates-in-mev-capital-usdt-vault-and-re7-labs-usd1-vault
- Venus: https://www.kucoin.com/news/insight/USDC/6a5c96ffdd913100071cc98e

**DeFi та інше**
- Огляд дохідності USDC (Aave, Fluid, Maple, Kamino): https://eco.com/support/en/articles/15182156-usdc-yield-in-2026-where-to-earn-interest-on-usdc
- Sky / sUSDS: https://eco.com/support/en/articles/15197989-susds-yield-explained-2026-sky-s-savings-token
- Jupiter Lend: https://defillama.com/yields/pool/d783c8df-e2ed-44b4-8317-161ccc1b5f06 , https://solanacompass.com/news/jupiter-lend-hits-241-billion-in-total-deposits-a-new-all-time-high
- Maple: https://maple.finance/insights/syrupusdc-and-syrupusdt-built-for-scale
- Pendle: https://cryptobriefing.com/pendle-susde-yield-3-month-high/
- Spark: https://yieldradar.org/yield/spark-savings
- Falcon: https://www.kucoin.com/blog/usdf-falcon-yield-bearing-stablecoin-2026
- Ondo USDY: https://ondo.finance/usdy
- HyperEVM: https://hyperliquidguide.com/ecosystem/hyperliquid-earn-usdc
- Aave на Plasma: https://aavescan.com/plasma-v3/usdt0
- Coinbase × Morpho: https://www.theblock.co/post/371281/coinbase-usdc-onchain-lending
- Morpho Steakhouse USDC: https://app.morpho.org/ethereum/vault/0xBEEF01735c132Ada46AA9aA4c54623cAA92A64CB/steakhouse-usdc
