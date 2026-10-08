---
name: vietnam-global-trade-monday
description: Produce a source-verified Vietnamese Monday global trade report for Vietnam welding consumables (HS 8311/7229) and MDF/HDF (HS 4411), including competitor comparisons, trade measures, freight, prices and demand. Use for this recurring report or a focused follow-up such as Check EU within this workflow.
---

# Vietnam global trade Monday report

## Trigger and scope

Activate on `$vietnam-global-trade-monday`, “báo cáo thương mại toàn cầu thứ Hai”, “Monday global trade report for Vietnam welding consumables and MDF/HDF”, or an equivalent request. A focused follow-up such as “Check EU” activates only the requested market/topic; do not force the full report format onto that follow-up.

Produce a decision-useful report in Vietnamese for a Vietnamese exporter. Cover welding consumables HS 8311, relevant steel welding wire HS 7229, and MDF/HDF within HS 4411. Product names such as ER70S-6/SG2, EM12K and EL12 are examples, not binding tariff classifications. Verify composition, dimensions, coating, processing and destination tariff subheading before assigning a measure. HS 4411 contains products beyond MDF/HDF; distinguish density, thickness and finishing when relevant.

This skill defines a recurring workflow, not an installed schedule. Run when invoked; create a Monday automation only when the user asks, using the host's supported scheduler and Asia/Ho_Chi_Minh timezone. Do not publish, email, push to GitHub or create a schedule solely because the skill is loaded.

## Research workflow

1. Set the actual report date in Asia/Ho_Chi_Minh, unless the user specifies another timezone or historical cutoff. Default to developments since the previous report, or the preceding seven days when unavailable. Separate publication date, event date and effective date. Never backdate a Sunday report to Monday or use information published after a historical cutoff.
2. Read the previous report if supplied to identify changes and corrections. Treat prior conversations, stored reports and search snippets as leads, never evidence. Do not preserve any old tariff, quota, deadline, regulation number or market figure without current verification.
3. Research all coverage lanes below. Use live web access or authoritative connected resources. Read underlying documents and annexes, not just search summaries. Consult [references/source-map.md](references/source-map.md) for discovery starting points.
4. Keep a compact evidence ledger using [references/evidence-template.md](references/evidence-template.md): claim, product/origin, dates, status, document identifier, direct URL, supporting section and limitations. Deduplicate syndicated news and resolve contradictory sources against the operative official text. Retain unresolved contradictions explicitly.
5. Compare Vietnam with China, Turkey/Türkiye, Malaysia and India using the same product, destination, period and units. Cover all four across the report; if data are unavailable, say which comparison cannot be supported. Do not invent rankings or fill missing prices. Explain practical implications for export quotations, target markets, purchasing or origin documentation.
6. Select 6–10 concise insights by commercial relevance, then verify every number and legal claim against the ledger. Give MDF/HDF at least two insights and welding at least two. An insight may cover several lanes. Include a concise unchanged/unverified status where a required lane has no new finding; do not fabricate news to meet the count.

## Required coverage lanes

- **EU steel scope and remedies:** current steel safeguard/regulation and product annexes; HS 7229 scope review if one exists; relevant AD/CVD on welding consumables, wire and upstream wire rod; country/company applicability; origin, melt-and-pour and documentary requirements where applicable. Distinguish upstream inputs from finished products and CN/TARIC from HS headings.
- **US Section 301 and 232:** distinguish each investigation and final action; verify current HTSUS, Chapter 99, exclusions, effective dates and stacking rules. Check applicability separately for 8311, 7229 and 4411. Do not add duties based on a broad sector label or investigation announcement. Review relevant AD/CVD separately when material.
- **UAE–Vietnam CEPA:** distinguish signing, ratification and entry into force; inspect product-specific tariff staging, rules of origin, proof of origin and direct-consignment conditions. Verify eligibility for the actual UAE tariff line before claiming savings. Note GCC implications without assuming UAE preferences apply across the GCC.
- **Freight/logistics:** recent relevant Asia–EU, US and UAE/GCC routes, with ASEAN/Africa/Latin America when material. State route, quote/index date, currency, container size and basis; distinguish global or Shanghai benchmarks from a Vietnam port quotation. Address surcharge/transit disruption only when verified.
- **Price, supply and demand:** welding wire/rod and relevant steel inputs; MDF/HDF, wood fibre/resin inputs and furniture/construction demand. Distinguish direct product evidence from proxies such as crude steel or HRC. Include destination opportunities or trade diversion as labelled inference, never a verified causal fact without evidence.
- **Competitiveness:** Vietnam versus China, Turkey, Malaysia and India across tariffs, remedies, price/supply or demand. Avoid implying that a remedy against China automatically grants Vietnam exemption or establishes Vietnamese origin.

## Verification rules

- Legal claims require an official operative notice/regulation, annex or customs guidance. Record whether the measure is proposed, under consultation/investigation, provisional, definitive, effective, expired or under review. A consultation closing date is not adoption; adoption is not automatically entry into force. An expiry review may affect continuation: verify rather than assume expiration.
- For a duty/quota claim check exact product definition, tariff line, origin, exporter-specific rate where relevant, effective period, exclusions and amendments. “ex” codes cover only the described subset. Do not apply a steel quota or melt-and-pour rule to all of HS 7229/8311 without confirmed scope. Never assume Section 301/232/AD/CVD duties simply add; verify interaction and calculation basis.
- “No new action found” must identify the authorities checked and cutoff. It is a bounded search result, not proof that no measure exists anywhere.
- Use official statistics and established market publishers for prices, freight and demand. Report the latest available observation with its date; do not label old monthly data as this week's movement. Normalize currency/unit/Incoterm before comparing; otherwise flag non-comparability. Do not infer welding wire prices directly from HRC or MDF prices from unrelated wood panels.
- Prefer official sources for policy and two independent reputable sources for a material disputed market claim. A single decisive official document can establish a legal fact. Paywalled or inaccessible text cannot support an exact claim unless an accessible authoritative source confirms it.
- Separate **Đã xác minh**, **Nhận định** and **Chưa xác minh** when status would otherwise be ambiguous. State uncertainty plainly. Never fabricate claims, source titles, links, regulation identifiers, dates, tariffs, forecasts or quotations.
- If live verification is unavailable, state “Chưa thể cập nhật nguồn trực tiếp” and provide a clearly labelled incomplete research outline. Do not present cached claims as a verified current report or invent sources to satisfy the requested link count.

## Vietnamese output contract

Use [references/report-template.md](references/report-template.md) when drafting the full report.

- Start exactly with `Cập nhật: DD/MM/YYYY`, using the actual date.
- Deliver **6–10 numbered or bulleted insights**, typically 2–3 short sentences each. Begin with a bold topic, state the verified change/status, then explain its implication for Vietnam. Prioritize material developments, with dates and units where necessary.
- Provide **5–8 unique reputable direct source links**, cited beside the claims they support using `[Tên nguồn – tài liệu/ngày](URL)`. Reuse a link where appropriate; avoid an extra duplicate bibliography. A claim needing an additional source must be retained only if support fits the contract, otherwise narrow or omit it; never weaken verification to fit a count. Discovery homepages are not substitutes for direct evidence links.
- Ensure every mandatory lane is represented, including explicit no-change/limited-data status if appropriate. Avoid filling the report with generic steel news at the expense of HS 4411.
- End with one short `Ưu tiên tuần tới:` line naming actionable verified deadlines or monitoring priorities. Do not invent deadlines. Clearly correct any material error inherited from the prior report.
- Focused follow-ups may be shorter and use as many direct links as needed. Preserve source verification and scope distinctions.
