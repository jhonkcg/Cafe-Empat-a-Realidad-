
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Café Empatía Real</title>
    <!-- Tailwind CSS para el diseño -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-[#12100E] text-[#E6E1DA] min-h-screen flex flex-col justify-between p-6">

    <!-- Cabecera -->
    <header class="w-full max-w-md mx-auto flex justify-between items-center py-4">
        <span class="text-sm tracking-widest text-[#D4A373] uppercase font-medium">1:1 Humano Real</span>
        <div class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse" title="Sistema Activo"></div>
    </header>

    <!-- Contenido Principal: Vista de Perfil y Conexión -->
    <main class="w-full max-w-md mx-auto my-auto space-y-6">
        
        <div class="text-center space-y-2">
            <h1 class="text-2xl font-semibold tracking-tight text-[#FDFBF7]">
                Café Empatía Real
            </h1>
            <p class="text-[#B0A89F] text-sm">
                Conexiones reales entre personas. Sin bots.
            </p>
        </div>

        <!-- Tarjeta de Ejemplo de Perfil Real -->
        <div class="bg-[#2A2421] border border-[#3E3530] rounded-2xl p-5 flex items-center space-x-4 shadow-xl">
            <!-- Foto de Perfil Real -->
            <div class="relative">
                <div class="w-16 h-16 rounded-full overflow-hidden border-2 border-[#D4A373] bg-[#1E1917]">
                    <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=200&q=80" alt="Foto real" class="w-full h-full object-cover">
                </div>
                <div class="absolute bottom-0 right-0 w-4 h-4 rounded-full bg-emerald-500 border-2 border-[#2A2421]" title="En línea"></div>
            </div>

            <!-- Datos de Identidad -->
            <div class="flex-1 min-w-0">
                <h2 class="text-base font-medium text-[#FDFBF7] truncate">Jhon Cova</h2>
                <p class="text-xs text-[#D4A373] font-mono">@arquitecto_calma</p>
                <span class="inline-block mt-2 px-2.5 py-0.5 rounded-full text-[10px] bg-[#3E3530] text-[#E6E1DA]">
                    Disponible para escuchar
                </span>
            </div>
        </div>

        <!-- Botón de Acción -->
        <div class="pt-2 space-y-3">
            <button onclick="alert('Próximamente: Conexión con pasarela USDT de 1$')" class="w-full py-4 px-6 rounded-xl bg-[#D4A373] text-[#12100E] font-semibold text-base hover:bg-[#C29362] transition shadow-lg shadow-[#D4A373]/10 cursor-pointer">
                Entrar a la sala ($1 USDT)
            </button>
            <p class="text-xs text-center text-[#7A726A]">
                Tu aporte valida tu compromiso humano y alimenta nuestra caja de ayuda humanitaria.
            </p>
        </div>
    </main>

    <!-- Pie de página -->
    <footer class="w-full max-w-md mx-auto text-center py-4 text-xs text-[#7A726A]">
        Café Empatía Real &bull; Espacio Seguro 1:1
    </footer>

</body>
</html>
