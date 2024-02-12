<template>
    <div class="max-w-lg mx-auto p-11 bg-white border border-gray-200 rounded-lg shadow-lg">
        <h1 class="text-center text-4xl font-semibold mb-5 text-purple-900">Login</h1>

        <form class="space-y-6">
            <div>
                <label class="text-xl font-normal">Email</label>
                <input type="email" placeholder="Enter your email"
                    class="w-full mt-2 py-3 border border-gray-200 rounded-lg pl-2 text-lg">
            </div>
            <div>
                <label class="text-xl font-normal">Password</label>
                <input type="password" placeholder="Enter your password"
                    class="w-full mt-2 py-3 border border-gray-200 rounded-lg pl-2 mb-1 text-lg">
            </div>

            <div class="flex justify-center">
                <button class="py-2 px-5 bg-purple-600 text-white rounded-xl text-xl">Login</button>
            </div>

            <p class="font-medium text-center text-xl">
                Do not have an account? <RouterLink to="/signup" class="text-purple-800">Register Now</RouterLink>
            </p>
        </form>
    </div>
</template>