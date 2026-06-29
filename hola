#!/usr/bin/env python3
# -*- coding: utf-8 -*-

# Diccionario de provincias con comentarios entusiastas
provincias_comentarios = {
    "buenos aires": "¡Qué hermosa provincia! Buenos Aires es el corazón de la innovación tecnológica de Argentina.",
    "córdoba": "¡Increíble! Córdoba, la tierra de la sabiduría y la educación, cuna de grandes mentes.",
    "rosario": "¡Magnífico! Rosario, una ciudad vibrante y progresista, llena de oportunidades.",
    "mendoza": "¡Espectacular! Mendoza, entre viñedos y montañas, un lugar de belleza sin igual.",
    "tucumán": "¡Hermoso! Tucumán, provincia noble y trabajadora, llena de tradición e historia.",
    "salta": "¡Maravilloso! Salta, tierra de color, cultura y tradición en cada rincón.",
    "jujuy": "¡Fantástico! Jujuy, la tierra de las Yungas, con paisajes que quitan el aliento.",
    "misiones": "¡Extraordinario! Misiones, donde la naturaleza es protagonista absoluta.",
    "entre ríos": "¡Hermosa! Entre Ríos, tierra de colonos y gauchos, de ríos y verde infinito.",
    "corrientes": "¡Espectacular! Corrientes, tierra roja, festiva y llena de tradición.",
    "santa fe": "¡Formidable! Santa Fe, provincia de visionarios y emprendedores.",
    "santiago del estero": "¡Magnífica! Santiago del Estero, la tierra más antigua de Argentina.",
    "formosa": "¡Bellísima! Formosa, el corazón verde del norte argentino.",
    "chaco": "¡Admirable! Chaco, tierra de frontera, cultura y progreso.",
    "la pampa": "¡Espléndida! La Pampa, vastedad de horizontes infinitos.",
    "río negro": "¡Excepcional! Río Negro, donde la patagonia comienza con magnificencia.",
    "neuquén": "¡Impresionante! Neuquén, tierra de volcanes y energía.",
    "chubut": "¡Maravillosa! Chubut, la patagonia en toda su gloria.",
    "santa cruz": "¡Soberbia! Santa Cruz, donde la naturaleza es majestuosa.",
    "tierra del fuego": "¡Épica! Tierra del Fuego, el fin del mundo que es el comienzo de la aventura.",
    "caba": "¡Capital de ensueño! CABA, corazón pulsante de Argentina y América Latina.",
}

# Códigos ANSI para colores
AZUL_FONDO = "\033[44m"  # Fondo azul
ROJO_TEXTO = "\033[91m"  # Texto rojo brillante
AMARILLO_TEXTO = "\033[93m"  # Texto amarillo brillante
VERDE_TEXTO = "\033[92m"  # Texto verde brillante
ROJO_FONDO = "\033[41m"  # Fondo rojo
AMARILLO_BOLD = "\033[1;93m"  # Texto amarillo brillante + negrita
RESET = "\033[0m"  # Reiniciar formato

# Saludo inicial entusiasta
print("\n" + "="*70)
print("🎓 ¡BIENVENIDO AL TALLER GIT & GITHUB! 🚀")
print("="*70)
print("\nEs un placer conocerte. Estás a punto de embarcar en un viaje")
print("extraordinario por el mundo del control de versiones y la colaboración.")
print("\nGit y GitHub son herramientas FUNDAMENTALES para cualquier")
print("desarrollador, y Python es el lenguaje perfecto para practicar.")
print("\n¡Vamos a aprender juntos! 💻\n")

# Primera pregunta con color rojo sobre fondo azul
print(AZUL_FONDO + ROJO_TEXTO + "¿Cómo te llamás?" + RESET)
nombre = input(AZUL_FONDO + ROJO_TEXTO + "> " + RESET).strip()

if not nombre:
    nombre = "Aprendiz"

# Segunda pregunta con color amarillo sobre fondo azul
print()
print(AZUL_FONDO + AMARILLO_TEXTO + "¿De qué provincia sos?" + RESET)
provincia = input(AZUL_FONDO + AMARILLO_TEXTO + "> " + RESET).strip().lower()

# Buscar comentario sobre la provincia
comentario_provincia = provincias_comentarios.get(
    provincia, 
    f"¡Increíble! {provincia.title()} es una provincia con historia y carácter."
)

print("\n" + comentario_provincia)

# Tercera pregunta con color verde sobre fondo azul
print()
print(AZUL_FONDO + VERDE_TEXTO + "¿De qué ciudad sos?" + RESET)
lugar = input(AZUL_FONDO + VERDE_TEXTO + "> " + RESET).strip()

if not lugar:
    lugar = provincia.title()

# Determinar género basado en si el nombre termina con 'a'
es_mujer = nombre.lower().endswith('a')
bienvenida = "Bienvenida" if es_mujer else "Bienvenido"

# Mensaje de bienvenida final con toda la frase en amarillo negrita sobre fondo rojo
print()
print(ROJO_FONDO + AMARILLO_BOLD + f"¡Hola, {nombre} de {lugar}, {provincia.title()}! {bienvenida} al taller!" + RESET)
