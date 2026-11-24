# ==============================================
# Sistema de Gestión de Estudiantes - Avance Paso 1
# ==============================================

# Lista para almacenar los datos de los estudiantes
estudiantes = []

def mostrar_menu():
    """Muestra el menú principal del sistema"""
    print("\n" + "="*40)
    print("    SISTEMA DE GESTIÓN DE ESTUDIANTES")
    print("="*40)
    print("1. Registrar nuevo estudiante")
    print("2. Ver lista de estudiantes")
    print("3. Buscar estudiante")
    print("4. Salir del sistema")
    print("="*40)

# Código principal (bucle de funcionamiento)
print("¡Bienvenido al sistema!")
while True:
    mostrar_menu()
    opcion = input("Seleccione una opción: ")
    
    if opcion == "4":
        print("👋 Gracias por usar el sistema. ¡Hasta pronto!")
        break
    elif opcion in ["1", "2", "3"]:
        print(f"✅ Opción {opcion} seleccionada — En desarrollo...")
    else:
        print("❌ Opción no válida. Intente nuevamente.")
