
<template>
    <div class="min-h-screen bg-slate-50 text-slate-800">

        <!-- Encabezado -->
        <header class="border-b border-slate-200 bg-white">
            <div class="mx-auto flex max-w-6xl items-center justify-between px-6 py-5">
                <div class="flex items-center gap-3">
                    <div class="rounded-xl bg-blue-900 px-3 py-2 text-xl text-white">
                        ✚
                    </div>

                    <div>
                        <h1 class="text-2xl font-bold text-blue-950">
                            FarmaGest
                        </h1>
                        <p class="text-xs text-slate-500">
                            Sistema de Gestión Farmacéutica
                        </p>
                    </div>
                </div>

                <span class="rounded-full bg-blue-50 px-3 py-1 text-xs font-medium text-blue-800">
                    Plataforma educativa
                </span>
            </div>
        </header>

        <!-- Contenido principal -->
        <main class="mx-auto max-w-6xl px-6 py-16">

            <div class="mb-10">
                <p class="mb-2 text-sm font-semibold uppercase tracking-wider text-blue-700">
                    Bienvenido a FarmaGest
                </p>

                <h2 class="text-3xl font-bold text-slate-900">
                    Selecciona tu entorno de trabajo
                </h2>

                <p class="mt-3 max-w-2xl text-slate-500">
                    Plataforma de simulación para la gestión
                    de farmacias privadas y asistenciales.
                </p>
            </div>

            <!-- Módulos -->
            <div class="grid gap-6 md:grid-cols-2">

                <!-- Farmacia privada -->
                <section class="rounded-2xl border border-slate-200 bg-white p-8 shadow-sm">
                    <div class="mb-6 flex h-14 w-14 items-center justify-center rounded-xl bg-blue-100 text-3xl">
                        🏪
                    </div>

                    <h3 class="text-2xl font-bold text-slate-900">
                        Farmacia Privada
                    </h3>

                    <p class="mt-3 text-sm leading-6 text-slate-500">
                        Administración de medicamentos, inventario,
                        ventas, recetas y convenios de salud.
                    </p>

                    <div class="mt-6 border-t border-slate-100 pt-5">
                        <span class="text-sm font-medium text-blue-800">
                            Módulo en desarrollo
                        </span>
                    </div>
                </section>

                <!-- Farmacia CESFAM -->
                <section class="rounded-2xl border border-slate-200 bg-white p-8 shadow-sm">
                    <div class="mb-6 flex h-14 w-14 items-center justify-center rounded-xl bg-emerald-100 text-3xl">
                        🏥
                    </div>

                    <h3 class="text-2xl font-bold text-slate-900">
                        Farmacia CESFAM
                    </h3>

                    <p class="mt-3 text-sm leading-6 text-slate-500">
                        Gestión de pacientes, recetas, dispensación,
                        programas GES y carros clínicos.
                    </p>

                    <div class="mt-6 border-t border-slate-100 pt-5">
                        <span class="text-sm font-medium text-emerald-700">
                            Módulo en desarrollo
                        </span>
                    </div>
                </section>
            </div>
        </main>

        <!-- Marca de agua pequeña -->
        <div class="fixed bottom-4 right-4 z-50 rounded-lg border border-slate-200 bg-white/90 px-3 py-2 text-right shadow-sm">
            <p class="text-[10px] font-bold uppercase tracking-wide text-slate-500">
                Uso académico · INACAP
            </p>
            <p class="text-[9px] text-slate-400">
                Sistema de simulación · Sin validez legal
            </p>
        </div>

    </div>
</template>
