# ハイドロゲルの架橋反応と主鎖:細胞用・治療用ゲルの整理

作成日: 2026-10-07 / 対象: 細胞封入・細胞デリバリー・治療用(臨床/前臨床)ゲル

## 0. 先に読んでほしい注意(照合の深さ)

- **PubMed / Crossref / OpenAlex / EuropePMC / PMC はこの環境のネットワーク制限で全てブロックされていた**ため、書誌の DB 照合はできていない。
- 代わりに Web 検索で出版社・大学・PMC ページの題名・誌名・年を確認した。照合の深さを次の記号で示す。
  - **◎** 題名・誌名・年を検索結果で確認(巻・頁は検索結果にあったものだけ記載。DOI 照合ではない)
  - **○** 一部のみ確認(ニュース記事経由、URL の slug から題名を推定、プレプリント、著者名が未確定など)
  - **△** 未照合(検索で出なかった。記憶ベースの主張)
- 本文中のタグ: **【出典】** = リンク先で確認した記述 / **【考察】** = 私の推論で未確認の記述(仮説として扱うこと)。
- DOI は検索結果に出たものを除き載せていない(推測で書かない方針)。

---

## 1. 架橋反応の分類と参考文献

| # | 反応 | 代表的な主鎖 | 細胞用/治療用での使われ方 | ゲルの特徴(一文) | 参考文献(照合) |
|---|---|---|---|---|---|
| 1 | **連鎖重合型ラジカル光重合**(メタクリレート/アクリレート + 光開始剤) | GelMA、PEGDA、HAMA | 3D 細胞封入、バイオプリンティング、マイクロパターニング | 作りやすく物性を振りやすいが、ラジカルと光開始剤を細胞に当てる点と網目の不均一さが注意点(後者は【考察】)。 | Nichol 2010, *Biomaterials* 31(21):5536-44 ◎ [PMC2878615](https://pmc.ncbi.nlm.nih.gov/articles/PMC2878615)【出典】GelMA は細胞が接着・増殖・遊走し、メタクリル化度と濃度で水和・力学特性を調整できる。<br>Fairbanks 2009, *Biomaterials* 30(35):6702-7 ◎ [PMC2896013](https://pmc.ncbi.nlm.nih.gov/articles/PMC2896013)【出典】開始剤 LAP は I2959 より 365 nm でのゲル化が約 10 倍速く、細胞封入時の生存率も保たれた。 |
| 2 | **段階重合型 thiol-ene 光反応**(thiol + norbornene) | PEG-NB、Gelatin-NB、HA-NB | hMSC 封入、3D 生化学パターニング、酵素応答性のタンパク質徐放 | 反応が段階重合で網目が均一になりやすく、GelMA より細胞が速く広がる報告がある。 | Fairbanks 2009, *Adv Mater*「A Versatile Synthetic Extracellular Matrix Mimic via Thiol-Norbornene Photopolymerization」◎ [CU Boulder](https://vivo.colorado.edu/display/pubid_11634)【出典】hMSC 封入で生存率 95% 超。<br>Gelatin-norbornene, *Biomater Sci* 2014 ◎(題名「Gelatin hydrogels formed by orthogonal thiol–norbornene photochemistry for cell encapsulation」、責任著者 C.-C. Lin。著者全員は未確認) [RSC](https://pubs.rsc.org/en/content/articlelanding/2014/bm/c4bm00070f)【出典】GelNB は GelMA より細胞の広がりが速く高度だった。<br>Anseth 研のタンパク質封入・酵素応答性徐放(題名のみ確認 ○): [pubid_25120](https://vivo.colorado.edu/display/pubid_25120)、[pubid_25146](https://experts.colorado.edu/display/pubid_25146) |
| 3 | **thiol-Michael 付加**(thiol + vinyl sulfone / maleimide / acrylate) | 多腕 PEG、HA | 細胞浸潤性ゲル、in situ ゲル化、骨再生(rhBMP-2 送達)、細胞・タンパク質送達 | 光も触媒も要らず生理条件で速く進み、分解性ペプチドの両端 Cys で細胞応答性にできる。 | Lutolf 2003, *PNAS* 100 ◎ [PMC154359](https://pmc.ncbi.nlm.nih.gov/articles/PMC154359)(DOI 10.1073/pnas.0737381100 は [citedrive](https://www.citedrive.com/en/discovery/synthetic-matrix-metalloproteinase-sensitive-hydrogels-for-the-conduction-of-tissue-regeneration-engineering-cell-invasion-characteristics) の表示)【出典】VS-PEG + Cys-RGD + 2Cys MMP 基質ペプチド。線維芽細胞が MMP 依存的に浸潤、ラット頭蓋骨欠損で 4 週に骨再生。<br>Phelps 2012, *Adv Mater* 24:64-70 ◎ [PDF](https://murthylab.berkeley.edu/wp-content/uploads/2012/04/Phelps-Adv-Mater-2012.pdf)【出典】maleimide 化 PEG は化学量論的に架橋でき、臨床で使える時間スケールで in situ ゲル化する。 |
| 4 | **SPAAC**(歪み促進アジド-アルキン付加) | PEG(+ 光 thiol-ene との併用) | 無銅で細胞存在下に架橋。後から光でパターニング | 銅触媒不要で細胞適合だが、環状アルキンの合成コストと疎水性が実用上の壁(【考察】)。 | DeForest, Polizzotti, Anseth 2009, *Nat Mater*「Sequential click reactions for synthesizing and patterning three-dimensional cell microenvironments」◎ [CU Boulder](https://vivo-cub.colorado.edu/display/pubid_25148)(反応が SPAAC + thiol-ene である点は私の記憶で未確認 △)。<br>DeForest & Anseth 2012, *Angew Chem*「Photoreversible patterning of biomolecules within click-based hydrogels」◎ [PMC3430005](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3430005/)【出典】thiol-ene と o-ニトロベンジルエーテルの光切断を直交させた可逆パターニング。 |
| 5 | **IEDDA**(tetrazine-norbornene) | PEG | 数分でゲル化、hMSC 封入、thiol-ene との逐次修飾 | 反応が速く不可逆で、thiol-norbornene との比較では貯蔵弾性率約 6 倍・加水分解耐性が高いとされる。 | Alge 2013, *Biomacromolecules* ◎ [PMC3623454](https://pmc.ncbi.nlm.nih.gov/articles/PMC3623454)【出典】「Synthetically Tractable Click Hydrogels for Three-Dimensional Cell Culture Formed Using Tetrazine-Norbornene Chemistry」。<br>約 6 倍の記述は総説経由 ○: [PMC12469877](https://pmc.ncbi.nlm.nih.gov/articles/PMC12469877)(一次文献は未特定) |
| 6 | **Diels-Alder**(furan + maleimide) | HA、PEG | 軟組織工学、細胞適合性ゲル | 触媒も開始剤も不要で、furan:maleimide 比で力学特性と分解を調整できる。 | Nimmo, Owen, Shoichet 2011, *Biomacromolecules* ◎ [figshare](https://figshare.com/articles/Diels_Alder_Click_Cross_Linked_Hyaluronic_Acid_Hydrogels_for_Tissue_Engineering/2683912/1)【出典】furan-HA + dimaleimide-PEG、細胞適合。 |
| 7 | **動的共有結合: hydrazone / oxime / Schiff base** | PEG、HA、アルギン酸、キトサン | 応力緩和する 3D 培養、注射型ゲル | 結合の交換で自己修復・応力緩和を示し、弾性率と緩和時間を独立に近い形で振れる。 | McKinnon 2014, *Adv Mater* 26(6):865-72 ◎ [PMC4582033](https://pmc.ncbi.nlm.nih.gov/articles/PMC4582033)【出典】PEG-hydrazone。弾性率・緩和時定数を 1 桁以上制御。<br>Grover 他 2012, *Biomacromolecules* 13(10):3013-7 ○ [PMC3474544](https://pmc.ncbi.nlm.nih.gov/articles/PMC3474544)【出典】8 腕 aminooxy-PEG + glutaraldehyde の oxime ゲルで MSC 封入(著者名は検索結果が「Grover, Lam ら」と曖昧)。<br>総説: [HA ゲルの生理条件架橋](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8466770/) ◎、[Dynamic covalent bonds, *Polym Chem* 2020](https://pubs.rsc.org/lg/content/articlehtml/2020/py/c9py01694e) ◎ |
| 8 | **boronate ester**(フェニルボロン酸 + ジオール/カテコール) | HA、PVA、多糖 | 自己修復・せん断減粘ゲル、3D 封入(benzoxaborole-catechol) | pH 感受性で自己修復するが、素の boronate ester は加水分解・交換しやすく長期安定性に課題。 | 総説のみ ○: [Polym Chem 2020](https://pubs.rsc.org/lg/content/articlehtml/2020/py/c9py01694e)【出典】。一次文献は未特定。 |
| 9 | **酵素架橋(transglutaminase / HRP-H₂O₂)** | PEG-ペプチド、HA-tyramine、ゼラチン | 注射型 in situ ゲル、成長因子の共有結合導入 | 生理条件で進み部位特異的に修飾できるが、酵素と H₂O₂ の管理が必要(後者は【考察】)。 | Ehrbar 2007, *Biomaterials* 28:3856-66 ◎ [PMC2093941](https://pmc.ncbi.nlm.nih.gov/articles/PMC2093941)【出典】FXIIIa で多腕 PEG に接着リガンドと成長因子を結合しつつ MMP 分解性網目を形成。<br>Kurisawa 他 2005, *Chem Commun* ◎ [RSC](https://pubs.rsc.org/en/content/articlelanding/2005/cc/b506989k)【出典】HA-tyramine + HRP で注射後 in situ ゲル化。 |
| 10 | **イオン架橋**(Ca²⁺ / Ba²⁺ ↔ アルギン酸) | アルギン酸 | 細胞封入・マイクロカプセル(膵島)、T 細胞担持インプラント | 最も単純で細胞に優しいが、不活性なので RGD 付与が必要で、イオンが抜けると崩れる。 | Lee & Mooney 2012, *Prog Polym Sci* 37:106-26 ◎ [PMC3223967](https://pmc.ncbi.nlm.nih.gov/articles/PMC3223967)【出典】RGD 付与で細胞接着が可能。<br>膵島カプセルの臨床状況(Ca²⁺ alginate/PLO/alginate と豚膵島 Diabecell の第 I/IIa 相、Ba²⁺ カプセルの first-in-man と被膜周囲線維化)は検索要約のみ △。候補: [PMC3660848](https://pmc.ncbi.nlm.nih.gov/articles/PMC3660848)、[PMC5027196](https://pmc.ncbi.nlm.nih.gov/articles/PMC5027196)(どれがどの主張の出典かは未特定) |
| 11 | **ホスト-ゲスト超分子**(adamantane ↔ β-cyclodextrin) | HA | 注射型・せん断減粘・自己修復、徐放 | 注射できて素早く再構築するが、力学強度と侵食速度のバランスが課題(【考察】)。 | Rodell, Kaminski, Burdick 2013「Rational design of network properties in guest–host assembled and shear-thinning hyaluronic acid hydrogels」○(題名は [Drexel の記録 URL](https://researchdiscovery.drexel.edu/esploro/outputs/journalArticle/Rational-Design-of-Network-Properties-in/991019176645104721) の slug から。誌名・著者は私の記憶 △)。Ad-HA / CD-HA の記述は学会抄録: [SFB 2013](https://abstracts.biomaterials.org/data/papers/2013/0243-000215.pdf#page=1) ○ |
| 12 | **ポリマー-ナノ粒子(PNP)相互作用** | 修飾セルロース(HPMC-C12)+ PEG-PLA ナノ粒子 | 注射型、細胞と薬物の共送達、CAR-T のデポ | せん断減粘と自己修復で注射でき、共有結合を使わないので細胞を化学反応に晒さない。 | Appel 2015, *Nat Commun* 6:6295 ◎ [IDEAS/RePEc](https://ideas.repec.org/a/nat/natcom/v6y2015i1d10.1038_ncomms7295.html)【出典】生体高分子がナノ粒子に選択吸着して一過性に架橋(HPMC-C12 の記述は記憶 △)。<br>Grosskopf 2022, *Sci Adv* ○ [Stanford ニュース](https://news.stanford.edu/2022/04/08/gel-delivery-enhances-cancer-treatment/)【出典(二次)】CAR-T + サイトカインの PNP ゲルをマウス腫瘍脇に注射し 12 日でがんフリー、数週間で分解。一次文献は未取得。 |
| 13 | **温度応答ゾル-ゲル転移** | PLGA-PEG-PLGA、Pluronic、PNIPAM、キトサン | 注射型の薬物徐放(ReGel)、LNP 担持キトサンゲル | 注射後に体温で固まるが、細胞封入は温度・浸透圧条件で制約される(【考察】)。 | Jeong 1997, *Nature* 388:860-2 ◎ [IDEAS/RePEc](https://ideas.repec.org/a/nat/nature/v388y1997i6645d10.1038_42218.html)【出典】PEO-PLLA 系の熱応答生分解性ゲル。ReGel は MacroMed 社の商品名(特許 [US7740877](https://patents.google.com/patent/US7740877) の記述)。 |
| 14 | **自己組織化ペプチド** | RADA16(PuraMatrix) | 3D 培養、止血、創傷治癒 | 水が 99.5% 超の β-sheet ナノファイバーで ECM 様だが、化学修飾なしでは生理活性の自由度が低い(後者は【考察】)。 | 検索要約のみ ○: [Frontiers 総説](https://www.frontiersin.org/articles/10.3389/fbioe.2021.679525/full)、[MIT DSpace](https://dspace.mit.edu/handle/1721.1/33396)。一次文献(Zhang ら)は未特定 △ |
| 15 | **化学架橋剤による多糖の共有結合化(BDDE)** | HA | 皮膚フィラー(臨床・市販) | 長期残存性は修飾度(MoD)で決まり、残留 BDDE の免疫反応が安全性上の論点。 | [Decomposition and Changes in In Vivo Post-HA Filler Injection: A Review](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11743293/) ◎【出典】BDDE 架橋フィラーは 1996 年に欧州、2003 年に米国で導入。 |
| 16 | **活性エステル(NHS)- アミン反応** | 多腕 PEG + trilysine | 硬膜シーラント(DuraSeal 系)、組織スペーサー | 2 液混合で即固化する単純な化学で、承認製品に使われる。 | [DuraSeal 市販後試験 NCT00704340](https://clinicaltrials.gov/study/NCT00704340) ◎(PEG ester 液 + trilysine amine 液の記述は [BioChempeg の解説](https://www.biochempeg.com/article/118.html) など)。SpaceOAR・CoSeal が PEG 製品に含まれる点は検索要約のみ ○(SpaceOAR が同一化学かは未確認) |
| 17 | **天然 ECM 抽出物・タンパク質ゲル**(Matrigel、collagen、fibrin) | ラミニン/コラーゲン IV 等 | オルガノイド・細胞培養、止血(fibrin) | 生理活性は高いが成分が不定でロット差が大きく、治療用には不向き。 | [Matrigel の組成とロット差(検索要約)](https://pmc.ncbi.nlm.nih.gov/articles/PMC7500703) ○【出典】ラミニン約 60%・コラーゲン IV 約 30%、ロット間で力学・生化学特性が変動。<br>collagen / fibrin 自体は**未調査** |

---

## 2. 主鎖ごとの整理(細胞・治療でよく使う組み合わせ)

| 主鎖 | よく使う架橋反応 | 主な用途 | 一文の特徴 |
|---|---|---|---|
| **PEG(多腕)** | thiol-Michael、thiol-ene、SPAAC、IEDDA、hydrazone/oxime、FXIIIa、NHS-amine | 3D 細胞培養の「ブランク」基質、シーラント | 生体不活性なので RGD や分解ペプチドを足して設計でき、反応の選択肢が最も広い。 |
| **HA** | BDDE、Diels-Alder、guest-host、HRP-tyramine、hydrazone | フィラー、注射型ゲル、軟骨 | CD44 を介した細胞認識があり、化学修飾の自由度が高い(CD44 の点は【考察】)。 |
| **ゼラチン(GelMA / GelNB)** | メタクリレート光重合、thiol-norbornene | 3D 培養、バイオプリンティング | 細胞接着配列を内蔵するが、由来ロットのばらつきがある(後者は【考察】)。 |
| **アルギン酸** | Ca²⁺ / Ba²⁺ イオン架橋 | 細胞カプセル、T 細胞インプラント | 最も単純で承認実績もあるが、細胞接着には RGD 付与が必要。 |
| **修飾セルロース + ナノ粒子(PNP)** | 非共有結合 | 注射型の細胞・サイトカイン共送達 | 共有結合を使わず注射可能で、細胞・生体分子に優しい。 |
| **PLGA-PEG-PLGA / Pluronic** | 熱応答ゾル-ゲル | 注射型徐放 | 温度だけでゲル化する一方、細胞封入には条件制約がある(後者は【考察】)。 |
| **自己組織化ペプチド** | 非共有結合(β-sheet) | 3D 培養、止血 | ECM 様ナノファイバーだが、物性の自由度は限られる(後者は【考察】)。 |

**【考察】全体の傾向**: 検索で見えた承認・市販製品(BDDE-HA、PEG-NHS/amine、アルギン酸のイオン架橋、fibrin 系)は反応が単純で、click 反応や動的共有結合は研究・前臨床が中心に見える。これは検索結果に基づく印象で、網羅的調査ではない。

---

## 3. 重要な変数

### 3-1. 設計で動かす変数(【考察】= 私の整理。個別に出典があるものは付記)

| 変数 | 決めるもの | 出典付きの補強 |
|---|---|---|
| 主鎖の種類・分子量 | 生体適合性、分解性、細胞認識、粘度 | — |
| ポリマー濃度・修飾度(メタクリル化度など) | 剛性、メッシュサイズ、膨潤 | GelMA の水和・力学特性は修飾度と濃度で調整可 ([Nichol 2010](https://pmc.ncbi.nlm.nih.gov/articles/PMC2878615)) |
| 架橋反応の種類 | 可逆/不可逆、細胞存在下の可否、ゲル化時間 | IEDDA は数分でゲル化 ([Alge 2013](https://pmc.ncbi.nlm.nih.gov/articles/PMC3623454)) |
| 官能基の化学量論比 | 未反応基、到達剛性、分解 | furan:maleimide 比で力学・分解を調整 ([Nimmo 2011](https://figshare.com/articles/Diels_Alder_Click_Cross_Linked_Hyaluronic_Acid_Hydrogels_for_Tissue_Engineering/2683912/1)) |
| 開始剤・光条件 | ラジカル由来の毒性、ゲル化速度 | LAP は I2959 より約 10 倍速い ([Fairbanks 2009](https://pmc.ncbi.nlm.nih.gov/articles/PMC2896013)) |
| 生理活性(RGD・分解ペプチド) | 接着、浸潤、リモデリング | MMP 基質活性・接着リガンド濃度・架橋密度が浸潤を決める ([Lutolf 2003](https://pmc.ncbi.nlm.nih.gov/articles/PMC154359)) |

### 3-2. 結果として決まる物性

| 物性 | 影響 | 出典付きの補強 |
|---|---|---|
| 剛性(G′、E) | 幹細胞・免疫細胞の挙動 | 3D 足場で硬いほど T 細胞活性化が高い(プレプリント ○ [bioRxiv](https://www.biorxiv.org/content/10.1101/580886.full.pdf))。PEGDA-Strep 上で弾性率 1→120 kPa に伴い CD69 が増加(検索要約 ○) |
| **粘弾性(応力緩和)** | 細胞の広がり・増殖・分化 | 緩和速度を弾性率・分解・リガンド密度と独立に制御でき、速い緩和で MSC の増殖と骨分化が促進 ([Chaudhuri 2016](https://mooneylab.seas.harvard.edu/publications/hydrogels-tunable-stress-relaxation-regulate-stem-cell-fate-and-activity))。T 細胞では粘性が高いと memory 様、弾性が高いと effector 様(検索要約 ○) |
| メッシュサイズ・膨潤率 | 栄養・薬物・ナノ粒子の拡散、細胞遊走 | 【考察】 |
| 分解速度・機構 | 放出、足場の置換、滞留 | MMP 分解性ペプチドで細胞応答性 ([Lutolf 2003](https://pmc.ncbi.nlm.nih.gov/articles/PMC154359)) |
| ゲル化時間 | 注射可否、細胞沈降 | 【考察】 |
| せん断減粘・自己修復 | 注射型の可否 | PNP・guest-host で実現 ([Appel 2015](https://ideas.repec.org/a/nat/natcom/v6y2015i1d10.1038_ncomms7295.html)) |
| 細胞適合性・ロット再現性 | 臨床応用 | Matrigel はロット差が大きい(検索要約 ○) |

---

## 4. 免疫細胞・遺伝子導入に近い文献(研究テーマ向け)

| 文献 | 内容 | 照合 |
|---|---|---|
| Stephan 2015, *Nat Biotechnol* 33:97-101 [nature.com](https://www.nature.com/articles/nbt.3104) | アルギン酸スキャフォールド(コラーゲン様分子とT細胞刺激微粒子で修飾)による腫瘍反応性 T 細胞の送達・増殖。切除後再発の抑制、卵巣がんモデルで退縮 | ◎ |
| Grosskopf 2022, *Sci Adv*(上記 #12) | PNP ゲルによる CAR-T + サイトカインの局所送達 | ○ |
| mRNA-LNP 担持ナノファイバー-ゲル複合体 [bioRxiv 2025](https://www.biorxiv.org/content/10.1101/2025.01.27.633179.full.pdf) | 局所免疫刺激ニッチ。プレプリント | ○ |
| LNP を担持した温度応答キトサンゲル(IRF5 mRNA / CCL5 siRNA で M1 化) | 検索要約のみ。一次文献は未特定 [関連ページ](https://scholars.houstonmethodist.org/en/publications/injectable-immunotherapeutic-hydrogel-containing-rna-loaded-lipid/) | ○ |

**【考察・率直な指摘】**
- ゲル「上」で免疫細胞に遺伝子導入する研究(誘引 → 接触 → LNP/ウイルスによる導入)に直接当たる文献は、今回の検索では見つかっていない。上の例はゲルを「細胞やLNPの担体・ニッチ」として使うものが中心。ここは空白領域か、検索語が合っていないかのどちらか。次回、検索語を変えて確認が必要。
- thiol-Michael 系(maleimide / vinyl sulfone)の未反応基が、細胞表面のチオールや LNP 表面・タンパク質と副反応する可能性は、私の推測で未確認。免疫細胞を触れさせる設計では、化学量論をずらして未反応基を残さない、または反応クエンチを入れる、が安全側。
- 光重合系はラジカルとの同時暴露が T 細胞の活性化状態や導入効率に影響する可能性があるが、これも未確認。PNP や動的共有結合のような「反応で細胞を晒さない」系のほうが免疫細胞では素直、というのが私の仮説。

---

## 5. 未調査・未照合の項目

- DB 照合(DOI・PMID・巻頁)は未実施。環境の Network access で `api.crossref.org` と `eutils.ncbi.nlm.nih.gov` を許可すれば、一括照合できる。
- collagen / fibrin の一次文献、disulfide 架橋、genipin / EDC-NHS 系、tyrosine の光二量化(Ru/SPS)は今回検索していない。
- 承認製品の網羅(FDA 承認データベース照合)は未実施。SpaceOAR・CoSeal の化学は未確認。
- 治療用ゲルの臨床試験(CAR-T 局所デリバリーなど)の現況は未調査。
