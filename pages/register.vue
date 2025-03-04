<template>
  <div class="bg-black h-screen flex text-white">
    <!-- sidebar -->
    <div class="bg-zinc-900 w-[516px] p-12 flex flex-col justify-center">
      <RegisterLogo />
      <h1 class="font-bold text-lg mt-8">Sign up for a free account</h1>
      <p class="text-zinc-300 text-sm mt-0.5">
        Already registered?
        <span class="text-indigo-400 font-bold underline">Log in</span>
        to your account
      </p>

      <!-- email address -->
      <div class="mt-8">
        <label for="" class="text-zinc-300 text-sm font-medium block mb-1"
          >Email Address</label
        >
        <input
          type="email"
          placeholder="me@example.com"
          class="block w-full bg-zinc-700 border border-gray-500 rounded p-1 placeholder:text-zinc-400 text-sm"
        />
      </div>
      <!-- end of email address -->

      <!-- password -->
      <div class="mt-6">
        <label for="" class="text-zinc-300 text-sm font-medium block mb-1"
          >Password</label
        >
        <input
          type="password"
          placeholder="**************"
          class="block w-full bg-zinc-700 border border-gray-500 rounded p-1 placeholder:text-zinc-400 text-sm"
        />
      </div>
      <!-- end of password -->

      <div>
        <button
          class="w-full mt-8 bg-indigo-500 rounded-full px-4 py-2 text-sm font-bold cursor-pointer"
        >
          Sign Up
        </button>
      </div>
    </div>
    <!-- end of sidebar -->
    <!-- quicknote introduction  -->
    <div></div>
    <!-- end of quicknote introduction -->
  </div>
</template>
