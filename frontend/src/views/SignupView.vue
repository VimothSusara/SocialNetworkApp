<template>
    <div class="max-w-lg mx-auto py-5 px-9 bg-white border border-gray-200 rounded-lg shadow-lg">
        <h1 class="text-center text-4xl font-semibold mb-3 text-purple-900">Signup</h1>

        <form class="space-y-2">
            <div>
                <label class="text-lg font-normal">Name</label>
                <input type="text" placeholder="Enter your name"
                    class="w-full mt-1 py-2 border border-gray-200 rounded-lg pl-2 text-md">
            </div>
            <div>
                <label class="text-lg font-normal">Email</label>
                <input type="email" placeholder="Enter your email"
                    class="w-full mt-1 py-2 border border-gray-200 rounded-lg pl-2 text-md">
            </div>
            <div>
                <label class="text-lg font-normal">Password</label>
                <input type="password" placeholder="Enter your password"
                    class="w-full mt-1 py-2 border border-gray-200 rounded-lg pl-2 text-md">
            </div>
            <div>
                <label class="text-lg font-normal">Repeat Password</label>
                <input type="password" placeholder="Repeat your password"
                    class="w-full mt-1 py-2 border border-gray-200 rounded-lg pl-2 text-md">
            </div>

            <div class="flex justify-center">
                <button class="py-2 px-5 bg-purple-600 text-white rounded-xl text-xl mt-2">Signup</button>
            </div>

            <p class="font-medium text-center text-xl">
                Already have an account? <RouterLink to="/login" class="text-purple-800">Login</RouterLink>
            </p>
        </form>
    </div>
</template>