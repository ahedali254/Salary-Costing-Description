<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Salary & Costing Dashboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-100 font-sans p-4 md:p-6 text-slate-800">

    <div class="max-w-7xl mx-auto space-y-6">
        
        <!-- Main Header -->
        <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-200 text-center">
            <h1 class="text-3xl font-extrabold text-blue-900 mb-1">My Salary & Costing Description</h1>
            <p class="text-sm text-slate-500">গুগল শিট থেকে সিঙ্ক করা রিয়েল-টাইম লাইভ ড্যাশবোর্ড</p>
        </div>

        <!-- My Dashboard Summary Cards -->
        <div class="grid grid-cols-2 md:grid-cols-5 gap-4">
            <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-blue-600">
                <span class="text-xs font-semibold text-slate-400 uppercase">Total Income</span>
                <p class="text-xl font-bold text-blue-600 mt-1">6,94,485 ৳</p>
            </div>
            <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-indigo-600">
                <span class="text-xs font-semibold text-slate-400 uppercase">Total House Rent</span>
                <p class="text-xl font-bold text-indigo-600 mt-1">64,400 ৳</p>
            </div>
            <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-amber-600">
                <span class="text-xs font-semibold text-slate-400 uppercase">Total Mill Cost</span>
                <p class="text-xl font-bold text-amber-600 mt-1">81,100 ৳</p>
            </div>
            <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-purple-600">
                <span class="text-xs font-semibold text-slate-400 uppercase">Total Sent House</span>
                <p class="text-xl font-bold text-purple-600 mt-1">3,79,500 ৳</p>
            </div>
            <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-teal-600 col-span-2 md:col-span-1">
                <span class="text-xs font-semibold text-slate-400 uppercase">Education & Others</span>
                <p class="text-xl font-bold text-teal-600 mt-1">1,69,485 ৳</p>
            </div>
        </div>

        <!-- Two Columns Layout for Loan & Sub-summaries -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            
            <!-- Loan Details Table -->
            <div class="md:col-span-2 bg-white p-5 rounded-2xl shadow-sm border border-slate-200">
                <div class="flex justify-between items-center mb-4 border-b pb-3">
                    <h3 class="font-bold text-lg text-rose-600 flex items-center gap-2">
                        <span>🔴 ঋণ ও ধারের বিবরণ (Loan Details)</span>
                    </h3>
                    <span class="bg-rose-50 text-rose-700 text-xs font-bold px-2.5 py-1 rounded-full">Total Loan: 7,930 ৳</span>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-sm border-collapse">
                        <thead>
                            <tr class="bg-slate-50 text-slate-600 text-xs uppercase">
                                <th class="p-3 rounded-l-lg">নাম (Name)</th>
                                <th class="p-3">তারিখ (Date)</th>
                                <th class="p-3">পরিমাণ (Amount)</th>
                                <th class="p-3 rounded-r-lg">মন্তব্য (Remarks)</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-100">
                            <tr class="hover:bg-slate-50">
                                <td class="p-3 font-semibold text-slate-700">Sohan Shekh</td>
                                <td class="p-3 text-slate-500">5 Jan-2026</td>
                                <td class="p-3 font-bold text-rose-600">2,000 ৳</td>
                                <td class="p-3 text-slate-500 text-xs">5000-3000</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-3 font-semibold text-slate-700">Maruf Hossain</td>
                                <td class="p-3 text-slate-500">12 May-2026</td>
                                <td class="p-3 font-bold text-rose-600">130 ৳</td>
                                <td class="p-3 text-slate-500 text-xs">Mobil Load</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-3 font-semibold text-slate-700">Abdullah Arafat</td>
                                <td class="p-3 text-slate-500">12 May-2026</td>
                                <td class="p-3 font-bold text-rose-600">300 ৳</td>
                                <td class="p-3 text-slate-500 text-xs">bkas</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-3 font-semibold text-slate-700">Sohanur</td>
                                <td class="p-3 text-slate-500">25 Aug-2026</td>
                                <td class="p-3 font-bold text-rose-600">1,500 ৳</td>
                                <td class="p-3 text-slate-500 text-xs">others purpose</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-3 font-semibold text-slate-700">Riad</td>
                                <td class="p-3 text-slate-500">29 Aug-2026</td>
                                <td class="p-3 font-bold text-rose-600">2,000 ৳</td>
                                <td class="p-3 text-slate-500 text-xs">Wife Perpose</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-3 font-semibold text-slate-700">Khairul</td>
                                <td class="p-3 text-slate-500">18 Aug-2026</td>
                                <td class="p-3 font-bold text-rose-600">2,000 ৳</td>
                                <td class="p-3 text-slate-500 text-xs">Wife Perpose</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Quick Stats / Costing Overview -->
            <div class="bg-white p-5 rounded-2xl shadow-sm border border-slate-200 flex flex-col justify-between">
                <div>
                    <h3 class="font-bold text-lg text-slate-700 mb-4 border-b pb-3">📌 সারসংক্ষেপ (Overview)</h3>
                    <ul class="space-y-3 text-sm">
                        <li class="flex justify-between p-2 bg-slate-50 rounded-lg">
                            <span class="text-slate-500">Total Sent House:</span>
                            <span class="font-bold text-slate-700">3,79,500 ৳</span>
                        </li>
                        <li class="flex justify-between p-2 bg-slate-50 rounded-lg">
                            <span class="text-slate-500">Total Loan:</span>
                            <span class="font-bold text-rose-600">7,930 ৳</span>
                        </li>
                        <li class="flex justify-between p-2 bg-slate-50 rounded-lg">
                            <span class="text-slate-500">Total Others Costing:</span>
                            <span class="font-bold text-emerald-600">5,200 ৳</span>
                        </li>
                    </ul>
                </div>
                <div class="mt-4 pt-4 border-t text-center text-xs text-slate-400">
                    UG Security Services Limited (UGSSL)
                </div>
            </div>

        </div>

        <!-- Main Year-Month Table matching your sheet structure -->
        <div class="bg-white p-5 rounded-2xl shadow-sm border border-slate-200">
            <h3 class="font-bold text-lg text-slate-700 mb-4 border-b pb-3">📋 সাল ও মাসওয়ারি খরচ ও আয়ের বিবরণ (Year/Month Records)</h3>
            <div class="overflow-x-auto">
                <table class="w-full text-left border-collapse text-sm">
                    <thead>
                        <tr class="bg-blue-900 text-white text-center">
                            <th class="p-3 border-r border-blue-800">Year/Month</th>
                            <th class="p-3 border-r border-blue-800">2023</th>
                            <th class="p-3 border-r border-blue-800">2024</th>
                            <th class="p-3 border-r border-blue-800">2025</th>
                            <th class="p-3 border-r border-blue-800">2026</th>
                            <th class="p-3 border-r border-blue-800">2027</th>
                            <th class="p-3">2028</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-100 text-center">
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">January</td>
                            <td class="p-3">15,850</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">17,750</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">February</td>
                            <td class="p-3">15,850</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">March</td>
                            <td class="p-3">6,000</td>
                            <td class="p-3">15,850</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">April</td>
                            <td class="p-3">14,450</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">May</td>
                            <td class="p-3">14,450</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">June</td>
                            <td class="p-3">14,450</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">14,500</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">July</td>
                            <td class="p-3">14,450</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,535</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">August</td>
                            <td class="p-3">14,450</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">3,090</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                        <tr class="hover:bg-slate-50">
                            <td class="p-3 font-semibold text-slate-700 bg-slate-50 text-left">September</td>
                            <td class="p-3">14,450</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3">15,750</td>
                            <td class="p-3 font-bold text-blue-600">2,110</td>
                            <td class="p-3">-</td>
                            <td class="p-3">-</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

    </div>

</body>
</html>
