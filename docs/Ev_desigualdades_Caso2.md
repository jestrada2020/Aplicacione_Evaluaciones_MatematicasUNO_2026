---
title: "Evaluación de Desigualdades (Caso 2)"
output: html_document
---


# Evaluación de Desigualdades (Caso 2)

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

Bienvenido a la **Evaluación de Desigualdades (Caso 2)**. Este examen interactivo consta de **16 preguntas** diseñadas para evaluar tu comprensión sobre la traducción de enunciados verbales a desigualdades algebraicas y viceversa.

> **Instrucciones:**
> * Presta mucha atención a la redacción y los términos técnicos ("no es menor que", "a lo más", "al menos", "entre", "no negativo").
> * El **50% de las preguntas (8 preguntas)** te pedirá seleccionar las **afirmaciones verdaderas**.
> * El otro **50% de las preguntas (8 preguntas)** te pedirá seleccionar **únicamente las afirmaciones falsas**.
> * Al final de la prueba, podrás visualizar un reporte detallado con tus respuestas y una recomendación de estudio personalizada.
> * ¡Mucho éxito!

---

## Bloque 1: Desigualdades del 1 al 8

En esta primera sección evaluaremos la traducción directa de enunciados básicos sobre signos, intervalos y límites superiores o inferiores.

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443650912620"><div class="learnr-question-text">Analiza el enunciado: $x$ es negativo. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443650912620" value="1" data-correct="true" > $x < 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443650912620" value="2" data-correct="true" > La variable $x$ toma únicamente valores menores que cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443650912620" value="3" data-correct="true" > El número real $0$ no está incluido en el conjunto de soluciones de la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443650912620" value="4" data-correct="false" > $x \le 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443650912620" value="5" data-correct="false" > $x > 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443650912620" value="6" data-correct="false" > $x \ge 0$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443650912620')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Identificaste correctamente todas las afirmaciones verdaderas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que el término 'negativo' excluye al cero.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443651056095"><div class="learnr-question-text">Analiza el enunciado: $y$ es no negativo. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651056095" value="1" data-correct="true" > $y < 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651056095" value="2" data-correct="true" > La variable $y$ sólo puede tomar valores estrictamente menores que cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651056095" value="3" data-correct="true" > $y > 0$ (se omite el caso en el que la variable vale exactamente cero)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651056095" value="4" data-correct="false" > $y \ge 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651056095" value="5" data-correct="false" > El valor $y = 0$ está incluido de forma válida dentro de la solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651056095" value="6" data-correct="false" > El conjunto incluye a todos los números reales positivos y al cero.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651056095')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Seleccionaste todas las afirmaciones falsas correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que 'no negativo' incluye a todos los reales positivos y al cero. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443651151759"><div class="learnr-question-text">Analiza el enunciado: $q$ es menor o igual a $\pi$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651151759" value="1" data-correct="true" > $q \le \pi$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651151759" value="2" data-correct="true" > El valor máximo que puede tomar la variable $q$ es exactamente el número real $\pi$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651151759" value="3" data-correct="true" > El número real $\pi$ está incluido en el conjunto solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651151759" value="4" data-correct="false" > $q < \pi$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651151759" value="5" data-correct="false" > $q > \pi$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651151759" value="6" data-correct="false" > $q \ge \pi$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651151759')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Identificación correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la inclusión del extremo en desigualdades débiles.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443651255958"><div class="learnr-question-text">Analiza el enunciado: $d$ está entre $4$ y $5$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651255958" value="1" data-correct="true" > $d \le 4 \text{ o } d \ge 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651255958" value="2" data-correct="true" > Los extremos $4$ y $5$ están incluidos de manera obligatoria dentro del conjunto solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651255958" value="3" data-correct="true" > $4 \le d \le 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651255958" value="4" data-correct="false" > $4 < d < 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651255958" value="5" data-correct="false" > Representa un intervalo completamente abierto denotado por $(4, 5)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651255958" value="6" data-correct="false" > El valor real $d = 4.5$ satisface de forma válida la desigualdad.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651255958')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Detectaste con éxito todos los enunciados falsos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. El término 'entre' generalmente denota un intervalo abierto (sin incluir los extremos). Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443651372497"><div class="learnr-question-text">Analiza el enunciado: $t$ no es menor que $5$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651372497" value="1" data-correct="true" > $t \ge 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651372497" value="2" data-correct="true" > La variable $t$ es mayor o igual a $5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651372497" value="3" data-correct="true" > El valor entero $t = 5$ satisface de manera correcta la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651372497" value="4" data-correct="false" > $t > 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651372497" value="5" data-correct="false" > $t < 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651372497" value="6" data-correct="false" > $t \le 5$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651372497')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Magnífico! Has traducido correctamente la equivalencia.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. 'No menor que' es equivalente a ser mayor o igual.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443651529242"><div class="learnr-question-text">Analiza el enunciado: El negativo de $z$ no es mayor a $3$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651529242" value="1" data-correct="true" > $-z > 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651529242" value="2" data-correct="true" > Es equivalente a decir que la variable $z$ es menor o igual a $-3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651529242" value="3" data-correct="true" > $z < -3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651529242" value="4" data-correct="false" > $-z \le 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651529242" value="5" data-correct="false" > Es equivalente a plantear la desigualdad despejada $z \ge -3$ (al multiplicar por $-1$ e invertir la dirección del sentido).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651529242" value="6" data-correct="false" > El valor $z = -2$ satisface plenamente la condición dada.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651529242')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Magnífico! Has identificado las trampas de los signos negativos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ten cuidado al despejar variables con signos negativos; recuerda que multiplicar por $-1$ invierte la desigualdad.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443651628236"><div class="learnr-question-text">Analiza el enunciado: El cociente de $p$ y $q$ es a lo más $7$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651628236" value="1" data-correct="true" > $\frac{p}{q} \le 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651628236" value="2" data-correct="true" > El valor máximo posible que puede tomar la división de $p$ entre $q$ es exactamente $7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651628236" value="3" data-correct="true" > Representa que el cociente es menor o igual que la constante numérica $7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651628236" value="4" data-correct="false" > $\frac{p}{q} < 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651628236" value="5" data-correct="false" > $\frac{p}{q} > 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651628236" value="6" data-correct="false" > $\frac{p}{q} \ge 7$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651628236')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Concepto de cota superior dominado.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. 'A lo más' establece un tope o límite superior (menor o igual).</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443651717594"><div class="learnr-question-text">Analiza el enunciado: El recíproco de $w$ es al menos $9$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651717594" value="1" data-correct="true" > $\frac{1}{w} < 9$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651717594" value="2" data-correct="true" > $\frac{1}{w} \le 9$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651717594" value="3" data-correct="true" > $w \ge 9$ (confundir el número con su recíproco)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651717594" value="4" data-correct="false" > $\frac{1}{w} \ge 9$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651717594" value="5" data-correct="false" > Representa que la división de 1 entre $w$ es mayor o igual a $9$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651717594" value="6" data-correct="false" > El valor del recíproco de $w$ puede ser exactamente el entero $9$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651717594')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Detectaste todos los enunciados incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. 'Al menos' establece un piso o límite inferior (mayor o igual) y el recíproco es $1/w$. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Desigualdades del 9 al 16

En esta sección avanzamos con expresiones que involucran valores absolutos, signos específicos y fracciones.

### Pregunta 9 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443651836610"><div class="learnr-question-text">Analiza el enunciado: El valor absoluto de $x$ es mayor que $7$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651836610" value="1" data-correct="true" > $|x| > 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651836610" value="2" data-correct="true" > Geométricamente, representa que la distancia del número $x$ al origen (cero) es estrictamente mayor que $7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651836610" value="3" data-correct="true" > Es equivalente a la unión de los intervalos abiertos: $x < -7$ o $x > 7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651836610" value="4" data-correct="true" > El valor negativo $x = -8$ satisface correctamente la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651836610" value="5" data-correct="false" > $|x| \ge 7$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651836610" value="6" data-correct="false" > El valor extremo $x = -7$ está incluido de manera válida en las soluciones.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651836610')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has comprendido la distancia en la recta real.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la interpretación geométrica y algebraica del valor absoluto.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443651949252"><div class="learnr-question-text">Analiza el enunciado: $b$ es positivo. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443651949252" value="1" data-correct="true" > $b \le 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651949252" value="2" data-correct="true" > El valor neutro $b = 0$ está incluido de manera válida en las soluciones.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651949252" value="3" data-correct="true" > $b \ge 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651949252" value="4" data-correct="false" > $b > 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651949252" value="5" data-correct="false" > La variable $b$ toma únicamente valores estrictamente mayores que cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443651949252" value="6" data-correct="false" > El conjunto solución está representado por el intervalo abierto $(0, \infty)$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443651949252')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Has descartado con éxito todos los errores.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que los números positivos son estrictamente mayores que cero (excluyendo al cero). Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 11 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443652053246"><div class="learnr-question-text">Analiza el enunciado: $s$ es no positivo. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443652053246" value="1" data-correct="true" > $s \le 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652053246" value="2" data-correct="true" > La variable $s$ puede tomar valores negativos o el cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652053246" value="3" data-correct="true" > El valor $s = 0$ satisface de forma correcta la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652053246" value="4" data-correct="false" > $s < 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652053246" value="5" data-correct="false" > $s > 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652053246" value="6" data-correct="false" > $s \ge 0$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443652053246')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has dominado este término.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. 'No positivo' incluye a los números negativos y al cero.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 12 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443652146216"><div class="learnr-question-text">Analiza el enunciado: $w$ es mayor o igual a $-4$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443652146216" value="1" data-correct="true" > $w < -4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652146216" value="2" data-correct="true" > La variable $w$ solo puede tomar valores estrictamente menores que $-4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652146216" value="3" data-correct="true" > $w > -4$ (se omite el valor límite de la desigualdad)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652146216" value="4" data-correct="false" > $w \ge -4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652146216" value="5" data-correct="false" > El valor exacto $w = -4$ forma parte de las soluciones correctas.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652146216" value="6" data-correct="false" > El intervalo de solución correspondiente es el intervalo semi-cerrado $[-4, \infty)$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443652146216')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has encontrado los planteamientos incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda incluir el extremo en desigualdades no estrictas. Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 13 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443652234777"><div class="learnr-question-text">Analiza el enunciado: $c$ está entre $\frac{1}{5}$ y $\frac{1}{3}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443652234777" value="1" data-correct="true" > $\frac{1}{5} < c < \frac{1}{3}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652234777" value="2" data-correct="true" > Representa de forma geométrica un intervalo abierto con extremos en las fracciones indicadas.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652234777" value="3" data-correct="true" > El valor de la variable $c$ es estrictamente mayor que $0.20$ y estrictamente menor que $0.333...$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652234777" value="4" data-correct="false" > $\frac{1}{5} \le c \le \frac{1}{3}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652234777" value="5" data-correct="false" > Los valores límites extremos $\frac{1}{5}$ y $\frac{1}{3}$ forman parte de la solución.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652234777" value="6" data-correct="false" > $c < \frac{1}{5} \text{ o } c > \frac{1}{3}$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443652234777')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Fantástico! Dominas los intervalos de fracciones.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Analiza con cuidado la exclusión de los extremos fraccionarios.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 14 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443652331380"><div class="learnr-question-text">Analiza el enunciado: $p$ es no mayor que $-2$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443652331380" value="1" data-correct="true" > $p > -2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652331380" value="2" data-correct="true" > La variable $p$ toma únicamente valores mayores que el número real $-2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652331380" value="3" data-correct="true" > $p < -2$ (se excluye incorrectamente la igualdad con el extremo)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652331380" value="4" data-correct="false" > $p \le -2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652331380" value="5" data-correct="false" > El valor extremo $p = -2$ satisface de forma válida la desigualdad.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652331380" value="6" data-correct="false" > Representa de manera simplificada que $p$ es menor o igual a $-2$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443652331380')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Espectacular! Has completado el descarte de manera brillante.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. 'No mayor que' equivale a menor o igual (incluyendo al extremo). Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 15 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17798443652437177"><div class="learnr-question-text">Analiza el enunciado: El negativo de $m$ no es menor que $-2$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443652437177" value="1" data-correct="true" > $-m \ge -2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652437177" value="2" data-correct="true" > Es equivalente algebraicamente a plantear que la variable $m$ es menor o igual a $2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652437177" value="3" data-correct="true" > El valor entero $m = 1$ satisface correctamente la condición dada.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652437177" value="4" data-correct="false" > $-m > -2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652437177" value="5" data-correct="false" > $-m < -2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652437177" value="6" data-correct="false" > $m \ge 2$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443652437177')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Destreza en desigualdades con signos negativos demostrada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Multiplicar por $-1$ para despejar $m$ invierte el sentido de la desigualdad.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 16 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17798443652526851"><div class="learnr-question-text">Analiza el enunciado: El cociente de $r$ y $s$ es al menos $\frac{1}{5}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17798443652526851" value="1" data-correct="true" > $\frac{r}{s} < \frac{1}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652526851" value="2" data-correct="true" > $\frac{r}{s} \le \frac{1}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652526851" value="3" data-correct="true" > $\frac{r}{s} > \frac{1}{5}$ (se excluye el caso límite de la igualdad)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652526851" value="4" data-correct="false" > $\frac{r}{s} \ge \frac{1}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652526851" value="5" data-correct="false" > El resultado de la división entre $r$ y $s$ puede ser exactamente igual al decimal $0.2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17798443652526851" value="6" data-correct="false" > Representa matemáticamente que el cociente es mayor o igual a la fracción $\frac{1}{5}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17798443652526851')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has finalizado toda la evaluación detectando todos los planteamientos incorrectos con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. 'Al menos' establece un límite inferior (mayor o igual). Busca las afirmaciones falsas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17798443652762300', 16, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente en la traducción y análisis de desigualdades matemáticas. Has alcanzado un nivel de lógica excelente y comprendes con total claridad los límites y la notación de intervalos. ¡Sigue así, estás listo para desafíos mayores!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún hay conceptos de límites y sentido de desigualdades que puedes pulir. Te sugerimos repasar con detenimiento términos clave como \'a lo más\' (menor o igual), \'al menos\' (mayor o igual) y qué sucede con el sentido de la desigualdad al operar con números negativos (como en $-z \\le 3$). ¡Con un poco más de repaso lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar a fondo la traducción de frases límite (\'no es menor que\', \'no positivo\', \'a lo más\') y resolver paso a paso los ejercicios iniciales de la recta real y sus intervalos. ¡No te desanimes, con la práctica y atención al detalle dominarás las desigualdades!')">Calcular Mis Resultados</button><div id="sr17798443652762300"></div>
