# T.DAY — Manual da Obra

Resumo de tudo que foi construído nesta sessão (07/07/2026), na branch
`claude/previous-work-summary-1uxm8s`.

---

## 1. Playlist no Spotify

- **Nome:** T.DAY — Trilha por Momentos
- **Visibilidade:** privada
- **Regras aplicadas:** sem Pabllo Vittar, sem funk
- **Observação:** o Spotify gera a seleção a partir de uma descrição, então segue de perto
  a curadoria, mas pode não ser faixa-por-faixa idêntica ao CSV.
- **Para a lista exata (64 faixas):** importe o arquivo `.csv` via Soundiiz ou TuneMyMusic.
- **Para tornar pública:** app → abrir a playlist → menu `···` → "Tornar pública".

> Foi criada uma versão anterior (antes das regras) que pode conter funk/Pabllo Vittar.
> Ela deve ser excluída manualmente no app — o conector do Spotify aqui só cria e busca,
> não edita nem apaga playlists.

---

## 2. Curadoria — 8 momentos (64 faixas)

Jornada de um dia, do acordar à noite. A lista global (por continente) foi reorganizada
por **energia**. `★` = já aparece nos Dias 01–10 do app · `↺` = trocada para remover funk.

**01 · Despertar (manhã leve):** Una Mattina — Einaudi · Nuvole Bianche — Einaudi · Your Song — Elton John · Yellow — Coldplay · First Love — Utada Hikaru · Photograph — Ed Sheeran · Cinema Paradiso — Bocelli · Fix You — Coldplay

**02 · Foco (instrumental):** Experience — Einaudi · I Giorni — Einaudi · Divenire — Einaudi · Gabriel's Oboe — Yo-Yo Ma · Cello Suite No.1 Prélude — Yo-Yo Ma · The Swan — Yo-Yo Ma · Nocturne — Jay Chou · Something Just Like This — Coldplay

**03 · Pré-treino (aquecimento):** Mi Gente — J Balvin · Calm Down — Rema · Essence — Wizkid · One Dance — Drake · Envolver — Anitta · Hips Don't Lie — Shakira · Padam Padam — Kylie Minogue · Provenza — Karol G

**04 · Beast Mode (força máxima):** Till I Collapse — Eminem ★ · Lose Yourself — Eminem ★ · Thunderstruck — AC/DC ★ · Highway to Hell — AC/DC · Back in Black — AC/DC ★ · God's Plan — Drake ★ · The Real Slim Shady — Eminem · Bad — Michael Jackson

**05 · Cardio (BPM alto):** How You Like That — BLACKPINK · Dynamite — BTS · Kill This Love — BLACKPINK · Can't Get You Out of My Head — Kylie Minogue · Shape of You — Ed Sheeran · Hung Up — Madonna · Vogue — Madonna · Last Last — Burna Boy

**06 · Recovery (soul):** Someone Like You — Adele · Easy on Me — Adele · Thinking Out Loud — Ed Sheeran · Como É Grande o Meu Amor por Você — Roberto Carlos · Detalhes — Roberto Carlos · The Prayer — Bocelli · Hikari — Utada Hikaru · Tu Hi Re — A.R. Rahman

**07 · Festa (pista global):** Waka Waka — Shakira · Tusa — Karol G · Downtown — Anitta ↺ (era "Vai Malandra", funk) · Jai Ho — A.R. Rahman · Ye — Burna Boy · Come Closer — Wizkid · Pink Venom — BLACKPINK · Cheap Thrills — Sia

**08 · Noite (clássica):** Nessun Dorma — Pavarotti · Con Te Partirò — Bocelli · 'O sole mio — Pavarotti · The Second Waltz — André Rieu · The Blue Danube — André Rieu · Libertango — Yo-Yo Ma · Bohemian Rhapsody — Queen · Feels Like We Only Go Backwards — Tame Impala

---

## 3. Arquivos entregues

| Arquivo | O que é |
|---|---|
| `playlist_por_momentos.txt` | Curadoria legível (8 momentos + faixas) |
| `playlist_por_momentos_importar.csv` | Lista importável (`Momento, Artista, Track`) — use para importar as 64 faixas exatas |
| `RELATORIO_verificacao.md` | Laudo de verificação da lista global |
| `MANUAL.md` | Este documento |

---

## 4. Verificação da lista global (175 faixas)

**Erros a corrigir:**

| Na lista | Correto | Problema |
|---|---|---|
| Chaiyya Chiavya | Chaiyya Chaiyya | Digitação (A.R. Rahman) |
| Tamly Maak | Tamally Maak | Transliteração (Amr Diab) |
| J Balvin - Reggaeton | Reggaetón | Título malformado |
| Di Capua: Torna a Surriento | De Curtis: Torna a Surriento | Compositor errado |

**A conferir (Amr Diab):** "Ana Lawson", "Bayen Habeit", "Wa Ma'ah".

**Cruzamento com o app:** ~9 faixas / 5 artistas já estão nos Dias 01–10 (Eminem, AC/DC,
Queen, Drake, Sia). As outras 166 são material novo.

---

## 5. Regras permanentes

- ⛔ **Nunca Pabllo Vittar** — em nenhuma playlist, em hipótese alguma.
- ⛔ **Sem funk** — nada de funk carioca, baile funk ou brega funk.

---

## 6. Próximos passos possíveis

- [ ] Excluir a 1ª playlist antiga (feita antes das regras)
- [ ] Importar as 64 faixas exatas via CSV (Soundiiz/TuneMyMusic)
- [ ] Integrar os 8 momentos no app T.DAY (`index.html`)
- [ ] Corrigir os 4 erros direto nos arquivos `playlist_global_*`
