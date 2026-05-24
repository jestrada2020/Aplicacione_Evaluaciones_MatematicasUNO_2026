---
title: "Evaluación Completa de Potenciación"
output: html_document
---


# Evaluación Completa de Potenciación

<style>
/* Estilos Premium para la Evaluación de Potenciación */
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
  background: linear-gradient(135deg, #6366f1 0%, #a855f7 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  text-align: center;
  margin-bottom: 2rem;
  box-shadow: 0 10px 25px -5px rgba(99, 102, 241, 0.3);
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
  border-left: 5px solid #6366f1;
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
  background-color: #faf5ff !important;
  transform: translateX(4px);
}

.answer-option.selected {
  background-color: #eef2ff !important;
  border-color: #6366f1 !important;
}

/* Botones */
.btn-primary, .btn-submit, .btn-action {
  background: linear-gradient(135deg, #6366f1 0%, #a855f7 100%) !important;
  border: none !important;
  color: white !important;
  font-weight: 600 !important;
  font-family: 'Outfit', sans-serif !important;
  padding: 0.6rem 1.5rem !important;
  border-radius: 8px !important;
  transition: all 0.2s ease !important;
  box-shadow: 0 4px 12px rgba(99, 102, 241, 0.2) !important;
}

.btn-primary:hover, .btn-submit:hover {
  transform: translateY(-1px) !important;
  box-shadow: 0 6px 16px rgba(99, 102, 241, 0.3) !important;
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

Bienvenido a la **Evaluación Completa de Potenciación**. Este examen consta de **20 preguntas interactivas** divididas en dos grandes bloques:
1. **Leyes Fundamentales**: Ejercicios de operaciones de potencias básicas con misma base.
2. **Potenciación Avanzada y Radicales**: Ejercicios con exponentes fraccionarios, simplificación algebraica compleja y radicales.

> **Instrucciones:**
> * Presta mucha atención al enunciado de cada pregunta.
> * El **50% de las preguntas (10 preguntas)** te pedirá seleccionar las **afirmaciones verdaderas**.
> * El otro **50% de las preguntas (10 preguntas)** te pedirá seleccionar **únicamente las afirmaciones falsas**.
> * ¡Mucho éxito!

---

## Bloque 1: Leyes de Exponentes Básicas

En esta primera sección evaluaremos la simplificación de productos y cocientes algebraicos y numéricos aplicando las leyes fundamentales de los exponentes.

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617222322623"><div class="learnr-question-text">Analiza el enunciado matemático: $$3^2 \cdot 3$$ e identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="1" data-correct="true" > Es equivalente a $3^3$ debido a que se suman los exponentes (2 + 1).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="2" data-correct="true" > Su valor simplificado es igual a 27.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="3" data-correct="true" > Es equivalente a realizar la multiplicación tradicional $9 \cdot 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="4" data-correct="true" > Representa un producto de potencias con la misma base.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="5" data-correct="false" > Su valor simplificado es igual a 9.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="6" data-correct="false" > Es equivalente a $3^6$ (multiplicando los exponentes).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222322623" value="7" data-correct="false" > Su valor simplificado es igual a 18.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222322623')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado correctamente todas las afirmaciones verdaderas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto, revisa las leyes de exponentes y vuelve a intentarlo.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617222467173"><div class="learnr-question-text">Analiza el enunciado algebraico: $$a^2 \cdot a^3 \cdot a^5$$ e identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222467173" value="1" data-correct="true" > Es equivalente a $a^{30}$ ya que se deben multiplicar los exponentes.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222467173" value="2" data-correct="true" > El exponente final se calcula multiplicando $2 \cdot 3 \cdot 5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222467173" value="3" data-correct="true" > Es equivalente a la expresión $3a^{10}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222467173" value="4" data-correct="false" > Es equivalente a la expresión $a^{10}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222467173" value="5" data-correct="false" > La regla aplicada consiste en conservar la base común y sumar todos sus exponentes.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222467173" value="6" data-correct="false" > Si asignamos el valor de $a = 2$, el resultado de evaluar la expresión simplificada es 1024.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222467173')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Seleccionaste con éxito todas las afirmaciones falsas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que debes seleccionar aquellas afirmaciones que sean matemáticamente incorrectas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617222568079"><div class="learnr-question-text">Analiza la expresión con coeficientes y variables: $$2m \cdot 3m \cdot m^6$$ e identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222568079" value="1" data-correct="true" > El coeficiente numérico de la expresión simplificada es 6.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222568079" value="2" data-correct="true" > La expresión simplificada resultante es equivalente a $6m^8$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222568079" value="3" data-correct="true" > El exponente final de la variable $m$ se obtiene de la suma $1 + 1 + 6$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222568079" value="4" data-correct="true" > Si asignamos $m = 1$, el valor numérico de la expresión es 6.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222568079" value="5" data-correct="false" > La expresión simplificada es equivalente a $5m^6$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222568079" value="6" data-correct="false" > La expresión simplificada es equivalente a $6m^6$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222568079')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente trabajo! Todo está correcto.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda sumar los exponentes implícitos de valor 1 para las variables que no lo muestran visiblemente.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617222653304"><div class="learnr-question-text">Analiza el enunciado numérico: $$2^2 \cdot 2^3 \cdot 2^4$$ e identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222653304" value="1" data-correct="true" > Es equivalente a $2^{24}$ al multiplicar directamente los exponentes.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222653304" value="2" data-correct="true" > Su valor final simplificado es igual a 48.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222653304" value="3" data-correct="true" > Es equivalente a la potencia $8^9$ que resulta de multiplicar las bases.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222653304" value="4" data-correct="false" > Es equivalente a la potencia simplificada $2^9$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222653304" value="5" data-correct="false" > Su valor final evaluado es igual a 512.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222653304" value="6" data-correct="false" > Representa la multiplicación de los valores individuales $4 \cdot 8 \cdot 16$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222653304')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Magnífico! Has reconocido los errores más frecuentes de potenciación.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda que las afirmaciones falsas corresponden a errores comunes de multiplicación de bases o exponentes.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617222758017"><div class="learnr-question-text">Analiza la expresión con exponentes algebraicos: $$4a \cdot a^x \cdot 5a^2$$ e identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222758017" value="1" data-correct="true" > La expresión completamente simplificada equivale a $20a^{x+3}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222758017" value="2" data-correct="true" > El coeficiente numérico resultante de la expresión es 20.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222758017" value="3" data-correct="true" > El exponente final se obtiene mediante la suma algebraica de los exponentes: $1 + x + 2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222758017" value="4" data-correct="true" > Si $x = 1$, la expresión resultante simplificada equivale a $20a^4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222758017" value="5" data-correct="false" > La expresión simplificada equivale a $9a^{2x}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222758017" value="6" data-correct="false" > La expresión simplificada equivale a $20a^{3x}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222758017')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Manejas muy bien las propiedades algebraicas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ten cuidado al operar las constantes numéricas y al agrupar los términos de los exponentes.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617222846263"><div class="learnr-question-text">Analiza el producto continuo de potencias: $$3 \cdot 3^2 \cdot 3^3 \cdot 3^4$$ e identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222846263" value="1" data-correct="true" > Es equivalente a la potencia $3^9$ (al omitir el exponente implícito de valor 1 del primer término).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222846263" value="2" data-correct="true" > Es equivalente a la potencia $3^{24}$ que resulta de multiplicar los exponentes.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222846263" value="3" data-correct="true" > Su valor final simplificado es igual a $12^{10}$ al multiplicar las bases.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222846263" value="4" data-correct="false" > La expresión simplificada en una sola potencia equivale a $3^{10}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222846263" value="5" data-correct="false" > Su valor final simplificado evaluado numéricamente es 59049.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222846263" value="6" data-correct="false" > Representa una multiplicación de potencias que comparten la base 3.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222846263')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Impecable! Detectaste todos los conceptos incorrectos exitosamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Asegúrate de identificar las propiedades incorrectas referentes a la base y los exponentes.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617222922407"><div class="learnr-question-text">Analiza el enunciado con variables mixtas en el exponente: $$5 \cdot 5^2 \cdot 5^m$$ e identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617222922407" value="1" data-correct="true" > La expresión simplificada final equivale a $5^{m+3}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222922407" value="2" data-correct="true" > La base de la potencia resultante se mantiene igual a 5.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222922407" value="3" data-correct="true" > El exponente final se obtiene mediante la suma directa de los exponentes $1 + 2 + m$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222922407" value="4" data-correct="true" > Si el valor de $m$ es igual a 1, el valor simplificado final del número es 625.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222922407" value="5" data-correct="false" > La expresión simplificada equivale a $125^m$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617222922407" value="6" data-correct="false" > La expresión simplificada equivale a $5^{2m}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617222922407')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Fantástico! Las propiedades se aplicaron de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda aplicar correctamente la suma de monomios y números enteros en los exponentes.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617223012058"><div class="learnr-question-text">Analiza el cociente algebraico simple: $$a^3 \div a$$ e identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223012058" value="1" data-correct="true" > Es equivalente a $a^3$ al suponer incorrectamente que el divisor tiene exponente 0.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223012058" value="2" data-correct="true" > Es equivalente a $a^4$ al realizar una suma de exponentes en lugar de una resta.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223012058" value="3" data-correct="true" > Es equivalente a la constante 3 cancelando la variable $a$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223012058" value="4" data-correct="false" > Es equivalente a la potencia simplificada $a^2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223012058" value="5" data-correct="false" > El exponente final se calcula restando el exponente del numerador menos el del denominador (3 - 1).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223012058" value="6" data-correct="false" > Si asignamos $a = 5$, el valor final simplificado es igual a 25.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223012058')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado con éxito los errores conceptuales.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Repasa la regla de la división de potencias de igual base y selecciona las afirmaciones incorrectas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 9 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617223126279"><div class="learnr-question-text">Analiza el cociente algebraico: $$a^6 \div a^4$$ e identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223126279" value="1" data-correct="true" > La expresión reducida equivale a $a^2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223126279" value="2" data-correct="true" > Para resolver la división de potencias de igual base se resta el exponente inferior al superior.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223126279" value="3" data-correct="true" > Esta expresión es geométricamente equivalente al área de un cuadrado de lado $a$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223126279" value="4" data-correct="true" > Si asignamos $a = -3$, el valor evaluado de la expresión simplificada es 9.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223126279" value="5" data-correct="false" > La expresión reducida equivale a $a^{1.5}$ (dividiendo los exponentes).</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223126279" value="6" data-correct="false" > La expresión reducida equivale a $a^{10}$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223126279')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Comprendes de manera óptima las bases de la división algebraica.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Revisa las reglas de división y el comportamiento de números negativos elevados a exponentes pares.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617223222718"><div class="learnr-question-text">Analiza el cociente de potencias idénticas: $$3^5 \div 3^5$$ e identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223222718" value="1" data-correct="true" > El resultado final simplificado es igual a 0.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223222718" value="2" data-correct="true" > Es equivalente a la potencia $3^{10}$ al sumar erróneamente los exponentes.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223222718" value="3" data-correct="true" > El resultado final simplificado de la operación es igual a 3.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223222718" value="4" data-correct="false" > Es equivalente a la potencia $3^0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223222718" value="5" data-correct="false" > El valor simplificado evaluado equivale al número entero 1.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223222718" value="6" data-correct="false" > Representa un número real distinto de cero dividido entre sí mismo, lo cual siempre es igual a 1.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223222718')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Finalizaste la evaluación identificando todos los conceptos erróneos de manera precisa.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda qué sucede cuando se resta el mismo exponente y cuál es el valor de cualquier base elevada a la cero.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Potenciación Avanzada y Radicales

En este bloque evaluaremos el uso de exponentes fraccionarios, racionalización y simplificación algebraica avanzada basándonos en la guía de evaluación avanzada.

### Pregunta 11 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617223314791"><div class="learnr-question-text">Usar propiedades de potenciación e identificar afirmaciones **verdaderas** sobre la expresión: $$\left(-8\right)^{\frac{1}{3}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223314791" value="1" data-correct="true" > $$\left(-8\right)^{\frac{1}{3}}=\sqrt[3]{-8}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223314791" value="2" data-correct="true" > $$\left(-8\right)^{\frac{1}{3}}=\sqrt[3]{-2^{3}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223314791" value="3" data-correct="true" > $$\left(-8\right)^{\frac{1}{3}}=\left(-2^3\right)^{\frac{1}{3}}= \sqrt[3]{2^{3}} \sqrt[3]{-1}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223314791" value="4" data-correct="true" > Su resultado es exactamente igual a el número entero $-2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223314791" value="5" data-correct="false" > $$\left(-8\right)^{\frac{1}{3}}=\sqrt[3]{8}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223314791" value="6" data-correct="false" > $$\left(-8\right)^{\frac{1}{3}}=\sqrt[3]{2^{3}}$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223314791')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la potencia con base negativa correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto, analiza detenidamente el signo y las bases cúbicas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 12 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617223406911"><div class="learnr-question-text">Usar propiedades de potenciación e identificar únicamente las afirmaciones **falsas** sobre la expresión: $$\left(-64\right)^{\frac{1}{5}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223406911" value="1" data-correct="true" > $$\left(-64\right)^{\frac{1}{5}}=\sqrt[3]{64}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223406911" value="2" data-correct="true" > $$\left(-64\right)^{\frac{1}{5}}=\sqrt[5]{2^{6}}$$ (falta signo negativo en la base)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223406911" value="3" data-correct="true" > $$\left(-64\right)^{\frac{1}{5}}=\left(-2^3\right)^{\frac{1}{5}}= \sqrt[5]{2^{3}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223406911" value="4" data-correct="false" > $$\left(-64\right)^{\frac{1}{5}}=\sqrt[5]{-2^6}= -2 \sqrt[5]{2}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223406911" value="5" data-correct="false" > $$\left(-64\right)^{\frac{1}{5}}=\sqrt[5]{-2^{6}}$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223406911')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Identificaste los errores de bases y exponentes con precisión.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Selecciona sólo las representaciones que sean matemáticamente incorrectas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 13 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617223486598"><div class="learnr-question-text">Usar propiedades de potenciación e identificar afirmaciones **verdaderas** sobre la expresión: $$\left(512\right)^{\frac{1}{4}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223486598" value="1" data-correct="true" > $$\left(512\right)^{\frac{1}{4}}=\sqrt[4]{2^4(32)}=2 \sqrt[4]{32}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223486598" value="2" data-correct="true" > $$\left(512\right)^{\frac{1}{4}}=2^2\sqrt[4]{2}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223486598" value="3" data-correct="true" > $$\left(512\right)^{\frac{1}{4}}=\sqrt[4]{2^9}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223486598" value="4" data-correct="true" > $$\left(512\right)^{\frac{1}{4}}=4\sqrt[4]{2}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223486598" value="5" data-correct="false" > $$\left(512\right)^{\frac{1}{4}}=\sqrt[4]{-2^{9}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223486598" value="6" data-correct="false" > $$\left(512\right)^{\frac{1}{4}}=\sqrt[4]{2^4(16)}$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223486598')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Manejas muy bien las equivalencias radicales.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Realiza la descomposición factorial de 512 en base 2.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 14 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617223589531"><div class="learnr-question-text">Usar propiedades de potenciación e identificar únicamente las afirmaciones **falsas** sobre la expresión: $$\left(-216\right)^{\frac{1}{3}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223589531" value="1" data-correct="true" > $$\left(-216\right)^{\frac{1}{3}}=\sqrt[4]{2^4(16)}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223589531" value="2" data-correct="true" > $$\left(-216\right)^{\frac{1}{3}}=\sqrt[4]{-2^{9}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223589531" value="3" data-correct="true" > $$\left(-216\right)^{\frac{1}{3}}=\left(-2^9\right)^{\frac{1}{3}}= 4\sqrt[5]{-2^{3}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223589531" value="4" data-correct="false" > $$\left(-216\right)^{\frac{1}{3}}=-\sqrt[3]{12(18)}=- \sqrt[3]{8(27)}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223589531" value="5" data-correct="false" > $$\left(-216\right)^{\frac{1}{3}}=-2(3)=-6$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223589531" value="6" data-correct="false" > $$\left(-216\right)^{\frac{1}{3}}=\sqrt[3]{-216}$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223589531')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Identificaste los errores conceptuales de manera óptima.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ubica los planteamientos erróneos de la raíz cúbica de -216.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 15 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617223676573"><div class="learnr-question-text">Usar propiedades de potenciación e identificar afirmaciones **verdaderas** sobre la expresión: $$\left(0.04\right)^{\frac{-7}{2}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223676573" value="1" data-correct="true" > $$\left(0.04\right)^{\frac{-7}{2}}=\left(\frac{10}{2}\right)^7=5^7$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223676573" value="2" data-correct="true" > $$\left(0.04\right)^{\frac{-7}{2}}=\left(\frac{4}{100}\right)^{-\frac{7}{2}}=\left(\frac{100}{4}\right)^{\frac{7}{2}}=25^{\frac{7}{2}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223676573" value="3" data-correct="true" > El valor final simplificado es igual a la constante entera 78125.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223676573" value="4" data-correct="true" > $$\left(0.04\right)^{\frac{-7}{2}}=\sqrt{0.04^{-7}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223676573" value="5" data-correct="false" > $$\left(0.04\right)^{\frac{-7}{2}}=\sqrt[2]{-2^{9}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223676573" value="6" data-correct="false" > $$\left(0.04\right)^{\frac{-7}{2}}=5^{-7}$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223676573')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Magnífico! Has operado la potencia decimal negativa correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda pasar el decimal 0.04 a fracción (4/100) y aplicar las leyes de los exponentes negativos.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 16 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617223816659"><div class="learnr-question-text">Usar propiedades de potenciación e identificar únicamente las afirmaciones **falsas** sobre la expresión: $$\left(-32\right)^{\frac{1}{5}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223816659" value="1" data-correct="true" > $$\left(-32\right)^{\frac{1}{5}}=\sqrt[2]{2^4(16)}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223816659" value="2" data-correct="true" > $$\left(-32\right)^{\frac{1}{5}}=\sqrt[2]{-2^{9}3^3}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223816659" value="3" data-correct="true" > Su resultado simplificado equivale al número real positivo 2.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223816659" value="4" data-correct="false" > $$\left(-32\right)^{\frac{1}{5}}= \sqrt[5]{(-1)^52^{5}}=-2$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223816659" value="5" data-correct="false" > $$\left(-32\right)^{\frac{1}{5}}=\left(-2^5\right)^{\frac{1}{5}}=(-2)^1$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223816659')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Espectacular! Has completado el ejercicio descartando los fallos comunes.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Busca cuáles afirmaciones contienen fallos aritméticos elementales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 17 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617223918862"><div class="learnr-question-text">Usar propiedades de potenciación e identificar afirmaciones **verdaderas** sobre la expresión: $$\sqrt[n]{\dfrac{4^{n}.6}{4^{2n+1}+2^{4n+1}}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223918862" value="1" data-correct="true" > $$\sqrt[n]{\dfrac{4^{n}.6}{4^{2n+1}+2^{4n+1}}}=\sqrt[n]{\dfrac{2^{2n}.(2).(3)}{2^{4n+2}+2^{4n+1}}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223918862" value="2" data-correct="true" > $$\sqrt[n]{\dfrac{4^{n}.6}{4^{2n+1}+2^{4n+1}}}=\sqrt[n]{\dfrac{2^{2n}.(2).(3)}{2^{4n}2^2+2^{4n}2^1}}=\sqrt[n]{\dfrac{2^{2n}.(2).(3)}{2^{4n}(2^2+2^1)}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223918862" value="3" data-correct="true" > $$\sqrt[n]{\dfrac{4^{n}.6}{4^{2n+1}+2^{4n+1}}}=\sqrt[n]{\dfrac{2^{2n}.(2).(3)}{2^{4n}(6)}}=\sqrt[n]{\dfrac{2^{2n}}{2^{4n}}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223918862" value="4" data-correct="true" > El resultado final de simplificar toda la expresión radical es exactamente $\frac{1}{4}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223918862" value="5" data-correct="true" > $$\sqrt[n]{\dfrac{4^{n}.6}{4^{2n+1}+2^{4n+1}}}=\sqrt[n]{\left( \dfrac{1}{2^2} \right)^n}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223918862" value="6" data-correct="false" > El resultado final de la expresión simplificada es igual a 2.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223918862')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Perfecto! Dominas la factorización exponencial avanzada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Realiza la simplificación algebraica factorizando $2^{4n}$ en el denominador.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 18 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617223992709"><div class="learnr-question-text">Usar propiedades de potenciación e identificar únicamente las afirmaciones **falsas** sobre la expresión: $$\dfrac{2^{n+3}-2^{n}+7}{2^{n+1}-2^{n}+1}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617223992709" value="1" data-correct="true" > $$\dfrac{2^{n+3}-2^{n}+7}{2^{n+1}-2^{n}+1}=\dfrac{1}{7}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223992709" value="2" data-correct="true" > $$\dfrac{2^{n+3}-2^{n}+7}{2^{n+1}-2^{n}+1}=\dfrac{2^n(2^3-1)+7}{2^n(2^1-1)+1}=\frac{1}{7}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223992709" value="3" data-correct="true" > El resultado final simplificado para cualquier valor de $n$ es la fracción $\frac{7}{2}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223992709" value="4" data-correct="false" > $$\dfrac{2^{n+3}-2^{n}+7}{2^{n+1}-2^{n}+1}=\dfrac{2^n2^3-2^{n}+7}{2^n2-2^{n}+1}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617223992709" value="5" data-correct="false" > $$\dfrac{2^{n+3}-2^{n}+7}{2^{n+1}-2^{n}+1}=\dfrac{2^n(2^3-1)+7}{2^n(2^1-1)+1}=\dfrac{7(2^n+1)}{2^n+1}=7$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617223992709')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Impecable! Has reconocido los desvíos matemáticos erróneos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Identifica las operaciones algebraicas erróneas referentes a la factorización de $2^n$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 19 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796617224098516"><div class="learnr-question-text">Usar propiedades de potenciación e identificar afirmaciones **verdaderas** sobre la expresión: $$\dfrac{2.2^{3n}-4.4^{n}}{(2.2^{n})^{3}-8.2^{2n+1}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617224098516" value="1" data-correct="true" > $$\dfrac{2.2^{3n}-4.4^{n}}{(2.2^{n})^{3}-8.2^{2n+1}}=\dfrac{2.2^{3n}-2^2.2^{2n}}{2^3.2^{3n}-2^3.2^{2n+1}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224098516" value="2" data-correct="true" > $$\dfrac{2.2^{3n}-4.4^{n}}{(2.2^{n})^{3}-8.2^{2n+1}}=\dfrac{2.2^{2n}(2^n-2)}{2^3.2^{2n}(2^n-2)}=\dfrac{2.2^{2n}}{2^3.2^{2n}}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224098516" value="3" data-correct="true" > El resultado simplificado final de toda la expresión es la constante racional $\frac{1}{4}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224098516" value="4" data-correct="true" > $$\dfrac{2.2^{3n}-4.4^{n}}{(2.2^{n})^{3}-8.2^{2n+1}}=\dfrac{2.2^{2n}}{2^3.2^{2n}}=\dfrac{2}{2^3}=\dfrac{2}{8}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224098516" value="5" data-correct="false" > El resultado simplificado final es igual a $\frac{1}{8}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224098516" value="6" data-correct="false" > El resultado simplificado final es igual a 2.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617224098516')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Fantástico! Resuelto con completa pericia matemática.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Recuerda reescribir $4$ como $2^2$ y $8$ como $2^3$ para trabajar con bases iguales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 20 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796617224195621"><div class="learnr-question-text">Usar propiedades de potenciación e identificar únicamente las afirmaciones **falsas** sobre la expresión: $$\left(\dfrac{8x}{y^4}\right)^{\frac{1}{5}}.\left(\dfrac{4x^4}{y}\right)^{\frac{1}{5}}$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796617224195621" value="1" data-correct="true" > $$\left(\dfrac{8x}{y^4}\right)^{\frac{1}{5}}.\left(\dfrac{4x^4}{y}\right)^{\frac{1}{5}}=\left(\dfrac{(8)(4)(8)xx^4}{y^4y}\right)^{\frac{1}{5}}$$ (se multiplicaron las constantes erróneamente)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224195621" value="2" data-correct="true" > $$\left(\dfrac{8x}{y^4}\right)^{\frac{1}{5}}.\left(\dfrac{4x^4}{y}\right)^{\frac{1}{5}}=\sqrt[5]{\left(\dfrac{2^5x^5}{y^5}\right)}=\dfrac{2y}{x}$$ (las variables están invertidas)</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224195621" value="3" data-correct="true" > El resultado simplificado final equivale a $\dfrac{y}{2x}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224195621" value="4" data-correct="false" > $$\left(\dfrac{8x}{y^4}\right)^{\frac{1}{5}}.\left(\dfrac{4x^4}{y}\right)^{\frac{1}{5}}=\left(\dfrac{32x^5}{y^5}\right)^{\frac{1}{5}}=\dfrac{2x}{y}$$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796617224195621" value="5" data-correct="false" > $$\left(\dfrac{8x}{y^4}\right)^{\frac{1}{5}}.\left(\dfrac{4x^4}{y}\right)^{\frac{1}{5}}=\sqrt[5]{\left(\dfrac{2^5x^5}{y^5}\right)}=\dfrac{2x}{y}$$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796617224195621')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has finalizado toda la evaluación detectando todos los errores algebraicos con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Fíjate en los exponentes y la posición de las variables reducidas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796617224405118', 20, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente de las leyes de potenciación y radicales. Has alcanzado un nivel excelente. ¡Sigue así, estás listo para retos aún mayores!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún hay conceptos que puedes pulir. Te sugerimos repasar la ley de cociente de potencias ($a^m \\div a^n = a^{m-n}$) y la simplificación de exponentes fraccionarios con bases negativas. ¡Con un poco más de práctica lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar a fondo las propiedades básicas de la potenciación (suma de exponentes en el producto y resta en la división) y resolver de nuevo los ejercicios sencillos antes de intentar los de nivel avanzado. ¡No te desanimes, la práctica hace al maestro!')">Calcular Mis Resultados</button><div id="sr17796617224405118"></div>
