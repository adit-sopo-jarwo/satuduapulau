# satuduapulau

"dev": [ "Composer\\Config::disableProcessTimeout", "npx concurrently -c \"#93c5fd,#c4b5fd,#fdba74\" \"php artisan serve\" \"php artisan queue:listen --tries=1\" \"npm run dev\" --names='server,queue,vite'" ]


tambahkan di composer.json bagian script biar kalo misal pake laravel tailwind langsung sekali panggil pake composer run dev gak perlu php artisan serve dan npm run dev
