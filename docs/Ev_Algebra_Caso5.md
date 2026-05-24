---
title: "Evaluación de Álgebra: Despeje de Variables (Caso 5)"
output: html_document
---


# Evaluación de Álgebra: Despeje de Variables (Caso 5)

<style>
/* Estilos Premium para la Evaluación de Álgebra (Caso 5) - Tema Amatista */
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
  font-size: 1.25rem;
  font-weight: 600;
  color: #1e2638;
  margin-bottom: 1rem;
  line-height: 1.5;
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

Bienvenido a la **Evaluación de Álgebra: Despeje de Variables (Caso 5)**. Este examen interactivo consta de **22 preguntas** diseñadas para evaluar tu destreza en la manipulación y aislamiento de variables en ecuaciones literales algebraicas Complejas.

> **Instrucciones:**
> * Resuelve los despejes algebraicos de forma detallada antes de seleccionar tus opciones.
> * Presta atención a las operaciones inversas, potenciación, radicación y propiedades de ecuaciones cuadráticas.
> * El **50% de las preguntas (11 preguntas)** te pedirá seleccionar las **afirmaciones verdaderas**.
> * El **50% de las preguntas (11 preguntas)** te pedirá seleccionar **únicamente las afirmaciones falsas**.
> * Al final de la prueba, podrás visualizar un reporte detallado con tus respuestas y una recomendación de estudio personalizada.
> * ¡Mucho éxito!

---

## Bloque 1: Despejes del 1 al 11

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513746866158"><div class="learnr-question-text">Dada la ecuación $V=\frac{1}{3}\pi h(r^{2}+R^{2}+rR)$, despeje la variable $R$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513746866158" value="1" data-correct="true" > $R = \dfrac{-r \pm \sqrt{\dfrac{12V}{\pi h} - 3r^{2}}}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746866158" value="2" data-correct="true" > Físicamente, si asumimos dimensiones estrictamente positivas, el radio mayor se simplifica como $R = \dfrac{-r + \sqrt{\dfrac{12V}{\pi h} - 3r^{2}}}{2}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746866158" value="3" data-correct="true" > La ecuación es cuadrática con respecto a $R$ y se resuelve aplicando la fórmula general sobre $R^2 + rR + \left(r^2 - \frac{3V}{\pi h}\right) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746866158" value="4" data-correct="false" > $R = \sqrt{\dfrac{3V}{\pi h} - r^{2} - rR}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746866158" value="5" data-correct="false" > $R = \dfrac{-r \pm \sqrt{3r^{2} - \dfrac{12V}{\pi h}} }{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746866158" value="6" data-correct="false" > El término independiente en la ecuación cuadrática de $R$ es $\frac{3V}{\pi h}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513746866158')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto el despeje de la ecuación cuadrática correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Distribuye la expresión, forma una cuadrática en términos de $R$ y aplica la fórmula cuadrática.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513746992852"><div class="learnr-question-text">Dada la ecuación $C=2\pi r$, despeje la variable $r$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513746992852" value="1" data-correct="true" > $r = 2\pi C$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746992852" value="2" data-correct="true" > $r = \dfrac{2\pi}{C}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746992852" value="3" data-correct="true" > $r = C - 2\pi$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746992852" value="4" data-correct="false" > $r = \dfrac{C}{2\pi}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746992852" value="5" data-correct="false" > La variable $r$ es directamente proporcional a la circunferencia $C$ e inversamente proporcional al factor constante $2\pi$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513746992852" value="6" data-correct="false" > Al dividir ambos lados entre $2\pi$ se obtiene el despeje lineal directo.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513746992852')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas sobre este despeje básico.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513747093680"><div class="learnr-question-text">Dada la ecuación $P=2w+2l$, despeje la variable $l$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747093680" value="1" data-correct="true" > $l = \dfrac{P - 2w}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747093680" value="2" data-correct="true" > $l = \dfrac{P}{2} - w$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747093680" value="3" data-correct="true" > Restando $2w$ a ambos lados se obtiene $2l = P - 2w$, que al dividirse entre $2$ genera el despeje correcto.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747093680" value="4" data-correct="false" > $l = P - w$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747093680" value="5" data-correct="false" > $l = \dfrac{P + 2w}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747093680" value="6" data-correct="false" > $l = 2P - w$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747093680')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has aislado el cateto o dimensión lineal correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Aísla el término con $l$ restando $2w$ y luego divide toda la expresión entre $2$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513747185072"><div class="learnr-question-text">Dada la ecuación $l=Prt$, despeje la variable $t$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747185072" value="1" data-correct="true" > $t = \dfrac{Pr}{l}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747185072" value="2" data-correct="true" > $t = l - Pr$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747185072" value="3" data-correct="true" > $t = l \cdot P \cdot r$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747185072" value="4" data-correct="false" > $t = \dfrac{l}{Pr}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747185072" value="5" data-correct="false" > La variable $t$ es inversamente proporcional al producto de $P$ y $r$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747185072" value="6" data-correct="false" > Dividir la igualdad por el producto $Pr$ aísla de forma directa la variable $t$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747185072')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado todas las afirmaciones incorrectas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Selecciona únicamente las afirmaciones falsas del despeje.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513747277843"><div class="learnr-question-text">Dada la ecuación $S=2\pi rh$, despeje la variable $h$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747277843" value="1" data-correct="true" > $h = \dfrac{S}{2\pi r}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747277843" value="2" data-correct="true" > La variable $h$ es inversamente proporcional al producto del radio $r$ y de la constante $2\pi$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747277843" value="3" data-correct="true" > Dividiendo ambos lados de la ecuación entre el factor $2\pi r$ se aísla $h$ directamente.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747277843" value="4" data-correct="false" > $h = S - 2\pi r$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747277843" value="5" data-correct="false" > $h = \dfrac{2\pi r}{S}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747277843" value="6" data-correct="false" > $h = \dfrac{S \cdot r}{2\pi}$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747277843')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Despeje lineal de superficie de cilindro correcto.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Para aislar la altura $h$, divide toda la superficie lateral entre el perímetro de la base $2\pi r$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513747361030"><div class="learnr-question-text">Dada la ecuación $A=\frac{1}{2}bh$, despeje la variable $h$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747361030" value="1" data-correct="true" > $h = \dfrac{A}{2b}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747361030" value="2" data-correct="true" > $h = 2A - b$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747361030" value="3" data-correct="true" > $h = \dfrac{b}{2A}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747361030" value="4" data-correct="false" > $h = \dfrac{2A}{b}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747361030" value="5" data-correct="false" > Multiplicar por $2$ a ambos lados de la ecuación genera $2A = bh$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747361030" value="6" data-correct="false" > La altura $h$ es inversamente proporcional a la base $b$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747361030')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Identificación correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Selecciona únicamente las afirmaciones incorrectas del despeje del área del triángulo.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513747447075"><div class="learnr-question-text">Dada la ecuación $V=\frac{1}{3}\pi r^{2}h$, despeje la variable $h$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747447075" value="1" data-correct="true" > $h = \dfrac{3V}{\pi r^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747447075" value="2" data-correct="true" > Multiplicar la ecuación por $3$ y luego dividir entre $\pi r^2$ genera el despeje lineal correcto de $h$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747447075" value="3" data-correct="true" > La altura $h$ es inversamente proporcional al cuadrado del radio de la base $r$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747447075" value="4" data-correct="false" > $h = \dfrac{V}{3\pi r^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747447075" value="5" data-correct="false" > $h = 3V - \pi r^{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747447075" value="6" data-correct="false" > $h = \dfrac{\pi r^{2}}{3V}$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747447075')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has despejado la altura del cono correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Multiplica por 3 para despejar la fracción y luego divide por el área de la base cónica $\pi r^2$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513747599696"><div class="learnr-question-text">Dada la ecuación $F=g\dfrac{mM}{d^{2}}$, despeje la variable $m$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747599696" value="1" data-correct="true" > $m = \dfrac{FgM}{d^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747599696" value="2" data-correct="true" > $m = Fd^{2} - gM$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747599696" value="3" data-correct="true" > $m = \dfrac{gM}{Fd^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747599696" value="4" data-correct="false" > $m = \dfrac{Fd^{2}}{gM}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747599696" value="5" data-correct="false" > Multiplicar ambos miembros por $d^2$ genera $Fd^2 = gmM$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747599696" value="6" data-correct="false" > La masa $m$ es directamente proporcional al cuadrado de la distancia $d$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747599696')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado todos los distractores incorrectos con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Selecciona únicamente las afirmaciones falsas del despeje de la ley gravitacional.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 9 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513747692907"><div class="learnr-question-text">Dada la ecuación $A=\frac{1}{2}(b_{1}+b_{2})$, despeje la variable $b_{1}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747692907" value="1" data-correct="true" > $b_{1} = 2A - b_{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747692907" value="2" data-correct="true" > Multiplicando ambos lados por $2$ se obtiene $2A = b_1 + b_2$, facilitando el aislamiento directo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747692907" value="3" data-correct="true" > La variable $b_1$ se obtiene restando $b_2$ al doble de la constante $A$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747692907" value="4" data-correct="false" > $b_{1} = \dfrac{2A}{b_{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747692907" value="5" data-correct="false" > $b_{1} = A - \dfrac{b_{2}}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747692907" value="6" data-correct="false" > $b_{1} = 2(A - b_{2})$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747692907')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Despeje lineal resuelto de manera adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Multiplica por 2 para eliminar el denominador y luego resta $b_2$ a ambos lados de la ecuación.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513747795291"><div class="learnr-question-text">Dada la ecuación $A=P+Prt$, despeje la variable $r$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747795291" value="1" data-correct="true" > $r = \dfrac{A}{P} - Pt$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747795291" value="2" data-correct="true" > $r = \dfrac{A - 2P}{Pt}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747795291" value="3" data-correct="true" > $r = A - P - Pt$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747795291" value="4" data-correct="false" > $r = \dfrac{A - P}{Pt}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747795291" value="5" data-correct="false" > Restando $P$ en ambos miembros se obtiene $A - P = Prt$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747795291" value="6" data-correct="false" > Dividir la expresión $(A-P)$ entre el factor $Pt$ aísla de forma correcta la tasa de interés $r$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747795291')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Selecciona únicamente las afirmaciones falsas del despeje financiero.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 11 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513747874198"><div class="learnr-question-text">Dada la ecuación $L^{2}=b\left({1 - \frac{v^{2}}{c^{2}}}\right)$, despeje la variable $v$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747874198" value="1" data-correct="true" > $v = \pm c\sqrt{1 - \dfrac{L^{2}}{b}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747874198" value="2" data-correct="true" > El primer paso algebraico consiste en dividir ambos lados entre $b$ dando $\frac{L^2}{b} = 1 - \frac{v^2}{c^2}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747874198" value="3" data-correct="true" > Extraer la raíz cuadrada al final genera dos soluciones válidas dadas por el signo $\pm$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747874198" value="4" data-correct="false" > $v = c\left(1 - \dfrac{L^{2}}{b}\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747874198" value="5" data-correct="false" > $v = \pm c\sqrt{\dfrac{L^{2}}{b} - 1}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747874198" value="6" data-correct="false" > $v = \pm \sqrt{c^{2} - \dfrac{L^{2}}{b}}$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747874198')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación con radicación y despeje de forma adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Divide entre $b$, despeja $v^2/c^2$, multiplica por $c^2$ y extrae la raíz cuadrada.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Despejes del 12 al 22

### Pregunta 12 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513747956237"><div class="learnr-question-text">Dada la ecuación $s=\frac{1}{2}gt^{2}+v_{0}t$, despeje la variable $t$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513747956237" value="1" data-correct="true" > $t = \sqrt{\dfrac{2s}{g} - v_{0}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747956237" value="2" data-correct="true" > $t = \dfrac{s}{\frac{1}{2}gt + v_{0}}$ (no es un despeje completo al conservar la variable en el lado derecho)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747956237" value="3" data-correct="true" > $t = \dfrac{-v_{0} \pm \sqrt{v_{0}^{2} - 2gs}}{g}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747956237" value="4" data-correct="false" > $t = \dfrac{-v_{0} \pm \sqrt{v_{0}^{2} + 2gs}}{g}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747956237" value="5" data-correct="false" > Multiplicar toda la ecuación por $2$ genera la cuadrática ordenada $gt^2 + 2v_0t - 2s = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513747956237" value="6" data-correct="false" > Físicamente, si consideramos tiempo positivo ($t > 0$), se descarta la raíz negativa resultando en $t = \dfrac{-v_{0} + \sqrt{v_{0}^{2} + 2gs}}{g}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513747956237')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todos los errores algebraicos de la cuadrática.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas sobre la resolución de esta ecuación cuadrática de movimiento.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 13 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513748061803"><div class="learnr-question-text">Dada la ecuación $S=\dfrac{p}{q+p(1-q)}$, despeje la variable $q$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748061803" value="1" data-correct="true" > $q = \dfrac{p(1 - S)}{S(1 - p)}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748061803" value="2" data-correct="true" > Multiplicando la ecuación por el denominador complejo se obtiene $S(q + p - pq) = p$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748061803" value="3" data-correct="true" > Agrupando los términos con $q$ en un lado obtenemos $Sq(1-p) = p(1-S)$ antes de aislar la variable.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748061803" value="4" data-correct="false" > $q = \dfrac{p - S}{S - p}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748061803" value="5" data-correct="false" > $q = \dfrac{S(1 - p)}{p(1 - S)}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748061803" value="6" data-correct="false" > $q = \dfrac{p(S - 1)}{S(p - 1)}$ (omitiendo la simplificación correcta de los signos)</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748061803')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación racional compleja para $q$ correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Elimina la fracción, distribuye y agrupa todos los términos que contengan la variable $q$ para factorizarla y despejarla.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 14 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513748158348"><div class="learnr-question-text">Dada la ecuación $A=2\pi r(r+h)$, despeje la variable $r$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748158348" value="1" data-correct="true" > $r = \sqrt{\dfrac{A}{2\pi} - rh}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748158348" value="2" data-correct="true" > $r = \dfrac{A}{2\pi(r+h)}$ (no representa un despeje al contener la variable buscada en el miembro derecho)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748158348" value="3" data-correct="true" > $r = \dfrac{-\pi h \pm \sqrt{\pi^{2}h^{2} - 2\pi A}}{2\pi}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748158348" value="4" data-correct="false" > $r = \dfrac{-\pi h \pm \sqrt{\pi^{2}h^{2} + 2\pi A}}{2\pi}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748158348" value="5" data-correct="false" > La ecuación cuadrática resultante al distribuir los términos es $2\pi r^2 + 2\pi rh - A = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748158348" value="6" data-correct="false" > El discriminante al aplicar la fórmula general simplificada es $4\pi^2h^2 + 8\pi A$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748158348')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos del despeje cuadrático.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda ordenar la ecuación cuadrática $2\pi r^2 + 2\pi rh - A = 0$ para $r$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 15 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513748259904"><div class="learnr-question-text">Dada la ecuación $P+N=\dfrac{C+2}{C}$, despeje la variable $C$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748259904" value="1" data-correct="true" > $C = \dfrac{2}{P + N - 1}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748259904" value="2" data-correct="true" > Multiplicar por $C$ da $(P+N)C = C + 2$, que al agrupar los términos de $C$ resulta en $C(P+N-1) = 2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748259904" value="3" data-correct="true" > El valor de $C$ es inversamente proporcional a la expresión $P+N-1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748259904" value="4" data-correct="false" > $C = \dfrac{2}{P + N}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748259904" value="5" data-correct="false" > $C = \dfrac{P + N - 1}{2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748259904" value="6" data-correct="false" > $C = 2(P + N - 1)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748259904')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has despejado la variable en la fracción lineal correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Despeja el denominador multiplicando ambos miembros por $C$, agrupa los términos con $C$ en el miembro izquierdo y factoriza.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 16 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513748345258"><div class="learnr-question-text">Dada la ecuación $A=B\sqrt[3]{\dfrac{C}{D}}-E$, despeje la variable $D$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748345258" value="1" data-correct="true" > $D = \dfrac{C(A+E)^{3}}{B^{3}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748345258" value="2" data-correct="true" > $D = \dfrac{CB}{A+E}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748345258" value="3" data-correct="true" > $D = \dfrac{CB^{3}}{A^{3} + E^{3}}$ (incorrecto desarrollo algebraico de la suma de potencias)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748345258" value="4" data-correct="false" > $D = \dfrac{CB^{3}}{(A+E)^{3}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748345258" value="5" data-correct="false" > Sumando $E$ y dividiendo entre $B$ obtenemos la igualdad intermedia $\frac{A+E}{B} = \sqrt[3]{\frac{C}{D}}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748345258" value="6" data-correct="false" > Elevar al cubo ambos miembros de la ecuación elimina la raíz cúbica resultando en $\left(\frac{A+E}{B}\right)^3 = \frac{C}{D}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748345258')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todas las trampas algebraicas del despeje.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que la potencia de un binomio $(A+E)^3$ no se distribuye linealmente.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 17 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513748438807"><div class="learnr-question-text">Dada la ecuación $F=\dfrac{\pi PR^{4}}{8VL}$, despeje la variable $R$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748438807" value="1" data-correct="true" > $R = \pm \left(\dfrac{8VLF}{\pi P}\right)^{1/4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748438807" value="2" data-correct="true" > Aislando el término $R^4$ obtenemos $R^4 = \dfrac{8VLF}{\pi P}$ antes de aplicar la raíz cuarta.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748438807" value="3" data-correct="true" > Físicamente, si consideramos dimensiones de radio estrictamente positivas, se tiene $R = \left(\dfrac{8VLF}{\pi P}\right)^{1/4}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748438807" value="4" data-correct="false" > $R = \left(\dfrac{\pi P}{8VLF}\right)^{4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748438807" value="5" data-correct="false" > $R = \pm \dfrac{2VLF}{\pi P}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748438807" value="6" data-correct="false" > $R = \pm \left(\dfrac{8VLF - \pi P}{4}\right)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748438807')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto el despeje de la cuarta potencia correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Despeja el término de potencia $R^4$ y luego aplica la raíz cuarta a ambos miembros de la ecuación.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 18 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513748539057"><div class="learnr-question-text">Dada la ecuación $V=V_{max}\left(1-\left(\dfrac{r}{r_0}\right)^2 \right)$, despeje la variable $r$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748539057" value="1" data-correct="true" > $r = \pm r_{0} \left(1 - \sqrt{\dfrac{V}{V_{max}}}\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748539057" value="2" data-correct="true" > $r = \pm r_{0}\sqrt{1 - V_{max}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748539057" value="3" data-correct="true" > $r = r_{0} - \sqrt{1 - \dfrac{V}{V_{max}}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748539057" value="4" data-correct="false" > $r = \pm r_{0}\sqrt{1 - \dfrac{V}{V_{max}}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748539057" value="5" data-correct="false" > Dividiendo entre $V_{max}$ y reordenando términos se obtiene $\left(\frac{r}{r_0}\right)^2 = 1 - \frac{V}{V_{max}}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748539057" value="6" data-correct="false" > Multiplicar por $r_0^2$ y extraer la raíz genera el término con el factor multiplicativo $r_0$ libre fuera de la raíz.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748539057')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas del despeje de la velocidad de flujo.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 19 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513748629660"><div class="learnr-question-text">Dada la ecuación $W=b\left(\dfrac{a}{a+x}\right)^2$, despeje la variable $x$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748629660" value="1" data-correct="true" > $x = a\left(\pm \sqrt{\dfrac{b}{W}} - 1\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748629660" value="2" data-correct="true" > Considerando la raíz positiva, el despeje simplificado se expresa como $x = a\left(\sqrt{\dfrac{b}{W}} - 1\right)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748629660" value="3" data-correct="true" > El primer paso consiste en aislar la potencia dividiendo entre $b$, lo que da $\frac{W}{b} = \left(\frac{a}{a+x}\right)^2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748629660" value="4" data-correct="false" > $x = a\left(\dfrac{b}{W} - 1\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748629660" value="5" data-correct="false" > $x = \pm \sqrt{\dfrac{ab}{W}} - a$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748629660" value="6" data-correct="false" > $x = a\left(\pm \sqrt{\dfrac{W}{b}} + 1\right)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748629660')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has despejado la variable en el denominador cuadrático correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Despeja el término cuadrático dividiendo por $b$, aplica la raíz cuadrada y despeja $x$ en la ecuación lineal resultante.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 20 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513748727179"><div class="learnr-question-text">Dada la ecuación $W=b\left(\dfrac{a}{a+x}\right)^2$, despeje la variable $a$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748727179" value="1" data-correct="true" > $a = \dfrac{x}{\sqrt{\dfrac{W}{b}} - 1}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748727179" value="2" data-correct="true" > $a = \dfrac{x\sqrt{W}}{\sqrt{W} - \sqrt{b}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748727179" value="3" data-correct="true" > $a = \dfrac{x(W-b)}{b}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748727179" value="4" data-correct="false" > $a = \dfrac{x\sqrt{W}}{\sqrt{b} - \sqrt{W}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748727179" value="5" data-correct="false" > Dividiendo entre $b$ y extrayendo la raíz positiva obtenemos $\sqrt{\frac{W}{b}} = \frac{a}{a+x}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748727179" value="6" data-correct="false" > Es equivalente a la expresión simplificada $a = \dfrac{x}{\sqrt{\dfrac{b}{W}} - 1}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748727179')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todas las trampas algebraicas de la distribución.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas sobre el despeje de la variable $a$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 21 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513748811770"><div class="learnr-question-text">Dada la ecuación $d=2\pi\left(\dfrac{vR}{0.52\cos(\theta)}\right)^{1/3}$, despeje la variable $v$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748811770" value="1" data-correct="true" > $v = \dfrac{0.52\cos(\theta)}{R} \left(\dfrac{d}{2\pi}\right)^{3}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748811770" value="2" data-correct="true" > Es equivalente a la expresión completamente simplificada $v = \dfrac{0.065 d^{3} \cos(\theta)}{\pi^{3} R}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748811770" value="3" data-correct="true" > El primer paso requiere dividir entre $2\pi$ y luego elevar al cubo a ambos lados para eliminar el exponente fraccionario $1/3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748811770" value="4" data-correct="false" > $v = \dfrac{0.52 d^{3}\cos(\theta)}{2\pi R}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748811770" value="5" data-correct="false" > $v = \left(\dfrac{d}{4\pi^{3}}\right) \cdot \dfrac{0.52\cos(\theta)}{R}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748811770" value="6" data-correct="false" > El término $\pi^3$ queda en el numerador de la expresión simplificada.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748811770')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Despeje con exponentes fraccionarios y trigonometría correcto.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Divide entre $2\pi$, eleva ambos lados al cubo, multiplica por $0.52\cos(\theta)$ y divide por $R$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 22 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513748904536"><div class="learnr-question-text">Dada la ecuación $d=2\pi\left(\dfrac{vR}{0.52\cos(\theta)}\right)^{1/3}$, despeje la variable $\theta$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513748904536" value="1" data-correct="true" > $\theta = \arccos\left(\dfrac{0.52 d^{3}}{8\pi^{3} vR}\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748904536" value="2" data-correct="true" > $\theta = \cos\left(\dfrac{8\pi^{3} vR}{0.52 d^{3}}\right)$ (incorrecto uso de la función coseno en lugar de su inversa arcoseno)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748904536" value="3" data-correct="true" > $\theta = \arccos\left(\dfrac{vR}{0.52} \left(\dfrac{2\pi}{d}\right)^{3}\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748904536" value="4" data-correct="false" > $\theta = \arccos\left(\dfrac{8\pi^{3} vR}{0.52 d^{3}}\right)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748904536" value="5" data-correct="false" > Elevar al cubo y despejar genera la igualdad intermedia $\cos(\theta) = \dfrac{vR}{0.52 \left(\frac{d}{2\pi}\right)^3}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513748904536" value="6" data-correct="false" > Es equivalente a la expresión con decimales simplificados $\theta = \arccos\left(\dfrac{200\pi^{3} vR}{13 d^{3}}\right)$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513748904536')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has finalizado toda la evaluación detectando todos los distractores incorrectos con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas del despeje angular. Recuerda que aislar un ángulo requiere la función arcoseno (arccos).</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796513749118037', 22, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente en la manipulación y el despeje de variables en ecuaciones literales complejas. Comprendes con total claridad el aislamiento mediante cuadráticas, radicación de diferentes índices y funciones trigonométricas inversas. ¡Sigue así, estás listo para desafíos mayores!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún hay conceptos de aislamiento cuadrático y despeje de variables en denominadores que puedes pulir. Te sugerimos repasar la aplicación de la fórmula cuadrática para ecuaciones literales (como en $s = \\frac{1}{2}gt^2 + v_0t$ o $A = 2\\pi r(r+h)$). ¡Con un poco más de repaso lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar a fondo las propiedades de las operaciones inversas (multiplicar denominadores, potencias inversas a raíces, etc.) y practicar con ecuaciones lineales simples antes de avanzar. ¡No te desanimes, con la práctica dominarás el despeje de variables!')">Calcular Mis Resultados</button><div id="sr17796513749118037"></div>
