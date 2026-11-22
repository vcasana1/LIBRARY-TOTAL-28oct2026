# LIBRARY TOTAL — índice vigente

**Repositorio:** `vcasana1/LIBRARY-TOTAL-28oct2026` · **Rama:** `main` · **Comprobación:** 2026-11-22 · **PDF principales:** 382 (`001`–`382`, en orden alfabético ASCII, sin huecos numéricos ni duplicados binarios), más 1 PDF parcial identificado en `DOCUMENTOS_PARCIALES/`. Las versiones distintas de una misma obra se conservan expresamente.

**Ruta del Mac comprobada:** `/Users/vcasana/Documents/LIBRARY TOTAL/`. Los 337 PDF previos coincidían con `main` en el commit `e6473ce42726d1e6103059a977ea0c3d2022ef79`. Incorporación del 2026-11-01: 16 PDF nuevos numerados 338–353 y 1 parcial separado, copiados desde Descargas; los originales de Descargas y los PDF 001–337 se conservan sin cambios. El registro `INCORPORACIONES_2026-11-01.json` se retiró el 2026-11-22 (queda en el historial de git, commit `4a661ae`). **Incorporación y renumeración del 2026-11-22:** 26 PDF nuevos (bibliografía de Alpöge, §21) y renumeración completa de la carpeta en orden alfabético; los números 001–353 y 338–353 citados en notas anteriores y en el registro del 2026-11-01 corresponden a la numeración antigua; equivalencias en `RENUMERACION_2026-11-22.md`. **Segunda incorporación del 2026-11-22:** 3 PDF (Gallagher 1970; Motohashi 1977 y 1978), copiados desde Descargas, y nueva renumeración completa a 382 PDF; `RENUMERACION_2026-11-22.md` se ha rehecho y da cada número en la numeración del 2026-11-01, en la primera del 2026-11-22 (379 PDF) y el vigente; la tabla anterior se ha retirado.

## Uso

1. Localizar por autor, título o palabra clave en las secciones temáticas o en el catálogo numerado final.
2. Cada nombre en el catálogo final coincide exactamente con un PDF existente en este repositorio. El identificador más fiable es **nombre completo + SHA de Git**; el número es solo un identificador operativo.
3. Verificar en la **imagen de la página original** cada ecuación, fórmula, exponente, cuantificador y dominio antes de atribuirlo al paper. La extracción de texto y el OCR no son prueba suficiente.
4. Usar el catálogo final para identificar **los 382 PDF principales**; las secciones temáticas son ayudas de búsqueda y pueden repetir referencias.

## Incidencias vigentes

- PDF sin capa de texto: `057_Brent_1979_Zeros_Riemann_Zeta_Critical_Strip.pdf`, `146_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf`, `369_Volchkov_1995_Equality_Equivalent_Riemann_Hypothesis_Russian.pdf`.
- OCR delicado en fórmulas: `017_Backlund_1916_Nullstellen_Riemannschen_Zetafunktion.pdf` y `382_vonMangoldt_1905_Verteilung_Nullstellen_Riemannschen_Funktion_Xi.pdf`.
- PDF incompleto: `112_Edwards_1974_Riemanns_Zeta_Function.pdf` (escaneo solo de pp. impresas 1–122/311); `146_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf` (solo pp. 92–96).
- PDF a doble página: `209_Jutila_1977_Zero_Density_Estimates_L_Functions.pdf`, `213_Kaczorowski_1991_k_Functions_Multiplicative_Number_Theory_V.pdf`, `322_Ramachandra_1976_Problems_Analytic_Number_Theory.pdf`. Comprobar página impresa y página del PDF.
- `199_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf` y `201_Ivic_2003_Riemann_Zeta_Dover_Reprint.pdf` son ediciones del mismo libro; erratas en `ERRATA_Ivic.md`.
- El preprint `006_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` es anónimo y no es un artículo de Riemann. La fuente de Riemann se encuentra en `326_Riemann-Wilkins_1859_Prime_Counting_English_Translation.pdf` (transcripción en alemán).
- `077_Claude_2026_More_Than_Two_Thirds_Zeros_Zeta_Critical_Line.pdf` no es la versión arXiv firmada por L. Alpöge y R. Furman (arXiv:2608.13637v2).
- Verificar antes de citar: `096_Dannon_2008_Riemann_Zeta_Function.pdf`, `368_Vega_2023_Simple_Proof_Riemann_Hypothesis.pdf`, `375_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf` y `006_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` (sin revisión por pares acreditada).
- PDF sin capa de texto (solo consulta visual): también `246_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf` y `324_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf`.
- Bibliografía de Alpöge (§21): la referencia [3] Behrend (PNAS 32, 1946, 331–332) **no está** en la biblioteca: la descarga automática devolvió una página de protección en lugar del PDF. Las referencias [9] Davenport–Montgomery (3.ª ed.) y [15] Howe 1979 no se incorporaron porque ya las tienes; en la biblioteca figura la 2.ª ed. de Davenport (1980) y, como sustituto abierto de Howe, `139_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf`. [1] (código Lean, commit 7cbf7a0c…) y [28] (página de verificación de Sutherland) no son PDF y permanecen en Descargas, fuera de la carpeta plana.

## Fuentes citadas todavía pendientes

Esta lista recoge ausencias detectadas por coincidencia de título/autor en el inventario y **no** equivale a una auditoría bibliográfica de los originales ni a afirmar que no puedan conseguirse en línea.

- **Rudnick & Sarnak**, *Zeros of principal L-functions and random matrix theory*, Duke Math. J. **81** (1996), 269–322. Base del salto de estadística 2-level a n-level.
- **Forrester & Odlyzko**, *Gaussian unitary ensemble eigenvalues and Riemann zeta function zeros: a nonlinear equation for a new statistic*, Phys. Rev. E **54** (1996), R4493. Tratamiento Fredholm/Painlevé de nearest-neighbour; evita usar el Wigner surmise como exacto.
- **Grossmann**, *Über die Nullstellen der Riemannschen Zeta-Funktion und der Dirichletschen L-Funktionen*, tesis, Göttingen, 1913. Sus constantes (0.29062, 1.7862, 6.13695; T > 50) están citadas en Backlund 1916, p. 355. (La tesis de Xylouris 2011 de la carpeta es otra.)
- **Selberg**, *Contributions to the theory of the Riemann zeta-function*, Arch. Math. Naturvid. **48** (1946), no. 5, 89–155. Los momentos de S(t) están en Titchmarsh §9.25, (9.25.1).
- **F. Riesz**, *Sur un théorème de maximum de MM. Hardy et Littlewood*, J. London Math. Soc. **7** (1932) 10–13. **Mertens**, J. Reine Angew. Math. **78** (1874) 46–62 (Mertens está en Tenenbaum).
- **Tsang**, *The distribution of the values of the Riemann zeta function*, tesis, Princeton, 1984. Citado de segunda mano a través de `115_Fazzari-Gerspach-Minelli_2025_Selberg_CLT_Weighted_Linear_Statistics_Zeta_Zeros.pdf` (§3, antes de (3.6); su Thm. 5.1).
- **Kargin**, *Statistical properties of zeta functions' zeros*, Probability Surveys **11** (2014), 121–160, arXiv:1302.1452. El survey.

---

## 1. Núcleo RVM: sumas sobre ordenadas, fases y partes fraccionarias

- `011_Aryan_2019_Extension_Landau_Gonek_Formula.pdf` — extensión de la fórmula de Landau–Gonek; recupera sin RH consecuencias de pair correlation. arXiv:1902.05473
- `055_Brent-Platt-Trudgian_2020_Sums_Over_Zeros_Riemann_Zeta.pdf` — estimación explícita de sumas sobre ceros.
- `080_Coffey_2009_Certain_Sums_Over_Nontrivial_Zeta_Zeros.pdf` — coeficientes b_n como sumas sobre ceros y sobre las λ_j de Li/Keiper. arXiv:0912.2390
- `109_Durkan-Hughes-PearceCrump_2026_Generalisations_Landau_Gonek_Theorem.pdf` — sumas Σ_ρ χ(ρ)X^ρ; sensibilidad a la naturaleza aritmética de X. arXiv:2601.18025
- `200_Ivic_2001_Sums_Over_Ordinates_Zeta_Zeros.pdf` — G(s) = Σ_{γ>0} γ^{-s}; evaluación de sumas sobre γ e integrales de S(T). **Referencia base.**
- `289_Murahara-Onozuka_2025_Equidistribution_A_Points_Zeta_Derivatives.pdf` — sumas exponenciales sobre a-puntos de derivadas de ζ, siguiendo a Fujii. arXiv:2510.07710
- `006_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` **(preprint anónimo; revisar procedencia)** — sumas parciales S(N)=Σ e^{iγ_n}, banda estrecha de |S(N)|, picos y espaciados multimodales. Directamente sobre tu problema.
- `375_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf` — dinámica de bobinado de fase de ζ, heatmaps y estadística. Sin arbitraje.
- `119_Ford-Meng-Zaharescu_2017_Simultaneous_Fractional_Parts.pdf` — distribución simultánea de {α_1γ,…,α_nγ}. arXiv:1511.06814
- `120_Ford-Soundararajan-Zaharescu_2009_Imaginary_Parts_II.pdf` — partes fraccionarias de αγ, continuación. arXiv:0805.2745
- `121_Ford-Zaharescu_2005_Imaginary_Parts_Zeta_Zeros.pdf` — partes fraccionarias de αγ, primer trabajo de la serie.
- `335_Saffari-Vaughan_1977_Fractional_Parts_X_Over_N_II.pdf` — partes fraccionarias de x/n y sucesiones relacionadas.
- `012_Aryan_2022_Extension_Landau_Gonek_Formula_Published.pdf` — versión publicada de la extensión de la fórmula de Landau–Gonek. J. Number Theory 233 (2022) 389–404
- `146_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf` — Gonek, fórmula de Landau y valores medios de ζ; **incompleto (solo pp. 92–96) y sin capa de texto**
- `157_Guillera_2013_Sums_Nontrivial_Zeros_Riemann_Zeta.pdf` — identidades con sumas sobre los ceros no triviales; desarrollos asintóticos en la línea de Cramér. arXiv:1307.5723
- `212_KaczorowskiLanguascoPerelli2000_2000_A_note_on_Landau_s_formula.pdf` — forma ponderada de la versión uniforme de Gonek de la fórmula de Landau. Funct. Approx. 28 (2000) 173–186

## 2. Pair correlation de Montgomery

- `077_Claude_2026_More_Than_Two_Thirds_Zeros_Zeta_Critical_Line.pdf` — «Claude» (Anthropic), *More than two thirds of the zeros of the Riemann zeta function lie on the critical line*, versión del 10-8-2026, 35 pág. Proporciones de ceros simples y en la recta crítica, incondicionalmente, con la segunda varianza de Montgomery y la ley de inercia de Sylvester; formalización Lean en `github.com/anthropics/zeta-23-lean` (de ahí sale la desigualdad de Montgomery–Vaughan portada a PaperMath). Publicado en arXiv como arXiv:2608.13637v2 (21-8-2026), firmado por L. Alpöge y R. Furman.
- `280_Montgomery_1973_Pair_Correlation_Zeros_Zeta.pdf` — **el original**. F(α), 2/3 de ceros simples bajo RH.
- `023_Baluyot-Goldston-etal_2025_Pair_Correlation_Zeros_I_Proportions_Simple_Critical.pdf` — proporciones de ceros simples y en la crítica. arXiv:2501.14545
- `067_Carneiro-Chandee-Littmann-Milinovich_2014_Hilbert_Spaces_Pair_Correlation.pdf` — N(T,β) vía espacios de Hilbert de funciones enteras. arXiv:1406.5462
- `068_Carneiro-Milinovich-Ramos_2023_Fourier_Optimization_Montgomery_Pair_Correlation.pdf` — cotas del promedio de F(α,T) por optimización de Fourier. arXiv:2310.01913
- `072_Chan_2002_More_Precise_Pair_Correlation_Zeros_Primes_Short_Intervals.pdf` — segundos términos principales en la equivalencia Goldston–Montgomery.
- `085_Conrey-Keating_2016_Pair_Correlation_Twin_Primes_Revisited.pdf` — conexión ratios-conjecture / correlaciones aritméticas. arXiv:1604.06124
- `041_Bogomolny-Keating_1995_Random_Matrix_Theory_Riemann_Zeros_I_Three_Four_Point_Correlations.pdf` — correlaciones de 3 y 4 puntos de los ceros = GUE desde Hardy–Littlewood. doi:10.1088/0951-7715/8/6/013
- `042_Bogomolny-Keating_1996_Gutzwiller_Trace_Formula_Spectral_Statistics_Beyond_Diagonal.pdf` — correlación de dos puntos más allá de la aproximación diagonal; para ζ equivale a Hardy–Littlewood para pares de primos. doi:10.1103/PhysRevLett.77.1472
- `043_Bogomolny-Keating_1996_Random_Matrix_Theory_Riemann_Zeros_II_n_Point_Correlations.pdf` — correlaciones de n puntos = GUE para todo n, desde Hardy–Littlewood. doi:10.1088/0951-7715/9/4/006
- `097_Das-Ismoilov-Ramos_2025_Fourier_Optimization_Pair_Correlation_Problems.pdf` — marco genérico de cotas de pair correlation. arXiv:2502.05106
- `143_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_II_Alternative_Hypothesis.pdf` — PCC bajo hipótesis alternativa. arXiv:2507.06823
- `144_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_I_Simple_Critical.pdf` — PCC sin RH y ceros simples. arXiv:2503.15449
- `226_Kolountzakis-Revesz_2003_Turan_Extremal_Problem.pdf` — problema extremal de Turán; herramienta de optimización de Fourier.
- `135_GPY2009_2009_Annals_of_Mathematics.pdf` — Goldston–Pintz–Yıldırım, *Primes in tuples I*. Ann. of Math. 170 (2009)
- `279_MontgomerySoundararajan2004_2004_Comm_Math_Phys.pdf` — primos en intervalos cortos: varianza menor que la del modelo de Cramér. arXiv:math/0409258

## 3. Gaps entre ceros y arg ζ

- `382_vonMangoldt_1905_Verteilung_Nullstellen_Riemannschen_Funktion_Xi.pdf` — H. von Mangoldt, *Zur Verteilung der Nullstellen der Riemannschen Funktion ξ(t)*, Math. Ann. 60 (1905) 1–19, doi:10.1007/BF01447494. p. 1: |N(T) − (T/2π)log(T/2πe)| < 0.43200 log T + 1.91662 log log T + 13.07873 para T > 28.558 (primera fila de la tabla de récords).
- `017_Backlund_1916_Nullstellen_Riemannschen_Zetafunktion.pdf` — R. J. Backlund, *Über die Nullstellen der Riemannschen Zetafunktion*, Acta Math. 41 (1916) 345–375, doi:10.1007/BF02422950. Q(T) = N(T) − (T/2π log T/2π − T/2π + 7/8) (p. 354); (39): |Q(T)| < 0.137 log T + 0.443 log log T + 4.350, válida para todo T ≥ 2 (pp. 355, 375). En p. 355 cita a von Mangoldt (0.43200, 1.91662, 12.20375; T > 28.558) y Grossmann (0.29062, 1.7862, 6.13695; T > 50), y su propia cota de 1914 (T > 200).
- `364_Trudgian_2012_Improved_Upper_Bound_Argument_Zeta.pdf` — T. S. Trudgian, *An improved upper bound for the argument of the Riemann zeta-function on the critical line*, Math. Comp. 81 (2012) 1053–1061, doi:10.1090/S0025-5718-2011-02537-8. Thm. 1: |S(t)| ≤ 1.998 + 0.17 log t para t > t₀ > e.
- `131_Fujii_1974_Zeros_Dirichlet_L_Functions_I.pdf` — momentos de S(t+h)−S(t) (y de L(s,χ)) en intervalos cortos, con prueba; incondicional. Trans. AMS 196 (1974), DOI 10.1090/S0002-9947-1974-0349603-2
- `134_Fujii_1981_Zeros_Dirichlet_L_Functions_II_Corrections.pdf` — pruebas completas de consecuencias del teorema principal de Fujii 1974 (momentos de S(t+h)−S(t)), con correcciones a la parte I y a los artículos siguientes. Trans. AMS 267 (1981).
- `133_Fujii_1975_Distribution_Zeros_Zeta_Short_Intervals.pdf` — momentos de S(t+h)−S(t) en intervalos cortos (anuncio, sin pruebas). Bull. AMS 81 (1975), DOI 10.1090/S0002-9904-1975-13674-3
- `188_Hughes-Rudnick_2002_Linear_Statistics_Zeros_Zeta.pdf` — estadísticos lineales de ceros escalados; momentos gaussianos. arXiv:math/0208220
- `132_Fujii_1975_Difference_r_Consecutive_Ordinates_Zeros_Zeta.pdf` — momentos incondicionales de diferencias de r ordenadas consecutivas, muestreados en los ceros; conteo de r-gaps pequeños. Proc. Japan Acad. 51 (1975), DOI 10.3792/pja/1195518466
- `086_Conrey-TurnageButterbaugh_2018_r_Gaps_Between_Zeros_Zeta.pdf` — r-gaps, constantes explícitas bajo RH. arXiv:1708.00030
- `145_Gonek-Sahay_2024_Consecutive_Moderate_Gaps_Between_Zeros_Zeta.pdf` — gaps consecutivos moderados. arXiv:2412.15481
- `196_Inoue-Kobayashi-Toma_2026_Explicit_Extreme_Values_Argument_Zeta.pdf` — valores extremos explícitos de arg ζ; mejora Conrey–Turnage-Butterbaugh. arXiv:2510.14309
- `198_Ivic-Korolev_2018_Distribution_Values_Argument_Zeta.pdf` — distribución del signo de S(t): medida de {t∈[T,T+H]: S(t)>0} para T^{27/82+ε} ≤ H ≤ T.
- `234_Korolev_2016_Extreme_Values_S_Short_Intervals_Indian_J.pdf` — máximo y mínimo de S(t) en segmentos muy cortos de la recta crítica, bajo RH. Indian J. Pure Appl. Math. 47 (2016) 603–615, DOI 10.1007/s13226-016-0205-4
- `197_Inoue_2024_Note_On_r_Gaps_Between_Zeros_Zeta.pdf` — prueba del resultado anunciado por Selberg sobre r-gaps. arXiv:2303.06613
- `378_Zhao_2026_Density_Results_r_Gaps_Between_Zeros_Zeta.pdf` — resultados de densidad para r-gaps. arXiv:2603.17334
- `232_Korolev_2012_Gram_Law_Argument_Riemann_Zeta_Publ_Inst_Math.pdf` — ley de Gram y S(t) en los puntos de Gram; fórmulas de Selberg para momentos de Δ_n en intervalos cortos (Teorema 4.2). Publ. Inst. Math. 92(106) (2012), DOI 10.2298/PIM1206053K
- `233_Korolev_2012_Gram_Law_Riemann_Zeta.pdf` — ley de Gram, fórmulas de Selberg. arXiv:1011.3997
- `230_Korolev_2010_Gram_Law_Selberg_Conjecture_Zeros_Izv_Math.pdf` — ley de Gram y conjetura de Selberg sobre la distribución de los ceros. Izv. Math. 74 (2010) 743, DOI 10.1070/IM2010v074n04ABEH002506
- `231_Korolev_2011_Gram_Law_Argument_Riemann_Zeta_arXiv.pdf` — S(t) en los puntos de Gram; panorámica de los sentidos de "ley de Gram"; fórmulas de Selberg. arXiv:1106.0516
- `235_Korolev_2016_Gram_Law_Theory_Zeta_Part1_Proc_Steklov.pdf` — monografía (146 pág.) sobre la ley de Gram en la teoría de ζ, parte 1. Proc. Steklov Inst. Math. 292, suppl. 2 (2016) S1–S146, DOI 10.1134/S0081543816030019
- `203_Jerby_2023_New_Discriminant_Hardy_Z_Function_Corrected_Gram_Law.pdf` — discriminante Δ_n(a) de Z(t), ley de Gram corregida. arXiv:2310.14415
- `363_Trudgian_2008_Gram_Law_Fails_Positive_Proportion_Of_The_Time.pdf` — proporción positiva de fallos de la ley de Gram y de éxitos débiles. arXiv:0811.0883
- `125_Franca-LeClair_2014_Statistical_Properties_Riemann_Zeros_Explicit_Equation_nth_Zero.pdf` — ecuación para el n-ésimo cero con Lambert W (ỹ_n, sin puntos de Gram ni ley de Gram) y término arg ζ; reconstruye π(x) con ceros sintéticos. arXiv:1307.8395
- `126_Franca-LeClair_2014_Theory_Zeros_Riemann_Zeta_And_Other_L_Functions.pdf` — notas de curso: ceros de la línea crítica ↔ ceros del coseno, ecuación del n-ésimo cero, L-funciones. arXiv:1407.4358
- `128_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions_CNTP_Published.pdf` — versión publicada de la ecuación trascendente del n-ésimo cero (CNTP 9 (2015) 1–50).
- `250_LeClair_2016_Riemann_Hypothesis_Random_Walks_Zeta_Case.pdf` — producto de Euler truncado en N(t)<[t²], B_N(t)=O(√N) vía Kac, argumento heurístico de S(t)=O(1), modelo probabilístico de ceros y cero 10^100. arXiv:1601.00914
- `027_Bellotti-Wong_2025_Improved_Argument_Zero_Counting_Zeta.pdf` — cota explícita |N(T) − (T/2π)log(T/2πe)| ≤ 0.10076 log T + 0.24460 log log T + 8.08344. arXiv:2412.15470
- `089_Conrey_1989_More_Than_Two_Fifths_Zeros_Critical_Line.pdf` — Conrey, más de dos quintos de los ceros en la recta crítica. J. reine angew. Math. 399 (1989)
- `127_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions.pdf` — versión arXiv de las ecuaciones trascendentes para ceros individuales (publicada: `128_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions_CNTP_Published.pdf`). arXiv:1502.06003
- `168_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Riemann_Zeta.pdf` — cota explícita |N(T) − (T/2π)log(T/2πe)| ≤ 0.1038 log T + 0.2573 log log T + 9.3675. arXiv:2107.06506
- `365_Trudgian_2014_Improved_Upper_Bound_Argument_Zeta_II.pdf` — cota superior mejorada para S(T) en la recta crítica, II. arXiv:1208.5846v2 (el PDF lleva la plantilla de Math. Comp.); publicado en J. Number Theory 134 (2014) 280–292, doi:10.1016/j.jnt.2013.07.017. Lema 3: Phragmén–Lindelöf con logaritmos; con potencias distintas del logaritmo su prueba tiene un hueco, corregido por Fiori (§7).
- `032_Bennett-Martin-OBryant-Rechnitzer_2021_Counting_Zeros_Dirichlet_L_Functions.pdf` — M. A. Bennett, G. Martin, K. O'Bryant, A. Rechnitzer, *Counting zeros of Dirichlet L-functions*, arXiv:2005.02989v1 (2020); publicado en Math. Comp. 90 (2021) 1455–1482, doi:10.1090/mcom/3599. Cotas explícitas de N(T,χ) para conductor q > 1 y T ≥ 5/7; nueva cota de |L(s,χ)| para σ < −1/2. Fuente de la función 𝓔(T,d) del método de Backlund que usan Bellotti–Wong y `rvm_clock_envelope` (Teorema 3.5).

## 4. RMT, GUE/CUE y estadística de espaciados

- `036_Berry_1988_Semiclassical_Formula_Number_Variance_Riemann_Zeros.pdf` — varianza del número de ceros desde los primos: régimen universal GUE y régimen no universal por primos, separados por la escala τ*. doi:10.1088/0951-7715/1/3/001
- `298_Odlyzko_1987_Distribution_Spacings_Between_Zeros_Zeta.pdf` — **datos base**: 10^5 ceros y ceros 10^12+1…10^12+10^5, precisión 10^-8.
- `124_Forrester-Mays_2015_Finite_Size_Corrections_RMT_Odlyzko_Data.pdf` — correcciones de tamaño finito contra el dataset de Odlyzko. arXiv:1506.06531
- `050_Bornemann-Forrester-Mays_2017_Finite_Size_Effects_Spacing_Distributions.pdf` — efectos de tamaño finito en distribuciones de espaciado. arXiv:1608.04638
- `293_Nishigaki_2024_Consecutive_Level_Spacings_GUE_Ratio.pdf` — espaciados consecutivos GUE y su ratio, derivación ab initio. doi:10.1093/ptep/ptae120
- `294_Nishigaki_2025_Consecutive_Level_Spacings_CUE_Finite_Size_Zeta.pdf` — lo mismo para CUE, con correcciones finitas y ceros de ζ.
- `343_Shir-MartinezAzcona-Chenu_2025_Surmise_Level_Spacing_Beyond_Nearest.pdf` — surmise más allá del vecino inmediato. arXiv:2504.20134
- `044_Bohigas-Leboeuf-Sanchez_2001_Spectral_Spacing_Correlations.pdf` — autocovarianzas de espaciados como función de correlación discretizada.
- `123_Forrester-Lebowitz_2013_Local_CLT_Determinantal_Point_Processes.pdf` — TCL local para procesos determinantales. arXiv:1311.7126
- `204_Johansson_2001_Discrete_Orthogonal_Polynomial_Ensembles_Plancherel.pdf` — ensembles discretos de polinomios ortogonales.
- `219_Kargin_2013_Fluctuations_Riemann_Zeta_Zeros.pdf` — *On fluctuations of Riemann's zeta zeros*, arXiv:1203.5309, 25 pág. Fluctuaciones gaussianas de γ_k en torno a su posición predicha; ley conjunta de γ_k y γ_{k+x} con correlación (1-β)₊. **No confundir** con Kargin, *Statistical properties of zeta functions' zeros*, Probability Surveys 11 (2014), arXiv:1302.1452 — ese es el survey (soporte de Fourier en Montgomery, escalas, qué es local), y **no está en la biblioteca**.
- `115_Fazzari-Gerspach-Minelli_2025_Selberg_CLT_Weighted_Linear_Statistics_Zeta_Zeros.pdf` — TCL de Selberg ponderado por estadística local de ceros. arXiv:2507.04150
- `070_Cartier-Julia-Moussa-Vanhove_2006_Random_Matrices_Zeta_Dynamical_Systems.pdf` — actas *Frontiers in Number Theory, Physics and Geometry I*.
- `051_Borwein-Straub-Wan-Zudilin_2012_Densities_Short_Uniform_Random_Walks.pdf` — densidades de paseos aleatorios uniformes cortos (3–5 pasos); referencia para caminatas de fase. arXiv:1103.2995
- `087_ConreySnaith2008_2008_Communications_in_Number_Theory_and_Physics.pdf` — correlaciones de autovalores y ceros de Riemann (cocientes de polinomios característicos). CNTP (2008). arXiv:0803.2795
- `114_ErdosEtAl2012_2012_Spectral_statistics_of_Erd.pdf` — estadística espectral de grafos de Erdős–Rényi II: espaciados y autovalores extremos. arXiv:1103.3869
- `176_HeuslerEtAl2007_2007_Periodic_orbit_theory_of_level_correlations.pdf` — teoría de órbitas periódicas de las correlaciones de niveles. arXiv:nlin/0610053
- `288_MullerEtAl2005_2005_Periodic_orbit_theory_of_universality_in_quantum_chaos.pdf` — teoría de órbitas periódicas de la universalidad en caos cuántico. arXiv:nlin/0503052
- `221_Keating_2022_Hierarchical_Structure_Trace_Formula.pdf` — J. P. Keating, *Hierarchical structure in the trace formula*, arXiv:2205.13815v1 [nlin.CD] (2022), 10 pág., dedicado a M. Berry. Estructura jerárquica en cómo contribuyen las órbitas periódicas a la fórmula de traza de Gutzwiller, motivada por RMT y teoría de números; consecuencias para la distribución de valores de determinantes espectrales (análogo de los productos de Euler truncados y de la conjetura de Fyodorov–Hiary–Keating).
- `312_PillaiYin2014_2014_Universality_of_covariance_matrices.pdf` — universalidad de matrices de covarianza. Ann. Appl. Probab. 24 (2014), DOI 10.1214/13-AAP939

## 5. Criterio de Li–Weil y positividad

- `079_Coffey_2005_Polygamma_Theory_Li_Keiper_Constants_Riemann_Hypothesis.pdf` — constantes λ_k y c_n, teoría poligamma.
- `339_Sekatskii_2013_Generalized_Bombieri_Lagarias_Li_Criterion.pdf` — teorema de Bombieri–Lagarias generalizado y criterio de Li generalizado.
- `340_Sekatskii_2014_Generalized_Li_Criterion_Zeroes_Location.pdf` — primeras aplicaciones a la localización de ceros. arXiv:1304.7895
- (ver también `080_Coffey_2009_Certain_Sums_Over_Nontrivial_Zeta_Zeros.pdf`)
- `010_AriasdeReyna_2024_Explicit_Formula_Quasicrystal_Definition.pdf` — RH ⇔ cierta medida con Λ(n) y cosh(x/2) es una distribución temperada; definición de cuasicristal de Fourier. arXiv:2402.10604
- `018_BaezDuarte-Balazard-Landreau-Saias_2000_Notes_sur_la_fonction_zeta_de_Riemann_3.pdf` — Báez-Duarte–Balazard–Landreau–Saias, criterio de Nyman–Beurling (distancias). Adv. Math. 149 (2000), DOI 10.1006/aima.1999.1861
- `019_BaezDuarte2002_2002_BaezDuarte2002.pdf` — refuerzo del criterio de Nyman–Beurling. arXiv:math/0202141
- `021_Balazard-Saias-Yor_1999_Notes_Fonction_Zeta_Riemann_2_Transcription_VellaChemla.pdf` — ∫ log|ζ| sobre la recta crítica en términos de los ceros con Re ρ > 1/2. Adv. Math. 143 (1999); transcripción
- `082_Connes1998_1998_Connes1998.pdf` — Connes, fórmula de traza en geometría no conmutativa y ceros de ζ (espectro de absorción). arXiv:math/9811068
- `245_Lagarias2007_2007_Li_coefficients_for_automorphic_functions.pdf` — Lagarias, coeficientes de Li para L-funciones automorfas. Ann. Inst. Fourier 57 (2007)
- `328_RodgersTao2018_2018_RodgersTao2018.pdf` — Rodgers–Tao, la constante de de Bruijn–Newman es no negativa. arXiv:1801.05914
- `338_Sekatskii-Beltraminelli-Merlini_2012_Integrals_Logarithm_Zeta_RH.pdf` — igualdades con integrales de log ζ equivalentes a RH (teorema de Littlewood generalizado)
- `351_Suzuki2025Hilbert_2025_On_the_Hilbert_space_derived_from_the_Weil_distribution.pdf` — Suzuki, espacio de Hilbert derivado de la distribución de Weil. Canad. J. Math. (2025), DOI 10.4153/S0008414X25101739
- `369_Volchkov_1995_Equality_Equivalent_Riemann_Hypothesis_Russian.pdf` — Volchkov, igualdad equivalente a RH (en ruso; **sin capa de texto**)
- `370_Weil_1952_Formules_Explicites_Nombres_Premiers_Transcription_VellaChemla.pdf` — Weil, *Sur les « formules explicites »* (1952); transcripción
- `379_deBruijn1950_1950_The_roots_of_trigonometric_integrals.pdf` — de Bruijn, raíces de integrales trigonométricas (origen de la constante de de Bruijn–Newman). Duke Math. J. 17 (1950) 197–226, DOI 10.1215/S0012-7094-50-01720-0

## 6. Matrices aritméticas: Redheffer, Toeplitz multiplicativas, GCD, Hilbert

- `025_Barrett-Jarvis_1992_Spectral_Properties_Redheffer_Matrix.pdf` — det A_n = M(n); propiedades espectrales.
- `367_Vaughan_1996_Eigenvalues_Redheffer_Matrix_II.pdf` — estimaciones precisas de autovalores. doi:10.1017/S1446788700037654
- `371_Wilf_2004_Redheffer_Matrix_Partially_Ordered_Set.pdf` — permutaciones que contribuyen al determinante; permanente.
- `329_Roesler_1986_Riemann_Hypothesis_Eigenvalue_Problem.pdf` — RH como problema de autovalores de una matriz entera.
- `330_Roesler_1987_Riemann_Hypothesis_Eigenvalue_Problem_II.pdf` — continuación; distribución de autovalores.
- `183_Hilberdink_2006_Determinants_Multiplicative_Toeplitz_Matrices.pdf` — a_ij = f(i/j) con f multiplicativa; determinantes truncados.
- `184_Hilberdink_2015_Multiplicative_Toeplitz_Matrices_Riemann_Zeta.pdf` — conexión directa con ζ.
- `185_Hilberdink_2017_Singular_Values_Multiplicative_Toeplitz_Matrices.pdf` — valores singulares. doi:10.1080/03081087.2016.1204978
- `182_Hilberdink-Pushnitski_2023_Spectral_Asymptotics_LCM_Matrices.pdf` — asintótica espectral de matrices n^σ m^σ / [n,m]^τ. arXiv:2110.14323
- `259_Lindqvist-Seip_1998_Note_Greatest_Common_Divisor_Matrices.pdf` — formas cuadráticas de matrices GCD como normas L².
- `059_Brevig-Perfekt-Seip-Siskakis-Vukotic_2016_Multiplicative_Hilbert_Matrix.pdf` — la matriz de Hilbert multiplicativa. arXiv:1411.7294
- `311_Perfekt-Pushnitski_2018_Spectrum_Multiplicative_Hilbert_Matrix.pdf` — su espectro. arXiv:1705.01959
- `297_Odlyzko-TeRiele_1985_Disproof_Mertens_Conjecture.pdf` — refutación de la conjetura de Mertens.
- `217_Kannan-Bachem_1979_Polynomial_Algorithms_Smith_Hermite_Normal_Forms.pdf` — algoritmos polinómicos para formas normales.
- `244_Labahn-Neiger-Zhou_2018_Hermite_Normal_Form_Polynomial_Matrix.pdf` — forma normal de Hermite para matrices polinómicas. arXiv:1607.04176
- `333_Rota_1964_Foundations_Combinatorial_Theory_Mobius_Functions.pdf` — funciones de Möbius sobre posets.
- `265_Matiyasevich2007a_1983_Hidden_Life_of_Riemann_s_Zeta_Function_1_Arrow_Bow_and_Targets.pdf` — Matiyasevich, RH reformulada como enunciados sobre autovalores de matrices (1). arXiv:0707.1983
- `266_Matiyasevich2007b_2007_Hidden_Life_of_Riemann_s_Zeta_Function_2_Electrons_and_Trains.pdf` — Matiyasevich, ídem (2). arXiv:0709.0028
- `278_Montgomery-Vaughan_1974_Hilberts_Inequality.pdf` — Montgomery–Vaughan, desigualdad de Hilbert generalizada

## 7. Sumas exponenciales y métodos de Van der Corput / Vinogradov

- `150_Graham-Kolesnik_1991_Computing_Optimal_Exponent_Pairs.pdf` — cálculo de pares de exponentes óptimos (cap. 5).
- `151_Graham-Kolesnik_1991_Simplest_Van_Der_Corput_Estimates.pdf` — estimaciones vdC de primera y segunda derivada (cap. 2).
- `053_Bourgain_2017_Decoupling_Exponential_Sums_Riemann_Zeta.pdf` — desacoplamiento; ζ(1/2+it) ≪ t^{13/84+ε}; par de exponentes (13/84, 55/84). arXiv:1408.5794v2, J. Amer. Math. Soc. 30 (2017)
- `323_Revers_2026_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf` — M. Revers, *A new improved explicit estimate for ζ(1/2+it)*, arXiv:2602.05614v1 (2026), 40 pág.; preprint, sin arbitrar. |ζ(1/2+it)| ≤ 0.611 t^{1/6} log t para t ≥ 3 y ≤ 0.566 t^{1/6} log t para t ≥ 8.97·10^17 (Thm. 1.1), por van der Corput explícito más cálculo con aritmética de intervalos (Lema 2.1, §3.4). Mejora el 0.618 de Hiary–Patel–Yang 2024 y completa detalles que, según el autor, faltan en su prueba; recuerda (p. 3) que el error del lema de Cheng–Graham (1/π en vez de 2/π) afecta a Hiary 2016 y a Platt–Trudgian 2015. Fuente alternativa del dato en σ = 1/2 de `rvm_clock_envelope` (Teorema 3.3(a)).
- `179_Hiary-Patel-Yang_2024_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf` — G. A. Hiary, D. Patel, A. Yang, *An improved explicit estimate for ζ(1/2+it)*, J. Number Theory 256 (2024) 195–217, doi:10.1016/j.jnt.2023.09.003. |ζ(1/2+it)| ≤ 0.618 t^{1/6} log t para t ≥ 3 (Thm. 1.1), con una versión nueva del lema de Kusmin–Landau; recupera y mejora el 0.63 de Hiary 2016, afectado por el error del lema de Cheng–Graham. Dato en σ = 1/2 de `rvm_clock_envelope` (Teorema 3.3(a)).
- `305_Patel-Yang_2024_Explicit_Sub_Weyl_Bound_Zeta_Critical_Line.pdf` — D. Patel, A. Yang, *An explicit sub-Weyl bound for ζ(1/2+it)*, J. Number Theory 262 (2024) 301–334, doi:10.1016/j.jnt.2024.03.011. |ζ(1/2+it)| ≤ 66.7 t^{27/164} para t ≥ 3; según el resumen, con sus otros resultados son las cotas más finas conocidas en σ = 1/2 para t ≥ exp(61).
- `373_Yang_2024_Explicit_Bounds_Zeta_Critical_Strip_Zero_Free_Region.pdf` — A. Yang, *Explicit bounds on ζ(s) in the critical strip and a zero-free region*, J. Math. Anal. Appl. 534 (2024) 128124, doi:10.1016/j.jmaa.2024.128124. |ζ(σ_k+it)| ≤ 1.546 t^{1/(2^k−2)} log t con σ_k = 1 − k/(2^k−2), k ≥ 4, t ≥ 3 (Thm. 1.1), por un test explícito de la k-ésima derivada (proceso A^{k−2}B de van der Corput); región libre de ceros de tipo Littlewood σ > 1 − log log|t|/(21.233 log|t|), |t| ≥ 3. **Aviso:** en §3.1 (3 ≤ t ≤ T_k) el Lema 3.1 cita el de Trudgian con log|Q+s| donde va |Log(Q+s)|, y con (3.12) tal como está impresa A(3) = 1.5638, no ≤ 1.4747. Rehecho con aritmética de intervalos para 4 ≤ k ≤ 9, la constante en ese tramo es ≤ 1.878 (`rvm_clock_envelope` v10, Obs. 4.5(ii)). El tramo t ≥ T_k (§3.2) no se ve afectado.
- `306_Patel_2022_Explicit_Upper_Bound_Zeta_1_Line.pdf` — D. Patel, *An explicit upper bound for |ζ(1+it)|*, arXiv:2009.00769v1 (2020); publicado en Indag. Math. 33 (2022) 1012–1032, doi:10.1016/j.indag.2022.04.007. |ζ(1+it)| ≤ min(log t, ½ log t + 1.93, ⅕ log t + 44.02) para t ≥ 3 (Thm. 1.1). La introducción es un buen repaso de la lista histórica de cotas de ζ. Dato en σ = 1 de `rvm_clock_envelope` (Teorema 3.3(c)).
- `178_Hiary-Leong-Yang_2025_Explicit_Bounds_Zeta_1_Line.pdf` — G. A. Hiary, N. Leong, A. Yang, *Explicit bounds for the Riemann zeta-function on the 1-line*, arXiv:2306.13289v2 (2024); publicado en Funct. Approx. Comment. Math. 73 (2025) 53–89, doi:10.7169/facm/240711-13-8. |ζ(1+it)| ≤ 1.731 log t/log log t (Thm. 1) y 1/|ζ(1+it)| ≤ 431.7 log t/log log t (Thm. 2), ambos para t ≥ 3; en §2, de pasada, |ζ(1+it)| ≤ log t − 0.45 para t ≥ 3.
- `029_Bellotti_2024_Explicit_Bounds_Zeta_New_Zero_Free_Region.pdf` — C. Bellotti, *Explicit bounds for the Riemann zeta function and a new zero-free region*, J. Math. Anal. Appl. 536 (2024) 128249, doi:10.1016/j.jmaa.2024.128249. |ζ(σ+it)| ≤ 70.6995 |t|^{4.43795(1−σ)^{3/2}} log^{2/3}|t| para 1/2 ≤ σ ≤ 1, |t| ≥ 3 (Thm. 1.1); región libre de ceros de Korobov–Vinogradov con constante 53.989 (Thm. 1.2). El 58.096 que citan Bellotti–Wong y Fiori para |ζ(1+it)| no aparece aquí (Thm. 1.1 da 70.6995 en σ = 1): es el Lema 5 de Leong, `252_Leong_2024_Explicit_Estimates_Log_Derivative_Reciprocal_Zeta.pdf`.
- `282_Mossinghoff-Trudgian-Yang_2022_Explicit_Zero_Free_Regions_Riemann_Zeta.pdf` — M. J. Mossinghoff, T. S. Trudgian, A. Yang, *Explicit zero-free regions for the Riemann zeta-function*, arXiv:2212.06867v1 (13-12-2022), 27 pág.; versión publicada no comprobada. No hay ceros en σ ≥ 1 − 1/(55.241 (log|t|)^{2/3} (log log|t|)^{1/3}) para |t| ≥ 3, ni en σ ≥ 1 − 1/(5.558691 log|t|) para |t| ≥ 2 (resumen); mejora la región de Ford 2000 (57.54, 49.13). Polinomios trigonométricos no negativos.
- `252_Leong_2024_Explicit_Estimates_Log_Derivative_Reciprocal_Zeta.pdf` — N. Leong, *Explicit estimates for the logarithmic derivative and the reciprocal of the Riemann zeta function*, arXiv:2405.04869v5 (30-1-2026; v1 de 8-5-2024), 31 pág. Lema 5 (p. 8): |ζ(1+it)| ≤ 58.096 (log|t|)^{2/3} para |t| ≥ 3, con el argumento de Bellotti 2024 y otros parámetros (la cota que Bellotti–Wong (2.1) atribuyen a Bellotti). Cotas explícitas de |ζ'/ζ| y |1/ζ| cerca de σ = 1.
- `319_Rademacher_1959_Phragmen_Lindelof_Theorem_Applications.pdf` — H. Rademacher, *On the Phragmén–Lindelöf theorem and some applications*, Math. Z. 72 (1959) 192–204, doi:10.1007/BF01162949. Principio de Phragmén–Lindelöf en una banda con cotas A|Q+s|^α y B|Q+s|^β en las dos rectas (Teorema 2): la versión que usan las cotas explícitas de ζ y de las funciones L.
- `118_Fiori_2025_Note_Phragmen_Lindelof_Theorem.pdf` — A. Fiori, *A note on the Phragmén–Lindelöf theorem*, arXiv:2502.13282v3 (6-1-2026), preprint. Generaliza el teorema de Rademacher (Thm. 1) y corrige el Lema 3 de Trudgian 2014, cuya prueba falla con potencias distintas del logaritmo: según la Obs. 4, |log(Q+s)| no es monótono en σ. El Cor. 3 es la versión con la misma potencia de |log(Q+s)| en las dos rectas. En §4 aplica el resultado a ζ en [1, 2] y en [5/7, 1]. Es el Teorema 3.4 de `rvm_clock_envelope`.
- `224_Kinnunen_1997_Hardy_Littlewood_Maximal_Function_Sobolev_Function.pdf` — análisis armónico auxiliar: maximal de Hardy–Littlewood acotado en W^{1,p}, |D Mu| ≤ M Du. Israel J. Math. 100 (1997)
- `193_Huxley_1989_Exponential_Sums_Riemann_Zeta.pdf` — método de Bombieri–Iwaniec, trabajo Huxley–Watt en contexto.
- `218_Karatsuba-Voronin_1992_Vinogradov_Method_Riemann_Zeta.pdf` — método de Vinogradov, teorema del valor medio (cap. IV).
- `024_Baricz-Laforgia-Pogany_2015_Van_Der_Corput_Inequalities_Bessel.pdf` — desigualdades vdC para funciones de Bessel. doi:10.1080/10652469.2014.975419
- `222_Kelly-Le_2018_Van_Der_Corput_Sets_Compact_Groups.pdf` — conjuntos vdC en grupos compactos. doi:10.1007/s00013-017-1136-y
- `239_Kowalski_2021_Exponential_Sums_Finite_Fields_Elementary.pdf` — métodos elementales, curso ETH.
- `240_Kowalski_2021_Exponential_Sums_Finite_Fields_II.pdf` — métodos cohomológicos.
- `208_Jun-Lee_2014_Dedekind_And_Exponential_Sums.pdf` — equidistribución de sumas de Dedekind generalizadas. doi:10.1016/j.jnt.2013.10.020
- `295_Norvidas_2011_Entire_Functions_Exponential_Sums.pdf` — espacios de Bernstein y sumas exponenciales.
- `122_Ford_2002_Vinogradov_Integral_Bounds_Riemann_Zeta.pdf` — Ford, integral de Vinogradov y cotas para ζ; región libre de ceros. arXiv:1910.08209
- `155_GrepstadEtAl2019_1909_On_the_asymptotic_behaviour_of_the_sine_product.pdf` — comportamiento asintótico del producto de senos Π|2 sin πrα|. arXiv:1909.00980
- `159_Guth-Maynard_2026_New_Large_Value_Estimates_Dirichlet_Polynomials.pdf` — Guth–Maynard, nuevas estimaciones de valores grandes de polinomios de Dirichlet. arXiv:2405.20552
- `256_LiYang2023_2023_An_improvement_on_Gauss_s_circle_problem_and_Dirichlet_s_divisor_problem.pdf` — mejora en el problema del círculo de Gauss y del divisor de Dirichlet (Bombieri–Iwaniec). arXiv:2308.14859

## 8. Funciones multiplicativas: Liouville, Möbius, Chowla

- `270_Matomaki-Radziwill_2016_Multiplicative_Functions_Short_Intervals.pdf` — **el teorema MR**: promedios cortos vs. largos. doi:10.4007/annals.2016.183.3.6
- `268_Matomaki-Radziwill_2015_Liouville_Short_Intervals.pdf` — prueba corta y autocontenida para λ(n). arXiv:1502.02374
- `267_Matomaki-Radziwill-Tao_2015_Averaged_Chowla_Conjecture.pdf` — Chowla promediada. arXiv:1503.05121
- `164_Harman-Pintz-Wolke_1985_Mobius_And_Liouville_Functions.pdf` — nota sobre valores de μ y λ.
- `071_Cassaigne-Ferenczi-Mauduit-Rivat-Sarkozy_1999_Liouville_Pseudorandom_Sequences.pdf` — λ como sucesión binaria pseudoaleatoria.
- `094_Croot_2003_Oscillations_Multiplicative_PlusMinusOne.pdf` — oscilaciones de funciones multiplicativas ±1. [texto extraído ilegible]
- `152_Granville-Soundararajan_2003_Decay_Of_Mean_Values.pdf` — decaimiento de valores medios. [texto extraído ilegible]
- `336_Sawin_2022_Mobius_Cancellation_Polynomial_Sequences.pdf` — cancelación de Möbius en F_q[u], análogo de Chowla. doi:10.1007/s00222-022-01115-y
- `108_Drmota_2009_Sum_Of_Digits_Of_Primes.pdf` — suma de dígitos de los primos (charla, con Mauduit y Rivat).
- `001_AbercrombieBanksShparlinski2009_2009_Arithmetic_functions_on_Beatty_sequences.pdf` — funciones aritméticas sobre sucesiones de Beatty. Acta Arith. 136 (2009), DOI 10.4064/aa136-1-6
- `015_Aymone-Sidoravicius_2017_Partial_Sums_Biased_Random_Multiplicative_Functions.pdf` — sumas parciales de funciones multiplicativas aleatorias sesgadas. arXiv:1412.1157
- `016_Aymone2020_2020_A_note_on_multiplicative_functions_resembling_the_M_bius_function.pdf` — funciones multiplicativas que se parecen a μ con M_f(x)=o(√x). arXiv:1908.11014
- `034_BergelsonKulagaPrzymusLemanczykRichter2019_2019_Discrete_Contin_Dyn_Syst.pdf` — generalización del criterio de ortogonalidad de Kátai. arXiv:1705.07322
- `039_Bjorner_2011_Cell_Complex_Number_Theory.pdf` — Björner, complejo simplicial de los libres de cuadrados; característica de Euler = función de Mertens. arXiv:1101.5704
- `054_Bourgain_undated_On_the_Fourier_Walsh_spectrum_of_the_M_obius_function.pdf` — Bourgain, espectro de Fourier–Walsh de μ. arXiv:1112.1423
- `058_BretcheDressTenenbaum2020_2020_Mathematika.pdf` — de la Bretèche–Dress–Tenenbaum, la suma M(n,z)=Σ_{d|n, d≤z} μ(d). arXiv:1902.09956
- `091_Coons2010_2010_On_the_multiplicative_Erd_s_discrepancy_problem.pdf` — problema de discrepancia de Erdős multiplicativo. arXiv:1003.5388
- `129_Frantzikinakis2020_1908_Correlations_of_multiplicative_functions_along_deterministic_and_independent_sequences.pdf` — correlaciones de funciones multiplicativas sobre sucesiones deterministas e independientes (2020; el «1908» del nombre es el id arXiv). arXiv:1908.02732
- `166_Harper_2020_Moments_Random_Multiplicative_Functions_I.pdf` — Harper, momentos bajos de funciones multiplicativas aleatorias; caos multiplicativo crítico. arXiv:1703.06654
- `173_HelfgottRadziwill2021_undated_HelfgottRadziwill2021.pdf` — Helfgott–Radziwiłł, expansión, divisibilidad y paridad. arXiv:2103.06853
- `211_Kaczorowski-Pintz_1986_Oscillatory_Properties_Arithmetical_Functions_I.pdf` — Kaczorowski–Pintz, propiedades oscilatorias de funciones aritméticas I. Acta Math. Hung. 48 (1986)
- `236_Kotnik-vandeLune_2004_Order_Mertens_Function.pdf` — Kotnik–van de Lune, orden de la función de Mertens (experimento numérico sobre M(x)/√x)
- `251_LeeLeong2024_2024_New_explicit_bounds_for_the_Mertens_function_and_the_reciprocal_of_the_Riemann_zeta_function.pdf` — cotas explícitas incondicionales para M(x) y para 1/ζ en la banda crítica. arXiv:2208.06141
- `261_Liu2022_2022_Multiplicative_functions_resembling_the_M_bius_function.pdf` — funciones multiplicativas parecidas a μ: resultados O y Ω. arXiv:2205.00972
- `271_Matomaki-Shao-Tao-Teravainen_2023_Higher_Uniformity_Arithmetic_Functions.pdf` — uniformidad superior de μ, Λ y d_k en intervalos cortos. arXiv:2204.03754
- `272_Matomaki-Teravainen_2023_Mobius_Function_All_Short_Intervals.pdf` — μ en todos los intervalos cortos, Σ_{x<n≤x+x^θ} μ(n)=o(x^θ) para θ>0.55. arXiv:1911.09076
- `275_MelottiSaias2020_2020_On_path_partitions_of_the_divisor_graph.pdf` — particiones en caminos del grafo de divisores. arXiv:1807.07783
- `276_Mirsky_1949_Frequency_Pairs_Square_Free_Numbers_Given_Difference.pdf` — Mirsky, frecuencia de pares de libres de cuadrados con diferencia dada (1949)
- `283_MossinghoffOliveiraTrudgian2021_2021_The_distribution_of_k_free_numbers.pdf` — distribución de los k-libres: error R_k(x). arXiv:1912.04972
- `287_Muellner2017_2017_Automatic_sequences_fulfill_the_Sarnak_conjecture.pdf` — las sucesiones automáticas cumplen la conjetura de Sarnak. arXiv:1602.03042
- `290_MussardoLeClair2021_2021_Randomness_of_M_obius_coefficients_and_Brownian_motion_growth_of_the_Mertens_function_and_the_Riemann_hypothes.pdf` — Mussardo–LeClair, aleatoriedad de μ, movimiento browniano y crecimiento de M(x). arXiv:2101.10336
- `292_Ng2004_2004_Proc_London_Math_Soc.pdf` — Ng, distribución de M(x) bajo RH y otras hipótesis. arXiv:math/0310381
- `296_Nunes2015_2015_Journal_of_Number_Theory.pdf` — libres de cuadrados en progresiones aritméticas. arXiv:1402.0684
- `313_Pintz_2026_Oscillation_Mobius_Function_Zeta_Zeros.pdf` — Pintz, oscilación de M(x) y ceros de ζ. arXiv:2608.24878
- `348_Soundararajan_2009_Partial_Sums_Mobius_Function.pdf` — Soundararajan, sumas parciales de μ: M(x) bajo RH. arXiv:0705.0723
- `353_Tao-Teravainen_2018_Odd_Order_Logarithmically_Averaged_Chowla.pdf` — Tao–Teräväinen, casos de orden impar de Chowla con media logarítmica. arXiv:1710.02112
- `354_Tao-Teravainen_2019_Structure_Logarithmically_Averaged_Correlations.pdf` — Tao–Teräväinen, estructura de las correlaciones logarítmicas; Chowla y Elliott. arXiv:1708.02610
- `356_Tao_2016_Logarithmically_Averaged_Chowla_Elliott_Two_Point.pdf` — Tao, Chowla y Elliott logarítmicos para correlaciones de dos puntos. arXiv:1509.05422
- `359_Tenenbaum_2017_Generalized_Mertens_Sums.pdf` — Tenenbaum, sumas de Mertens generalizadas. arXiv:1910.02781

## 9. Números smooth e intervalos cortos

- `153_Granville_2008_Smooth_Numbers_Survey.pdf` — survey de referencia (MSRI).
- `022_Balog_1987_Integers_Without_Large_Prime_Factors.pdf` — Astérisque 147-148, pp. 27-31.
- `130_Friedlander-Granville_1993_Smoothing_Smooth_Numbers.pdf` — [texto extraído ilegible]
- `095_Croot_2007_Smooth_Numbers_Short_Intervals.pdf` — exponente 3/(14√e)+ε.
- `273_Matomaki_2010_Smooth_Numbers_Short_Intervals.pdf` — exponente 1/(5√e)+ε en [x, x+C√x].
- `274_Matomaki_2016_Smooth_Numbers_Short_Intervals_II.pdf` — intervalo √x(log x)^{7/3+δ}.
- `349_Soundararajan_2010_Smooth_Numbers_Short_Intervals.pdf` — bajo RH, x^ε-smooth en [x, x+C(ε)√x]. arXiv:1009.1591

## 10. Formas modulares, L-funciones y momentos

- `372_Xylouris_2011_Nullstellen_Dirichletschen_L_Funktionen_Kleinste_Primzahl.pdf` — T. Xylouris, *Über die Nullstellen der Dirichletschen L-Funktionen und die kleinste Primzahl in einer arithmetischen Progression*, tesis, Bonn, 2011 (Bonner Math. Schriften 404). Constante de Linnik L = 5 (Kap. 6). No es la tesis de Grossmann (1913).
- `165_Harper_2013_Conditional_Bounds_Zeta_Moments.pdf` — bajo RH, momentos 2k-ésimos ≪ T log^{k²}T. arXiv:1305.4618
- `209_Jutila_1977_Zero_Density_Estimates_L_Functions.pdf` — M. Jutila, *Zero-density estimates for L-functions*, Acta Arithmetica **XXXII** (1977), pp. 55–62; completo, en 5 hojas a doble página. Método de Halász–Montgomery para mejorar Ingham en σ > 3/4; el corolario da N(α,q,χ) con A(α)=2 para α ≥ 21/26 = 0.8076…, 7/9 y 11/14 = 0.7857… según k.
- `136_Gallagher_1970_Large_Sieve_Density_Estimate_Near_Sigma_1.pdf` — P. X. Gallagher, *A large sieve density estimate near σ = 1*, Invent. Math. **11** (1970), 329–339, doi:10.1007/BF01403187; 11 pág. Fuente del teorema de los números primos de Gallagher (Teorema 7) usado en (I6) de rh_stepwise.
- `284_Motohashi_1977_On_Gallaghers_Prime_Number_Theorem.pdf` — Y. Motohashi, *On Gallagher's prime number theorem*, Proc. Japan Acad. **53**, Ser. A (1977), 50–52, doi:10.3792/pjaa.53.50; 3 pág. Versión con el factor min(1, δ log x) del cero excepcional; OCR defectuoso en fórmulas (mirar la página).
- `285_Motohashi_1978_Primes_in_Arithmetic_Progressions.pdf` — Y. Motohashi, *Primes in arithmetic progressions*, Invent. Math. **44** (1978), 163–178, doi:10.1007/BF01390349; 16 pág. Demostración completa del teorema de Gallagher en el caso con carácter excepcional.
- `320_Radziwill-Soundararajan_2015_Quadratic_Twists_Central_L_Values.pdf` — momentos y distribución de valores centrales. arXiv:1403.7067
- `140_Ghosh-Sarnak_2012_Real_Zeros_Hecke_Cusp_Forms.pdf` — ceros reales de formas cuspidales de Hecke. arXiv:1103.3262
- `253_Lester-Matomaki-Radziwill_2015_Small_Scale_Zeros_Modular_Forms.pdf` — ceros y masa a escala pequeña. arXiv:1501.01292
- `269_Matomaki-Radziwill_2015_Sign_Changes_Hecke_Eigenvalues.pdf` — cambios de signo de λ_f(n). arXiv:1405.7671
- `249_Lau-Liu-Wu_2010_Symmetric_Square_L_Function_Coefficients.pdf` — resultados Ω± para el cuadrado simétrico.
- `238_Kowalski-Robert-Wu_2007_Small_Gaps_And_B_Free_Numbers.pdf` — no existencia de gaps en series de formas modulares.
- `084_Conrad_2005_Partial_Euler_Products_Critical_Line.pdf` — Conrad, productos de Euler parciales en la recta crítica (de Birch–Swinnerton-Dyer a RH). Canad. J. Math. 57 (2005)
- `142_Goldfeld_1982_Produits_Partiels_Euleriens_Courbes_Elliptiques.pdf` — Goldfeld, productos parciales eulerianos de curvas elípticas. C. R. Acad. Sci. Paris 294 (1982)
- `147_Gonek_2012_Finite_Euler_Products_Riemann_Hypothesis.pdf` — Gonek, productos de Euler finitos y RH; modelo ζ_X = P_X + χP_X(1−s). Trans. AMS 364 (2012) 2157–2191, DOI 10.1090/S0002-9947-2011-05546-7
- `141_Ghosh_2022_Statistics_Approximations_Zeros_Truncated_Symmetrized_Euler_Products.pdf` — A. Ghosh, *Report: Statistics of approximations to zeroes of ζ-function via truncated symmetrized Euler products*, arXiv:2211.11042v2 (2022), 24 pág.; informe, sin arbitrar. Ceros de la ζ_X de Gonek 2012: distancia entre ceros aproximados y ceros reales con X fijo (§1) y con X ≈ t/2π (§3.1); heurística vía F_X y sus pendientes casi constantes cerca de las ordenadas γ (§3.2).
- `342_Sheth_2025_Euler_Products_Centre_Chebyshev_Bias.pdf` — Sheth, productos de Euler en el centro y sesgo de Chebyshev. Math. Proc. Camb. Phil. Soc. 179 (2025), DOI 10.1017/S0305004125000234
- `008_Arguin-Bourgade-Radziwill_2020_Fyodorov_Hiary_Keating_Conjecture_I.pdf` — L.-P. Arguin, P. Bourgade, M. Radziwiłł, *The Fyodorov–Hiary–Keating Conjecture. I*, arXiv:2007.00988v2 (2020), 49 pág. Incondicional: cota superior del máximo de |ζ| en intervalos cortos, medida ≪ y e^{-2y}. Esquema iterativo multiescala con barreras; §7 *Decoupling and second moment* (aproximación de indicadores por polinomios de Dirichlet, comparación con modelo aleatorio), §8 *Decoupling and twisted fourth moment*, Apéndice A sumas sobre primos. Fuente del desacoplo de escalas de primos.
- `009_Arguin-Bourgade-Radziwill_2023_Fyodorov_Hiary_Keating_Conjecture_II.pdf` — mismos autores, *The Fyodorov–Hiary–Keating Conjecture. II*, arXiv:2307.00982v1 (2023), 41 pág. Incondicional: cota inferior; tensión de max log|ζ| − (log log T − ¾ log log log T); §3 *Approximations by Gaussian random walks*; Lema 5: aproximación integral de ζ por producto de Euler finito directamente en la recta crítica.

## 11. Determinantes de Hankel y valores de ζ

- `170_Haynes-Zudilin_2015_Hankel_Determinants_Zeta_Values.pdf` — asintótica de Hankel con ζ(an+b); aplicación diofántica. arXiv:1510.01901
- `277_Monien_2009_Hankel_Determinants_Dirichlet_Series.pdf` — determinantes de Hankel de series de Dirichlet. arXiv:0901.1883
- `116_FazziGuglielmiMarkovsky2021_2021_A_gradient_system_approach_for_Hankel_structured_low_rank_approximation.pdf` — enfoque de sistema gradiente para aproximación de bajo rango con estructura de Hankel. arXiv:2002.06621
- `350_StampachStovicek2020_2020_On_Hankel_matrices_commuting_with_Jacobi_matrices_from_the_Askey_scheme.pdf` — matrices de Hankel que conmutan con matrices de Jacobi del esquema de Askey. arXiv:1911.07059

## 12. Verificación numérica y cálculo

- `316_Platt-Trudgian_2021_RH_True_Up_To_3e12.pdf` — RH verificada rigurosamente (aritmética de intervalos) hasta altura 3·10^12. arXiv:2004.09765
- `344_Sidi_2003_Riemann_And_Generalized_Zeta_Extrapolation.pdf` — extrapolación numérica de ζ (apéndice E).
- (ver también `298_Odlyzko_1987_Distribution_Spacings_Between_Zeros_Zeta.pdf` y `297_Odlyzko-TeRiele_1985_Disproof_Mertens_Conjecture.pdf`)
- `056_Brent2018_2019_On_asymptotic_approximations_to_the_log_Gamma_and_Riemann_Siegel_theta_functions.pdf` — Brent, cotas del error en las aproximaciones asintóticas de log Γ y de la θ de Riemann–Siegel (reloj RvM). arXiv:1609.03682
- `057_Brent_1979_Zeros_Riemann_Zeta_Critical_Strip.pdf` — Brent, ceros de ζ en la banda crítica (verificación, 1979); **sin capa de texto**
- `065_Buthe2014_2015_A_method_for_proving_the_completeness_of_a_list_of_zeros_of_certain_functions.pdf` — Büthe, método para probar la completitud de una lista de ceros (extensión del método de Turing). arXiv:1308.6704
- `092_Corless-Gonnet-Hare-Jeffrey-Knuth_1996_Lambert_W_Function.pdf` — Corless–Gonnet–Hare–Jeffrey–Knuth, la función W de Lambert (inversión del reloj). Adv. Comput. Math. 5 (1996)
- `172_Helfgott-Thompson_2023_Summing_Mobius_Faster_Elementary_Algorithm.pdf` — Helfgott–Thompson, algoritmo elemental más rápido para M(x). arXiv:2101.08773
- `189_Hurst2026_2026_Practical_computations_of_the_Mertens_function_M_10.pdf` — Hurst, cálculo de M(10^24) y M(10^25). arXiv:2607.07566
- `190_Hurst_2018_Computations_Mertens_Function_Improved_Bounds.pdf` — Hurst, cálculos de M(x) y cotas mejoradas de la conjetura de Mertens. arXiv:1610.08551
- `191_Hutchinson_1925_Roots_Riemann_Zeta_Function.pdf` — Hutchinson, raíces de ζ (cálculo de ceros, ley de Gram). Trans. AMS 27 (1925)
- `205_Johansson_2017_Arb_Arbitrary_Precision_Interval_Arithmetic.pdf` — Johansson, Arb: aritmética de intervalos de precisión arbitraria. arXiv:1611.02831
- `206_Johansson_2018_Numerical_Integration_Ball_Arithmetic.pdf` — Johansson, integración numérica en aritmética de bolas. arXiv:1802.07942
- `317_Platt_2017_Isolating_Nontrivial_Zeros_Zeta.pdf` — Platt, aislamiento de ceros no triviales de ζ. Math. Comp., DOI 10.1090/mcom/3198

## 13. Tratados, monografías y panorámicas

- `162_Hardy-Littlewood-Polya_1934_Inequalities.pdf` — G. H. Hardy, J. E. Littlewood, G. Pólya, *Inequalities*, Cambridge University Press, **1.ª edición, 1934**. Cap. X, Rearrangements; §10.12 (pp. 276–278) define el reordenamiento en orden decreciente como inversa de la función de distribución.
- `258_Lieb-Loss_2001_Analysis_Second_Edition.pdf` — E. H. Lieb, M. Loss, *Analysis*, 2.ª ed., Grad. Stud. Math. 14, AMS, 2001, doi:10.1090/gsm/014. Thm. 1.14, principio de la bañera (p. 28).
- `337_Schechter_2002_Principles_Functional_Analysis_Second_Edition.pdf` — M. Schechter, *Principles of Functional Analysis*, 2.ª ed., Grad. Stud. Math. 36, AMS, 2002.
- `243_LMS_2015_Atle_Selberg_Obituary.pdf` — necrológica de Atle Selberg (London Mathematical Society; el PDF no lleva autor y es de 7-4-2015), con su lista de publicaciones; [15] es *Contributions to the theory of the Riemann zeta-function*, Arch. Math. Naturvid. 48 (1946) no. 5, 89–155. No enuncia los momentos de S(t).
- `331_Rosser-Schoenfeld_1962_Approximate_Formulas_Functions_Prime_Numbers.pdf` — J. B. Rosser, L. Schoenfeld, *Approximate formulas for some functions of prime numbers*, Illinois J. Math. 6 (1962) 64–94, doi:10.1215/ijm/1255631807. Cotas explícitas de θ, ψ, π(x), p_n. No contiene la cota de N(T) de Rosser 1941.
- `326_Riemann-Wilkins_1859_Prime_Counting_English_Translation.pdf` — **el texto de Riemann**, en alemán (original de 1859 transcrito por D. R. Wilkins, 10 páginas; no es una traducción al inglés pese al nombre del fichero). La inversión de Möbius para π y la serie Li(x) − ½Li(x^{1/2}) − ⅓Li(x^{1/3}) − ⅕Li(x^{1/5}) + ⅙Li(x^{1/6}) − … están en las págs. 8–9.
- `360_Titchmarsh-HeathBrown_1986_Theory_Riemann_Zeta_Function.pdf` — el tratado estándar. 2ª edición revisada por D. R. Heath-Brown, Clarendon Press. 418 hojas que llegan hasta la página impresa 412; las *Further references* de Heath-Brown terminan en Weil, así que el escaneo está completo.
- `199_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf` — Wiley 1985, edición original. 538 pág. escaneadas; **con capa OCR desde 2026-08-19**, ya es grepeable. Completo (el índice de materias llega hasta las entradas en Z). No incluye erratas: usar `ERRATA_Ivic.md`.
- `201_Ivic_2003_Riemann_Zeta_Dover_Reprint.pdf` — **mismo libro que `199_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf`**. Dover 2003, *unabridged republication* de Wiley 1985: cuerpo y paginación idénticos, no es una edición revisada. Lo único que añade es la lista de erratas en pág. xvii–xix (PDF 15–17), transcrita en `ERRATA_Ivic.md`. Completo; con capa OCR desde 2026-08-19.
- `112_Edwards_1974_Riemanns_Zeta_Function.pdf` — **ESCANEO INCOMPLETO**. Reimpresión Dover 2001 del original de Academic Press 1974. El PDF tiene 135 hojas que cubren las páginas impresas **1–122 de 311** (desfase: hoja PDF ≈ página impresa + 13).
  - **Sí está**: cap. 1 el paper de Riemann (p. 1), cap. 2 fórmula del producto para ξ (39), cap. 3 fórmula principal de Riemann (48), cap. 4 teorema de los números primos (68), cap. 5 De la Vallée Poussin (88), cap. 6 análisis numérico de las raíces por Euler–Maclaurin (96) — hasta ~p. 122.
  - **No está**: cap. 7 fórmula de Riemann–Siegel (136), cap. 8 cálculos a gran escala / Turing / fenómeno de Lehmer (171), cap. 9 crecimiento de zeta y Lindelöf (182), cap. 10 análisis de Fourier (203), cap. 11 ceros en la línea / teorema de Hardy (226), cap. 12 miscelánea (260), apéndice con el paper de Riemann (299), referencias (306) e índice (311).
  - Consecuencia práctica: para Riemann–Siegel, Turing o Hardy **no sirve este fichero**; usar `360_Titchmarsh-HeathBrown_1986_Theory_Riemann_Zeta_Function.pdf` o los Ivić de la biblioteca.
- `307_Patterson_1988_Introduction_Riemann_Zeta_Function.pdf` — S. J. Patterson, *An Introduction to the Theory of the Riemann Zeta-Function*, Cambridge Studies in Advanced Mathematics **14**. 172 hojas, completo (bibliografía p. 153, índice p. 156).
- `308_Patterson_1988_Zeros_Zeta_And_Prime_Number_Theorem.pdf` — cap. 4, ceros y TNP. doi:10.1017/CBO9780511623707.006
- `286_Motohashi_1997_Spectral_Theory_Riemann_Zeta.pdf` — teoría espectral, Cambridge Tracts 127.
- `358_Tenenbaum_2015_Analytic_Probabilistic_Number_Theory.pdf` — GSM 163, 3ª edición.
- `322_Ramachandra_1976_Problems_Analytic_Number_Theory.pdf` — K. Ramachandra, *Some problems of analytic number theory*, Acta Arithmetica **XXXI** (1976), pp. 313–324; completo, en 7 hojas a doble página. Dedicado a la memoria de Turán. Primos en intervalos cortos, resultado de Selberg para N₀(x), método de Heilbronn y aproximación diofántica simultánea.
- `046_Bombieri_2010_Classical_Theory_Zeta_And_L_Functions.pdf` — panorámica histórica. doi:10.1007/s00032-010-0121-8
- `090_Conrey_2003_Riemann_Hypothesis.pdf` — el survey del Notices.
- `088_Conrey_1986_Review_Ivic_Riemann_Zeta_Function.pdf` — reseña de una página (American Scientist).
- `163_Hardy-Littlewood_1917_Riemann_Zeta_And_Distribution_Primes.pdf` — memoria original de Acta Mathematica.
- `076_Christ_2014_Value_Distribution_Zeta_Near_Critical_Line_Thesis.pdf` — tesis doctoral (Würzburg 2013, 191 pág.): distribución de valores de ζ y funciones afines cerca de la recta crítica. arXiv:1405.1553
- `083_Connes2026_2026_Connes2026.pdf` — Connes, *The Riemann Hypothesis: past, present and a letter through time* (panorámica, 2026). arXiv:2602.04022
- `093_Cramer_1919_Nullstellen_Riemannschen_Zetafunktion.pdf` — Cramér, estudios sobre los ceros de ζ. Math. Z. 4 (1919)
- `160_Hadamard_1896_Distribution_Zeros_Zeta_Consequences_Arithmetiques.pdf` — Hadamard, distribución de los ceros de ζ y consecuencias aritméticas. Bull. SMF 24 (1896)
- `247_Landau_1912_Nullstellen_Zetafunktion.pdf` — Landau, sobre los ceros de la función zeta. Math. Ann. 71 (1912)
- `260_Littlewood_1924_Zeros_Riemann_Zeta_Function.pdf` — Littlewood, sobre los ceros de ζ. Proc. Camb. Phil. Soc. (1924), DOI 10.1017/S0305004100014225
- `380_deLaValleePoussin_1896_Recherches_Analytiques_Nombres_Premiers_I.pdf` — de la Vallée Poussin, *Recherches analytiques…* I (1896): teorema de los números primos
- `381_vonMangoldt_1895_Zu_Riemanns_Abhandlung_Anzahl_Primzahlen.pdf` — von Mangoldt, sobre la memoria de Riemann (1895)

## 14. Otras funciones zeta y contextos adyacentes

- `167_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Dedekind_Zeta.pdf` — E. Hasanalizade, Q. Shen, P.-J. Wong, *Counting zeros of Dedekind zeta functions*, Math. Comp. 91 (2022) 277–293, doi:10.1090/mcom/3665. Prop. 3.5 (Jensen) y Prop. 3.7 (truco de Backlund) para ζ_K; Bellotti–Wong las usan con K = Q como sus Lemas 2.1 y 2.3.
- `013_Avdonin-Ivanov_2001_Exponential_Riesz_Bases_Subspaces_Divided_Differences.pdf` — bases de Riesz de exponenciales y de diferencias divididas; criterio de Pavlov vía Helson–Szegő/A₂. arXiv:math/0103160
- `263_Lyubarskii-Seip_1997_Complete_Interpolating_Sequences_Paley_Wiener_Muckenhoupt_Ap.pdf` — sucesiones de interpolación completa en Paley–Wiener y condición A_p; Kadec 1/4 como corolario. Rev. Mat. Iberoam. 13 (1997), DOI 10.4171/RMI/224
- `194_Igusa_2000_Introduction_Local_Zeta_Functions.pdf` — zetas locales.
- `228_Komori-Matsumoto-Tsumura_2023_Zeta_Functions_Root_Systems.pdf` — zetas de sistemas de raíces.
- `257_Li_2019_Zeta_L_Functions_Number_Theory_Combinatorics.pdf` — CBMS 129. doi:10.1090/cbms/129
- `377_Zhao_2016_Multiple_Zeta_Polylogarithms_Special_Values.pdf` — zetas múltiples y polilogaritmos.
- `248_Lapidus-VanFrankenhuysen_2000_Fractal_Geometry_Number_Theory.pdf` — dimensiones complejas de cuerdas fractales.
- `215_Kanemitsu-Tsukada_2015_Hecke_Type_Zeta_Functions.pdf` — cap. 8 de *Contributions to the Theory of Zeta-Functions*.
- `216_Kanemitsu-Tsukada_2015_Modular_Relation_Supremacy.pdf` — *Contributions to the Theory of Zeta-Functions: The Modular Relation Supremacy*, World Scientific, Series on Number Theory and Its Applications vol. 9. 316 hojas, completo (índice hasta p. 303). Fórmulas de Voronoĭ, funciones de Bessel generalizadas de Wilton, transformación theta.
- `040_Bloch_2000_Higher_Regulators_K_Theory_Zeta_Elliptic_Curves.pdf` — S. Bloch, monografía AMS (vol. 11 de la serie), 110 pág., completo. Reguladores superiores, K-teoría algebraica y funciones zeta de curvas elípticas.
- `318_Popov_1985_Transfer_Functions_Riemann_Zeta.pdf` — sistemas con funciones de transferencia ligadas a ζ.
- `207_Jones-Sato-Wada-Wiens_1976_Diophantine_Representation_Primes.pdf` — el polinomio de 26 variables (Monthly).
- `229_Korolev-Laurincikas_2023_Approximation_Mellin_Transform_Zeta_Axioms.pdf` — aproximación de ζ por transformadas de Mellin. Axioms 12 (2023), 520.
- `020_Balanzario-SanchezOrtiz_2007_Zeros_Davenport_Heilbronn_Counterexample.pdf` — ceros fuera de la recta del contraejemplo de Davenport–Heilbronn. Math. Comp. 76 (2007)
- `045_Bohr_1926_Fastperiodische_Funktionen_III_Dirichletentwicklung.pdf` — Bohr, funciones casi periódicas III: desarrollos de Dirichlet. Acta Math. (1926)
- `073_Chandrasekharan-Mandelbrojt_1959_Solutions_Riemann_Functional_Equation.pdf` — Chandrasekharan–Mandelbrojt, soluciones de la ecuación funcional de Riemann (1959)
- `099_Davenport-Heilbronn_1936_Zeros_Certain_Dirichlet_Series_I.pdf` — Davenport–Heilbronn, ceros de ciertas series de Dirichlet I (1936)
- `156_Grosswald-Schnitzer_1978_Class_Modified_Zeta_L_Functions.pdf` — Grosswald–Schnitzer, una clase de funciones ζ y L modificadas. Pacific J. Math. 74 (1978)
- `161_Hamburger_1921_Riemannsche_Funktionalgleichung_Zeta_Funktion_I.pdf` — Hamburger, ecuación funcional de Riemann I. Math. Z. 10 (1921)
- `174_HerichiLapidus2014_2014_Truncated_infinitesimal_shifts_spectral_operators_and_quantized_universality_of_the_Riemann_zeta_function.pdf` — Herichi–Lapidus, desplazamientos infinitesimales truncados y universalidad cuantizada de ζ. Ann. Fac. Sci. Toulouse 23 (2014)
- `175_HerreraMoree2018_2018_Coefficients_and_higher_order_derivatives_of_cyclotomic_polynomials_old_and_new.pdf` — coeficientes y derivadas de polinomios ciclotómicos. arXiv:1805.05207
- `186_Hoffman1992_1992_Multiple_harmonic_series.pdf` — Hoffman, series armónicas múltiples. Pacific J. Math. 152 (1992)
- `210_Kaczorowski-Perelli_1999_Structure_Selberg_Class_I.pdf` — Kaczorowski–Perelli, estructura de la clase de Selberg I. Acta Math. 182 (1999)
- `225_Knopp_1994_Dirichlet_Series_Riemann_Functional_Equation.pdf` — Knopp, series de Dirichlet con la ecuación funcional de Riemann (Hamburger). Invent. Math. 117 (1994)
- `291_Nakamura_2020_Dirichlet_Series_Periodic_Coefficients_Functional_Equation.pdf` — series de Dirichlet de coeficientes periódicos con la ecuación funcional de Riemann; ceros reales de L(s,χ). arXiv:2008.02570
- `310_Perelli_2016_Converse_Theorems_Zeta_Selberg_Class.pdf` — Perelli, teoremas recíprocos: de ζ a la clase de Selberg. arXiv:1605.02354
- `345_Siegel_1922_Satz_Hamburger_Funktionalgleichung_Zetafunktion.pdf` — Siegel, sobre el teorema de Hamburger. Math. Ann. 86 (1922)

## 15. Material no arbitrado — contrastar antes de usar

- `096_Dannon_2008_Riemann_Zeta_Function.pdf` — Gauge Institute Journal.
- `368_Vega_2023_Simple_Proof_Riemann_Hypothesis.pdf` — vía función Ψ de Dedekind. doi:10.33774/coe-2023-5flmk
- `141_Ghosh_2022_Statistics_Approximations_Zeros_Truncated_Symmetrized_Euler_Products.pdf` — informe de 2022 sobre los ceros de ζ_X de Gonek; ver §10.
- `323_Revers_2026_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf` — preprint v1 de 2026 (cota explícita de ζ(1/2+it)); ver §7. Afirma completar una prueba publicada; contrastar antes de usarlo como única fuente.
- `118_Fiori_2025_Note_Phragmen_Lindelof_Theorem.pdf` — preprint (arXiv v3, 2026) sobre Phragmén–Lindelöf; ver §7. Corrige un lema publicado (Trudgian 2014, Lema 3).
- `006_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` — preprint anónimo de 2026 sobre S(N)=Σ e^{iγ_n}, citas rotas.
- `375_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf` — ver §1.

## 16. Primos generalizados de Beurling

- `037_Beurling_1937_Distribution_Nombres_Premiers_Generalises_I.pdf` — Beurling, primos generalizados I (1937)
- `060_Broucke-Debruyne-Revesz_2025_Well_Behaved_Beurling_Number_Systems.pdf` — sistemas de Beurling bien comportados (ahorro de potencia en primos y enteros). arXiv:2309.01567
- `061_Broucke-Debruyne-Vindas_2020_Beurling_Integers_RH_Large_Oscillation.pdf` — enteros de Beurling con RH y oscilación grande. arXiv:2004.11501
- `062_Broucke-Vindas_2024_Generalized_Prime_Random_Approximation.pdf` — aproximación aleatoria de primos generalizados. arXiv:2102.08478
- `101_Debruyne-Vindas_2019_Complex_Tauberian_Theorems_Laplace_Transforms.pdf` — teoremas tauberianos complejos para transformadas de Laplace. arXiv:1604.05069
- `106_Diamond-Montgomery-Vorhauer_2006_Beurling_Primes_Large_Oscillation.pdf` — Diamond–Montgomery–Vorhauer, primos de Beurling con oscilación grande. Math. Ann. 334 (2006), DOI 10.1007/s00208-005-0638-2
- `107_Diamond_1970_Asymptotic_Distribution_Beurling_Generalized_Integers.pdf` — Diamond, distribución asintótica de los enteros generalizados de Beurling (1970)
- `181_Hilberdink-Lapidus_2006_Beurling_Zeta_Generalised_Primes_Fractal_Membranes.pdf` — Hilberdink–Lapidus, zetas de Beurling, primos generalizados y membranas fractales. arXiv:math/0410270
- `376_Zhang_2013_Normalization_Beurling_Generalized_Primes_RH.pdf` — Zhang, normalización de primos generalizados de Beurling con RH. Ann. Univ. Sci. Budapest. Sect. Comp. 39 (2013)

## 17. Paseos aleatorios, excursiones y caminos de Dyck

- `066_Carmona-Petrelis_2017_Limit_Theorems_Random_Walk_Excursion.pdf` — excursión de paseo aleatorio condicionada a encerrar un área: teoremas límite. arXiv:1709.06448
- `074_Chatterjee2007_2007_Stein_s_method_for_concentration_inequalities.pdf` — Chatterjee, método de Stein para desigualdades de concentración. PTRF 138 (2007), DOI 10.1007/s00440-006-0029-y
- `104_Denisov-Kolb-Wachtel_2015_Local_Asymptotics_Random_Walk_Excursions.pdf` — asintótica local del área de las excursiones de paseos aleatorios (Oberwolfach Preprint 2013-19)
- `105_DerridaEnaudLebowitz2004_2004_The_asymmetric_exclusion_process_and_Brownian_excursions.pdf` — proceso de exclusión asimétrico y excursiones brownianas. arXiv:cond-mat/0306078
- `110_DurrettIglehartMiller1977_1977_Weak_convergence_to_Brownian_meander_and_Brownian_excursion.pdf` — convergencia débil al meandro y a la excursión brownianos. Ann. Probab. (1977)
- `148_GordinPeligrad2011_2011_On_the_functional_central_limit_theorem_via_martingale_approximation.pdf` — teorema central del límite funcional vía aproximación por martingalas. Bernoulli 17 (2011). arXiv:0910.3448
- `149_Gouezel2010_2010_Almost_sure_invariance_principle_for_dynamical_systems_by_spectral_methods.pdf` — principio de invariancia casi segura por métodos espectrales. Ann. Probab. 38 (2010), DOI 10.1214/10-AOP525
- `169_HaugPrellberg2015_2015_Uniform_asymptotics_of_area_weighted_Dyck_paths.pdf` — asintótica uniforme de caminos de Dyck ponderados por área. arXiv:1412.5108
- `202_Janson_2007_Brownian_Excursion_Area_Wright_Constants.pdf` — Janson, área de la excursión browniana y constantes de Wright. Probab. Surveys 4 (2007), DOI 10.1214/07-PS104
- `214_Kaigh1976_1976_An_invariance_principle_for_random_walk_conditioned_by_a_late_return_to_zero.pdf` — principio de invariancia para paseos condicionados a un retorno tardío a cero. Ann. Probab. (1976)
- `223_KhorunzhiyMarckert2009_2009_Uniform_bounds_for_exponential_moment_of_maximum_of_a_Dyck_path.pdf` — cotas uniformes del momento exponencial del máximo de un camino de Dyck. arXiv:0902.1229
- `237_Kousha2012_2012_Asymptotic_behavior_and_the_moderate_deviation_principle_for_the_maximum_of_a_Dyck_path.pdf` — comportamiento asintótico y desviaciones moderadas del máximo de un camino de Dyck. arXiv:1008.0606
- `304_OwczarekPrellberg2014_2014_Pressure_exerted_by_a_vesicle_on_a_surface.pdf` — presión de una vesícula sobre una superficie (caminos de Dyck). arXiv:1311.2174
- `309_PeligradUtev2005_2005_A_new_maximal_inequality_and_invariance_principle_for_stationary_sequences.pdf` — desigualdad maximal y principio de invariancia para sucesiones estacionarias. Ann. Probab. 33 (2005). arXiv:math/0406606
- `325_Richard_2005_Q_Functional_Equations_Excursion_Moments.pdf` — ecuaciones q-funcionales y momentos de excursiones. arXiv:math/0503198

## 18. Cuasicristales, bases de Riesz e interpolación de Fourier

- `014_Avdonin_1977_Riesz_Bases_Exponential_Functions_L2_Brief.pdf` — Avdonin, bases de Riesz de exponenciales en L² (nota breve, 1977)
- `048_Bondarenko-Radchenko-Seip_2023_Fourier_Interpolation_Zeros_Zeta_L_Functions.pdf` — Bondarenko–Radchenko–Seip, interpolación de Fourier con ceros de ζ y L-funciones. arXiv:2005.02996
- `081_Cohn-Elkies_2003_New_Upper_Bounds_Sphere_Packings_I.pdf` — Cohn–Elkies, cotas de programación lineal para empaquetamiento de esferas. Ann. of Math. 157 (2003). arXiv:math/0110009
- `113_Engert1970_1970_Finite_dimensional_translation_invariant_subspaces.pdf` — subespacios invariantes por traslación de dimensión finita. Pacific J. Math. 32 (1970)
- `187_Hruscev-Nikolskii-Pavlov_1981_Unconditional_Bases_Exponentials_Reproducing_Kernels.pdf` — Hruščev–Nikolskii–Pavlov, bases incondicionales de exponenciales y núcleos reproductores (1981)
- `195_Ingham_1936_Trigonometrical_Inequalities_Theory_Series.pdf` — Ingham, desigualdades trigonométricas en la teoría de series (1936)
- `241_Kozma-Lev_2011_Exponential_Riesz_Bases_Discrepancy_BMO.pdf` — Kozma–Lev, bases de Riesz de exponenciales, discrepancia de rotaciones irracionales y BMO. arXiv:1009.2188
- `242_Kurasov-Sarnak_2020_Stable_Polynomials_Crystalline_Measures.pdf` — Kurasov–Sarnak, polinomios estables y medidas cristalinas. arXiv:2004.05678
- `254_Lev-Olevskii_2015_Quasicrystals_Poisson_Summation_Formula.pdf` — Lev–Olevskii, cuasicristales y fórmula de sumación de Poisson. arXiv:1312.6884
- `255_Lev_2012_Riesz_Bases_Exponentials_Multiband_Spectra_Preprint.pdf` — Lev, bases de Riesz de exponenciales sobre espectros multibanda. arXiv:1101.3894
- `301_Olevskii-Ulanovskii_2020_Fourier_Quasicrystals_Unit_Masses.pdf` — Olevskii–Ulanovskii, cuasicristales de Fourier con masas unidad. C. R. Math. 358 (2020), DOI 10.5802/crmath.142
- `352_Szekelyhidi1982_1982_Note_on_exponential_polynomials.pdf` — Székelyhidi, nota sobre polinomios exponenciales. Pacific J. Math. 103 (1982)
- `374_Young_1974_Inequalities_Perturbation_Theorem_Paley_Wiener.pdf` — Young, desigualdades para el teorema de perturbación de Paley–Wiener. Proc. AMS 43 (1974)

## 19. Positividad total y funciones absolutamente monótonas

- `030_Belton2022_2022_Mathematics_Research_Reports.pdf` — preservadores de núcleos totalmente positivos y funciones de frecuencia de Pólya. Math. Res. Rep. 3 (2022), DOI 10.5802/mrr.12
- `035_Bernstein_1929_Fonctions_Absolument_Monotones.pdf` — Bernstein, funciones absolutamente monótonas. Acta Math. (1929)
- `049_BorceaBranden2009_2009_Annals_of_Mathematics.pdf` — Borcea–Brändén, teoremas maestros de Pólya–Schur. Ann. of Math. 170 (2009)
- `063_Burbea1974_1974_Pacific_Journal_of_Mathematics.pdf` — Burbea, positividad total y núcleos reproductores. Pacific J. Math. 55 (1974)
- `064_Burbea1976_1976_Pacific_Journal_of_Mathematics.pdf` — Burbea, positividad total de ciertos núcleos reproductores. Pacific J. Math. 67 (1976)

## 20. Otros temas (fuera del núcleo aritmético)

- `002_AkianGaubertNiv2018_2018_Tropical_compound_matrix_identities.pdf` — identidades de matrices compuestas tropicales. arXiv:1702.00980
- `031_Benedetto-Powell-Yilmaz_2006_Sigma_Delta_Quantization_Finite_Frames.pdf` — cuantización Sigma-Delta y marcos finitos
- `033_Benvenuti2019_2019_The_inverse_eigenvalue_problem_for_Leslie_matrices.pdf` — problema inverso de autovalores para matrices de Leslie. Electron. J. Linear Algebra 35 (2019)
- `047_Bonami1970_1970_Etude_des_coefficients_de_Fourier_des_fonctions_de_L_p_G.pdf` — Bonami, coeficientes de Fourier de funciones de L^p(G). Ann. Inst. Fourier 20 (1970)
- `069_CarrascoFlorens2000_2000_Econometric_Theory.pdf` — Carrasco–Florens, GMM con un continuo de condiciones de momentos (econometría)
- `098_Daubechies-DeVore_2003_Bandlimited_Function_Stable_Sigma_Delta_Modulators.pdf` — Daubechies–DeVore, moduladores Sigma-Delta estables de orden arbitrario. Ann. of Math. 158 (2003)
- `103_DellAnnaEtAl2016_2016_Violation_of_cluster_decomposition_and_absence_of_light_cones_in_local_integer_and_half_integer_spin_chains.pdf` — violación de la descomposición en clústeres en cadenas de espines. arXiv:1604.08281
- `111_DuttEtAl2019_2019_Nature_Communications.pdf` — espectroscopía de bandas en una dimensión sintética (fotónica). Nat. Commun. (2019), DOI 10.1038/s41467-019-11117-9
- `137_Gallier2016_2016_Spectral_theory_of_unsigned_and_signed_graphs_applications_to_graph_clustering_a_survey.pdf` — Gallier, teoría espectral de grafos con y sin signo; clustering. arXiv:1601.04692
- `158_Gunturk-Thao_2003_Ergodic_Dynamics_Sigma_Delta_Quantization.pdf` — dinámica ergódica en la cuantización Sigma-Delta. arXiv:math/0308223
- `264_LyubarskiiVershynin2010_2010_Uncertainty_principles_and_vector_quantization.pdf` — Lyubarskii–Vershynin, principios de incertidumbre y cuantización vectorial. arXiv:math/0611343
- `299_OganesyanHuse2007_2007_Localization_of_interacting_fermions_at_high_temperature.pdf` — Oganesyan–Huse, localización de fermiones interactuantes a alta temperatura. arXiv:cond-mat/0610854
- `327_RigalZadunaisky2015_2015_Twisted_semigroup_algebras.pdf` — álgebras de semigrupo torcidas. arXiv:1406.2985

## 21. Bibliografía de Alpöge — «Dirichlet L-functions and the Critical Line»

Referencias de las pp. 54–55 de *Dirichlet L-functions and the Critical Line* (lista de 29 fuentes), incorporadas el 2026-11-22 desde `Bibliografia_Alpoge_20261122_sin_Howe_Davenport.zip`. Los datos bibliográficos (revista, años, DOI) proceden de esa lista y de la portada de cada PDF; no se ha verificado el contenido matemático. Temas: cohomología prismática, representaciones de Galois, teoría theta (Howe–Rallis), Iwasawa y K-teoría, volúmenes aritméticos, más Landau 1905 y Huxley 1976 para ventanas unilaterales y densidad de ceros (relacionados con §8 y §10).

### 21.1 Libros y monografías

- `026_Bellaiche-Chenevier_2009_Families_Galois_Representations_Selmer_Groups.pdf` — J. Bellaïche y G. Chenevier, *Families of Galois representations and Selmer groups*, Astérisque 324 (2009), 326 pp. (monografía). numdam AST_2009__324__R1_0. Papel en la bibliografía: COHOMOLOGÍA.
- `180_Hida_2004_pAdic_Automorphic_Forms_Shimura_Varieties.pdf` — H. Hida, *p-Adic automorphic forms on Shimura varieties*, Springer Monographs in Mathematics, Springer, 2004 (libro completo, 397 pp. PDF). doi:10.1007/978-1-4684-9390-0. Papel en la bibliografía: AUTOMORFAS / SHIMURA.

### 21.2 Artículos

- `007_Anschutz-LeBras_2023_Prismatic_Dieudonne_Theory_arXiv_v4.pdf` — J. Anschütz y A.-C. Le Bras, *Prismatic Dieudonné theory*, Forum Math. Pi 11 (2023), e2, 1–92. arXiv:1907.10525v4; doi:10.1017/fmp.2022.22. Papel en la bibliografía: COHOMOLOGÍA LOCAL.
- `038_Bhatt-Scholze_2022_Prisms_Prismatic_Cohomology.pdf` — B. Bhatt y P. Scholze, *Prisms and prismatic cohomology*, Ann. of Math. (2) 196 (2022), 1135–1275. doi:10.4007/annals.2022.196.3.5. Papel en la bibliografía: COHOMOLOGÍA LOCAL.
- `052_Bost_1996_Periodes_Isogenies_Varietes_Abeliennes.pdf` — J.-B. Bost, *Périodes et isogénies des variétés abéliennes sur les corps de nombres (d’après Masser et Wüstholz)*, Séminaire Bourbaki exp. 795, Astérisque 237 (1996), 115–161. numdam SB_1994-1995__37__115_0. Papel en la bibliografía: PENDIENTES / PERÍODOS.
- `075_Chenevier-Harris_2013_Construction_Automorphic_Galois_Representations_II.pdf` — G. Chenevier y M. Harris, *Construction of automorphic Galois representations, II*, Cambridge J. Math. 1 (2013), 53–73. doi:10.4310/CJM.2013.v1.n1.a2. Papel en la bibliografía: CONGRUENCIAS AUTOMORFAS.
- `078_Coates-Sinnott_1974_Analogue_Stickelberger_Theorem_Higher_K_Groups.pdf` — J. Coates y W. Sinnott, *An analogue of Stickelberger’s theorem for the higher K-groups*, Invent. Math. 24 (1974), 149–161. doi:10.1007/BF01404303. Papel en la bibliografía: COHOMOLOGÍA / K-TEORÍA.
- `102_Deligne-Lusztig_1976_Representations_Reductive_Groups_Finite_Fields.pdf` — P. Deligne y G. Lusztig, *Representations of reductive groups over finite fields*, Ann. of Math. (2) 103 (1976), 103–161. doi:10.2307/1971021. Papel en la bibliografía: REPRESENTACIONES.
- `117_Ferrero-Washington_1979_Iwasawa_Invariant_Mu_p_Vanishes_Abelian_Number_Fields.pdf` — B. Ferrero y L. C. Washington, *The Iwasawa invariant μ_p vanishes for abelian number fields*, Ann. of Math. (2) 109 (1979), 377–395. JSTOR 1971116. Papel en la bibliografía: IWASAWA.
- `138_Gan-Qiu-Takeda_2014_Regularized_Siegel_Weil_Formula_Rallis_Inner_Product_arXiv_v3.pdf` — W. T. Gan, Y. Qiu y S. Takeda, *The regularized Siegel–Weil formula (the second term identity) and the Rallis inner product formula*, Invent. Math. 198 (2014), 739–831. arXiv:1207.4709v3; doi:10.1007/s00222-014-0509-0. Papel en la bibliografía: THETA / RALLIS.
- `139_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf` — W. T. Gan y S. Takeda, *A proof of the Howe duality conjecture*, J. Amer. Math. Soc. 29 (2016), 473–493. arXiv:1407.1995v4; doi:10.1090/jams/839. **Alternativa a Howe 1979** (el original de Howe no está en el zip porque ya lo tienes): cita a Howe, «θ-series and invariant theory», como [H1], y su Teorema 1.2 demuestra la dualidad local para pares simpléctico-ortogonales o unitarios sobre cuerpos locales no arquimedianos. No sustituye el contenido de teoría de invariantes de Howe ni resultados globales (cadenas de levantamientos theta, Rallis, períodos).. Papel en la bibliografía: CORRESPONDENCIA THETA.
- `154_Grayson_1984_Reduction_Theory_Using_Semistability.pdf` — D. R. Grayson, *Reduction theory using semistability*, Comment. Math. Helv. 59 (1984), 600–634. doi:10.1007/BF02566369. Papel en la bibliografía: PENDIENTES ARAKELOV.
- `192_Huxley_1976_Imperfect_Hybrid_Zero_Density_Theorem.pdf` — M. N. Huxley, *An imperfect hybrid zero-density theorem*, J. London Math. Soc. (2) 13 (1976), 53–56. doi:10.1112/jlms/s2-13.1.53. Papel en la bibliografía: CEROS / PRIMOS AUXILIARES.
- `220_Kato_2004_pAdic_Hodge_Theory_Values_Zeta_Functions_Modular_Forms.pdf` — K. Kato, *p-adic Hodge theory and values of zeta functions of modular forms*, Astérisque 295 (2004), 117–290. numdam AST_2004__295__117_0. Papel en la bibliografía: COHOMOLOGÍA / IWASAWA.
- `227_Kolyvagin_1990_Euler_Systems.pdf` — V. A. Kolyvagin, *Euler systems*, The Grothendieck Festschrift II, Birkhäuser (1990), 435–483. Papel en la bibliografía: COHOMOLOGÍA / EULER SYSTEMS.
- `246_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf` — E. Landau, *Über einen Satz von Tschebyschef*, Math. Ann. 61 (1905), 527–550. Göttinger Digitalisierungszentrum PPN235181684_0061. **Sin capa de texto** (escaneo). Papel en la bibliografía: VENTANAS UNILATERALES.
- `262_Lubin-Tate_1965_Formal_Complex_Multiplication_Local_Fields.pdf` — J. Lubin y J. Tate, *Formal complex multiplication in local fields*, Ann. of Math. (2) 81 (1965), 380–387. doi:10.2307/1970622. Papel en la bibliografía: DIVISIBILIDAD LOCAL.
- `281_Moriwaki_2009_Continuity_Volumes_Arithmetic_Varieties_arXiv_v2.pdf` — A. Moriwaki, *Continuity of volumes on arithmetic varieties*, J. Algebraic Geom. 18 (2009), 407–457. arXiv:math/0612269v2; doi:10.1090/S1056-3911-08-00500-6. Papel en la bibliografía: VOLUMEN ARITMÉTICO.
- `300_Ohsawa-Takegoshi_1987_Extension_L2_Holomorphic_Functions.pdf` — T. Ohsawa y K. Takegoshi, *On the extension of L² holomorphic functions*, Math. Z. 195 (1987), 197–204. doi:10.1007/BF01166457. Papel en la bibliografía: INTERPOLACIÓN L².
- `321_Rallis_1984_Injectivity_Properties_Liftings_Weil_Representations.pdf` — S. Rallis, *Injectivity properties of liftings associated to Weil representations*, Compositio Math. 52 (1984), 139–169. numdam CM_1984__52_2_139_0. Papel en la bibliografía: TORRES THETA.
- `324_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf` — K. A. Ribet, *A modular construction of unramified p-extensions of Q(μ_p)*, Invent. Math. 34 (1976), 151–162. doi:10.1007/BF01403065. **Sin capa de texto** (escaneo). Papel en la bibliografía: IWASAWA / GALOIS.
- `341_Selberg-Chowla_1967_On_Epstein_Zeta_Function.pdf` — A. Selberg y S. Chowla, *On Epstein’s zeta-function*, J. reine angew. Math. 227 (1967), 86–110. doi:10.1515/crll.1967.227.86. Papel en la bibliografía: PERÍODOS CM.
- `346_Sorensen_2020_A_Patching_Lemma.pdf` — C. M. Sorensen, *A patching lemma*, en *Shimura Varieties*, Cambridge Univ. Press (2020), 297–305. doi:10.1017/9781108649711.012. Las dos copias de Descargas eran idénticas (SHA-256 c4f6061e…cb4fd); entra una. Papel en la bibliografía: PATCHING.
- `347_Soule_2003_Bound_Torsion_K_Theory_Algebraic_Integers.pdf` — C. Soulé, *A bound for the torsion in the K-theory of algebraic integers*, Doc. Math., Extra Vol. Kato (2003), 761–788. doi:10.4171/DMS/3/21. Papel en la bibliografía: COHOMOLOGÍA / K-TEORÍA.
- `357_Taylor-Wiles_1995_Ring_Theoretic_Properties_Certain_Hecke_Algebras.pdf` — R. Taylor y A. Wiles, *Ring-theoretic properties of certain Hecke algebras*, Ann. of Math. (2) 141 (1995), 553–572. doi:10.2307/2118560. Papel en la bibliografía: CONGRUENCIAS / HECKE.

### 21.3 Anuncio

- `003_Alpoge_2026_Announcement_Remark_Riemann_Hypothesis_Proof.pdf` — L. Alpöge, anuncio y nota sobre la prueba de RH con Claude (4 pp., sin DOI): suplemento a la referencia [28] de la bibliografía; remite a `alpo.ge/lean.tar.gz.part01…part14`. Papel en la bibliografía: VERIFICACIÓN FORMAL.

## Incorporación del 22 de noviembre de 2026 (segunda)

Origen: `~/Downloads` (copias; los originales se conservan allí). Se renumeró la carpeta entera en orden alfabético ASCII (244 PDF cambian de número; ninguno cambia de contenido). Hashes en `INCORPORACIONES_2026-11-22.json` (`second_incorporation`).

| Número | Documento | Páginas PDF | Tipo |
|---|---|---:|---|
| 136 | `136_Gallagher_1970_Large_Sieve_Density_Estimate_Near_Sigma_1.pdf` | 11 | art |
| 284 | `284_Motohashi_1977_On_Gallaghers_Prime_Number_Theorem.pdf` | 3 | art |
| 285 | `285_Motohashi_1978_Primes_in_Arithmetic_Progressions.pdf` | 16 | art |

## Incorporación del 22 de noviembre de 2026

Origen: `~/Downloads/Bibliografia_Alpoge_20261122_sin_Howe_Davenport.zip` (524 MB), dividido en: (a) 25 PDF de contenido (2 libros: Hida y Bellaïche–Chenevier; 23 artículos, incluido el sustituto de Howe de Gan–Takeda) y 1 suplemento (anuncio de Alpöge), que entran en la biblioteca; (b) fuera de la carpeta plana, en Descargas: tu lista de 29 referencias (`00_Bibliografia_original_29_referencias.*`), el ZIP del código Lean (397 MB, supera el límite de 100 MB de GitHub), la página de verificación de Sutherland, `MANIFIESTO.csv`, `LEEME.txt` y `SHA256SUMS.txt`. Los SHA-256 de los 26 PDF coinciden con `SHA256SUMS.txt` del zip.

Se renombraron según `Autor_Año_Título` y se **renumeró la carpeta entera** en orden alfabético ASCII del nombre sin número (los 16 PDF añadidos el 2026-11-01 estaban al final, fuera de orden). Equivalencias antiguo → nuevo en `RENUMERACION_2026-11-22.md`; nombres originales, hashes y fuentes en `INCORPORACIONES_2026-11-22.json`.

| Número | Documento | Páginas PDF | Tipo |
|---|---|---:|---|
| 003 | `003_Alpoge_2026_Announcement_Remark_Riemann_Hypothesis_Proof.pdf` | 4 | anuncio |
| 007 | `007_Anschutz-LeBras_2023_Prismatic_Dieudonne_Theory_arXiv_v4.pdf` | 97 | art |
| 026 | `026_Bellaiche-Chenevier_2009_Families_Galois_Representations_Selmer_Groups.pdf` | 327 | libro |
| 038 | `038_Bhatt-Scholze_2022_Prisms_Prismatic_Cohomology.pdf` | 125 | art |
| 052 | `052_Bost_1996_Periodes_Isogenies_Varietes_Abeliennes.pdf` | 48 | art |
| 075 | `075_Chenevier-Harris_2013_Construction_Automorphic_Galois_Representations_II.pdf` | 15 | art |
| 078 | `078_Coates-Sinnott_1974_Analogue_Stickelberger_Theorem_Higher_K_Groups.pdf` | 13 | art |
| 102 | `102_Deligne-Lusztig_1976_Representations_Reductive_Groups_Finite_Fields.pdf` | 60 | art |
| 117 | `117_Ferrero-Washington_1979_Iwasawa_Invariant_Mu_p_Vanishes_Abelian_Number_Fields.pdf` | 20 | art |
| 138 | `138_Gan-Qiu-Takeda_2014_Regularized_Siegel_Weil_Formula_Rallis_Inner_Product_arXiv_v3.pdf` | 59 | art |
| 139 | `139_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf` | 21 | art |
| 154 | `154_Grayson_1984_Reduction_Theory_Using_Semistability.pdf` | 36 | art |
| 180 | `180_Hida_2004_pAdic_Automorphic_Forms_Shimura_Varieties.pdf` | 397 | libro |
| 192 | `192_Huxley_1976_Imperfect_Hybrid_Zero_Density_Theorem.pdf` | 4 | art |
| 220 | `220_Kato_2004_pAdic_Hodge_Theory_Values_Zeta_Functions_Modular_Forms.pdf` | 175 | art |
| 227 | `227_Kolyvagin_1990_Euler_Systems.pdf` | 49 | art |
| 246 | `246_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf` | 25 | art |
| 262 | `262_Lubin-Tate_1965_Formal_Complex_Multiplication_Local_Fields.pdf` | 9 | art |
| 281 | `281_Moriwaki_2009_Continuity_Volumes_Arithmetic_Varieties_arXiv_v2.pdf` | 43 | art |
| 300 | `300_Ohsawa-Takegoshi_1987_Extension_L2_Holomorphic_Functions.pdf` | 8 | art |
| 321 | `321_Rallis_1984_Injectivity_Properties_Liftings_Weil_Representations.pdf` | 32 | art |
| 324 | `324_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf` | 13 | art |
| 341 | `341_Selberg-Chowla_1967_On_Epstein_Zeta_Function.pdf` | 25 | art |
| 346 | `346_Sorensen_2020_A_Patching_Lemma.pdf` | 9 | art |
| 347 | `347_Soule_2003_Bound_Torsion_K_Theory_Algebraic_Integers.pdf` | 28 | art |
| 357 | `357_Taylor-Wiles_1995_Ring_Theoretic_Properties_Certain_Hecke_Algebras.pdf` | 22 | art |

## Incorporación del 1 de noviembre de 2026

(Numeración vigente tras la renumeración del 2026-11-22; en el momento de la incorporación se añadieron como 338–353 sin renumerar el fondo anterior.) Comprobación de apertura y páginas con pypdf, interpretación de todas las páginas con MuPDF y SHA-256 de cada incorporación; esto no constituye validación de las afirmaciones matemáticas de los documentos.

- Davenport es la segunda edición de 1980, no la tercera de 2000.
- Se conservan Amberger v1 y v5 como versiones distintas.
- Hiary–Leong–Yang v3 se añade sin sustituir la v2 ya existente (nº 178 tras la renumeración).
- El PDF parcial de Olver contiene solo portada e índice (8 páginas); el libro completo está en el nº 303. MuPDF advierte de longitudes de flujos incorrectas, pero termina con código 0; se preservan los bytes originales.
- El archivo descargado con título Einstein–Grossmann está vacío y no es la tesis de Grossmann. No se incorpora y permanece en Descargas.
- El PDF de Davenport produce avisos de glifos de la capa OCR (`HiddenHorzOCR`) en MuPDF; termina con código 0. Se conserva sin alterar.

| Número | Documento | Páginas PDF | Observación |
|---|---|---:|---|
| 004 | `004_Amberger_2025_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v1.pdf` | 18 | Versión histórica v1; se conserva también v5. |
| 005 | `005_Amberger_2026_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v5.pdf` | 26 | Versión v5; no sustituye v1. |
| 028 | `028_Bellotti-Wong_2026_Counting_Zeros_Artin_L_Functions_arXiv_v1.pdf` | 24 | La otra copia descargada tiene idéntico SHA-256. |
| 100 | `100_Davenport_1980_Multiplicative_Number_Theory_Second_Edition.pdf` | 188 | Segunda edición de 1980, revisada por H. L. Montgomery; no es la tercera edición de 2000. |
| 171 | `171_HeathBrown_2016_New_kth_Derivative_Estimate_Exponential_Sums_Vinogradov_arXiv_v3.pdf` | 17 | Preprint v3 de 2016, correspondiente al trabajo publicado en 2017. |
| 177 | `177_Hiary-Leong-Yang_2024_Explicit_Bounds_Zeta_1_Line_arXiv_v3.pdf` | 31 | Versión v3; se mantiene intacta la v2 existente en el nº 178. |
| 302 | `302_Olver_1974_Introduction_Asymptotics_Special_Functions.pdf` | 324 | Libro independiente de 1974, formado por los siete primeros capítulos de Asymptotics and Special Functions; ISBN 0-12-525856-9. |
| 303 | `303_Olver_1997_Asymptotics_Special_Functions_AK_Peters_Reprint.pdf` | 591 | Reimpresión A K Peters de 1997 de la obra de 1974; portada y datos editoriales verificados en el PDF local. |
| 314 | `314_Platt-Trudgian_2014_Improved_Explicit_Bound_Zeta_Critical_Line_arXiv_v2.pdf` | 9 | Preprint v2 de 2014, publicado en J. Number Theory 147 (2015) 842–851. |
| 315 | `315_Platt-Trudgian_2015_Zeroes_Partial_Sums_Zeta_Function_arXiv_v2.pdf` | 5 | Trabajo diferente de An improved explicit bound; no es una copia de ese artículo. |
| 332 | `332_Rosser_1941_Explicit_Bounds_Functions_Prime_Numbers.pdf` | 23 | Incluye portada JSTOR y artículo de pp. 211–232. |
| 334 | `334_Rudin_1987_Real_Complex_Analysis_Third_Edition.pdf` | 430 | Tercera edición internacional de 1987, McGraw-Hill; ISBN 0-07-054234-1. |
| 355 | `355_Tao-Trudgian-Yang_2025_New_Exponent_Pairs_Zero_Density_Additive_Energy_arXiv_v1.pdf` | 44 | Preprint v1. |
| 361 | `361_Titchmarsh_1939_Theory_Functions_Second_Edition.pdf` | 452 | Segunda edición de 1939; el escaneo corresponde a una reimpresión posterior. |
| 362 | `362_Trudgian-Yang_2024_Toward_Optimal_Exponent_Pairs_arXiv_v3.pdf` | 38 | Preprint v3. |
| 366 | `366_Turing_1953_Some_Calculations_Riemann_Zeta_Function.pdf` | 19 | Artículo de pp. 99–117. |

### Documento parcial conservado

- `DOCUMENTOS_PARCIALES/Olver_1997_Asymptotics_Special_Functions_SOLO_Portada_Indice_8pp.pdf` — 8 páginas; solo portada e índice.

Los nombres originales, hashes, duplicados y decisiones del 2026-11-01 estaban en `INCORPORACIONES_2026-11-01.json`, retirado el 2026-11-22; se recuperan del commit `4a661ae` del repositorio.

## Catálogo canónico de archivos (382 PDF principales)

- `001_AbercrombieBanksShparlinski2009_2009_Arithmetic_functions_on_Beatty_sequences.pdf`
- `002_AkianGaubertNiv2018_2018_Tropical_compound_matrix_identities.pdf`
- `003_Alpoge_2026_Announcement_Remark_Riemann_Hypothesis_Proof.pdf`
- `004_Amberger_2025_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v1.pdf`
- `005_Amberger_2026_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v5.pdf`
- `006_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf`
- `007_Anschutz-LeBras_2023_Prismatic_Dieudonne_Theory_arXiv_v4.pdf`
- `008_Arguin-Bourgade-Radziwill_2020_Fyodorov_Hiary_Keating_Conjecture_I.pdf`
- `009_Arguin-Bourgade-Radziwill_2023_Fyodorov_Hiary_Keating_Conjecture_II.pdf`
- `010_AriasdeReyna_2024_Explicit_Formula_Quasicrystal_Definition.pdf`
- `011_Aryan_2019_Extension_Landau_Gonek_Formula.pdf`
- `012_Aryan_2022_Extension_Landau_Gonek_Formula_Published.pdf`
- `013_Avdonin-Ivanov_2001_Exponential_Riesz_Bases_Subspaces_Divided_Differences.pdf`
- `014_Avdonin_1977_Riesz_Bases_Exponential_Functions_L2_Brief.pdf`
- `015_Aymone-Sidoravicius_2017_Partial_Sums_Biased_Random_Multiplicative_Functions.pdf`
- `016_Aymone2020_2020_A_note_on_multiplicative_functions_resembling_the_M_bius_function.pdf`
- `017_Backlund_1916_Nullstellen_Riemannschen_Zetafunktion.pdf`
- `018_BaezDuarte-Balazard-Landreau-Saias_2000_Notes_sur_la_fonction_zeta_de_Riemann_3.pdf`
- `019_BaezDuarte2002_2002_BaezDuarte2002.pdf`
- `020_Balanzario-SanchezOrtiz_2007_Zeros_Davenport_Heilbronn_Counterexample.pdf`
- `021_Balazard-Saias-Yor_1999_Notes_Fonction_Zeta_Riemann_2_Transcription_VellaChemla.pdf`
- `022_Balog_1987_Integers_Without_Large_Prime_Factors.pdf`
- `023_Baluyot-Goldston-etal_2025_Pair_Correlation_Zeros_I_Proportions_Simple_Critical.pdf`
- `024_Baricz-Laforgia-Pogany_2015_Van_Der_Corput_Inequalities_Bessel.pdf`
- `025_Barrett-Jarvis_1992_Spectral_Properties_Redheffer_Matrix.pdf`
- `026_Bellaiche-Chenevier_2009_Families_Galois_Representations_Selmer_Groups.pdf`
- `027_Bellotti-Wong_2025_Improved_Argument_Zero_Counting_Zeta.pdf`
- `028_Bellotti-Wong_2026_Counting_Zeros_Artin_L_Functions_arXiv_v1.pdf`
- `029_Bellotti_2024_Explicit_Bounds_Zeta_New_Zero_Free_Region.pdf`
- `030_Belton2022_2022_Mathematics_Research_Reports.pdf`
- `031_Benedetto-Powell-Yilmaz_2006_Sigma_Delta_Quantization_Finite_Frames.pdf`
- `032_Bennett-Martin-OBryant-Rechnitzer_2021_Counting_Zeros_Dirichlet_L_Functions.pdf`
- `033_Benvenuti2019_2019_The_inverse_eigenvalue_problem_for_Leslie_matrices.pdf`
- `034_BergelsonKulagaPrzymusLemanczykRichter2019_2019_Discrete_Contin_Dyn_Syst.pdf`
- `035_Bernstein_1929_Fonctions_Absolument_Monotones.pdf`
- `036_Berry_1988_Semiclassical_Formula_Number_Variance_Riemann_Zeros.pdf`
- `037_Beurling_1937_Distribution_Nombres_Premiers_Generalises_I.pdf`
- `038_Bhatt-Scholze_2022_Prisms_Prismatic_Cohomology.pdf`
- `039_Bjorner_2011_Cell_Complex_Number_Theory.pdf`
- `040_Bloch_2000_Higher_Regulators_K_Theory_Zeta_Elliptic_Curves.pdf`
- `041_Bogomolny-Keating_1995_Random_Matrix_Theory_Riemann_Zeros_I_Three_Four_Point_Correlations.pdf`
- `042_Bogomolny-Keating_1996_Gutzwiller_Trace_Formula_Spectral_Statistics_Beyond_Diagonal.pdf`
- `043_Bogomolny-Keating_1996_Random_Matrix_Theory_Riemann_Zeros_II_n_Point_Correlations.pdf`
- `044_Bohigas-Leboeuf-Sanchez_2001_Spectral_Spacing_Correlations.pdf`
- `045_Bohr_1926_Fastperiodische_Funktionen_III_Dirichletentwicklung.pdf`
- `046_Bombieri_2010_Classical_Theory_Zeta_And_L_Functions.pdf`
- `047_Bonami1970_1970_Etude_des_coefficients_de_Fourier_des_fonctions_de_L_p_G.pdf`
- `048_Bondarenko-Radchenko-Seip_2023_Fourier_Interpolation_Zeros_Zeta_L_Functions.pdf`
- `049_BorceaBranden2009_2009_Annals_of_Mathematics.pdf`
- `050_Bornemann-Forrester-Mays_2017_Finite_Size_Effects_Spacing_Distributions.pdf`
- `051_Borwein-Straub-Wan-Zudilin_2012_Densities_Short_Uniform_Random_Walks.pdf`
- `052_Bost_1996_Periodes_Isogenies_Varietes_Abeliennes.pdf`
- `053_Bourgain_2017_Decoupling_Exponential_Sums_Riemann_Zeta.pdf`
- `054_Bourgain_undated_On_the_Fourier_Walsh_spectrum_of_the_M_obius_function.pdf`
- `055_Brent-Platt-Trudgian_2020_Sums_Over_Zeros_Riemann_Zeta.pdf`
- `056_Brent2018_2019_On_asymptotic_approximations_to_the_log_Gamma_and_Riemann_Siegel_theta_functions.pdf`
- `057_Brent_1979_Zeros_Riemann_Zeta_Critical_Strip.pdf`
- `058_BretcheDressTenenbaum2020_2020_Mathematika.pdf`
- `059_Brevig-Perfekt-Seip-Siskakis-Vukotic_2016_Multiplicative_Hilbert_Matrix.pdf`
- `060_Broucke-Debruyne-Revesz_2025_Well_Behaved_Beurling_Number_Systems.pdf`
- `061_Broucke-Debruyne-Vindas_2020_Beurling_Integers_RH_Large_Oscillation.pdf`
- `062_Broucke-Vindas_2024_Generalized_Prime_Random_Approximation.pdf`
- `063_Burbea1974_1974_Pacific_Journal_of_Mathematics.pdf`
- `064_Burbea1976_1976_Pacific_Journal_of_Mathematics.pdf`
- `065_Buthe2014_2015_A_method_for_proving_the_completeness_of_a_list_of_zeros_of_certain_functions.pdf`
- `066_Carmona-Petrelis_2017_Limit_Theorems_Random_Walk_Excursion.pdf`
- `067_Carneiro-Chandee-Littmann-Milinovich_2014_Hilbert_Spaces_Pair_Correlation.pdf`
- `068_Carneiro-Milinovich-Ramos_2023_Fourier_Optimization_Montgomery_Pair_Correlation.pdf`
- `069_CarrascoFlorens2000_2000_Econometric_Theory.pdf`
- `070_Cartier-Julia-Moussa-Vanhove_2006_Random_Matrices_Zeta_Dynamical_Systems.pdf`
- `071_Cassaigne-Ferenczi-Mauduit-Rivat-Sarkozy_1999_Liouville_Pseudorandom_Sequences.pdf`
- `072_Chan_2002_More_Precise_Pair_Correlation_Zeros_Primes_Short_Intervals.pdf`
- `073_Chandrasekharan-Mandelbrojt_1959_Solutions_Riemann_Functional_Equation.pdf`
- `074_Chatterjee2007_2007_Stein_s_method_for_concentration_inequalities.pdf`
- `075_Chenevier-Harris_2013_Construction_Automorphic_Galois_Representations_II.pdf`
- `076_Christ_2014_Value_Distribution_Zeta_Near_Critical_Line_Thesis.pdf`
- `077_Claude_2026_More_Than_Two_Thirds_Zeros_Zeta_Critical_Line.pdf`
- `078_Coates-Sinnott_1974_Analogue_Stickelberger_Theorem_Higher_K_Groups.pdf`
- `079_Coffey_2005_Polygamma_Theory_Li_Keiper_Constants_Riemann_Hypothesis.pdf`
- `080_Coffey_2009_Certain_Sums_Over_Nontrivial_Zeta_Zeros.pdf`
- `081_Cohn-Elkies_2003_New_Upper_Bounds_Sphere_Packings_I.pdf`
- `082_Connes1998_1998_Connes1998.pdf`
- `083_Connes2026_2026_Connes2026.pdf`
- `084_Conrad_2005_Partial_Euler_Products_Critical_Line.pdf`
- `085_Conrey-Keating_2016_Pair_Correlation_Twin_Primes_Revisited.pdf`
- `086_Conrey-TurnageButterbaugh_2018_r_Gaps_Between_Zeros_Zeta.pdf`
- `087_ConreySnaith2008_2008_Communications_in_Number_Theory_and_Physics.pdf`
- `088_Conrey_1986_Review_Ivic_Riemann_Zeta_Function.pdf`
- `089_Conrey_1989_More_Than_Two_Fifths_Zeros_Critical_Line.pdf`
- `090_Conrey_2003_Riemann_Hypothesis.pdf`
- `091_Coons2010_2010_On_the_multiplicative_Erd_s_discrepancy_problem.pdf`
- `092_Corless-Gonnet-Hare-Jeffrey-Knuth_1996_Lambert_W_Function.pdf`
- `093_Cramer_1919_Nullstellen_Riemannschen_Zetafunktion.pdf`
- `094_Croot_2003_Oscillations_Multiplicative_PlusMinusOne.pdf`
- `095_Croot_2007_Smooth_Numbers_Short_Intervals.pdf`
- `096_Dannon_2008_Riemann_Zeta_Function.pdf`
- `097_Das-Ismoilov-Ramos_2025_Fourier_Optimization_Pair_Correlation_Problems.pdf`
- `098_Daubechies-DeVore_2003_Bandlimited_Function_Stable_Sigma_Delta_Modulators.pdf`
- `099_Davenport-Heilbronn_1936_Zeros_Certain_Dirichlet_Series_I.pdf`
- `100_Davenport_1980_Multiplicative_Number_Theory_Second_Edition.pdf`
- `101_Debruyne-Vindas_2019_Complex_Tauberian_Theorems_Laplace_Transforms.pdf`
- `102_Deligne-Lusztig_1976_Representations_Reductive_Groups_Finite_Fields.pdf`
- `103_DellAnnaEtAl2016_2016_Violation_of_cluster_decomposition_and_absence_of_light_cones_in_local_integer_and_half_integer_spin_chains.pdf`
- `104_Denisov-Kolb-Wachtel_2015_Local_Asymptotics_Random_Walk_Excursions.pdf`
- `105_DerridaEnaudLebowitz2004_2004_The_asymmetric_exclusion_process_and_Brownian_excursions.pdf`
- `106_Diamond-Montgomery-Vorhauer_2006_Beurling_Primes_Large_Oscillation.pdf`
- `107_Diamond_1970_Asymptotic_Distribution_Beurling_Generalized_Integers.pdf`
- `108_Drmota_2009_Sum_Of_Digits_Of_Primes.pdf`
- `109_Durkan-Hughes-PearceCrump_2026_Generalisations_Landau_Gonek_Theorem.pdf`
- `110_DurrettIglehartMiller1977_1977_Weak_convergence_to_Brownian_meander_and_Brownian_excursion.pdf`
- `111_DuttEtAl2019_2019_Nature_Communications.pdf`
- `112_Edwards_1974_Riemanns_Zeta_Function.pdf`
- `113_Engert1970_1970_Finite_dimensional_translation_invariant_subspaces.pdf`
- `114_ErdosEtAl2012_2012_Spectral_statistics_of_Erd.pdf`
- `115_Fazzari-Gerspach-Minelli_2025_Selberg_CLT_Weighted_Linear_Statistics_Zeta_Zeros.pdf`
- `116_FazziGuglielmiMarkovsky2021_2021_A_gradient_system_approach_for_Hankel_structured_low_rank_approximation.pdf`
- `117_Ferrero-Washington_1979_Iwasawa_Invariant_Mu_p_Vanishes_Abelian_Number_Fields.pdf`
- `118_Fiori_2025_Note_Phragmen_Lindelof_Theorem.pdf`
- `119_Ford-Meng-Zaharescu_2017_Simultaneous_Fractional_Parts.pdf`
- `120_Ford-Soundararajan-Zaharescu_2009_Imaginary_Parts_II.pdf`
- `121_Ford-Zaharescu_2005_Imaginary_Parts_Zeta_Zeros.pdf`
- `122_Ford_2002_Vinogradov_Integral_Bounds_Riemann_Zeta.pdf`
- `123_Forrester-Lebowitz_2013_Local_CLT_Determinantal_Point_Processes.pdf`
- `124_Forrester-Mays_2015_Finite_Size_Corrections_RMT_Odlyzko_Data.pdf`
- `125_Franca-LeClair_2014_Statistical_Properties_Riemann_Zeros_Explicit_Equation_nth_Zero.pdf`
- `126_Franca-LeClair_2014_Theory_Zeros_Riemann_Zeta_And_Other_L_Functions.pdf`
- `127_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions.pdf`
- `128_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions_CNTP_Published.pdf`
- `129_Frantzikinakis2020_1908_Correlations_of_multiplicative_functions_along_deterministic_and_independent_sequences.pdf`
- `130_Friedlander-Granville_1993_Smoothing_Smooth_Numbers.pdf`
- `131_Fujii_1974_Zeros_Dirichlet_L_Functions_I.pdf`
- `132_Fujii_1975_Difference_r_Consecutive_Ordinates_Zeros_Zeta.pdf`
- `133_Fujii_1975_Distribution_Zeros_Zeta_Short_Intervals.pdf`
- `134_Fujii_1981_Zeros_Dirichlet_L_Functions_II_Corrections.pdf`
- `135_GPY2009_2009_Annals_of_Mathematics.pdf`
- `136_Gallagher_1970_Large_Sieve_Density_Estimate_Near_Sigma_1.pdf`
- `137_Gallier2016_2016_Spectral_theory_of_unsigned_and_signed_graphs_applications_to_graph_clustering_a_survey.pdf`
- `138_Gan-Qiu-Takeda_2014_Regularized_Siegel_Weil_Formula_Rallis_Inner_Product_arXiv_v3.pdf`
- `139_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf`
- `140_Ghosh-Sarnak_2012_Real_Zeros_Hecke_Cusp_Forms.pdf`
- `141_Ghosh_2022_Statistics_Approximations_Zeros_Truncated_Symmetrized_Euler_Products.pdf`
- `142_Goldfeld_1982_Produits_Partiels_Euleriens_Courbes_Elliptiques.pdf`
- `143_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_II_Alternative_Hypothesis.pdf`
- `144_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_I_Simple_Critical.pdf`
- `145_Gonek-Sahay_2024_Consecutive_Moderate_Gaps_Between_Zeros_Zeta.pdf`
- `146_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf`
- `147_Gonek_2012_Finite_Euler_Products_Riemann_Hypothesis.pdf`
- `148_GordinPeligrad2011_2011_On_the_functional_central_limit_theorem_via_martingale_approximation.pdf`
- `149_Gouezel2010_2010_Almost_sure_invariance_principle_for_dynamical_systems_by_spectral_methods.pdf`
- `150_Graham-Kolesnik_1991_Computing_Optimal_Exponent_Pairs.pdf`
- `151_Graham-Kolesnik_1991_Simplest_Van_Der_Corput_Estimates.pdf`
- `152_Granville-Soundararajan_2003_Decay_Of_Mean_Values.pdf`
- `153_Granville_2008_Smooth_Numbers_Survey.pdf`
- `154_Grayson_1984_Reduction_Theory_Using_Semistability.pdf`
- `155_GrepstadEtAl2019_1909_On_the_asymptotic_behaviour_of_the_sine_product.pdf`
- `156_Grosswald-Schnitzer_1978_Class_Modified_Zeta_L_Functions.pdf`
- `157_Guillera_2013_Sums_Nontrivial_Zeros_Riemann_Zeta.pdf`
- `158_Gunturk-Thao_2003_Ergodic_Dynamics_Sigma_Delta_Quantization.pdf`
- `159_Guth-Maynard_2026_New_Large_Value_Estimates_Dirichlet_Polynomials.pdf`
- `160_Hadamard_1896_Distribution_Zeros_Zeta_Consequences_Arithmetiques.pdf`
- `161_Hamburger_1921_Riemannsche_Funktionalgleichung_Zeta_Funktion_I.pdf`
- `162_Hardy-Littlewood-Polya_1934_Inequalities.pdf`
- `163_Hardy-Littlewood_1917_Riemann_Zeta_And_Distribution_Primes.pdf`
- `164_Harman-Pintz-Wolke_1985_Mobius_And_Liouville_Functions.pdf`
- `165_Harper_2013_Conditional_Bounds_Zeta_Moments.pdf`
- `166_Harper_2020_Moments_Random_Multiplicative_Functions_I.pdf`
- `167_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Dedekind_Zeta.pdf`
- `168_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Riemann_Zeta.pdf`
- `169_HaugPrellberg2015_2015_Uniform_asymptotics_of_area_weighted_Dyck_paths.pdf`
- `170_Haynes-Zudilin_2015_Hankel_Determinants_Zeta_Values.pdf`
- `171_HeathBrown_2016_New_kth_Derivative_Estimate_Exponential_Sums_Vinogradov_arXiv_v3.pdf`
- `172_Helfgott-Thompson_2023_Summing_Mobius_Faster_Elementary_Algorithm.pdf`
- `173_HelfgottRadziwill2021_undated_HelfgottRadziwill2021.pdf`
- `174_HerichiLapidus2014_2014_Truncated_infinitesimal_shifts_spectral_operators_and_quantized_universality_of_the_Riemann_zeta_function.pdf`
- `175_HerreraMoree2018_2018_Coefficients_and_higher_order_derivatives_of_cyclotomic_polynomials_old_and_new.pdf`
- `176_HeuslerEtAl2007_2007_Periodic_orbit_theory_of_level_correlations.pdf`
- `177_Hiary-Leong-Yang_2024_Explicit_Bounds_Zeta_1_Line_arXiv_v3.pdf`
- `178_Hiary-Leong-Yang_2025_Explicit_Bounds_Zeta_1_Line.pdf`
- `179_Hiary-Patel-Yang_2024_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf`
- `180_Hida_2004_pAdic_Automorphic_Forms_Shimura_Varieties.pdf`
- `181_Hilberdink-Lapidus_2006_Beurling_Zeta_Generalised_Primes_Fractal_Membranes.pdf`
- `182_Hilberdink-Pushnitski_2023_Spectral_Asymptotics_LCM_Matrices.pdf`
- `183_Hilberdink_2006_Determinants_Multiplicative_Toeplitz_Matrices.pdf`
- `184_Hilberdink_2015_Multiplicative_Toeplitz_Matrices_Riemann_Zeta.pdf`
- `185_Hilberdink_2017_Singular_Values_Multiplicative_Toeplitz_Matrices.pdf`
- `186_Hoffman1992_1992_Multiple_harmonic_series.pdf`
- `187_Hruscev-Nikolskii-Pavlov_1981_Unconditional_Bases_Exponentials_Reproducing_Kernels.pdf`
- `188_Hughes-Rudnick_2002_Linear_Statistics_Zeros_Zeta.pdf`
- `189_Hurst2026_2026_Practical_computations_of_the_Mertens_function_M_10.pdf`
- `190_Hurst_2018_Computations_Mertens_Function_Improved_Bounds.pdf`
- `191_Hutchinson_1925_Roots_Riemann_Zeta_Function.pdf`
- `192_Huxley_1976_Imperfect_Hybrid_Zero_Density_Theorem.pdf`
- `193_Huxley_1989_Exponential_Sums_Riemann_Zeta.pdf`
- `194_Igusa_2000_Introduction_Local_Zeta_Functions.pdf`
- `195_Ingham_1936_Trigonometrical_Inequalities_Theory_Series.pdf`
- `196_Inoue-Kobayashi-Toma_2026_Explicit_Extreme_Values_Argument_Zeta.pdf`
- `197_Inoue_2024_Note_On_r_Gaps_Between_Zeros_Zeta.pdf`
- `198_Ivic-Korolev_2018_Distribution_Values_Argument_Zeta.pdf`
- `199_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf`
- `200_Ivic_2001_Sums_Over_Ordinates_Zeta_Zeros.pdf`
- `201_Ivic_2003_Riemann_Zeta_Dover_Reprint.pdf`
- `202_Janson_2007_Brownian_Excursion_Area_Wright_Constants.pdf`
- `203_Jerby_2023_New_Discriminant_Hardy_Z_Function_Corrected_Gram_Law.pdf`
- `204_Johansson_2001_Discrete_Orthogonal_Polynomial_Ensembles_Plancherel.pdf`
- `205_Johansson_2017_Arb_Arbitrary_Precision_Interval_Arithmetic.pdf`
- `206_Johansson_2018_Numerical_Integration_Ball_Arithmetic.pdf`
- `207_Jones-Sato-Wada-Wiens_1976_Diophantine_Representation_Primes.pdf`
- `208_Jun-Lee_2014_Dedekind_And_Exponential_Sums.pdf`
- `209_Jutila_1977_Zero_Density_Estimates_L_Functions.pdf`
- `210_Kaczorowski-Perelli_1999_Structure_Selberg_Class_I.pdf`
- `211_Kaczorowski-Pintz_1986_Oscillatory_Properties_Arithmetical_Functions_I.pdf`
- `212_KaczorowskiLanguascoPerelli2000_2000_A_note_on_Landau_s_formula.pdf`
- `213_Kaczorowski_1991_k_Functions_Multiplicative_Number_Theory_V.pdf`
- `214_Kaigh1976_1976_An_invariance_principle_for_random_walk_conditioned_by_a_late_return_to_zero.pdf`
- `215_Kanemitsu-Tsukada_2015_Hecke_Type_Zeta_Functions.pdf`
- `216_Kanemitsu-Tsukada_2015_Modular_Relation_Supremacy.pdf`
- `217_Kannan-Bachem_1979_Polynomial_Algorithms_Smith_Hermite_Normal_Forms.pdf`
- `218_Karatsuba-Voronin_1992_Vinogradov_Method_Riemann_Zeta.pdf`
- `219_Kargin_2013_Fluctuations_Riemann_Zeta_Zeros.pdf`
- `220_Kato_2004_pAdic_Hodge_Theory_Values_Zeta_Functions_Modular_Forms.pdf`
- `221_Keating_2022_Hierarchical_Structure_Trace_Formula.pdf`
- `222_Kelly-Le_2018_Van_Der_Corput_Sets_Compact_Groups.pdf`
- `223_KhorunzhiyMarckert2009_2009_Uniform_bounds_for_exponential_moment_of_maximum_of_a_Dyck_path.pdf`
- `224_Kinnunen_1997_Hardy_Littlewood_Maximal_Function_Sobolev_Function.pdf`
- `225_Knopp_1994_Dirichlet_Series_Riemann_Functional_Equation.pdf`
- `226_Kolountzakis-Revesz_2003_Turan_Extremal_Problem.pdf`
- `227_Kolyvagin_1990_Euler_Systems.pdf`
- `228_Komori-Matsumoto-Tsumura_2023_Zeta_Functions_Root_Systems.pdf`
- `229_Korolev-Laurincikas_2023_Approximation_Mellin_Transform_Zeta_Axioms.pdf`
- `230_Korolev_2010_Gram_Law_Selberg_Conjecture_Zeros_Izv_Math.pdf`
- `231_Korolev_2011_Gram_Law_Argument_Riemann_Zeta_arXiv.pdf`
- `232_Korolev_2012_Gram_Law_Argument_Riemann_Zeta_Publ_Inst_Math.pdf`
- `233_Korolev_2012_Gram_Law_Riemann_Zeta.pdf`
- `234_Korolev_2016_Extreme_Values_S_Short_Intervals_Indian_J.pdf`
- `235_Korolev_2016_Gram_Law_Theory_Zeta_Part1_Proc_Steklov.pdf`
- `236_Kotnik-vandeLune_2004_Order_Mertens_Function.pdf`
- `237_Kousha2012_2012_Asymptotic_behavior_and_the_moderate_deviation_principle_for_the_maximum_of_a_Dyck_path.pdf`
- `238_Kowalski-Robert-Wu_2007_Small_Gaps_And_B_Free_Numbers.pdf`
- `239_Kowalski_2021_Exponential_Sums_Finite_Fields_Elementary.pdf`
- `240_Kowalski_2021_Exponential_Sums_Finite_Fields_II.pdf`
- `241_Kozma-Lev_2011_Exponential_Riesz_Bases_Discrepancy_BMO.pdf`
- `242_Kurasov-Sarnak_2020_Stable_Polynomials_Crystalline_Measures.pdf`
- `243_LMS_2015_Atle_Selberg_Obituary.pdf`
- `244_Labahn-Neiger-Zhou_2018_Hermite_Normal_Form_Polynomial_Matrix.pdf`
- `245_Lagarias2007_2007_Li_coefficients_for_automorphic_functions.pdf`
- `246_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf`
- `247_Landau_1912_Nullstellen_Zetafunktion.pdf`
- `248_Lapidus-VanFrankenhuysen_2000_Fractal_Geometry_Number_Theory.pdf`
- `249_Lau-Liu-Wu_2010_Symmetric_Square_L_Function_Coefficients.pdf`
- `250_LeClair_2016_Riemann_Hypothesis_Random_Walks_Zeta_Case.pdf`
- `251_LeeLeong2024_2024_New_explicit_bounds_for_the_Mertens_function_and_the_reciprocal_of_the_Riemann_zeta_function.pdf`
- `252_Leong_2024_Explicit_Estimates_Log_Derivative_Reciprocal_Zeta.pdf`
- `253_Lester-Matomaki-Radziwill_2015_Small_Scale_Zeros_Modular_Forms.pdf`
- `254_Lev-Olevskii_2015_Quasicrystals_Poisson_Summation_Formula.pdf`
- `255_Lev_2012_Riesz_Bases_Exponentials_Multiband_Spectra_Preprint.pdf`
- `256_LiYang2023_2023_An_improvement_on_Gauss_s_circle_problem_and_Dirichlet_s_divisor_problem.pdf`
- `257_Li_2019_Zeta_L_Functions_Number_Theory_Combinatorics.pdf`
- `258_Lieb-Loss_2001_Analysis_Second_Edition.pdf`
- `259_Lindqvist-Seip_1998_Note_Greatest_Common_Divisor_Matrices.pdf`
- `260_Littlewood_1924_Zeros_Riemann_Zeta_Function.pdf`
- `261_Liu2022_2022_Multiplicative_functions_resembling_the_M_bius_function.pdf`
- `262_Lubin-Tate_1965_Formal_Complex_Multiplication_Local_Fields.pdf`
- `263_Lyubarskii-Seip_1997_Complete_Interpolating_Sequences_Paley_Wiener_Muckenhoupt_Ap.pdf`
- `264_LyubarskiiVershynin2010_2010_Uncertainty_principles_and_vector_quantization.pdf`
- `265_Matiyasevich2007a_1983_Hidden_Life_of_Riemann_s_Zeta_Function_1_Arrow_Bow_and_Targets.pdf`
- `266_Matiyasevich2007b_2007_Hidden_Life_of_Riemann_s_Zeta_Function_2_Electrons_and_Trains.pdf`
- `267_Matomaki-Radziwill-Tao_2015_Averaged_Chowla_Conjecture.pdf`
- `268_Matomaki-Radziwill_2015_Liouville_Short_Intervals.pdf`
- `269_Matomaki-Radziwill_2015_Sign_Changes_Hecke_Eigenvalues.pdf`
- `270_Matomaki-Radziwill_2016_Multiplicative_Functions_Short_Intervals.pdf`
- `271_Matomaki-Shao-Tao-Teravainen_2023_Higher_Uniformity_Arithmetic_Functions.pdf`
- `272_Matomaki-Teravainen_2023_Mobius_Function_All_Short_Intervals.pdf`
- `273_Matomaki_2010_Smooth_Numbers_Short_Intervals.pdf`
- `274_Matomaki_2016_Smooth_Numbers_Short_Intervals_II.pdf`
- `275_MelottiSaias2020_2020_On_path_partitions_of_the_divisor_graph.pdf`
- `276_Mirsky_1949_Frequency_Pairs_Square_Free_Numbers_Given_Difference.pdf`
- `277_Monien_2009_Hankel_Determinants_Dirichlet_Series.pdf`
- `278_Montgomery-Vaughan_1974_Hilberts_Inequality.pdf`
- `279_MontgomerySoundararajan2004_2004_Comm_Math_Phys.pdf`
- `280_Montgomery_1973_Pair_Correlation_Zeros_Zeta.pdf`
- `281_Moriwaki_2009_Continuity_Volumes_Arithmetic_Varieties_arXiv_v2.pdf`
- `282_Mossinghoff-Trudgian-Yang_2022_Explicit_Zero_Free_Regions_Riemann_Zeta.pdf`
- `283_MossinghoffOliveiraTrudgian2021_2021_The_distribution_of_k_free_numbers.pdf`
- `284_Motohashi_1977_On_Gallaghers_Prime_Number_Theorem.pdf`
- `285_Motohashi_1978_Primes_in_Arithmetic_Progressions.pdf`
- `286_Motohashi_1997_Spectral_Theory_Riemann_Zeta.pdf`
- `287_Muellner2017_2017_Automatic_sequences_fulfill_the_Sarnak_conjecture.pdf`
- `288_MullerEtAl2005_2005_Periodic_orbit_theory_of_universality_in_quantum_chaos.pdf`
- `289_Murahara-Onozuka_2025_Equidistribution_A_Points_Zeta_Derivatives.pdf`
- `290_MussardoLeClair2021_2021_Randomness_of_M_obius_coefficients_and_Brownian_motion_growth_of_the_Mertens_function_and_the_Riemann_hypothes.pdf`
- `291_Nakamura_2020_Dirichlet_Series_Periodic_Coefficients_Functional_Equation.pdf`
- `292_Ng2004_2004_Proc_London_Math_Soc.pdf`
- `293_Nishigaki_2024_Consecutive_Level_Spacings_GUE_Ratio.pdf`
- `294_Nishigaki_2025_Consecutive_Level_Spacings_CUE_Finite_Size_Zeta.pdf`
- `295_Norvidas_2011_Entire_Functions_Exponential_Sums.pdf`
- `296_Nunes2015_2015_Journal_of_Number_Theory.pdf`
- `297_Odlyzko-TeRiele_1985_Disproof_Mertens_Conjecture.pdf`
- `298_Odlyzko_1987_Distribution_Spacings_Between_Zeros_Zeta.pdf`
- `299_OganesyanHuse2007_2007_Localization_of_interacting_fermions_at_high_temperature.pdf`
- `300_Ohsawa-Takegoshi_1987_Extension_L2_Holomorphic_Functions.pdf`
- `301_Olevskii-Ulanovskii_2020_Fourier_Quasicrystals_Unit_Masses.pdf`
- `302_Olver_1974_Introduction_Asymptotics_Special_Functions.pdf`
- `303_Olver_1997_Asymptotics_Special_Functions_AK_Peters_Reprint.pdf`
- `304_OwczarekPrellberg2014_2014_Pressure_exerted_by_a_vesicle_on_a_surface.pdf`
- `305_Patel-Yang_2024_Explicit_Sub_Weyl_Bound_Zeta_Critical_Line.pdf`
- `306_Patel_2022_Explicit_Upper_Bound_Zeta_1_Line.pdf`
- `307_Patterson_1988_Introduction_Riemann_Zeta_Function.pdf`
- `308_Patterson_1988_Zeros_Zeta_And_Prime_Number_Theorem.pdf`
- `309_PeligradUtev2005_2005_A_new_maximal_inequality_and_invariance_principle_for_stationary_sequences.pdf`
- `310_Perelli_2016_Converse_Theorems_Zeta_Selberg_Class.pdf`
- `311_Perfekt-Pushnitski_2018_Spectrum_Multiplicative_Hilbert_Matrix.pdf`
- `312_PillaiYin2014_2014_Universality_of_covariance_matrices.pdf`
- `313_Pintz_2026_Oscillation_Mobius_Function_Zeta_Zeros.pdf`
- `314_Platt-Trudgian_2014_Improved_Explicit_Bound_Zeta_Critical_Line_arXiv_v2.pdf`
- `315_Platt-Trudgian_2015_Zeroes_Partial_Sums_Zeta_Function_arXiv_v2.pdf`
- `316_Platt-Trudgian_2021_RH_True_Up_To_3e12.pdf`
- `317_Platt_2017_Isolating_Nontrivial_Zeros_Zeta.pdf`
- `318_Popov_1985_Transfer_Functions_Riemann_Zeta.pdf`
- `319_Rademacher_1959_Phragmen_Lindelof_Theorem_Applications.pdf`
- `320_Radziwill-Soundararajan_2015_Quadratic_Twists_Central_L_Values.pdf`
- `321_Rallis_1984_Injectivity_Properties_Liftings_Weil_Representations.pdf`
- `322_Ramachandra_1976_Problems_Analytic_Number_Theory.pdf`
- `323_Revers_2026_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf`
- `324_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf`
- `325_Richard_2005_Q_Functional_Equations_Excursion_Moments.pdf`
- `326_Riemann-Wilkins_1859_Prime_Counting_English_Translation.pdf`
- `327_RigalZadunaisky2015_2015_Twisted_semigroup_algebras.pdf`
- `328_RodgersTao2018_2018_RodgersTao2018.pdf`
- `329_Roesler_1986_Riemann_Hypothesis_Eigenvalue_Problem.pdf`
- `330_Roesler_1987_Riemann_Hypothesis_Eigenvalue_Problem_II.pdf`
- `331_Rosser-Schoenfeld_1962_Approximate_Formulas_Functions_Prime_Numbers.pdf`
- `332_Rosser_1941_Explicit_Bounds_Functions_Prime_Numbers.pdf`
- `333_Rota_1964_Foundations_Combinatorial_Theory_Mobius_Functions.pdf`
- `334_Rudin_1987_Real_Complex_Analysis_Third_Edition.pdf`
- `335_Saffari-Vaughan_1977_Fractional_Parts_X_Over_N_II.pdf`
- `336_Sawin_2022_Mobius_Cancellation_Polynomial_Sequences.pdf`
- `337_Schechter_2002_Principles_Functional_Analysis_Second_Edition.pdf`
- `338_Sekatskii-Beltraminelli-Merlini_2012_Integrals_Logarithm_Zeta_RH.pdf`
- `339_Sekatskii_2013_Generalized_Bombieri_Lagarias_Li_Criterion.pdf`
- `340_Sekatskii_2014_Generalized_Li_Criterion_Zeroes_Location.pdf`
- `341_Selberg-Chowla_1967_On_Epstein_Zeta_Function.pdf`
- `342_Sheth_2025_Euler_Products_Centre_Chebyshev_Bias.pdf`
- `343_Shir-MartinezAzcona-Chenu_2025_Surmise_Level_Spacing_Beyond_Nearest.pdf`
- `344_Sidi_2003_Riemann_And_Generalized_Zeta_Extrapolation.pdf`
- `345_Siegel_1922_Satz_Hamburger_Funktionalgleichung_Zetafunktion.pdf`
- `346_Sorensen_2020_A_Patching_Lemma.pdf`
- `347_Soule_2003_Bound_Torsion_K_Theory_Algebraic_Integers.pdf`
- `348_Soundararajan_2009_Partial_Sums_Mobius_Function.pdf`
- `349_Soundararajan_2010_Smooth_Numbers_Short_Intervals.pdf`
- `350_StampachStovicek2020_2020_On_Hankel_matrices_commuting_with_Jacobi_matrices_from_the_Askey_scheme.pdf`
- `351_Suzuki2025Hilbert_2025_On_the_Hilbert_space_derived_from_the_Weil_distribution.pdf`
- `352_Szekelyhidi1982_1982_Note_on_exponential_polynomials.pdf`
- `353_Tao-Teravainen_2018_Odd_Order_Logarithmically_Averaged_Chowla.pdf`
- `354_Tao-Teravainen_2019_Structure_Logarithmically_Averaged_Correlations.pdf`
- `355_Tao-Trudgian-Yang_2025_New_Exponent_Pairs_Zero_Density_Additive_Energy_arXiv_v1.pdf`
- `356_Tao_2016_Logarithmically_Averaged_Chowla_Elliott_Two_Point.pdf`
- `357_Taylor-Wiles_1995_Ring_Theoretic_Properties_Certain_Hecke_Algebras.pdf`
- `358_Tenenbaum_2015_Analytic_Probabilistic_Number_Theory.pdf`
- `359_Tenenbaum_2017_Generalized_Mertens_Sums.pdf`
- `360_Titchmarsh-HeathBrown_1986_Theory_Riemann_Zeta_Function.pdf`
- `361_Titchmarsh_1939_Theory_Functions_Second_Edition.pdf`
- `362_Trudgian-Yang_2024_Toward_Optimal_Exponent_Pairs_arXiv_v3.pdf`
- `363_Trudgian_2008_Gram_Law_Fails_Positive_Proportion_Of_The_Time.pdf`
- `364_Trudgian_2012_Improved_Upper_Bound_Argument_Zeta.pdf`
- `365_Trudgian_2014_Improved_Upper_Bound_Argument_Zeta_II.pdf`
- `366_Turing_1953_Some_Calculations_Riemann_Zeta_Function.pdf`
- `367_Vaughan_1996_Eigenvalues_Redheffer_Matrix_II.pdf`
- `368_Vega_2023_Simple_Proof_Riemann_Hypothesis.pdf`
- `369_Volchkov_1995_Equality_Equivalent_Riemann_Hypothesis_Russian.pdf`
- `370_Weil_1952_Formules_Explicites_Nombres_Premiers_Transcription_VellaChemla.pdf`
- `371_Wilf_2004_Redheffer_Matrix_Partially_Ordered_Set.pdf`
- `372_Xylouris_2011_Nullstellen_Dirichletschen_L_Funktionen_Kleinste_Primzahl.pdf`
- `373_Yang_2024_Explicit_Bounds_Zeta_Critical_Strip_Zero_Free_Region.pdf`
- `374_Young_1974_Inequalities_Perturbation_Theorem_Paley_Wiener.pdf`
- `375_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf`
- `376_Zhang_2013_Normalization_Beurling_Generalized_Primes_RH.pdf`
- `377_Zhao_2016_Multiple_Zeta_Polylogarithms_Special_Values.pdf`
- `378_Zhao_2026_Density_Results_r_Gaps_Between_Zeros_Zeta.pdf`
- `379_deBruijn1950_1950_The_roots_of_trigonometric_integrals.pdf`
- `380_deLaValleePoussin_1896_Recherches_Analytiques_Nombres_Premiers_I.pdf`
- `381_vonMangoldt_1895_Zu_Riemanns_Abhandlung_Anzahl_Primzahlen.pdf`
- `382_vonMangoldt_1905_Verteilung_Nullstellen_Riemannschen_Funktion_Xi.pdf`
