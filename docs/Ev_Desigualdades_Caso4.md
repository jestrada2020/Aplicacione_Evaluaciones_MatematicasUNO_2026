---
title: "Evaluación de Desigualdades (Caso 4)"
output: html_document
---


# Evaluación de Desigualdades (Caso 4)

<style>
/* Estilos Premium para la Evaluación de Desigualdades (Caso 4) - Tema Amatista */
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
  background: linear-gradient(135deg, #8b5cf6 0%, #6d28d9 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  text-align: center;
  margin-bottom: 2rem;
  box-shadow: 0 10px 25px -5px rgba(139, 92, 246, 0.3);
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
  border-left: 5px solid #8b5cf6;
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
  border-color: #8b5cf6 !important;
  background-color: #f5f3ff !important;
  transform: translateX(4px);
}

.answer-option.selected {
  background-color: #ede9fe !important;
  border-color: #8b5cf6 !important;
}

/* Botones */
.btn-primary, .btn-submit, .btn-action {
  background: linear-gradient(135deg, #8b5cf6 0%, #6d28d9 100%) !important;
  border: none !important;
  color: white !important;
  font-weight: 600 !important;
  font-family: 'Outfit', sans-serif !important;
  padding: 0.6rem 1.5rem !important;
  border-radius: 8px !important;
  transition: all 0.2s ease !important;
  box-shadow: 0 4px 12px rgba(139, 92, 246, 0.2) !important;
}

.btn-primary:hover, .btn-submit:hover {
  transform: translateY(-1px) !important;
  box-shadow: 0 6px 16px rgba(139, 92, 246, 0.3) !important;
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

.alert-warning {
  background-color: #fffbeb !important;
  border-color: #f59e0b !important;
  color: #78350f !important;
  border-radius: 8px !important;
}

/* Insignias de Verdadero/Falso */
.badge-true {
  background: #dbeafe;
  color: #1e40af;
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

Bienvenido a la **Evaluación de Desigualdades (Caso 4)**. Este examen interactivo consta de **8 preguntas** diseñadas para evaluar tu capacidad de simplificar analíticamente expresiones con valor absoluto bajo diferentes condiciones algebraicas.

> **Instrucciones:**
> * Analiza con detenimiento el signo del argumento (la expresión dentro de las barras) bajo la condición establecida.
> * Recuerda la definición formal: $|u| = u$ si $u \ge 0$, y $|u| = -u$ si $u < 0$.
> * El **50% de las preguntas (4 preguntas)** te pedirá seleccionar las **afirmaciones verdaderas**.
> * El **50% de las preguntas (4 preguntas)** te pedirá seleccionar **únicamente las afirmaciones falsas**.
> * Al final de la prueba, podrás visualizar un reporte detallado con tus respuestas y una recomendación de estudio personalizada.
> * ¡Mucho éxito!

---

## Bloque Único: Simplificación de Valores Absolutos

En esta sección evaluaremos de forma analítica el comportamiento y la simplificación de diferentes funciones de valor absoluto.

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513805587035"><div class="learnr-question-text">Si $x < -3$, entonces $|3 + x| = ?$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513805587035" value="1" data-correct="true" > $-3 - x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805587035" value="2" data-correct="true" > La expresión dentro del valor absoluto, $3 + x$, es estrictamente negativa para cualquier $x < -3$, por lo que su valor absoluto equivale a su opuesto algebraico.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805587035" value="3" data-correct="true" > Si evaluamos un caso particular en el dominio como $x = -4$, obtenemos $|3 + (-4)| = |-1| = 1$, lo cual coincide con la fórmula simplificada $-3 - (-4) = 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805587035" value="4" data-correct="false" > $3 + x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805587035" value="5" data-correct="false" > $x - 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805587035" value="6" data-correct="false" > El resultado simplificado es un número negativo para cualquier valor de $x$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513805587035')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has comprendido la aplicación del valor absoluto para argumentos negativos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Puesto que $x &lt; -3$, sumando 3 a ambos lados se obtiene $3 + x &lt; 0$. Al ser el argumento negativo, se debe multiplicar por $-1$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513805701636"><div class="learnr-question-text">Si $x > 5$, entonces $|5 - x| = ?$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513805701636" value="1" data-correct="true" > $5 - x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805701636" value="2" data-correct="true" > La expresión dentro del valor absoluto es positiva porque el valor absoluto nunca puede devolver un resultado negativo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805701636" value="3" data-correct="true" > El resultado simplificado es $-x - 5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805701636" value="4" data-correct="false" > $x - 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805701636" value="5" data-correct="false" > Dado que $x > 5$, la cantidad $5 - x$ es menor que cero, por lo que su valor absoluto equivale a su negativo $-(5 - x) = x - 5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805701636" value="6" data-correct="false" > Para el caso particular $x = 6$, la simplificación correcta da $1$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513805701636')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todas las afirmaciones incorrectas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que para $x &gt; 5$, la cantidad $5 - x$ es estrictamente negativa.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513805788201"><div class="learnr-question-text">Si $x < 2$, entonces $|2 - x| = ?$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513805788201" value="1" data-correct="true" > $2 - x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805788201" value="2" data-correct="true" > Puesto que $x < 2$, la diferencia $2 - x$ es estrictamente positiva, por lo que el valor absoluto no altera la expresión.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805788201" value="3" data-correct="true" > El valor absoluto de cualquier expresión estrictamente positiva es la expresión misma.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805788201" value="4" data-correct="false" > $x - 2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805788201" value="5" data-correct="false" > $-2 - x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805788201" value="6" data-correct="false" > La expresión se reduce a la constante $2$ para cualquier valor de $x$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513805788201')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Simplificación correcta para argumento positivo.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Analiza el signo del argumento: si $x &lt; 2$, entonces la resta $2 - x$ es estrictamente positiva.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513805875429"><div class="learnr-question-text">Si $x \ge -7$, entonces $|7 + x| = ?$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513805875429" value="1" data-correct="true" > $-7 - x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805875429" value="2" data-correct="true" > La expresión dentro del valor absoluto es estrictamente negativa en todo el dominio indicado.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805875429" value="3" data-correct="true" > El resultado simplificado es $x - 7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805875429" value="4" data-correct="false" > $7 + x$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805875429" value="5" data-correct="false" > Dado que $x \ge -7$, la expresión $7 + x$ es mayor o igual a cero, por lo que su valor absoluto conserva la misma expresión.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805875429" value="6" data-correct="false" > Si elegimos el valor extremo $x = -7$, la expresión se anula de forma válida: $|7 + (-7)| = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513805875429')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todos los enunciados falsos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que si $x \ge -7$, entonces $7 + x \ge 0$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513805973648"><div class="learnr-question-text">Si $a < b$, entonces $|a - b| = ?$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513805973648" value="1" data-correct="true" > $b - a$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805973648" value="2" data-correct="true" > Al ser $a < b$, la diferencia $a - b$ es estrictamente menor a cero, lo cual requiere multiplicar por $-1$ para obtener un resultado positivo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805973648" value="3" data-correct="true" > La distancia geométrica entre $a$ y $b$ cuando $a$ está a la izquierda de $b$ se representa como la longitud del segmento $b - a$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805973648" value="4" data-correct="false" > $a - b$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805973648" value="5" data-correct="false" > $-a - b$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513805973648" value="6" data-correct="false" > El valor absoluto se cancela directamente dando como resultado cero.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513805973648')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la distancia geométrica y su signo correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Dado que $a &lt; b$, la resta $a - b$ da un resultado negativo, lo que obliga a cambiar el orden al simplificar el valor absoluto.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513806075350"><div class="learnr-question-text">Si $a > b$, entonces $|a - b| = ?$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513806075350" value="1" data-correct="true" > $b - a$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806075350" value="2" data-correct="true" > La diferencia $a - b$ es siempre negativa ya que estamos restando variables.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806075350" value="3" data-correct="true" > El resultado simplificado de la distancia es $-a + b$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806075350" value="4" data-correct="false" > $a - b$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806075350" value="5" data-correct="false" > Dado que $a$ es mayor que $b$, la resta de $a$ menos $b$ produce una cantidad mayor a cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806075350" value="6" data-correct="false" > La expresión $|a - b|$ representa la distancia entre $a$ y $b$, que al ser $a > b$ equivale a la resta directa $a - b$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513806075350')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los planteamientos incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Si $a &gt; b$, entonces $a - b &gt; 0$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513806162727"><div class="learnr-question-text">Simplificar $|x^2 + 4| = ?$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513806162727" value="1" data-correct="true" > $x^2 + 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806162727" value="2" data-correct="true" > El término $x^2$ es siempre mayor o igual a cero para cualquier número real $x$, por lo que $x^2 + 4$ es estrictamente positivo en todo su dominio.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806162727" value="3" data-correct="true" > Al ser el argumento siempre positivo, no se requiere ningún cambio de signo al quitar las barras de valor absoluto.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806162727" value="4" data-correct="false" > $-x^2 - 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806162727" value="5" data-correct="false" > $x^2 - 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806162727" value="6" data-correct="false" > La expresión depende del signo de la variable $x$ y se debe separar en dos ramas para su resolución.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513806162727')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has demostrado dominio en el comportamiento de funciones cuadráticas positivas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. El cuadrado de cualquier número real es no negativo, por lo que $x^2 + 4$ es siempre mayor o igual a 4 (estrictamente positivo).</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513806247654"><div class="learnr-question-text">Simplificar $|-x^2 - 1| = ?$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513806247654" value="1" data-correct="true" > $-x^2 - 1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806247654" value="2" data-correct="true" > El valor absoluto simplemente elimina el signo menos de adelante dando como resultado $-x^2 + 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806247654" value="3" data-correct="true" > La expresión resultante es negativa para valores negativos de la variable $x$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806247654" value="4" data-correct="false" > $x^2 + 1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806247654" value="5" data-correct="false" > Puesto que $-x^2 - 1$ es siempre estrictamente menor que cero para cualquier real $x$, su valor absoluto es su opuesto algebraico, el cual es $x^2 + 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513806247654" value="6" data-correct="false" > Para cualquier valor de $x$ (por ejemplo, $x = 0$), la expresión se evalúa de manera correcta dando un resultado positivo ($1$).</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513806247654')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has concluido la prueba analizando correctamente los opuestos cuadráticos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que $-x^2 - 1$ es estrictamente menor que cero en todos los reales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796513806494410', 8, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente en la simplificación y el análisis analítico de expresiones con valor absoluto bajo condiciones dadas. Has alcanzado un nivel de lógica excelente y comprendes con total claridad cuándo una cantidad es negativa y cómo opera el valor absoluto sobre ella. ¡Sigue así, estás listo para desafíos mayores!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún puedes pulir la aplicación de signos al remover barras de valor absoluto cuando el argumento es negativo (como en el caso de $|-x^2 - 1|$ o $|3+x|$ cuando $x < -3$). Recuerda que un argumento negativo requiere multiplicar por $-1$ a toda la expresión. ¡Con un poco más de repaso lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar a fondo la definición formal de valor absoluto y el análisis de signos de variables, diferencias ($a - b$ según su orden) y expresiones cuadráticas. ¡No te desanimes, con la práctica y la atención al detalle dominarás el valor absoluto!')">Calcular Mis Resultados</button><div id="sr17796513806494410"></div>
