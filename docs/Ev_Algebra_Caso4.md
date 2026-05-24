---
title: "Evaluación de Álgebra: Expresiones Racionales (Caso 4)"
output: html_document
---


# Evaluación de Álgebra: Expresiones Racionales (Caso 4)

<style>
/* Estilos Premium para la Evaluación de Álgebra (Caso 4) - Tema Amatista */
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

Bienvenido a la **Evaluación de Álgebra: Expresiones Racionales (Caso 4)**. Este examen interactivo consta de **14 preguntas** diseñadas para evaluar tu capacidad de simplificar expresiones algebraicas complejas, factorizar polinomios e identificar restricciones en los reales.

> **Instrucciones:**
> * Realiza las operaciones en papel y simplifica al máximo antes de responder.
> * Presta mucha atención a la factorización de factores comunes, diferencias de cuadrados y trinomios.
> * El **50% de las preguntas (7 preguntas)** te pedirá seleccionar las **afirmaciones verdaderas**.
> * El **50% de las preguntas (7 preguntas)** te pedirá seleccionar **únicamente las afirmaciones falsas**.
> * Al final de la prueba, podrás visualizar un reporte detallado con tus respuestas y una recomendación de estudio personalizada.
> * ¡Mucho éxito!

---

## Bloque 1: Preguntas de la 1 a la 7

En esta sección abordaremos operaciones de división de fracciones algebraicas, fracciones complejas y exponentes negativos.

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513733215543"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{q^{2}-1}{q^{2}+2q-3} \div \dfrac{q-4}{q+3}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733215543" value="1" data-correct="true" > $\dfrac{q+1}{q-4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733215543" value="2" data-correct="true" > La operación de división equivale a multiplicar por el recíproco de la segunda fracción: $\frac{q+1}{q+3} \times \frac{q+3}{q-4}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733215543" value="3" data-correct="true" > El dominio de la expresión original requiere excluir los valores $q = 1$, $q = -3$ y $q = 4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733215543" value="4" data-correct="false" > $\dfrac{q-1}{q-4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733215543" value="5" data-correct="false" > $q-4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733215543" value="6" data-correct="false" > La expresión final es irreducible y no posee ninguna restricción real en sus variables.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733215543')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has factorizado y simplificado la división de fracciones correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Factoriza $q^2-1 = (q-1)(q+1)$ y $q^2+2q-3 = (q-1)(q+3)$, cancela factores comunes y multiplica por el recíproco del divisor.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513733354559"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{s^{2}-5s+6}{s^{2}+7s+10} \div \dfrac{2-s}{s+2}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733354559" value="1" data-correct="true" > $\dfrac{s-3}{s+5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733354559" value="2" data-correct="true" > La división simplificada da como resultado una expresión estrictamente positiva en todo su dominio real.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733354559" value="3" data-correct="true" > El trinomio del denominador se descompone como $(s-2)(s-5)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733354559" value="4" data-correct="false" > $\dfrac{3-s}{s+5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733354559" value="5" data-correct="false" > Dado que $2-s = -(s-2)$, al multiplicar por el recíproco aparece un signo negativo que altera el numerador final a $3-s$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733354559" value="6" data-correct="false" > El dominio excluye los valores $s = -2$, $s = -5$ y $s = 2$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733354559')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todos los enunciados falsos en esta operación.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Presta especial atención al factor $2-s = -(s-2)$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513733457507"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{x^{2}+xy+y^{2}}{\dfrac{x^{2}}{y}-\dfrac{y^{2}}{x}}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733457507" value="1" data-correct="true" > $\dfrac{xy}{x-y}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733457507" value="2" data-correct="true" > El denominador se combina como $\frac{x^3-y^3}{xy}$, y el término de diferencia de cubos se simplifica algebraicamente con el numerador.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733457507" value="3" data-correct="true" > La expresión simplificada requiere obligatoriamente que $x \neq 0$, $y \neq 0$ y $x \neq y$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733457507" value="4" data-correct="false" > $\dfrac{x-y}{xy}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733457507" value="5" data-correct="false" > $xy(x-y)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733457507" value="6" data-correct="false" > El resultado final simplificado equivale a $x+y$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733457507')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has simplificado la fracción compleja utilizando diferencias de cubos con maestría.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Resuelve primero la resta del denominador buscando el común denominador $xy$ y factoriza la diferencia de cubos $x^3-y^3 = (x-y)(x^2+xy+y^2)$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513733556201"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{u^{-2}-v^{-2}}{u^{2}v^{2}}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733556201" value="1" data-correct="true" > $\dfrac{v^{2}-u^{2}}{u^{2}v^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733556201" value="2" data-correct="true" > $\dfrac{u^{2}-v^{2}}{u^{4}v^{4}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733556201" value="3" data-correct="true" > La expresión simplificada se reduce de forma directa a la constante $1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733556201" value="4" data-correct="false" > $\dfrac{v^{2}-u^{2}}{u^{4}v^{4}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733556201" value="5" data-correct="false" > El numerador se reescribe usando exponentes positivos como $\frac{1}{u^2} - \frac{1}{v^2} = \frac{v^2-u^2}{u^2v^2}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733556201" value="6" data-correct="false" > El exponente final de las variables $u$ y $v$ en el denominador es $4$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733556201')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los planteamientos incorrectos de esta simplificación de exponentes.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda reescribir $u^{-2} = 1/u^2$ y efectuar la resta del numerador.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513733641848"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{1+\dfrac{1}{\sqrt{x}}}{1+\dfrac{1}{\sqrt{y}}}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733641848" value="1" data-correct="true" > $\dfrac{\sqrt{y}(\sqrt{x}+1)}{\sqrt{x}(\sqrt{y}+1)}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733641848" value="2" data-correct="true" > La expresión se obtiene al sumar las fracciones del numerador y denominador para luego aplicar la ley de extremos y medios.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733641848" value="3" data-correct="true" > Las restricciones físicas de las raíces del dominio exigen que tanto $x$ como $y$ sean estrictamente positivos ($x > 0, y > 0$).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733641848" value="4" data-correct="false" > $\dfrac{\sqrt{x}(\sqrt{y}+1)}{\sqrt{y}(\sqrt{x}+1)}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733641848" value="5" data-correct="false" > $\sqrt{\dfrac{x}{y}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733641848" value="6" data-correct="false" > La expresión se reduce a la unidad ($1$) para cualquier valor de las variables.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733641848')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la división con radicales algebraicos de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Suma las fracciones en el numerador dando $(\sqrt{x}+1)/\sqrt{x}$ y en el denominador dando $(\sqrt{y}+1)/\sqrt{y}$, y luego opera.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513733725943"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{\dfrac{1}{(x+h)^{2}}-\dfrac{1}{x^{2}}}{h}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733725943" value="1" data-correct="true" > $-\dfrac{2x-h}{x^{2}(x+h)^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733725943" value="2" data-correct="true" > $\dfrac{2x+h}{x^{2}(x+h)^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733725943" value="3" data-correct="true" > La expresión simplificada se anula por completo cuando el valor de $h$ tiende a cero.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733725943" value="4" data-correct="false" > $-\dfrac{2x+h}{x^{2}(x+h)^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733725943" value="5" data-correct="false" > El numerador simplificado antes de dividir por $h$ es $\frac{x^2 - (x+h)^2}{x^2(x+h)^2} = \frac{-h(2x+h)}{x^2(x+h)^2}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733725943" value="6" data-correct="false" > El dominio requiere que $h \neq 0$, $x \neq 0$ y $x+h \neq 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733725943')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has encontrado los distractores falsos del cociente diferencial de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Ten cuidado con los signos al desarrollar $x^2 - (x+h)^2 = -2xh - h^2$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513733806443"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{v}{\sqrt{z}}-\dfrac{z}{\sqrt{v}}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733806443" value="1" data-correct="true" > $\dfrac{v\sqrt{v}-z\sqrt{z}}{\sqrt{zv}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733806443" value="2" data-correct="true" > Es equivalente a la expresión con exponentes fraccionarios $\dfrac{v^{3/2}-z^{3/2}}{(zv)^{1/2}}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733806443" value="3" data-correct="true" > Para efectuar la resta se busca el común denominador el cual es el producto de las raíces $\sqrt{z}\sqrt{v} = \sqrt{zv}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733806443" value="4" data-correct="false" > $\dfrac{v-z}{\sqrt{zv}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733806443" value="5" data-correct="false" > $\sqrt{v} - \sqrt{z}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733806443" value="6" data-correct="false" > La expresión es completamente equivalente a la constante $0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733806443')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has efectuado la resta de fracciones con radicales correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Multiplica el primer término por $\sqrt{v}/\sqrt{v}$ y el segundo por $\sqrt{z}/\sqrt{z}$ para hallar el común denominador.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Preguntas de la 8 a la 14

En esta sección evaluaremos trinomios cuadráticos factorizables, irreducibles, diferencias de cuadrados y simplificación de cubos.

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513733897798"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{\dfrac{1}{x^{2}}-x}{\dfrac{1}{x^{2}}+x}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513733897798" value="1" data-correct="true" > $\dfrac{1-x}{1+x}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733897798" value="2" data-correct="true" > El resultado de la simplificación es equivalente a la unidad ($1$) para cualquier valor real.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733897798" value="3" data-correct="true" > La expresión no tiene ninguna restricción de dominio y es válida para $x = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733897798" value="4" data-correct="false" > $\dfrac{1-x^{3}}{1+x^{3}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733897798" value="5" data-correct="false" > Multiplicar tanto el numerador como el denominador por el factor cuadrático $x^2$ elimina directamente las fracciones complejas.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513733897798" value="6" data-correct="false" > El dominio excluye los valores $x = 0$ y $x = -1$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513733897798')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado los enunciados falsos de forma exitosa.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda multiplicar por $x^2$ arriba y abajo: $(1-x^3)/(1+x^3)$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 9 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513734036235"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{x^{2}+3x+2}{x^{2}+6x+8}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513734036235" value="1" data-correct="true" > $\dfrac{x+1}{x+4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734036235" value="2" data-correct="true" > El polinomio del numerador se factoriza como $(x+1)(x+2)$ y el del denominador como $(x+2)(x+4)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734036235" value="3" data-correct="true" > La expresión simplificada posee restricciones de dominio en $x \neq -2$ y $x \neq -4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734036235" value="4" data-correct="false" > $\dfrac{x-1}{x-4}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734036235" value="5" data-correct="false" > $\dfrac{3x+2}{6x+8}$ (obtenido al cancelar erróneamente los términos $x^2$)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734036235" value="6" data-correct="false" > La expresión equivale a la constante $\frac{1}{2}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513734036235')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has factorizado y simplificado los trinomios de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Factoriza ambos trinomios cuadráticos de la forma $x^2+bx+c$ buscando números que multiplicados den el término libre y sumados den el término medio.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513734128802"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{x^{4}+4x^{2}+4}{4-x^{4}}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513734128802" value="1" data-correct="true" > $\dfrac{x^{2}-2}{x^{2}+2}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734128802" value="2" data-correct="true" > El binomio del denominador se descompone como la diferencia de cuadrados: $(x^2-2)(x^2+2)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734128802" value="3" data-correct="true" > La expresión simplificada equivale a la constante $-1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734128802" value="4" data-correct="false" > $\dfrac{x^{2}+2}{2-x^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734128802" value="5" data-correct="false" > El numerador es un trinomio cuadrado perfecto de la forma $(x^2+2)^2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734128802" value="6" data-correct="false" > El dominio excluye los valores reales $x = \sqrt{2}$ y $x = -\sqrt{2}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513734128802')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado todas las afirmaciones incorrectas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que $4-x^4 = (2-x^2)(2+x^2)$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 11 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513734213524"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{x^{2}-2yx-3y^{2}}{x^{2}-yx+3y^{2}}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513734213524" value="1" data-correct="true" > No es posible simplificar la fracción algebraica mediante cancelación de factores comunes en los números reales porque el polinomio del denominador $x^2 - yx + 3y^2$ es irreducible.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734213524" value="2" data-correct="true" > El discriminante del polinomio cuadrático del denominador con respecto a $x$ es $D = -11y^2 \le 0$, lo que confirma que no posee raíces reales (salvo para el caso trivial $y = 0$).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734213524" value="3" data-correct="true" > La factorización del numerador es $(x - 3y)(x + y)$, pero este no comparte factores comunes reales con el denominador.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734213524" value="4" data-correct="false" > $\dfrac{x-3y}{x+3y}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734213524" value="5" data-correct="false" > $\dfrac{x+y}{x-y}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734213524" value="6" data-correct="false" > $-2yx$ (obtenido al cancelar erróneamente términos cuadráticos y libres similares)</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513734213524')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has demostrado rigor matemático e identificado de forma correcta la irreducibilidad de la expresión.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Aunque el numerador sea factorizable como $(x-3y)(x+y)$, comprueba que el discriminante del denominador es negativo y por tanto irreducible en los números reales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 12 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513734298011"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{3x^{2}-7x-20}{3x^{3}+5x^{2}}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513734298011" value="1" data-correct="true" > $\dfrac{x+4}{x^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734298011" value="2" data-correct="true" > $\dfrac{x-4}{3x^{2}+5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734298011" value="3" data-correct="true" > La factorización del trinomio del numerador es $(3x-5)(x+4)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734298011" value="4" data-correct="false" > $\dfrac{x-4}{x^{2}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734298011" value="5" data-correct="false" > El polinomio $3x^2 - 7x - 20$ se factoriza agrupando términos como $(3x+5)(x-4)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734298011" value="6" data-correct="false" > El dominio excluye los valores $x = 0$ y $x = -5/3$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513734298011')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los enunciados incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda factorizar el numerador mediante aspas o agrupación dando $(3x+5)(x-4)$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 13 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513734376349"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{x^{3}-9x}{x^{3}-6x^{2}+9x}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513734376349" value="1" data-correct="true" > $\dfrac{x+3}{x-3}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734376349" value="2" data-correct="true" > El numerador se descompone como $x(x-3)(x+3)$ y el denominador como el factor $x(x-3)^2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734376349" value="3" data-correct="true" > Los valores $x = 0$ y $x = 3$ no pertenecen al dominio de la expresión simplificada por anular el denominador de la fracción original.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734376349" value="4" data-correct="false" > $\dfrac{x-3}{x+3}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734376349" value="5" data-correct="false" > $\dfrac{x^{2}-9}{x^{2}-6x+9}$ (expresión no simplificada al máximo)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734376349" value="6" data-correct="false" > La expresión se reduce a la unidad ($1$) para cualquier valor real positivo.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513734376349')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la simplificación de cubos y diferencia de cuadrados perfectamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Factoriza primero por término común $x$ y luego aplica diferencia de cuadrados en el numerador y trinomio cuadrado perfecto en el denominador.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 14 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513734475056"><div class="learnr-question-text">Simplificar la expresión racional: $\dfrac{yx^{2}+xy^{2}}{x^{2}-y^{2}}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513734475056" value="1" data-correct="true" > $\dfrac{x-y}{xy}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734475056" value="2" data-correct="true" > $\dfrac{xy}{x+y}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734475056" value="3" data-correct="true" > El numerador se descompone únicamente como $xy(x-y)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734475056" value="4" data-correct="false" > $\dfrac{xy}{x-y}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734475056" value="5" data-correct="false" > El numerador es $xy(x+y)$ y el denominador es $(x-y)(x+y)$, cancelándose el factor común de suma $(x+y)$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513734475056" value="6" data-correct="false" > Las restricciones del dominio requieren que la variable $x$ sea distinta de $y$ y distinta de $-y$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513734475056')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has finalizado la evaluación analizando correctamente los factores de expresiones racionales de dos variables.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda extraer el término común $xy$ en el numerador.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796513734692173', 14, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente en la factorización y simplificación de expresiones racionales complejas. Comprendes con total claridad la ley de extremos y medios, la irreducibilidad de polinomios cuadráticos y la descomposición en factores. ¡Sigue así, estás listo para desafíos algebraicos mayores!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún hay conceptos de fracciones complejas, factorización diferencial de cubos y trinomios que puedes pulir. Te sugerimos repasar la factorización de diferencias y sumas de cubos, así como la ley de signos al reordenar binomios (como $2-s = -(s-2)$). ¡Con un poco más de repaso lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar los métodos de factorización de polinomios de segundo y tercer grado (diferencias de cuadrados, trinomio de la forma $ax^2+bx+c$, etc.) y la simplificación de fracciones simples antes de avanzar. ¡No te desanimes, con la práctica dominarás el álgebra!')">Calcular Mis Resultados</button><div id="sr17796513734692173"></div>
