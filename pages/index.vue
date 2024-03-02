<template>
    <div class="flex items-start max-lg:flex-col gap-20 md:gap-24 xl:gap-28">
        <div class="flex flex-col gap-7 md:gap-10 xl:gap-12 lg:w-3/5 max-lg:items-center max-lg:text-center">
            <div class="flex flex-col gap-3 md:gap-4 xl:gap-5 text-white">
                <div class="flex items-center gap-1.5 px-5 py-2.5 bg-[#262626] rounded-full text-xs md:text-sm xl:text-lg font-light z-[1]">
                    <img src="/images/welcome/icon.png" alt="">
                    <p>No LLC Required, No Credit Check.</p>
                </div>
                <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%]">
                    Welcome to FireBanK Empowering Your <span class="text-[#CAFF33]">Financial Journey</span>
                </p>
                <p class="text-white/90 -mt-1.5 text-xs md:text-sm xl:text-lg font-light leading-[150%]">At FireBanK, our mission is to provide comprehensive banking solutions that empower individuals and businesses to achieve their financial goals. We are committed to delivering personalized and innovative services that prioritize our customers' needs.</p>
            </div>
            <NuxtLink to="/" class="py-4 px-7 rounded-full bg-[#CAFF33] text-black text-xs md:text-sm xl:text-lg w-fit">Open Account</NuxtLink>
        </div>
        <img src="/images/welcome/change.png" alt="" class="lg:w-2/5">
    </div>
    <div class="flex flex-col gap-14 md:gap-20 xl:gap-24 text-white">
        <div class="flex flex-col gap-2 md:gap-2.5 xl:gap-3">
            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%]">Our <span class="text-[#CAFF33]">Products</span></p>
            <p class="text-xs md:text-sm xl:text-lg font-light text-[#B3B3B3] leading-[150%]">Discover a range of comprehensive and customizable banking products at FireBanK, designed to suit your unique financial needs and aspirations</p>
        </div>
        <div class="flex items-center max-lg:flex-col lg:justify-center gap-8 md:gap-10 xl:gap-12">
            <div class="flex flex-col gap-3 md:gap-4 xl:gap-5 items-center text-center">
                <img src="/images/products/1.png" alt="">
                <p class="mt-1.5 text-lg md:text-xl xl:text-2xl">Checking Accounts</p>
                <p class="text-xs md:text-sm xl:text-lg font-light text-[#B3B3B3] leading-[150%]">Enjoy easy and convenient access to your funds with our range of checking account options. Benefit from features such as online and mobile banking, debit cards, and free ATM access.</p>
            </div>
            <div class="max-md:w-[250px] max-lg:w-[500px] h-px lg:w-px lg:h-full bg-[#262626]"></div>
            <div class="flex flex-col gap-3 md:gap-4 xl:gap-5 items-center text-center">
                <img src="/images/products/2.png" alt="">
                <p class="mt-1.5 text-lg md:text-xl xl:text-2xl">Savings Accounts</p>
                <p class="text-xs md:text-sm xl:text-lg font-light text-[#B3B3B3] leading-[150%]">Build your savings with our competitive interest rates and flexible savings account options. Whether you're saving for a specific goal or want to grow your wealth over time, we have the right account for you.</p>
            </div>
            <div class="max-md:w-[250px] max-lg:w-[500px] h-px lg:w-px lg:h-full bg-[#262626]"></div>
            <div class="flex flex-col gap-3 md:gap-4 xl:gap-5 items-center text-center">
                <img src="/images/products/3.png" alt="">
                <p class="mt-1.5 text-lg md:text-xl xl:text-2xl">Loans and Mortgages</p>
                <p class="text-xs md:text-sm xl:text-lg font-light text-[#B3B3B3] leading-[150%]">Realize your dreams with our flexible loan and mortgage options. From personal loans to home mortgages, our experienced loan officers are here to guide you through the application process and help you secure the funds you need.</p>
            </div>
        </div>
    </div>
    <div class="flex flex-col gap-10 md:gap-14 xl:gap-20 text-white">
        <div class="flex flex-col gap-2 md:gap-2.5 xl:gap-3">
            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">Use Cases</p>
            <p class="text-xs md:text-sm xl:text-lg font-light text-[#B3B3B3] leading-[150%]">At FireBanK, we cater to the diverse needs of individuals and businesses alike, offering a wide range of financial solutions</p>
        </div>
        <div class="flex flex-col gap-10 md:gap-12 xl:gap-16">
            <div class="flex items-center max-lg:flex-col gap-7 md:gap-14 xl:gap-24">
                <div class="lg:w-[45%] rounded-xl p-5 md:p-10 xl:p-12 bg-[#1C1C1C] relative">
                    <img src="/images/cases/abstract1.png" alt="" class="absolute top-0 left-0 z-[0]">
                    <div class="grid grid-cols-2 gap-2.5 md:gap-3.5 xl:gap-5 text-sm md:text-base xl:text-xl leading-[150%]">
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/1.png" alt="">
                            <p>Managing Personal Finances</p>
                        </div>
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/2.png" alt="">
                            <p>Saving for the Future</p>
                        </div>
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/3.png" alt="">
                            <p>Homeownership</p>
                        </div>
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/4.png" alt="">
                            <p>Education Funding</p>
                        </div>
                    </div>
                </div>
                <div class="lg:w-[55%] flex flex-col gap-10 md:gap-12 xl:gap-14">
                    <div class="flex flex-col gap-2 md:gap-3 xl:gap-3.5">
                        <p class="text-xl md:text-2xl xl:text-3xl font-medium">For Individuals</p>
                        <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">For individuals, our mortgage services pave the way to homeownership, and our flexible personal loans provide vital support during various life milestones. We also prioritize retirement planning, ensuring a financially secure future for our customers</p>
                    </div>
                    <div class="flex items-center max-lg:flex-col gap-7 md:gap-10 xl:gap-12">
                        <div class="flex flex-col gap-1 max-lg:items-center max-lg:text-center">
                            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">78%</p>
                            <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Secure Retirement Planning</p>
                        </div>
                        <div class="max-md:w-[250px] max-lg:w-[500px] max-lg:border-b lg:h-[100px] lg:border-l border-dashed border-[#262626]"></div>
                        <div class="flex flex-col gap-1 max-lg:items-center max-lg:text-center">
                            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">63%</p>
                            <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Manageable Debt Consolidation</p>
                        </div>
                        <div class="max-md:w-[250px] max-lg:w-[500px] max-lg:border-b lg:h-[100px] lg:border-l border-dashed border-[#262626]"></div>
                        <div class="flex flex-col gap-1 max-lg:items-center max-lg:text-center">
                            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">91%</p>
                            <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Reducing financial burdens</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex items-center max-lg:flex-col gap-7 md:gap-14 xl:gap-24">
                <div class="lg:w-[45%] rounded-xl p-5 md:p-10 xl:p-12 bg-[#1C1C1C] lg:order-last relative">                    
                    <img src="/images/cases/abstract2.png" alt="" class="absolute top-0 right-0 z-[0]">
                    <div class="grid grid-cols-2 gap-2.5 md:gap-3.5 xl:gap-5 text-sm md:text-base xl:text-xl leading-[150%]">
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/5.png" alt="">
                            <p>Startups and Entrepreneurs</p>
                        </div>
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/6.png" alt="">
                            <p>Cash Flow Management</p>
                        </div>
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/7.png" alt="">
                            <p>Business Expansion</p>
                        </div>
                        <div class="rounded-lg flex flex-col items-center text-center gap-3.5 md:gap-5 xl:gap-6 bg-[#1A1A1A] p-3.5 md:p-6 xl:p-7 border border-[#262626] z-[1]">
                            <img src="/images/cases/8.png" alt="">
                            <p>Payment Solutions</p>
                        </div>
                    </div>
                </div>
                <div class="lg:w-[55%] flex flex-col gap-10 md:gap-12 xl:gap-14">
                    <div class="flex flex-col gap-2 md:gap-3 xl:gap-3.5">
                        <p class="text-xl md:text-2xl xl:text-3xl font-medium">For Business</p>
                        <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]"> For businesses, we empower growth with working capital solutions that optimize cash flow, and our tailored financing options fuel business expansion. Whatever your financial aspirations, YourBank is committed to providing the right tools and support to achieve them</p>
                    </div>
                    <div class="flex items-center max-lg:flex-col gap-7 md:gap-10 xl:gap-12">
                        <div class="flex flex-col gap-1 max-lg:items-center max-lg:text-center">
                            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">65%</p>
                            <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Cash Flow Management</p>
                        </div>
                        <div class="max-md:w-[250px] max-lg:w-[500px] max-lg:border-b lg:h-[100px] lg:border-l border-dashed border-[#262626]"></div>
                        <div class="flex flex-col gap-1 max-lg:items-center max-lg:text-center">
                            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">70%</p>
                            <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Drive Business Expansion</p>
                        </div>
                        <div class="max-md:w-[250px] max-lg:w-[500px] max-lg:border-b lg:h-[100px] lg:border-l border-dashed border-[#262626]"></div>
                        <div class="flex flex-col gap-1 max-lg:items-center max-lg:text-center">
                            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%] text-[#CAFF33]">45%</p>
                            <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Streamline payroll processing</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="flex flex-col gap-10 md:gap-14 xl:gap-20 text-white">
        <div class="flex flex-col gap-2 md:gap-2.5 xl:gap-3">
            <p class="text-2xl md:text-4xl xl:text-5xl font-medium leading-[150%]">Our <span class="text-[#CAFF33]">Features</span></p>
            <p class="text-xs md:text-sm xl:text-lg font-light text-[#B3B3B3] leading-[150%]">Experience a host of powerful features at YourBank, including seamless online banking, secure transactions, and personalized financial insights, all designed to enhance your banking experience</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-5 xl:gap-7">
            <div class="flex flex-col gap-5 xl:gap-7 rounded-xl p-7 md:p-10 xl:p-12 bg-[#1C1C1C] border border-[#262626]">
                <div class="flex items-center justify-between">
                    <p class="text-base md:text-lg xl:text-2xl">24/7 Account Access</p>
                    <img src="/images/features/icon.png" alt="">
                </div>
                <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Enjoy the convenience of accessing your accounts anytime, anywhere through our secure online banking platform. Check balances, transfer funds, and pay bills with ease.</p>
            </div>
            <div class="flex flex-col gap-5 xl:gap-7 rounded-xl p-7 md:p-10 xl:p-12 bg-[#1C1C1C] border border-[#262626]">
                <div class="flex items-center justify-between">
                    <p class="text-base md:text-lg xl:text-2xl">Mobile Banking App</p>
                    <img src="/images/features/icon.png" alt="">
                </div>
                <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Stay connected to your finances on the go with our user-friendly mobile banking app. Easily manage your accounts, deposit checks, and make payments from your smartphone or tablet.</p>
            </div>
            <div class="flex flex-col gap-5 xl:gap-7 rounded-xl p-7 md:p-10 xl:p-12 bg-[#1C1C1C] border border-[#262626]">
                <div class="flex items-center justify-between">
                    <p class="text-base md:text-lg xl:text-2xl">Secure Transactions</p>
                    <img src="/images/features/icon.png" alt="">
                </div>
                <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Rest assured knowing that your transactions are protected by industry-leading security measures. We employ encryption and multi-factor authentication to safeguard your financial information.</p>
            </div>
            <div class="flex flex-col gap-5 xl:gap-7 rounded-xl p-7 md:p-10 xl:p-12 bg-[#1C1C1C] border border-[#262626]">
                <div class="flex items-center justify-between">
                    <p class="text-base md:text-lg xl:text-2xl">Bill Pay and Transfers</p>
                    <img src="/images/features/icon.png" alt="">
                </div>
                <p class="text-sm md:text-base xl:text-lg leading-[150%] font-light text-[#B3B3B3]">Save time and avoid late fees with our convenient bill pay service. Set up recurring payments or make one-time transfers between your accounts with just a few clicks.</p>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>
