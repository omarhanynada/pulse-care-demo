<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PulseCare - Telehealth & E-Prescription Platform</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style> body { font-family: 'Inter', sans-serif; } </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="bg-blue-600 text-white p-2 rounded-lg font-bold text-lg">💊 Pulse</div>
                <span class="text-xl font-bold text-slate-900">Bask Health Demo</span>
            </div>
            <span class="text-sm bg-emerald-100 text-emerald-800 px-3 py-1 rounded-full font-medium">System Status: Online</span>
        </div>
    </header>
    <main class="max-w-4xl mx-auto px-4 py-6 space-y-6">
        <div class="bg-gradient-to-r from-blue-600 to-indigo-700 rounded-2xl p-6 text-white shadow-lg">
            <h1 class="text-2xl font-bold mb-2">Welcome, Dr. Ahmed / Valued Patient</h1>
            <p class="text-blue-100 text-sm mb-4">A unified platform for managing medical records, electronic prescriptions, and telehealth sessions.</p>
            <div class="flex flex-wrap gap-3">
                <button onclick="alert('Virtual consultation started successfully!')" class="bg-white text-blue-600 px-4 py-2 rounded-xl font-semibold text-sm shadow hover:bg-blue-50 transition">🎥 Start Video Consult</button>
                <button onclick="alert('Opened prescriptions log')" class="bg-blue-500 bg-opacity-40 text-white px-4 py-2 rounded-xl font-semibold text-sm border border-blue-400 hover:bg-opacity-50 transition">📋 View Prescriptions (Rx)</button>
            </div>
        </div>
        <div class="grid grid-cols-2 gap-4">
            <div class="bg-white p-4 rounded-xl shadow-sm border border-slate-100">
                <p class="text-slate-500 text-xs">Upcoming Consultations</p>
                <p class="text-xl font-bold text-slate-800 mt-1">3 Sessions</p>
            </div>
            <div class="bg-white p-4 rounded-xl shadow-sm border border-slate-100">
                <p class="text-slate-500 text-xs">Active Prescriptions</p>
                <p class="text-xl font-bold text-emerald-600 mt-1">5 Rx</p>
            </div>
        </div>
        <div class="bg-white rounded-2xl shadow-sm border border-slate-100 p-5">
            <h2 class="text-lg font-bold text-slate-900 mb-4">Recent Electronic Prescriptions</h2>
            <div class="space-y-3">
                <div class="flex items-center justify-between p-3 bg-slate-50 rounded-xl border border-slate-100">
                    <div>
                        <h3 class="font-semibold text-sm text-slate-800">Amoxicillin 500mg</h3>
                        <p class="text-xs text-slate-500">Dispensed by: Central Medical Pharmacy</p>
                    </div>
                    <span class="text-xs bg-emerald-100 text-emerald-700 px-2.5 py-1 rounded-md font-medium">Completed</span>
                </div>
            </div>
        </div>
    </main>
</body>
</html>
