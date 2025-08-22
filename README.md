<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transforma Tu Vida en 5 Días - Guía Sin Harinas</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }
        .btn-whatsapp {
            background: linear-gradient(135deg, #25D366 0%, #128C7E 100%);
            transition: all 0.3s ease;
        }
        .btn-whatsapp:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(37, 211, 102, 0.3);
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        .testimonial-card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
        }
        .countdown-box {
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
        }
    </style>
</head>
<body class="text-gray-800">
    <!-- Hero Section -->
    <section class="hero-gradient text-white py-20 px-4">
        <div class="container mx-auto max-w-6xl">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
                        Transforma Tu Salud en <span class="text-yellow-300">Solo 5 Días</span>
                    </h1>
                    <p class="text-xl mb-8 text-white/90">
                        Descubre el poder de vivir sin harinas procesadas. Nuestra guía exclusiva te llevará paso a paso hacia una vida más saludable y energética.
                    </p>
                    <div class="bg-white/10 p-6 rounded-2xl mb-8">
                        <h3 class="text-2xl font-semibold mb-4">🔥 OFERTA EXCLUSIVA</h3>
                        <p class="text-lg mb-2">✅ Guía completa de 5 días</p>
                        <p class="text-lg mb-2">✅ Plan de comidas detallado</p>
                        <p class="text-lg mb-2">✅ Recetas exclusivas</p>
                        <p class="text-lg mb-4">✅ Soporte 24/7 por WhatsApp</p>
                        <div class="countdown-box p-4 rounded-xl text-center">
                            <p class="font-bold">🚨 PRECIO ESPECIAL POR TIEMPO LIMITADO</p>
                        </div>
                    </div>
                    <button onclick="scrollToWhatsApp()" class="btn-whatsapp text-white font-bold py-4 px-8 rounded-full text-lg shadow-2xl flex items-center justify-center mx-auto md:mx-0">
                        <span>💬 OBTENER GUÍA POR WHATSAPP</span>
                    </button>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="bg-white/20 p-6 rounded-3xl">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/05eebd2f-462a-4cc7-b0a7-230303f1fc86.png" alt="Persona saludable y feliz sosteniendo plato con comida saludable colorida, fondo de cocina moderna con vegetales frescos" class="rounded-2xl shadow-2xl" />
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto max-w-6xl px-4">
            <h2 class="text-4xl font-bold text-center mb-16 text-gray-800">¿Por Qué Elegir Nuestra Guía?</h2>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="card-hover bg-gray-50 p-8 rounded-2xl text-center">
                    <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <span class="text-3xl">⚡</span>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Más Energía</h3>
                    <p class="text-gray-600">Despierta cada mañana con energía renovada y sin esa pesadez después de comer.</p>
                </div>

                <div class="card-hover bg-gray-50 p-8 rounded-2xl text-center">
                    <div class="w-20 h-20 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <span class="text-3xl">⚖️</span>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Pérdida de Peso</h3>
                    <p class="text-gray-600">Pierde esos kilos de más de forma natural y sostenible sin pasar hambre.</p>
                </div>

                <div class="card-hover bg-gray-50 p-8 rounded-2xl text-center">
                    <div class="w-20 h-20 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <span class="text-3xl">🧠</span>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Claridad Mental</h3>
                    <p class="text-gray-600">Mejora tu concentración y enfoque eliminando el azúcar y las harinas procesadas.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gray-100">
        <div class="container mx-auto max-w-6xl px-4">
            <h2 class="text-4xl font-bold text-center mb-16 text-gray-800">Historias de Éxito Real</h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="testimonial-card p-8 rounded-2xl">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/462d45dc-aaff-4d2e-8b0b-905f6a6399c4.png" alt="Mujer latina sonriente de 35 años con cabello castaño ondeado, vistiendo blusa azul clara, mostrando resultados positivos después del programa sin harinas" class="w-16 h-16 rounded-full mr-4" />
                        <div>
                            <h4 class="font-semibold">María G.</h4>
                            <p class="text-gray-600">32 años - Perdió 4kg</p>
                        </div>
                    </div>
                    <p class="text-gray-700 italic">"En solo 5 días noté cambios increíbles. Más energía, mejor digestión y esa ansiedad por lo dulce desapareció. ¡La mejor inversión en mi salud!"</p>
                </div>

                <div class="testimonial-card p-8 rounded-2xl">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d81dbd0d-07e1-4d20-a89c-eab785f193f9.png" alt="Hombre feliz de 40 años mostrando resultados positivos después del programa de 5 días" class="w-16 h-16 rounded-full mr-4" />
                        <div>
                            <h4 class="font-semibold">Carlos R.</h4>
                            <p class="text-gray-600">40 años - Mejoró su digestión</p>
                        </div>
                    </div>
                    <p class="text-gray-700 italic">"Sufría de hinchazón constante. Esta guía me enseñó alternativas deliciosas. Ahora me siento ligero y lleno de vitalidad todo el día."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="py-20 bg-white">
        <div class="container mx-auto max-w-6xl px-4">
            <h2 class="text-4xl font-bold text-center mb-16 text-gray-800">Cómo Funciona Nuestra Guía</h2>
            
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="w-16 h-16 bg-blue-500 text-white rounded-full flex items-center justify-center mx-auto mb-4 text-2xl font-bold">1</div>
                    <h3 class="font-semibold mb-2">Compra Segura</h3>
                    <p class="text-gray-600">Accede a la guía mediante WhatsApp de forma instantánea y segura</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-green-500 text-white rounded-full flex items-center justify-center mx-auto mb-4 text-2xl font-bold">2</div>
                    <h3 class="font-semibold mb-2">Recibe Guía</h3>
                    <p class="text-gray-600">Obtén tu guía completa con todos los materiales digitales</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-purple-500 text-white rounded-full flex items-center justify-center mx-auto mb-4 text-2xl font-bold">3</div>
                    <h3 class="font-semibold mb-2">Sigue el Plan</h3>
                    <p class="text-gray-600">Implementa el plan de 5 días paso a paso con nuestro apoyo</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-orange-500 text-white rounded-full flex items-center justify-center mx-auto mb-4 text-2xl font-bold">4</div>
                    <h3 class="font-semibold mb-2">Transforma</h3>
                    <p class="text-gray-600">Disfruta de los resultados y continúa con hábitos saludables</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="py-20 bg-gradient-to-r from-blue-600 to-purple-600 text-white">
        <div class="container mx-auto max-w1-4xl px-4 text-center">
            <h2 class="text-4xl font-bold mb-6">¡No Esperes Más Para Cambiar Tu Vida!</h2>
            <p class="text-xl mb-8">Únete a cientos de personas que ya transformaron su salud con nuestra guía de 5 días sin harinas</p>
            
            <div class="bg-white/10 p-8 rounded-2xl max-w-2xl mx-auto mb-8">
                <h3 class="text-2xl font-semibold mb-4">🎯 LO QUE OBTENDRÁS:</h3>
                <ul class="text-left space-y-2">
                    <li>✅ Guía completa de 5 días en PDF</li>
                    <li>✅ Plan de comidas detallado con alternativas</li>
                    <li>✅ Lista de compras organizada</li>
                    <li>✅ Recetas exclusivas y deliciosas</li>
                    <li>✅ Soporte personalizado por WhatsApp</li>
                    <li>✅ Acceso a comunidad privada</li>
                </ul>
            </div>

            <button onclick="openWhatsApp()" class="btn-whatsapp text-white font-bold py-5 px-12 rounded-full text-xl shadow-2xl mx-auto flex items-center justify-center">
                <span>💬 INICIAR MI TRANSFORMACIÓN AHORA</span>
            </button>
            
            <p class="mt-6 text-white/80">Precio especial: $29.99 (Normal: $49.99)</p>
            <p class="text-white/60">Pago seguro • Garantía de satisfacción</p>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-20 bg-white">
        <div class="container mx-auto max-w-4xl px-4">
            <h2 class="text-4xl font-bold text-center mb-16 text-gray-800">Preguntas Frecuentes</h2>
            
            <div class="space-y-6">
                <div class="border-b pb-6">
                    <h3 class="text-xl font-semibold mb-2">¿Qué incluye exactamente la guía?</h3>
                    <p class="text-gray-600">Incluye un plan completo de 5 días con desayunos, almuerzos, cenas y snacks. Lista de compras, recetas detalladas, tips de preparación y soporte personalizado por WhatsApp.</p>
                </div>
                
                <div class="border-b pb-6">
                    <h3 class="text-xl font-semibold mb-2">¿Necesito conocimientos de cocina?</h3>
                    <p class="text-gray-600">No, todas las recetas son simples y fáciles de preparar. Incluimos instrucciones paso a paso para todos los niveles.</p>
                </div>
                
                <div class="border-b pb-6">
                    <h3 class="text-xl font-semibold mb-2">¿Cómo recibo la guía después de pagar?</h3>
                    <p class="text-gray-600">Inmediatamente después del pago, te enviaremos la guía completa por WhatsApp junto con todos los materiales adicionales.</p>
                </div>
                
                <div class="border-b pb-6">
                    <h3 class="text-xl font-semibold mb-2">¿Hay garantía?</h3>
                    <p class="text-gray-600">Sí, ofrecemos garantía de 7 días. Si no estás satisfecho, te devolvemos tu dinero.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer CTA -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto max-w-6xl px-4 text-center">
            <h3 class="text-2xl font-bold mb-4">¿Listo para Empezar?</h3>
            <p class="mb-8 text-gray-300">Tu transformación de 5 días comienza con un solo clic</p>
            <button onclick="openWhatsApp()" class="btn-whatsapp text-white font-bold py-4 px-10 rounded-full text-lg mx-auto">
                💬 OBTENER GUÍA AHORA
            </button>
            <p class="mt-8 text-gray-400">© 2024 Guía 5 Días Sin Harinas. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script>
        function openWhatsApp() {
            const phoneNumber = "1158102330"; // Número actualizado
            const message = "quiero sumarme a la guia"; // Mensaje actualizado
            const url = `https://wa.me/${phoneNumber}?text=${encodeURIComponent(message)}`;
            window.open(url, '_blank');
        }
        
        function scrollToWhatsApp() {
            const element = document.querySelector('footer');
            element.scrollIntoView({ behavior: 'smooth' });
        }
        
        // Efecto de contador regresivo
        let count = 10;
        const countdown = setInterval(() => {
            document.querySelector('.countdown-box p').textContent = `🚨 OFERTA TERMINA EN ${count} MINUTOS`;
            count--;
            if (count < 0) {
                clearInterval(countdown);
                document.querySelector('.countdown-box p').textContent = "🚨 OFERTA TERMINANDO PRONTO";
            }
        }, 60000);
    </script>
</body>
</html>
