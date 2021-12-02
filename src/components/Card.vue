<template>
    <div class="w-full bg-white rounded-2xl shadow-md overflow-hidden">
        <div class="w-full overflow-hidden" id="banner">
            <img class="object-cover min-h-100 w-full hover:scale-110 transition-transform duration-300 ease-in-out" src="../assets/banner.png" alt="banner">
        </div>
        <div id="content" class="px-[25px] py-[16px]">
            <div id="header">
                <h5 class="font-bold text-[24px] text-primary">Bahasa Indonesia</h5>
                <p class="text-gray-400 text-[16px] mt-[6px]">Kelas | Sekolah Dasar</p>
            </div>
            <div id="profile" class="flex mt-[32px] self-center">
                <div class="rounded-full w-[59px] overflow-hidden mr-[15px]">
                    <img class="object-cover" src="../assets/profile.png" alt="profile">
                </div>
            <div>
                <h5 class="font-medium text-[20px]">Cici Sang Putri</h5>
                <p class="text-gray-400 text-[16px]">Kelas | Sekolah Dasar</p>
            </div>
            </div>
                <div id="footer" class="flex justify-between items-center mt-[38px]">
                <span class="text-xl font-bold text-primary">Rp.90.000</span>
                <button class="py-[8px] px-[16px] rounded-lg ring-[2px] font-medium ring-blue-900 text-blue-900 hover:text-white hover:bg-blue-900 transition-all duration-200 ease-in-out">Lihat Kelas</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Card"
}
</script>