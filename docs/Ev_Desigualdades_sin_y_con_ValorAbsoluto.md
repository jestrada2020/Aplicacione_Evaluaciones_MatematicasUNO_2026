---
title: "Evaluación de Desigualdades (Sin y Con Valor Absoluto)"
output: html_document
---


# Evaluación de Desigualdades (Sin y Con Valor Absoluto)

<style>
/* Estilos Premium para la Evaluación de Desigualdades */
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap');

body {
  font-family: 'Inter', sans-serif;
  background: #f7f9fc;
  color: #2e384d;
}

h1, h2, h3, h4, .tutorial-title {
  font-family: 'Outfit', sans-serif;
  font-weight: 700;
  color: #1e2638;
}

.tutorial-title {
  background: linear-gradient(135deg, #a855f7 0%, #7e22ce 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  text-align: center;
  margin-bottom: 2rem;
  box-shadow: 0 10px 25px -5px rgba(168, 85, 247, 0.3);
  font-size: 2.5rem;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.section.level2 {
  background: white;
  border-radius: 16px;
  padding: 2rem;
  margin-bottom: 2rem;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
  border: 1px solid #eef2f6;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.section.level2:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 20px -8px rgba(0, 0, 0, 0.08);
}

/* Estilo para las preguntas de learnr */
.tutorial-question {
  background-color: #fafbfc;
  border-radius: 12px;
  padding: 1.5rem;
  border-left: 5px solid #a855f7;
  margin-top: 1rem;
}

.tutorial-question-title {
  font-family: 'Outfit', sans-serif;
  font-size: 1.2rem;
  font-weight: 600;
  color: #1e2638;
  margin-bottom: 1rem;
}

/* Opciones de respuesta */
.answer-option {
  background: white !important;
  border: 1.5px solid #e2e8f0 !important;
  border-radius: 8px !important;
  padding: 0.75rem 1rem !important;
  margin-bottom: 0.5rem !important;
  transition: all 0.2s ease !important;
  cursor: pointer;
}

.answer-option:hover {
  border-color: #a855f7 !important;
  background-color: #fcfaff !important;
  transform: translateX(4px);
}

.answer-option.selected {
  background-color: #f3e8ff !important;
  border-color: #a855f7 !important;
}

/* Botones */
.btn-primary, .btn-submit, .btn-action {
  background: linear-gradient(135deg, #a855f7 0%, #7e22ce 100%) !important;
  border: none !important;
  color: white !important;
  font-weight: 600 !important;
  font-family: 'Outfit', sans-serif !important;
  padding: 0.6rem 1.5rem !important;
  border-radius: 8px !important;
  transition: all 0.2s ease !important;
  box-shadow: 0 4px 12px rgba(168, 85, 247, 0.2) !important;
}

.btn-primary:hover, .btn-submit:hover {
  transform: translateY(-1px) !important;
  box-shadow: 0 6px 16px rgba(168, 85, 247, 0.3) !important;
  opacity: 0.95;
}

/* Alertas de retroalimentación */
.alert-success {
  background-color: #ecfdf5 !important;
  border-color: #10b981 !important;
  color: #065f46 !important;
  border-radius: 8px !important;
}

.alert-danger {
  background-color: #fef2f2 !important;
  border-color: #ef4444 !important;
  color: #991b1b !important;
  border-radius: 8px !important;
}

/* Insignias de Verdadero/Falso */
.badge-true {
  background: #e0f2fe;
  color: #0369a1;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.85rem;
  font-weight: 600;
  display: inline-block;
  margin-bottom: 0.5rem;
}

.badge-false {
  background: #fee2e2;
  color: #991b1b;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.85rem;
  font-weight: 600;
  display: inline-block;
  margin-bottom: 0.5rem;
}
</style>



## Introducción

Bienvenido a la **Evaluación Completa de Desigualdades (Sin y Con Valor Absoluto)**. Este examen interactivo consta de **17 preguntas** estructuradas en dos grandes bloques:

1. **Desigualdades sin Valor Absoluto (Preguntas 1 a 8)**: Ejercicios sobre inecuaciones lineales simples, lineales con fracciones complejas y desigualdades racionales con puntos críticos y restricciones de dominio.
2. **Desigualdades con Valor Absoluto (Preguntas 9 a 17)**: Ejercicios sobre inecuaciones clásicas de distancia, inecuaciones con coeficientes, inecuaciones racionales con valor absoluto, y inecuaciones avanzadas con suma o resta de valores absolutos.

> **Instrucciones:**
> * Presta mucha atención a la notación de intervalos y a las restricciones (indeterminaciones en el denominador, inclusión/exclusión de extremos).
> * Alrededor del **50% de las preguntas** te pedirá seleccionar las **afirmaciones verdaderas**, y el otro **50%** te pedirá identificar **únicamente las afirmaciones falsas**.
> * Al final de la prueba, podrás calcular tu puntuación en tiempo real y obtener una recomendación detallada según tus resultados.
> * ¡Mucho éxito en tu evaluación!

---

## Bloque 1: Desigualdades sin Valor Absoluto

En esta sección evaluaremos la resolución de inecuaciones lineales, operaciones con fracciones algebraicas y análisis por intervalos de expresiones racionales.

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617324416271"><div class="learnr-question-text">Analiza la desigualdad: $\dfrac{3(x-4)}{2} \geq \frac{5}{4}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617324416271" value="1" data-correct="true" > $x \geq \frac{29}{6}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324416271" value="2" data-correct="true" > El extremo inferior $\frac{29}{6}$ está incluido en el conjunto solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324416271" value="3" data-correct="true" > El número real $0$ no satisface la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324416271" value="4" data-correct="false" > $x > \frac{29}{6}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324416271" value="5" data-correct="false" > $x \leq \frac{29}{6}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324416271" value="6" data-correct="false" > $x \geq \frac{23}{6}$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617324416271')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto correctamente la desigualdad lineal con fracciones.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la multiplicación por constantes y el despeje lineal.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617324548017"><div class="learnr-question-text">Analiza la desigualdad: $5x-4 < 3x+5$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617324548017" value="1" data-correct="true" > $x \geq \frac{9}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324548017" value="2" data-correct="true" > La variable $x$ puede tomar de forma válida el valor real $4.5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324548017" value="3" data-correct="true" > Representa un intervalo cerrado denotado por $(-\infty, 4.5]$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324548017" value="4" data-correct="false" > $x < \frac{9}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324548017" value="5" data-correct="false" > Representa un intervalo completamente abierto en la recta real.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324548017" value="6" data-correct="false" > El valor entero $x = 4$ satisface de forma correcta la condición.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617324548017')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Has identificado todas las afirmaciones falsas con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Busca las afirmaciones que son matemáticamente incorrectas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617324684739"><div class="learnr-question-text">Analiza la desigualdad: $\frac{x-5}{3} + \frac{x+4}{2} \leq \frac{x+3}{6}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617324684739" value="1" data-correct="true" > $x \leq \frac{1}{4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324684739" value="2" data-correct="true" > El valor decimal $x = 0.25$ satisface plenamente la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324684739" value="3" data-correct="true" > El conjunto solución está representado por el intervalo semi-infinito $(-\infty, 0.25]$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324684739" value="4" data-correct="false" > $x \geq \frac{1}{4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324684739" value="5" data-correct="false" > $x < 0$ (excluye incorrectamente las soluciones positivas)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324684739" value="6" data-correct="false" > $x \leq \frac{5}{4}$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617324684739')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Operación con fracciones dominada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda multiplicar por el mínimo común múltiplo (6) para simplificar las fracciones.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617324775929"><div class="learnr-question-text">Analiza la desigualdad: $\frac{2x-1}{5} - \frac{3x+1}{3} \geq \frac{x-5}{15}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617324775929" value="1" data-correct="true" > $x \geq -\frac{3}{10}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324775929" value="2" data-correct="true" > Al resolver, el sentido de la desigualdad permanece sin cambios.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324775929" value="3" data-correct="true" > $x \leq -\frac{13}{10}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324775929" value="4" data-correct="false" > $x \leq -\frac{3}{10}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324775929" value="5" data-correct="false" > El sentido de la desigualdad se invierte al dividir por la constante negativa $-10$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324775929" value="6" data-correct="false" > El valor real $x = -0.3$ está incluido de manera válida en la solución.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617324775929')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Has identificado todas las trampas de signos de forma brillante.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ten especial cuidado al operar con divisiones por coeficientes negativos. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617324876424"><div class="learnr-question-text">Analiza la desigualdad racional: $\dfrac{x-3}{x+2} < 0$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617324876424" value="1" data-correct="true" > $x \in (-2, 3)$ o $-2 < x < 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324876424" value="2" data-correct="true" > El extremo $x = -2$ se excluye obligatoriamente porque causa una división por cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324876424" value="3" data-correct="true" > El conjunto de soluciones representa un intervalo completamente abierto y finito.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324876424" value="4" data-correct="false" > $x \in [-2, 3]$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324876424" value="5" data-correct="false" > $x < -2$ o $x > 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324876424" value="6" data-correct="false" > La variable $x$ puede tomar el valor real $-3$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617324876424')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has dominado el análisis de desigualdades racionales básicas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa los puntos críticos del numerador y del denominador, y el análisis de signos por intervalos.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617324967538"><div class="learnr-question-text">Analiza la desigualdad racional: $\dfrac{2x+4}{x-2} > 0$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617324967538" value="1" data-correct="true" > $-2 < x < 2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324967538" value="2" data-correct="true" > La variable $x$ puede tomar de forma válida el valor real $0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324967538" value="3" data-correct="true" > $x \leq -2$ o $x \geq 2$ (se incluyen de manera incorrecta los extremos)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324967538" value="4" data-correct="false" > $x < -2$ o $x > 2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324967538" value="5" data-correct="false" > Representa la unión de dos intervalos abiertos e infinitos en los extremos.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617324967538" value="6" data-correct="false" > El valor de $x = -2.5$ pertenece al conjunto solución.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617324967538')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Identificaste correctamente todos los enunciados falsos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que la desigualdad es estrictamente mayor que cero y debes buscar las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617325061728"><div class="learnr-question-text">Analiza la desigualdad racional: $\dfrac{x-4}{x-3} \geq 2$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325061728" value="1" data-correct="true" > $x \in [2, 3)$ o $2 \leq x < 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325061728" value="2" data-correct="true" > El extremo $x = 3$ se excluye porque indefine la fracción, mientras que $x = 2$ se incluye por ser desigualdad no estricta.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325061728" value="3" data-correct="true" > El valor real $x = 2.5$ satisface plenamente la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325061728" value="4" data-correct="false" > $x \in [2, 3]$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325061728" value="5" data-correct="false" > $x \leq 2$ o $x > 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325061728" value="6" data-correct="false" > $x \geq 2$ (omite el límite de la indeterminación en $x=3$)</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325061728')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la desigualdad racional con constante no nula con total dominio.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Cuidado al restar la constante y no multiplicar cruzado sin analizar el signo de $x-3$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617325159351"><div class="learnr-question-text">Analiza la desigualdad racional: $\dfrac{2x+4}{x-3} \leq 3$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325159351" value="1" data-correct="true" > $3 < x \leq 13$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325159351" value="2" data-correct="true" > La variable $x$ puede tomar el valor real $3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325159351" value="3" data-correct="true" > $x \leq 3$ o $x \geq 13$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325159351" value="4" data-correct="false" > $x < 3$ o $x \geq 13$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325159351" value="5" data-correct="false" > El número $13$ forma parte del conjunto solución de forma cerrada.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325159351" value="6" data-correct="false" > El valor de $x = 0$ pertenece de forma correcta a las soluciones.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325159351')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Detectaste con éxito todas las afirmaciones incorrectas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la simplificación y el signo resultante del análisis por intervalos. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Desigualdades con Valor Absoluto

En esta sección evaluaremos la interpretación de desigualdades con valor absoluto como distancias, desigualdades simultáneas, inecuaciones racionales con valor absoluto y sumas/restas de valores absolutos en intervalos de la recta numérica.

### Pregunta 9 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617325251617"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto: $\mid x-3\mid < 8$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325251617" value="1" data-correct="true" > $-5 < x < 11$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325251617" value="2" data-correct="true" > Representa que la distancia del número $x$ al punto $3$ es estrictamente menor a $8$ unidades.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325251617" value="3" data-correct="true" > El valor de $x = 0$ satisface plenamente la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325251617" value="4" data-correct="false" > $-5 \leq x \leq 11$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325251617" value="5" data-correct="false" > $x < -5$ o $x > 11$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325251617" value="6" data-correct="false" > El valor extremo $x = 11$ está incluido en las soluciones.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325251617')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Concepto de distancia y valor absoluto dominado.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la interpretación geométrica y algebraica de desigualdades menores que una constante.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617325348991"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto: $\mid x-6\mid > 6$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325348991" value="1" data-correct="true" > $0 < x < 12$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325348991" value="2" data-correct="true" > El valor real $x = 6$ satisface de forma correcta la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325348991" value="3" data-correct="true" > $x \leq 0$ o $x \geq 12$ (se incluyen de manera incorrecta los límites)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325348991" value="4" data-correct="false" > $x < 0$ o $x > 12$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325348991" value="5" data-correct="false" > Geométricamente, representa que la distancia de $x$ al origen o punto $6$ en la recta real es estrictamente mayor que $6$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325348991" value="6" data-correct="false" > El valor de $x = -1$ es una solución totalmente válida.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325348991')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Has encontrado todas las afirmaciones falsas correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que la distancia mayor a $6$ excluye el intervalo central cerrado. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 11 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617325445729"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto: $\mid 3x-4\mid \leq 5$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325445729" value="1" data-correct="true" > $-\frac{1}{3} \leq x \leq 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325445729" value="2" data-correct="true" > Los dos valores límites extremos $-\frac{1}{3}$ y $3$ están incluidos en la solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325445729" value="3" data-correct="true" > El entero $x = 0$ satisface de forma correcta la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325445729" value="4" data-correct="false" > $x \leq -\frac{1}{3}$ o $x \geq 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325445729" value="5" data-correct="false" > $-\frac{1}{3} < x < 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325445729" value="6" data-correct="false" > El valor de $x = 4$ pertenece al conjunto solución.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325445729')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has calculado con total precisión los extremos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la resolución simultánea de desigualdades con coeficientes en valor absoluto.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 12 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617325534659"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto: $\mid 2x-5\mid \geq 3$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325534659" value="1" data-correct="true" > $1 < x < 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325534659" value="2" data-correct="true" > La variable $x$ puede tomar el valor de $2$ dentro de la solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325534659" value="3" data-correct="true" > $x < 1$ o $x > 4$ (se excluyen incorrectamente los extremos cerrados)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325534659" value="4" data-correct="false" > $x \leq 1$ o $x \geq 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325534659" value="5" data-correct="false" > El conjunto solución está constituido por la unión de dos intervalos infinitos semicerrados.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325534659" value="6" data-correct="false" > El valor de $x = 5$ es plenamente válido como solución.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325534659')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Identificación correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa los intervalos exteriores resultantes de una desigualdad de tipo mayor o igual. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 13 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617325619990"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto: $\left| \dfrac{2(x+5)}{3} \right| \leq \frac{4}{5}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325619990" value="1" data-correct="true" > $-\frac{31}{5} \leq x \leq -\frac{19}{5}$ o $-6.2 \leq x \leq -3.8$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325619990" value="2" data-correct="true" > El conjunto solución está compuesto únicamente por números reales negativos.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325619990" value="3" data-correct="true" > El valor entero $x = -4$ satisface plenamente la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325619990" value="4" data-correct="false" > $x \leq -6.2$ o $x \geq -3.8$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325619990" value="5" data-correct="false" > $-6.2 < x < -3.8$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325619990" value="6" data-correct="false" > El valor entero $x = 0$ forma parte de las soluciones correctas.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325619990')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Operación algebraica precisa con fracciones en valor absoluto.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Opera paso a paso: multiplica por 3, divide entre 2 y resta 5 manteniendo la desigualdad.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 14 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617325706014"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto y fracción: $\left| \dfrac{x + 5}{x - 3} \right| \leq 3$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325706014" value="1" data-correct="true" > $1 \leq x \leq 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325706014" value="2" data-correct="true" > El punto de indeterminación $x = 3$ forma parte del conjunto solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325706014" value="3" data-correct="true" > $x < 1$ o $x > 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325706014" value="4" data-correct="false" > $x \leq 1$ o $x \geq 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325706014" value="5" data-correct="false" > El conjunto de soluciones excluye por completo al intervalo abierto $(1, 7)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325706014" value="6" data-correct="false" > El valor real $x = 0$ satisface de forma correcta la desigualdad.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325706014')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Resolviste con éxito una de las desigualdades racionales más retadoras.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Elevar al cuadrado ambos lados (dado que son no negativos) facilita notablemente la solución. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 15 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617325804583"><div class="learnr-question-text">Analiza la desigualdad con valor absoluto y fracción: $\left| \dfrac{x + 1}{2 - x} \right| \geq 2$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325804583" value="1" data-correct="true" > $x \in [1, 2) \cup (2, 5]$ o $1 \leq x \leq 5$ con $x \neq 2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325804583" value="2" data-correct="true" > El número real $2$ debe excluirse obligatoriamente de la solución porque indefine el denominador inicial.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325804583" value="3" data-correct="true" > El valor extremo $x = 5$ satisface plenamente la condición.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325804583" value="4" data-correct="false" > $1 \leq x \leq 5$ (olvida excluir el punto de indeterminación $2$)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325804583" value="5" data-correct="false" > $x \leq 1$ o $x \geq 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325804583" value="6" data-correct="false" > $x \in (1, 5)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325804583')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Fantástico! Dominio absoluto sobre las restricciones y análisis racional.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. No olvides restringir el dominio ($x \neq 2$) y realizar el análisis elevando al cuadrado.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 16 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617325905571"><div class="learnr-question-text">Analiza la desigualdad con suma de valores absolutos: $\mid 3x - 4\mid + \mid 2x - 3\mid \leq 3$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325905571" value="1" data-correct="true" > $x \leq \frac{4}{5}$ o $x \geq 2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325905571" value="2" data-correct="true" > El conjunto solución está compuesto por dos intervalos infinitos separados.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325905571" value="3" data-correct="true" > $\frac{4}{5} < x < 2$ (excluye incorrectamente los extremos cerrados)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325905571" value="4" data-correct="false" > $\frac{4}{5} \leq x \leq 2$ (o $0.8 \leq x \leq 2$)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325905571" value="5" data-correct="false" > La resolución requiere dividir la recta real en tres intervalos delimitados por los puntos críticos $x = 1.33...$ y $x = 1.5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325905571" value="6" data-correct="false" > El valor entero $x = 1$ satisface correctamente la desigualdad.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325905571')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto de manera impecable una desigualdad de suma de valores absolutos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda resolver por casos analizando el signo de cada término absoluto en los tres intervalos. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 17 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617325995523"><div class="learnr-question-text">Analiza la desigualdad con resta de valores absolutos: $\mid x - 4\mid - \mid 5 - x\mid \geq 2$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617325995523" value="1" data-correct="true" > El conjunto de soluciones es el conjunto vacío (denotado por $\emptyset$ o no tiene solución).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325995523" value="2" data-correct="true" > La diferencia de estos valores absolutos tiene un valor máximo de $1$, haciendo imposible que sea mayor o igual a $2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325995523" value="3" data-correct="true" > Para todo número real $x$, la expresión $|x-4| - |x-5| \leq 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325995523" value="4" data-correct="false" > $x \geq 5.5$ (error algebraico común de ignorar restricciones)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325995523" value="5" data-correct="false" > $x \leq 4.5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617325995523" value="6" data-correct="false" > El conjunto solución incluye a todos los números reales.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617325995523')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Espectacular! Has completado la prueba de manera extraordinaria identificando un conjunto vacío geométrico y algebraico.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Analiza el comportamiento algebraico por casos o aplica la desigualdad triangular.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796617326203374', 17, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente en la resolución y análisis de desigualdades matemáticas, tanto lineales, racionales como de valor absoluto. Has alcanzado un nivel de lógica excelente y comprendes con total claridad los límites, las restricciones de dominio y las propiedades geométricas del valor absoluto. ¡Sigue así, estás listo para desafíos mayores!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún hay conceptos de límites, inecuaciones racionales (como las restricciones en el denominador en $x \\neq 2$) y resolución de valor absoluto por casos que puedes pulir. Te sugerimos repasar con detenimiento términos clave y resolver paso a paso los ejercicios de inecuaciones cuadráticas y racionales. ¡Con un poco más de repaso lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar a fondo las propiedades del valor absoluto, cómo analizar los signos en intervalos en inecuaciones racionales (asegurando excluir las indeterminaciones) y resolver paso a paso los ejercicios iniciales de la recta real. ¡No te desanimes, con la práctica y atención al detalle dominarás las desigualdades!')">Calcular Mis Resultados</button><div id="sr17796617326203374"></div>
