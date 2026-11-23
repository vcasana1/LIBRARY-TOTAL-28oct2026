# LIBRARY TOTAL — índice vigente

**Repositorio:** `vcasana1/LIBRARY-TOTAL-28oct2026` · **Rama:** `main` · **Comprobación:** 2026-11-23 · **PDF principales:** 422 (`001`–`422`, en orden alfabético ASCII, sin huecos numéricos ni duplicados binarios), más 1 PDF parcial identificado en `DOCUMENTOS_PARCIALES/`. Las versiones distintas de una misma obra se conservan expresamente.

**Ruta del Mac comprobada:** `/Users/vcasana/Documents/LIBRARY TOTAL/`. Los 337 PDF previos coincidían con `main` en el commit `e6473ce42726d1e6103059a977ea0c3d2022ef79`. Incorporación del 2026-11-01: 16 PDF nuevos numerados 338–353 y 1 parcial separado, copiados desde Descargas; los originales de Descargas y los PDF 001–337 se conservan sin cambios. El registro `INCORPORACIONES_2026-11-01.json` se retiró el 2026-11-22 (queda en el historial de git, commit `4a661ae`). **Incorporación y renumeración del 2026-11-22:** 26 PDF nuevos (bibliografía de Alpöge, §21) y renumeración completa de la carpeta en orden alfabético; los números 001–353 y 338–353 citados en notas anteriores y en el registro del 2026-11-01 corresponden a la numeración antigua; equivalencias en `RENUMERACION_2026-11-22.md` (retirado el 2026-11-23; tabla acumulada en `RENUMERACION_2026-11-23.md`). **Segunda incorporación del 2026-11-22:** 3 PDF (Gallagher 1970; Motohashi 1977 y 1978), copiados desde Descargas, y nueva renumeración completa a 382 PDF; `RENUMERACION_2026-11-22.md` (retirado el 2026-11-23; tabla acumulada en `RENUMERACION_2026-11-23.md`) se ha rehecho y da cada número en la numeración del 2026-11-01, en la primera del 2026-11-22 (379 PDF) y el vigente; la tabla anterior se ha retirado. **Incorporación y renumeración del 2026-11-23:** 40 PDF nuevos (bibliografía de postRHera: método de Stepanov–Bombieri, curvas CM y números de Hurwitz, interpolación $p$-ádica, módulos singulares de Gross–Zagier, integrales log-seno), copiados desde `POSTRHERA_bibliografia.zip` y dos PDF sueltos idénticos a los del zip; renumeración completa a 422 PDF (`RENUMERACION_2026-11-23.md`, hashes en `INCORPORACIONES_2026-11-23.json`). Los índices del 2026-11-22 (`RENUMERACION_2026-11-22.md` e `INCORPORACIONES_2026-11-22.json`) se retiraron el 2026-11-23 y quedan en el historial de git (commit `5f26776`).

## Uso

1. Localizar por autor, título o palabra clave en las secciones temáticas o en el catálogo numerado final.
2. Cada nombre en el catálogo final coincide exactamente con un PDF existente en este repositorio. El identificador más fiable es **nombre completo + SHA de Git**; el número es solo un identificador operativo.
3. Verificar en la **imagen de la página original** cada ecuación, fórmula, exponente, cuantificador y dominio antes de atribuirlo al paper. La extracción de texto y el OCR no son prueba suficiente.
4. Usar el catálogo final para identificar **los 422 PDF principales**; las secciones temáticas son ayudas de búsqueda y pueden repetir referencias.

## Incidencias vigentes

- PDF sin capa de texto: `070_Brent_1979_Zeros_Riemann_Zeta_Critical_Strip.pdf`, `163_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf`, `407_Volchkov_1995_Equality_Equivalent_Riemann_Hypothesis_Russian.pdf`.
- OCR delicado en fórmulas: `020_Backlund_1916_Nullstellen_Riemannschen_Zetafunktion.pdf` y `422_vonMangoldt_1905_Verteilung_Nullstellen_Riemannschen_Funktion_Xi.pdf`.
- PDF incompleto: `127_Edwards_1974_Riemanns_Zeta_Function.pdf` (escaneo solo de pp. impresas 1–122/311); `163_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf` (solo pp. 92–96).
- PDF a doble página: `230_Jutila_1977_Zero_Density_Estimates_L_Functions.pdf`, `234_Kaczorowski_1991_k_Functions_Multiplicative_Number_Theory_V.pdf`, `354_Ramachandra_1976_Problems_Analytic_Number_Theory.pdf`. Comprobar página impresa y página del PDF.
- `220_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf` y `222_Ivic_2003_Riemann_Zeta_Dover_Reprint.pdf` son ediciones del mismo libro; erratas en `ERRATA_Ivic.md`.
- El preprint `009_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` es anónimo y no es un artículo de Riemann. La fuente de Riemann se encuentra en `358_Riemann-Wilkins_1859_Prime_Counting_English_Translation.pdf` (transcripción en alemán).
- `091_Claude_2026_More_Than_Two_Thirds_Zeros_Zeta_Critical_Line.pdf` no es la versión arXiv firmada por L. Alpöge y R. Furman (arXiv:2608.13637v2).
- Verificar antes de citar: `110_Dannon_2008_Riemann_Zeta_Function.pdf`, `406_Vega_2023_Simple_Proof_Riemann_Hypothesis.pdf`, `413_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf` y `009_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` (sin revisión por pares acreditada).
- PDF sin capa de texto (solo consulta visual): también `276_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf` y `356_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf`.
- Bibliografía de Alpöge (§21): la referencia [3] Behrend (PNAS 32, 1946, 331–332) **no está** en la biblioteca: la descarga automática devolvió una página de protección en lugar del PDF. Las referencias [9] Davenport–Montgomery (3.ª ed.) y [15] Howe 1979 no se incorporaron porque ya las tienes; en la biblioteca figura la 2.ª ed. de Davenport (1980) y, como sustituto abierto de Howe, `156_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf`. [1] (código Lean, commit 7cbf7a0c…) y [28] (página de verificación de Sutherland) no son PDF y permanecen en Descargas, fuera de la carpeta plana.
- Incorporación del 2026-11-23: sin capa de texto (solo consulta visual) `056_Bombieri_1978_On_Exponential_Sums_in_Finite_Fields_II.pdf`, `153_Gallagher_1971_A_Larger_Sieve.pdf`, `211_Hurwitz_1899_Lemniscatische_Functionen.pdf` y `247_Katz_1981_Divisibilities_Congruences_Cartier_Duality.pdf`; solo la portada tiene texto y el resto es escaneo en `242_Katz_1975_Congruences_Bernoulli_Hurwitz.pdf`, `246_Katz_1978_pAdic_L_Functions_for_CM_Fields.pdf` y `173_Gross-Zagier_1985_On_Singular_Moduli.pdf`. `054_Bombieri_1966_On_Exponential_Sums_in_Finite_Fields_Russian_1968.pdf` es la traducción rusa de 1968 del artículo de Bombieri de 1966 (el original inglés, Amer. J. Math. 88, falta). `153_Gallagher_1971_A_Larger_Sieve.pdf` es un escaneo a doble página (pp. 77–81, con la p. 76 del artículo anterior). `211_Hurwitz_1899_Lemniscatische_Functionen.pdf` está extraído del volumen 51 digitalizado (el DOI de la reimpresión citado en v4 corresponde a otro capítulo). Los dos PDF sueltos de Gross–Zagier se incorporaron una sola vez.

## Fuentes citadas todavía pendientes

Esta lista recoge ausencias detectadas por coincidencia de título/autor en el inventario y **no** equivale a una auditoría bibliográfica de los originales ni a afirmar que no puedan conseguirse en línea.

- **Rudnick & Sarnak**, *Zeros of principal L-functions and random matrix theory*, Duke Math. J. **81** (1996), 269–322. Base del salto de estadística 2-level a n-level.
- **Forrester & Odlyzko**, *Gaussian unitary ensemble eigenvalues and Riemann zeta function zeros: a nonlinear equation for a new statistic*, Phys. Rev. E **54** (1996), R4493. Tratamiento Fredholm/Painlevé de nearest-neighbour; evita usar el Wigner surmise como exacto.
- **Grossmann**, *Über die Nullstellen der Riemannschen Zeta-Funktion und der Dirichletschen L-Funktionen*, tesis, Göttingen, 1913. Sus constantes (0.29062, 1.7862, 6.13695; T > 50) están citadas en Backlund 1916, p. 355. (La tesis de Xylouris 2011 de la carpeta es otra.)
- **Selberg**, *Contributions to the theory of the Riemann zeta-function*, Arch. Math. Naturvid. **48** (1946), no. 5, 89–155. Los momentos de S(t) están en Titchmarsh §9.25, (9.25.1).
- **F. Riesz**, *Sur un théorème de maximum de MM. Hardy et Littlewood*, J. London Math. Soc. **7** (1932) 10–13. **Mertens**, J. Reine Angew. Math. **78** (1874) 46–62 (Mertens está en Tenenbaum).
- **Tsang**, *The distribution of the values of the Riemann zeta function*, tesis, Princeton, 1984. Citado de segunda mano a través de `130_Fazzari-Gerspach-Minelli_2025_Selberg_CLT_Weighted_Linear_Statistics_Zeta_Zeros.pdf` (§3, antes de (3.6); su Thm. 5.1).
- **Kargin**, *Statistical properties of zeta functions' zeros*, Probability Surveys **11** (2014), 121–160, arXiv:1302.1452. El survey.

---

- **Pendientes de la bibliografía de postRHera (cotejo del 2026-11-23):**
  - [Behrend (1946), On sets of integers which contain no three terms in arithmetical progression](https://pmc.ncbi.nlm.nih.gov/articles/PMC1078964/) — Citada en v4. Ficha y texto en PMC. La descarga devolvió una página web y la copia candidata local tampoco era un PDF.
  - [Kanemitsu–Yoshimoto (1996), Farey series and the Riemann hypothesis](https://doi.org/10.4064/aa-75-4-351-374) — Citada en v4. Acta Arith. 75, 351–374. El editor anuncia acceso libre, pero sus enlaces y el archivo polaco devolvieron errores en la descarga.
  - [Kurokawa–Mimachi–Wakayama (2007), Jackson’s integral of the Hurwitz zeta function](https://doi.org/10.1007/BF03031427) — Citada en v4. Ficha de la revista. PDF completo pendiente.
  - [Milnor (1983), On polylogarithms, Hurwitz zeta functions, and the Kubert identities](https://doi.org/10.5169/seals-52983) — Citada en v4. El archivo de e-periodica identifica la obra, pp. 281–322. El enlace al PDF devolvió una pantalla de verificación.
  - [Onodera (2011), Generalized log sine integrals and the Mordell–Tornheim zeta values](https://doi.org/10.1090/S0002-9947-2010-05176-1) — Citada en v4. Trans. AMS 363, 1463–1485. La descarga del editor devolvió 403.
  - [Patrì (2013), Sum of the generalized harmonic series with even natural exponent](https://www1.mat.uniroma1.it/ricerca/rendiconti/ARCHIVIO/2013%281-2%29/19-26.pdf) — Citada en v4. Enlace institucional identificado. La conexión a la copia del editor expiró.
  - [Smith (1875/76), On the value of a certain arithmetical determinant](https://doi.org/10.1112/plms/s1-7.1.208) — Citada en v4. Ficha del editor. PDF completo pendiente.
  - [Lang (1987), Elliptic Functions, 2.ª ed.](https://doi.org/10.1007/978-1-4612-4752-4) — Citada en v4. Libro. Falta comprobar la localización precisa del criterio de Deuring citado en v4.
  - [Lewin (1981), Polylogarithms and Associated Functions](https://search.worldcat.org/search?q=ti%3APolylogarithms%20and%20Associated%20Functions%20au%3ALewin) — Citada en v4. Libro. Edición exacta pendiente.
  - [Oberhettinger (1974), Tables of Mellin Transforms](https://doi.org/10.1007/978-3-642-65975-1) — Citada en v4. Libro. PDF completo pendiente.
  - [Silverman (2009), The Arithmetic of Elliptic Curves, 2.ª ed.](https://doi.org/10.1007/978-0-387-09494-6) — Citada en v4. Libro. La descarga directa del editor no entregó un PDF.
  - [Widder (1941), The Laplace Transform](https://search.worldcat.org/search?q=ti%3AThe%20Laplace%20Transform%20au%3AWidder) — Citada en v4. Libro. Edición exacta pendiente.
  - [Stepanov (1970), Elementary method in the theory of congruences for a prime modulus](https://www.impan.pl/en/publishing-house/journals-and-series/acta-arithmetica/all/17/3/97246/elementary-method-in-the-theory-of-congruences-for-a-prime-modulus) — Lectura relacionada. Acta Arith. 17, 231–247. El editor y el repositorio devolvieron errores de descarga.
  - [Stepanov (1972), An elementary proof of the Hasse–Weil theorem for hyperelliptic curves](https://www.sciencedirect.com/science/article/pii/0022314X72900595) — Lectura relacionada. Ficha de revista. PDF completo pendiente.
  - [Bombieri (1965), On the large sieve](https://doi.org/10.1112/S0025579300005313) — Lectura relacionada. Trabajo fundamental de criba, citado por Gallagher 1967. Descarga de editor bloqueada.
  - [Bombieri (1966), On exponential sums in finite fields, original inglés](https://doi.org/10.2307/2373048) — Lectura relacionada. El lote contiene la traducción rusa completa de 1968. La edición inglesa quedó pendiente.
  - [Gallagher (1967), The large sieve](https://doi.org/10.1112/S0025579300007968) — Lectura relacionada. Mathematika 14, 14–20. Las rutas de los editores no entregaron un PDF.
  - [Stöhr–Voloch (1986), Weierstrass points and curves over finite fields](https://doi.org/10.1112/plms/s3-52.1.1) — Lectura relacionada. Sistemas lineales, órdenes de Frobenius y cota de puntos. Enlace de autor roto y descarga editorial bloqueada.
  - [Chellali (1990), Congruences entre nombres de Bernoulli–Hurwitz dans le cas supersingulier](https://www.sciencedirect.com/science/article/pii/0022314X9090110D) — Lectura relacionada. Artículo original pendiente. El teorema 1.1 aparece reformulado en el §5 de Bannai–Kobayashi 2016.
  - [Schmidt (1976), Equations over Finite Fields. An Elementary Approach](https://doi.org/10.1007/BFb0080437) — Lectura relacionada. Monografía del método. PDF completo pendiente.

## 1. Núcleo RVM: sumas sobre ordenadas, fases y partes fraccionarias

- `014_Aryan_2019_Extension_Landau_Gonek_Formula.pdf` — extensión de la fórmula de Landau–Gonek; recupera sin RH consecuencias de pair correlation. arXiv:1902.05473
- `068_Brent-Platt-Trudgian_2020_Sums_Over_Zeros_Riemann_Zeta.pdf` — estimación explícita de sumas sobre ceros.
- `094_Coffey_2009_Certain_Sums_Over_Nontrivial_Zeta_Zeros.pdf` — coeficientes b_n como sumas sobre ceros y sobre las λ_j de Li/Keiper. arXiv:0912.2390
- `124_Durkan-Hughes-PearceCrump_2026_Generalisations_Landau_Gonek_Theorem.pdf` — sumas Σ_ρ χ(ρ)X^ρ; sensibilidad a la naturaleza aritmética de X. arXiv:2601.18025
- `221_Ivic_2001_Sums_Over_Ordinates_Zeta_Zeros.pdf` — G(s) = Σ_{γ>0} γ^{-s}; evaluación de sumas sobre γ e integrales de S(T). **Referencia base.**
- `320_Murahara-Onozuka_2025_Equidistribution_A_Points_Zeta_Derivatives.pdf` — sumas exponenciales sobre a-puntos de derivadas de ζ, siguiendo a Fujii. arXiv:2510.07710
- `009_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` **(preprint anónimo; revisar procedencia)** — sumas parciales S(N)=Σ e^{iγ_n}, banda estrecha de |S(N)|, picos y espaciados multimodales. Directamente sobre tu problema.
- `413_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf` — dinámica de bobinado de fase de ζ, heatmaps y estadística. Sin arbitraje.
- `134_Ford-Meng-Zaharescu_2017_Simultaneous_Fractional_Parts.pdf` — distribución simultánea de {α_1γ,…,α_nγ}. arXiv:1511.06814
- `135_Ford-Soundararajan-Zaharescu_2009_Imaginary_Parts_II.pdf` — partes fraccionarias de αγ, continuación. arXiv:0805.2745
- `136_Ford-Zaharescu_2005_Imaginary_Parts_Zeta_Zeros.pdf` — partes fraccionarias de αγ, primer trabajo de la serie.
- `369_Saffari-Vaughan_1977_Fractional_Parts_X_Over_N_II.pdf` — partes fraccionarias de x/n y sucesiones relacionadas.
- `015_Aryan_2022_Extension_Landau_Gonek_Formula_Published.pdf` — versión publicada de la extensión de la fórmula de Landau–Gonek. J. Number Theory 233 (2022) 389–404
- `163_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf` — Gonek, fórmula de Landau y valores medios de ζ; **incompleto (solo pp. 92–96) y sin capa de texto**
- `176_Guillera_2013_Sums_Nontrivial_Zeros_Riemann_Zeta.pdf` — identidades con sumas sobre los ceros no triviales; desarrollos asintóticos en la línea de Cramér. arXiv:1307.5723
- `233_KaczorowskiLanguascoPerelli2000_2000_A_note_on_Landau_s_formula.pdf` — forma ponderada de la versión uniforme de Gonek de la fórmula de Landau. Funct. Approx. 28 (2000) 173–186

## 2. Pair correlation de Montgomery

- `091_Claude_2026_More_Than_Two_Thirds_Zeros_Zeta_Critical_Line.pdf` — «Claude» (Anthropic), *More than two thirds of the zeros of the Riemann zeta function lie on the critical line*, versión del 10-8-2026, 35 pág. Proporciones de ceros simples y en la recta crítica, incondicionalmente, con la segunda varianza de Montgomery y la ley de inercia de Sylvester; formalización Lean en `github.com/anthropics/zeta-23-lean` (de ahí sale la desigualdad de Montgomery–Vaughan portada a PaperMath). Publicado en arXiv como arXiv:2608.13637v2 (21-8-2026), firmado por L. Alpöge y R. Furman.
- `311_Montgomery_1973_Pair_Correlation_Zeros_Zeta.pdf` — **el original**. F(α), 2/3 de ceros simples bajo RH.
- `026_Baluyot-Goldston-etal_2025_Pair_Correlation_Zeros_I_Proportions_Simple_Critical.pdf` — proporciones de ceros simples y en la crítica. arXiv:2501.14545
- `080_Carneiro-Chandee-Littmann-Milinovich_2014_Hilbert_Spaces_Pair_Correlation.pdf` — N(T,β) vía espacios de Hilbert de funciones enteras. arXiv:1406.5462
- `081_Carneiro-Milinovich-Ramos_2023_Fourier_Optimization_Montgomery_Pair_Correlation.pdf` — cotas del promedio de F(α,T) por optimización de Fourier. arXiv:2310.01913
- `085_Chan_2002_More_Precise_Pair_Correlation_Zeros_Primes_Short_Intervals.pdf` — segundos términos principales en la equivalencia Goldston–Montgomery.
- `099_Conrey-Keating_2016_Pair_Correlation_Twin_Primes_Revisited.pdf` — conexión ratios-conjecture / correlaciones aritméticas. arXiv:1604.06124
- `049_Bogomolny-Keating_1995_Random_Matrix_Theory_Riemann_Zeros_I_Three_Four_Point_Correlations.pdf` — correlaciones de 3 y 4 puntos de los ceros = GUE desde Hardy–Littlewood. doi:10.1088/0951-7715/8/6/013
- `050_Bogomolny-Keating_1996_Gutzwiller_Trace_Formula_Spectral_Statistics_Beyond_Diagonal.pdf` — correlación de dos puntos más allá de la aproximación diagonal; para ζ equivale a Hardy–Littlewood para pares de primos. doi:10.1103/PhysRevLett.77.1472
- `051_Bogomolny-Keating_1996_Random_Matrix_Theory_Riemann_Zeros_II_n_Point_Correlations.pdf` — correlaciones de n puntos = GUE para todo n, desde Hardy–Littlewood. doi:10.1088/0951-7715/9/4/006
- `111_Das-Ismoilov-Ramos_2025_Fourier_Optimization_Pair_Correlation_Problems.pdf` — marco genérico de cotas de pair correlation. arXiv:2502.05106
- `160_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_II_Alternative_Hypothesis.pdf` — PCC bajo hipótesis alternativa. arXiv:2507.06823
- `161_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_I_Simple_Critical.pdf` — PCC sin RH y ceros simples. arXiv:2503.15449
- `255_Kolountzakis-Revesz_2003_Turan_Extremal_Problem.pdf` — problema extremal de Turán; herramienta de optimización de Fourier.
- `151_GPY2009_2009_Annals_of_Mathematics.pdf` — Goldston–Pintz–Yıldırım, *Primes in tuples I*. Ann. of Math. 170 (2009)
- `310_MontgomerySoundararajan2004_2004_Comm_Math_Phys.pdf` — primos en intervalos cortos: varianza menor que la del modelo de Cramér. arXiv:math/0409258

## 3. Gaps entre ceros y arg ζ

- `422_vonMangoldt_1905_Verteilung_Nullstellen_Riemannschen_Funktion_Xi.pdf` — H. von Mangoldt, *Zur Verteilung der Nullstellen der Riemannschen Funktion ξ(t)*, Math. Ann. 60 (1905) 1–19, doi:10.1007/BF01447494. p. 1: |N(T) − (T/2π)log(T/2πe)| < 0.43200 log T + 1.91662 log log T + 13.07873 para T > 28.558 (primera fila de la tabla de récords).
- `020_Backlund_1916_Nullstellen_Riemannschen_Zetafunktion.pdf` — R. J. Backlund, *Über die Nullstellen der Riemannschen Zetafunktion*, Acta Math. 41 (1916) 345–375, doi:10.1007/BF02422950. Q(T) = N(T) − (T/2π log T/2π − T/2π + 7/8) (p. 354); (39): |Q(T)| < 0.137 log T + 0.443 log log T + 4.350, válida para todo T ≥ 2 (pp. 355, 375). En p. 355 cita a von Mangoldt (0.43200, 1.91662, 12.20375; T > 28.558) y Grossmann (0.29062, 1.7862, 6.13695; T > 50), y su propia cota de 1914 (T > 200).
- `401_Trudgian_2012_Improved_Upper_Bound_Argument_Zeta.pdf` — T. S. Trudgian, *An improved upper bound for the argument of the Riemann zeta-function on the critical line*, Math. Comp. 81 (2012) 1053–1061, doi:10.1090/S0025-5718-2011-02537-8. Thm. 1: |S(t)| ≤ 1.998 + 0.17 log t para t > t₀ > e.
- `147_Fujii_1974_Zeros_Dirichlet_L_Functions_I.pdf` — momentos de S(t+h)−S(t) (y de L(s,χ)) en intervalos cortos, con prueba; incondicional. Trans. AMS 196 (1974), DOI 10.1090/S0002-9947-1974-0349603-2
- `150_Fujii_1981_Zeros_Dirichlet_L_Functions_II_Corrections.pdf` — pruebas completas de consecuencias del teorema principal de Fujii 1974 (momentos de S(t+h)−S(t)), con correcciones a la parte I y a los artículos siguientes. Trans. AMS 267 (1981).
- `149_Fujii_1975_Distribution_Zeros_Zeta_Short_Intervals.pdf` — momentos de S(t+h)−S(t) en intervalos cortos (anuncio, sin pruebas). Bull. AMS 81 (1975), DOI 10.1090/S0002-9904-1975-13674-3
- `208_Hughes-Rudnick_2002_Linear_Statistics_Zeros_Zeta.pdf` — estadísticos lineales de ceros escalados; momentos gaussianos. arXiv:math/0208220
- `148_Fujii_1975_Difference_r_Consecutive_Ordinates_Zeros_Zeta.pdf` — momentos incondicionales de diferencias de r ordenadas consecutivas, muestreados en los ceros; conteo de r-gaps pequeños. Proc. Japan Acad. 51 (1975), DOI 10.3792/pja/1195518466
- `100_Conrey-TurnageButterbaugh_2018_r_Gaps_Between_Zeros_Zeta.pdf` — r-gaps, constantes explícitas bajo RH. arXiv:1708.00030
- `162_Gonek-Sahay_2024_Consecutive_Moderate_Gaps_Between_Zeros_Zeta.pdf` — gaps consecutivos moderados. arXiv:2412.15481
- `217_Inoue-Kobayashi-Toma_2026_Explicit_Extreme_Values_Argument_Zeta.pdf` — valores extremos explícitos de arg ζ; mejora Conrey–Turnage-Butterbaugh. arXiv:2510.14309
- `219_Ivic-Korolev_2018_Distribution_Values_Argument_Zeta.pdf` — distribución del signo de S(t): medida de {t∈[T,T+H]: S(t)>0} para T^{27/82+ε} ≤ H ≤ T.
- `263_Korolev_2016_Extreme_Values_S_Short_Intervals_Indian_J.pdf` — máximo y mínimo de S(t) en segmentos muy cortos de la recta crítica, bajo RH. Indian J. Pure Appl. Math. 47 (2016) 603–615, DOI 10.1007/s13226-016-0205-4
- `218_Inoue_2024_Note_On_r_Gaps_Between_Zeros_Zeta.pdf` — prueba del resultado anunciado por Selberg sobre r-gaps. arXiv:2303.06613
- `418_Zhao_2026_Density_Results_r_Gaps_Between_Zeros_Zeta.pdf` — resultados de densidad para r-gaps. arXiv:2603.17334
- `261_Korolev_2012_Gram_Law_Argument_Riemann_Zeta_Publ_Inst_Math.pdf` — ley de Gram y S(t) en los puntos de Gram; fórmulas de Selberg para momentos de Δ_n en intervalos cortos (Teorema 4.2). Publ. Inst. Math. 92(106) (2012), DOI 10.2298/PIM1206053K
- `262_Korolev_2012_Gram_Law_Riemann_Zeta.pdf` — ley de Gram, fórmulas de Selberg. arXiv:1011.3997
- `259_Korolev_2010_Gram_Law_Selberg_Conjecture_Zeros_Izv_Math.pdf` — ley de Gram y conjetura de Selberg sobre la distribución de los ceros. Izv. Math. 74 (2010) 743, DOI 10.1070/IM2010v074n04ABEH002506
- `260_Korolev_2011_Gram_Law_Argument_Riemann_Zeta_arXiv.pdf` — S(t) en los puntos de Gram; panorámica de los sentidos de "ley de Gram"; fórmulas de Selberg. arXiv:1106.0516
- `264_Korolev_2016_Gram_Law_Theory_Zeta_Part1_Proc_Steklov.pdf` — monografía (146 pág.) sobre la ley de Gram en la teoría de ζ, parte 1. Proc. Steklov Inst. Math. 292, suppl. 2 (2016) S1–S146, DOI 10.1134/S0081543816030019
- `224_Jerby_2023_New_Discriminant_Hardy_Z_Function_Corrected_Gram_Law.pdf` — discriminante Δ_n(a) de Z(t), ley de Gram corregida. arXiv:2310.14415
- `400_Trudgian_2008_Gram_Law_Fails_Positive_Proportion_Of_The_Time.pdf` — proporción positiva de fallos de la ley de Gram y de éxitos débiles. arXiv:0811.0883
- `140_Franca-LeClair_2014_Statistical_Properties_Riemann_Zeros_Explicit_Equation_nth_Zero.pdf` — ecuación para el n-ésimo cero con Lambert W (ỹ_n, sin puntos de Gram ni ley de Gram) y término arg ζ; reconstruye π(x) con ceros sintéticos. arXiv:1307.8395
- `141_Franca-LeClair_2014_Theory_Zeros_Riemann_Zeta_And_Other_L_Functions.pdf` — notas de curso: ceros de la línea crítica ↔ ceros del coseno, ecuación del n-ésimo cero, L-funciones. arXiv:1407.4358
- `143_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions_CNTP_Published.pdf` — versión publicada de la ecuación trascendente del n-ésimo cero (CNTP 9 (2015) 1–50).
- `281_LeClair_2016_Riemann_Hypothesis_Random_Walks_Zeta_Case.pdf` — producto de Euler truncado en N(t)<[t²], B_N(t)=O(√N) vía Kac, argumento heurístico de S(t)=O(1), modelo probabilístico de ceros y cero 10^100. arXiv:1601.00914
- `034_Bellotti-Wong_2025_Improved_Argument_Zero_Counting_Zeta.pdf` — cota explícita |N(T) − (T/2π)log(T/2πe)| ≤ 0.10076 log T + 0.24460 log log T + 8.08344. arXiv:2412.15470
- `103_Conrey_1989_More_Than_Two_Fifths_Zeros_Critical_Line.pdf` — Conrey, más de dos quintos de los ceros en la recta crítica. J. reine angew. Math. 399 (1989)
- `142_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions.pdf` — versión arXiv de las ecuaciones trascendentes para ceros individuales (publicada: `143_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions_CNTP_Published.pdf`). arXiv:1502.06003
- `187_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Riemann_Zeta.pdf` — cota explícita |N(T) − (T/2π)log(T/2πe)| ≤ 0.1038 log T + 0.2573 log log T + 9.3675. arXiv:2107.06506
- `402_Trudgian_2014_Improved_Upper_Bound_Argument_Zeta_II.pdf` — cota superior mejorada para S(T) en la recta crítica, II. arXiv:1208.5846v2 (el PDF lleva la plantilla de Math. Comp.); publicado en J. Number Theory 134 (2014) 280–292, doi:10.1016/j.jnt.2013.07.017. Lema 3: Phragmén–Lindelöf con logaritmos; con potencias distintas del logaritmo su prueba tiene un hueco, corregido por Fiori (§7).
- `039_Bennett-Martin-OBryant-Rechnitzer_2021_Counting_Zeros_Dirichlet_L_Functions.pdf` — M. A. Bennett, G. Martin, K. O'Bryant, A. Rechnitzer, *Counting zeros of Dirichlet L-functions*, arXiv:2005.02989v1 (2020); publicado en Math. Comp. 90 (2021) 1455–1482, doi:10.1090/mcom/3599. Cotas explícitas de N(T,χ) para conductor q > 1 y T ≥ 5/7; nueva cota de |L(s,χ)| para σ < −1/2. Fuente de la función 𝓔(T,d) del método de Backlund que usan Bellotti–Wong y `rvm_clock_envelope` (Teorema 3.5).

## 4. RMT, GUE/CUE y estadística de espaciados

- `044_Berry_1988_Semiclassical_Formula_Number_Variance_Riemann_Zeros.pdf` — varianza del número de ceros desde los primos: régimen universal GUE y régimen no universal por primos, separados por la escala τ*. doi:10.1088/0951-7715/1/3/001
- `329_Odlyzko_1987_Distribution_Spacings_Between_Zeros_Zeta.pdf` — **datos base**: 10^5 ceros y ceros 10^12+1…10^12+10^5, precisión 10^-8.
- `139_Forrester-Mays_2015_Finite_Size_Corrections_RMT_Odlyzko_Data.pdf` — correcciones de tamaño finito contra el dataset de Odlyzko. arXiv:1506.06531
- `061_Bornemann-Forrester-Mays_2017_Finite_Size_Effects_Spacing_Distributions.pdf` — efectos de tamaño finito en distribuciones de espaciado. arXiv:1608.04638
- `324_Nishigaki_2024_Consecutive_Level_Spacings_GUE_Ratio.pdf` — espaciados consecutivos GUE y su ratio, derivación ab initio. doi:10.1093/ptep/ptae120
- `325_Nishigaki_2025_Consecutive_Level_Spacings_CUE_Finite_Size_Zeta.pdf` — lo mismo para CUE, con correcciones finitas y ceros de ζ.
- `378_Shir-MartinezAzcona-Chenu_2025_Surmise_Level_Spacing_Beyond_Nearest.pdf` — surmise más allá del vecino inmediato. arXiv:2504.20134
- `052_Bohigas-Leboeuf-Sanchez_2001_Spectral_Spacing_Correlations.pdf` — autocovarianzas de espaciados como función de correlación discretizada.
- `138_Forrester-Lebowitz_2013_Local_CLT_Determinantal_Point_Processes.pdf` — TCL local para procesos determinantales. arXiv:1311.7126
- `225_Johansson_2001_Discrete_Orthogonal_Polynomial_Ensembles_Plancherel.pdf` — ensembles discretos de polinomios ortogonales.
- `240_Kargin_2013_Fluctuations_Riemann_Zeta_Zeros.pdf` — *On fluctuations of Riemann's zeta zeros*, arXiv:1203.5309, 25 pág. Fluctuaciones gaussianas de γ_k en torno a su posición predicha; ley conjunta de γ_k y γ_{k+x} con correlación (1-β)₊. **No confundir** con Kargin, *Statistical properties of zeta functions' zeros*, Probability Surveys 11 (2014), arXiv:1302.1452 — ese es el survey (soporte de Fourier en Montgomery, escalas, qué es local), y **no está en la biblioteca**.
- `130_Fazzari-Gerspach-Minelli_2025_Selberg_CLT_Weighted_Linear_Statistics_Zeta_Zeros.pdf` — TCL de Selberg ponderado por estadística local de ceros. arXiv:2507.04150
- `083_Cartier-Julia-Moussa-Vanhove_2006_Random_Matrices_Zeta_Dynamical_Systems.pdf` — actas *Frontiers in Number Theory, Physics and Geometry I*.
- `062_Borwein-Straub-Wan-Zudilin_2012_Densities_Short_Uniform_Random_Walks.pdf` — densidades de paseos aleatorios uniformes cortos (3–5 pasos); referencia para caminatas de fase. arXiv:1103.2995
- `101_ConreySnaith2008_2008_Communications_in_Number_Theory_and_Physics.pdf` — correlaciones de autovalores y ceros de Riemann (cocientes de polinomios característicos). CNTP (2008). arXiv:0803.2795
- `129_ErdosEtAl2012_2012_Spectral_statistics_of_Erd.pdf` — estadística espectral de grafos de Erdős–Rényi II: espaciados y autovalores extremos. arXiv:1103.3869
- `195_HeuslerEtAl2007_2007_Periodic_orbit_theory_of_level_correlations.pdf` — teoría de órbitas periódicas de las correlaciones de niveles. arXiv:nlin/0610053
- `319_MullerEtAl2005_2005_Periodic_orbit_theory_of_universality_in_quantum_chaos.pdf` — teoría de órbitas periódicas de la universalidad en caos cuántico. arXiv:nlin/0503052
- `248_Keating_2022_Hierarchical_Structure_Trace_Formula.pdf` — J. P. Keating, *Hierarchical structure in the trace formula*, arXiv:2205.13815v1 [nlin.CD] (2022), 10 pág., dedicado a M. Berry. Estructura jerárquica en cómo contribuyen las órbitas periódicas a la fórmula de traza de Gutzwiller, motivada por RMT y teoría de números; consecuencias para la distribución de valores de determinantes espectrales (análogo de los productos de Euler truncados y de la conjetura de Fyodorov–Hiary–Keating).
- `343_PillaiYin2014_2014_Universality_of_covariance_matrices.pdf` — universalidad de matrices de covarianza. Ann. Appl. Probab. 24 (2014), DOI 10.1214/13-AAP939

## 5. Criterio de Li–Weil y positividad

- `093_Coffey_2005_Polygamma_Theory_Li_Keiper_Constants_Riemann_Hypothesis.pdf` — constantes λ_k y c_n, teoría poligamma.
- `373_Sekatskii_2013_Generalized_Bombieri_Lagarias_Li_Criterion.pdf` — teorema de Bombieri–Lagarias generalizado y criterio de Li generalizado.
- `374_Sekatskii_2014_Generalized_Li_Criterion_Zeroes_Location.pdf` — primeras aplicaciones a la localización de ceros. arXiv:1304.7895
- (ver también `094_Coffey_2009_Certain_Sums_Over_Nontrivial_Zeta_Zeros.pdf`)
- `013_AriasdeReyna_2024_Explicit_Formula_Quasicrystal_Definition.pdf` — RH ⇔ cierta medida con Λ(n) y cosh(x/2) es una distribución temperada; definición de cuasicristal de Fourier. arXiv:2402.10604
- `021_BaezDuarte-Balazard-Landreau-Saias_2000_Notes_sur_la_fonction_zeta_de_Riemann_3.pdf` — Báez-Duarte–Balazard–Landreau–Saias, criterio de Nyman–Beurling (distancias). Adv. Math. 149 (2000), DOI 10.1006/aima.1999.1861
- `022_BaezDuarte2002_2002_BaezDuarte2002.pdf` — refuerzo del criterio de Nyman–Beurling. arXiv:math/0202141
- `024_Balazard-Saias-Yor_1999_Notes_Fonction_Zeta_Riemann_2_Transcription_VellaChemla.pdf` — ∫ log|ζ| sobre la recta crítica en términos de los ceros con Re ρ > 1/2. Adv. Math. 143 (1999); transcripción
- `096_Connes1998_1998_Connes1998.pdf` — Connes, fórmula de traza en geometría no conmutativa y ceros de ζ (espectro de absorción). arXiv:math/9811068
- `275_Lagarias2007_2007_Li_coefficients_for_automorphic_functions.pdf` — Lagarias, coeficientes de Li para L-funciones automorfas. Ann. Inst. Fourier 57 (2007)
- `362_RodgersTao2018_2018_RodgersTao2018.pdf` — Rodgers–Tao, la constante de de Bruijn–Newman es no negativa. arXiv:1801.05914
- `372_Sekatskii-Beltraminelli-Merlini_2012_Integrals_Logarithm_Zeta_RH.pdf` — igualdades con integrales de log ζ equivalentes a RH (teorema de Littlewood generalizado)
- `388_Suzuki2025Hilbert_2025_On_the_Hilbert_space_derived_from_the_Weil_distribution.pdf` — Suzuki, espacio de Hilbert derivado de la distribución de Weil. Canad. J. Math. (2025), DOI 10.4153/S0008414X25101739
- `407_Volchkov_1995_Equality_Equivalent_Riemann_Hypothesis_Russian.pdf` — Volchkov, igualdad equivalente a RH (en ruso; **sin capa de texto**)
- `408_Weil_1952_Formules_Explicites_Nombres_Premiers_Transcription_VellaChemla.pdf` — Weil, *Sur les « formules explicites »* (1952); transcripción
- `419_deBruijn1950_1950_The_roots_of_trigonometric_integrals.pdf` — de Bruijn, raíces de integrales trigonométricas (origen de la constante de de Bruijn–Newman). Duke Math. J. 17 (1950) 197–226, DOI 10.1215/S0012-7094-50-01720-0

## 6. Matrices aritméticas: Redheffer, Toeplitz multiplicativas, GCD, Hilbert

- `032_Barrett-Jarvis_1992_Spectral_Properties_Redheffer_Matrix.pdf` — det A_n = M(n); propiedades espectrales.
- `405_Vaughan_1996_Eigenvalues_Redheffer_Matrix_II.pdf` — estimaciones precisas de autovalores. doi:10.1017/S1446788700037654
- `409_Wilf_2004_Redheffer_Matrix_Partially_Ordered_Set.pdf` — permutaciones que contribuyen al determinante; permanente.
- `363_Roesler_1986_Riemann_Hypothesis_Eigenvalue_Problem.pdf` — RH como problema de autovalores de una matriz entera.
- `364_Roesler_1987_Riemann_Hypothesis_Eigenvalue_Problem_II.pdf` — continuación; distribución de autovalores.
- `202_Hilberdink_2006_Determinants_Multiplicative_Toeplitz_Matrices.pdf` — a_ij = f(i/j) con f multiplicativa; determinantes truncados.
- `204_Hilberdink_2015_Multiplicative_Toeplitz_Matrices_Riemann_Zeta.pdf` — conexión directa con ζ.
- `205_Hilberdink_2017_Singular_Values_Multiplicative_Toeplitz_Matrices.pdf` — valores singulares. doi:10.1080/03081087.2016.1204978
- `201_Hilberdink-Pushnitski_2023_Spectral_Asymptotics_LCM_Matrices.pdf` — asintótica espectral de matrices n^σ m^σ / [n,m]^τ. arXiv:2110.14323
- `290_Lindqvist-Seip_1998_Note_Greatest_Common_Divisor_Matrices.pdf` — formas cuadráticas de matrices GCD como normas L².
- `072_Brevig-Perfekt-Seip-Siskakis-Vukotic_2016_Multiplicative_Hilbert_Matrix.pdf` — la matriz de Hilbert multiplicativa. arXiv:1411.7294
- `342_Perfekt-Pushnitski_2018_Spectrum_Multiplicative_Hilbert_Matrix.pdf` — su espectro. arXiv:1705.01959
- `328_Odlyzko-TeRiele_1985_Disproof_Mertens_Conjecture.pdf` — refutación de la conjetura de Mertens.
- `238_Kannan-Bachem_1979_Polynomial_Algorithms_Smith_Hermite_Normal_Forms.pdf` — algoritmos polinómicos para formas normales.
- `273_Labahn-Neiger-Zhou_2018_Hermite_Normal_Form_Polynomial_Matrix.pdf` — forma normal de Hermite para matrices polinómicas. arXiv:1607.04176
- `367_Rota_1964_Foundations_Combinatorial_Theory_Mobius_Functions.pdf` — funciones de Möbius sobre posets.
- `296_Matiyasevich2007a_1983_Hidden_Life_of_Riemann_s_Zeta_Function_1_Arrow_Bow_and_Targets.pdf` — Matiyasevich, RH reformulada como enunciados sobre autovalores de matrices (1). arXiv:0707.1983
- `297_Matiyasevich2007b_2007_Hidden_Life_of_Riemann_s_Zeta_Function_2_Electrons_and_Trains.pdf` — Matiyasevich, ídem (2). arXiv:0709.0028
- `309_Montgomery-Vaughan_1974_Hilberts_Inequality.pdf` — Montgomery–Vaughan, desigualdad de Hilbert generalizada

## 7. Sumas exponenciales y métodos de Van der Corput / Vinogradov

- `167_Graham-Kolesnik_1991_Computing_Optimal_Exponent_Pairs.pdf` — cálculo de pares de exponentes óptimos (cap. 5).
- `168_Graham-Kolesnik_1991_Simplest_Van_Der_Corput_Estimates.pdf` — estimaciones vdC de primera y segunda derivada (cap. 2).
- `065_Bourgain_2017_Decoupling_Exponential_Sums_Riemann_Zeta.pdf` — desacoplamiento; ζ(1/2+it) ≪ t^{13/84+ε}; par de exponentes (13/84, 55/84). arXiv:1408.5794v2, J. Amer. Math. Soc. 30 (2017)
- `355_Revers_2026_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf` — M. Revers, *A new improved explicit estimate for ζ(1/2+it)*, arXiv:2602.05614v1 (2026), 40 pág.; preprint, sin arbitrar. |ζ(1/2+it)| ≤ 0.611 t^{1/6} log t para t ≥ 3 y ≤ 0.566 t^{1/6} log t para t ≥ 8.97·10^17 (Thm. 1.1), por van der Corput explícito más cálculo con aritmética de intervalos (Lema 2.1, §3.4). Mejora el 0.618 de Hiary–Patel–Yang 2024 y completa detalles que, según el autor, faltan en su prueba; recuerda (p. 3) que el error del lema de Cheng–Graham (1/π en vez de 2/π) afecta a Hiary 2016 y a Platt–Trudgian 2015. Fuente alternativa del dato en σ = 1/2 de `rvm_clock_envelope` (Teorema 3.3(a)).
- `198_Hiary-Patel-Yang_2024_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf` — G. A. Hiary, D. Patel, A. Yang, *An improved explicit estimate for ζ(1/2+it)*, J. Number Theory 256 (2024) 195–217, doi:10.1016/j.jnt.2023.09.003. |ζ(1/2+it)| ≤ 0.618 t^{1/6} log t para t ≥ 3 (Thm. 1.1), con una versión nueva del lema de Kusmin–Landau; recupera y mejora el 0.63 de Hiary 2016, afectado por el error del lema de Cheng–Graham. Dato en σ = 1/2 de `rvm_clock_envelope` (Teorema 3.3(a)).
- `336_Patel-Yang_2024_Explicit_Sub_Weyl_Bound_Zeta_Critical_Line.pdf` — D. Patel, A. Yang, *An explicit sub-Weyl bound for ζ(1/2+it)*, J. Number Theory 262 (2024) 301–334, doi:10.1016/j.jnt.2024.03.011. |ζ(1/2+it)| ≤ 66.7 t^{27/164} para t ≥ 3; según el resumen, con sus otros resultados son las cotas más finas conocidas en σ = 1/2 para t ≥ exp(61).
- `411_Yang_2024_Explicit_Bounds_Zeta_Critical_Strip_Zero_Free_Region.pdf` — A. Yang, *Explicit bounds on ζ(s) in the critical strip and a zero-free region*, J. Math. Anal. Appl. 534 (2024) 128124, doi:10.1016/j.jmaa.2024.128124. |ζ(σ_k+it)| ≤ 1.546 t^{1/(2^k−2)} log t con σ_k = 1 − k/(2^k−2), k ≥ 4, t ≥ 3 (Thm. 1.1), por un test explícito de la k-ésima derivada (proceso A^{k−2}B de van der Corput); región libre de ceros de tipo Littlewood σ > 1 − log log|t|/(21.233 log|t|), |t| ≥ 3. **Aviso:** en §3.1 (3 ≤ t ≤ T_k) el Lema 3.1 cita el de Trudgian con log|Q+s| donde va |Log(Q+s)|, y con (3.12) tal como está impresa A(3) = 1.5638, no ≤ 1.4747. Rehecho con aritmética de intervalos para 4 ≤ k ≤ 9, la constante en ese tramo es ≤ 1.878 (`rvm_clock_envelope` v10, Obs. 4.5(ii)). El tramo t ≥ T_k (§3.2) no se ve afectado.
- `337_Patel_2022_Explicit_Upper_Bound_Zeta_1_Line.pdf` — D. Patel, *An explicit upper bound for |ζ(1+it)|*, arXiv:2009.00769v1 (2020); publicado en Indag. Math. 33 (2022) 1012–1032, doi:10.1016/j.indag.2022.04.007. |ζ(1+it)| ≤ min(log t, ½ log t + 1.93, ⅕ log t + 44.02) para t ≥ 3 (Thm. 1.1). La introducción es un buen repaso de la lista histórica de cotas de ζ. Dato en σ = 1 de `rvm_clock_envelope` (Teorema 3.3(c)).
- `197_Hiary-Leong-Yang_2025_Explicit_Bounds_Zeta_1_Line.pdf` — G. A. Hiary, N. Leong, A. Yang, *Explicit bounds for the Riemann zeta-function on the 1-line*, arXiv:2306.13289v2 (2024); publicado en Funct. Approx. Comment. Math. 73 (2025) 53–89, doi:10.7169/facm/240711-13-8. |ζ(1+it)| ≤ 1.731 log t/log log t (Thm. 1) y 1/|ζ(1+it)| ≤ 431.7 log t/log log t (Thm. 2), ambos para t ≥ 3; en §2, de pasada, |ζ(1+it)| ≤ log t − 0.45 para t ≥ 3.
- `036_Bellotti_2024_Explicit_Bounds_Zeta_New_Zero_Free_Region.pdf` — C. Bellotti, *Explicit bounds for the Riemann zeta function and a new zero-free region*, J. Math. Anal. Appl. 536 (2024) 128249, doi:10.1016/j.jmaa.2024.128249. |ζ(σ+it)| ≤ 70.6995 |t|^{4.43795(1−σ)^{3/2}} log^{2/3}|t| para 1/2 ≤ σ ≤ 1, |t| ≥ 3 (Thm. 1.1); región libre de ceros de Korobov–Vinogradov con constante 53.989 (Thm. 1.2). El 58.096 que citan Bellotti–Wong y Fiori para |ζ(1+it)| no aparece aquí (Thm. 1.1 da 70.6995 en σ = 1): es el Lema 5 de Leong, `283_Leong_2024_Explicit_Estimates_Log_Derivative_Reciprocal_Zeta.pdf`.
- `313_Mossinghoff-Trudgian-Yang_2022_Explicit_Zero_Free_Regions_Riemann_Zeta.pdf` — M. J. Mossinghoff, T. S. Trudgian, A. Yang, *Explicit zero-free regions for the Riemann zeta-function*, arXiv:2212.06867v1 (13-12-2022), 27 pág.; versión publicada no comprobada. No hay ceros en σ ≥ 1 − 1/(55.241 (log|t|)^{2/3} (log log|t|)^{1/3}) para |t| ≥ 3, ni en σ ≥ 1 − 1/(5.558691 log|t|) para |t| ≥ 2 (resumen); mejora la región de Ford 2000 (57.54, 49.13). Polinomios trigonométricos no negativos.
- `283_Leong_2024_Explicit_Estimates_Log_Derivative_Reciprocal_Zeta.pdf` — N. Leong, *Explicit estimates for the logarithmic derivative and the reciprocal of the Riemann zeta function*, arXiv:2405.04869v5 (30-1-2026; v1 de 8-5-2024), 31 pág. Lema 5 (p. 8): |ζ(1+it)| ≤ 58.096 (log|t|)^{2/3} para |t| ≥ 3, con el argumento de Bellotti 2024 y otros parámetros (la cota que Bellotti–Wong (2.1) atribuyen a Bellotti). Cotas explícitas de |ζ'/ζ| y |1/ζ| cerca de σ = 1.
- `351_Rademacher_1959_Phragmen_Lindelof_Theorem_Applications.pdf` — H. Rademacher, *On the Phragmén–Lindelöf theorem and some applications*, Math. Z. 72 (1959) 192–204, doi:10.1007/BF01162949. Principio de Phragmén–Lindelöf en una banda con cotas A|Q+s|^α y B|Q+s|^β en las dos rectas (Teorema 2): la versión que usan las cotas explícitas de ζ y de las funciones L.
- `133_Fiori_2025_Note_Phragmen_Lindelof_Theorem.pdf` — A. Fiori, *A note on the Phragmén–Lindelöf theorem*, arXiv:2502.13282v3 (6-1-2026), preprint. Generaliza el teorema de Rademacher (Thm. 1) y corrige el Lema 3 de Trudgian 2014, cuya prueba falla con potencias distintas del logaritmo: según la Obs. 4, |log(Q+s)| no es monótono en σ. El Cor. 3 es la versión con la misma potencia de |log(Q+s)| en las dos rectas. En §4 aplica el resultado a ζ en [1, 2] y en [5/7, 1]. Es el Teorema 3.4 de `rvm_clock_envelope`.
- `252_Kinnunen_1997_Hardy_Littlewood_Maximal_Function_Sobolev_Function.pdf` — análisis armónico auxiliar: maximal de Hardy–Littlewood acotado en W^{1,p}, |D Mu| ≤ M Du. Israel J. Math. 100 (1997)
- `214_Huxley_1989_Exponential_Sums_Riemann_Zeta.pdf` — método de Bombieri–Iwaniec, trabajo Huxley–Watt en contexto.
- `239_Karatsuba-Voronin_1992_Vinogradov_Method_Riemann_Zeta.pdf` — método de Vinogradov, teorema del valor medio (cap. IV).
- `031_Baricz-Laforgia-Pogany_2015_Van_Der_Corput_Inequalities_Bessel.pdf` — desigualdades vdC para funciones de Bessel. doi:10.1080/10652469.2014.975419
- `250_Kelly-Le_2018_Van_Der_Corput_Sets_Compact_Groups.pdf` — conjuntos vdC en grupos compactos. doi:10.1007/s00013-017-1136-y
- `268_Kowalski_2021_Exponential_Sums_Finite_Fields_Elementary.pdf` — métodos elementales, curso ETH.
- `269_Kowalski_2021_Exponential_Sums_Finite_Fields_II.pdf` — métodos cohomológicos.
- `229_Jun-Lee_2014_Dedekind_And_Exponential_Sums.pdf` — equidistribución de sumas de Dedekind generalizadas. doi:10.1016/j.jnt.2013.10.020
- `326_Norvidas_2011_Entire_Functions_Exponential_Sums.pdf` — espacios de Bernstein y sumas exponenciales.
- `137_Ford_2002_Vinogradov_Integral_Bounds_Riemann_Zeta.pdf` — Ford, integral de Vinogradov y cotas para ζ; región libre de ceros. arXiv:1910.08209
- `172_GrepstadEtAl2019_1909_On_the_asymptotic_behaviour_of_the_sine_product.pdf` — comportamiento asintótico del producto de senos Π|2 sin πrα|. arXiv:1909.00980
- `178_Guth-Maynard_2026_New_Large_Value_Estimates_Dirichlet_Polynomials.pdf` — Guth–Maynard, nuevas estimaciones de valores grandes de polinomios de Dirichlet. arXiv:2405.20552
- `287_LiYang2023_2023_An_improvement_on_Gauss_s_circle_problem_and_Dirichlet_s_divisor_problem.pdf` — mejora en el problema del círculo de Gauss y del divisor de Dirichlet (Bombieri–Iwaniec). arXiv:2308.14859

## 8. Funciones multiplicativas: Liouville, Möbius, Chowla

- `301_Matomaki-Radziwill_2016_Multiplicative_Functions_Short_Intervals.pdf` — **el teorema MR**: promedios cortos vs. largos. doi:10.4007/annals.2016.183.3.6
- `299_Matomaki-Radziwill_2015_Liouville_Short_Intervals.pdf` — prueba corta y autocontenida para λ(n). arXiv:1502.02374
- `298_Matomaki-Radziwill-Tao_2015_Averaged_Chowla_Conjecture.pdf` — Chowla promediada. arXiv:1503.05121
- `183_Harman-Pintz-Wolke_1985_Mobius_And_Liouville_Functions.pdf` — nota sobre valores de μ y λ.
- `084_Cassaigne-Ferenczi-Mauduit-Rivat-Sarkozy_1999_Liouville_Pseudorandom_Sequences.pdf` — λ como sucesión binaria pseudoaleatoria.
- `108_Croot_2003_Oscillations_Multiplicative_PlusMinusOne.pdf` — oscilaciones de funciones multiplicativas ±1. [texto extraído ilegible]
- `169_Granville-Soundararajan_2003_Decay_Of_Mean_Values.pdf` — decaimiento de valores medios. [texto extraído ilegible]
- `370_Sawin_2022_Mobius_Cancellation_Polynomial_Sequences.pdf` — cancelación de Möbius en F_q[u], análogo de Chowla. doi:10.1007/s00222-022-01115-y
- `123_Drmota_2009_Sum_Of_Digits_Of_Primes.pdf` — suma de dígitos de los primos (charla, con Mauduit y Rivat).
- `001_AbercrombieBanksShparlinski2009_2009_Arithmetic_functions_on_Beatty_sequences.pdf` — funciones aritméticas sobre sucesiones de Beatty. Acta Arith. 136 (2009), DOI 10.4064/aa136-1-6
- `018_Aymone-Sidoravicius_2017_Partial_Sums_Biased_Random_Multiplicative_Functions.pdf` — sumas parciales de funciones multiplicativas aleatorias sesgadas. arXiv:1412.1157
- `019_Aymone2020_2020_A_note_on_multiplicative_functions_resembling_the_M_bius_function.pdf` — funciones multiplicativas que se parecen a μ con M_f(x)=o(√x). arXiv:1908.11014
- `042_BergelsonKulagaPrzymusLemanczykRichter2019_2019_Discrete_Contin_Dyn_Syst.pdf` — generalización del criterio de ortogonalidad de Kátai. arXiv:1705.07322
- `047_Bjorner_2011_Cell_Complex_Number_Theory.pdf` — Björner, complejo simplicial de los libres de cuadrados; característica de Euler = función de Mertens. arXiv:1101.5704
- `066_Bourgain_undated_On_the_Fourier_Walsh_spectrum_of_the_M_obius_function.pdf` — Bourgain, espectro de Fourier–Walsh de μ. arXiv:1112.1423
- `071_BretcheDressTenenbaum2020_2020_Mathematika.pdf` — de la Bretèche–Dress–Tenenbaum, la suma M(n,z)=Σ_{d|n, d≤z} μ(d). arXiv:1902.09956
- `105_Coons2010_2010_On_the_multiplicative_Erd_s_discrepancy_problem.pdf` — problema de discrepancia de Erdős multiplicativo. arXiv:1003.5388
- `144_Frantzikinakis2020_1908_Correlations_of_multiplicative_functions_along_deterministic_and_independent_sequences.pdf` — correlaciones de funciones multiplicativas sobre sucesiones deterministas e independientes (2020; el «1908» del nombre es el id arXiv). arXiv:1908.02732
- `185_Harper_2020_Moments_Random_Multiplicative_Functions_I.pdf` — Harper, momentos bajos de funciones multiplicativas aleatorias; caos multiplicativo crítico. arXiv:1703.06654
- `192_HelfgottRadziwill2021_undated_HelfgottRadziwill2021.pdf` — Helfgott–Radziwiłł, expansión, divisibilidad y paridad. arXiv:2103.06853
- `232_Kaczorowski-Pintz_1986_Oscillatory_Properties_Arithmetical_Functions_I.pdf` — Kaczorowski–Pintz, propiedades oscilatorias de funciones aritméticas I. Acta Math. Hung. 48 (1986)
- `265_Kotnik-vandeLune_2004_Order_Mertens_Function.pdf` — Kotnik–van de Lune, orden de la función de Mertens (experimento numérico sobre M(x)/√x)
- `282_LeeLeong2024_2024_New_explicit_bounds_for_the_Mertens_function_and_the_reciprocal_of_the_Riemann_zeta_function.pdf` — cotas explícitas incondicionales para M(x) y para 1/ζ en la banda crítica. arXiv:2208.06141
- `292_Liu2022_2022_Multiplicative_functions_resembling_the_M_bius_function.pdf` — funciones multiplicativas parecidas a μ: resultados O y Ω. arXiv:2205.00972
- `302_Matomaki-Shao-Tao-Teravainen_2023_Higher_Uniformity_Arithmetic_Functions.pdf` — uniformidad superior de μ, Λ y d_k en intervalos cortos. arXiv:2204.03754
- `303_Matomaki-Teravainen_2023_Mobius_Function_All_Short_Intervals.pdf` — μ en todos los intervalos cortos, Σ_{x<n≤x+x^θ} μ(n)=o(x^θ) para θ>0.55. arXiv:1911.09076
- `306_MelottiSaias2020_2020_On_path_partitions_of_the_divisor_graph.pdf` — particiones en caminos del grafo de divisores. arXiv:1807.07783
- `307_Mirsky_1949_Frequency_Pairs_Square_Free_Numbers_Given_Difference.pdf` — Mirsky, frecuencia de pares de libres de cuadrados con diferencia dada (1949)
- `314_MossinghoffOliveiraTrudgian2021_2021_The_distribution_of_k_free_numbers.pdf` — distribución de los k-libres: error R_k(x). arXiv:1912.04972
- `318_Muellner2017_2017_Automatic_sequences_fulfill_the_Sarnak_conjecture.pdf` — las sucesiones automáticas cumplen la conjetura de Sarnak. arXiv:1602.03042
- `321_MussardoLeClair2021_2021_Randomness_of_M_obius_coefficients_and_Brownian_motion_growth_of_the_Mertens_function_and_the_Riemann_hypothes.pdf` — Mussardo–LeClair, aleatoriedad de μ, movimiento browniano y crecimiento de M(x). arXiv:2101.10336
- `323_Ng2004_2004_Proc_London_Math_Soc.pdf` — Ng, distribución de M(x) bajo RH y otras hipótesis. arXiv:math/0310381
- `327_Nunes2015_2015_Journal_of_Number_Theory.pdf` — libres de cuadrados en progresiones aritméticas. arXiv:1402.0684
- `344_Pintz_2026_Oscillation_Mobius_Function_Zeta_Zeros.pdf` — Pintz, oscilación de M(x) y ceros de ζ. arXiv:2608.24878
- `383_Soundararajan_2009_Partial_Sums_Mobius_Function.pdf` — Soundararajan, sumas parciales de μ: M(x) bajo RH. arXiv:0705.0723
- `390_Tao-Teravainen_2018_Odd_Order_Logarithmically_Averaged_Chowla.pdf` — Tao–Teräväinen, casos de orden impar de Chowla con media logarítmica. arXiv:1710.02112
- `391_Tao-Teravainen_2019_Structure_Logarithmically_Averaged_Correlations.pdf` — Tao–Teräväinen, estructura de las correlaciones logarítmicas; Chowla y Elliott. arXiv:1708.02610
- `393_Tao_2016_Logarithmically_Averaged_Chowla_Elliott_Two_Point.pdf` — Tao, Chowla y Elliott logarítmicos para correlaciones de dos puntos. arXiv:1509.05422
- `396_Tenenbaum_2017_Generalized_Mertens_Sums.pdf` — Tenenbaum, sumas de Mertens generalizadas. arXiv:1910.02781

## 9. Números smooth e intervalos cortos

- `170_Granville_2008_Smooth_Numbers_Survey.pdf` — survey de referencia (MSRI).
- `025_Balog_1987_Integers_Without_Large_Prime_Factors.pdf` — Astérisque 147-148, pp. 27-31.
- `145_Friedlander-Granville_1993_Smoothing_Smooth_Numbers.pdf` — [texto extraído ilegible]
- `109_Croot_2007_Smooth_Numbers_Short_Intervals.pdf` — exponente 3/(14√e)+ε.
- `304_Matomaki_2010_Smooth_Numbers_Short_Intervals.pdf` — exponente 1/(5√e)+ε en [x, x+C√x].
- `305_Matomaki_2016_Smooth_Numbers_Short_Intervals_II.pdf` — intervalo √x(log x)^{7/3+δ}.
- `384_Soundararajan_2010_Smooth_Numbers_Short_Intervals.pdf` — bajo RH, x^ε-smooth en [x, x+C(ε)√x]. arXiv:1009.1591

## 10. Formas modulares, L-funciones y momentos

- `410_Xylouris_2011_Nullstellen_Dirichletschen_L_Funktionen_Kleinste_Primzahl.pdf` — T. Xylouris, *Über die Nullstellen der Dirichletschen L-Funktionen und die kleinste Primzahl in einer arithmetischen Progression*, tesis, Bonn, 2011 (Bonner Math. Schriften 404). Constante de Linnik L = 5 (Kap. 6). No es la tesis de Grossmann (1913).
- `184_Harper_2013_Conditional_Bounds_Zeta_Moments.pdf` — bajo RH, momentos 2k-ésimos ≪ T log^{k²}T. arXiv:1305.4618
- `230_Jutila_1977_Zero_Density_Estimates_L_Functions.pdf` — M. Jutila, *Zero-density estimates for L-functions*, Acta Arithmetica **XXXII** (1977), pp. 55–62; completo, en 5 hojas a doble página. Método de Halász–Montgomery para mejorar Ingham en σ > 3/4; el corolario da N(α,q,χ) con A(α)=2 para α ≥ 21/26 = 0.8076…, 7/9 y 11/14 = 0.7857… según k.
- `152_Gallagher_1970_Large_Sieve_Density_Estimate_Near_Sigma_1.pdf` — P. X. Gallagher, *A large sieve density estimate near σ = 1*, Invent. Math. **11** (1970), 329–339, doi:10.1007/BF01403187; 11 pág. Fuente del teorema de los números primos de Gallagher (Teorema 7) usado en (I6) de rh_stepwise.
- `315_Motohashi_1977_On_Gallaghers_Prime_Number_Theorem.pdf` — Y. Motohashi, *On Gallagher's prime number theorem*, Proc. Japan Acad. **53**, Ser. A (1977), 50–52, doi:10.3792/pjaa.53.50; 3 pág. Versión con el factor min(1, δ log x) del cero excepcional; OCR defectuoso en fórmulas (mirar la página).
- `316_Motohashi_1978_Primes_in_Arithmetic_Progressions.pdf` — Y. Motohashi, *Primes in arithmetic progressions*, Invent. Math. **44** (1978), 163–178, doi:10.1007/BF01390349; 16 pág. Demostración completa del teorema de Gallagher en el caso con carácter excepcional.
- `352_Radziwill-Soundararajan_2015_Quadratic_Twists_Central_L_Values.pdf` — momentos y distribución de valores centrales. arXiv:1403.7067
- `157_Ghosh-Sarnak_2012_Real_Zeros_Hecke_Cusp_Forms.pdf` — ceros reales de formas cuspidales de Hecke. arXiv:1103.3262
- `284_Lester-Matomaki-Radziwill_2015_Small_Scale_Zeros_Modular_Forms.pdf` — ceros y masa a escala pequeña. arXiv:1501.01292
- `300_Matomaki-Radziwill_2015_Sign_Changes_Hecke_Eigenvalues.pdf` — cambios de signo de λ_f(n). arXiv:1405.7671
- `279_Lau-Liu-Wu_2010_Symmetric_Square_L_Function_Coefficients.pdf` — resultados Ω± para el cuadrado simétrico.
- `267_Kowalski-Robert-Wu_2007_Small_Gaps_And_B_Free_Numbers.pdf` — no existencia de gaps en series de formas modulares.
- `098_Conrad_2005_Partial_Euler_Products_Critical_Line.pdf` — Conrad, productos de Euler parciales en la recta crítica (de Birch–Swinnerton-Dyer a RH). Canad. J. Math. 57 (2005)
- `159_Goldfeld_1982_Produits_Partiels_Euleriens_Courbes_Elliptiques.pdf` — Goldfeld, productos parciales eulerianos de curvas elípticas. C. R. Acad. Sci. Paris 294 (1982)
- `164_Gonek_2012_Finite_Euler_Products_Riemann_Hypothesis.pdf` — Gonek, productos de Euler finitos y RH; modelo ζ_X = P_X + χP_X(1−s). Trans. AMS 364 (2012) 2157–2191, DOI 10.1090/S0002-9947-2011-05546-7
- `158_Ghosh_2022_Statistics_Approximations_Zeros_Truncated_Symmetrized_Euler_Products.pdf` — A. Ghosh, *Report: Statistics of approximations to zeroes of ζ-function via truncated symmetrized Euler products*, arXiv:2211.11042v2 (2022), 24 pág.; informe, sin arbitrar. Ceros de la ζ_X de Gonek 2012: distancia entre ceros aproximados y ceros reales con X fijo (§1) y con X ≈ t/2π (§3.1); heurística vía F_X y sus pendientes casi constantes cerca de las ordenadas γ (§3.2).
- `377_Sheth_2025_Euler_Products_Centre_Chebyshev_Bias.pdf` — Sheth, productos de Euler en el centro y sesgo de Chebyshev. Math. Proc. Camb. Phil. Soc. 179 (2025), DOI 10.1017/S0305004125000234
- `011_Arguin-Bourgade-Radziwill_2020_Fyodorov_Hiary_Keating_Conjecture_I.pdf` — L.-P. Arguin, P. Bourgade, M. Radziwiłł, *The Fyodorov–Hiary–Keating Conjecture. I*, arXiv:2007.00988v2 (2020), 49 pág. Incondicional: cota superior del máximo de |ζ| en intervalos cortos, medida ≪ y e^{-2y}. Esquema iterativo multiescala con barreras; §7 *Decoupling and second moment* (aproximación de indicadores por polinomios de Dirichlet, comparación con modelo aleatorio), §8 *Decoupling and twisted fourth moment*, Apéndice A sumas sobre primos. Fuente del desacoplo de escalas de primos.
- `012_Arguin-Bourgade-Radziwill_2023_Fyodorov_Hiary_Keating_Conjecture_II.pdf` — mismos autores, *The Fyodorov–Hiary–Keating Conjecture. II*, arXiv:2307.00982v1 (2023), 41 pág. Incondicional: cota inferior; tensión de max log|ζ| − (log log T − ¾ log log log T); §3 *Approximations by Gaussian random walks*; Lema 5: aproximación integral de ζ por producto de Euler finito directamente en la recta crítica.

## 11. Determinantes de Hankel y valores de ζ

- `189_Haynes-Zudilin_2015_Hankel_Determinants_Zeta_Values.pdf` — asintótica de Hankel con ζ(an+b); aplicación diofántica. arXiv:1510.01901
- `308_Monien_2009_Hankel_Determinants_Dirichlet_Series.pdf` — determinantes de Hankel de series de Dirichlet. arXiv:0901.1883
- `131_FazziGuglielmiMarkovsky2021_2021_A_gradient_system_approach_for_Hankel_structured_low_rank_approximation.pdf` — enfoque de sistema gradiente para aproximación de bajo rango con estructura de Hankel. arXiv:2002.06621
- `385_StampachStovicek2020_2020_On_Hankel_matrices_commuting_with_Jacobi_matrices_from_the_Askey_scheme.pdf` — matrices de Hankel que conmutan con matrices de Jacobi del esquema de Askey. arXiv:1911.07059

## 12. Verificación numérica y cálculo

- `347_Platt-Trudgian_2021_RH_True_Up_To_3e12.pdf` — RH verificada rigurosamente (aritmética de intervalos) hasta altura 3·10^12. arXiv:2004.09765
- `379_Sidi_2003_Riemann_And_Generalized_Zeta_Extrapolation.pdf` — extrapolación numérica de ζ (apéndice E).
- (ver también `329_Odlyzko_1987_Distribution_Spacings_Between_Zeros_Zeta.pdf` y `328_Odlyzko-TeRiele_1985_Disproof_Mertens_Conjecture.pdf`)
- `069_Brent2018_2019_On_asymptotic_approximations_to_the_log_Gamma_and_Riemann_Siegel_theta_functions.pdf` — Brent, cotas del error en las aproximaciones asintóticas de log Γ y de la θ de Riemann–Siegel (reloj RvM). arXiv:1609.03682
- `070_Brent_1979_Zeros_Riemann_Zeta_Critical_Strip.pdf` — Brent, ceros de ζ en la banda crítica (verificación, 1979); **sin capa de texto**
- `078_Buthe2014_2015_A_method_for_proving_the_completeness_of_a_list_of_zeros_of_certain_functions.pdf` — Büthe, método para probar la completitud de una lista de ceros (extensión del método de Turing). arXiv:1308.6704
- `106_Corless-Gonnet-Hare-Jeffrey-Knuth_1996_Lambert_W_Function.pdf` — Corless–Gonnet–Hare–Jeffrey–Knuth, la función W de Lambert (inversión del reloj). Adv. Comput. Math. 5 (1996)
- `191_Helfgott-Thompson_2023_Summing_Mobius_Faster_Elementary_Algorithm.pdf` — Helfgott–Thompson, algoritmo elemental más rápido para M(x). arXiv:2101.08773
- `209_Hurst2026_2026_Practical_computations_of_the_Mertens_function_M_10.pdf` — Hurst, cálculo de M(10^24) y M(10^25). arXiv:2607.07566
- `210_Hurst_2018_Computations_Mertens_Function_Improved_Bounds.pdf` — Hurst, cálculos de M(x) y cotas mejoradas de la conjetura de Mertens. arXiv:1610.08551
- `212_Hutchinson_1925_Roots_Riemann_Zeta_Function.pdf` — Hutchinson, raíces de ζ (cálculo de ceros, ley de Gram). Trans. AMS 27 (1925)
- `226_Johansson_2017_Arb_Arbitrary_Precision_Interval_Arithmetic.pdf` — Johansson, Arb: aritmética de intervalos de precisión arbitraria. arXiv:1611.02831
- `227_Johansson_2018_Numerical_Integration_Ball_Arithmetic.pdf` — Johansson, integración numérica en aritmética de bolas. arXiv:1802.07942
- `348_Platt_2017_Isolating_Nontrivial_Zeros_Zeta.pdf` — Platt, aislamiento de ceros no triviales de ζ. Math. Comp., DOI 10.1090/mcom/3198

## 13. Tratados, monografías y panorámicas

- `181_Hardy-Littlewood-Polya_1934_Inequalities.pdf` — G. H. Hardy, J. E. Littlewood, G. Pólya, *Inequalities*, Cambridge University Press, **1.ª edición, 1934**. Cap. X, Rearrangements; §10.12 (pp. 276–278) define el reordenamiento en orden decreciente como inversa de la función de distribución.
- `289_Lieb-Loss_2001_Analysis_Second_Edition.pdf` — E. H. Lieb, M. Loss, *Analysis*, 2.ª ed., Grad. Stud. Math. 14, AMS, 2001, doi:10.1090/gsm/014. Thm. 1.14, principio de la bañera (p. 28).
- `371_Schechter_2002_Principles_Functional_Analysis_Second_Edition.pdf` — M. Schechter, *Principles of Functional Analysis*, 2.ª ed., Grad. Stud. Math. 36, AMS, 2002.
- `272_LMS_2015_Atle_Selberg_Obituary.pdf` — necrológica de Atle Selberg (London Mathematical Society; el PDF no lleva autor y es de 7-4-2015), con su lista de publicaciones; [15] es *Contributions to the theory of the Riemann zeta-function*, Arch. Math. Naturvid. 48 (1946) no. 5, 89–155. No enuncia los momentos de S(t).
- `365_Rosser-Schoenfeld_1962_Approximate_Formulas_Functions_Prime_Numbers.pdf` — J. B. Rosser, L. Schoenfeld, *Approximate formulas for some functions of prime numbers*, Illinois J. Math. 6 (1962) 64–94, doi:10.1215/ijm/1255631807. Cotas explícitas de θ, ψ, π(x), p_n. No contiene la cota de N(T) de Rosser 1941.
- `358_Riemann-Wilkins_1859_Prime_Counting_English_Translation.pdf` — **el texto de Riemann**, en alemán (original de 1859 transcrito por D. R. Wilkins, 10 páginas; no es una traducción al inglés pese al nombre del fichero). La inversión de Möbius para π y la serie Li(x) − ½Li(x^{1/2}) − ⅓Li(x^{1/3}) − ⅕Li(x^{1/5}) + ⅙Li(x^{1/6}) − … están en las págs. 8–9.
- `397_Titchmarsh-HeathBrown_1986_Theory_Riemann_Zeta_Function.pdf` — el tratado estándar. 2ª edición revisada por D. R. Heath-Brown, Clarendon Press. 418 hojas que llegan hasta la página impresa 412; las *Further references* de Heath-Brown terminan en Weil, así que el escaneo está completo.
- `220_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf` — Wiley 1985, edición original. 538 pág. escaneadas; **con capa OCR desde 2026-08-19**, ya es grepeable. Completo (el índice de materias llega hasta las entradas en Z). No incluye erratas: usar `ERRATA_Ivic.md`.
- `222_Ivic_2003_Riemann_Zeta_Dover_Reprint.pdf` — **mismo libro que `220_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf`**. Dover 2003, *unabridged republication* de Wiley 1985: cuerpo y paginación idénticos, no es una edición revisada. Lo único que añade es la lista de erratas en pág. xvii–xix (PDF 15–17), transcrita en `ERRATA_Ivic.md`. Completo; con capa OCR desde 2026-08-19.
- `127_Edwards_1974_Riemanns_Zeta_Function.pdf` — **ESCANEO INCOMPLETO**. Reimpresión Dover 2001 del original de Academic Press 1974. El PDF tiene 135 hojas que cubren las páginas impresas **1–122 de 311** (desfase: hoja PDF ≈ página impresa + 13).
  - **Sí está**: cap. 1 el paper de Riemann (p. 1), cap. 2 fórmula del producto para ξ (39), cap. 3 fórmula principal de Riemann (48), cap. 4 teorema de los números primos (68), cap. 5 De la Vallée Poussin (88), cap. 6 análisis numérico de las raíces por Euler–Maclaurin (96) — hasta ~p. 122.
  - **No está**: cap. 7 fórmula de Riemann–Siegel (136), cap. 8 cálculos a gran escala / Turing / fenómeno de Lehmer (171), cap. 9 crecimiento de zeta y Lindelöf (182), cap. 10 análisis de Fourier (203), cap. 11 ceros en la línea / teorema de Hardy (226), cap. 12 miscelánea (260), apéndice con el paper de Riemann (299), referencias (306) e índice (311).
  - Consecuencia práctica: para Riemann–Siegel, Turing o Hardy **no sirve este fichero**; usar `397_Titchmarsh-HeathBrown_1986_Theory_Riemann_Zeta_Function.pdf` o los Ivić de la biblioteca.
- `338_Patterson_1988_Introduction_Riemann_Zeta_Function.pdf` — S. J. Patterson, *An Introduction to the Theory of the Riemann Zeta-Function*, Cambridge Studies in Advanced Mathematics **14**. 172 hojas, completo (bibliografía p. 153, índice p. 156).
- `339_Patterson_1988_Zeros_Zeta_And_Prime_Number_Theorem.pdf` — cap. 4, ceros y TNP. doi:10.1017/CBO9780511623707.006
- `317_Motohashi_1997_Spectral_Theory_Riemann_Zeta.pdf` — teoría espectral, Cambridge Tracts 127.
- `395_Tenenbaum_2015_Analytic_Probabilistic_Number_Theory.pdf` — GSM 163, 3ª edición.
- `354_Ramachandra_1976_Problems_Analytic_Number_Theory.pdf` — K. Ramachandra, *Some problems of analytic number theory*, Acta Arithmetica **XXXI** (1976), pp. 313–324; completo, en 7 hojas a doble página. Dedicado a la memoria de Turán. Primos en intervalos cortos, resultado de Selberg para N₀(x), método de Heilbronn y aproximación diofántica simultánea.
- `057_Bombieri_2010_Classical_Theory_Zeta_And_L_Functions.pdf` — panorámica histórica. doi:10.1007/s00032-010-0121-8
- `104_Conrey_2003_Riemann_Hypothesis.pdf` — el survey del Notices.
- `102_Conrey_1986_Review_Ivic_Riemann_Zeta_Function.pdf` — reseña de una página (American Scientist).
- `182_Hardy-Littlewood_1917_Riemann_Zeta_And_Distribution_Primes.pdf` — memoria original de Acta Mathematica.
- `090_Christ_2014_Value_Distribution_Zeta_Near_Critical_Line_Thesis.pdf` — tesis doctoral (Würzburg 2013, 191 pág.): distribución de valores de ζ y funciones afines cerca de la recta crítica. arXiv:1405.1553
- `097_Connes2026_2026_Connes2026.pdf` — Connes, *The Riemann Hypothesis: past, present and a letter through time* (panorámica, 2026). arXiv:2602.04022
- `107_Cramer_1919_Nullstellen_Riemannschen_Zetafunktion.pdf` — Cramér, estudios sobre los ceros de ζ. Math. Z. 4 (1919)
- `179_Hadamard_1896_Distribution_Zeros_Zeta_Consequences_Arithmetiques.pdf` — Hadamard, distribución de los ceros de ζ y consecuencias aritméticas. Bull. SMF 24 (1896)
- `277_Landau_1912_Nullstellen_Zetafunktion.pdf` — Landau, sobre los ceros de la función zeta. Math. Ann. 71 (1912)
- `291_Littlewood_1924_Zeros_Riemann_Zeta_Function.pdf` — Littlewood, sobre los ceros de ζ. Proc. Camb. Phil. Soc. (1924), DOI 10.1017/S0305004100014225
- `420_deLaValleePoussin_1896_Recherches_Analytiques_Nombres_Premiers_I.pdf` — de la Vallée Poussin, *Recherches analytiques…* I (1896): teorema de los números primos
- `421_vonMangoldt_1895_Zu_Riemanns_Abhandlung_Anzahl_Primzahlen.pdf` — von Mangoldt, sobre la memoria de Riemann (1895)

## 14. Otras funciones zeta y contextos adyacentes

- `186_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Dedekind_Zeta.pdf` — E. Hasanalizade, Q. Shen, P.-J. Wong, *Counting zeros of Dedekind zeta functions*, Math. Comp. 91 (2022) 277–293, doi:10.1090/mcom/3665. Prop. 3.5 (Jensen) y Prop. 3.7 (truco de Backlund) para ζ_K; Bellotti–Wong las usan con K = Q como sus Lemas 2.1 y 2.3.
- `016_Avdonin-Ivanov_2001_Exponential_Riesz_Bases_Subspaces_Divided_Differences.pdf` — bases de Riesz de exponenciales y de diferencias divididas; criterio de Pavlov vía Helson–Szegő/A₂. arXiv:math/0103160
- `294_Lyubarskii-Seip_1997_Complete_Interpolating_Sequences_Paley_Wiener_Muckenhoupt_Ap.pdf` — sucesiones de interpolación completa en Paley–Wiener y condición A_p; Kadec 1/4 como corolario. Rev. Mat. Iberoam. 13 (1997), DOI 10.4171/RMI/224
- `215_Igusa_2000_Introduction_Local_Zeta_Functions.pdf` — zetas locales.
- `257_Komori-Matsumoto-Tsumura_2023_Zeta_Functions_Root_Systems.pdf` — zetas de sistemas de raíces.
- `288_Li_2019_Zeta_L_Functions_Number_Theory_Combinatorics.pdf` — CBMS 129. doi:10.1090/cbms/129
- `417_Zhao_2016_Multiple_Zeta_Polylogarithms_Special_Values.pdf` — zetas múltiples y polilogaritmos.
- `278_Lapidus-VanFrankenhuysen_2000_Fractal_Geometry_Number_Theory.pdf` — dimensiones complejas de cuerdas fractales.
- `236_Kanemitsu-Tsukada_2015_Hecke_Type_Zeta_Functions.pdf` — cap. 8 de *Contributions to the Theory of Zeta-Functions*.
- `237_Kanemitsu-Tsukada_2015_Modular_Relation_Supremacy.pdf` — *Contributions to the Theory of Zeta-Functions: The Modular Relation Supremacy*, World Scientific, Series on Number Theory and Its Applications vol. 9. 316 hojas, completo (índice hasta p. 303). Fórmulas de Voronoĭ, funciones de Bessel generalizadas de Wilton, transformación theta.
- `048_Bloch_2000_Higher_Regulators_K_Theory_Zeta_Elliptic_Curves.pdf` — S. Bloch, monografía AMS (vol. 11 de la serie), 110 pág., completo. Reguladores superiores, K-teoría algebraica y funciones zeta de curvas elípticas.
- `349_Popov_1985_Transfer_Functions_Riemann_Zeta.pdf` — sistemas con funciones de transferencia ligadas a ζ.
- `228_Jones-Sato-Wada-Wiens_1976_Diophantine_Representation_Primes.pdf` — el polinomio de 26 variables (Monthly).
- `258_Korolev-Laurincikas_2023_Approximation_Mellin_Transform_Zeta_Axioms.pdf` — aproximación de ζ por transformadas de Mellin. Axioms 12 (2023), 520.
- `023_Balanzario-SanchezOrtiz_2007_Zeros_Davenport_Heilbronn_Counterexample.pdf` — ceros fuera de la recta del contraejemplo de Davenport–Heilbronn. Math. Comp. 76 (2007)
- `053_Bohr_1926_Fastperiodische_Funktionen_III_Dirichletentwicklung.pdf` — Bohr, funciones casi periódicas III: desarrollos de Dirichlet. Acta Math. (1926)
- `086_Chandrasekharan-Mandelbrojt_1959_Solutions_Riemann_Functional_Equation.pdf` — Chandrasekharan–Mandelbrojt, soluciones de la ecuación funcional de Riemann (1959)
- `113_Davenport-Heilbronn_1936_Zeros_Certain_Dirichlet_Series_I.pdf` — Davenport–Heilbronn, ceros de ciertas series de Dirichlet I (1936)
- `175_Grosswald-Schnitzer_1978_Class_Modified_Zeta_L_Functions.pdf` — Grosswald–Schnitzer, una clase de funciones ζ y L modificadas. Pacific J. Math. 74 (1978)
- `180_Hamburger_1921_Riemannsche_Funktionalgleichung_Zeta_Funktion_I.pdf` — Hamburger, ecuación funcional de Riemann I. Math. Z. 10 (1921)
- `193_HerichiLapidus2014_2014_Truncated_infinitesimal_shifts_spectral_operators_and_quantized_universality_of_the_Riemann_zeta_function.pdf` — Herichi–Lapidus, desplazamientos infinitesimales truncados y universalidad cuantizada de ζ. Ann. Fac. Sci. Toulouse 23 (2014)
- `194_HerreraMoree2018_2018_Coefficients_and_higher_order_derivatives_of_cyclotomic_polynomials_old_and_new.pdf` — coeficientes y derivadas de polinomios ciclotómicos. arXiv:1805.05207
- `206_Hoffman1992_1992_Multiple_harmonic_series.pdf` — Hoffman, series armónicas múltiples. Pacific J. Math. 152 (1992)
- `231_Kaczorowski-Perelli_1999_Structure_Selberg_Class_I.pdf` — Kaczorowski–Perelli, estructura de la clase de Selberg I. Acta Math. 182 (1999)
- `253_Knopp_1994_Dirichlet_Series_Riemann_Functional_Equation.pdf` — Knopp, series de Dirichlet con la ecuación funcional de Riemann (Hamburger). Invent. Math. 117 (1994)
- `322_Nakamura_2020_Dirichlet_Series_Periodic_Coefficients_Functional_Equation.pdf` — series de Dirichlet de coeficientes periódicos con la ecuación funcional de Riemann; ceros reales de L(s,χ). arXiv:2008.02570
- `341_Perelli_2016_Converse_Theorems_Zeta_Selberg_Class.pdf` — Perelli, teoremas recíprocos: de ζ a la clase de Selberg. arXiv:1605.02354
- `380_Siegel_1922_Satz_Hamburger_Funktionalgleichung_Zetafunktion.pdf` — Siegel, sobre el teorema de Hamburger. Math. Ann. 86 (1922)

## 15. Material no arbitrado — contrastar antes de usar

- `110_Dannon_2008_Riemann_Zeta_Function.pdf` — Gauge Institute Journal.
- `406_Vega_2023_Simple_Proof_Riemann_Hypothesis.pdf` — vía función Ψ de Dedekind. doi:10.33774/coe-2023-5flmk
- `158_Ghosh_2022_Statistics_Approximations_Zeros_Truncated_Symmetrized_Euler_Products.pdf` — informe de 2022 sobre los ceros de ζ_X de Gonek; ver §10.
- `355_Revers_2026_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf` — preprint v1 de 2026 (cota explícita de ζ(1/2+it)); ver §7. Afirma completar una prueba publicada; contrastar antes de usarlo como única fuente.
- `133_Fiori_2025_Note_Phragmen_Lindelof_Theorem.pdf` — preprint (arXiv v3, 2026) sobre Phragmén–Lindelöf; ver §7. Corrige un lema publicado (Trudgian 2014, Lema 3).
- `009_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf` — preprint anónimo de 2026 sobre S(N)=Σ e^{iγ_n}, citas rotas.
- `413_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf` — ver §1.

## 16. Primos generalizados de Beurling

- `045_Beurling_1937_Distribution_Nombres_Premiers_Generalises_I.pdf` — Beurling, primos generalizados I (1937)
- `073_Broucke-Debruyne-Revesz_2025_Well_Behaved_Beurling_Number_Systems.pdf` — sistemas de Beurling bien comportados (ahorro de potencia en primos y enteros). arXiv:2309.01567
- `074_Broucke-Debruyne-Vindas_2020_Beurling_Integers_RH_Large_Oscillation.pdf` — enteros de Beurling con RH y oscilación grande. arXiv:2004.11501
- `075_Broucke-Vindas_2024_Generalized_Prime_Random_Approximation.pdf` — aproximación aleatoria de primos generalizados. arXiv:2102.08478
- `115_Debruyne-Vindas_2019_Complex_Tauberian_Theorems_Laplace_Transforms.pdf` — teoremas tauberianos complejos para transformadas de Laplace. arXiv:1604.05069
- `121_Diamond-Montgomery-Vorhauer_2006_Beurling_Primes_Large_Oscillation.pdf` — Diamond–Montgomery–Vorhauer, primos de Beurling con oscilación grande. Math. Ann. 334 (2006), DOI 10.1007/s00208-005-0638-2
- `122_Diamond_1970_Asymptotic_Distribution_Beurling_Generalized_Integers.pdf` — Diamond, distribución asintótica de los enteros generalizados de Beurling (1970)
- `200_Hilberdink-Lapidus_2006_Beurling_Zeta_Generalised_Primes_Fractal_Membranes.pdf` — Hilberdink–Lapidus, zetas de Beurling, primos generalizados y membranas fractales. arXiv:math/0410270
- `416_Zhang_2013_Normalization_Beurling_Generalized_Primes_RH.pdf` — Zhang, normalización de primos generalizados de Beurling con RH. Ann. Univ. Sci. Budapest. Sect. Comp. 39 (2013)

## 17. Paseos aleatorios, excursiones y caminos de Dyck

- `079_Carmona-Petrelis_2017_Limit_Theorems_Random_Walk_Excursion.pdf` — excursión de paseo aleatorio condicionada a encerrar un área: teoremas límite. arXiv:1709.06448
- `087_Chatterjee2007_2007_Stein_s_method_for_concentration_inequalities.pdf` — Chatterjee, método de Stein para desigualdades de concentración. PTRF 138 (2007), DOI 10.1007/s00440-006-0029-y
- `118_Denisov-Kolb-Wachtel_2015_Local_Asymptotics_Random_Walk_Excursions.pdf` — asintótica local del área de las excursiones de paseos aleatorios (Oberwolfach Preprint 2013-19)
- `119_DerridaEnaudLebowitz2004_2004_The_asymmetric_exclusion_process_and_Brownian_excursions.pdf` — proceso de exclusión asimétrico y excursiones brownianas. arXiv:cond-mat/0306078
- `125_DurrettIglehartMiller1977_1977_Weak_convergence_to_Brownian_meander_and_Brownian_excursion.pdf` — convergencia débil al meandro y a la excursión brownianos. Ann. Probab. (1977)
- `165_GordinPeligrad2011_2011_On_the_functional_central_limit_theorem_via_martingale_approximation.pdf` — teorema central del límite funcional vía aproximación por martingalas. Bernoulli 17 (2011). arXiv:0910.3448
- `166_Gouezel2010_2010_Almost_sure_invariance_principle_for_dynamical_systems_by_spectral_methods.pdf` — principio de invariancia casi segura por métodos espectrales. Ann. Probab. 38 (2010), DOI 10.1214/10-AOP525
- `188_HaugPrellberg2015_2015_Uniform_asymptotics_of_area_weighted_Dyck_paths.pdf` — asintótica uniforme de caminos de Dyck ponderados por área. arXiv:1412.5108
- `223_Janson_2007_Brownian_Excursion_Area_Wright_Constants.pdf` — Janson, área de la excursión browniana y constantes de Wright. Probab. Surveys 4 (2007), DOI 10.1214/07-PS104
- `235_Kaigh1976_1976_An_invariance_principle_for_random_walk_conditioned_by_a_late_return_to_zero.pdf` — principio de invariancia para paseos condicionados a un retorno tardío a cero. Ann. Probab. (1976)
- `251_KhorunzhiyMarckert2009_2009_Uniform_bounds_for_exponential_moment_of_maximum_of_a_Dyck_path.pdf` — cotas uniformes del momento exponencial del máximo de un camino de Dyck. arXiv:0902.1229
- `266_Kousha2012_2012_Asymptotic_behavior_and_the_moderate_deviation_principle_for_the_maximum_of_a_Dyck_path.pdf` — comportamiento asintótico y desviaciones moderadas del máximo de un camino de Dyck. arXiv:1008.0606
- `335_OwczarekPrellberg2014_2014_Pressure_exerted_by_a_vesicle_on_a_surface.pdf` — presión de una vesícula sobre una superficie (caminos de Dyck). arXiv:1311.2174
- `340_PeligradUtev2005_2005_A_new_maximal_inequality_and_invariance_principle_for_stationary_sequences.pdf` — desigualdad maximal y principio de invariancia para sucesiones estacionarias. Ann. Probab. 33 (2005). arXiv:math/0406606
- `357_Richard_2005_Q_Functional_Equations_Excursion_Moments.pdf` — ecuaciones q-funcionales y momentos de excursiones. arXiv:math/0503198

## 18. Cuasicristales, bases de Riesz e interpolación de Fourier

- `017_Avdonin_1977_Riesz_Bases_Exponential_Functions_L2_Brief.pdf` — Avdonin, bases de Riesz de exponenciales en L² (nota breve, 1977)
- `059_Bondarenko-Radchenko-Seip_2023_Fourier_Interpolation_Zeros_Zeta_L_Functions.pdf` — Bondarenko–Radchenko–Seip, interpolación de Fourier con ceros de ζ y L-funciones. arXiv:2005.02996
- `095_Cohn-Elkies_2003_New_Upper_Bounds_Sphere_Packings_I.pdf` — Cohn–Elkies, cotas de programación lineal para empaquetamiento de esferas. Ann. of Math. 157 (2003). arXiv:math/0110009
- `128_Engert1970_1970_Finite_dimensional_translation_invariant_subspaces.pdf` — subespacios invariantes por traslación de dimensión finita. Pacific J. Math. 32 (1970)
- `207_Hruscev-Nikolskii-Pavlov_1981_Unconditional_Bases_Exponentials_Reproducing_Kernels.pdf` — Hruščev–Nikolskii–Pavlov, bases incondicionales de exponenciales y núcleos reproductores (1981)
- `216_Ingham_1936_Trigonometrical_Inequalities_Theory_Series.pdf` — Ingham, desigualdades trigonométricas en la teoría de series (1936)
- `270_Kozma-Lev_2011_Exponential_Riesz_Bases_Discrepancy_BMO.pdf` — Kozma–Lev, bases de Riesz de exponenciales, discrepancia de rotaciones irracionales y BMO. arXiv:1009.2188
- `271_Kurasov-Sarnak_2020_Stable_Polynomials_Crystalline_Measures.pdf` — Kurasov–Sarnak, polinomios estables y medidas cristalinas. arXiv:2004.05678
- `285_Lev-Olevskii_2015_Quasicrystals_Poisson_Summation_Formula.pdf` — Lev–Olevskii, cuasicristales y fórmula de sumación de Poisson. arXiv:1312.6884
- `286_Lev_2012_Riesz_Bases_Exponentials_Multiband_Spectra_Preprint.pdf` — Lev, bases de Riesz de exponenciales sobre espectros multibanda. arXiv:1101.3894
- `332_Olevskii-Ulanovskii_2020_Fourier_Quasicrystals_Unit_Masses.pdf` — Olevskii–Ulanovskii, cuasicristales de Fourier con masas unidad. C. R. Math. 358 (2020), DOI 10.5802/crmath.142
- `389_Szekelyhidi1982_1982_Note_on_exponential_polynomials.pdf` — Székelyhidi, nota sobre polinomios exponenciales. Pacific J. Math. 103 (1982)
- `412_Young_1974_Inequalities_Perturbation_Theorem_Paley_Wiener.pdf` — Young, desigualdades para el teorema de perturbación de Paley–Wiener. Proc. AMS 43 (1974)

## 19. Positividad total y funciones absolutamente monótonas

- `037_Belton2022_2022_Mathematics_Research_Reports.pdf` — preservadores de núcleos totalmente positivos y funciones de frecuencia de Pólya. Math. Res. Rep. 3 (2022), DOI 10.5802/mrr.12
- `043_Bernstein_1929_Fonctions_Absolument_Monotones.pdf` — Bernstein, funciones absolutamente monótonas. Acta Math. (1929)
- `060_BorceaBranden2009_2009_Annals_of_Mathematics.pdf` — Borcea–Brändén, teoremas maestros de Pólya–Schur. Ann. of Math. 170 (2009)
- `076_Burbea1974_1974_Pacific_Journal_of_Mathematics.pdf` — Burbea, positividad total y núcleos reproductores. Pacific J. Math. 55 (1974)
- `077_Burbea1976_1976_Pacific_Journal_of_Mathematics.pdf` — Burbea, positividad total de ciertos núcleos reproductores. Pacific J. Math. 67 (1976)

## 20. Otros temas (fuera del núcleo aritmético)

- `003_AkianGaubertNiv2018_2018_Tropical_compound_matrix_identities.pdf` — identidades de matrices compuestas tropicales. arXiv:1702.00980
- `038_Benedetto-Powell-Yilmaz_2006_Sigma_Delta_Quantization_Finite_Frames.pdf` — cuantización Sigma-Delta y marcos finitos
- `041_Benvenuti2019_2019_The_inverse_eigenvalue_problem_for_Leslie_matrices.pdf` — problema inverso de autovalores para matrices de Leslie. Electron. J. Linear Algebra 35 (2019)
- `058_Bonami1970_1970_Etude_des_coefficients_de_Fourier_des_fonctions_de_L_p_G.pdf` — Bonami, coeficientes de Fourier de funciones de L^p(G). Ann. Inst. Fourier 20 (1970)
- `082_CarrascoFlorens2000_2000_Econometric_Theory.pdf` — Carrasco–Florens, GMM con un continuo de condiciones de momentos (econometría)
- `112_Daubechies-DeVore_2003_Bandlimited_Function_Stable_Sigma_Delta_Modulators.pdf` — Daubechies–DeVore, moduladores Sigma-Delta estables de orden arbitrario. Ann. of Math. 158 (2003)
- `117_DellAnnaEtAl2016_2016_Violation_of_cluster_decomposition_and_absence_of_light_cones_in_local_integer_and_half_integer_spin_chains.pdf` — violación de la descomposición en clústeres en cadenas de espines. arXiv:1604.08281
- `126_DuttEtAl2019_2019_Nature_Communications.pdf` — espectroscopía de bandas en una dimensión sintética (fotónica). Nat. Commun. (2019), DOI 10.1038/s41467-019-11117-9
- `154_Gallier2016_2016_Spectral_theory_of_unsigned_and_signed_graphs_applications_to_graph_clustering_a_survey.pdf` — Gallier, teoría espectral de grafos con y sin signo; clustering. arXiv:1601.04692
- `177_Gunturk-Thao_2003_Ergodic_Dynamics_Sigma_Delta_Quantization.pdf` — dinámica ergódica en la cuantización Sigma-Delta. arXiv:math/0308223
- `295_LyubarskiiVershynin2010_2010_Uncertainty_principles_and_vector_quantization.pdf` — Lyubarskii–Vershynin, principios de incertidumbre y cuantización vectorial. arXiv:math/0611343
- `330_OganesyanHuse2007_2007_Localization_of_interacting_fermions_at_high_temperature.pdf` — Oganesyan–Huse, localización de fermiones interactuantes a alta temperatura. arXiv:cond-mat/0610854
- `359_RigalZadunaisky2015_2015_Twisted_semigroup_algebras.pdf` — álgebras de semigrupo torcidas. arXiv:1406.2985

## 21. Bibliografía de Alpöge — «Dirichlet L-functions and the Critical Line»

Referencias de las pp. 54–55 de *Dirichlet L-functions and the Critical Line* (lista de 29 fuentes), incorporadas el 2026-11-22 desde `Bibliografia_Alpoge_20261122_sin_Howe_Davenport.zip`. Los datos bibliográficos (revista, años, DOI) proceden de esa lista y de la portada de cada PDF; no se ha verificado el contenido matemático. Temas: cohomología prismática, representaciones de Galois, teoría theta (Howe–Rallis), Iwasawa y K-teoría, volúmenes aritméticos, más Landau 1905 y Huxley 1976 para ventanas unilaterales y densidad de ceros (relacionados con §8 y §10).

### 21.1 Libros y monografías

- `033_Bellaiche-Chenevier_2009_Families_Galois_Representations_Selmer_Groups.pdf` — J. Bellaïche y G. Chenevier, *Families of Galois representations and Selmer groups*, Astérisque 324 (2009), 326 pp. (monografía). numdam AST_2009__324__R1_0. Papel en la bibliografía: COHOMOLOGÍA.
- `199_Hida_2004_pAdic_Automorphic_Forms_Shimura_Varieties.pdf` — H. Hida, *p-Adic automorphic forms on Shimura varieties*, Springer Monographs in Mathematics, Springer, 2004 (libro completo, 397 pp. PDF). doi:10.1007/978-1-4684-9390-0. Papel en la bibliografía: AUTOMORFAS / SHIMURA.

### 21.2 Artículos

- `010_Anschutz-LeBras_2023_Prismatic_Dieudonne_Theory_arXiv_v4.pdf` — J. Anschütz y A.-C. Le Bras, *Prismatic Dieudonné theory*, Forum Math. Pi 11 (2023), e2, 1–92. arXiv:1907.10525v4; doi:10.1017/fmp.2022.22. Papel en la bibliografía: COHOMOLOGÍA LOCAL.
- `046_Bhatt-Scholze_2022_Prisms_Prismatic_Cohomology.pdf` — B. Bhatt y P. Scholze, *Prisms and prismatic cohomology*, Ann. of Math. (2) 196 (2022), 1135–1275. doi:10.4007/annals.2022.196.3.5. Papel en la bibliografía: COHOMOLOGÍA LOCAL.
- `064_Bost_1996_Periodes_Isogenies_Varietes_Abeliennes.pdf` — J.-B. Bost, *Périodes et isogénies des variétés abéliennes sur les corps de nombres (d’après Masser et Wüstholz)*, Séminaire Bourbaki exp. 795, Astérisque 237 (1996), 115–161. numdam SB_1994-1995__37__115_0. Papel en la bibliografía: PENDIENTES / PERÍODOS.
- `088_Chenevier-Harris_2013_Construction_Automorphic_Galois_Representations_II.pdf` — G. Chenevier y M. Harris, *Construction of automorphic Galois representations, II*, Cambridge J. Math. 1 (2013), 53–73. doi:10.4310/CJM.2013.v1.n1.a2. Papel en la bibliografía: CONGRUENCIAS AUTOMORFAS.
- `092_Coates-Sinnott_1974_Analogue_Stickelberger_Theorem_Higher_K_Groups.pdf` — J. Coates y W. Sinnott, *An analogue of Stickelberger’s theorem for the higher K-groups*, Invent. Math. 24 (1974), 149–161. doi:10.1007/BF01404303. Papel en la bibliografía: COHOMOLOGÍA / K-TEORÍA.
- `116_Deligne-Lusztig_1976_Representations_Reductive_Groups_Finite_Fields.pdf` — P. Deligne y G. Lusztig, *Representations of reductive groups over finite fields*, Ann. of Math. (2) 103 (1976), 103–161. doi:10.2307/1971021. Papel en la bibliografía: REPRESENTACIONES.
- `132_Ferrero-Washington_1979_Iwasawa_Invariant_Mu_p_Vanishes_Abelian_Number_Fields.pdf` — B. Ferrero y L. C. Washington, *The Iwasawa invariant μ_p vanishes for abelian number fields*, Ann. of Math. (2) 109 (1979), 377–395. JSTOR 1971116. Papel en la bibliografía: IWASAWA.
- `155_Gan-Qiu-Takeda_2014_Regularized_Siegel_Weil_Formula_Rallis_Inner_Product_arXiv_v3.pdf` — W. T. Gan, Y. Qiu y S. Takeda, *The regularized Siegel–Weil formula (the second term identity) and the Rallis inner product formula*, Invent. Math. 198 (2014), 739–831. arXiv:1207.4709v3; doi:10.1007/s00222-014-0509-0. Papel en la bibliografía: THETA / RALLIS.
- `156_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf` — W. T. Gan y S. Takeda, *A proof of the Howe duality conjecture*, J. Amer. Math. Soc. 29 (2016), 473–493. arXiv:1407.1995v4; doi:10.1090/jams/839. **Alternativa a Howe 1979** (el original de Howe no está en el zip porque ya lo tienes): cita a Howe, «θ-series and invariant theory», como [H1], y su Teorema 1.2 demuestra la dualidad local para pares simpléctico-ortogonales o unitarios sobre cuerpos locales no arquimedianos. No sustituye el contenido de teoría de invariantes de Howe ni resultados globales (cadenas de levantamientos theta, Rallis, períodos).. Papel en la bibliografía: CORRESPONDENCIA THETA.
- `171_Grayson_1984_Reduction_Theory_Using_Semistability.pdf` — D. R. Grayson, *Reduction theory using semistability*, Comment. Math. Helv. 59 (1984), 600–634. doi:10.1007/BF02566369. Papel en la bibliografía: PENDIENTES ARAKELOV.
- `213_Huxley_1976_Imperfect_Hybrid_Zero_Density_Theorem.pdf` — M. N. Huxley, *An imperfect hybrid zero-density theorem*, J. London Math. Soc. (2) 13 (1976), 53–56. doi:10.1112/jlms/s2-13.1.53. Papel en la bibliografía: CEROS / PRIMOS AUXILIARES.
- `241_Kato_2004_pAdic_Hodge_Theory_Values_Zeta_Functions_Modular_Forms.pdf` — K. Kato, *p-adic Hodge theory and values of zeta functions of modular forms*, Astérisque 295 (2004), 117–290. numdam AST_2004__295__117_0. Papel en la bibliografía: COHOMOLOGÍA / IWASAWA.
- `256_Kolyvagin_1990_Euler_Systems.pdf` — V. A. Kolyvagin, *Euler systems*, The Grothendieck Festschrift II, Birkhäuser (1990), 435–483. Papel en la bibliografía: COHOMOLOGÍA / EULER SYSTEMS.
- `276_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf` — E. Landau, *Über einen Satz von Tschebyschef*, Math. Ann. 61 (1905), 527–550. Göttinger Digitalisierungszentrum PPN235181684_0061. **Sin capa de texto** (escaneo). Papel en la bibliografía: VENTANAS UNILATERALES.
- `293_Lubin-Tate_1965_Formal_Complex_Multiplication_Local_Fields.pdf` — J. Lubin y J. Tate, *Formal complex multiplication in local fields*, Ann. of Math. (2) 81 (1965), 380–387. doi:10.2307/1970622. Papel en la bibliografía: DIVISIBILIDAD LOCAL.
- `312_Moriwaki_2009_Continuity_Volumes_Arithmetic_Varieties_arXiv_v2.pdf` — A. Moriwaki, *Continuity of volumes on arithmetic varieties*, J. Algebraic Geom. 18 (2009), 407–457. arXiv:math/0612269v2; doi:10.1090/S1056-3911-08-00500-6. Papel en la bibliografía: VOLUMEN ARITMÉTICO.
- `331_Ohsawa-Takegoshi_1987_Extension_L2_Holomorphic_Functions.pdf` — T. Ohsawa y K. Takegoshi, *On the extension of L² holomorphic functions*, Math. Z. 195 (1987), 197–204. doi:10.1007/BF01166457. Papel en la bibliografía: INTERPOLACIÓN L².
- `353_Rallis_1984_Injectivity_Properties_Liftings_Weil_Representations.pdf` — S. Rallis, *Injectivity properties of liftings associated to Weil representations*, Compositio Math. 52 (1984), 139–169. numdam CM_1984__52_2_139_0. Papel en la bibliografía: TORRES THETA.
- `356_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf` — K. A. Ribet, *A modular construction of unramified p-extensions of Q(μ_p)*, Invent. Math. 34 (1976), 151–162. doi:10.1007/BF01403065. **Sin capa de texto** (escaneo). Papel en la bibliografía: IWASAWA / GALOIS.
- `375_Selberg-Chowla_1967_On_Epstein_Zeta_Function.pdf` — A. Selberg y S. Chowla, *On Epstein’s zeta-function*, J. reine angew. Math. 227 (1967), 86–110. doi:10.1515/crll.1967.227.86. Papel en la bibliografía: PERÍODOS CM.
- `381_Sorensen_2020_A_Patching_Lemma.pdf` — C. M. Sorensen, *A patching lemma*, en *Shimura Varieties*, Cambridge Univ. Press (2020), 297–305. doi:10.1017/9781108649711.012. Las dos copias de Descargas eran idénticas (SHA-256 c4f6061e…cb4fd); entra una. Papel en la bibliografía: PATCHING.
- `382_Soule_2003_Bound_Torsion_K_Theory_Algebraic_Integers.pdf` — C. Soulé, *A bound for the torsion in the K-theory of algebraic integers*, Doc. Math., Extra Vol. Kato (2003), 761–788. doi:10.4171/DMS/3/21. Papel en la bibliografía: COHOMOLOGÍA / K-TEORÍA.
- `394_Taylor-Wiles_1995_Ring_Theoretic_Properties_Certain_Hecke_Algebras.pdf` — R. Taylor y A. Wiles, *Ring-theoretic properties of certain Hecke algebras*, Ann. of Math. (2) 141 (1995), 553–572. doi:10.2307/2118560. Papel en la bibliografía: CONGRUENCIAS / HECKE.

### 21.3 Anuncio

- `005_Alpoge_2026_Announcement_Remark_Riemann_Hypothesis_Proof.pdf` — L. Alpöge, anuncio y nota sobre la prueba de RH con Claude (4 pp., sin DOI): suplemento a la referencia [28] de la bibliografía; remite a `alpo.ge/lean.tar.gz.part01…part14`. Papel en la bibliografía: VERIFICACIÓN FORMAL.

## 22. postRHera — Stepanov–Bombieri, curvas CM, $p$-ádico y log-seno (incorporación del 2026-11-23)

### 22.1 Método de Stepanov–Bombieri, sumas exponenciales en cuerpos finitos y cribas

- `386_Stepanov_1969_On_the_Number_of_Points_of_a_Hyperelliptic_Curve.pdf` — Stepanov (1969), On the number of points of a hyperelliptic curve over a finite prime field. Traducción inglesa, pp. 1103–1114. Fuente citada en la sección sobre el método. Ficha: https://doi.org/10.1070/IM1969v003n05ABEH000834
- `055_Bombieri_1974_Counting_Points_on_Curves_Over_Finite_Fields.pdf` — Bombieri (1973/1974), Counting points on curves over finite fields (d’après S. A. Stepanov). Exposé 430, junio de 1973, publicado en 1974, pp. 234–241 más portada de Numdam. Construcción de una función auxiliar y comparación entre multiplicidad y polos. Ficha: https://www.numdam.org/item/SB_1972-1973__15__234_0/
- `387_Stepanov_1972_Congruences_in_Two_Unknowns.pdf` — Stepanov (1972), Congruences in two unknowns. Traducción inglesa, pp. 677–704. Desarrollo del método para congruencias en dos variables. Ficha: https://doi.org/10.1070/IM1972v006n04ABEH001895
- `054_Bombieri_1966_On_Exponential_Sums_in_Finite_Fields_Russian_1968.pdf` — Bombieri (1966), On exponential sums in finite fields. Traducción rusa publicada en 1968, pp. 58–87. Original inglés en Amer. J. Math. 88, pp. 71–105, DOI 10.2307/2373048. Ficha: https://www.mathnet.ru/eng/mat462
- `056_Bombieri_1978_On_Exponential_Sums_in_Finite_Fields_II.pdf` — Bombieri (1978), On exponential sums in finite fields, II. Artículo completo, pp. 29–39, extraído de las hojas 36–46 del volumen 47 digitalizado. Trata el número de raíces características de las sumas. Ficha: https://gdz.sub.uni-goettingen.de/id/PPN356556735_0047
- `153_Gallagher_1971_A_Larger_Sieve.pdf` — Gallagher (1971), A larger sieve. Escaneo a doble página, pp. 77–81 completas. La primera hoja incluye también la p. 76 del artículo anterior. Ficha: https://doi.org/10.4064/aa-18-1-77-81

### 22.2 Módulos singulares y puntos de Heegner

- `173_Gross-Zagier_1985_On_Singular_Moduli.pdf` — Gross–Zagier (1985), On singular moduli. Edición de revista, pp. 191–220 más portada bibliotecaria. Copia del sitio institucional de Zagier. Ficha: https://doi.org/10.1515/crll.1985.355.191
- `174_Gross-Zagier_1986_Heegner_Points_Derivatives_L_Series.pdf` — Gross–Zagier (1986), Heegner points and derivatives of L-series. Edición de revista, Invent. Math. 84, pp. 225–320. Copia del sitio institucional de Zagier. Ficha: https://doi.org/10.1007/BF01388809

### 22.3 Curvas CM, números de Hurwitz, grupos formales e interpolación $p$-ádica

- `211_Hurwitz_1899_Lemniscatische_Functionen.pdf` — Hurwitz (1899 en el volumen), Ueber die Entwickelungscoefficienten der lemniskatischen Functionen. Artículo original, pp. 196–226, extraído de las hojas 207–237 del volumen 51 de Göttingen. Springer fecha el artículo en diciembre de 1898. El DOI de la reimpresión citado en v4 corresponde a otro capítulo. Ficha: https://doi.org/10.1007/BF01453637
- `120_Deuring_1941_Typen_Multiplikatorenringe.pdf` — Deuring (1941), Die Typen der Multiplikatorenringe elliptischer Funktionenkörper. Escaneo de la Universidad de Maguncia, pp. 197–272. Fuente primaria para reducción de curvas CM. Ficha: https://doi.org/10.1007/BF02940746
- `360_Robert_1975_Regularite_Ideaux_Premiers_CM.pdf` — Robert (1975), Régularité des idéaux premiers d’un corps quadratique imaginaire de nombre de classes un. Artículo para el caso de número de clases uno y sus antecedentes sobre Hurwitz. Ficha: https://www.numdam.org/item/AST_1975__24-25__75_0/
- `361_Robert_1978_Nombres_de_Hurwitz_et_Unites_Elliptiques.pdf` — Robert (1978), Nombres de Hurwitz et unités elliptiques. Edición de revista más portada, pp. 297–389. Unidades elípticas y cuerpos cuadráticos imaginarios. Ficha: https://www.numdam.org/item/ASENS_1978_4_11_3_297_0/
- `242_Katz_1975_Congruences_Bernoulli_Hurwitz.pdf` — Katz (1975), The congruences of Clausen–von Staudt and Kummer for Bernoulli–Hurwitz numbers. Escaneo autoral de la edición, pp. 1–4 más portada bibliotecaria. Ficha: https://doi.org/10.1007/BF02547966
- `243_Katz_1976_pAdic_Interpolation_Real_Analytic_Eisenstein_Series.pdf` — Katz (1976), p-adic interpolation of real analytic Eisenstein series. Escaneo autoral, pp. 459–571 más portada. Ficha: https://annals.math.princeton.edu/1976/104-3/p06
- `245_Katz_1977_Formal_Groups_and_pAdic_Interpolation.pdf` — Katz (1977), Formal groups and p-adic interpolation. Artículo citado por Katz en el estudio supersingular posterior. Ficha: https://www.numdam.org/item/AST_1977__41-42__55_0/
- `244_Katz_1977_Eisenstein_Measure_and_pAdic_Interpolation.pdf` — Katz (1977), The Eisenstein measure and p-adic interpolation. Escaneo autoral, pp. 238–311 más portada. Interpolación en el caso ordinario. Ficha: https://web.math.princeton.edu/~nmk/old/
- `246_Katz_1978_pAdic_L_Functions_for_CM_Fields.pdf` — Katz (1978), p-adic L-functions for CM fields. Escaneo autoral, pp. 199–297 más portada. Ficha: https://web.math.princeton.edu/~nmk/old/
- `247_Katz_1981_Divisibilities_Congruences_Cartier_Duality.pdf` — Katz (1981/1982), Divisibilities, congruences, and Cartier duality. Escaneo del autor, pp. 667–678. Teorema 3.11 y aplicación supersingular en §4, fórmula de la p. 677. Ficha: https://web.math.princeton.edu/~nmk/old/
- `029_Bannai-Kobayashi_2010_Algebraic_Theta_Functions_arXiv_v4.pdf` — Bannai–Kobayashi (2010), Algebraic theta functions and the p-adic interpolation of Eisenstein–Kronecker numbers. arXiv v4, de 2007. La edición de revista apareció en 2010. Ficha: https://arxiv.org/abs/math/0610163v4
- `030_Bannai-Kobayashi_2016_Integral_Structures_pAdic_Fourier_Theory.pdf` — Bannai–Kobayashi (2016), Integral structures on p-adic Fourier theory. Edición de revista más portada. §5, pp. 543–549, reproduce y desarrolla las congruencias de Katz y Chellali. Ficha: https://doi.org/10.5802/aif.3018
- `028_Bannai-Kobayashi-Tsuji_2010_Elliptic_Polylogarithm_CM.pdf` — Bannai–Kobayashi–Tsuji (2010), On the de Rham and p-adic realizations of the elliptic polylogarithm for CM elliptic curves. Edición de revista, pp. 185–234 más portada. Especialización en torsión, también con buena reducción supersingular. Ficha: https://doi.org/10.24033/asens.2119
- `027_Bannai-Furusho-Kobayashi_2014_Eisenstein_Kronecker_Series_arXiv_v2.pdf` — Bannai–Furusho–Kobayashi, p-adic Eisenstein–Kronecker series for CM elliptic curves and the Kronecker limit formulas. arXiv v2. Relaciones de distribución de la theta de Kronecker. Ficha: https://arxiv.org/abs/0807.4007v2
- `008_Andreatta-Iovita_2024_Katz_Type_pAdic_L_Nonsplit_arXiv_v3.pdf` — Andreatta–Iovita, Katz type p-adic L-functions for primes p non-split in the CM field. arXiv v3. Bibliografía para primos no descompuestos. Ficha: https://arxiv.org/abs/1905.00792v3
- `067_Boxall_1986_pAdic_Interpolation_Logarithmic_Derivatives.pdf` — Boxall (1986), p-adic interpolation of logarithmic derivatives associated to certain Lubin–Tate formal groups. Edición de revista más portada. Referencia de Bannai–Kobayashi para grupos formales de Lubin–Tate. Ficha: https://www.numdam.org/item/AIF_1986__36_3_1_0/
- `280_Lazard_1955_Groupes_de_Lie_Formels.pdf` — Lazard (1955), Sur les groupes de Lie formels à un paramètre. Artículo clásico sobre grupos formales, pp. 251–274 más portada. Ficha: https://doi.org/10.24033/bsmf.1462
- `254_Koblitz_1983_pAdic_Eigen_Functions_Kubert_Distributions.pdf` — Koblitz (1983), p-adic eigen-functions for Kubert distributions. Edición de revista, pp. 674–686. Ficha: https://doi.org/10.4153/CJM-1983-038-8
- `350_Porubsky_2000_Covering_Systems_Kubert_Identities.pdf` — Porubský (2000), Covering systems, Kubert identities and difference equations. Edición de revista más portada, pp. 381–413. Ficha: https://www.dml.cz/handle/10338.dmlcz/136785

### 22.4 Integrales log-seno, zeta de Hurwitz, transformadas de Mellin y temas afines

- `002_Adam_2020_Generalized_Hypergeometric_Expansion_Hurwitz_Zeta.pdf` — Adam, Generalized hypergeometric expansion related to the Hurwitz zeta function. arXiv 2009.07134. Ficha: https://arxiv.org/abs/2009.07134
- `004_Alkan_2013_Harmonic_Zeta_Log_Sine_Integrals.pdf` — Alkan (2013), Approximation by special values of harmonic zeta function and log-sine integrals. Edición de revista, pp. 515–550. Ficha: https://intlpress.com/api/bgcloud-front/resource/pdf/volume/1805799893224603650-1805799893224603650-68bba1c69bbe72ba8dae7b9eeef33c68.pdf
- `063_Borwein-Straub_2012_Log_Sine_Evaluations_Mahler_Measures_Preprint.pdf` — Borwein–Straub (2012), Log-sine evaluations of Mahler measures. Preprint autoral de marzo de 2011. Ficha: https://doi.org/10.1017/S1446788712000067
- `089_Choi-Cho-Srivastava_2009_Log_Sine_Integrals.pdf` — Choi–Cho–Srivastava (2009), Log-sine integrals involving series associated with the zeta function and polylogarithms. Edición de revista, pp. 199–217. Ficha: https://doi.org/10.7146/math.scand.a-15115
- `376_Shalev_2025_Log_Sine_Integrals_Apery_Like_Sums.pdf` — Shalev, Closed-form evaluations of log-sine integrals and Apéry-like sums in terms of polylogarithms. Versión de arXiv citada por el manuscrito. Ficha: https://arxiv.org/abs/2508.05770
- `404_Umezawa_2019_Multiple_Zeta_Values_Iterated_Log_Sine_arXiv_v1.pdf` — Umezawa (2019), Multiple zeta values and iterated log-sine integrals. arXiv v1. Ficha: https://arxiv.org/abs/1904.09717v1
- `415_Zhang-Williams_1995_Values_Riemann_Zeta_Integrals.pdf` — Zhang–Williams (1995), Values of the Riemann zeta function and integrals involving log(2 sinh(θ/2)) and log(2 sin(θ/2)). Edición de revista, pp. 271–289, con portadas y páginas de cierre. Ficha: https://doi.org/10.2140/pjm.1995.168.271
- `249_Kellerhals_1995_Volumes_in_Hyperbolic_5_Space_Author.pdf` — Kellerhals (1995), Volumes in hyperbolic 5-space. Versión de autora con paginación interna. Ficha: https://doi.org/10.1007/BF01902056
- `414_Zagier_2006_The_Mellin_Transform_and_Related_Analytic_Techniques.pdf` — Zagier (2006), The Mellin transform and related analytic techniques. Versión autoral del apéndice. Ficha: https://people.mpim-bonn.mpg.de/zagier/files/tex/MellinTransform/fulltext.pdf
- `203_Hilberdink_2011_Flows_of_Mellin_Transforms.pdf` — Hilberdink (2011), Flows of Mellin transforms with periodic integrator. Edición de revista, pp. 455–469, más portada. Ficha: https://doi.org/10.5802/jtnb.771
- `274_Lagarias-Li_2016_Lerch_Zeta_IV_Hecke_Operators_arXiv_v3.pdf` — Lagarias–Li (2016), The Lerch zeta function IV. Hecke operators. arXiv v3. Ficha: https://arxiv.org/abs/1511.08116v3
- `040_Bensimhoun_2024_Asymptotic_Limit_Problems_arXiv_v2.pdf` — Bensimhoun (2024), A framework for asymptotic limit problems of probabilistic nature. arXiv v2, como en el manuscrito. Ficha: https://arxiv.org/abs/2404.03513v2
- `146_Fuchs_2025_Fejer_Kernel_Prime_Indicators.pdf` — Fuchs, Fejér-kernel prime indicators. Versión de arXiv descargada. Ficha: https://arxiv.org/abs/2506.18933

## Incorporación del 23 de noviembre de 2026

Origen: `POSTRHERA_bibliografia.zip` (40 PDF) y dos PDF sueltos de Gross–Zagier idénticos (misma suma SHA-256) a los del zip, incorporados una sola vez. Se comprobó la apertura y el número de páginas con `pdfinfo`, la suma SHA-256 de cada PDF frente a `fuentes.tsv` del zip y la ausencia de duplicados binarios con los 382 PDF previos (`git hash-object` frente al árbol del commit `5f26776`). Esto no constituye validación de las afirmaciones matemáticas de los documentos. Se renumeró la carpeta entera (equivalencias en `RENUMERACION_2026-11-23.md`; nombres, hashes y fuentes en `INCORPORACIONES_2026-11-23.json`).

| Número | Documento | Páginas PDF | Observación |
|---:|---|---:|---|
| 002 | `002_Adam_2020_Generalized_Hypergeometric_Expansion_Hurwitz_Zeta.pdf` | 32 | arXiv 2009.07134. |
| 004 | `004_Alkan_2013_Harmonic_Zeta_Log_Sine_Integrals.pdf` | 36 | Edición de revista, pp. 515–550. |
| 008 | `008_Andreatta-Iovita_2024_Katz_Type_pAdic_L_Nonsplit_arXiv_v3.pdf` | 57 | arXiv v3. Bibliografía para primos no descompuestos. |
| 027 | `027_Bannai-Furusho-Kobayashi_2014_Eisenstein_Kronecker_Series_arXiv_v2.pdf` | 28 | arXiv v2. Relaciones de distribución de la theta de Kronecker. |
| 028 | `028_Bannai-Kobayashi-Tsuji_2010_Elliptic_Polylogarithm_CM.pdf` | 51 | Edición de revista, pp. 185–234 más portada. Especialización en torsión, también con buena reducción supersingular. |
| 029 | `029_Bannai-Kobayashi_2010_Algebraic_Theta_Functions_arXiv_v4.pdf` | 55 | arXiv v4, de 2007. La edición de revista apareció en 2010. |
| 030 | `030_Bannai-Kobayashi_2016_Integral_Structures_pAdic_Fourier_Theory.pdf` | 31 | Edición de revista más portada. §5, pp. 543–549, reproduce y desarrolla las congruencias de Katz y Chellali. |
| 040 | `040_Bensimhoun_2024_Asymptotic_Limit_Problems_arXiv_v2.pdf` | 26 | arXiv v2, como en el manuscrito. |
| 054 | `054_Bombieri_1966_On_Exponential_Sums_in_Finite_Fields_Russian_1968.pdf` | 30 | Traducción rusa publicada en 1968, pp. 58–87. Original inglés en Amer. J. Math. 88, pp. 71–105, DOI 10.2307/2373048. |
| 055 | `055_Bombieri_1974_Counting_Points_on_Curves_Over_Finite_Fields.pdf` | 9 | Exposé 430, junio de 1973, publicado en 1974, pp. 234–241 más portada de Numdam. Construcción de una función auxiliar y comparación entre multiplicidad y polos. |
| 056 | `056_Bombieri_1978_On_Exponential_Sums_in_Finite_Fields_II.pdf` | 11 | Sin capa de texto. Artículo completo, pp. 29–39, extraído de las hojas 36–46 del volumen 47 digitalizado. Trata el número de raíces características de las sumas. |
| 063 | `063_Borwein-Straub_2012_Log_Sine_Evaluations_Mahler_Measures_Preprint.pdf` | 25 | Preprint autoral de marzo de 2011. |
| 067 | `067_Boxall_1986_pAdic_Interpolation_Logarithmic_Derivatives.pdf` | 28 | Edición de revista más portada. Referencia de Bannai–Kobayashi para grupos formales de Lubin–Tate. |
| 089 | `089_Choi-Cho-Srivastava_2009_Log_Sine_Integrals.pdf` | 19 | Edición de revista, pp. 199–217. |
| 120 | `120_Deuring_1941_Typen_Multiplikatorenringe.pdf` | 76 | Escaneo de la Universidad de Maguncia, pp. 197–272. Fuente primaria para reducción de curvas CM. |
| 146 | `146_Fuchs_2025_Fejer_Kernel_Prime_Indicators.pdf` | 34 | Versión de arXiv descargada. |
| 153 | `153_Gallagher_1971_A_Larger_Sieve.pdf` | 3 | Sin capa de texto. Escaneo a doble página, pp. 77–81 completas. La primera hoja incluye también la p. 76 del artículo anterior. |
| 173 | `173_Gross-Zagier_1985_On_Singular_Moduli.pdf` | 31 | Solo la portada tiene texto; el resto es escaneo. Edición de revista, pp. 191–220 más portada bibliotecaria. Copia del sitio institucional de Zagier. |
| 174 | `174_Gross-Zagier_1986_Heegner_Points_Derivatives_L_Series.pdf` | 96 | Edición de revista, Invent. Math. 84, pp. 225–320. Copia del sitio institucional de Zagier. |
| 203 | `203_Hilberdink_2011_Flows_of_Mellin_Transforms.pdf` | 16 | Edición de revista, pp. 455–469, más portada. |
| 211 | `211_Hurwitz_1899_Lemniscatische_Functionen.pdf` | 31 | Sin capa de texto. Artículo original, pp. 196–226, extraído de las hojas 207–237 del volumen 51 de Göttingen. Springer fecha el artículo en diciembre de 1898. El DOI de la reimpresión citado en v4 corresponde a otro capítulo. |
| 242 | `242_Katz_1975_Congruences_Bernoulli_Hurwitz.pdf` | 5 | Solo la portada tiene texto. Escaneo autoral de la edición, pp. 1–4 más portada bibliotecaria. |
| 243 | `243_Katz_1976_pAdic_Interpolation_Real_Analytic_Eisenstein_Series.pdf` | 114 | Escaneo autoral, pp. 459–571 más portada. |
| 244 | `244_Katz_1977_Eisenstein_Measure_and_pAdic_Interpolation.pdf` | 75 | Escaneo autoral, pp. 238–311 más portada. Interpolación en el caso ordinario. |
| 245 | `245_Katz_1977_Formal_Groups_and_pAdic_Interpolation.pdf` | 12 | Artículo citado por Katz en el estudio supersingular posterior. |
| 246 | `246_Katz_1978_pAdic_L_Functions_for_CM_Fields.pdf` | 100 | Solo la portada tiene texto. Escaneo autoral, pp. 199–297 más portada. |
| 247 | `247_Katz_1981_Divisibilities_Congruences_Cartier_Duality.pdf` | 12 | Sin capa de texto. Escaneo del autor, pp. 667–678. Teorema 3.11 y aplicación supersingular en §4, fórmula de la p. 677. |
| 249 | `249_Kellerhals_1995_Volumes_in_Hyperbolic_5_Space_Author.pdf` | 28 | Versión de autora con paginación interna. |
| 254 | `254_Koblitz_1983_pAdic_Eigen_Functions_Kubert_Distributions.pdf` | 13 | Edición de revista, pp. 674–686. |
| 274 | `274_Lagarias-Li_2016_Lerch_Zeta_IV_Hecke_Operators_arXiv_v3.pdf` | 42 | arXiv v3. |
| 280 | `280_Lazard_1955_Groupes_de_Lie_Formels.pdf` | 25 | Artículo clásico sobre grupos formales, pp. 251–274 más portada. |
| 350 | `350_Porubsky_2000_Covering_Systems_Kubert_Identities.pdf` | 34 | Edición de revista más portada, pp. 381–413. |
| 360 | `360_Robert_1975_Regularite_Ideaux_Premiers_CM.pdf` | 7 | Artículo para el caso de número de clases uno y sus antecedentes sobre Hurwitz. |
| 361 | `361_Robert_1978_Nombres_de_Hurwitz_et_Unites_Elliptiques.pdf` | 94 | Edición de revista más portada, pp. 297–389. Unidades elípticas y cuerpos cuadráticos imaginarios. |
| 376 | `376_Shalev_2025_Log_Sine_Integrals_Apery_Like_Sums.pdf` | 19 | Versión de arXiv citada por el manuscrito. |
| 386 | `386_Stepanov_1969_On_the_Number_of_Points_of_a_Hyperelliptic_Curve.pdf` | 12 | Traducción inglesa, pp. 1103–1114. Fuente citada en la sección sobre el método. |
| 387 | `387_Stepanov_1972_Congruences_in_Two_Unknowns.pdf` | 28 | Traducción inglesa, pp. 677–704. Desarrollo del método para congruencias en dos variables. |
| 404 | `404_Umezawa_2019_Multiple_Zeta_Values_Iterated_Log_Sine_arXiv_v1.pdf` | 18 | arXiv v1. |
| 414 | `414_Zagier_2006_The_Mellin_Transform_and_Related_Analytic_Techniques.pdf` | 16 | Versión autoral del apéndice. |
| 415 | `415_Zhang-Williams_1995_Values_Riemann_Zeta_Integrals.pdf` | 23 | Edición de revista, pp. 271–289, con portadas y páginas de cierre. |

## Incorporación del 22 de noviembre de 2026 (segunda)

Origen: `~/Downloads` (copias; los originales se conservan allí). Se renumeró la carpeta entera en orden alfabético ASCII (244 PDF cambian de número; ninguno cambia de contenido). Hashes en `INCORPORACIONES_2026-11-22.json` (retirado el 2026-11-23, commit `5f26776`) (`second_incorporation`).

| Número | Documento | Páginas PDF | Tipo |
|---|---|---:|---|
| 152 | `152_Gallagher_1970_Large_Sieve_Density_Estimate_Near_Sigma_1.pdf` | 11 | art |
| 315 | `315_Motohashi_1977_On_Gallaghers_Prime_Number_Theorem.pdf` | 3 | art |
| 316 | `316_Motohashi_1978_Primes_in_Arithmetic_Progressions.pdf` | 16 | art |

## Incorporación del 22 de noviembre de 2026

Origen: `~/Downloads/Bibliografia_Alpoge_20261122_sin_Howe_Davenport.zip` (524 MB), dividido en: (a) 25 PDF de contenido (2 libros: Hida y Bellaïche–Chenevier; 23 artículos, incluido el sustituto de Howe de Gan–Takeda) y 1 suplemento (anuncio de Alpöge), que entran en la biblioteca; (b) fuera de la carpeta plana, en Descargas: tu lista de 29 referencias (`00_Bibliografia_original_29_referencias.*`), el ZIP del código Lean (397 MB, supera el límite de 100 MB de GitHub), la página de verificación de Sutherland, `MANIFIESTO.csv`, `LEEME.txt` y `SHA256SUMS.txt`. Los SHA-256 de los 26 PDF coinciden con `SHA256SUMS.txt` del zip.

Se renombraron según `Autor_Año_Título` y se **renumeró la carpeta entera** en orden alfabético ASCII del nombre sin número (los 16 PDF añadidos el 2026-11-01 estaban al final, fuera de orden). Equivalencias antiguo → nuevo en `RENUMERACION_2026-11-22.md` (retirado el 2026-11-23; tabla acumulada en `RENUMERACION_2026-11-23.md`); nombres originales, hashes y fuentes en `INCORPORACIONES_2026-11-22.json` (retirado el 2026-11-23, commit `5f26776`).

| Número | Documento | Páginas PDF | Tipo |
|---|---|---:|---|
| 005 | `005_Alpoge_2026_Announcement_Remark_Riemann_Hypothesis_Proof.pdf` | 4 | anuncio |
| 010 | `010_Anschutz-LeBras_2023_Prismatic_Dieudonne_Theory_arXiv_v4.pdf` | 97 | art |
| 033 | `033_Bellaiche-Chenevier_2009_Families_Galois_Representations_Selmer_Groups.pdf` | 327 | libro |
| 046 | `046_Bhatt-Scholze_2022_Prisms_Prismatic_Cohomology.pdf` | 125 | art |
| 064 | `064_Bost_1996_Periodes_Isogenies_Varietes_Abeliennes.pdf` | 48 | art |
| 088 | `088_Chenevier-Harris_2013_Construction_Automorphic_Galois_Representations_II.pdf` | 15 | art |
| 092 | `092_Coates-Sinnott_1974_Analogue_Stickelberger_Theorem_Higher_K_Groups.pdf` | 13 | art |
| 116 | `116_Deligne-Lusztig_1976_Representations_Reductive_Groups_Finite_Fields.pdf` | 60 | art |
| 132 | `132_Ferrero-Washington_1979_Iwasawa_Invariant_Mu_p_Vanishes_Abelian_Number_Fields.pdf` | 20 | art |
| 155 | `155_Gan-Qiu-Takeda_2014_Regularized_Siegel_Weil_Formula_Rallis_Inner_Product_arXiv_v3.pdf` | 59 | art |
| 156 | `156_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf` | 21 | art |
| 171 | `171_Grayson_1984_Reduction_Theory_Using_Semistability.pdf` | 36 | art |
| 199 | `199_Hida_2004_pAdic_Automorphic_Forms_Shimura_Varieties.pdf` | 397 | libro |
| 213 | `213_Huxley_1976_Imperfect_Hybrid_Zero_Density_Theorem.pdf` | 4 | art |
| 241 | `241_Kato_2004_pAdic_Hodge_Theory_Values_Zeta_Functions_Modular_Forms.pdf` | 175 | art |
| 256 | `256_Kolyvagin_1990_Euler_Systems.pdf` | 49 | art |
| 276 | `276_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf` | 25 | art |
| 293 | `293_Lubin-Tate_1965_Formal_Complex_Multiplication_Local_Fields.pdf` | 9 | art |
| 312 | `312_Moriwaki_2009_Continuity_Volumes_Arithmetic_Varieties_arXiv_v2.pdf` | 43 | art |
| 331 | `331_Ohsawa-Takegoshi_1987_Extension_L2_Holomorphic_Functions.pdf` | 8 | art |
| 353 | `353_Rallis_1984_Injectivity_Properties_Liftings_Weil_Representations.pdf` | 32 | art |
| 356 | `356_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf` | 13 | art |
| 375 | `375_Selberg-Chowla_1967_On_Epstein_Zeta_Function.pdf` | 25 | art |
| 381 | `381_Sorensen_2020_A_Patching_Lemma.pdf` | 9 | art |
| 382 | `382_Soule_2003_Bound_Torsion_K_Theory_Algebraic_Integers.pdf` | 28 | art |
| 394 | `394_Taylor-Wiles_1995_Ring_Theoretic_Properties_Certain_Hecke_Algebras.pdf` | 22 | art |

## Incorporación del 1 de noviembre de 2026

(Numeración vigente tras la renumeración del 2026-11-22; en el momento de la incorporación se añadieron como 338–353 sin renumerar el fondo anterior.) Comprobación de apertura y páginas con pypdf, interpretación de todas las páginas con MuPDF y SHA-256 de cada incorporación; esto no constituye validación de las afirmaciones matemáticas de los documentos.

- Davenport es la segunda edición de 1980, no la tercera de 2000.
- Se conservan Amberger v1 y v5 como versiones distintas.
- Hiary–Leong–Yang v3 se añade sin sustituir la v2 ya existente (nº 197 tras la renumeración).
- El PDF parcial de Olver contiene solo portada e índice (8 páginas); el libro completo está en el nº 334. MuPDF advierte de longitudes de flujos incorrectas, pero termina con código 0; se preservan los bytes originales.
- El archivo descargado con título Einstein–Grossmann está vacío y no es la tesis de Grossmann. No se incorpora y permanece en Descargas.
- El PDF de Davenport produce avisos de glifos de la capa OCR (`HiddenHorzOCR`) en MuPDF; termina con código 0. Se conserva sin alterar.

| Número | Documento | Páginas PDF | Observación |
|---|---|---:|---|
| 006 | `006_Amberger_2025_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v1.pdf` | 18 | Versión histórica v1; se conserva también v5. |
| 007 | `007_Amberger_2026_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v5.pdf` | 26 | Versión v5; no sustituye v1. |
| 035 | `035_Bellotti-Wong_2026_Counting_Zeros_Artin_L_Functions_arXiv_v1.pdf` | 24 | La otra copia descargada tiene idéntico SHA-256. |
| 114 | `114_Davenport_1980_Multiplicative_Number_Theory_Second_Edition.pdf` | 188 | Segunda edición de 1980, revisada por H. L. Montgomery; no es la tercera edición de 2000. |
| 190 | `190_HeathBrown_2016_New_kth_Derivative_Estimate_Exponential_Sums_Vinogradov_arXiv_v3.pdf` | 17 | Preprint v3 de 2016, correspondiente al trabajo publicado en 2017. |
| 196 | `196_Hiary-Leong-Yang_2024_Explicit_Bounds_Zeta_1_Line_arXiv_v3.pdf` | 31 | Versión v3; se mantiene intacta la v2 existente en el nº 197. |
| 333 | `333_Olver_1974_Introduction_Asymptotics_Special_Functions.pdf` | 324 | Libro independiente de 1974, formado por los siete primeros capítulos de Asymptotics and Special Functions; ISBN 0-12-525856-9. |
| 334 | `334_Olver_1997_Asymptotics_Special_Functions_AK_Peters_Reprint.pdf` | 591 | Reimpresión A K Peters de 1997 de la obra de 1974; portada y datos editoriales verificados en el PDF local. |
| 345 | `345_Platt-Trudgian_2014_Improved_Explicit_Bound_Zeta_Critical_Line_arXiv_v2.pdf` | 9 | Preprint v2 de 2014, publicado en J. Number Theory 147 (2015) 842–851. |
| 346 | `346_Platt-Trudgian_2015_Zeroes_Partial_Sums_Zeta_Function_arXiv_v2.pdf` | 5 | Trabajo diferente de An improved explicit bound; no es una copia de ese artículo. |
| 366 | `366_Rosser_1941_Explicit_Bounds_Functions_Prime_Numbers.pdf` | 23 | Incluye portada JSTOR y artículo de pp. 211–232. |
| 368 | `368_Rudin_1987_Real_Complex_Analysis_Third_Edition.pdf` | 430 | Tercera edición internacional de 1987, McGraw-Hill; ISBN 0-07-054234-1. |
| 392 | `392_Tao-Trudgian-Yang_2025_New_Exponent_Pairs_Zero_Density_Additive_Energy_arXiv_v1.pdf` | 44 | Preprint v1. |
| 398 | `398_Titchmarsh_1939_Theory_Functions_Second_Edition.pdf` | 452 | Segunda edición de 1939; el escaneo corresponde a una reimpresión posterior. |
| 399 | `399_Trudgian-Yang_2024_Toward_Optimal_Exponent_Pairs_arXiv_v3.pdf` | 38 | Preprint v3. |
| 403 | `403_Turing_1953_Some_Calculations_Riemann_Zeta_Function.pdf` | 19 | Artículo de pp. 99–117. |

### Documento parcial conservado

- `DOCUMENTOS_PARCIALES/Olver_1997_Asymptotics_Special_Functions_SOLO_Portada_Indice_8pp.pdf` — 8 páginas; solo portada e índice.

Los nombres originales, hashes, duplicados y decisiones del 2026-11-01 estaban en `INCORPORACIONES_2026-11-01.json`, retirado el 2026-11-22; se recuperan del commit `4a661ae` del repositorio.

## Catálogo canónico de archivos (422 PDF principales)

- `001_AbercrombieBanksShparlinski2009_2009_Arithmetic_functions_on_Beatty_sequences.pdf`
- `002_Adam_2020_Generalized_Hypergeometric_Expansion_Hurwitz_Zeta.pdf`
- `003_AkianGaubertNiv2018_2018_Tropical_compound_matrix_identities.pdf`
- `004_Alkan_2013_Harmonic_Zeta_Log_Sine_Integrals.pdf`
- `005_Alpoge_2026_Announcement_Remark_Riemann_Hypothesis_Proof.pdf`
- `006_Amberger_2025_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v1.pdf`
- `007_Amberger_2026_Estimating_Number_Zeros_Dedekind_Zeta_Functions_arXiv_v5.pdf`
- `008_Andreatta-Iovita_2024_Katz_Type_pAdic_L_Nonsplit_arXiv_v3.pdf`
- `009_Anonymous_2026_Unexpected_Phase_Summation_Patterns_Riemann_Zeros.pdf`
- `010_Anschutz-LeBras_2023_Prismatic_Dieudonne_Theory_arXiv_v4.pdf`
- `011_Arguin-Bourgade-Radziwill_2020_Fyodorov_Hiary_Keating_Conjecture_I.pdf`
- `012_Arguin-Bourgade-Radziwill_2023_Fyodorov_Hiary_Keating_Conjecture_II.pdf`
- `013_AriasdeReyna_2024_Explicit_Formula_Quasicrystal_Definition.pdf`
- `014_Aryan_2019_Extension_Landau_Gonek_Formula.pdf`
- `015_Aryan_2022_Extension_Landau_Gonek_Formula_Published.pdf`
- `016_Avdonin-Ivanov_2001_Exponential_Riesz_Bases_Subspaces_Divided_Differences.pdf`
- `017_Avdonin_1977_Riesz_Bases_Exponential_Functions_L2_Brief.pdf`
- `018_Aymone-Sidoravicius_2017_Partial_Sums_Biased_Random_Multiplicative_Functions.pdf`
- `019_Aymone2020_2020_A_note_on_multiplicative_functions_resembling_the_M_bius_function.pdf`
- `020_Backlund_1916_Nullstellen_Riemannschen_Zetafunktion.pdf`
- `021_BaezDuarte-Balazard-Landreau-Saias_2000_Notes_sur_la_fonction_zeta_de_Riemann_3.pdf`
- `022_BaezDuarte2002_2002_BaezDuarte2002.pdf`
- `023_Balanzario-SanchezOrtiz_2007_Zeros_Davenport_Heilbronn_Counterexample.pdf`
- `024_Balazard-Saias-Yor_1999_Notes_Fonction_Zeta_Riemann_2_Transcription_VellaChemla.pdf`
- `025_Balog_1987_Integers_Without_Large_Prime_Factors.pdf`
- `026_Baluyot-Goldston-etal_2025_Pair_Correlation_Zeros_I_Proportions_Simple_Critical.pdf`
- `027_Bannai-Furusho-Kobayashi_2014_Eisenstein_Kronecker_Series_arXiv_v2.pdf`
- `028_Bannai-Kobayashi-Tsuji_2010_Elliptic_Polylogarithm_CM.pdf`
- `029_Bannai-Kobayashi_2010_Algebraic_Theta_Functions_arXiv_v4.pdf`
- `030_Bannai-Kobayashi_2016_Integral_Structures_pAdic_Fourier_Theory.pdf`
- `031_Baricz-Laforgia-Pogany_2015_Van_Der_Corput_Inequalities_Bessel.pdf`
- `032_Barrett-Jarvis_1992_Spectral_Properties_Redheffer_Matrix.pdf`
- `033_Bellaiche-Chenevier_2009_Families_Galois_Representations_Selmer_Groups.pdf`
- `034_Bellotti-Wong_2025_Improved_Argument_Zero_Counting_Zeta.pdf`
- `035_Bellotti-Wong_2026_Counting_Zeros_Artin_L_Functions_arXiv_v1.pdf`
- `036_Bellotti_2024_Explicit_Bounds_Zeta_New_Zero_Free_Region.pdf`
- `037_Belton2022_2022_Mathematics_Research_Reports.pdf`
- `038_Benedetto-Powell-Yilmaz_2006_Sigma_Delta_Quantization_Finite_Frames.pdf`
- `039_Bennett-Martin-OBryant-Rechnitzer_2021_Counting_Zeros_Dirichlet_L_Functions.pdf`
- `040_Bensimhoun_2024_Asymptotic_Limit_Problems_arXiv_v2.pdf`
- `041_Benvenuti2019_2019_The_inverse_eigenvalue_problem_for_Leslie_matrices.pdf`
- `042_BergelsonKulagaPrzymusLemanczykRichter2019_2019_Discrete_Contin_Dyn_Syst.pdf`
- `043_Bernstein_1929_Fonctions_Absolument_Monotones.pdf`
- `044_Berry_1988_Semiclassical_Formula_Number_Variance_Riemann_Zeros.pdf`
- `045_Beurling_1937_Distribution_Nombres_Premiers_Generalises_I.pdf`
- `046_Bhatt-Scholze_2022_Prisms_Prismatic_Cohomology.pdf`
- `047_Bjorner_2011_Cell_Complex_Number_Theory.pdf`
- `048_Bloch_2000_Higher_Regulators_K_Theory_Zeta_Elliptic_Curves.pdf`
- `049_Bogomolny-Keating_1995_Random_Matrix_Theory_Riemann_Zeros_I_Three_Four_Point_Correlations.pdf`
- `050_Bogomolny-Keating_1996_Gutzwiller_Trace_Formula_Spectral_Statistics_Beyond_Diagonal.pdf`
- `051_Bogomolny-Keating_1996_Random_Matrix_Theory_Riemann_Zeros_II_n_Point_Correlations.pdf`
- `052_Bohigas-Leboeuf-Sanchez_2001_Spectral_Spacing_Correlations.pdf`
- `053_Bohr_1926_Fastperiodische_Funktionen_III_Dirichletentwicklung.pdf`
- `054_Bombieri_1966_On_Exponential_Sums_in_Finite_Fields_Russian_1968.pdf`
- `055_Bombieri_1974_Counting_Points_on_Curves_Over_Finite_Fields.pdf`
- `056_Bombieri_1978_On_Exponential_Sums_in_Finite_Fields_II.pdf`
- `057_Bombieri_2010_Classical_Theory_Zeta_And_L_Functions.pdf`
- `058_Bonami1970_1970_Etude_des_coefficients_de_Fourier_des_fonctions_de_L_p_G.pdf`
- `059_Bondarenko-Radchenko-Seip_2023_Fourier_Interpolation_Zeros_Zeta_L_Functions.pdf`
- `060_BorceaBranden2009_2009_Annals_of_Mathematics.pdf`
- `061_Bornemann-Forrester-Mays_2017_Finite_Size_Effects_Spacing_Distributions.pdf`
- `062_Borwein-Straub-Wan-Zudilin_2012_Densities_Short_Uniform_Random_Walks.pdf`
- `063_Borwein-Straub_2012_Log_Sine_Evaluations_Mahler_Measures_Preprint.pdf`
- `064_Bost_1996_Periodes_Isogenies_Varietes_Abeliennes.pdf`
- `065_Bourgain_2017_Decoupling_Exponential_Sums_Riemann_Zeta.pdf`
- `066_Bourgain_undated_On_the_Fourier_Walsh_spectrum_of_the_M_obius_function.pdf`
- `067_Boxall_1986_pAdic_Interpolation_Logarithmic_Derivatives.pdf`
- `068_Brent-Platt-Trudgian_2020_Sums_Over_Zeros_Riemann_Zeta.pdf`
- `069_Brent2018_2019_On_asymptotic_approximations_to_the_log_Gamma_and_Riemann_Siegel_theta_functions.pdf`
- `070_Brent_1979_Zeros_Riemann_Zeta_Critical_Strip.pdf`
- `071_BretcheDressTenenbaum2020_2020_Mathematika.pdf`
- `072_Brevig-Perfekt-Seip-Siskakis-Vukotic_2016_Multiplicative_Hilbert_Matrix.pdf`
- `073_Broucke-Debruyne-Revesz_2025_Well_Behaved_Beurling_Number_Systems.pdf`
- `074_Broucke-Debruyne-Vindas_2020_Beurling_Integers_RH_Large_Oscillation.pdf`
- `075_Broucke-Vindas_2024_Generalized_Prime_Random_Approximation.pdf`
- `076_Burbea1974_1974_Pacific_Journal_of_Mathematics.pdf`
- `077_Burbea1976_1976_Pacific_Journal_of_Mathematics.pdf`
- `078_Buthe2014_2015_A_method_for_proving_the_completeness_of_a_list_of_zeros_of_certain_functions.pdf`
- `079_Carmona-Petrelis_2017_Limit_Theorems_Random_Walk_Excursion.pdf`
- `080_Carneiro-Chandee-Littmann-Milinovich_2014_Hilbert_Spaces_Pair_Correlation.pdf`
- `081_Carneiro-Milinovich-Ramos_2023_Fourier_Optimization_Montgomery_Pair_Correlation.pdf`
- `082_CarrascoFlorens2000_2000_Econometric_Theory.pdf`
- `083_Cartier-Julia-Moussa-Vanhove_2006_Random_Matrices_Zeta_Dynamical_Systems.pdf`
- `084_Cassaigne-Ferenczi-Mauduit-Rivat-Sarkozy_1999_Liouville_Pseudorandom_Sequences.pdf`
- `085_Chan_2002_More_Precise_Pair_Correlation_Zeros_Primes_Short_Intervals.pdf`
- `086_Chandrasekharan-Mandelbrojt_1959_Solutions_Riemann_Functional_Equation.pdf`
- `087_Chatterjee2007_2007_Stein_s_method_for_concentration_inequalities.pdf`
- `088_Chenevier-Harris_2013_Construction_Automorphic_Galois_Representations_II.pdf`
- `089_Choi-Cho-Srivastava_2009_Log_Sine_Integrals.pdf`
- `090_Christ_2014_Value_Distribution_Zeta_Near_Critical_Line_Thesis.pdf`
- `091_Claude_2026_More_Than_Two_Thirds_Zeros_Zeta_Critical_Line.pdf`
- `092_Coates-Sinnott_1974_Analogue_Stickelberger_Theorem_Higher_K_Groups.pdf`
- `093_Coffey_2005_Polygamma_Theory_Li_Keiper_Constants_Riemann_Hypothesis.pdf`
- `094_Coffey_2009_Certain_Sums_Over_Nontrivial_Zeta_Zeros.pdf`
- `095_Cohn-Elkies_2003_New_Upper_Bounds_Sphere_Packings_I.pdf`
- `096_Connes1998_1998_Connes1998.pdf`
- `097_Connes2026_2026_Connes2026.pdf`
- `098_Conrad_2005_Partial_Euler_Products_Critical_Line.pdf`
- `099_Conrey-Keating_2016_Pair_Correlation_Twin_Primes_Revisited.pdf`
- `100_Conrey-TurnageButterbaugh_2018_r_Gaps_Between_Zeros_Zeta.pdf`
- `101_ConreySnaith2008_2008_Communications_in_Number_Theory_and_Physics.pdf`
- `102_Conrey_1986_Review_Ivic_Riemann_Zeta_Function.pdf`
- `103_Conrey_1989_More_Than_Two_Fifths_Zeros_Critical_Line.pdf`
- `104_Conrey_2003_Riemann_Hypothesis.pdf`
- `105_Coons2010_2010_On_the_multiplicative_Erd_s_discrepancy_problem.pdf`
- `106_Corless-Gonnet-Hare-Jeffrey-Knuth_1996_Lambert_W_Function.pdf`
- `107_Cramer_1919_Nullstellen_Riemannschen_Zetafunktion.pdf`
- `108_Croot_2003_Oscillations_Multiplicative_PlusMinusOne.pdf`
- `109_Croot_2007_Smooth_Numbers_Short_Intervals.pdf`
- `110_Dannon_2008_Riemann_Zeta_Function.pdf`
- `111_Das-Ismoilov-Ramos_2025_Fourier_Optimization_Pair_Correlation_Problems.pdf`
- `112_Daubechies-DeVore_2003_Bandlimited_Function_Stable_Sigma_Delta_Modulators.pdf`
- `113_Davenport-Heilbronn_1936_Zeros_Certain_Dirichlet_Series_I.pdf`
- `114_Davenport_1980_Multiplicative_Number_Theory_Second_Edition.pdf`
- `115_Debruyne-Vindas_2019_Complex_Tauberian_Theorems_Laplace_Transforms.pdf`
- `116_Deligne-Lusztig_1976_Representations_Reductive_Groups_Finite_Fields.pdf`
- `117_DellAnnaEtAl2016_2016_Violation_of_cluster_decomposition_and_absence_of_light_cones_in_local_integer_and_half_integer_spin_chains.pdf`
- `118_Denisov-Kolb-Wachtel_2015_Local_Asymptotics_Random_Walk_Excursions.pdf`
- `119_DerridaEnaudLebowitz2004_2004_The_asymmetric_exclusion_process_and_Brownian_excursions.pdf`
- `120_Deuring_1941_Typen_Multiplikatorenringe.pdf`
- `121_Diamond-Montgomery-Vorhauer_2006_Beurling_Primes_Large_Oscillation.pdf`
- `122_Diamond_1970_Asymptotic_Distribution_Beurling_Generalized_Integers.pdf`
- `123_Drmota_2009_Sum_Of_Digits_Of_Primes.pdf`
- `124_Durkan-Hughes-PearceCrump_2026_Generalisations_Landau_Gonek_Theorem.pdf`
- `125_DurrettIglehartMiller1977_1977_Weak_convergence_to_Brownian_meander_and_Brownian_excursion.pdf`
- `126_DuttEtAl2019_2019_Nature_Communications.pdf`
- `127_Edwards_1974_Riemanns_Zeta_Function.pdf`
- `128_Engert1970_1970_Finite_dimensional_translation_invariant_subspaces.pdf`
- `129_ErdosEtAl2012_2012_Spectral_statistics_of_Erd.pdf`
- `130_Fazzari-Gerspach-Minelli_2025_Selberg_CLT_Weighted_Linear_Statistics_Zeta_Zeros.pdf`
- `131_FazziGuglielmiMarkovsky2021_2021_A_gradient_system_approach_for_Hankel_structured_low_rank_approximation.pdf`
- `132_Ferrero-Washington_1979_Iwasawa_Invariant_Mu_p_Vanishes_Abelian_Number_Fields.pdf`
- `133_Fiori_2025_Note_Phragmen_Lindelof_Theorem.pdf`
- `134_Ford-Meng-Zaharescu_2017_Simultaneous_Fractional_Parts.pdf`
- `135_Ford-Soundararajan-Zaharescu_2009_Imaginary_Parts_II.pdf`
- `136_Ford-Zaharescu_2005_Imaginary_Parts_Zeta_Zeros.pdf`
- `137_Ford_2002_Vinogradov_Integral_Bounds_Riemann_Zeta.pdf`
- `138_Forrester-Lebowitz_2013_Local_CLT_Determinantal_Point_Processes.pdf`
- `139_Forrester-Mays_2015_Finite_Size_Corrections_RMT_Odlyzko_Data.pdf`
- `140_Franca-LeClair_2014_Statistical_Properties_Riemann_Zeros_Explicit_Equation_nth_Zero.pdf`
- `141_Franca-LeClair_2014_Theory_Zeros_Riemann_Zeta_And_Other_L_Functions.pdf`
- `142_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions.pdf`
- `143_Franca-LeClair_2015_Transcendental_Equations_Individual_Zeros_L_Functions_CNTP_Published.pdf`
- `144_Frantzikinakis2020_1908_Correlations_of_multiplicative_functions_along_deterministic_and_independent_sequences.pdf`
- `145_Friedlander-Granville_1993_Smoothing_Smooth_Numbers.pdf`
- `146_Fuchs_2025_Fejer_Kernel_Prime_Indicators.pdf`
- `147_Fujii_1974_Zeros_Dirichlet_L_Functions_I.pdf`
- `148_Fujii_1975_Difference_r_Consecutive_Ordinates_Zeros_Zeta.pdf`
- `149_Fujii_1975_Distribution_Zeros_Zeta_Short_Intervals.pdf`
- `150_Fujii_1981_Zeros_Dirichlet_L_Functions_II_Corrections.pdf`
- `151_GPY2009_2009_Annals_of_Mathematics.pdf`
- `152_Gallagher_1970_Large_Sieve_Density_Estimate_Near_Sigma_1.pdf`
- `153_Gallagher_1971_A_Larger_Sieve.pdf`
- `154_Gallier2016_2016_Spectral_theory_of_unsigned_and_signed_graphs_applications_to_graph_clustering_a_survey.pdf`
- `155_Gan-Qiu-Takeda_2014_Regularized_Siegel_Weil_Formula_Rallis_Inner_Product_arXiv_v3.pdf`
- `156_Gan-Takeda_2016_Proof_Howe_Duality_Conjecture_arXiv_v4.pdf`
- `157_Ghosh-Sarnak_2012_Real_Zeros_Hecke_Cusp_Forms.pdf`
- `158_Ghosh_2022_Statistics_Approximations_Zeros_Truncated_Symmetrized_Euler_Products.pdf`
- `159_Goldfeld_1982_Produits_Partiels_Euleriens_Courbes_Elliptiques.pdf`
- `160_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_II_Alternative_Hypothesis.pdf`
- `161_Goldston-Lee-Schettler-Suriajaya_2025_Pair_Correlation_Conjecture_I_Simple_Critical.pdf`
- `162_Gonek-Sahay_2024_Consecutive_Moderate_Gaps_Between_Zeros_Zeta.pdf`
- `163_Gonek_1985_Formula_Landau_Mean_Values_Zeta_INCOMPLETE_pp92-96.pdf`
- `164_Gonek_2012_Finite_Euler_Products_Riemann_Hypothesis.pdf`
- `165_GordinPeligrad2011_2011_On_the_functional_central_limit_theorem_via_martingale_approximation.pdf`
- `166_Gouezel2010_2010_Almost_sure_invariance_principle_for_dynamical_systems_by_spectral_methods.pdf`
- `167_Graham-Kolesnik_1991_Computing_Optimal_Exponent_Pairs.pdf`
- `168_Graham-Kolesnik_1991_Simplest_Van_Der_Corput_Estimates.pdf`
- `169_Granville-Soundararajan_2003_Decay_Of_Mean_Values.pdf`
- `170_Granville_2008_Smooth_Numbers_Survey.pdf`
- `171_Grayson_1984_Reduction_Theory_Using_Semistability.pdf`
- `172_GrepstadEtAl2019_1909_On_the_asymptotic_behaviour_of_the_sine_product.pdf`
- `173_Gross-Zagier_1985_On_Singular_Moduli.pdf`
- `174_Gross-Zagier_1986_Heegner_Points_Derivatives_L_Series.pdf`
- `175_Grosswald-Schnitzer_1978_Class_Modified_Zeta_L_Functions.pdf`
- `176_Guillera_2013_Sums_Nontrivial_Zeros_Riemann_Zeta.pdf`
- `177_Gunturk-Thao_2003_Ergodic_Dynamics_Sigma_Delta_Quantization.pdf`
- `178_Guth-Maynard_2026_New_Large_Value_Estimates_Dirichlet_Polynomials.pdf`
- `179_Hadamard_1896_Distribution_Zeros_Zeta_Consequences_Arithmetiques.pdf`
- `180_Hamburger_1921_Riemannsche_Funktionalgleichung_Zeta_Funktion_I.pdf`
- `181_Hardy-Littlewood-Polya_1934_Inequalities.pdf`
- `182_Hardy-Littlewood_1917_Riemann_Zeta_And_Distribution_Primes.pdf`
- `183_Harman-Pintz-Wolke_1985_Mobius_And_Liouville_Functions.pdf`
- `184_Harper_2013_Conditional_Bounds_Zeta_Moments.pdf`
- `185_Harper_2020_Moments_Random_Multiplicative_Functions_I.pdf`
- `186_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Dedekind_Zeta.pdf`
- `187_Hasanalizade-Shen-Wong_2022_Counting_Zeros_Riemann_Zeta.pdf`
- `188_HaugPrellberg2015_2015_Uniform_asymptotics_of_area_weighted_Dyck_paths.pdf`
- `189_Haynes-Zudilin_2015_Hankel_Determinants_Zeta_Values.pdf`
- `190_HeathBrown_2016_New_kth_Derivative_Estimate_Exponential_Sums_Vinogradov_arXiv_v3.pdf`
- `191_Helfgott-Thompson_2023_Summing_Mobius_Faster_Elementary_Algorithm.pdf`
- `192_HelfgottRadziwill2021_undated_HelfgottRadziwill2021.pdf`
- `193_HerichiLapidus2014_2014_Truncated_infinitesimal_shifts_spectral_operators_and_quantized_universality_of_the_Riemann_zeta_function.pdf`
- `194_HerreraMoree2018_2018_Coefficients_and_higher_order_derivatives_of_cyclotomic_polynomials_old_and_new.pdf`
- `195_HeuslerEtAl2007_2007_Periodic_orbit_theory_of_level_correlations.pdf`
- `196_Hiary-Leong-Yang_2024_Explicit_Bounds_Zeta_1_Line_arXiv_v3.pdf`
- `197_Hiary-Leong-Yang_2025_Explicit_Bounds_Zeta_1_Line.pdf`
- `198_Hiary-Patel-Yang_2024_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf`
- `199_Hida_2004_pAdic_Automorphic_Forms_Shimura_Varieties.pdf`
- `200_Hilberdink-Lapidus_2006_Beurling_Zeta_Generalised_Primes_Fractal_Membranes.pdf`
- `201_Hilberdink-Pushnitski_2023_Spectral_Asymptotics_LCM_Matrices.pdf`
- `202_Hilberdink_2006_Determinants_Multiplicative_Toeplitz_Matrices.pdf`
- `203_Hilberdink_2011_Flows_of_Mellin_Transforms.pdf`
- `204_Hilberdink_2015_Multiplicative_Toeplitz_Matrices_Riemann_Zeta.pdf`
- `205_Hilberdink_2017_Singular_Values_Multiplicative_Toeplitz_Matrices.pdf`
- `206_Hoffman1992_1992_Multiple_harmonic_series.pdf`
- `207_Hruscev-Nikolskii-Pavlov_1981_Unconditional_Bases_Exponentials_Reproducing_Kernels.pdf`
- `208_Hughes-Rudnick_2002_Linear_Statistics_Zeros_Zeta.pdf`
- `209_Hurst2026_2026_Practical_computations_of_the_Mertens_function_M_10.pdf`
- `210_Hurst_2018_Computations_Mertens_Function_Improved_Bounds.pdf`
- `211_Hurwitz_1899_Lemniscatische_Functionen.pdf`
- `212_Hutchinson_1925_Roots_Riemann_Zeta_Function.pdf`
- `213_Huxley_1976_Imperfect_Hybrid_Zero_Density_Theorem.pdf`
- `214_Huxley_1989_Exponential_Sums_Riemann_Zeta.pdf`
- `215_Igusa_2000_Introduction_Local_Zeta_Functions.pdf`
- `216_Ingham_1936_Trigonometrical_Inequalities_Theory_Series.pdf`
- `217_Inoue-Kobayashi-Toma_2026_Explicit_Extreme_Values_Argument_Zeta.pdf`
- `218_Inoue_2024_Note_On_r_Gaps_Between_Zeros_Zeta.pdf`
- `219_Ivic-Korolev_2018_Distribution_Values_Argument_Zeta.pdf`
- `220_Ivic_1985_Riemann_Zeta_Theory_Applications.pdf`
- `221_Ivic_2001_Sums_Over_Ordinates_Zeta_Zeros.pdf`
- `222_Ivic_2003_Riemann_Zeta_Dover_Reprint.pdf`
- `223_Janson_2007_Brownian_Excursion_Area_Wright_Constants.pdf`
- `224_Jerby_2023_New_Discriminant_Hardy_Z_Function_Corrected_Gram_Law.pdf`
- `225_Johansson_2001_Discrete_Orthogonal_Polynomial_Ensembles_Plancherel.pdf`
- `226_Johansson_2017_Arb_Arbitrary_Precision_Interval_Arithmetic.pdf`
- `227_Johansson_2018_Numerical_Integration_Ball_Arithmetic.pdf`
- `228_Jones-Sato-Wada-Wiens_1976_Diophantine_Representation_Primes.pdf`
- `229_Jun-Lee_2014_Dedekind_And_Exponential_Sums.pdf`
- `230_Jutila_1977_Zero_Density_Estimates_L_Functions.pdf`
- `231_Kaczorowski-Perelli_1999_Structure_Selberg_Class_I.pdf`
- `232_Kaczorowski-Pintz_1986_Oscillatory_Properties_Arithmetical_Functions_I.pdf`
- `233_KaczorowskiLanguascoPerelli2000_2000_A_note_on_Landau_s_formula.pdf`
- `234_Kaczorowski_1991_k_Functions_Multiplicative_Number_Theory_V.pdf`
- `235_Kaigh1976_1976_An_invariance_principle_for_random_walk_conditioned_by_a_late_return_to_zero.pdf`
- `236_Kanemitsu-Tsukada_2015_Hecke_Type_Zeta_Functions.pdf`
- `237_Kanemitsu-Tsukada_2015_Modular_Relation_Supremacy.pdf`
- `238_Kannan-Bachem_1979_Polynomial_Algorithms_Smith_Hermite_Normal_Forms.pdf`
- `239_Karatsuba-Voronin_1992_Vinogradov_Method_Riemann_Zeta.pdf`
- `240_Kargin_2013_Fluctuations_Riemann_Zeta_Zeros.pdf`
- `241_Kato_2004_pAdic_Hodge_Theory_Values_Zeta_Functions_Modular_Forms.pdf`
- `242_Katz_1975_Congruences_Bernoulli_Hurwitz.pdf`
- `243_Katz_1976_pAdic_Interpolation_Real_Analytic_Eisenstein_Series.pdf`
- `244_Katz_1977_Eisenstein_Measure_and_pAdic_Interpolation.pdf`
- `245_Katz_1977_Formal_Groups_and_pAdic_Interpolation.pdf`
- `246_Katz_1978_pAdic_L_Functions_for_CM_Fields.pdf`
- `247_Katz_1981_Divisibilities_Congruences_Cartier_Duality.pdf`
- `248_Keating_2022_Hierarchical_Structure_Trace_Formula.pdf`
- `249_Kellerhals_1995_Volumes_in_Hyperbolic_5_Space_Author.pdf`
- `250_Kelly-Le_2018_Van_Der_Corput_Sets_Compact_Groups.pdf`
- `251_KhorunzhiyMarckert2009_2009_Uniform_bounds_for_exponential_moment_of_maximum_of_a_Dyck_path.pdf`
- `252_Kinnunen_1997_Hardy_Littlewood_Maximal_Function_Sobolev_Function.pdf`
- `253_Knopp_1994_Dirichlet_Series_Riemann_Functional_Equation.pdf`
- `254_Koblitz_1983_pAdic_Eigen_Functions_Kubert_Distributions.pdf`
- `255_Kolountzakis-Revesz_2003_Turan_Extremal_Problem.pdf`
- `256_Kolyvagin_1990_Euler_Systems.pdf`
- `257_Komori-Matsumoto-Tsumura_2023_Zeta_Functions_Root_Systems.pdf`
- `258_Korolev-Laurincikas_2023_Approximation_Mellin_Transform_Zeta_Axioms.pdf`
- `259_Korolev_2010_Gram_Law_Selberg_Conjecture_Zeros_Izv_Math.pdf`
- `260_Korolev_2011_Gram_Law_Argument_Riemann_Zeta_arXiv.pdf`
- `261_Korolev_2012_Gram_Law_Argument_Riemann_Zeta_Publ_Inst_Math.pdf`
- `262_Korolev_2012_Gram_Law_Riemann_Zeta.pdf`
- `263_Korolev_2016_Extreme_Values_S_Short_Intervals_Indian_J.pdf`
- `264_Korolev_2016_Gram_Law_Theory_Zeta_Part1_Proc_Steklov.pdf`
- `265_Kotnik-vandeLune_2004_Order_Mertens_Function.pdf`
- `266_Kousha2012_2012_Asymptotic_behavior_and_the_moderate_deviation_principle_for_the_maximum_of_a_Dyck_path.pdf`
- `267_Kowalski-Robert-Wu_2007_Small_Gaps_And_B_Free_Numbers.pdf`
- `268_Kowalski_2021_Exponential_Sums_Finite_Fields_Elementary.pdf`
- `269_Kowalski_2021_Exponential_Sums_Finite_Fields_II.pdf`
- `270_Kozma-Lev_2011_Exponential_Riesz_Bases_Discrepancy_BMO.pdf`
- `271_Kurasov-Sarnak_2020_Stable_Polynomials_Crystalline_Measures.pdf`
- `272_LMS_2015_Atle_Selberg_Obituary.pdf`
- `273_Labahn-Neiger-Zhou_2018_Hermite_Normal_Form_Polynomial_Matrix.pdf`
- `274_Lagarias-Li_2016_Lerch_Zeta_IV_Hecke_Operators_arXiv_v3.pdf`
- `275_Lagarias2007_2007_Li_coefficients_for_automorphic_functions.pdf`
- `276_Landau_1905_Uber_Einen_Satz_Von_Tschebyschef.pdf`
- `277_Landau_1912_Nullstellen_Zetafunktion.pdf`
- `278_Lapidus-VanFrankenhuysen_2000_Fractal_Geometry_Number_Theory.pdf`
- `279_Lau-Liu-Wu_2010_Symmetric_Square_L_Function_Coefficients.pdf`
- `280_Lazard_1955_Groupes_de_Lie_Formels.pdf`
- `281_LeClair_2016_Riemann_Hypothesis_Random_Walks_Zeta_Case.pdf`
- `282_LeeLeong2024_2024_New_explicit_bounds_for_the_Mertens_function_and_the_reciprocal_of_the_Riemann_zeta_function.pdf`
- `283_Leong_2024_Explicit_Estimates_Log_Derivative_Reciprocal_Zeta.pdf`
- `284_Lester-Matomaki-Radziwill_2015_Small_Scale_Zeros_Modular_Forms.pdf`
- `285_Lev-Olevskii_2015_Quasicrystals_Poisson_Summation_Formula.pdf`
- `286_Lev_2012_Riesz_Bases_Exponentials_Multiband_Spectra_Preprint.pdf`
- `287_LiYang2023_2023_An_improvement_on_Gauss_s_circle_problem_and_Dirichlet_s_divisor_problem.pdf`
- `288_Li_2019_Zeta_L_Functions_Number_Theory_Combinatorics.pdf`
- `289_Lieb-Loss_2001_Analysis_Second_Edition.pdf`
- `290_Lindqvist-Seip_1998_Note_Greatest_Common_Divisor_Matrices.pdf`
- `291_Littlewood_1924_Zeros_Riemann_Zeta_Function.pdf`
- `292_Liu2022_2022_Multiplicative_functions_resembling_the_M_bius_function.pdf`
- `293_Lubin-Tate_1965_Formal_Complex_Multiplication_Local_Fields.pdf`
- `294_Lyubarskii-Seip_1997_Complete_Interpolating_Sequences_Paley_Wiener_Muckenhoupt_Ap.pdf`
- `295_LyubarskiiVershynin2010_2010_Uncertainty_principles_and_vector_quantization.pdf`
- `296_Matiyasevich2007a_1983_Hidden_Life_of_Riemann_s_Zeta_Function_1_Arrow_Bow_and_Targets.pdf`
- `297_Matiyasevich2007b_2007_Hidden_Life_of_Riemann_s_Zeta_Function_2_Electrons_and_Trains.pdf`
- `298_Matomaki-Radziwill-Tao_2015_Averaged_Chowla_Conjecture.pdf`
- `299_Matomaki-Radziwill_2015_Liouville_Short_Intervals.pdf`
- `300_Matomaki-Radziwill_2015_Sign_Changes_Hecke_Eigenvalues.pdf`
- `301_Matomaki-Radziwill_2016_Multiplicative_Functions_Short_Intervals.pdf`
- `302_Matomaki-Shao-Tao-Teravainen_2023_Higher_Uniformity_Arithmetic_Functions.pdf`
- `303_Matomaki-Teravainen_2023_Mobius_Function_All_Short_Intervals.pdf`
- `304_Matomaki_2010_Smooth_Numbers_Short_Intervals.pdf`
- `305_Matomaki_2016_Smooth_Numbers_Short_Intervals_II.pdf`
- `306_MelottiSaias2020_2020_On_path_partitions_of_the_divisor_graph.pdf`
- `307_Mirsky_1949_Frequency_Pairs_Square_Free_Numbers_Given_Difference.pdf`
- `308_Monien_2009_Hankel_Determinants_Dirichlet_Series.pdf`
- `309_Montgomery-Vaughan_1974_Hilberts_Inequality.pdf`
- `310_MontgomerySoundararajan2004_2004_Comm_Math_Phys.pdf`
- `311_Montgomery_1973_Pair_Correlation_Zeros_Zeta.pdf`
- `312_Moriwaki_2009_Continuity_Volumes_Arithmetic_Varieties_arXiv_v2.pdf`
- `313_Mossinghoff-Trudgian-Yang_2022_Explicit_Zero_Free_Regions_Riemann_Zeta.pdf`
- `314_MossinghoffOliveiraTrudgian2021_2021_The_distribution_of_k_free_numbers.pdf`
- `315_Motohashi_1977_On_Gallaghers_Prime_Number_Theorem.pdf`
- `316_Motohashi_1978_Primes_in_Arithmetic_Progressions.pdf`
- `317_Motohashi_1997_Spectral_Theory_Riemann_Zeta.pdf`
- `318_Muellner2017_2017_Automatic_sequences_fulfill_the_Sarnak_conjecture.pdf`
- `319_MullerEtAl2005_2005_Periodic_orbit_theory_of_universality_in_quantum_chaos.pdf`
- `320_Murahara-Onozuka_2025_Equidistribution_A_Points_Zeta_Derivatives.pdf`
- `321_MussardoLeClair2021_2021_Randomness_of_M_obius_coefficients_and_Brownian_motion_growth_of_the_Mertens_function_and_the_Riemann_hypothes.pdf`
- `322_Nakamura_2020_Dirichlet_Series_Periodic_Coefficients_Functional_Equation.pdf`
- `323_Ng2004_2004_Proc_London_Math_Soc.pdf`
- `324_Nishigaki_2024_Consecutive_Level_Spacings_GUE_Ratio.pdf`
- `325_Nishigaki_2025_Consecutive_Level_Spacings_CUE_Finite_Size_Zeta.pdf`
- `326_Norvidas_2011_Entire_Functions_Exponential_Sums.pdf`
- `327_Nunes2015_2015_Journal_of_Number_Theory.pdf`
- `328_Odlyzko-TeRiele_1985_Disproof_Mertens_Conjecture.pdf`
- `329_Odlyzko_1987_Distribution_Spacings_Between_Zeros_Zeta.pdf`
- `330_OganesyanHuse2007_2007_Localization_of_interacting_fermions_at_high_temperature.pdf`
- `331_Ohsawa-Takegoshi_1987_Extension_L2_Holomorphic_Functions.pdf`
- `332_Olevskii-Ulanovskii_2020_Fourier_Quasicrystals_Unit_Masses.pdf`
- `333_Olver_1974_Introduction_Asymptotics_Special_Functions.pdf`
- `334_Olver_1997_Asymptotics_Special_Functions_AK_Peters_Reprint.pdf`
- `335_OwczarekPrellberg2014_2014_Pressure_exerted_by_a_vesicle_on_a_surface.pdf`
- `336_Patel-Yang_2024_Explicit_Sub_Weyl_Bound_Zeta_Critical_Line.pdf`
- `337_Patel_2022_Explicit_Upper_Bound_Zeta_1_Line.pdf`
- `338_Patterson_1988_Introduction_Riemann_Zeta_Function.pdf`
- `339_Patterson_1988_Zeros_Zeta_And_Prime_Number_Theorem.pdf`
- `340_PeligradUtev2005_2005_A_new_maximal_inequality_and_invariance_principle_for_stationary_sequences.pdf`
- `341_Perelli_2016_Converse_Theorems_Zeta_Selberg_Class.pdf`
- `342_Perfekt-Pushnitski_2018_Spectrum_Multiplicative_Hilbert_Matrix.pdf`
- `343_PillaiYin2014_2014_Universality_of_covariance_matrices.pdf`
- `344_Pintz_2026_Oscillation_Mobius_Function_Zeta_Zeros.pdf`
- `345_Platt-Trudgian_2014_Improved_Explicit_Bound_Zeta_Critical_Line_arXiv_v2.pdf`
- `346_Platt-Trudgian_2015_Zeroes_Partial_Sums_Zeta_Function_arXiv_v2.pdf`
- `347_Platt-Trudgian_2021_RH_True_Up_To_3e12.pdf`
- `348_Platt_2017_Isolating_Nontrivial_Zeros_Zeta.pdf`
- `349_Popov_1985_Transfer_Functions_Riemann_Zeta.pdf`
- `350_Porubsky_2000_Covering_Systems_Kubert_Identities.pdf`
- `351_Rademacher_1959_Phragmen_Lindelof_Theorem_Applications.pdf`
- `352_Radziwill-Soundararajan_2015_Quadratic_Twists_Central_L_Values.pdf`
- `353_Rallis_1984_Injectivity_Properties_Liftings_Weil_Representations.pdf`
- `354_Ramachandra_1976_Problems_Analytic_Number_Theory.pdf`
- `355_Revers_2026_Improved_Explicit_Estimate_Zeta_Critical_Line.pdf`
- `356_Ribet_1976_Modular_Construction_Unramified_p_Extensions.pdf`
- `357_Richard_2005_Q_Functional_Equations_Excursion_Moments.pdf`
- `358_Riemann-Wilkins_1859_Prime_Counting_English_Translation.pdf`
- `359_RigalZadunaisky2015_2015_Twisted_semigroup_algebras.pdf`
- `360_Robert_1975_Regularite_Ideaux_Premiers_CM.pdf`
- `361_Robert_1978_Nombres_de_Hurwitz_et_Unites_Elliptiques.pdf`
- `362_RodgersTao2018_2018_RodgersTao2018.pdf`
- `363_Roesler_1986_Riemann_Hypothesis_Eigenvalue_Problem.pdf`
- `364_Roesler_1987_Riemann_Hypothesis_Eigenvalue_Problem_II.pdf`
- `365_Rosser-Schoenfeld_1962_Approximate_Formulas_Functions_Prime_Numbers.pdf`
- `366_Rosser_1941_Explicit_Bounds_Functions_Prime_Numbers.pdf`
- `367_Rota_1964_Foundations_Combinatorial_Theory_Mobius_Functions.pdf`
- `368_Rudin_1987_Real_Complex_Analysis_Third_Edition.pdf`
- `369_Saffari-Vaughan_1977_Fractional_Parts_X_Over_N_II.pdf`
- `370_Sawin_2022_Mobius_Cancellation_Polynomial_Sequences.pdf`
- `371_Schechter_2002_Principles_Functional_Analysis_Second_Edition.pdf`
- `372_Sekatskii-Beltraminelli-Merlini_2012_Integrals_Logarithm_Zeta_RH.pdf`
- `373_Sekatskii_2013_Generalized_Bombieri_Lagarias_Li_Criterion.pdf`
- `374_Sekatskii_2014_Generalized_Li_Criterion_Zeroes_Location.pdf`
- `375_Selberg-Chowla_1967_On_Epstein_Zeta_Function.pdf`
- `376_Shalev_2025_Log_Sine_Integrals_Apery_Like_Sums.pdf`
- `377_Sheth_2025_Euler_Products_Centre_Chebyshev_Bias.pdf`
- `378_Shir-MartinezAzcona-Chenu_2025_Surmise_Level_Spacing_Beyond_Nearest.pdf`
- `379_Sidi_2003_Riemann_And_Generalized_Zeta_Extrapolation.pdf`
- `380_Siegel_1922_Satz_Hamburger_Funktionalgleichung_Zetafunktion.pdf`
- `381_Sorensen_2020_A_Patching_Lemma.pdf`
- `382_Soule_2003_Bound_Torsion_K_Theory_Algebraic_Integers.pdf`
- `383_Soundararajan_2009_Partial_Sums_Mobius_Function.pdf`
- `384_Soundararajan_2010_Smooth_Numbers_Short_Intervals.pdf`
- `385_StampachStovicek2020_2020_On_Hankel_matrices_commuting_with_Jacobi_matrices_from_the_Askey_scheme.pdf`
- `386_Stepanov_1969_On_the_Number_of_Points_of_a_Hyperelliptic_Curve.pdf`
- `387_Stepanov_1972_Congruences_in_Two_Unknowns.pdf`
- `388_Suzuki2025Hilbert_2025_On_the_Hilbert_space_derived_from_the_Weil_distribution.pdf`
- `389_Szekelyhidi1982_1982_Note_on_exponential_polynomials.pdf`
- `390_Tao-Teravainen_2018_Odd_Order_Logarithmically_Averaged_Chowla.pdf`
- `391_Tao-Teravainen_2019_Structure_Logarithmically_Averaged_Correlations.pdf`
- `392_Tao-Trudgian-Yang_2025_New_Exponent_Pairs_Zero_Density_Additive_Energy_arXiv_v1.pdf`
- `393_Tao_2016_Logarithmically_Averaged_Chowla_Elliott_Two_Point.pdf`
- `394_Taylor-Wiles_1995_Ring_Theoretic_Properties_Certain_Hecke_Algebras.pdf`
- `395_Tenenbaum_2015_Analytic_Probabilistic_Number_Theory.pdf`
- `396_Tenenbaum_2017_Generalized_Mertens_Sums.pdf`
- `397_Titchmarsh-HeathBrown_1986_Theory_Riemann_Zeta_Function.pdf`
- `398_Titchmarsh_1939_Theory_Functions_Second_Edition.pdf`
- `399_Trudgian-Yang_2024_Toward_Optimal_Exponent_Pairs_arXiv_v3.pdf`
- `400_Trudgian_2008_Gram_Law_Fails_Positive_Proportion_Of_The_Time.pdf`
- `401_Trudgian_2012_Improved_Upper_Bound_Argument_Zeta.pdf`
- `402_Trudgian_2014_Improved_Upper_Bound_Argument_Zeta_II.pdf`
- `403_Turing_1953_Some_Calculations_Riemann_Zeta_Function.pdf`
- `404_Umezawa_2019_Multiple_Zeta_Values_Iterated_Log_Sine_arXiv_v1.pdf`
- `405_Vaughan_1996_Eigenvalues_Redheffer_Matrix_II.pdf`
- `406_Vega_2023_Simple_Proof_Riemann_Hypothesis.pdf`
- `407_Volchkov_1995_Equality_Equivalent_Riemann_Hypothesis_Russian.pdf`
- `408_Weil_1952_Formules_Explicites_Nombres_Premiers_Transcription_VellaChemla.pdf`
- `409_Wilf_2004_Redheffer_Matrix_Partially_Ordered_Set.pdf`
- `410_Xylouris_2011_Nullstellen_Dirichletschen_L_Funktionen_Kleinste_Primzahl.pdf`
- `411_Yang_2024_Explicit_Bounds_Zeta_Critical_Strip_Zero_Free_Region.pdf`
- `412_Young_1974_Inequalities_Perturbation_Theorem_Paley_Wiener.pdf`
- `413_Youvan_2024_Phase_Winding_Riemann_Zeta.pdf`
- `414_Zagier_2006_The_Mellin_Transform_and_Related_Analytic_Techniques.pdf`
- `415_Zhang-Williams_1995_Values_Riemann_Zeta_Integrals.pdf`
- `416_Zhang_2013_Normalization_Beurling_Generalized_Primes_RH.pdf`
- `417_Zhao_2016_Multiple_Zeta_Polylogarithms_Special_Values.pdf`
- `418_Zhao_2026_Density_Results_r_Gaps_Between_Zeros_Zeta.pdf`
- `419_deBruijn1950_1950_The_roots_of_trigonometric_integrals.pdf`
- `420_deLaValleePoussin_1896_Recherches_Analytiques_Nombres_Premiers_I.pdf`
- `421_vonMangoldt_1895_Zu_Riemanns_Abhandlung_Anzahl_Primzahlen.pdf`
- `422_vonMangoldt_1905_Verteilung_Nullstellen_Riemannschen_Funktion_Xi.pdf`
