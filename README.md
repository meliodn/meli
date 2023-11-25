import time
import random

def mostrar_mensaje_financiero():
    mensajes = [
        "¡Compra de amor completada!",
        "¡Tu cartera emocional ha aumentado!",
        "¡Ganancias emocionales aseguradas!",
        "¡Inversión en felicidad exitosa!",
        "¡Amor en alza en el mercado de emociones!",
    ]

    return random.choice(mensajes)

def main():
    print("Bienvenido al Mercado de Emociones")

    while True:
        input("Presiona Enter para realizar una transacción de amor...")
        print("\nProcesando transacción...")
        time.sleep(2)  # Simular un breve tiempo de procesamiento

        mensaje = mostrar_mensaje_financiero()
        print(f"\n{mensaje}\n")

if __name__ == "__main__":
    main()
